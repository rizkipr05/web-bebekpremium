# 🦆 Bebek Premium - Landing Page

Website *landing page* eksklusif untuk restoran **Nasi Bebek Premium** Jakarta Utara. Proyek ini dibangun dari awal untuk menyajikan antarmuka (UI) yang modern, estetik, dan berkelas (*premium*) tanpa menggunakan *framework* yang berat, guna mengedepankan performa dan pengalaman pengguna (UX) yang sangat mulus.

## ✨ Fitur Utama
- **Modern & Premium UI:** Tata letak grid yang bersih dengan skema warna aksen merah dan emas yang menggugah selera.
- **Responsive Design:** 100% didukung mulai dari layar ponsel (Mobile) hingga Monitor Desktop besar.
- **Navigasi Mulus:** Navbar *Sticky* berefek kaca buram (*Glassmorphism*) dilengkapi auto-scroll halus.
- **Interaktif:** Terdiri dari Testimonial Slider, Menu Interaktif (Hover zoom), serta *FAQ Accordion* interaktif.
- **Integrasi Penuh:** Dilengkapi Google Maps Embed secara bawaan dan pintasan koneksi langsung ke WhatsApp pemesanan (*Delivery/Booking*).
- **Aset Vektor:** Memanfaatkan logo dengan format `.svg` kode murni sehingga gambar selalu tajam walau diperbesar berkali-kali lipat tanpa resolusi pecah.

## 🛠️ Teknologi yang Digunakan
Proyek ini sepenuhnya berbasis *frontend* murni statis agar pemuatannya secepat kilat:
- **HTML5** (Struktur Logis dan Semantik SEO)
- **CSS3 / Vanilla CSS** (CSS Grid, Variables, Hover Animation, Responsive Media Queries)
- **JavaScript (ES6)** (Logika *mobile menu* & *accordion dropdown*, tanpa jQuery) 
- Font dari Google Fonts (*Outfit*) dan ikon (*FontAwesome* CDN).

## 📁 Struktur Direktori
```text
📦 web-bebekpremium
 ┣ 📂 assets
 ┃ ┣ 📜 about.png           # Foto suasana / interior
 ┃ ┣ 📜 gallery_1.png       # Foto aksi memasak koki
 ┃ ┣ 📜 gallery_2.png       # Foto malam piring bebek
 ┃ ┣ 📜 hero.png            # Foto HD besar (Latar Paling Atas)
 ┃ ┣ 📜 logo-light.svg      # Vektor Logo terang (Khusus Footer)
 ┃ ┣ 📜 logo.svg            # Vektor Logo utama (Navbar)
 ┃ ┣ 📜 menu_bebek.png      # Gambar katalog produk Bebek
 ┃ ┗ 📜 menu_esteh.png      # Gambar katalog Teh
 ┣ 📜 index.html            # Entri utama dan seluruh struktur halaman
 ┣ 📜 script.js             # Skrip interaktivitas situs
 ┣ 📜 style.css             # Modul panduan gaya CSS (Styling)
 ┗ 📜 README.md             # Instruksi & Dokumentasi Repositori
```

## 🚀 Cara Menjalankan Lokal 
Oleh karena proyek ini bersifat murni statis, **tidak ada prasyarat (dependencies)** PHP, npm, Node.js, atau database yang diperlukan!

1. Buka terminal Anda dan salin kode *clone* ini:
   ```bash
   git clone https://github.com/rizkipr05/web-bebekpremium.git
   ```
2. Pindah ke direktori tempat situs berada:
   ```bash
   cd web-bebekpremium
   ```
3. Langsung klik ganda / buka `index.html` menggunakan peramban web (browser) favorit Anda (*Google Chrome*, *Safari*, dll).
4. **Tips Tambahan:** Jika Anda developer yang menggunakan Visual Studio Code, sangat disarankan membuka *folder* tersebut dan memakai bantuan ekstensi `Live Server` untuk melihat perubahan (*hot-reload*) secara seketika.

## 🧑‍💻 Modifikasi (Customization)
- **Mengganti Tema Warna:** Cukup buka `style.css` pada bagian atas sekali (`:root`) untuk memodifikasi warna utama secara global (`--primary-color`).
- **Mengganti Logo Baru:** Cukup ganti *file* di direktori `assets/logo.svg` dan `assets/logo-light.svg` dengan *file* SVG/PNG transparan Anda sendiri.
- **Mengganti Alamat/Nomor Kontak:** Buka `index.html` dan carilah seksi bagian tulisan `ID="kontak"`. Alamat WA dan tautan peta *google* berada pada tag *anchor* (`<a>`) serta `<iframe>`.

---

Dikembangkan secara khusus 👨‍💻 untuk **Nasi Bebek Premium**.
