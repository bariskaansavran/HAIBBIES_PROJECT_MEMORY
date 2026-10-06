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


## 3. OTONOM YAPAY ZEKA ŞİRKETİ MİMARİSİ (GÜN 2 GÜNCELLEMESİ)
Dün geceki Ar-Ge (Hermes ve Google Cloud) çalışmaları sonucunda şirketin vizyonu ve mimarisi devasa bir seviyeye atladı. Sistem artık basit bir script değil, sanal bir şirkettir.

**Kullanılacak Teknolojiler & Altyapı:**
- **CrewAI (Şirket İskeleti):** Şirketin hiyerarşik altyapısı (CEO ve Çalışanlar) tamamen bu resmi ve açık kaynak kütüphane üzerine kurulacak.
- **Telegram Bot Entegrasyonu (Tony Stark Mimarisi):** Sistemin "Uzaktan Kumandası". Ofisteki veya yoldaki patron (Barış), Telegram üzerinden evdeki CEO ajana metinle emirler verecek, biten işleri (videoları) Telegram'dan teslim alacak. Bilgisayar dışarıya açılmayacak, %100 güvenli ağ olacak.
- **Google Cloud (Vertex AI) 300$ Kredi:** Şirketin ana beyni olarak Anthropic **Claude 3.5 Sonnet**, gören gözü (video analiz) olarak **Gemini 1.5 Flash**, seslendirmeni olarak Cloud TTS kullanılacak. Toplam Maliyet: 0 TL.
- **Yerel LLM (Hermes vb.):** Alternatif olarak, internetsiz ve API'siz metin/senaryo üretiminde bilgisayarın kendi GPU'su kullanılacak.

**Şirket Departmanları (Ajan Rolleri):**
1. **Medya & Pazarlama Departmanı (Tam Otonom):** Patronun klasöre attığı "Ham 3D Baskı Videolarını" alır; kurgular (FFmpeg/MoviePy), seslendirir, altyazı basar, YouTube/Reels açıklamalarını yazar ve teslim eder.
2. **Ar-Ge ve 3D Tasarım Departmanı (Yarı Otonom / Asistan):** Patronun *"Bana altıgen vazo konsepti çalış"* emriyle bilgisayardaki Blender'ı (Python `bpy` koduyla) arka planda çalıştırır. Kabataslak temel geometriyi (Base Mesh) çizer, `.blend` olarak `ARGE_TASARIMLAR` klasörüne kaydeder. Pah kırma, ince ayarlar ve son baskı kalitesi (QA/Slicer) tamamen Patrondadır. Yapay zeka sadece sıfırdan "Kaba İnşaat" çizerek saatler kazandırır.
