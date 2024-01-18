---
title: "Salgın ve Veri Gizliliği"
subtitle: ""
date: 2020-03-20T21:54:09Z
lastmod: 2024-01-18T23:39:09Z
draft: false
author: "Abdullah Gulabi"
authorLink: ""
description: ""
license: ""
images: []

tags: ["privacy", "Covid", "gizlilik", "privacy"]
categories: [Blog]

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
> 2020 yılının başında, Covid-19 salgını başlangıcında ülkelerin salgınla mücadele kapsamında devreye aldıkları uygulamarı veri gizliliği açısından değerlendirdiğim makale.

> Article from early 2020, My evaluation on the responses of various countries' Covid-19 responses and their data privacy implications.

Pandemi haline gelen Covid-19 salgını ve buna karşı alınan önlemler ülkeden ülkeye farklılık gösteriyor. Kimi ülke yayılmayı durdurmayı başarabildi, kimisi de durdurmaya yaklaşıyor ancak çoğu ülke için mücadele daha yeni başlıyor.

Birey ve toplum düzeyinde can güvenliğimizin derdine düştüğümüz bu dönemde verilerimizin gizliliği ne durumda?

Hatırlayacağımız üzere geçmişte terör tehditleri ile karşılaşan toplumlar, güvenlik gerekçesi ile pek çok veriye erişim, izleme ve takip yasalarına rıza gösterdi.

Şimdi bir virüs tehdidi söz konusu ve gizlilik konusundaki benzerlikler dikkatimi çekiyor.

Kaynakları en altta liste halinde sundum.

### Çin

Devreye aldığı katı önlemler ve kurallar ile Çin akıntıyı tersine çevirmiş durumda.

Çin’deki vakalar merkezi sistem üzerinden kayıt altına alınıyor. Bu veriyi yüz tanıma teknolojisi ile birleştirerek insanları ve özellikle de şüpheli veya hastalık taşıyan kişileri gerçek zamanlı takip ederek, sokağa çıkma yasağını ihlal edenler tespit edildi, insanların hareketleri kısıtlandı ve düzenlendi [1](https://www.geospatialworld.net/blogs/how-china-is-using-technology-to-fight-coronavirus/)

### Kore Cumhuriyeti

Olabildiğinde çok test yaparak Güney Kore (Kore Cumhuriyeti) hem vakaların tespitinde başarılı oldu, hemde elindeki verileri kullanarak insanlara etraflarında bilinen vaka konumlarını ve hareketlerini bildirdi.

Cep telefonu sinyalleri, konum bilgileri, kredi kartı hareketleri, güvenlik kamerası kayıtları kullanılan veriler arasında.

Böylelikle insanlar bilinen vaka olan konumlara gitmeyerek, yayılmanın önü alınmaya çalışıldı [2](https://www.washingtonpost.com/world/asia_pacific/coronavirus-south-korea-tracking-apps/2020/03/13/2bed568e-5fac-11ea-ac50-18701e14e06d_story.html).

### İsrail

İsrail hükümeti, emniyet gücü Shin Bet’e ülkedeki tüm cep telefonu bilgilerine erişim izni verdi ve şüpheli veya kesinleşmiş Covid-19 hastalarının yakınlarında bulunan kişilere “Merhaba, koronavirus hastası birinin yakınlarında bulundunuz, derhal kendinizi 14 gün…” şeklinde SMS mesajları iletilmeye başlandı [3](https://www.npr.org/2020/03/19/818327945/israel-begins-tracking-and-texting-those-possibly-exposed-to-the-coronavirus).

### ABD

Koronavirüs vaka sayısının artması ile aynı tarihlerde, EARN IT olarak bilinen bir yasa tasarısı gündeme geldi. Bu yasa ile tüm şifreli iletişim teknolojilerine, yetkili mercilere erişim verme zorunluluğu getirilmek isteniyor. [4](https://cyberlaw.stanford.edu/blog/2020/01/earn-it-act-how-ban-end-end-encryption-without-actually-banning-it)

ABD’de ve dünyada vaka sayısının tırmanmaya devam etmesi ile birlikte, ABD hükümetinin Silikon Vadisi şirketleri ile vatandaşlarının konum bilgilerini kullanarak virüs ile daha etkin mücadele etme yöntemlerini araştırdığı da haberler arasında.

Bir diğer husus ise, yabancı devletlerin ABD’den, Silikon Vadisi firmalarının topladığı veriler üzerinden kendi vatandaşlarının bilgilerine erişmek için başvuruda bulunmuş olması… [5](https://edition.cnn.com/2020/03/18/tech/us-government-location-data-coronavirus/index.html).

### Avrupa Birliği

Avrupa Birliği GDPR’ın kamu sağlığı sebebiyle veriye erişime engel olmadığını ancak veri işleyicisinin sorumluluklarını hatırlatan “Covid-19 salgını kapsamında kişisel verilerin işlenmesine ilişkin duyuru” metnini 19 Mart 2020 tarihinde yayınladı [6](https://edpb.europa.eu/news/news/2020/statement-edpb-chair-processing-personal-data-context-covid-19-outbreak_en).

Avusturya ve Almanya’da telekom operatörleri GDPR uyumu içinde anonimleştirilmiş verileri hükümetin erişimine açarak salgın takibine imkan sağlamış oldular [7](https://www.tagesspiegel.de/wissen/wie-breitet-sich-das-coronavirus-aus-rki-bekommt-handydaten-von-deutscher-telekom/25655144.html).

### Türkiye

Ülkemizde alınan önlemler, bilinç düzeyi ve kaygılar giderek artarken bu konuların daha çok gündeme alınacağı aşikar. CİMER üzerinden yapılan başvurular henüz şuan vaka ihbarından ziyade piyasa fırsatçıları konularında.

Sağlık Bakanlığı’nın e-Nabız uygulaması ile bir çözüm olabilir mi? Kan şekeri, hareket ve konum, sağlık geçmişi, nabız verilerine erişebilen bir uygulama. Ateş ölçümü veya semptom takibinde kitlesel katılım ile bir salgın önleme aracı haline dönüşebilir mi?

Belki de dünyada gördüğümüz diğer yaklaşımlara benzer bir uygulama ile karşılaşırız?

Sizlerin görüş ve yorumlarını merak ediyorum.

\#evdekal Türkiye.