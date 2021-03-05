# Yapay Zeka ile Hastalık Teşhisi Koymanın Risk ve Tehditleri
**Tarih: 2020**

## İçindekiler
- [Tehditlerin Belirlenmesi](#Tehditlerin-Belirlenmesi)
- [Açıklıkların Belirlenmesi](#Açıklıkların-Belirlenmesi)
- [Mevcut ve Planlanan Kontrollerin Belirlenmesi](#Mevcut-ve-Planlanan-Kontrollerin-Belirlenmesi)
- [Olasılık Değerlendirmesi ve Etki Analizi](#Olasılık-Değerlendirmesi-ve-Etki-Analizi)
- [Risk Derecelendirmesi](#Risk-Derecelendirmesi)
  * [Risk Derecelendirme Matrisi Tanımı](#Risk-Derecelendirme-Matrisi-Tanımı)
  * [Risk Derecelendirme Matrisi](#Risk-Derecelendirme-Matrisi)
- [Uygun Kontrollerin Belirlenmesi](#Uygun-Kontrollerin-Belirlenmesi)
  * [Teknik Güvenlik Kontrolleri](#Teknik-Güvenlik-Kontrolleri)
  * [Yönetimsel Kontroller](#Yönetimsel-Kontroller)
  * [Operasyonel Kontroller](#Operasyonel-Kontroller)
- [Sonuçların Dokümantasyonu](#Sonuçların-Dokümantasyonu)
- [Risk İşleme](#Risk-İşleme)
- [Değerlendirme ve Takip](#Değerlendirme-ve-Takip)
- [Kaynakça](#Kaynakça)


*Şirket Tanımı:* Sağlık Alanında Yapay Zeka

*Şirket Amacı:* Sağlık alanında kararların yavaş yavaş yapay zekaya güvenilerek alınmasını sağlayarak daha güvenli, hata olasılığı az ve hızlı şekilde karar verilebilmesini sağlayacak kansere erken teşhis koyarak süreci hızlandırma amacı taşıyor.

> Cilt kanseri tespiti, göz sağlığı, akciğer kanseri ve felç teşhisi, ani kalp krizi riskinin belirlenmesi…

# Tehditlerin Belirlenmesi

1. Risk yönetim ekibimden olası tehditlerin tanımlanmasını istedim.

2. Alınan yanıtları tehdit kategorilerine ayırıp gruplayarak risk yönetim ekibime incelemeleri için tekrar gönderdim.

3. Geriye yapılan dönüşlerle birlikte tehdit listesi oluştu.

Aşağıdaki tabloda Tehdit Faktörü, Tehdit Nedeni ve Önlemi listelenmiştir bu önlemlerin alınmaması dahilinde hasta sağlığı tehdit edilecek ve kriz denilecek çok büyük olumsuzluklar başımıza gelecektir.

| **Tehdit Faktörü** | **Tehdit**                                           | **Tehdit Nedeni**                                            | **Tehdit Önlemi**                                            |
| ------------------ | ---------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Çalışanlar         | Virüs  Bulaşıcılığı                                  | Virüs  Bulaşıcılığının yüksek  olması ve günlük  hayatımızda çok fazla  yerde olması | Bu sürece özel bir otel  veya  konaklanma yeri tutulması  ve bu soruna çözüm  bulana kadar burada  konaklanması. |
| Çalışanlar         | Teçhizat                                             | Virüs Bulaşıcılığı                                           | Çalışma alanları otelin  içinde  konumlanmalı ve  tüm teknolojik  ihtiyaçlar ve teçhizatlar  bulunmalı |
| Eğitim             | Eğitim ve  Mentorluk  Desteğinin  Dışardan  Alınması | Uçak ile başka ülkelerden  veya  şehirlerden gelen mentor  ve  eğitimcilerimizin virüsü  yayma riski | Havayolları uzun mesafe  yolculuklarının  engellenmesi ve  bu süreç dahilinde  mentorluğun veya  eğitim uzaktan online  yollarla yapılması. |
| Çalışma Ortamı     | Ortam Sağlığı ve Güvenliği                           | Geliştirilecek ürünün  sağlıklı bir ortamda  olmaması  insanların sağlığını  tehdit edebilir. | Her mola arasında temizlik  görevlilerin ortamı  temizlemesi.  Çalışanların bu sürece  özel  kıyafetler ve özel maskelerle  çalışması. |

| **Tehdit Faktörü** | **Tehdit**              | **Tehdit Nedeni**                                            | **Tehdit Önlemi**                                            |
| ------------------ | ----------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Teknik             | Yeni Teknoloji          | Aşina olunmayan bir teknolojiye  geçiş ile yanlış teşhis koymak. | En iyi yazılım  geliştiricileri ve sağlık  çalışanlarıyla bu  sürece ait özel bir ekip  oluşturulması |
| Sektör             | Sağlık Sektörü          | Sağlık sektöründe olmamız  başlı  başına bir tehdit  ve sonucun %100 geçerli  olmaması | En iyi yazılım  geliştiricileri ve sağlık  çalışanlarıyla bu  sürece ait özel bir ekip  oluşturulması |
| Takım              | Takım Ruhu              | Bu süreçte çözüm bulana kadar  otelde  konaklanma  zorunluluğunun  olduğu moral  bozukluğu  çalışmanın kötüye  gitmesine sebep  olabilir | Sık sık takım motivesi ve  ekibin birbirine  kenetlenerek  bağımlı bir şekilde  çalışması, ekibin  tüm ihtiyaçlarının en iyi şekilde  giderilmesi |
| Hasta              | Hastanın Deneyimsizliği | Hastanın daha önce böyle büyük  bir virüsle karşı  karşıya kalmamış olması ve  telaş | Hasta bilgilendirme  toplantıları yapılması,  ihtiyaçlarının sorulması. |
| Organizasyon       | Ekip Stabilitesi        | Projedeki en önemli kişilerin  projeyi  bitiremeden ayrılması | Bu kişilerle sözleşme  yapılması ve olası durumda  yerine  geçebilecek kişinin  ayarlanması |

| **Tehdit Faktörü** | **Tehdit**    | **Tehdit  Nedeni**                                           | **Tehdit  Önlemi**                                           |
| ------------------ | ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Ekonomi            | Bütçe         | Bütçenin yeterli olmaması                                    | Risk toleransı için ayrılan fondan kullanmak ve  maliyetleri tek tek kayıt altında tutmak |
| Zaman              | Zaman Baskısı | Şartlar çalışanların ürünü  kısa sürede  bitirmesini talep ediyor | Proje maliyetleri ve süresi göz  önüne alınarak sözleşme  imzalanması ve sözleşmenin dışına çıkılmaması |



# Açıklıkların Belirlenmesi

Tehditlerimiz yukarıda açıkça belirtilmiştir bunlara karşı eğer önlem alınmazsa ciddi açıklıklar oluşmasına neden olacaktır.

1. Çalışanların konaklayacağı bir yerimiz yok. Bu bizim bir açığımız

2. İhtiyacımız olan teçhizat dışardan karşılanırsa ve eğer bunlar dezenfekte edilmeden çalışma alanına girerse virüs tehtidine karşı bir açığımız olur.

3. Dışardan bir mentorluk veya eğitim almak zorunda kalmamız durumunda dışardan birinin içeriye girmesi.

4. Ortamın ciddi bir şekilde temizlenmemesi.

5. Takım motivasyonunun çökmesi bütün sürecin alt üst olmasına sebep olabilir bu açığın iyi kapanması çalışanların motivasyonunun yüksek tutulması gerekir.

6. Hasta veya çalışan, deneyimsizliğiyle beraber gelen telaş ve korku halinde yanlış kararlar vermesi.

7. Çalışma alanında olan kişilerin dikkatsizliği.

8. Çalışanların dışarıda gezmeye vs. alışkanlığı bulunması.

Bunlar virüse davet veren açıklıklardır. Bilinçli şekilde önlem alıp korku ve telaşın olmaması için motivasyonun yüksek tutulması ve sık sık bilgilendirme toplantıları yapılıp ihtiyaçların sorulması gerekmektedir.

# Mevcut ve Planlanan Kontrollerin Belirlenmesi

1. Her çalışanın kendine özel odası, yatağı, temizlik malzemesi olması.

2. Plastik bardak kullanılması.

3. Herkesin kendi temizliğinden sorumlu olmasının üstüne temizlik görevlilerinin verimli çalışması.

4. Bu yapılan uygulamaların temizlik görevlilerince düzenli olarak teyit edilmesi.

5. Bu süreç içerisinde buzlukta tutulan besinlerin kullanılması, ek takviye gıdalar ve vitaminler alınması.

6. İnsanların yemek ihtiyacının dışardan değil içerden giderilmesi.

7. Eğitim ve Mentorluğun online olarak yapılmasına devam edilmesi.

Herkesi eşit ve yüksek derecede önlem almalı. Temel ihtiyaçlarımızı sağlayacak ürün çeşitliliğinin fazla olması kontrolü arttırmamızı sağlar.

# Olasılık Değerlendirmesi ve Etki Analizi

Bu virüsün herkese bulaşabilmesinden dolayı her an hazırlıklı olup her an tehlikedeymiş gibi önlem alırsak olasılıklar düşüş gösterecektir.

Aşağıdaki tabloda

* Riskin gerçekleşme olasılığının çok küçük olması 1 ile

* Riskin gerçekleşme olasılığı, gerçekleşmeme daha az ise 2 ile

* Riskin gerçekleşme olasılığı orta derece ise 3 ile

* Riskin gerçekleşme olasılığı fazla ise 4 ile

* Riskin gerçekleşme olasılığı neredeyse kesin ise 5 ile gösterilmiştir.

| **MALİYET  ETKİSİ OLASILIĞI** | **ETKİ  DEĞERİ** |
| ----------------------------- | ---------------- |
| Fazla Sayılmayacak Maliyet    | 1                |
| Maliyet artış aralığı < %10   | 2                |
| Maliyet artış aralığı < %30   | 3                |
| Maliyet artış aralığı < %50   | 4                |
| Maliyet artış aralığı < %60   | 5                |

| **SÜRE  ARALIĞI** | **MALİYET ARALIĞI OLASILIĞI** | **ETKİ  DEĞERİ** |
| ----------------- | ----------------------------- | ---------------- |
| Süre <= 40        | Maliyet <= 1000₺              | 1                |
| Süre <= 80        | Maliyet <= 2500₺              | 2                |
| Süre <= 100       | Maliyet <= 4500₺              | 3                |
| Süre <= 140       | Maliyet <= 7000₺              | 4                |
| Süre <= 180       | Maliyet <= 15000₺             | 5                |

| **RİSKİN  PROJE ANINDA GERÇEKLEŞME OLASILIĞI** | **ETKİ DEĞERİ** |
| ---------------------------------------------- | --------------- |
| %71 - %90                                      | 1               |
| %51 - %70                                      | 2               |
| %30 - %50                                      | 3               |
| %10 - %30                                      | 4               |
| <= %10                                         | 5               |

# Risk Derecelendirmesi

## Risk Derecelendirme Matrisi Tanımı

Aşağıdaki tablo Olasılık ve risk derecesi olarak ayrılmıştır risk derecelendirme aşağıdaki tabloya göre yapılacaktır. Yüksek risk derecesinde olan riskler için proje başlamadan önce risk önlemleri mutlaka alınmalı. Böylece riskten doğacak riskleri de önlemiş oluruz.

| **ETKİ** | **ÇOK CİDDİ**  **(5)** | **CİDDİ**  **(4)** | **ORTA**  **(3)** | **HAFİF**  **(2)** | **ÇOK HAFİF**  **(1)** |
| -------- | ---------------------- | ------------------ | ----------------- | ------------------ | ---------------------- |
| 5        | 25                     | 20                 | 15                | 10                 | 5                      |
| 4        | 20                     | 16                 | 12                | 8                  | 4                      |
| 3        | 15                     | 12                 | 9                 | 6                  | 3                      |
| 2        | 10                     | 8                  | 6                 | 4                  | 2                      |
| 1        | 5                      | 4                  | 3                 | 2                  | 1                      |

## Risk Derecelendirme Matrisi

| **Riskler**                                          | **Gerçekleşme**  **Olasılığı** | **Zamana**  **Etkisi** | **Zamana**  **Göre**  **Risk** | **Maliyete Etkisi** | **Maliyete**  **Göre**  **Riski** |
| ---------------------------------------------------- | ------------------------------ | ---------------------- | ------------------------------ | ------------------- | --------------------------------- |
| 1. Virüs Bulaşıcılığı                                | 4                              | 3                      | 12 / Yüksek                    | 4                   | 16 / Yüksek                       |
| 2. Teçhizat                                          | 3                              | 1                      | 3 / Çok Hafif                  | 3                   | 9 / Orta                          |
| 3.Eğitim ve Mentorluk  Desteğinin Dışardan  Alınması | 4                              | 1                      | 4 / Hafif                      | 1                   | 4 / Hafif                         |
| 3. Ortam Sağlığı ve  Güvenliği                       | 1                              | 2                      | 2 / Çok Hafif                  | 2                   | 2 / Çok Hafif                     |
| 4. Yeni Teknoloji                                    | 4                              | 3                      | 12 / Yüksek                    | 5                   | 20 / Çok Yüksek                   |
| 5. Sağlık Sektörü                                    | 4                              | 2                      | 8 / Orta                       | 5                   | 20 / Çok Yüksek                   |
| 6. Takım Ruhu                                        | 2                              | 3                      | 6 / Orta                       | 2                   | 4 / hafif                         |
| 7. Hastanın  Deneyimsizliği                          | 4                              | 3                      | 12 / Yüksek                    | 3                   | 12 / Yüksek                       |
| 8. Ekip Stabilitesi                                  | 2                              | 3                      | 6 / Orta                       | 2                   | 4 / hafif                         |
| 9. Bütçe                                             | 4                              | 2                      | 8 / Orta                       | 5                   | 20 / Çok Yüksek                   |
| 10. Zaman Baskısı                                    | 5                              | 4                      | 20 / Çok Yüksek                | 2                   | 10 / Orta                         |

Bu listelenen sonuçlardan süre ve maliyet açısından projeye olan etkisini değerlendirdiğimiz riskler arasından 6 adet riskin en yüksek risk grubunda olduğu sonucu ortaya çıkmıştır:

Risk 1: Virüs Bulaşıcılığı

Risk 4: Yeni Teknoloji

Risk 5: Sağlık Sektörü

Risk 6: Hastanın Deneyimsizliği

Risk 9: Bütçe

Risk 10: Zaman Baskısı

En yüksek risk grubundaki risklerin etkileri süre ve maliyet açısından değerlendirilmiştir.

# Uygun Kontrollerin Belirlenmesi

## Teknik Güvenlik Kontrolleri

1. Sürekli olarak özel kıyafet ve yüksek güvenlikli maskelerle çalışmak.

2. Burun akıntısı, vücut ağrıları ve halsizlik olması durumunda sağlık ekibine anında bildirmek.

3. Düzenli olarak ateşin ölçülmesi 

Güvenliğimiz için yukarıdaki maddelerin güvenliğini almalıyız eğer güvenlikten geçemeyen bir durum olursa aşağıdaki yönetimsel kontrollere başvurmalıyız.

## Yönetimsel Kontroller

1. Burun akıntısı, vücut ağrıları ve halsizlik olan çalışanların evlerin de karantina altında tutulmaları.

2. Bu hastaların durumlarını düzenli olarak kontrol etmek ve bilgilendirmeler sağlamak

3. Hastayı sürekli kontrol altında tutup telaşa mahal vermemek.

## Operasyonel Kontroller

1. Hastanın ciğerlerine düzenli olarak yeterli oksijen verilmesi

2. Sağlık çalışanları tarafından müdahaleye acilen başlanmalı

3. Sağlık çalışanları ve teknik ekip tarafından kan kontrolü yapılmalı

4. Travma sonrası stres bozukluğunu düzeltilmesi

Operasyonel kontroller en iyi sağlık çalışanları ve teknik ekibin müdahalesiyle düzenli olarak gerçekleşmelidir.

# Sonuçların Dokümantasyonu

Aşağıda yazılan maddelerin tek tek verileri tutulmalıdır

1. Bu süreçte çalışanlarımızdan kaç kişi rahatsızlandı ?

2. Kaç kişi ağır hastaya dönüştü ? 

3. Kaç kişi ölümle sonuçlandı ?

4. Kaç kişi iyileşti ?

5. Kaç kişi stres bozukluğu yaşadı ve psikolojik destek istedi ?

Bu tutulan veriler ışığında geri dönüşümlü olarak risklerin kontrol edilmesi, açıkların kontrol edilmesi olasılık etki değerleri ve risk derecelendirme matrisi güncellenecektir. Bu sayede yeni kararları daha tecrübeli ve veriye dayalı bir şekilde almamız çözümün sürecinde bize fayda sağlayacaktır. Bu önerilen yöntem örnek bir vaka ile sınanarak elde edilen sonuçlar tartışılacaktır. Bu analiz süreçleri birbirleriyle yoğun bilgi alışverişi içinde bulunacak şekilde tasarlanmıştır. Riskler için belirlenen stratejiler proje esnasında izlenerek, uyarı mekanizmasının yardımı ile risk veri setindeki son durum risk derecesinin değişimi görülebilir ve proje sonrası gereken müdahaleyi yapma fırsatı elde edilir. Proje boyunca meydana gelebilecek olumsuz sonuçlar izlenip risk haline gelmeden önlemi alınabilmektedir. Bu doğrultuda yapılan her çalışma projeyi olumlu yönde etkilemekle beraber riskler oluşmadan önlenmesi sağlanabilecektir. Tehdit unsurlarında karşılaşılması muhtemel riskler hepsi için farklılık göstermektedir. Bu nedenle risk belirleme aşamasında risklerin sınıflandırılması gerektiğinin önemi ortaya çıkmıştır. 

 # Risk İşleme

Sonuç Dokümantasyonu bölümünde topladığımız verilerin analiz edilmesi buna göre bir hamle yapılması gerekmektedir. 

1. Sınıflandırmak tehdit unsurlarının riske olan etkilerinin değerlendirilmesi açısından daha etkin olacağı için sınıflandırma yöntemine gidilmeli.

2. Yüksek dereceli risk olarak değerlendirilen riskler proje bütçesine yansıtılmalıdır.

3. Çalışma ortamında hasta olan kişilerin etrafındaki çalışma arkadaşları ve ekipteki yakın olduğu kişiler hastalığın sıçrama riskine karşın derhal kontrol altına alınmalı.

4. Hasta olan kişilerin yakınlarıyla fiziksel görüşmesi yasaklanmalı

5. Hasta olan kişinin tüm ihtiyaçlarının giderilmesi

6. Sonuç Dokümantasyonunda topladığım verileri sınıflandırarak bir risk haritası çıkartıyoruz 

# Değerlendirme ve Takip

Riskler için belirlenen stratejiler izlenmeli, verilerin son durum risk derecesinin değişimi dahilinde güncellenirse gereken müdahaleyi yapma fırsatı elde edilir.

Tuttuğumuz verilerle beraber veriye dayalı olarak ölüm, iyileşme, hasta, maliyet, zaman sonuçlarına bakılarak önlem alınması dahilinde kötüye mi yoksa iyiye mi gittiği analiz edilip veriye göre karar alınacak. Geri dönüşümlü olarak risklerin kontrol edilmesi, açıkların kontrol edilmesi olasılık etki değerleri ve risk derecelendirme matrisi güncellenmesi ani kararlarda hızlı yanıt vermemizi sağlayacaktır.

Yeni planlara ve yapıcı tartışmalara açık olmalıyız. Sürecin her döngüde 1 kere değerlendirme ve takibi yapılarak riske mahal vermemek ve virüsü atlatmak adına yardımcı olacaktır.

Bu döngünün sonunda yaptığımız uygulamaların sonucu iyiye mi yoksa kötüye mi gittiği açık bir şekilde belirtilmelidir. Mutlaka bir başarı çizgimiz olmalıdır ve buna göre önlem alınarak yeni döngüye geçilmelidir.

# Kaynakça

* [Bulut Bilişimde Güvenlik Zaafiyetleri ve Tehditleri](kaynakca/BulutBilisimdeGuvenlikZaafiyetleriveTehditleri.pdf)
* [Yazılım Geliştirme Projelerinde Risk Yönetimi](kaynakca/YazılımGelistirmeProjelerindeRiskYönetimi.pdf)

---

*All Right Reserved © Yiğit Çakmak*

