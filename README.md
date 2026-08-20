# Akış — YouTube Radyo

İndirmesiz, YouTube üzerinden akan, şarkı bitince Last.fm ile benzer bir
şarkı öneren kişisel radyo uygulaması. GitHub Pages üzerinden barındırılır,
telefonda "ana ekrana eklenebilir" uygulama gibi çalışır.

## GitHub Pages'e yükleme (git kullanmadan, tarayıcıdan)

1. github.com'da oturum aç, sağ üstten **New repository** ile yeni bir repo
   oluştur (örn. adı: `akis`). "Public" seç.
2. Repo sayfasında **Add file → Upload files** butonuna bas.
3. Bu klasördeki **tüm dosyaları** (index.html, manifest.json, sw.js,
   icon-192.png, icon-512.png, apple-touch-icon.png) sürükleyip bırak,
   sonra **Commit changes** de.
4. Repo'nun **Settings → Pages** sekmesine git.
5. "Build and deployment" altında **Branch**'i `main` / `/ (root)` olarak
   seç ve **Save** de.
6. Birkaç dakika bekle, sayfa tepesinde beliren
   `https://kullanici-adin.github.io/akis/` adresi senin kalıcı linkin.

## Telefonda "uygulama" gibi kurma

- **Android (Chrome):** Linki aç → sağ üstteki ⋮ menü → **"Ana ekrana ekle"**.
- **iPhone (Safari):** Linki aç → paylaş ikonu → **"Ana Ekrana Ekle"**.

Bu şekilde eklendiğinde tarayıcı çubuğu olmadan, kendi ikonuyla, tam ekran
bir uygulama gibi açılır.

## İlk kullanım

Uygulamayı ilk açtığında üstteki "API anahtarları" kısmına kendi ücretsiz
YouTube Data API v3 ve Last.fm API anahtarlarını gireceksin — bu anahtarlar
yalnızca o telefonun/tarayıcının hafızasında saklanır, GitHub'a veya
başka bir yere gitmez.
