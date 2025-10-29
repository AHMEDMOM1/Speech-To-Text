# 🗣️ **Speech-To-Text Uygulaması (Konuşmadan Metne)**

Bu proje, **Microsoft Azure Cognitive Services** kullanarak konuşmayı metne dönüştüren basit ve etkili bir **C# masaüstü uygulamasıdır**.
Ayrıca, konuşmayı farklı dillere çevirebilir ve metin üzerinde çeşitli işlemler yapabilirsiniz.

---

## ⚡ **Temel Özellikler**

✅ Konuşmayı **Microsoft Azure Speech Service** aracılığıyla metne dönüştürür.
✅ **Azure Translator** ile konuşmayı farklı dillere çevirebilir.
✅ **Metni panoya kopyalayabilir** veya **uygulama ekranında görüntüleyebilir.**
✅ Kullanıcı, açılır menüden **konuşma dilini** seçebilir.

---

## 🧰 **Gereksinimler**

Uygulamayı çalıştırmadan önce aşağıdakilerin kurulu olduğundan emin olun:

* 🔑 **Azure API anahtarları:** (Speech ve Translator hizmetleri için)
* 📦 Aşağıdaki **NuGet paketleri:**

  * DotNetEnv
  * Azure.CognitiveServices.Speech
  * Newtonsoft.Json

---

## 🚀 **Kurulum Adımları**

1. 💾 Projeyi bilgisayarınıza klonlayın:

   ```bash
   git clone https://github.com/AHMEDMOM1/Speech-To-Text
   ```
2. 📂 Klonlanan dizine gidin.
3. 🧾 Projenin kök dizinine bir **`.env`** dosyası oluşturun.
4. `.env` dosyasına kendi **Azure anahtarlarınızı** ve **bölgenizi** aşağıdaki formatta ekleyin:

   ```env
   Speech_API_KEY = "Konuşma_Hizmeti_API_Anahtarınız"
   Translator_API_KEY = "Çevirmen_API_Anahtarınız"
   Region = "Abonelik_Bölgeniz"
   ```
5. ▶️ Uygulamayı derleyin ve çalıştırın.

---

## 🎙️ **Kullanım Kılavuzu**

1. **“Başlat (Start)”** düğmesine tıklayın ve konuşmaya başlayın.

   * Uygulama konuşmayı otomatik olarak algılar.
   * Siz **“Durdur (Stop)”** düğmesine basana kadar dinlemeye devam eder.

2. **“Durdur (Stop)”** düğmesi, işlemi iptal etmek veya sonlandırmak için kullanılır.

---

## 🔘 **Mod Seçenekleri**

* 🗣️ **Speech:** Konuşmayı metne dönüştürür. (Lütfen konuşma dilini seçtiğinizden emin olun.)
* 🌍 **Translation:** Konuşmayı seçilen dile çevirir.

---

## ☑️ **Ek Özellikler**

* 📋 **Metni Kopyala (Copy Text):** Çeviri veya konuşma tamamlandığında metni panoya kopyalar.
* 💬 **Metni Göster (Show Text):** Metni doğrudan uygulama arayüzünde görüntüler.

---

## 🧩 **Kullanılan Teknolojiler**

| Teknoloji                   | Açıklama                     |
| --------------------------- | ---------------------------- |
| 💻 C#                       | Uygulama dili                |
| 🔌 Azure Cognitive Services | Konuşma ve çeviri hizmetleri |
| ⚙️ DotNetEnv                | Ortam değişkeni yönetimi     |
| 🧠 Newtonsoft.Json          | JSON veri işleme             |

---
