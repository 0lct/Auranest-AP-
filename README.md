# Discord Api ve Auracord-main
Bu repoda iki farklı sistemin detaylı açıklamalarını, kurulum adımlarını ve çalışma prensiplerini bulabilirsiniz.

# Discord Api
# Amaç
Discord Api, Discord sunucuları için kullanıcı ve sunucu aktivitelerini izleyen, güncelleyen ve çeşitli otomasyonlar sağlayan bir Node.js tabanlı API sistemidir.

# Özellikler
Kullanıcı güncellemeleri (kullanıcı adı, profil resmi vs.)
Sunucuya katılan/ayrılan üyelerin takibi
Sesli kanala giriş/çıkış güncellemeleri
Webhook ile bildirimler
MongoDB ile veri saklama
Kurulum
Depoyu klonla veya dosyaları indir.
Komut satırında Discord Api klasörüne gir:
cd "Discord Api"
modules'leri yükle:
npm install
Ayarları yap: config.json dosyasını düzenleyerek gerekli API anahtarlarını ve bağlantı bilgilerini gir.
Başlat:
node API.js
Çalışma Şekli
Sistem başlatıldığında Discord sunucusundaki aktiviteleri otomatik olarak izler ve günceller.
Webhook ile belirlenen kanallara bildirim gönderir.
Dosya Yapısı
API/ : Ana API dosyaları
Models/ : MongoDB modelleri
src/ : Ekstra yardımcı dosyalar ve güncellemeler
