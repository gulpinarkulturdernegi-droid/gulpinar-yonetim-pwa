# Gülpınar Derneği PWA

Bu paket, mevcut Blogger sitesine hiçbir dosya veya kod eklemeden ayrı bir PWA uygulama kabuğu oluşturur.

## GitHub Pages'e yükleme
1. GitHub'da `gulpinar-dernek-pwa` adlı **Public** bir repository oluşturun.
2. ZIP içindeki dosyaları (klasörün kendisini değil, içindekileri) repository'nin kök dizinine yükleyin.
3. Commit changes yapın.
4. Repository > Settings > Pages bölümüne girin.
5. Build and deployment altında Deploy from a branch seçin.
6. Branch: `main`, Folder: `/(root)` seçip Save'e basın.
7. Pages adresi yayınlandığında HTTPS üzerinden açın.

## Bilgisayara yükleme
1. GitHub Pages adresini Chrome veya Edge ile açın.
2. Tarayıcıdaki yükle simgesini veya menüdeki "Uygulamayı yükle" seçeneğini kullanın.
3. Uygulama adı Gülpınar Derneği olacaktır.

## Önemli sınır
Bu PWA, GitHub Pages üzerinde çalışan bağımsız bir uygulama kısayoludur. "Yönetim Sistemini Aç" düğmesi mevcut Blogger sistemini ayrı sekmede açar. Blogger'ın tüm yönetim ekranlarını bu PWA penceresinin içine gömmek, Blogger'ın çerçeve/güvenlik politikalarına bağlıdır ve bu paket bunu varsaymaz. PWA kabuğu çevrimdışı açılabilir; Blogger yönetim sistemi internet bağlantısı gerektirir.

GitHub Pages herkese açık yayın yapar. Bu depoya şifre, API anahtarı, üye listesi, T.C. kimlik numarası veya özel dernek verisi koymayın.
