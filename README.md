# 🧠 KufurEngelPro AI v2

Minecraft sunucuları için geliştirilmiş ** AI destekli sohbet
koruma ve moderasyon pluginidir.**

Küfür, hakaret, tehdit, spam ve toksik davranışları analiz ederek
sunucunuzda daha temiz ve güvenli bir sohbet ortamı oluşturur.

------------------------------------------------------------------------

# ✨ Özellikler

## 🤖 Offline AI Toxic Analiz

-   Küfür algılama
-   Hakaret algılama
-   Tehdit algılama
-   Spam tespiti
-   Reklam engelleme
-   Toksik davranış analizi

> Harici API veya internet bağlantısı gerektirmez.

------------------------------------------------------------------------

## 🛡️ Gelişmiş Bypass Koruması

Oyuncuların filtreleri aşmasını engeller:
Büyük/küçük harf değişimlerini de algılar.

------------------------------------------------------------------------

# 📊 Toxic Score Sistemi

  Skor    Durum
  ------- -----------
  0-30    Temiz
  31-60   Şüpheli
  61-80   Uyarı
  81-95   Mute
  96+     Ağır Ceza

------------------------------------------------------------------------

# 🔇 Otomatik Ceza Sistemi

Sistem oyuncu davranışına göre:

-   Uyarı verir
-   Geçici mute uygular
-   Tekrarlayan ihlallerde ağır ceza uygular

------------------------------------------------------------------------

# 👤 Oyuncu Takip Sistemi

Oyuncuların:

-   İhlal sayısı
-   Toxic seviyesi
-   Ceza geçmişi
-   Son kayıtları

takip edilir.

------------------------------------------------------------------------

# 📝 Log Sistemi

Tüm işlemler kayıt altına alınır.

Konum:

    plugins/KufurEngelPro-AI-v2/logs.yml

------------------------------------------------------------------------

# ⚙️ Gereksinimler

## Sunucu

-   Paper / Purpur
-   Minecraft 1.20.4 - 1.21.x
-   Java 17+

## Önerilen Sistem

    CPU: 2+ Core
    RAM: 2GB+
    SSD Depolama

------------------------------------------------------------------------

# 📥 Kurulum Rehberi

## 1. Plugin Dosyasını Yükleyin

Dosya:

    KufurEngelPro-AI-v2.jar

Dosyayı:

    plugins/

klasörüne atın.

Örnek:

    Server
    ├── plugins
    │   └── KufurEngelPro-AI-v2.jar
    ├── world
    └── server.properties

------------------------------------------------------------------------

## 2. Sunucuyu Yeniden Başlatın

Sunucu açıldıktan sonra plugin otomatik olarak ayar dosyalarını
oluşturur.

Oluşan klasör:

    plugins/KufurEngelPro-AI-v2/

İçerik:

    config.yml
    ai-rules.yml
    toxic-words.yml
    messages.yml
    logs.yml

------------------------------------------------------------------------

# 🔐 Yetkiler

Admin:

    kufurengel.admin

Bypass:

    kufurengel.bypass

Kontrol:

    kufurengel.check

------------------------------------------------------------------------

# 🛠 Komutlar

Reload:

    /kufur reload

Oyuncu kontrol:

    /kufur check <oyuncu>

İstatistik:

    /kufur stats

------------------------------------------------------------------------

# 🧪 Test

Örnek test mesajları:

    amk
    a.m.k
    a m k

Plugin:

✅ Mesajı analiz eder\
✅ Toxic skor hesaplar\
✅ Ceza uygular\
✅ Log oluşturur

------------------------------------------------------------------------

# 🎮 Desteklenen Sunucular

-   Survival
-   Skyblock
-   Faction
-   Towny
-   Prison
-   RP Sunucuları
-   Büyük topluluk sunucuları

------------------------------------------------------------------------

# 🚀 Gelecek Özellikler

-   Web panel
-   MySQL desteği
-   Discord webhook
-   PlaceholderAPI
-   LiteBans entegrasyonu
-   Gelişmiş AI modeli

------------------------------------------------------------------------

# 📌 Destek

Sorun ve öneriler için GitHub üzerinden issue oluşturabilirsiniz.

⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!
