# HumaFall site paketi

İçerik: `index.html` (tanıtım sitesi), `v/` (video ve görseller), `oyun/` (oyun), `_headers`, `robots.txt`.

## Netlify (sürükle-bırak)
1. app.netlify.com adresinde Sites sayfasını aç.
2. Bu zip'i açıp klasörü (ya da zip'i) "Drag and drop" alanına bırak.
3. Yayına girince verilen adresi aç; `_headers` otomatik uygulanır.

## Cloudflare Pages
1. Workers & Pages > Create > Pages > "Upload assets".
2. Proje adı ver, zip'i açılmış klasörü yükle, Deploy et.
3. `_headers` desteklenir.

## GitHub Pages
1. Yeni depo oluştur, bu klasörün içeriğini kök dizine yükle (index.html kökte olmalı).
2. Settings > Pages > Source: branch (main) / root.
3. Not: GitHub Pages `_headers` dosyasını uygulamaz; önbellek ve nosniff başlıkları ayarlanamaz. Site yine çalışır. Gerekirse kökte boş `.nojekyll` dosyası ekle.

## Alan adı
Barındırıcının Domains/Custom domain bölümünden alan adını ekle, DNS'te CNAME (www) veya barındırıcının verdiği A/ALIAS kaydını gir. Alan adı belli olunca sitemap.xml eklenebilir (şimdilik yok).

## Bilinen sınırlar
- Sıralama bölümü boş.
- Mağaza rozetleri "Yakında".
- Oyun skorları yalnızca oyuncunun cihazında tutulur.
- Sosyal medya bağlantıları (Instagram, TikTok, YouTube) doğrulanmadı.
- Google Fonts internetten yüklenir; çevrimdışıysa yedek yazı tipleri kullanılır.
