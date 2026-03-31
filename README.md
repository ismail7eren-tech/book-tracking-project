# 📚 Kitap Takip Uygulaması

> Okuma alışkanlıklarınızı, kitaplardan öğrendiklerinizi ve günlük sayfa hedeflerinizi şık bir arayüzle takip etmenizi sağlayan modern bir "Premium" web projesi.

---

## 🌟 Proje Hakkında

Bu proje, başlangıçta **Cursor IDE** kullanılarak temellendirilmiş; ardından **Antigravity (Google DeepMind)** yapay zeka kodlama asistanı yardımıyla mimarisi, güvenliği ve gelişmiş kullanıcı arayüzü (Glassmorphism tasarımı) baştan aşağı kurgulanarak profesyonel bir seviyeye taşınmıştır.

Amacımız; okurların yıllık okuma trendlerini görebilecekleri, kitaplardan aldıkları spesifik notları güvenle saklayabilecekleri ve kişisel istatistiklerini oluşturabilecekleri tek sunucu (Single Server) mimarisinde çalışan hızlı bir uygulama sunmaktır.

### ✨ Temel Özellikler
- **🔐 Güvenli Kullanıcı Girişi (Auth):** JWT (JSON Web Token) ve Bcrypt ile şifrelenmiş kayıt/giriş sistemi sayesinde her kullanıcıya özel, kimsenin göremediği özel bir kitaplık!
- **📊 Gelişmiş İstatistikler:** Yıllık okunan kitaplar, günlük ortalama okunan sayfalar ve son 12 ayın okuma verilerini gösteren dinamik çubuk grafik (Bar Chart).
- **🎨 Premium UI (Glassmorphism):** Koyu tema arkaplanlarla birleşen buzlu cam tasarımı, CSS animasyonları ve modern tipografi (Outfit) barındıran akıcı bir kullanıcı deneyimi.
- **📝 Konular ve Alıntılar:** Kitaplardan edindiğiniz bilgi çıkarımlarını not alabildiğiniz özel öğrenimler modülü.
- **⚡ Tek Sunucu Mimarisi:** Frontend (React) kodlarının Backend (Node.js/Express) sunucusu tarafından otomatik olarak entegre bir şekilde sunulduğu devasa kolaylık sağlayan yayıncı altyapısı.

---

## 🚀 Kullanılan Teknolojiler

**Frontend (Kullanıcı Arayüzü):**
- React (Vite)
- Custom CSS (Glassmorphism, CSS Variables, Akıcı Animasyonlar)

**Backend (Sunucu ve Veritabanı):**
- Node.js & Express.js
- Prisma ORM (Mevcut SQLite, istenildiğinde PostgreSQL'e geçmeye hazır)
- JSON Web Token (JWT) & Bcrypt (Kimlik Doğrulama)
- Zod (Gelen veri doğrulaması)

---

## ⚙️ Kurulum ve Çalıştırma

Tek port (4000) üzerinden tüm projeyi saniyeler içinde kendi sisteminizde ayağa kaldırın!

### 1. Depoyu İndirin
```bash
git clone https://github.com/your-username/kitap-takip-projesi.git
cd kitap-takip-projesi
```

### 2. Gerekli Paketleri Yükleyin
Hem backend hem frontend paketlerini tek seferde yüklemek için:
```bash
npm run install:all
```

### 3. Arayüz Kodlarını Derleyin
```bash
npm run build
```

### 4. Sunucuyu Başlatın!
```bash
npm start
```
Artık tarayıcınızdan `http://localhost:4000` adresine gidebilir, yeni hesabınızı doğrudan oluşturabilir ve harika paneli incelemeye başlayabilirsiniz!

---

> *"Okumadan geçen bir gün, yitirilmiş bir gündür."* 
> Kitap sevdalıları ve daima öğrenenler için özenle tasarlandı. Yapay zeka eşliğinde yetenekli kodlama ile zenginleştirildi. 
