# ⚽ Mat-Bol — Matematik Futbolu 🧮

Mat-Bol, matematiksel zekanızı ve futbol stratejinizi bir araya getiren, tarayıcı tabanlı, dinamik ve eğlenceli bir single-page (tek sayfa) web oyunudur. Oyuncular, seçtikleri takımlarla sahaya çıkarak pas, şut ve dripling gibi futbol aksiyonlarını gerçekleştirmek için zamana karşı matematik sorularını doğru yanıtlamak zorundadır.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

---

## 🌟 Öne Çıkan Özellikler

* **Akıcı ve Premium Arayüz:** Stadyum projektör atmosferi, hareketli saha çizgileri ve neon görsel efektlerle zenginleştirilmiş modern karanlık mod (Dark Mode) tasarımı.
* **Gerçekçi Futbol Mekanikleri:** * **Yazı-Tura Atışı:** Maça kimin başlayacağını belirleyen interaktif yazı-tura ekranı.
    * **Stratejik Aksiyonlar:** Top sizdeyken Pas, Şut veya Dripling yapma; savunmadayken ise rakibin atağını kesme hamleleri.
    * **Dinamik Saha ve Top:** Topun sahada gerçek zamanlı konum değiştirmesi ve pozisyona göre parlayan hedef bölgeler.
* **Gelişmiş Matematik Motoru:**
    * **5 Farklı Zorluk Seviyesi:** *Çok Kolay, Kolay, Orta, Zor, Çok Zor* ve en üst seviye olan *Champs League*.
    * **Zamana Karşı Yarış:** Her soru için zorluk derecesine göre dinamik olarak azalan süre barı.
    * **Dahili Numaratör (Numpad):** Mobil cihazlarla tam uyumlu, negatif sayı desteği ve silme özellikli şık klavye arayüzü.
* **Ses Efektleri ve Kontroller:** Maç içi heyecanı artıran ses efektleri (düdük, direk sesi vb.) ve açılıp kapatılabilir ses ayarları paneli.
* **Mobil Öncelikli (Responsive) Tasarım:** Mobil cihazlarda taşma yapmayan, güvenli alan (viewport-fit=cover) ve tam ekran odaklı kompakt yapı (maksimum 480px genişlik).

---

## 🎮 Oyun Nasıl Oynanır?

1.  **Ayarları Yapın:** Ana menüden zorluk seviyesini seçin ve ses ayarlarını kontrol edin.
2.  **Takımınızı Seçin:** Kendi takımınızı ve rakibinizi belirleyin.
3.  **Yazı-Tura Atın:** Maçın ilk vuruşunu (Kickoff) kimin yapacağını belirlemek için yazı-tura atışını gerçekleştirin.
4.  **Hücum ve Savunma:**
    * **Hücumda:** Top sizdeyken yapmak istediğiniz aksiyonu (Pas/Dripling/Şut) seçin ve karşınıza çıkan matematik sorusunu süre bitmeden doğru cevaplayın. Doğru cevap topu ileri taşır veya gol olmasını sağlar!
    * **Savunmada:** Rakip takım atağa kalktığında, savunma sorusunu doğru çözerek topu kapmaya ve kalenizi korumaya çalışın.
5.  **Penaltı ve Direk Pozisyonları:** Maçın gidişatına göre penaltı atışları veya direkten dönen toplarla oyunun heyecanını yaşayın.

---

## 🛠️ Kullanılan Teknolojiler

Oyun, herhangi bir harici kütüphane veya framework (React, Vue, jQuery vb.) kullanılmadan **Pure Vanilla Stack** ile geliştirilmiştir:

* **Semantik HTML5:** Oyun ekranları arası geçiş ve oyun yapısının kurgulanması.
* **Modern CSS3:** `CSS Variables` (Değişkenler), `radial-gradient` atmosfer efektleri, `clip-path` ile dinamik takım logoları ve akıcı `keyframes` animasyonları.
* **Modern JavaScript (ES6+):** Durum yönetimi (State management), dinamik soru üretme algoritması, zamanlayıcılar (`setTimeout`/`setInterval`) ve oyun içi mantıksal döngüler.
* **Google Fonts:** Projede esnek ve güçlü bir tipografi için *Bebas Neue* ve *DM Sans* fontları kullanılmıştır.

---

## 🚀 Kurulum ve Çalıştırma

Proje tamamen istemci taraflı (client-side) çalıştığı için herhangi bir sunucu kurulumuna veya bağımlılık yüklemesine gerek yoktur.

1.  Bu depoyu bilgisayarınıza indirin veya klonlayın:
    ```bash
    git clone [https://github.com/tolgahalilaltay/mat-bol.git](https://github.com/tolgahalilaltay/mat-bol.git)
    ```
2.  Proje klasörüne gidin:
    ```bash
    cd mat-bol
    ```
3.  `index.html` dosyasını herhangi bir modern web tarayıcısında (Chrome, Edge, Safari, Firefox vb.) çift tıklayarak açın ve oynamaya başlayın!

---

## 📝 Lisans

Bu proje **MIT Lisansı** altında lisanslanmıştır. Daha fazla bilgi için `LICENSE` dosyasına göz atabilirsiniz.

---

## 💡 Katkıda Bulunma

Projeyi daha da geliştirmek için katkılarınızı bekliyoruz!
1. Bu depoyu fork edin.
2. Yeni bir özellik veya hata düzeltmesi için bir dal (branch) açın (`git checkout -b yeni-ozellik`).
3. Değişikliklerinizi taahhüt edin (`git commit -am 'Yeni özellik eklendi'`).
4. Dalınızı push edin (`git push origin yeni-ozellik`).
5. Bir Çekme İsteği (Pull Request) oluşturun.
