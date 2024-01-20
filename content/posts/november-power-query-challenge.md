---
title: "November Power Query Challenge"
subtitle: ""
date: 2021-12-01T19:16:02Z
lastmod: 2024-01-20T14:11:02Z
draft: false
author: "Abdullah Gulabi"
authorLink: ""
description: ""
license: ""
images: []

tags: ["Power Query", "Excel"]
categories: ["Blog", "Excel Uygulamaları"]

featuredImage: ""
featuredImagePreview: ""

hiddenFromHomePage: false
hiddenFromSearch: false
twemoji: false
lightgallery: true
ruby: true
fraction: true
fontawesome: true
linkToMarkdown: false
rssFullText: false

toc:
  enable: true
  auto: true
code:
  copy: true
  maxShownLines: 50
math:
  enable: false
  # ...
mapbox:
  # ...
share:
  enable: true
  # ...
comment:
  enable: true
  # ...
library:
  css:
    # someCSS = "some.css"
    # located in "assets/"
    # Or
    # someCSS = "https://cdn.example.com/some.css"
  js:
    # someJS = "some.js"
    # located in "assets/"
    # Or
    # someJS = "https://cdn.example.com/some.js"
seo:
  images: []
  # ...
---

I came across [Access Analytic](https://accessanalytic.com.au)'s [November 2021 Power Query Challenge](https://accessanalytic.com.au/november-power-query-challenge/#) on [Wyn Hopkins' LinkedIn](https://www.linkedin.com/in/wynhopkins/) feed.
<!--more-->

Here's the file with my PQ answer.

What I found intriguing about this challange was that at first glance, it appeared something that would benefit from a few rounds of unpivoting and transposing - [Leila Gharani has an excellent video](https://www.youtube.com/watch?v=QbRgeskSn0U) on the subject.

But then in the spirit of challanges, I decided to challange myself not to transpose the data. 

I also used #date within #date with Date.Daysinmonth to achieve the result.

Happy spreadsheeting and power query-ing!

The M-code is printed below for your convenience:

>	let
>    Source = Excel.CurrentWorkbook(){[Name="Table1"]}[Content],
>    #"Removed Bottom Rows" = Table.RemoveLastN(Source,1),
>    #"Unpivoted Columns" = Table.UnpivotOtherColumns(#"Removed Bottom Rows", {"Column1", "Column2"}, "Attribute", "Value"),
>    #"Added Custom" = Table.AddColumn(#"Unpivoted Columns", "Element", each if [Attribute]="Finance" or [Attribute]="Operations" or [Attribute]= "HR" then "Actual" else if [Attribute]="Column3" or [Attribute]="Column5" or [Attribute]="Column7" then "Budget" else "Variance"), 
>    #"Added Custom1" = Table.AddColumn(#"Added Custom", "Department", each if Text.Contains ([Attribute], "Column") then null else [Attribute]),
>    #"Filled Down" = Table.FillDown(#"Added Custom1",{"Department"}),
>    #"Removed Columns" = Table.RemoveColumns(#"Filled Down",{"Attribute"}),
>    #"Split Column by Character Transition" = Table.SplitColumn(#"Removed Columns", "Column2", Splitter.SplitTextByCharacterTransition((c) => not List.Contains({"0".."9"}, c), {"0".."9"}), {"Column2.1", "Column2.2"}),
>    #"Renamed Columns" = Table.RenameColumns(#"Split Column by Character Transition",{{"Column2.1", "Case"}, {"Column2.2", "Year"}, {"Column1", "Month"}}),
>    #"Removed Top Rows" = Table.Skip(#"Renamed Columns",9),
>    #"Replaced Value" = Table.ReplaceValue(#"Removed Top Rows","Case"," Case",Replacer.ReplaceText,{"Case"}),
>    #"Changed Type" = Table.TransformColumnTypes(#"Replaced Value",{{"Year", Int64.Type}, {"Month", Int64.Type}}),
>    #"Added Custom2" = Table.AddColumn(#"Changed Type", "Date", each #date([Year], [Month], Date.DaysInMonth (#date([Year], [Month],1)))),
>    #"Removed Columns1" = Table.RemoveColumns(#"Added Custom2",{"Month", "Year"}),
>    #"Pivoted Column" = Table.Pivot(#"Removed Columns1", List.Distinct(#"Removed Columns1"[Case]), "Case", "Value", List.Sum),
>    #"Filtered Rows" = Table.SelectRows(#"Pivoted Column", each ([Element] <> "Variance")),
>    #"Reordered Columns" = Table.ReorderColumns(#"Filtered Rows",{"Department", "Element", "Date", "Base Case", "Worst Case"}) 
>    in
>    #"Reordered Columns"
    
Feel free to download the challange file with my solution below:

[PQ-November-2021-Challenge-2.xlsx](PQ-November-2021-Challenge-2.xlsx)

Cheers,

Abdullah.