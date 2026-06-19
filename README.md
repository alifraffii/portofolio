# Creative Developer Portfolio Template

Template portofolio modern dan profesional untuk developer dan designer dengan tema "Creative Developer". Template ini dibuat menggunakan HTML5, CSS3, dan JavaScript vanilla dengan desain yang responsif dan interaktif.

## 🎨 Fitur Utama

### Design & UI/UX
- **Modern & Profesional**: Desain clean dengan gradient yang menarik
- **Fully Responsive**: Tampil sempurna di semua device (desktop, tablet, mobile)
- **Smooth Animations**: Animasi yang halus dan engaging
- **Interactive Elements**: Hover effects dan micro-interactions
- **Typography**: Menggunakan font Inter yang modern dan readable

### Sections
1. **Hero Section**: Intro dengan floating cards dan call-to-action
2. **About Section**: Profil singkat dengan statistik achievements
3. **Skills Section**: Showcase teknologi dan tools yang dikuasai
4. **Projects Section**: Portfolio projects dengan preview dan tech stack
5. **Contact Section**: Form kontak dan informasi sosial media

### Teknologi
- **HTML5**: Semantic markup dan accessibility
- **CSS3**: Flexbox, Grid, Custom Properties, Animations
- **JavaScript ES6+**: Modern JavaScript dengan smooth interactions
- **Font Awesome**: Icons yang konsisten
- **Google Fonts**: Typography yang profesional

## 🚀 Cara Penggunaan

### 1. Download Template
```bash
# Clone atau download folder template
# Pastikan semua file ada dalam satu folder:
# - index.html
# - style.css
# - script.js
# - README.md
```

### 2. Kustomisasi Konten

#### Edit Informasi Personal (index.html)
```html
<!-- Ganti nama dan title -->
<h1 class="hero-title">
    Hi, I'm <span class="gradient-text">Nama Anda</span>
</h1>
<h2 class="hero-subtitle">Profesi Anda</h2>

<!-- Update contact info -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>email-anda@domain.com</span>
</div>
```

#### Customize Colors (style.css)
```css
/* Ganti color scheme utama */
:root {
    --primary-color: #6366f1;  /* Warna utama */
    --secondary-color: #8b5cf6; /* Warna sekunder */
    --accent-color: #ec4899;    /* Warna aksen */
}
```

#### Update Projects
```html
<!-- Edit project cards di section projects -->
<div class="project-card">
    <div class="project-content">
        <h3>Nama Project Anda</h3>
        <p>Deskripsi project...</p>
        <div class="project-tech">
            <span>React</span>
            <span>Node.js</span>
            <!-- Tambah tech stack -->
        </div>
    </div>
</div>
```

### 3. Deploy

#### GitHub Pages
1. Upload ke GitHub repository
2. Aktifkan GitHub Pages di Settings
3. Pilih branch main/master

#### Netlify
1. Drag & drop folder ke netlify.com
2. Atau connect dengan GitHub repository

#### Vercel
1. Import project dari GitHub
2. Deploy otomatis

## 📱 Responsive Breakpoints

```css
/* Mobile First Approach */
@media (max-width: 480px)  { /* Mobile */ }
@media (max-width: 768px)  { /* Tablet */ }
@media (max-width: 1024px) { /* Desktop Small */ }
@media (min-width: 1200px) { /* Desktop Large */ }
```

## 🎯 Customization Guide

### Mengganti Tema Warna
```css
/* Di file style.css, cari dan ganti gradient colors */
.gradient-text {
    background: linear-gradient(135deg, #your-color-1, #your-color-2);
}

.btn-primary {
    background: linear-gradient(135deg, #your-color-1, #your-color-2);
}
```

### Menambah Section Baru
```html
<!-- Template section baru -->
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">Section Title</h2>
            <p class="section-subtitle">Section description</p>
        </div>
        <!-- Content here -->
    </div>
</section>
```

### Menambah Animasi
```javascript
// Di script.js, tambah element ke observer
const newElements = document.querySelectorAll('.your-new-class');
newElements.forEach(el => {
    observer.observe(el);
});
```

## 🔧 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 60+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers

## 📦 Dependencies

### External CDN
- **Font Awesome 6.0.0**: Icons
- **Google Fonts (Inter)**: Typography

### No Build Process Required
- Pure HTML, CSS, JavaScript
- No npm, webpack, atau build tools
- Langsung bisa dibuka di browser

## 🎨 Color Palette

```css
/* Primary Colors */
--primary-blue: #6366f1
--primary-purple: #8b5cf6
--primary-pink: #ec4899

/* Neutral Colors */
--gray-50: #f8fafc
--gray-100: #f1f5f9
--gray-500: #64748b
--gray-900: #1e293b

/* Semantic Colors */
--success: #10b981
--error: #ef4444
--warning: #f59e0b
```

## 📝 SEO Tips

1. **Update Meta Tags**
```html
<meta name="description" content="Deskripsi portfolio Anda">
<meta name="keywords" content="developer, designer, portfolio">
<meta property="og:title" content="Nama Anda - Portfolio">
```

2. **Add Structured Data**
```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Person",
  "name": "Nama Anda",
  "jobTitle": "Developer"
}
</script>
```

## 🚀 Performance Tips

1. **Optimize Images**: Gunakan format WebP untuk gambar
2. **Lazy Loading**: Tambahkan `loading="lazy"` pada images
3. **Minify CSS/JS**: Untuk production, minify file CSS dan JS
4. **CDN**: Gunakan CDN untuk Font Awesome dan Google Fonts

## 📞 Support

Jika ada pertanyaan atau butuh bantuan kustomisasi:
- Buat issue di GitHub repository
- Email: support@yourportfolio.com

## 📄 License

MIT License - Bebas digunakan untuk project personal dan komersial.

---

**Happy Coding! 🚀**

*Template ini dibuat dengan ❤️ untuk membantu developer dan designer membuat portfolio yang menarik dan profesional.*