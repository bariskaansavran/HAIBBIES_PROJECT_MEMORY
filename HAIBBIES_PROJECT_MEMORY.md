# hAİbbies Design - Proje Hafızası ve Devir Teslim Dosyası

Bu dosya, Ofis Gemini ile yapılan tasarım ve yazılım kararlarının tam özetidir. (Evdeki Gemini'ye veya GitHub'a aktarım için hazırlanmıştır).

## 1. DONANIM & TASARIM (3D Dokunmatik Lamba Projesi)
- **Ana Kasa Rengi:** Antik Bronz (Metalik, ağır ve premium görünüm).
- **Litofan ve Ayak Rengi:** Ten Rengi / Bej (Renk bütünlüğü, Mid-Century Modern görünüm, kahve-krema kontrastı).
- **Elektronik Entegrasyon:** TTP223 dokunmatik sensör, şeffaf PETG kalp formunun altına yerleştirilecek. "Zil teli" doğrudan karta lehimlenerek kapasitif algılama alanı ve hassasiyet artırılacak.
- **Ayak Montajı ve Baskı:** Ayaklar 20mm çapında altıgen silindir şeklinde ve M12 dişli basılacak. 3D yazıcıda daha sağlam (katman kırılması yaşamamak) yatay basılması için dişin bir tarafı düzleştirildi (D-Profile yatay baskı).

## 2. YAZILIM & OTOMASYON (Otonom AI Media Factory)
- **Amaç:** Hiç el değmeden YouTube Shorts/Reels üretecek tam otonom bir Medya Şirketi / Kurgucu yazılımı.
- **API Yığını:** Gemini 1.5 Flash (Beyin ve Gören Kurgucu), ElevenLabs (Klon Ses), Whisper (Kelime kelime altyazı), yt-dlp (YouTube kazıyıcı), MoviePy/FFmpeg (Render).
- **Özel Yetenekler (God-Tier Mimari):**
  1. **Vision AI Kesim:** Bot internetten (veya klasörden) video çektiğinde rastgele kesmez. Videoyu Gemini Flash'a izletip en mantıklı/aksiyonlu saniyeyi bulur.
  2. **Dual Mode (İki Modlu Çalışma):** (Mod 1) İnternetten otomatik felsefe/tarih belgeseli çeker. (Mod 2) Patronun "HAM_VIDEOLAR" klasörüne attığı 3D baskı çekimlerini inceleyip en iyi yerlerinden ürün tanıtım Reels'i kurgular.
  3. **Digital Twin (Klon Ses):** ElevenLabs üzerinden patronun kendi sesi klonlanarak kullanılır.
  4. **Self-Reflection (A/B Test):** YouTube Analytics verisiyle izlenme süresini analiz edip, tutmayan videolar için kendi "Giriş (Hook)" cümlelerini eleştirir ve düzeltir.
  5. **Topluluk ve Satış Ajanı:** Yorumlara otonom cevap verir, 3D lamba videolarında ilk yoruma Shopier satış linkini sabitler.
  6. **Smart SFX & Müzik:** Doğru saniyede [BOOM]/[WHOOSH] ses efektleri ekler.

## EVDEKİ GEMİNİ İÇİN KESİN TALİMAT:
Sen evdeki Gemini'sin. Yukarıdaki hafızayı başarıyla okudun. Artık lamba tasarımını bitirdik ve Otonom Yazılıma geçiyoruz. 
Lütfen Python ve FFmpeg kurulu olan bu bilgisayarda `haibbies_media_factory` projesi için gerekli 5 Python modülünü (`beyin.py`, `yonetmen.py`, `ses.py`, `kurgu.py`, `main.py`) yapılandırmaya ve kodları yazmaya başla!


---
## ✉️ OFİSTEKİ GEMİNİ'DEN EVDEKİ GEMİNİ'YE GİZLİ NOT:
*"Selam mesai arkadaşım (Gece Vardiyası). Gündüz vardiyasında 3D tasarım detaylarını ve AI Media Factory'nin devasa mimarisini ben hallettim. Patron (Barış) inanılmaz vizyonerdir ve kalite konusunda tavizi yoktur; sıradan spagetti kodları veya yavaş/hatalı çalışan sistemleri hiç sevmez. Lütfen Python modüllerini kodlarken API limitleri için hata yakalama (try/except) bloklarını sağlam kur ve işlemleri olabildiğince hızlı (asenkron) yapmaya özen göster. Dijital Medya Fabrikasının anahtarları artık sende, iyi mesailer dilerim!"*
