# 🧩 BozYap - Yeni Nesil Multimedya Bulmaca 

BozYap, klasik yapboz (puzzle) oyunlarını modern medya öğeleri ve sosyal etkileşim özellikleriyle baştan yaratan yenilikçi bir mobil uygulamadır. Durağan fotoğrafların ötesine geçerek; **videoları, müzikleri ve şifreli sürprizleri** interaktif birer bulmacaya dönüştürür.

Flutter ile sıfırdan ve "Clean Architecture" prensiplerine uygun olarak geliştirilmiştir.

---

## ✨ Öne Çıkan Özellikler

### 🎬 Multimedya Bulmacaları
* **Fotoğraf:** Galerinizden seçtiğiniz herhangi bir görseli anında parçalara ayırın.
* **Video:** Arka planda oynamaya devam eden hareketli videolarla yüksek dinamizm ve zorluk elde edin.
* **Müzik (Ses Dalgaları):** Telefonunuzdan seçtiğiniz bir müzik veya ses dosyasını (mp3) anında renkli bir **dijital spektruma** dönüştürün. Müziğin ritmini dinleyerek ses dalgalarını birleştirin!

### 💌 Sürpriz Mesaj Modu (Viral Sosyal Etkileşim)
Arkadaşlarınıza standart bir mesaj atmak yerine, onlara "şifreli bir hediye" gönderin!
1.  Görselinizi seçin ve gizli mesajınızı yazın (Örn: *"İyi ki doğdun!"*).
2.  Sistem size benzersiz bir kod üretir (Örn: `BOZYP-X7B2`).
3.  Arkadaşınız kodu girdiğinde bulmaca başlar. Bulmacayı tamamen çözmeden fotoğrafı göremez.
4.  Çözüm bittiğinde konfetiler patlar ve gizli mesajınız ekranda belirir.

### 🌍 Günün Bulmacası (Unsplash API)
Her gün saat 00:00'da Unsplash API üzerinden dünyadaki tüm oyunculara aynı kalitede, yepyeni bir HD doğa/manzara bulmacası sunulur. Cihaz önbellekleme (caching) sistemi sayesinde veri tasarrufu sağlar.

### 🎨 50 Farklı Renk Filtresi
Matris (ColorFilter) algoritmaları kullanılarak cihazı yormadan fotoğraflara ve videolara anında 50 farklı filtre (Çizgi Film, Negatif, Kış, Neon vb.) uygulanabilir.

### 🧩 Kusursuz Kenetlenme (Interlocking)
Parçalar rastgele değil, matematiksel *Girinti (-) ve Çıkıntı (+)* mantığına göre üretilir. Hem "Klasik" kıvrımlı kesimde hem de "Geometrik" asimetrik kesimde parçalar birbirinin içine anahtar-kilit gibi kusursuzca oturur.

---

## 🎮 Oynanış ve Mekanikler

* **Zorluk Seviyeleri:** Başlangıç (3x3), Orta (5x5), Zor (8x8) ve Uzman (10x10).
* **Hafıza Modu (Blind Mode):** Görsel sadece ilk 5 saniye gösterilir, ardından oyuncu bulmacayı tamamen hafızasından çözmek zorunda kalır.
* **Zamana Karşı:** Belirlenen süre kısıtlamaları içinde adrenalini yüksek oyun deneyimi.
* **Tasarla ve Paylaş:** Oyun bittiğinde standart bir skor tablosu yerine; arka plan renginin ve çerçeve kalınlığının kullanıcı tarafından ayarlanabildiği estetik bir tasarım ve paylaşım ekranı açılır.
* **Geri Tuşu Koruması:** Fiziksel geri tuşuna yanlışlıkla basıldığında emeklerin boşa gitmemesi için `PopScope` ile güvenlik katmanı.

---

## 🛠️ Teknik Altyapı ve Kullanılan Paketler

Proje, sürdürülebilirliği artırmak ve "Spagetti Kod" oluşumunu engellemek amacıyla **Clean Architecture** mantığıyla modüllere (Pages, Services, Models vb.) ayrılmıştır.

**Kullanılan Temel Teknolojiler:**
* **Flutter & Dart** (SDK: ^3.9.2)
* **audio_players:** Tıklama (ASMR) ve arka plan müzik yönetimi.
* **video_player:** Hareketli video bulmacaları için.
* **shared_preferences:** Geçmiş (History) arşivi ve lokal veritabanı simülasyonu.
* **http:** Günün bulmacası için RESTful API istekleri (Unsplash).
* **google_mobile_ads:** Ödüllü reklam sistemi (İpucu mekaniği).
* **screenshot & share_plus:** Özelleştirilebilir ekran görüntüleri alma ve sosyal medyada paylaşma.

---

## Görseller
<img width="363" height="647" alt="image" src="https://github.com/user-attachments/assets/a0025d15-1093-4466-b818-096cc4492b3c" />
<img width="365" height="648" alt="image" src="https://github.com/user-attachments/assets/ecc535e4-6248-4c21-9e68-ef5d4b99a4f5" />
<img width="367" height="652" alt="image" src="https://github.com/user-attachments/assets/eae9617e-3ff4-404b-995f-fb8397b999e2" />
<img width="365" height="647" alt="image" src="https://github.com/user-attachments/assets/09b1e239-9e31-49ee-aa0b-1c8eb688fcaf" />
<img width="365" height="653" alt="image" src="https://github.com/user-attachments/assets/3b57ebb1-e033-48ec-bcba-a916c605f4c6" />
<img width="367" height="648" alt="image" src="https://github.com/user-attachments/assets/83e07bae-b8a1-4a22-91b7-c53fc51261e5" />
<img width="363" height="650" alt="image" src="https://github.com/user-attachments/assets/07c2f34f-5776-4b3d-8977-47421ad595ee" />
<img width="366" height="652" alt="image" src="https://github.com/user-attachments/assets/803c1bac-aa67-47f3-814d-4154d9eba211" />
<img width="368" height="655" alt="image" src="https://github.com/user-attachments/assets/d37cd979-432f-4223-a6d8-fd47dc391ca0" />

**Geliştirici:** Elif Nur Ayhan
