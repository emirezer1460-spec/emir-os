EMIR OS — Hızlı Not (ilk PWA sürümü)

İçerik:
- index.html: hızlı not arayüzü
- manifest.webmanifest: ana ekrana eklenebilir uygulama tanımı
- sw.js: temel çevrimdışı önbellek
- icon.svg: uygulama simgesi

Önemli:
1. Ana ekrana uygulama gibi eklemek için dosyaları HTTPS destekleyen bir web sunucusunda yayınlamak gerekir. Yalnızca index.html dosyasını indirip açmak, kurulu PWA deneyimi sağlamaz.
2. Notlar şimdilik cihazdaki tarayıcının localStorage alanında saklanır. Bulut senkronizasyonu yoktur.
3. Yayınlandıktan sonra tabletinde siteyi açıp tarayıcı menüsünden "Ana ekrana ekle" / "Add to Home screen" seçeneğini kullan. Seçenek ve davranış HarmonyOS sürümüne/tarayıcıya göre değişebilir.
4. Bir sonraki aşama: HTTPS ile yayınlama, ardından aynı notları tablet ve bilgisayarda kullanmak için hesap ve bulut veritabanı eklemek.
