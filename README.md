📘 KufurEngelPro AI v2 Kurulum Rehberi

1️⃣ Gereksinimleri Kontrol Edin
Kurulumdan önce:
✅ Paper / Purpur 1.20.4 - 1.21.x
✅ Java 17+
✅ Sunucuya erişim (FTP veya dosya yöneticisi)

2️⃣ Plugin Kurulumu

1. İndirdiğiniz:
KufurEngelPro-AI-v2.jar

dosyasını açın.
2. Sunucu klasörünüzde bulunan:
/plugins

klasörüne yükleyin.

Örnek:
Minecraft Server
│
├── plugins
│   └── KufurEngelPro-AI-v2.jar
│
├── server.jar
└── world

3️⃣ Sunucuyu Başlatın
Sunucuyu tamamen yeniden başlatın.
İlk açılışta plugin kendi dosyalarını oluşturur:
plugins/
└── KufurEngelPro-AI-v2/
    ├── config.yml
    ├── ai-rules.yml
    ├── toxic-words.yml
    ├── messages.yml
    └── logs.yml

4️⃣ Ayarları Düzenleme
config.yml dosyasından:
- Ceza süreleri
- Toxic seviyeleri
- Mesajlar
- Filtre hassasiyeti
ayarlanabilir.
Örnek:
punishments:
  warning: true
  mute-time: 10m
  ban-after: 5

5️⃣ Yetkileri Verme
LuckPerms kullanıyorsanız:
Admin:
/lp user Oyuncu permission set kufurengel.admin true

Bypass:
/lp user Oyuncu permission set kufurengel.bypass true

6️⃣ Plugin Komutları
Ayarları yenileme:
/kufur reload

Oyuncu kontrol:
/kufur check OyuncuAdı

İstatistik:
/kufur stats

Plugin:
✅ Mesajı analiz eder
✅ Toxic skor hesaplar
✅ Gerekirse uyarı/mute uygular
✅ Log kaydı oluşturur  
8️⃣ Sorun Giderme
Plugin çalışmıyorsa:
Kontrol edin:
/plugins

listesinde:
KufurEngelPro-AI-v2

görünmeli.
