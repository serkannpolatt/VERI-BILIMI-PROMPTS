<h1> CHATGPT Veri Bilimi için Promptlar </h1>
---
# İçindekiler:
1. [Python yaz](#write-python)
2. [Kodu açıkla](#kodu-açıkla)
3. [Kodu optimize et](#kodu-optimize-et)
4. [Kodu biçimlendir](#format-kodu)
5. [Kodu bir dilden diğerine çevirin](#translate-code)
6. [Kavramları açıklayın](#kavramları-açıklayın)
7. [Fikir önerin](#fikir-önerin)
8. [Sorun Giderme Sorunu](#Sorun-Giderme-Problemi)
9. [SQL yaz](#write-sql)
10. [Diğer Kodu Yaz](#diğer-kodu-yaz)
11. [Çeşitli](#çeşitli)

---
# PYTHON YAZIN
## 1. Tren Sınıflandırma Modeli
> İstem: Bir veri bilimcisi olarak hareket etmenizi ve benim için kod yazmanızı istiyorum. "[Veri kümesini tanımla]" veri kümem var. Lütfen "[hedef değişken]"i tahmin eden bir makine öğrenimi modeli oluşturun.

## 2. Otomatik Makine Öğrenimi
> İstem: Benim için TPOT'u kullanan otomatik makine öğrenimi (AutoML) botu gibi davranmanızı istiyorum. '[...]' öngören bir model üzerinde çalışıyorum. Test setinde en yüksek AUC puanına sahip en iyi sınıflandırma modelini bulmak için lütfen Python kodunu yazın.

## 3. Hiperparametreyi Ayarla
> İstem: Bir veri bilimcisi olarak hareket etmenizi ve benim için kod yazmanızı istiyorum. Bir `[model adı]` eğittim. Lütfen hiperparametreleri ayarlamak için kodu yazın.

## 4. Verileri Keşfedin
> İstem: Bir veri bilimcisi olarak hareket etmenizi ve benim için kod yazmanızı istiyorum. "[Veri kümesini tanımla]" veri kümem var. Lütfen veri görselleştirme ve keşfetme için kod yazın.

## 5. Veri Oluşturun
> İstem: Sahte bir veri oluşturucu olarak hareket etmenizi istiyorum. X satırı ve y sütunu olan bir veri kümesine ihtiyacım var: `[sütun adlarını girin]`

## 6. Regex'i yazın
> Komut: Bir kodlayıcı olarak hareket etmenizi istiyorum. Lütfen bana Python'da `[regex'i açıkla]' şeklinde bir normal ifade yazın

## 7. Tren Zaman Serisi
> İstem: Bir veri bilimcisi olarak hareket etmenizi ve benim için kod yazmanızı istiyorum. Bir zaman serisi veri kümem var `[veri kümesini tanımla]`. Lütfen "[hedef değişken]"i tahmin eden bir makine öğrenimi modeli oluşturun. Lütfen tren olarak "[zaman aralığı]"nı ve doğrulama olarak "[zaman aralığı]"nı kullanın.

## 8. Adres Dengesizliği Verileri
> Komut: Bir kodlayıcı olarak hareket etmenizi istiyorum. Dengesiz bir veri kümesi üzerinde bir makine öğrenimi modeli eğittim. Tahmin değişkeni "[Sütun adını girin]" sütunudur. Python'da verilerimi nasıl aşırı örnekleyebilirim ve/veya yetersiz örnekleyebilirim?

## 9. Özelliğin Önemini Alın
> Komut: Bir veri bilimcisi gibi hareket etmenizi ve modelin sonuçlarını açıklamanızı istiyorum. Bir karar ağacı modeli eğittim ve en önemli özellikleri bulmak istiyorum. Lütfen kodu yazın.

## 10. Matplotlib ile Verileri Görselleştirin
> Komut: Python'da kodlayıcı olarak hareket etmenizi istiyorum. "[name]" sütunlarına sahip bir "[name]" veri kümem var. "[Grafik gereksinimlerini açıklayın]"

## 11. Görüntü Izgarası Matplotlib'ini Görselleştirin
> Komut: Bir kodlayıcı olarak hareket etmenizi istiyorum. Bir resim klasörüm var. `[Dosyaların dizinde nasıl organize edildiğini açıklayın]` `[Görüntülerin nasıl yazdırılmasını istediğinizi açıklayın]`

## 12. Kireçli Modeli Açıklayın
> Komut: Bir veri bilimcisi gibi hareket etmenizi ve modelin sonuçlarını açıklamanızı istiyorum. Bir `[kütüphane adı]` modeli eğittim ve çıktıyı LIME kullanarak açıklamak istiyorum. Lütfen kodu yazın.

## 13. Shap ile Modeli Açıklayın
> Komut: Bir veri bilimcisi gibi hareket etmenizi ve modelin sonuçlarını açıklamanızı istiyorum. Bir scikit-learn XGBoost modeli eğittim ve çıktıyı Shap ile bir dizi grafik kullanarak açıklamak istiyorum. Lütfen kodu yazın.

## 14. Çok İş parçacıklı İşlevleri Yazma
> Komut: Bir kodlayıcı olarak hareket etmenizi istiyorum. Bu kodu Python'daki iş parçacıkları arasında paralelleştirmeme yardım edebilir misiniz?

## 15. İşlev Hızını Karşılaştırın
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Python'da aynı görevi gerçekleştiren iki algoritmanın verimliliğini karşılaştırmak istiyorum. Lütfen 5 kez tekrarlanabilecek bir deneyi yürütmeme yardımcı olacak kodu yazın. Lütfen denemenin çalışma zamanını ve diğer özet istatistiklerini yayınlayın. `[İşlevleri ekle]`

## 16. NumPy Dizisi Oluşturun
> İstem: Bir veri bilimcisi gibi hareket etmenizi istiyorum. Bir numpy dizisi oluşturmam gerekiyor. Bu numpy dizisi (x,y,z) şeklinde olmalıdır. Lütfen numpy dizisini rastgele değerlerle başlatın.

## 17. Birim Testini Yaz
Kredi: [@svpino](https://twitter.com/svpino)
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Lütfen `[Fonksiyon Ekle]` fonksiyonu için birim testleri yazın. Test senaryoları şunlardır: `[Test senaryolarını ekleyin]`

## 18. Sütunu Doğrula
> İstem: Bir veri bilimcisi gibi hareket etmenizi istiyorum. Lütfen pandalarımın Dataframe'inin `[gereksinimleri buraya ekleyin]' olup olmadığını test etmek için kod yazın.

# KODU AÇIKLAYIN
## 19. Python'u açıklayın
Kredi: [@svpino](https://twitter.com/svpino)
> İstem: Kod açıklayıcısı olarak hareket etmenizi istiyorum. Bu kod ne yapıyor? '[Kodu girin]'

## 20. SQL'i açıklayın
> İstem: Bir veri bilimi eğitmeni olarak hareket etmenizi istiyorum. Lütfen bana bu SQL kodunun ne yaptığını açıklayabilir misiniz? `[SQL kodunu girin]`

## 21. Google E-Tablolar Formülünü Açıklayın
> İstem: Google E-Tablolar formül açıklayıcısı olarak hareket etmenizi istiyorum. Aşağıdaki Google E-Tablolar komutunu açıklayın. '[Formül ekle]'

# KODU OPTİMİZE ET
## 22. Kod Hızını Artırın
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Lütfen aşağıdaki kodun zaman karmaşıklığını geliştirmeme yardımcı olun. '[Kodu girin]'

## 23. Pandaları Optimize Edin
> İstem: Kod iyileştirici olarak hareket etmenizi istiyorum. Aşağıdaki panda kodunda neyin yanlış olduğunu belirtebilir ve onu optimize edebilir misiniz? `[Kodu buraya ekleyin]`

## 24. Pandaları Yeniden Optimize Edin
> İstem: Kod iyileştirici olarak hareket etmenizi istiyorum. Aşağıdaki panda kodunda neyin yanlış olduğunu belirtebilir ve onu optimize edebilir misiniz? `[Kodu buraya ekleyin]`

## 25. Python'u Optimize Edin
> İstem: Kod iyileştirici olarak hareket etmenizi istiyorum. Kod kötü yazılmış. Bunu nasıl düzeltebilirim? `[Kodu buraya ekleyin]`

## 26. SQL'i Optimize Edin
> İstem: SQL kod iyileştiricisi olarak hareket etmenizi istiyorum. Aşağıdaki kod yavaştır. Hızlandırmama yardım eder misin? "[SQL'i Ekle]'

## 27. Python'u Basitleştirin
> İstem: Kod basitleştirici olarak hareket etmenizi istiyorum. Aşağıdaki kodu basitleştirebilir misiniz?

# FORMAT KODU
## 28. Belgeleri Yazın
Kredi: [@svpino](https://twitter.com/svpino)
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Lütfen aşağıda func1'e ilişkin belgeleri sağlayın. '[İşlev ekle]'

## 29. Okunabilirliği Artırın
> İstem: Bir kod analizcisi olarak hareket etmenizi istiyorum. Okunabilirlik ve sürdürülebilirlik açısından aşağıdaki kodu geliştirebilir misiniz? '[Kodu girin]'

## 30. SQL'i biçimlendirin
> İstem: SQL biçimlendirici olarak hareket etmenizi istiyorum. Lütfen aşağıdaki SQL kodunu biçimlendirin. Lütfen tüm ayrılmış anahtar kelimeleri büyük harfe dönüştürün `[Gereksinimleri girin]`. '[Kodu Girin]'

# KODU ÇEVİR
## 31. DBMS Arasında Çeviri
> İstem: Bir kodlayıcı olarak hareket etmenizi ve MySQL için SQL kodu yazmanızı istiyorum. MySQL için PostgreSQL'in DATE_TRUNC'unun eşdeğeri nedir?

## 32. Python'u R'ye çevirin
Kredi: [@svpino](https://twitter.com/svpino)
> İstem: Kod çevirmeni olarak hareket etmenizi istiyorum. Lütfen aşağıdaki kodu Python'dan R'ye dönüştürebilir misiniz? '[Kodu girin]'

## 33. R'yi Python'a çevirin
Kredi: [@svpino](https://twitter.com/svpino)
> İstem: Kod çevirmeni olarak hareket etmenizi istiyorum. Lütfen aşağıdaki kodu R'den Python'a dönüştürebilir misiniz? '[Kodu girin]'

# KAVRAMLARI AÇIKLAYIN
## 34. Beş Yaşındaki Çocuğa Açıklayın
> İstem: Bir veri bilimi eğitmeni olarak hareket etmenizi istiyorum. Beş yaşındaki bir çocuğa `[kavramı]' açıklayın.

## 35. Lisans'a Açıklayın
> İstem: Bir veri bilimi eğitmeni olarak hareket etmenizi istiyorum. Bir lisans öğrencisine `[kavramı]' açıklayın.

## 36. Profesöre açıklayın
> İstem: Bir veri bilimi eğitmeni olarak hareket etmenizi istiyorum. Bir profesöre "[kavramı]" açıklayın.

## 37. Ticari Paydaşlara Açıklayın
> İstem: Bir veri bilimi eğitmeni olarak hareket etmenizi istiyorum. Bir iş paydaşına `[kavramı]' açıklayın.

## 38. Stackoverflow Gibi Açıklayın
> İstem: StackOverflow'ta yanıtlayıcı olarak hareket etmenizi istiyorum. Cevabınızı desteklemek için kod parçacıkları, örnek tablolar ve çıktılar sağlayabilirsiniz. '[Teknik soruyu girin]'

# FİKİRLER ÖNERİYORUZ
## 39. Edge Durumlarını Önerin
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Lütfen bu işlev `[insert function]` için uç durumları yakalamama yardım edin

## 40. Veri Kümesini Önerin
> İstem: Bir veri bilimi kariyer koçu olarak hareket etmenizi istiyorum. `[...]` için tahmine dayalı bir model oluşturmak istiyorum. Aynı zamanda bilgimi `[...]' alanında sergilemek istiyorum. Lütfen kullanım durumum için en alakalı beş veri kümesini önerebilir misiniz?

## 41. Portföy Fikirleri Önerin
> Komut: Bir veri bilimi koçu olarak hareket etmenizi istiyorum. Geçmişim `[...]' ve `[kariyer hedefi]'ni istiyorum. '[...]'de bir '[...]' olarak rol almama yardımcı olacak bir veri bilimi projeleri portföyü oluşturmam gerekiyor. '[...]' konusundaki uzmanlığımı sergileyecek ve '[şirket]' ile alakalı beş spesifik portföy projesi önerebilir misiniz?

## 42. Kaynak Önerin
> Komut: Bir veri bilimi koçu olarak hareket etmenizi istiyorum. "[Konu]" hakkında bilgi edinmek istiyorum. Lütfen en iyi 3 özel kaynağı önerin. "[kaynak türünü belirtin]" ifadesini ekleyebilirsiniz

## 43. Zaman Karmaşıklığını Önerin
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Lütfen aşağıdaki iki algoritmanın zaman karmaşıklığını karşılaştırın. `[İki işlev ekleyin]`

## 44. Özellik Mühendisliği Önerin
> İstem: Bir veri bilimci gibi hareket etmenizi ve özellik mühendisliği yapmanızı istiyorum. '[Özellik adını girin]'i öngören bir model üzerinde çalışıyorum. Sütunlar var: `[Sütunları açıkla]`. Bu makine öğrenimi sorununa yönelik geliştirebileceğimiz özellikler önerebilir misiniz?

## 45. Karın Testi Adımlarını Önerin
> Komut: Bir istatistikçi olarak hareket etmenizi istiyorum. `[Bağlamı açıklayın]` Lütfen bu amaç için bir A/B testi tasarlayın. Lütfen istatistiksel testi çalıştırmam gereken somut adımları ekleyin.

## 46. Kariyer Koçluğu
> Komut istemi: Bir kariyer danışmanı olarak hareket etmenizi istiyorum. '[rol adı]' olarak bir rol arıyorum. Arka planım `[...]`. Rolü nasıl ve hangi kaynaklarla 6 ay içinde tam olarak alabilirim?

# PROBLEM GİDERMEK
## 47. Kendi ChatGPT Kodunu Doğrulayın
> Uyarı: Yukarıdaki kodunuz yanlış. `[Neyin yanlış olduğunu belirtin]`. Tekrar dener misin?

## 48. Doğru Python Kodu
> İstem: Bir yazılım geliştiricisi olarak hareket etmenizi istiyorum. Bu kodun `[beklenen işlev]` olması gerekiyor. Lütfen çalıştırılamayan bu Python kodunda hata ayıklamama yardım edin. '[İşlev ekle]'

## 49. Doğru SQL Kodu
> İstem: SQL kod düzelticisi olarak hareket etmenizi istiyorum. Bu kod `[DBMS'niz, ör. PostgreSQL]`. Benim için düzeltebilir misin? `[SQL kodu burada]`

## 50. PowerBI Modelinde Sorun Giderme
Katkıda bulunanlar: [Mathias Halkjær Petersen](https://www.linkedin.com/in/mhalkjaer/)
> İstem: Power BI modelleyicisi olarak hareket etmenizi istiyorum. Şu anki projemin detayları burada. '[Ayrıntıları girin]'. Tabloda herhangi bir sorun görüyor musunuz?

#SQL YAZIN
## 51. Değişen Ortalama Oluşturun
> İstem: Bir veri bilimci gibi davranmanızı ve benim için SQL kodu yazmanızı istiyorum. İki sütunlu `[Sütun adlarını girin]' içeren bir tablom var. "[hangi değer]" için geçerli bir ortalama hesaplamak istiyorum. PostgreSQL 14 için çalışan SQL kodu nedir?

## 52. Leetcode Sorusunu Çöz
Katkıda bulunanlar: [DataLemur](www.datalemur.com)
> İstem: Size sütunlarla birlikte tablolar verildiğini varsayalım... Aşağıdaki çıktıyı alın... `[Data Lemur'dan Soru)`

# DİĞER KODU YAZIN
## 53. Google E-Tablolar Formülünü Yazın
> İstem: Google E-Tablolar formülünü oluşturan bir bot gibi davranmanızı istiyorum. Lütfen "[gereksinimleri açıklayın]" şeklinde bir formül oluşturun

## 54. R yaz
> İstem: R kullanan bir veri bilimci gibi davranmanızı istiyorum. "[Gereksinimi buraya ekleyin]" şeklinde bir R betiği yazabilir misiniz?

## 55. Kabuğu Yaz
> Komut: Bir Linux terminal uzmanı olarak hareket etmenizi istiyorum. Lütfen kodu "[gereksinimleri açıklayın]" bölümüne yazın

## 56. VBA'yı yaz
> İstem: Bir Excel VBA geliştiricisi olarak hareket etmenizi istiyorum. '[İşlevi buraya ekleyin]' şeklinde bir VBA yazabilir misiniz?

# ÇEŞİTLİ
## 57. Tabloları Biçimlendir
> İstem: Belge biçimlendirici olarak hareket etmenizi istiyorum. Lütfen aşağıdakileri Google Dokümanlar'a yerleştirmem için güzel bir tablo halinde biçimlendirir misiniz? `[metin tablosunu buraya ekleyin]`

## 58. Kitabı Özetle
> İstem: Teknik kitap özetleyicisi olarak hareket etmenizi istiyorum. Lütfen `[name]` kitabını 5 ana noktayla özetleyebilir misiniz?

## 59. Makaleyi Özetleyin
> Komut istemi: Bir akademisyen gibi hareket etmenizi istiyorum. Lütfen `[...]' makalesini basit terimlerle bir paragrafta özetleyin.

## 60. Duygusal Destek Sağlayın
> Komut istemi: Bana duygusal destek sağlamanızı istiyorum. `[Sorunu burada açıklayın.]'



