# 🍽️ Déjà You Restaurant

Sebuah website profil restoran modern dan interaktif yang dirancang menggunakan HTML, CSS, dan JavaScript. Website ini dilengkapi fitur katalog menu, ulasan pelanggan, formulir pemesanan cepat (*order form*), serta tampilan yang sepenuhnya responsif di berbagai perangkat.

---

## 📌 Daftar Isi
- [Tentang Proyek](#-tentang-proyek)
- [Fitur Utama](#-fitur-utama)
- [Teknologi yang Digunakan](#-teknologi-yang-digunakan)
- [Struktur Folder](#-struktur-folder)
- [Cara Menjalankan Proyek](#-cara-menjalankan-proyek)
- [Kontak & Hak Cipta](#-kontak--hak-cipta)

---

## 📖 Tentang Proyek
**Déjà You Restaurant** menghadirkan pengalaman kuliner khas dengan perpaduan menu lokal autentik hingga internasional. Antarmuka web ini didesain agar pengunjung dapat dengan mudah menelusuri menu unggulan, mengecek harga, membaca ulasan, dan melakukan reservasi atau pemesanan makanan langsung melalui satu halaman (*single-page layout*).

---

## ✨ Fitur Utama

- **Page Loader:** Animasi loading saat halaman pertama kali dimuat.
- **Navbar Interaktif & Active Scroll:** Navigasi otomatis menyesuaikan posisi bagian halaman yang sedang dilihat pengguna.
- **Search Bar Pop-up:** Form pencarian hidangan terintegrasi dengan tombol pintas.
- **Hero Slider:** *Carousel* otomatis hidangan spesial (*Special Dishes*) menggunakan Swiper.js.
- **Katalog Menu Lengkap:** 
  - *Popular Dishes* (Kategori hidangan utama terpopuler beserta harga dan rating).
  - *Beverages* (Aneka jus buah, blended coffee, frappe, hingga teh).
  - *Foods and Meals* (Menu cemilan dan makanan pendukung).
- **Customer Reviews Carousel:** Ulasan dan testimoni pelanggan yang bergeser dinamis (*autoplay carousel*).
- **Fast Order Form:** Formulir cepat untuk pemesanan makanan, mencakup detail menu tambahan, jadwal pengiriman, dan alamat penerima.
- **Fully Responsive Design:** Mendukung tampilan optimal di smartphone, tablet, maupun layar desktop.

---

## 🛠️ Teknologi yang Digunakan

- **HTML5:** Struktur semantik antarmuka web.
- **CSS3:** Custom styling, CSS Variables, Flexbox, Grid, dan Media Queries.
- **JavaScript (ES6):** Manipulasi DOM, navigasi interaktif, pencarian, dan event handling.
- **Swiper.js (v11):** Slider interaktif pada bagian Hero dan Customer Reviews.
- **Icons & Font:**
  - Font Awesome v6
  - Flaticon UIcons
  - Google Fonts (Nunito)

---

## 📁 Struktur Folder

```plaintext
DEJA-YOU-Restaurant/
│
├── images/                  # Aset gambar, ikon, dan favicon
│   ├── dejayu.png
│   ├── loader.gif
│   └── ... (gambar menu & review)
│
├── index.html               # Halaman utama aplikasi web
├── style.css                # Berkas styling desain antarmuka
├── script.js                # Interaktivitas web dan inisialisasi slider
└── README.md                # Dokumentasi proyek
```

---

## 🚀 Cara Menjalankan Proyek

Ikuti panduan langkah demi langkah berikut untuk menjalankan proyek ini di lingkungan lokal:

### Prasyarat
- [x] Web browser modern (Google Chrome, Mozilla Firefox, Microsoft Edge, dll.)
- [x] Git terpasang di sistem
- [x] Kode editor (disarankan menggunakan Visual Studio Code)

### Langkah Pemasangan & Menjalankan

1. **Kloning Repository**
   Buka terminal atau Git Bash, lalu jalankan perintah berikut:
   ```bash
   git clone [https://github.com/lxngvr/DEJA-YOU-Restaurant.git](https://github.com/lxngvr/DEJA-YOU-Restaurant.git)
   ```

2. **Masuk ke Direktori Proyek**
   ```bash
   cd DEJA-YOU-Restaurant
   ```

3. **Menjalankan Website**
   Pilih salah satu metode di bawah:

   * **Opsi A — Menggunakan Live Server (VS Code - Sangat Disarankan):**
     1. Buka folder proyek di VS Code:
        ```bash
        code .
        ```
     2. Pasang ekstensi **Live Server** oleh Ritwick Dey melalui tab *Extensions* (`Ctrl+Shift+X`).
     3. Klik kanan file `index.html` > pilih **Open with Live Server** (atau klik tombol **Go Live** di status bar pojok kanan bawah).
     4. Browser akan otomatis terbuka pada alamat:
        ```text
        [http://127.0.0.1:5500/index.html](http://127.0.0.1:5500/index.html)
        ```

   * **Opsi B — Membuka Langsung via File Explorer:**
     1. Buka folder proyek di sistem operasi kamu.
     2. Klik dua kali pada file `index.html`.
     3. Halaman akan terbuka langsung di browser default.

---

## 👤 Kontak & Hak Cipta

- **Developer:** Galang D. Ramadhan
- **Email:** galangdavaa@gmail.com

*© 2024 Déjà You Restaurant. All Rights Reserved.*
