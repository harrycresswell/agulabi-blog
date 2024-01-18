---
title: "Tech Without Big Tech"
subtitle: "An amateur's guide to losing the big-tech."
date: 2021-11-26T22:35:10Z
lastmod: 2021-11-26T22:35:10Z
draft: false
author: "Abdullah Gulabi"
authorLink: ""
description: ""
license: ""
images: []

tags: ["privacy", "surveillance", "tech", "data sovereignty"]
categories: ["articles"]

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

<!--more-->
I believe in sharing data, information and knowledge, but not private data. This is an outline of my solution to keeping the tech in my life while keeping big tech out.

The table below is a good summary of the entire post, scroll down for details and links for each. This post is more about how, and less about why.
<!--more-->
The surprisingly low cost of all these is at the end bit (spoiler: about  64 GBP or 86 USD per year).

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-sltr{background-color:#4472C4;color:#FFF;font-weight:bold;text-align:left;vertical-align:bottom}
.tg .tg-y4z7{background-color:#4472C4;color:#FFF;font-weight:bold;text-align:center;vertical-align:bottom}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-y4z7"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">#</span></th>
    <th class="tg-y4z7"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">For…</span></th>
    <th class="tg-sltr"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">I chose…</span></th>
    <th class="tg-sltr"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">To replace…</span></th>
    <th class="tg-sltr"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">Because…</span></th>
    <th class="tg-sltr"><span style="font-weight:700;text-decoration:none;color:white;background-color:#4472C4">Alternatives are…</span></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">1</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Passwords</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Bitwarden</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Google/Apple Password&nbsp;&nbsp;&nbsp;Manager</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Allows zero-knowledge&nbsp;&nbsp;&nbsp;password sync across devices.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">LessPass</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">2</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">E-mail</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Self hosting</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Gmail</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Hestia Control Panel&nbsp;&nbsp;&nbsp;handles everything (email and web server)</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Tutanota,&nbsp;&nbsp;&nbsp;ProtonMail - both zero-knowledge and encrypted</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">3</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Mobile Device</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">GrapheneOS or /e/ OS&nbsp;&nbsp;&nbsp;on supported devices</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Android OS</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">No data leaves my&nbsp;&nbsp;&nbsp;device except by explicit instruction.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">LineageOS,&nbsp;&nbsp;&nbsp;CalyxOS</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">4</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">App Store</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">F-Droid, </span><br><span style="font-weight:400;text-decoration:none;color:black">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Aurora Store</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Play Store</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">F-Droid allows access&nbsp;&nbsp;&nbsp;to privacy friendly apps. Aurora allows anonymous access to Play Store&nbsp;&nbsp;&nbsp;catalogue</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Avoid&nbsp;&nbsp;&nbsp;untrusted sources</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">5</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Navigation</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">OSMAnd+</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Google Maps</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Open source client&nbsp;&nbsp;&nbsp;accessing Open Street Maps</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Magic&nbsp;&nbsp;&nbsp;Earth</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">6</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Files &amp;&nbsp;&nbsp;&nbsp;Collaboration</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Nextcloud </span><br><span style="font-weight:400;text-decoration:none;color:black">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+ Collabora Online </span><br><span style="font-weight:400;text-decoration:none;color:black">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+ apps</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Google Drive,&nbsp;&nbsp;&nbsp;gDocs/sheets, OneDrive, Office 365 Online</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">I host Nextcloud on a&nbsp;&nbsp;&nbsp;VPS. Allows sharing and editing online with others and much&nbsp;&nbsp;&nbsp;more.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Haven't&nbsp;&nbsp;&nbsp;searched further</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">7</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Location Sharing</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">PhoneTrack on&nbsp;&nbsp;&nbsp;Nextcloud</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Google Maps</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">For device location&nbsp;&nbsp;&nbsp;history and find my family kind of location sharing.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Hauk</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">8</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Photos Back-Up</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Nextcloud</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Google Photos, iCloud&nbsp;&nbsp;&nbsp;Photos</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Nextcloud can natively&nbsp;&nbsp;&nbsp;handle photo syncing as well as files etc. Further functionality for tagging,&nbsp;&nbsp;&nbsp;facial recognition can happen within your own Nextcloud.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">PhotoPrism</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">9</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Podcasts</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">AntennaPod</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Apple/Google Podcasts</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Open source app with&nbsp;&nbsp;&nbsp;no tracking involved.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Haven't&nbsp;&nbsp;&nbsp;searched further</span></td>
  </tr>
  <tr>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">10</span></td>
    <td class="tg-baqh"><span style="font-weight:400;text-decoration:none;color:black">Accessing&nbsp;&nbsp;&nbsp;YouTube</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">NewPipe&nbsp;&nbsp;&nbsp;(Android), </span><br><span style="font-weight:400;text-decoration:none;color:black">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FreeTube (Desktop), </span><br><span style="font-weight:400;text-decoration:none;color:black">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Invidious (web)</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">YouTube</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">Enjoy&nbsp;&nbsp;&nbsp;YouTube with least possible data being sent back. Save, bookmark, follow,&nbsp;&nbsp;&nbsp;read comments - no account needed.</span></td>
    <td class="tg-0lax"><span style="font-weight:400;text-decoration:none;color:black">SkyTube (Android)</span></td>
  </tr>
</tbody>
</table>

I intend this post to serve as my data ownership story. I hope to start a discussion with like minded people and hope to learn from you.
> This is an updated version of an article I published on [my website oriented for the Turkish speaking youth.](https://muhendisrehberi.com/kisisel-verileri-paylasmamak/)

# 0. Domain
[Cloudflare](https://www.cloudflare.com/products/registrar/) has an at-cost registrar service, meaning you can pay the absolute lowest fee possible to register and later renew a domain name. 

Owning a domain name will be crucial in owning your data. If you're aware of other alternatives boasting at-cost pricing let me know and I can include them in this list. 

I haven't included this in the table above as it really boils down to your decision, does not change anything for the subsequent items.

## 1. Passwords
Privacy is not possible without security and using unique and strong passwords is one of the single most effective steps to take in achieving security and privacy. 

[Bitwarden](https://bitwarden.com/) is an excellent [zero-knowledge](https://bitwarden.com/resources/zero-knowledge-encryption-white-paper/) open source password manager that can sync across devices. 

[LessPass](https://www.lesspass.com/#/) is a great alternative that does not even need to sync yet can be used across devices.

## 2. E-mail
E-mail is [not a secure form of communication and has its flaws](https://www.jdfoxmicro.com/resource-center/articles/email-is-insecure/#SkipSidebar). It is however universally used and is crucial for your web presence. Ensuring its at least a little bit safer should be a priority, even [FBI's e-mail server get hacked from time to time!](https://www.nbcnews.com/tech/security/hacker-takes-fbi-email-server-blasts-spam-thousands-rcna5530)!

I chose to set up a [VPS (Virtual Private Server)](https://www.ionos.co.uk/servers/vps#packages) with a [hosting company](https://www.ionos.co.uk/) running an open source operating system ([Ubuntu](https://ubuntu.com/download/desktop)). 

I then set up an open source control panel ([HestiaCP](https://www.hestiacp.com/)) to manage the web server. HestiaCP makes it a breeze to set up and manage web spaces and mail servers.

Hestia also allows for one-click installation of [WordPress](https://wordpress.org/), [Nextcloud](https://nextcloud.com/), [Grav](https://getgrav.org/), [Laravel](https://laravel.com/), [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki), [Opencart](https://www.opencart.com/), [Prestashop](https://www.prestashop.com/en), [Symfony](https://symfony.com/), [Dokuwiki](https://www.dokuwiki.org/dokuwiki), [Drupal](https://www.drupal.org/) websites. 

[iRedMail](https://www.iredmail.org/) can be great alternative if you're self hosting and do not need the additional features HestiaCP provides.

There are excellent zero-knowledge encrypted e-mail service providers like [Tutanota](https://tutanota.com) or [ProtonMail](https://protonmail.com/) if you wish to simply use secure and private e-mail, both offering free tiers.

## 3. Mobile Device
A privacy respecting mobile device is crucial in the whole set up. I decided to prioritize privacy and security above all and found [GrapheneOS](https://grapheneos.org/) to fit the bill. I then had to choose a mobile device that supports this flavour of Android as an operating system (OS).

Custom (and unGoogled) OS variants are more private as they offer absolute control over app's access to device data and features. No access is granted "by default", access is rather "by explicit consent" allowing you to prevent apps from connecting to networks, accessing storage or sensor data. [Here](https://www.forbes.com/sites/zakdoffman/2021/10/23/apple-iphone-users-delete-facebook-app-after-new-tracking-warning/) is a good example why this would be necessary.

Another excellent alternative with a much longer list of supported devices would be [/e/ OS](https://e.foundation/). It basically matches GrapheneOS in terms of privacy as [research](https://www.scss.tcd.ie/Doug.Leith/Android_privacy_report.pdf) has shown it not to send any data out.

Despite the privacy focused marketing push from Apple, iPhones are not any different in terms of [unwanted tracking by third parties despite the opt-out settings](https://www.washingtonpost.com/technology/2021/09/23/iphone-tracking/). 

I am still in search of a similar privacy friendly solution for a modern tablet device, please let me know if you have any recommendations!

## 4. App Store
The privacy respecting mobile device does not have ready access to the app stores we're accustomed to but there are excellent repositories full of open-source and privacy respecting apps, such as [F-Droid](https://f-droid.org/).

F-droid is a repository, works just other app stores with the main difference being that it contains only free and open source software.

[Aurora Store](https://auroraoss.com/download/AuroraStore/) is useful for cases where there are no open source alternatives to the apps in question, like your mobile banking app for instance. You can anonymously access the entire Google Play Store catalogue through Aurora Store.

## 5. Navigation
One of the best things about big-tech and Google in particular is seamless search and navigation. It is however possible to completely replace and surpass the functionality offered by the likes of Google or Apple Maps with open source alternatives.

[OSMAnd+](https://f-droid.org/en/packages/net.osmand.plus/) provides map and navigation with support for offline navigation, voice directions and more. A great alternative is [Magic Earth](https://www.magicearth.com/).

## 6. Files & Collaboration
Undoubtedly one of the ways big tech has spoiled us has been the always synced files accessible and editable on all devices. [Nextcloud](https://nextcloud.com/) allows for syncing of files and folders, handles contacts and calendar sync, allows for [collaborating](https://nextcloud.com/collaboraonline/) on files online and can be expanded functionally with additional [apps](https://apps.nextcloud.com/). 

Nextcloud is the backbone of the big-tech replacing solution.

## 7. Location Sharing
[PhoneTrack](https://apps.nextcloud.com/apps/phonetrack) is an app that runs within Nextcloud that basically replicates Apple's Find My or Google Location Sharing features. You can simply set it up with your devices to track them live, as well as collect location information from your devices over a longer term.

If you decide to go without Nextcloud, you can simply install [Hauk](https://github.com/bilde2910/Hauk) on your server for a single-purpose solution to live location sharing.

## 8. Photos Back-up
Having all your photos and videos synced up to the cloud is another one of big-tech's guilty pleasures - thankfully one that Nextcloud handles natively. You can further extend the functionality with apps, to include [facial recognition](https://apps.nextcloud.com/apps/facerecognition), [automatic tagging](https://apps.nextcloud.com/apps/recognize) of photos, [finding duplicates](https://apps.nextcloud.com/apps/duplicatefinder) and many more...

## 9. Podcasts
I'm a big fan of podcasts and [AntennaPod](https://antennapod.org/) is easily one of the best podcast apps I've come across. In addition to all the podcast related features to love, it is also open source and will respect your data.

I also love the feature where you can specify the app to treat any local folder as a channel. The folder can then be populated by any means and the contents will simply be recognized as episodes.

## 10. Accessing YouTube
Regardless of Google's anti-privacy deeds, YouTube remains the most popular video platform. [NewPipe](https://newpipe.net/) app on android allows accessing YouTube videos in the most privacy friendly way possible.

You can watch, download as video or audio, create and manage local playlists and view comments. Everything on the app except for fetching the video content happens locally, nothing gets sent back. 

[SkyTube](https://skytube-app.com/) is a good alternative with similar functionality and privacy approach.

[FreeTube](https://freetubeapp.io/) is a desktop client achieving the same functionality available on [Windows, Mac and Linux](https://freetubeapp.io/#download).

[Invidious](https://github.com/iv-org/invidious) is an alternative frontend to YouTube and you can simply access a public instance to use it through your browser.

# Further Reading
I'd also like to share some sources for anyone looking to do some further learning on the subject.

1. [Carissa Veliz](https://www.carissaveliz.com/)'s book [Privacy is Power](https://www.penguin.co.uk/books/1120394/privacy-is-power/9780552177719.html)
2. Michael Bazzel's book [Extreme Privacy](https://www.amazon.co.uk/dp/B094LDWKGZ) and podcast [The Privacy, Security, and OSINT Show](https://inteltechniques.com/podcast.html)
3. The podcast [Surveillance Report](https://surveillancereport.tech/) by [Techlore](https://techlore.tech/) & [The New Oil](https://thenewoil.org/)
4. Sven Taylor's [Restore Privacy](https://restoreprivacy.com/) web site
5. [Krebs on Security](https://krebsonsecurity.com/) blog
6. [Achimm Brinkmann's LinkedIn](https://www.linkedin.com/in/achim-brinkmann-790370/) feed
7. [Dr. Paul Patras](https://www.linkedin.com/in/paulpatras)' team's paper on [Android OS Snooping](https://www.scss.tcd.ie/doug.leith/Android_privacy_report.pdf).
8. [Lourdes M. Tourrecha](https://www.linkedin.com/in/lourdesmturrecha/) and [Emily Ashley](https://www.linkedin.com/in/emily-ashley-17a7a754/)'s whitepaper [Defining the Privacy Tech Landscape 2021](https://www.riseofprivacytech.com/wp-content/uploads/2021/11/TROPT-Defining-the-Privacy-Tech-Landscape-2021-v1.0-1.pdf)
9. [Debbie Reynolds](https://www.linkedin.com/in/debbieareynolds/)' [Data Diva](https://www.debbiereynoldsconsulting.com/podcast) Podcast 

## Costs
>When something online is free, you’re not the customer, you’re the product.

The quote finds its root [all the way back to 1950](http://blogs.harvard.edu/futureoftheinternet/2012/03/21/meme-patrol-when-something-online-is-free-youre-not-the-customer-youre-the-product/)'s. Doing away with the free services meant incurring some costs, but I am happy to report that they were much more modest than I've thought.

The FLOSS (Free Libre Open Source Software) are absolutely free, with the only cost items being the domain registration and hosting service.

I was able to find that Cloudflare Registrar offers at-cost registration and renewal fees at 8.57 USD per year for .com domains.

For hosting, IONOS came recommended by [Kev Quirk](https://kevq.uk/the-hunt-for-better-wordpress-hosting/) and I echo his recommendations, they have great customer support as well as a clear pricing and refund policy. 

I opted for the VPS S+ package at 58 GBP per annum including VAT.

# Conclusion
I would like this post to inspire others to pursue their data ownership journey and to share their findings. We need better ways to handle our personal data.

The steps shared above are a step in the right direction, they do not make your data secure. Further steps are needed like your choice of browsers, ISP, the information you volunteer to online services, controlling physical access to your digital devices and much more!

I embarked on this journey simply because it seems preposterous that any and all aspects of our digital life be kept in record, and forever, and waiting to be abused and used against ourselves at the first opportunity. 

I would like to conclude with a reminder that your data is a valuable resource and it would be wise to think about all the ways we've been handing it over to others without second thought.