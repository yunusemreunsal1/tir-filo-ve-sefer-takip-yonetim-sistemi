Tır Filo ve Sefer Takip Yönetim Sistemi

Bu projede, lojistik firmalarının tır araçlarını, sürücülerini, yüklerini ve seferlerini ilişkisel bir veritabanında tutan, tırların sefer süreçlerini takip eden ve teslimat bilgilerini yöneten bir sistem geliştirilmesi amaçlanmaktadır.

Projenin hedefleri:

* Tır filo verilerini ilişkisel bir yapıda saklamak
* Tır ve sürücü bilgilerini yönetmek
* Tır seferlerini oluşturmak ve takip etmek
* Taşınan yüklerin bilgilerini kaydetmek
* Gönderici ve alıcı bilgilerini yönetmek
* Sefer rotalarını ve duraklarını takip etmek
* Tırların konum geçmişini kaydetmek
* Teslimat durumlarını takip etmek
* Tırların bakım kayıtlarını tutmak
* Yakıt kayıtlarını tutmak
* Geçmiş sefer ve teslimat bilgilerine erişmek

Sistemin Çalışma Akışı

Sistemde bir tır ve sürücü bir sefer ile ilişkilendirilir. Sefer için taşınacak yük, gönderici, alıcı ve rota bilgileri belirlenir.

Sefer başladığında tırın konum bilgileri ve sefer durumu sisteme kaydedilir. Rota üzerindeki duraklar takip edilir ve sefer boyunca oluşan konum bilgileri veritabanında tutulur.

Sefer tamamlandığında teslimat bilgileri sisteme işlenir. Böylece tamamlanan seferler ve teslimatlar geçmiş kayıtlar üzerinden görüntülenebilir.

Tırların bakım ve yakıt işlemleri de ilgili kayıtlarla birlikte sistemde tutulur.

Veritabanı Tabloları

* Tirlar
* Suruculer
* Seferler
* Yukler
* Gondericiler
* Alicilar
* Rotalar
* Duraklar
* Konum Takip
* Teslimatlar
* Bakimlar
* Yakit Kayitlari
