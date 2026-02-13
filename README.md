# Modern Shopping App

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)

<img src="https://upload.wikimedia.org/wikipedia/commons/2/2f/Google_2015_logo.svg" alt="Google Stitch" height="24" style="vertical-align: middle;"> **Google Stitch** &nbsp;&nbsp;&nbsp;
<img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Claude_AI_logo.svg" alt="Claude AI" height="24" style="vertical-align: middle;"> **Claude Opus 4.5**

![Made with AI](https://img.shields.io/badge/Made%20with-Vibe%20Coding-purple.svg)

**A modern, mobile-first e-commerce web application**

[English](#english) | [Turkce](#turkce)

</div>

---

<a name="english"></a>
## English

### About

Modern Shopping App is a **demo/simulation** e-commerce web application built with modern web technologies. This project demonstrates a complete e-commerce flow including product browsing, cart management, and checkout process. **Note:** This is a frontend-only demo - no real orders are created and no actual payments are processed. All data is simulated and stored locally using LocalStorage. This project was developed using **AI-assisted development** and **Vibe Coding** methodology, leveraging the power of AI tools to accelerate the development process while maintaining high code quality.

### Built with AI & Vibe Coding

This project was created using:
- **Google Stitch**: UI/UX design and prototyping
- **Claude Opus 4.5**: AI-powered code generation and development
- **Cursor IDE**: AI-integrated development environment
- **Vibe Coding Approach**: Rapid prototyping and iterative development with AI collaboration

### Features

- **Product Catalog**: Browse products with category filtering and search functionality
- **Product Details**: Detailed product pages with size selection, quantity picker, and reviews
- **Shopping Cart**: Full cart management with quantity adjustments and price calculations
- **Checkout Process**: Multi-step checkout simulation with address and payment method selection (demo only - no real payments)
- **User Profile**: Personal information, saved addresses, payment methods, and order history
- **Dark Mode**: Eye-friendly dark theme support
- **Responsive Design**: Mobile-first design that works on all devices
- **LocalStorage**: Persistent data storage for cart, orders, and user preferences

### Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Structure & Semantics |
| Tailwind CSS | Styling & Responsive Design |
| Vanilla JavaScript | Interactivity & Logic |
| Material Symbols | Iconography |
| LocalStorage API | Client-side Data Persistence |

### Project Structure

```
shopping_app/
├── index.html                      # Home page - Product listing
├── README.md                       # Documentation
├── js/
│   └── cart-manager.js             # Cart management system
├── pages/
│   ├── product-detail.html         # Product detail page
│   ├── shopping-cart.html          # Shopping cart
│   ├── checkout.html               # Checkout process
│   └── profile/
│       ├── user-profile.html       # User profile page
│       ├── personal-info.html      # Personal information
│       ├── saved-addresses.html    # Saved addresses
│       ├── payment-methods.html    # Payment methods
│       ├── orders.html             # Order history
│       └── settings.html           # App settings
```

### Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/imSurme/shopping_app.git
   ```

2. **Open in browser**
   ```bash
   # Simply open index.html in your browser
   # Or use a local server:
   npx serve .
   ```

3. **Start shopping!**
   - Browse products on the home page
   - Add items to your cart
   - Complete the checkout process

### Key Components

#### Cart Manager (`cart-manager.js`)
A centralized cart management system that handles:
- Adding/removing products
- Quantity updates
- Cart total calculations
- LocalStorage persistence
- Cart badge updates

#### Checkout Flow
Three-step checkout process:
1. **Address**: Delivery address selection/entry
2. **Payment**: Payment method selection
3. **Confirmation**: Order review and completion

---

<a name="turkce"></a>
## Turkce

### Hakkinda

Modern Shopping App, modern web teknolojileriyle gelistirilmis bir **demo/simulasyon** e-ticaret web uygulamasidir. Bu proje, urun gezintisi, sepet yonetimi ve odeme sureci dahil olmak uzere tam bir e-ticaret akisini gosterir. **Not:** Bu yalnizca frontend demo projesidir - gercek siparis olusturulmaz ve gercek odeme islemi yapilmaz. Tum veriler simule edilir ve LocalStorage kullanilarak yerel olarak saklanir. Bu proje, **yapay zeka destekli gelistirme** ve **Vibe Coding** metodolojisi kullanilarak olusturulmustur. AI araclari kullanilarak hizli ve kaliteli kod gelistirme sureci gerceklestirilmistir.

### AI ve Vibe Coding ile Gelistirildi

Bu proje asagidaki yaklasimlarla olusturuldu:
- **Google Stitch**: UI/UX tasarim ve prototipleme
- **Claude Opus 4.5**: AI destekli kod uretimi ve gelistirme
- **Cursor IDE**: AI entegreli gelistirme ortami
- **Vibe Coding Yaklasimi**: AI isbirligi ile hizli prototipleme ve yinelemeli gelistirme

### Ozellikler

- **Urun Katalogu**: Kategori filtreleme ve arama ozellikleriyle urunlere gozatin
- **Urun Detaylari**: Beden secimi, miktar secici ve degerlendirmeler iceren detayli urun sayfalari
- **Alisveris Sepeti**: Miktar ayarlama ve fiyat hesaplamalari ile tam sepet yonetimi
- **Odeme Sureci**: Adres ve odeme yontemi secimli cok adimli odeme simulasyonu (yalnizca demo - gercek odeme yapilmaz)
- **Kullanici Profili**: Kisisel bilgiler, kayitli adresler, odeme yontemleri ve siparis gecmisi
- **Karanlik Mod**: Goz dostu karanlik tema destegi
- **Duyarli Tasarim**: Tum cihazlarda calisan mobil oncelikli tasarim
- **LocalStorage**: Sepet, siparisler ve kullanici tercihleri icin kalici veri depolama

### Teknoloji Yigini

| Teknoloji | Amac |
|-----------|------|
| HTML5 | Yapi ve Semantik |
| Tailwind CSS | Stil ve Duyarli Tasarim |
| Vanilla JavaScript | Etkilesim ve Mantik |
| Material Symbols | Ikonografi |
| LocalStorage API | Istemci Tarafli Veri Kaliciligi |

### Proje Yapisi

```
shopping_app/
├── index.html                      # Ana sayfa - Urun listesi
├── README.md                       # Dokumantasyon
├── js/
│   └── cart-manager.js             # Sepet yonetim sistemi
├── pages/
│   ├── product-detail.html         # Urun detay sayfasi
│   ├── shopping-cart.html          # Alisveris sepeti
│   ├── checkout.html               # Odeme sureci
│   └── profile/
│       ├── user-profile.html       # Kullanici profil sayfasi
│       ├── personal-info.html      # Kisisel bilgiler
│       ├── saved-addresses.html    # Kayitli adresler
│       ├── payment-methods.html    # Odeme yontemleri
│       ├── orders.html             # Siparis gecmisi
│       └── settings.html           # Uygulama ayarlari
```

### Baslarken

1. **Depoyu klonlayin**
   ```bash
   git clone https://github.com/imSurme/shopping_app.git
   ```

2. **Tarayicida acin**
   ```bash
   # index.html dosyasini tarayicinizda acin
   # Veya yerel sunucu kullanin:
   npx serve .
   ```

3. **Alisverise baslayin!**
   - Ana sayfada urunlere gozatin
   - Sepetinize urun ekleyin
   - Odeme islemini tamamlayin

### Temel Bilesenler

#### Sepet Yoneticisi (`cart-manager.js`)
Asagidakileri yoneten merkezi sepet yonetim sistemi:
- Urun ekleme/cikarma
- Miktar guncellemeleri
- Sepet toplami hesaplamalari
- LocalStorage kaliciligi
- Sepet rozeti guncellemeleri

#### Odeme Akisi
Uc adimli odeme sureci:
1. **Adres**: Teslimat adresi secimi/girisi
2. **Odeme**: Odeme yontemi secimi
3. **Onay**: Siparis incelemesi ve tamamlama

---

<div align="center">

**Made with Vibe Coding**

*Design: Google Stitch | Code: Claude Opus 4.5*

</div>
