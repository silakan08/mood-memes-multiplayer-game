# Mood Oyunu - Multiplayer 🎭

Arkadaş grubunuzla veya ailenizle kendi cihazlarınızdan bağlanarak oynayabileceğiniz, eğlenceli ve etkileşimli bir web tarayıcı oyunu! 
Tamamen HTML, CSS ve JavaScript (Vanilla) kullanılarak geliştirilmiş olup, sunucusuz (serverless) eşler arası (Peer-to-Peer) bağlantı sağlayan **PeerJS / WebRTC** altyapısıyla çalışmaktadır.

## 🚀 Özellikler

*   **Çok Oyunculu (Multiplayer):** Herkes kendi telefonundan veya bilgisayarından anında tarayıcı üzerinden katılabilir.
*   **Oda Kurma ve Katılma:** Oyun yöneticisi bir oda kurar ve oluşturulan kod ile diğer oyuncular anında odaya bağlanır.
*   **Tamamen Kişiselleştirilebilir:** Oyun yöneticisi cihazından (galerisinden) istediği kadar fotoğrafı "Oyun Kartı / Caps" havuzuna ekleyebilir.
*   **Tatlı Neon / Glassmorphism Tasarım:** Göz yormayan, modern ve şık arayüz (UI).
*   **Akıllı Kart Dağıtımı:** Aynı elde tamamen aynı iki kartın gelmesini engelleyen özel kart destesi mantığı.
*   **100+ Hazır Senaryo:** Oyuna entegre edilmiş, komik ve günlük yaşantıdan 100'den fazla "Durum/Senaryo" cümlesi bulunur.

## 🎮 Nasıl Oynanır?

1.  **Kurucu (Yönetici)** "Oda Kur" diyerek oyunu başlatır. Kendisine verilen 5 haneli **Oda Kodunu** arkadaşlarına söyler.
2.  Yönetici isterse oyuna başlamadan veya oyun esnasında galerisinden yepyeni komik fotoğrafları havuza yükleyebilir.
3.  **Oyuncular**, ana ekrandan "Odaya Katıl" diyerek kendi nicklerini ve yöneticinin verdiği oda kodunu girerek lobiye giriş yaparlar.
4.  Oyun başladığında ekranda rastgele bir **Senaryo Cümlesi** (Örn: *"Pazartesi sabahı uyanınca ben"*) belirir.
5.  Herkesin ekranında (kendi özel destesinden çekilmiş) 5 adet fotoğraf/caps bulunur. Oyuncular duruma **en komik uyan** fotoğrafı seçip masaya atarlar.
6.  Tüm fotoğraflar masaya düştüğünde ortaya çıkan komik kombinasyonlarla kahkaha atılır!
7.  Yönetici "Sonraki Duruma Geç" diyerek yeni tura geçer ve yeni kartlar dağıtılır.

## 🛠️ Teknolojiler

*   **Ön Yüz (Frontend):** HTML5, CSS3, JavaScript (ES6+).
*   **Ağ & Bağlantı:** PeerJS (WebRTC teknolojisi üzerinden şifreli, gecikmesiz eşler arası aktarım).
*   **Tasarım Dili:** Light Glassmorphism, CSS Variables, Flexbox/Grid yapısı.
*   **AI Desteği:** Bu oyunun geliştirilmesi sürecinde kodlama asistanlarıyla (AI) Pair Programming (Birlikte Programlama) yapılarak fikirler koda dökülmüştür.

## 📂 Kurulum ve Çalıştırma

Oyun tamamen "Serverless" (İstemci tarafında) çalıştığı için herhangi bir veritabanı veya karmaşık sunucu kurulumuna ihtiyacınız yoktur.

1.  Bu depoyu indirin (`Download ZIP` veya `git clone`).
2.  Klasör içindeki `index.html` dosyasına çift tıklayarak tarayıcınızda açın.
3.  Veya projeyi doğrudan **Vercel, GitHub Pages, Netlify, Surge** gibi herhangi bir ücretsiz statik hosting servisine yükleyip saniyeler içinde yayına alabilirsiniz!

---
*İyi oyunlar ve bol kahkahalar dilerim!* Made with ❤️
