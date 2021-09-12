---
title: "Koin Uygulaması"
date: 2017-09-02
tags: ["fikrin hayatı","girişimcilik","koin","göksel köksal","mobil uygulama"]
slug: "koin-uygulamasi-fikrin-hayati-roportaji-goksel-koksal"
summary: Döviz kuru çevirici uygulaması.
author: "Abdullah Şahin"
cover:
    image: "koin-uygulamasi-fikrin-hayati-roportaji-goksel-koksal.jpg"
    alt: "koin uygulaması fikrin hayatı röportajı göksel koksal"
    caption: "<text>"
    relative: false # To use relative path for cover image, used in hugo Page-bundles
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "Döviz kuru çevirici uygulaması."
disableShare: false
disableHLJS: false
searchHidden: true
---

### Bize kendinizden bahsedebilir misiniz? Kimsiniz, ne yapıyorsunuz?

Merhaba ben Göksel. Yazılım geliştiriciyim ve 5 senedir iOS platformunda geliştirme yapıyorum. Çalıştığım şirketi ilk 1 sene ikna etmek zor olsa da çıktığı günden beri Swift yazıyorum. Yazılım mimarisi ve temiz kod konusunda [yazmayı severim](https://medium.com/@gokselkoksal). Bilkent Üniversitesi Bilgisayar Mühendisliği mezunuyum. Ankara’da Mobil Atölye ve İstanbul’da Monitise’da (eski Pozitron'da) çalıştıktan sonra 6 ay önce evlenerek Dublin’e taşındım ve Verizon’da çalışmaya başladım.

### Fikrinizden bahsedebilir misiniz?

Bizim fikrimiz basit bir döviz kuru çevirici. İsmi [Koin](https://itunes.apple.com/us/app/koin-simple-currency-converter/id1057039641), hemen şu an App Store’dan indirebilirsiniz. İnanılmaz yenilikçiyiz gibi bir iddiamız kesinlikle yok. Mütevazi ve ufak ama bir o kadar da güzel gözüken ve kullanışlı bir uygulama yapmaktı amacımız. Bunu da başardığımızı düşünüyorum. Kısaca; Koin ile çok kullandığınız döviz kurları arasında hızlıca çeviri yapabiliyorsunuz. Kur değerleri saatlik olarak güncelleniyor ve cihazınızda saklanıyor. Bu sayede yurtdışında internet paketinizin olmadığı bir ortamda bile saklanmış en güncel değerlere göre döviz çevirisi yapabiliyorsunuz. Hedef kitlemiz de çok seyahat ve alışveriş eden, farklı kurlarla ile uğraşan insanlar tabi ki.

Kendi sosyal ağlarımızda paylaşmak dışında bir marketing aktivitemiz olmadı. Aşağı yukarı 2 sene içerisinde 6300 indirilme aldık. Henüz 5 yıldız dışında bir değerlendirme aldığımız olmadı markette. (Hayır, hepsi tanıdık değil.)

### Fikri kaç kişi ile birlikte geliştirdiniz ve kimler hangi pozisyonda yer aldı?

Tasarımı [Ebru](https://dribbble.com/ebruhu), geliştirmeyi ben yaptım. Ebru benim ilkokul arkadaşım. Lise ve üniversiteyi aynı yerlerde okuyamasak da son 6 aya kadar aynı şirketlerde çalışıyorduk. Şu anda da eski şirketim olan Monitise'da tasarımcı olarak çalışmaya devam ediyor.

### Fikrin planını nasıl yaptınız, bitiş tarihlerini belirlerken nelere dikkat ettiniz? Bitiş tarihleri nelerdi?

Bir akşam Ebru ile yemek yerken ufak uygulamalar geliştirip milyoner olmak istediğimi söyledim. Ona da mantıklı gelince…

Milyoner kısmı hariç gerçekten bu şekilde oldu. O anda aklımda önceden bir kaç sayfasını çizdiğim bir döviz çevirici vardı. Başlangıç için güzel olacağını düşündük ve başladık. Hatırladığım kadarıyla 3-4 ay sürede bitirebileceğimizi öngörmüştük ama herhangi bir bitiş tarihi belirlemedik. Ürün geliştirme yaşayan bir süreç olduğu için daha kısa vadeli hedefler koymayı tercih ettik.

### Fikrinizde görev takibi ve görev paylaşımı için hangi servisleri veya araçları kullandınız?

Tüm projeyi Trello, Dropbox ve Telegram üzerinden yürüttük diyebilirim.

### Fikrin tasarım/geliştirme sürecinde hangi araçları/kütüphaneleri kullandınız ve nasıl bir süreç izlediniz?

Döviz kurları için [currencylayer](http://www.currencylayer.com).

Tasarım için [Sketch](https://www.sketchapp.com/).

Geliştirme içinse tabi ki Xcode ve Swift.

Kullandığım kütüphaneler:
* [Alamofire](https://github.com/Alamofire/Alamofire)
* [SwiftyJSON](https://github.com/SwiftyJSON/SwiftyJSON)
* [DateTools](https://github.com/MatthewYork/DateTools)
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout)
* [GKValidator :)](https://github.com/gokselkoksal/GKValidator)
* [iRate](https://github.com/nicklockwood/iRate)
* pop
* [PromiseKit](https://github.com/mxcl/PromiseKit)
* Realm

Dışardan kullandığım kütüphaneler konusunda biraz hassasım. Birşeyi kendim yazmak bana çok zaman kaybettirmeyecekse genellikle kendim yazmayı tercih ediyorum. Her kütüphane kendi kısıtları ile beraber geliyor ve genellikle sadece ufak bir kısmı kullanılıyor. Xcode ve Swift versiyon değişikliklerinde kütüphanenin güncellenmeme ihtimali de tam bir kabus. Bu nedenle “gerçekten” ihtiyacım olduğuna inanmam gerekiyor eklemeden önce. Paylaştığım liste uzun gibi gözükse de hepsi bu değerlendirmeden geçmiş kütüphaneler.

### Fikri geliştirirken ve tasarlarken karşılaştığınız en büyük zorluk ne oldu?

Tam zamanlı bir işte çalışıyorsanız akşam eve gelip uzanmak, Dota oynamak, film seyretmek çok tatlı geliyor. En çok zorlandığımız nokta bu fiziksel yorgunluğa rağmen motivasyon bulabilmek olmuştur herhalde. Yaptığınız üründen keyif almıyorsanız bu çok mümkün değil bence.

Bir de ben tasarım konusunda biraz hassas bir adamım. Ebru’ya biraz bela olmuş olabilirim bu süreçte. :) Karşınızdaki ile doğru iletişim kurabildikten sonra zor beğenmek bence bir artı bir haline geliyor. Ebru övgüyü seven ama aynı zamanda geri bildirimi de güzel göğüsleyen bir tasarımcı. Bu nedenle sonunda hep ikimizin de içine sinen tasarıma ulaşabildik.

### Bu fikir aracılığı ile gelecekte hayata geçireceğiniz fikirleriniz için neler öğrendiniz? Edindiğiniz tecrübeler neler oldu?

Uygulamayı markete göndermeden önce bir “analytics” ürünü entegre etmediğim için baya pişmanım. Bu çok önemli ama beni çok sıkan ve yapmak istemediğim birşeydi zamanında.

Yeterli populariteniz ve “marketing” ağınız yoksa ağzınızla kuş da tutsanız parayla uygulama satamıyorsunuz. Bu tarz ufak uygulamalarda en fazla reklam veya “in-app purchase” gidebileceğini öğrendim.

### Bu tarz projeler geliştirmek ve yer almak isteyen kişiler için neler tavsiye edersiniz?

Şu ana kadar markete herhangi bir uygulama koymadıysanız bu iş gözünüzde büyümesin. Çok ufak da olsa sizi heyecanlandıran bir fikriniz varsa hayata geçirin. En fazla 6 ay sonra markette bir uygulamanız olur ve en azından tecrübe edinmiş olursunuz. Kimse beğenmezse CV’nize yazarsınız. “Bizde tasarımcı arkadaş yok ama” diyorsanız da pintilik yapmayın, freelance çalışan biriyle anlaşın. Düşündüğünüz kadar büyük paralar ödemezsiniz.

### Fikrinizin sürecini adım adım özetleyebilir misiniz? (Bonus Soru)

* Örnekleme (Prototyping): Bu kısım çok önemli. Ürünün kullanılabilirliğini test etmek için sadece bir kağıda ihtiyacınız var. Telefon büyüklüğünde birkaç kağıda aklınızdakini çizin ve test edin. Mesela: [Travellr Paper Prototype](https://www.youtube.com/watch?v=_5FGeSQ7DBU)
* Tasarım <-> Geri Bildirim
* Geliştirme <-> Kullanıcı Testi (Tasarım Güncelleme)
* Market!
