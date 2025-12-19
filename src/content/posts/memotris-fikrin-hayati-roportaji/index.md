---
title: "Memotris"
meta_title: ""
description: “TUS İçin Kelime Kartlarıyla Hafızayı Güçlendiren Akıllı Platform”
date: 2025-12-19
image: "/images/posts/memotris-fikrin-hayati-roportaji-burak-can.jpg"
categories: ["art"]
authors: ["Abdullah Sahin"]
tags: ["fikrin hayatı", "girisimcilik", "memotris", "burak can"]
draft: false
---

##### 1. Bize kendinizden bahsedebilir misiniz? Kimsiniz, ne yapıyorsunuz?

Merhabalar, ben Burak Can. Şu anda Göğüs Cerrahisi asistanı olarak görev yapıyorum. Günlerimin büyük kısmı hastane koridorlarında, serviste hasta takibiyle, pansumanlarla ve tüp-dren takipleriyle geçiyor. Henüz asistanlığımın başlarındayım; yani "çömez" diyebileceğimiz o yoğun öğrenme sürecindeyim.

Ama işin ilginç tarafı şu: Önlüğümü çıkardığım an, bilgisayar başına geçip kod yazan tutkulu bir yazılım geliştiriciye dönüşüyorum. Tıp ve yazılım... Birbirine çok uzak görünebilirler ama aslında ikisi de temelde aynı şeyi yapıyor: _problem çözme_. Ben de bu iki dünyayı birleştirmeye, tıbbi eğitim sorunlarına teknolojik çözümler üretmeye çalışıyorum.

##### 2. Memotris'ten ve nasıl ortaya çıktığından bahsedebilir misiniz?

Memotris, öğrenmeyi daha kalıcı ve verimli hale getirmek için geliştirdiğim, "Aralıklı Tekrar" (Spaced Repetition) yöntemini temel alan akıllı bir çalışma platformu. Ama aslında hikaye bundan çok daha kişisel bir yerden başlıyor.

TUS'a hazırlanırken fark ettim ki asıl sorun _öğrenmek_ değil. Asıl sorun, o öğrendiğin devasa bilgi yığınını aylarca hafızanda taze tutabilmek. Sayısız ders notu, binlerce konu... Hepsini bir kez öğreniyorsun ama sınav gününe kadar hatırlamak başka bir mesele.

Piyasada Anki gibi global devler vardı tabii. Ama o uygulamayı her açtığımda içimden bir ses "Bu mu yani?" diyordu. Arayüzü 90'lardan kalma gibiydi, kullanımı karmaşıktı ve en önemlisi bizim sınav kültürümüze, çalışma dinamiklerimize hiç hitap etmiyordu.

Bir gece nöbetten sonra düşündüm: "Neden hem bilimsel metodu kullanan, hem de modern ve bizim ihtiyaçlarımızı anlayan bir platform yok?" İşte Memotris'in ilk satırları o gece yazıldı.

##### 3. Memotris kaç kişilik bir ekipten oluşuyor ve görev dağılımı nasıl?

Açıkçası Memotris şu an "tek kişilik bir ordu" tarafından yürütülüyor. Fikir aşamasından tasarıma, veritabanı mimarisinden arayüz kodlamasına, SEO çalışmalarından kullanıcı desteğine kadar her şeyi "Solo Founder" olarak ben yönetiyorum.

Bu durum bazen yorucu oluyor, yalan yok. Ama bir avantajı da var: Hedef kitlem bizzat benim. Bir doktor olarak, neyin gerçekten işe yarayıp neyin gereksiz olduğuna çok hızlı karar verebiliyorum. Kullanıcıların yaşadığı hayal kırıklıklarını birebir yaşadım çünkü.

##### 4. Memotris ilk kullanıcısını nasıl elde etti?

Henüz yolun başındayız, bu yüzden "müşteri" demek yerine "kullanıcı" demeyi tercih ediyorum — çünkü platform şu an temel özellikleriyle tamamen ücretsiz.

İlk kullanıcılarım, nöbet aralarında projeyi gösterdiğim yakın doktor arkadaşlarım ve çalışma grubum oldu. Onların geri bildirimleriyle ürünü şekillendirdim: "Şu buton daha büyük olsun", "Burası kafamı karıştırıyor", "Bu özellik harika ama şöyle olsa daha iyi"... Her biri altın değerinde bilgiydi.

Daha sonra profesyonel bir SEO optimizasyonu aldık ve internette görünürlüğümüz arttı. Şu an hiçbir reklam harcaması yapmadan, tamamen organik olarak ve _kulaktan kulağa_ yayılarak **100'den fazla aktif kullanıcıya** ulaştık. İnsanların fayda gördüğü bir şeyi birbirine tavsiye etmesi, bizim için en değerli büyüme motoru.

##### 5. Memotris'in geliştirilme sürecinde hangi araçları/teknolojileri kullandınız?

Modern ve kullanıcı dostu bir deneyim sunmak en başından önceliğimdi. Bunu başarmak için güncel ve güçlü bir teknoloji yığını tercih ettim:

###### Teknik Altyapı

- **Frontend:** Next.js 15 ve React 19 kullanıyorum. Bu, hem hızlı bir kullanıcı deneyimi hem de SEO dostu bir yapı sağlıyor.
- **Backend:** Convex — sunucu yönetimini sıfıra indiren, real-time senkronizasyon sunan harika bir platform. Veritabanı, API ve cron job'lar hep bir arada.
- **Kimlik Doğrulama:** Clerk ile güvenli ve rol tabanlı erişim kontrolü (RBAC).
- **PWA (Progressive Web App):** Uygulama mağazasına gerek kalmadan, tarayıcıdan yüklenebilen, **offline çalışabilen** bir deneyim. Hastanede internet kesilse bile çalışmaya devam edebilirsiniz.

###### Özellikler

Sadece kart çevirmek yetmezdi; kullanıcıyı motive etmek gerekiyordu:

- **SM-2 Algoritması:** Kartları "tam unutulacakken" tekrar gösteriyor. Bu, çalışma süresini yarı yarıya azaltırken kalıcılığı 3 kata kadar artırıyor.
- **Oyunlaştırma (Gamification):** XP puanları, çalışma serileri (streak), rozetler ve liderlik tabloları ile tatlı bir rekabet ortamı yarattık.
- **Akıllı Bildirim Sistemi:** Sistem, kullanıcının unutmaya başladığı anı hesaplayıp "Hey, bu kartlara bakman lazım" diye dürtüyor. Ama spam yapmadan — 4 saatlik "yorgunluk koruması" var.
- **Topluluk Özellikleri:** Desteler herkese açık paylaşılabiliyor, oylanabiliyor, yorumlanabiliyor. "Doğrulanmış İçerik Üreticisi" sistemiyle kaliteli içerikler öne çıkarılıyor.

###### Kolaylık

- **Import/Export:** Excel, JSON formatlarında kolayca veri aktarımı. Kimse verisini içeri sokarken veya dışarı alırken zorlanmasın.
- **Tek Tıkla Paylaşım:** Hazırlanan destelerin anında başkalarıyla paylaşılabilmesi, topluluk hissini çok güçlendirdi.

##### 6. Memotris'i geliştirirken karşılaştığınız zorluklar neler oldu?

Memotris'in kodlarına Mayıs 2025'te başladım. O dönem Hakkari'de sınırda zorunlu görevdeydim, ardından Karaman'da Acil Servis'te çalıştım. Son dönemdir de Göğüs Cerrahisi asistanıyım.

En büyük zorluğum teknik değildi açıkçası — _zihinseldi_. "Context Switching" yani bağlam değiştirme denen şey.

Düşünün: Bir an serviste hastanın drenini kontrol ediyorsunuz, belki bir acil durum yönetiyorsunuz, fiziksel ve mental olarak tükeniyorsunuz. Sonra 15-20 dakika boşluk bulup bilgisayarı açtığınızda, o "doktor" modundan çıkıp "yazılımcı" moduna geçmek, nerede kaldığını hatırlamak, koda odaklanmak... İnanılmaz zor bir süreç.

Bu dikkat dağınıklığını aşmak için kendi metodumu geliştirdim: Projeyi _çok küçük parçalara_ bölüyorum ve her boşlukta sadece _tek bir ufak göreve_ odaklanıyorum. Bir butonu düzelt, bir fonksiyon yaz, bir bug fix yap. Böylece yarım saat içinde bile somut bir ilerleme kaydedebiliyorum.

Ayrıca AI destekli kod editörleri (Cursor gibi) bu süreçte hayat kurtarıcı oldu. Sanki yanımda deneyimli bir yazılımcı oturuyor ve "Nerede kalmıştık?" soruma anında cevap veriyor.

##### 7. Memotris'i büyütmek için ne tür pazarlama stratejileri uyguladınız?

Şu an için _"Önce değer üret, büyüme arkadan gelir"_ mantığıyla ilerliyorum.

###### SEO (Arama Motoru Optimizasyonu)

TUS, ezber teknikleri, spaced repetition gibi konularda arama yapanların karşısına doğru içeriklerle çıkmaya çalışıyoruz. Blog yazıları, rehberler, teknik içerikler üretiyoruz.

###### Kulaktan Kulağa (Word of Mouth)

Şu ana kadarki en etkili yöntemimiz bu oldu. Bir asistanın diğerine "Bu uygulama ile çalışmak çok rahat" demesi, binlerce liralık reklamdan daha değerli. Şu anki 100+ kullanıcımızın büyük çoğunluğu bu samimi tavsiyelerle geldi.

###### İçerik Pazarlaması

Sosyal medyada (X, TikTok) TUS'a hazırlananlara yönelik içerikler üretmeyi planlıyoruz. Hedefimiz "TUS'a hazırlanan herkesin tanıdığı araç" olmak.

##### 8. Yapay Zekânın Memotris'e ne gibi bir katkısı oldu?

Yapay zeka benim gibi tek başına çalışan biri için gerçek bir _süper güç_.

###### Geliştirme Aşamasında

Cursor gibi AI destekli kod editörlerini yoğun şekilde kullanıyorum. Karmaşık bir algoritma yazarken, bir bug'ı çözerken veya yeni bir özellik eklerken sanki yanımda kıdemli bir yazılımcı oturuyor gibi hissediyorum. "Bu kodu nasıl optimize ederim?", "Bu hatanın kaynağı ne olabilir?" gibi sorulara anında kaliteli cevaplar alabiliyorum.

###### Ürün Tarafında (Yakında)

Kullanıcılarımıza yakında çok daha fazlasını sunacağız. Planlarımız arasında:

- **AI ile Kart Üretimi:** Kullanıcı uzun bir ders notunu veya PDF'i yükleyecek, yapay zeka saniyeler içinde bunu soru-cevap kartlarına dönüştürecek. Bu, kart hazırlama süresini 10 kat kısaltacak bir devrim.
- **Görsel Gizleme (Image Occlusion):** Özellikle anatomi ve patoloji için kritik. Bir görsel yükleyip üzerindeki etiketleri gizleyerek kendinizi test edebileceksiniz.
- **Klinik Vaka Simülasyonu:** "Hasta X semptomlarıyla geldi → Tanın ne? → Tedavin ne?" şeklinde dallanmalı senaryolar. TUS'un gerçek formatını simüle edecek.

##### 9. Memotris'in gelir kaynakları nelerdir?

Şu an için Memotris'in temel özellikleri tamamen **ücretsiz**. Odak noktamız para kazanmak değil; ürünün gerçekten işe yaradığını kanıtlamak ve kullanıcı tabanını büyütmek.

İlerleyen dönemde çok kanallı bir gelir modeli planlıyoruz:

###### 1. Freemium Model (B2C)

Temel özellikler hep ücretsiz kalacak. Ama sınırsız AI kullanımı, gelişmiş analizler, offline mod gibi premium özellikler için makul bir aylık/yıllık abonelik sistemi gelecek.

###### 2. Kurumsal Lisanslama (B2B)

Dershaneler ve üniversiteler için toplu lisans satışı. Kurumlar kendi öğrencilerinin ilerlemesini tek bir panelden takip edebilecek, özel içerikler oluşturabilecek.

###### 3. İçerik Üretici Pazaryeri (Marketplace)

"Doğrulanmış İçerik Üreticileri" — yani TUS'ta yüksek puan almış veya alanında uzman kişiler — kendi premium destelerini satabilecek. Memotris de bu satışlardan komisyon alacak. Bu model, hem kaliteli içerik üretimini teşvik ediyor hem de sürdürülebilir bir gelir kaynağı oluşturuyor.

##### 10. Memotris kurarken sahip olduğunuz deneyimin yeterli olduğunu düşünüyor muydunuz?

Kesinlikle **hayır**. Hatta çoğu zaman "Ben ne yapıyorum ya?" diye sorguladığım anlar oldu. Tıp fakültesinde bize kodlama öğretmiyorlar sonuçta.

Ama zamanla şunu fark ettim: Girişimcilikte "yeterli bilgiye sahip olmak" diye bir şey yok, _"yeterli meraka sahip olmak"_ var.

Proje boyunca bilmediğim onlarca teknolojiyi — PWA, Service Workers, IndexedDB, veritabanı optimizasyonu, push notification sistemleri — ihtiyacım oldukça, deneye yanıla öğrendim. Bir şeyi bilmemek, onu yapmama engel değil; _öğrenemeyeceğime inanmak_ engel.

Kervan yolda düzüldü diyebilirim. Ve hâlâ düzülmeye devam ediyor.

##### 11. Yeni başlayan girişimcilere tavsiye edebileceğiniz öğrenme kaynakları nelerdir?

###### Pratik Yapın

YouTube'da "baştan sona proje geliştirme" videoları izlemek, teorik bilgiden çok daha değerli. Bir e-ticaret sitesi, bir todo uygulaması, bir blog... Ne olursa olsun, _bir şey_ yapın.

###### Dokümantasyon Okuyun

Kullandığınız teknolojinin resmi dokümanları en iyi rehberdir. Next.js docs, Convex docs, React docs... Bunları okumaktan kaçmayın.

###### Yapay Zekâyı Akıllıca Kullanın

ChatGPT, Claude, Cursor gibi AI araçlarını sadece kod yazdırmak için kullanmayın. "Bu neden böyle çalışıyor?", "Alternatif yaklaşımlar neler?" gibi sorular sorun. Onları bir _öğretmen_ gibi kullanın.

###### Küçük Başlayın, Hızlı Bırakın (veya Devam Edin)

Büyük vizyonlar güzel ama ilk hafta "dünya çapında platform" kurmaya çalışmayın. En küçük çalışan versiyonu (MVP) yapın, kullanıcılara gösterin, geri bildirim alın. Ya doğru yolda olduğunuzu anlarsınız, ya da erken vazgeçip yeni bir şey denersiniz.

##### 12. Memotris olarak gelecek hedefleriniz ve planlarınız nelerdir?

###### Kısa Vade: TUS Pazarında "Vazgeçilmez" Olmak

Öncelikli hedefimiz, TUS'a hazırlanan hekimler arasında _"Bu olmadan çalışamıyorum"_ dedirten bir araç olmak. Bunun için AI özelliklerini (Text-to-Cards, Image Occlusion) ve TUS'a özel araçları (Klinik Vaka Simülasyonu) bir an önce yayına almayı hedefliyoruz.

###### Orta Vade: Komşu Pazarlara Genişleme

TUS'taki başarımızı "sosyal kanıt" olarak kullanarak — _"Doktorlar bile bu sistemi kullanıyor!"_ — DUS, YDS, YKS, KPSS gibi ezberin ve düzenli tekrarın kritik olduğu tüm sınavlara açılmak istiyoruz.

###### Uzun Vade: Türkiye'nin Öğrenme Platformu

Sınavlara hazırlanan herkesin cebinde, onları anlayan ve onlara özel bir çalışma planı sunan akıllı bir asistan. Sadece bir flashcard uygulaması değil; _akıllı bir öğrenme ekosistemi_.

---

Herhangi bir sorunuz, geri bildiriminiz veya bir sonraki röportajın kiminle olmasını istediğinizi belirtmek için lütfen Twitter'dan bizimle paylaşmaktan çekinmeyin: **[@fikrinhayati](https://twitter.com/fikrinhayati)**

---
