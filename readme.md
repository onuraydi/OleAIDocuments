# 🥗 OleAI - Yapay Zekâ Destekli Akıllı Tarif ve Mutfak Asistanı

**OleAI**, kullanıcıların ellerindeki malzemeleri en verimli şekilde değerlendirmelerini sağlayan, yapay zekâ destekli bir yemek tarifi öneri ve mutfak yönetimi platformudur. Gıda israfını azaltmayı ve "Bugün ne pişirsem?" sorusuna kişiselleştirilmiş yanıtlar vermeyi hedefler.


## 🚀 Proje Hakkında

OleAI, sadece bir tarif defteri değil; mutfak envanterinizi (Dolabım) takip eden, damak zevkinizi öğrenen ve buna uygun akıllı öneriler sunan kapsamlı bir ekosistemdir.

### 🌟 Temel Özellikler
* **🤖 Yapay Zekâ Destekli Öneri:** Mevcut malzemelerinize ve diyet tercihlerinize göre **TF-IDF** ve **Vektör Uzay Modelleri** kullanarak en uygun tarifleri önerir.
* **📦 Akıllı Mutfak Envanteri (Dolabım):** Evdeki malzemeleri yönetin, pişen yemeklerden sonra stokları otomatik güncelleyin.
* **🛒 Otomatik Alışveriş Listesi:** Biten malzemeleri tek tıkla alışveriş listenize ekleyin.
* **❤️ Sosyal Etkileşim:** Tarifleri beğenin, yorum yapın ve kendi özel tariflerinizi toplulukla paylaşın.
* **🔐 Güvenli Altyapı:** JWT tabanlı kimlik doğrulama ve rol bazlı erişim kontrolü.

---

## 🛠️ Teknoloji Yığını (Tech Stack)

Proje, modern ve ölçeklenebilir **Clean Architecture** prensiplerine göre geliştirilmiştir.

| Alan | Teknoloji / Araç |
| :--- | :--- |
| **Backend** | .NET Core 9, Entity Framework Core |
| **Frontend (Web)** | React, Vite, Tailwind CSS |
| **Frontend (Mobil)** | Kotlin, Jetpack Compose |
| **Yapay Zekâ (AI)** | Python, Scikit-learn (TF-IDF, Cosine Similarity) |
| **Veritabanı** | Microsoft SQL Server |
| **DevOps & CI/CD** | Docker, Kubernetes, GitHub Actions |
| **Test** | xUnit, Moq, Selenium, SonarQube |

---

## 📚 Proje Dokümantasyonu

Projenin tüm teknik detaylarına, analiz raporlarına ve diyagramlarına aşağıdaki bağlantılardan ulaşabilirsiniz:

### 1️⃣ [Gereksinim Analizi ve Kullanıcı Hikayeleri](./GereksinimAnalizi/2.GereksinimAnaliziDocument.md)
> * Kullanıcı Hikayeleri (User Stories)
> * Fonksiyonel ve Fonksiyonel Olmayan Gereksinimler (FR/NFR)
> * Risk Analizi
> * **İçerik:**

### 2️⃣ [Sistem Tasarımı ve Mimari](./SistemTasarimi/3.sistemTasarimi.md)
> * Sistem Mimarisi ve UML Diyagramları
> * Veritabanı Tasarımı (ER Diyagramı)
> * Sequence (Sıralama) Diyagramları
> * **İçerik:**

### 3️⃣ [Test Planı ve Senaryoları](./TestPlani/4.TestDocument.md)
> * Test Stratejileri ve Kullanılan Araçlar
> * Detaylı Test Senaryoları (Login, Tarif, AI, Güvenlik)
> * Test Case Tabloları
> * **İçerik:**

### 4️⃣ [DevOps Entegrasyonu ve CI/CD](./DevOpsEntegrasyonu/5.DevOpsEngterasyonu.md)
> * CI/CD Pipeline Akışı ve Adımları
> * DevOps Diyagramı
> * Konteynerizasyon ve Dağıtım Süreçleri
> * **İçerik:**

### 5️⃣ [Proje Yönetimi ve Planlama](./ProjeYonetimi/6.ProjeYonetimi.md)
> * Gantt Şeması ve Zaman Çizelgesi
> * Görev Dağılımı
> * Süreç Takibi
> * **İçerik:**

---

## 📊 Proje Süreci (Özet)

Proje geliştirme süreci aşağıdaki ana pipeline üzerinden yürütülmektedir:

```mermaid
graph LR
    A[📝 Kodlama] --> B[⚙️ CI/CD Pipeline]
    B --> C[🧪 Test & Analiz]
    C --> D[🐳 Dockerize]
    D --> E[🚀 Canlı Dağıtım]
