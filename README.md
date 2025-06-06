# 🏠 KoneksiJasa - Website Jasa Terpercaya ✨

<div align="center">

![KoneksiJasa Banner](https://img.shields.io/badge/KoneksiJasa-Premium%20Services-blueviolet?style=for-the-badge&logo=home&logoColor=white)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![WhatsApp API](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://faq.whatsapp.com/general/chats/how-to-use-click-to-chat)

![Mobile Responsive](https://img.shields.io/badge/Mobile-Responsive-green?style=flat-square)
![Cross Browser](https://img.shields.io/badge/Cross-Browser-blue?style=flat-square)
![No Framework](https://img.shields.io/badge/Vanilla-JS-yellow?style=flat-square)

---

**🚀 Platform modern untuk menghubungkan pelanggan dengan penyedia jasa terpercaya**

[🌟 Live Demo](#-demo) • [📱 Features](#-fitur-unggulan) • [⚡ Quick Start](#-quick-start) • [🤝 Contributing](#-contributing)

</div>

---

## 🎯 Tentang KoneksiJasa

**KoneksiJasa** adalah platform web modern yang menghubungkan pelanggan dengan penyedia jasa berkualitas untuk kebutuhan rumah tangga. Dengan desain yang elegan dan integrasi WhatsApp yang seamless, KoneksiJasa memberikan pengalaman booking yang mudah dan terpercaya.

### 💡 Mengapa KoneksiJasa?

- 🎨 **Modern UI/UX** - Desain glassmorphism dengan animasi smooth
- 📱 **Mobile-First** - Responsive design untuk semua device  
- ⚡ **Fast Loading** - Optimized performance tanpa framework berat
- 🔗 **WhatsApp Integration** - Booking langsung via WhatsApp API
- 🛡️ **Trusted Partners** - Mitra terverifikasi dengan rating tinggi

---

## ✨ Fitur Unggulan

### 🏆 **Core Features**

| Feature | Description | Status |
|---------|-------------|--------|
| 🌿 **Potong Rumput** | Layanan pemotongan rumput profesional | ✅ Active |
| 🚗 **Cuci Mobil** | Cuci mobil premium dengan waxing | ✅ Active |
| ❄️ **Service AC** | Perawatan AC dengan garansi resmi | ✅ Active |
| 📱 **WhatsApp Booking** | Booking langsung via WhatsApp | ✅ Active |
| 🎯 **Partner Verified** | Mitra terpercaya dengan rating tinggi | ✅ Active |

### 🎨 **UI/UX Features**

- **Glassmorphism Design** - Efek kaca modern dengan backdrop blur
- **Smooth Animations** - Animasi CSS yang halus dan responsif  
- **Particle Effects** - Background animasi partikel yang menarik
- **Hover Interactions** - Efek hover yang engaging
- **Loading States** - Visual feedback untuk semua interaksi

### 📱 **Mobile Optimization**

- **Touch-Friendly** - Tombol berukuran ideal untuk mobile
- **Swipe Gestures** - Navigation yang smooth di mobile
- **Fast Tap Response** - Respon cepat untuk sentuhan
- **Optimized Images** - Loading cepat dengan compression optimal

---

## 🚀 Quick Start

### 📋 Prerequisites

- Browser modern (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime, Atom)
- Local server (Live Server, XAMPP, atau python -m http.server)

### ⚡ Installation

```bash
# 1. Clone repository
git clone https://github.com/yourusername/koneksijasa.git

# 2. Navigate to directory
cd koneksijasa

# 3. Open dengan Live Server atau browser
# Untuk VS Code dengan Live Server extension:
# Klik kanan pada index.html → "Open with Live Server"

# Atau gunakan Python local server:
python -m http.server 8000
# Buka http://localhost:8000
```

### 🔧 Configuration

**Customize WhatsApp Numbers:**

```javascript
// Di script.js, update nomor WhatsApp
const providers = {
    erwin: '6281237575743',
    firman: '6285812882170', 
    erlangga: '6282269502453',
    kelvin: '6282233665564',
    agus: '6285785672280'
};

// Admin WhatsApp
const adminPhone = '62895383015559';
```

---

## 🎨 Customization Guide

### 🌈 **Color Scheme**

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    --accent-gradient: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    --success-gradient: linear-gradient(135deg, #11998e 0%, #38ef7d 100%);
    --neon-gradient: linear-gradient(135deg, #ff006e 0%, #8338ec 50%, #3a86ff 100%);
}
```

### 📝 **Content Update**

1. **Services** - Edit di section `<section class="services">`
2. **Providers** - Update di section `<section class="providers">` 
3. **Contact Info** - Modify di footer dan WhatsApp numbers
4. **Branding** - Update logo dan nama di header

### 🎯 **Adding New Services**

```html
<div class="service-card animate-on-scroll">
    <div class="service-icon">
        <i class="fas fa-your-icon"></i>
    </div>
    <h3>🎯 Service Baru</h3>
    <p>Deskripsi layanan yang menarik dan informatif.</p>
    <div class="price">Mulai dari Rp XXX.XXX</div>
    <button class="contact-btn" onclick="openBookingModal('🎯 Service Baru')">
        <i class="fas fa-calendar-check"></i>
        Pesan Layanan
    </button>
</div>
```

---

## 📱 Mobile Testing

### 🔧 **Testing Checklist**

- [ ] Responsive layout di berbagai screen size
- [ ] Touch interactions bekerja smooth
- [ ] WhatsApp API berfungsi di mobile browser
- [ ] Loading speed optimal
- [ ] Animasi tidak lag di mobile

### 📊 **Supported Devices**

| Device Type | Screen Size | Status |
|-------------|-------------|--------|
| 📱 Mobile Portrait | 320px - 768px | ✅ Tested |
| 📱 Mobile Landscape | 568px - 1024px | ✅ Tested |
| 📟 Tablet | 768px - 1024px | ✅ Tested |
| 💻 Desktop | 1024px+ | ✅ Tested |

---

## 🛠️ Tech Stack

<div align="center">

### **Frontend**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### **Styling & Animation**
![CSS Grid](https://img.shields.io/badge/CSS_Grid-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![CSS Flexbox](https://img.shields.io/badge/Flexbox-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![CSS Animations](https://img.shields.io/badge/CSS_Animations-FF6B6B?style=for-the-badge&logo=css3&logoColor=white)

### **Integration**
![WhatsApp API](https://img.shields.io/badge/WhatsApp_API-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-339AF0?style=for-the-badge&logo=fontawesome&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=google&logoColor=white)

</div>

---

## 📈 Performance

### ⚡ **Metrics**

- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s  
- **First Input Delay**: < 100ms
- **Cumulative Layout Shift**: < 0.1

### 🎯 **Optimization Features**

- CSS minification ready
- Image optimization dengan WebP support
- Lazy loading untuk improved performance
- Efficient JavaScript dengan vanilla approach
- Minimal external dependencies

---

## 🔧 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| 🌐 Chrome | 90+ | ✅ Fully Supported |
| 🦊 Firefox | 88+ | ✅ Fully Supported |
| 🧭 Safari | 14+ | ✅ Fully Supported |
| 📘 Edge | 90+ | ✅ Fully Supported |
| 📱 Mobile Browsers | Latest | ✅ Optimized |

---

## 🚀 Deployment

### 📂 **Static Hosting**

```bash
# Deploy ke Netlify
npm install -g netlify-cli
netlify deploy --prod --dir .

# Deploy ke Vercel  
npm install -g vercel
vercel --prod

# Deploy ke GitHub Pages
# Push ke repository, enable GitHub Pages di settings
```

### 🌐 **CDN Integration**

```html
<!-- Optional: Add CDN untuk performance boost -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://cdnjs.cloudflare.com">
```

---

## 🤝 Contributing

Kami menyambut kontribusi dari developer! 

### 📝 **How to Contribute**

1. **Fork** repository ini
2. **Create** feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** ke branch (`git push origin feature/AmazingFeature`)
5. **Open** Pull Request

### 🐛 **Bug Reports**

Temukan bug? Silakan buat [issue](https://github.com/yourusername/koneksijasa/issues) dengan detail:

- Browser dan versi
- Device dan OS
- Steps to reproduce
- Screenshot (jika perlu)

### 💡 **Feature Requests**

Punya ide fitur baru? Kami senang mendengarnya! Buat issue dengan label `enhancement`.

---

## 📄 License

```
MIT License

Copyright (c) 2025 KoneksiJasa

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

---

## 📞 Contact & Support

<div align="center">

### 💬 **Get in Touch**

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/62895383015559)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:koneksijasa@gmail.com)
[![Website](https://img.shields.io/badge/Website-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://koneksijasa.com)

---

### 🌟 **Show Your Support**

Jika project ini membantu, berikan ⭐ di GitHub!

[![GitHub stars](https://img.shields.io/github/stars/yourusername/koneksijasa?style=social)](https://github.com/yourusername/koneksijasa/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/koneksijasa?style=social)](https://github.com/yourusername/koneksijasa/network)

**Made with ❤️ for Indonesian service providers**

</div>

---

<div align="center">
<sub>Built with passion by the KoneksiJasa team • © 2025</sub>
</div>
