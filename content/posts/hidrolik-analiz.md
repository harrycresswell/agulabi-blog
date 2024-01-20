---
title: "Hidrolik Analiz"
subtitle: ""
date: 2015-05-02T21:36:00Z
lastmod: 2024-01-20T22:53:00Z
draft: false
author: "Abdullah Gulabi"
authorLink: ""
description: ""
license: ""
images: []

tags: ["Akışkanlar Mekaniği", "hidrolik analiz", "at nalı kesit", "horse shoe"]
categories: ["Mühendis Rehberi", "Excel Uygulamaları"]

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

Sizlerle teorik bir soruna pratik bir çözüm bulduğum "At nalı kesitler için hidrolik analiz" çalışmamı paylaşmak istiyorum. Bu çalışma İnşaat Mühendisliği lisans programı Akışkanlar Mekaniği dersi kapsamında [Prof. Dr. Sami Aköz](https://avesis.cu.edu.tr/msa/) hocamın yönlendirmesi ile yaptığım bir çalışma idi.
<!--more-->

At nalı kesitli bir borudaki serbest yüzeyli akımın debi, hidrolik yarıçap, ıslak çeper oranlarının abaklaştırılması konusunda hocamız çalışmamızı istedi.

At nalı kesitini tanımlayan eğri altında kalan için integral alındığnda sonuca ulaşmak mümkün oldu. Çalışmayı hocamıza sunduğumda ise istenen at nalı kesitin, standart at nalı kesit dışında özel bir at nalı kesiti olduğunu anladım.

Bu durumda çok daha karmaşık tanıma sahip eğrilerin taradığı alanın integralini almak veya alternatif bir çözüm sunmak gerekecekti.

Ben ise şöyle bir yöntem izledim.

AutoCAD ile karmaşık geometriyi istediğim eksene dik olacak şekilde çokça dilime ayırdım.
Bu dilimlerin tümünü tek seferde seçerek, <<Hatch>> komutu ile her birini ayrı olarak bölge haline getirdim.
LISP ile basit bir kod kullanarak alanları hızlıca topladım.
