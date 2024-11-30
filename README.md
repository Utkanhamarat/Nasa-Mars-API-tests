# Nasa-Mars-API-tests

**KULLANILAN TEKNOLOJILER**

Postman: API isteklerini test etmek ve senaryolar oluşturmak için.
Newman: Otomasyon ve raporlama süreçlerinde.
GitHub: Proje dokümantasyonu ve paylaşımı için.

PROJE ILE KAZANILAN BECERILER:

API testi ve hata senaryoları oluşturma becerisini kazandım.
Postman ve Newman ile test otomasyonu süreçlerini yönetme becerisini kazandım.
Dinamik ve eksik veri durumlarını yönetme yetkinliğini kazandım.
JSON, HTML formatında raporlama pratikliği ve yetkinliğini elde ettim.

PROJELERIMDE: Postman ile test koleksiyonları oluşturulmuş ve environment değişkenleri kullanılarak API test süreçleri daha dinamik ve sürdürülebilir hale getirilmiştir. Bu çalışma, API testi ve otomasyon konusundaki becerilerimi sergilemektedir.

25.10.2024 - 27.10.2024 Tarihleri arasında Bu projeyi tamamladım.


--Landsat Satellite--

NASA'nın Planetary Photojournal API'si kullanılmıştır. Bu API, gezegenlerle ilgili görsel ve meta veriye erişim sağlayan bir araçtır. 
Bu Projede NASA'nın açık kaynaklı API'sini kullanarak Dünya'nın herhangi bir bölgesinin uydu görüntüsü elde etmek istenmiştir.
İstenilen coğrafi bölgenin uydu görüntüsünü başarılı bir şekilde elde ettim (2024-10-17 tarihinde Las Vegas'ın uydu görüntüsünü elde ettim).

-Dinamik API Key Yönetimi: API anahtarını güvenli bir şekilde yönetmek için environment değişkenleri kullanıldı.
-Görsel Veriye Erişim: Belirli tarih ve koordinat bilgileriyle görsel veri sorgulama test edildi.
-Postman: API istekleri manuel olarak test edildi, hata senaryoları analiz edildi.
-Newman: Test koleksiyonları otomatikleştirilerek, JSON ve HTML formatında raporlar oluşturuldu.
-Başarılı yanıt kontrolü: Yanıtların 200 OK durum kodu döndürdüğünü doğrulayan testler yazdım.


Dosyalar:
Postman Koleksiyonu: (LandsatSatellite.postman_collection.json)
Environment Dosyası: (MarsEnvironment.postman_environment.json)
Test Raporları: Json => (LandsatSatelliteNEWMANtest.json), HTML => (LandsatSatelliteNEWMANtest.html)


--Mars Rover Photos--
Bu proje, NASA'nın Mars Rover Photos API'sini kullanarak API test süreçlerini otomatikleştirmeyi ve raporlamayı amaçlamaktadır. Mars yüzeyindeki Rover tarafından çekilen fotoğraflara erişim sağlar. Kullanıcılar, fotoğrafları belirli parametreler (sol - Mars günü, Dünya tarihi) ile sorgulayabilir. Proje, API test becerilerini, otomasyon süreçlerini ve detaylı raporlama, Postman ve Newman kullanılarak API testlerini yürütme, hataları ayıklama ve sonuçları raporlama konularında becerilerimi göstermektedir.

-Mars Günü (Sol) ile Fotoğraf Sorgulama: Belirli bir sol günü için fotoğraf verilerinin doğru şekilde döndürüldüğü test edildi.
-Kamera ve Sayfalama Parametreleri: API’nin kamera türü ve sayfalama parametreleri ile uyumluluğu doğrulandı.
-Postman: API istekleri manuel olarak test edildi ve test koleksiyonları oluşturuldu.
-Newman: Test koleksiyonları otomatik çalıştırıldı ve JSON ile HTML formatında raporlar oluşturuldu.
-Başarılı yanıt kontrolü: Yanıtların 200 OK durum kodu döndürdüğünü doğrulayan testler yazdım.


Dosyalar:
Postman Koleksiyonu: (MarsRoverPhotos.postman_collection)
Environment Dosyası: (MarsEnvironment.postman_environment.json)
Test Raporları: Json => (MarsRoverPhotosNEWMANtest.json), HTML => (MarsRoverPhotosNEWMANtest.html), Run Collection => (Mars Rover Photos.postmanRUNCOLLECTIONtest.json)


--Mars Weather--
NASA’nın InSight Mars hava durumu API’sini kullanarak, Mars yüzeyinde ölçülen sıcaklık, rüzgar ve basınç verilerini test etmek ve doğrulamak amacıyla bir test gerçekleştirdim. API, Elysium Planitia’da (Mars’ın ekvatoruna yakın düz ve pürüzsüz bir bölge) kaydedilen son yedi Sol’a (Mars Günü) ait özet hava durumu verilerini sağlamaktadır. Proje, API’nin veri doğruluğunu, eksik verileri ve sensör hatalarını yönetme yeteneklerini analiz etmeyi hedeflemektedir. 

-Postman ile API istekleri manuel olarak test ettim.
-Newman kullanılarak test koleksiyonları otomatikleştirilmiş ve JSON ile HTML formatında raporlar oluşturdum.
-Son 7 Sol verisi: API’nin en güncel Mars hava durumu özetlerini doğru şekilde sunduğu test edilmiştir.
-API’nin dinamik yapısı gereği, sürekli güncellenen verilerle uyumluluğu doğrulanmıştır.
-Başarılı yanıt kontrolü: Yanıtların 200 OK durum kodu döndürdüğünü doğrulayan testler yazdım.


Dosyalar:
Postman Koleksiyonu: (MarsWeather.postman_collection.json)
Environment Dosyası: (MarsEnvironment.postman_environment.json)
Test Raporları: Json => (MarsWeatherNEWMANtest.json), HTML => (MarsWeatherNEWMANtest.html), Run Collection => (Mars Weather.postmanRUNCOLLECTIONtest.json)


--Nasa Mission Call--
NASA’nın Mission Call API’sini kullanarak, uzay görevleri hakkında bilgi sağlayan API’nin test edilmesi ve otomasyon süreçlerinin geliştirilmesi üzerine bir proje gerçekleştirdim. Bu proje kapsamında, farklı görev bilgilerini sorgulayarak API’nin veri doğruluğunu, yanıt süreleri ve hata senaryolarına dayanıklılığı incelenmiştir. Proje, API test süreçlerini manuel ve otomatik olarak yürütme ve detaylı raporlama yetkinliklerimi sergilemektedir.

-Görev Bilgileri Sorgulama: Uzay görevleri hakkında genel bilgilerin doğru şekilde döndürüldüğünü doğrulamak için testler oluşturdum.
-Newman ile test koleksiyonları otomatikleştirilmiş ve test sonuçları JSON ve HTML formatında raporladım.
-Başarılı yanıt kontrolü: Yanıtların 200 OK durum kodu döndürdüğünü doğrulayan testler yazdım.
-Newman kullanılarak test koleksiyonları otomatikleştirilmiş ve JSON ile HTML formatında raporlar oluşturdum.


Dosyalar:
Postman Koleksiyonu: (NasaMissioncall.postman_collection.json)
Environment Dosyası: (MarsEnvironment.postman_environment.json)
Test Raporları: Json => (NasaMissioncallNEWMANtest.json), HTML => (NasaMissioncallNEWMANtest.html), Run Cmollection => (Nasa Mission call.postmanRUNCOLLECTIONtest.json)
