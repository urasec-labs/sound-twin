# 👥 AI Twin: Yapay Zeka Tabanlı Dijital İkiz Projesi

Bu proje; bireylerin kendi seslerini, yüzlerini ve konuşma tarzlarını yapay zeka teknolojileri kullanarak kopyalamasını ve tamamen özelleştirilmiş bir **Dijital İkiz (AI Twin)** oluşturmasını sağlayan açık kaynaklı bir yazılımdır.

Bu depo, orijinal projenin üzerine inşa edilmiş, Türkçe optimizasyonları ve kullanım kolaylığı geliştirmeleri içeren kişiselleştirilmiş bir sürümdür.

---

## ✨ Özellikler

* 🎙️ **Ses Klonlama (Voice Cloning):** Sadece birkaç dakikalık ses kaydı ile kendi sesinizi yüksek doğrulukla kopyalayın.
* 🎥 **Dudak Senkronizasyonu (Lip-Sync):** Verilen metinleri kendi sesinizle okuyan ve gerçekçi dudak hareketlerine sahip videolar üretin.
* 🧠 **Kişilik Entegrasyonu:** LLM (Büyük Dil Modelleri) desteği sayesinde yapay zekanın tıpkı sizin gibi düşünmesini ve konuşmasını sağlayın.
* 💻 **Kullanıcı Dostu Arayüz:** Web tabanlı arayüz üzerinden kodlama bilmeden dijital ikizinizle etkileşime geçin.

---

## 🚀 Hızlı Başlangıç

### 📋 Gereksinimler
Projenin sorunsuz çalışabilmesi için bilgisayarınızda aşağıdaki araçların kurulu olması gerekir:
* Python 3.10 veya üzeri
* Git
* FFmpeg (Video işleme için)
* CUDA destekli bir NVIDIA Ekran Kartı (Önerilen)

### 🛠️ Kurulum Adımları

1. **Depoyu bilgisayarınıza indirin:**
   ```bash
   git clone https://github.com[Kullanıcı Adınız]/digitaltwin.git
   cd digitaltwin
   ```

2. **Sanal ortam oluşturun ve aktif edin:**
   ```bash
   python -m venv venv
   # Windows için:
   .\venv\Scripts\activate
   # Mac/Linux için:
   source venv/bin/activate
   ```

3. **Gerekli kütüphaneleri yükleyin:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Uygulamayı başlatın:**
   ```bash
   python app.py
   ```
   Uygulama başladığında tarayıcınızdan `http://localhost:7860` (veya terminalde belirtilen) adresine giderek arayüze erişebilirsiniz.

---

## 🛠️ Nasıl Kullanılır?

1. **Sesinizi Tanıtın:** Arayüzdeki ses yükleme bölümüne 10-15 saniyelik temiz, arka plan gürültüsü olmayan bir ses kaydınızı yükleyin.
2. **Fotoğraf Seçin:** Dijital ikizinizin konuşurken kullanacağı net, karşıya bakan bir profil fotoğrafı ekleyin.
3. **Metni Yazın ve Üretin:** Yapay zekanın söylemesini istediğiniz metni yazın ve "Generate" butonuna basarak videonuzu hazır hale getirin.

---

## 📜 Lisans

Bu proje açık kaynak topluluğuna katkı sağlamak amacıyla geliştirilmiştir. 

* **Lisans:** Bu proje [MIT Lisansı](LICENSE) ile korunmaktadır. Özgürce değiştirebilir ve kendi projelerinizde kullanabilirsiniz.

---

## 🤝 İletişim & Katkıda Bulunma

Projeyi daha da geliştirmek için her türlü geri bildirime ve katkıya (Pull Request) açığım. Bir hata bulursanız lütfen "Issues" kısmından bildirmekten çekinmeyin.

* **Geliştirici:** [Adınız Soyadınız]
* **GitHub:** @[Kullanıcı Adınız]
* **E-posta:** [E-posta Adresiniz]
