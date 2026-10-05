# Raynova — Web Developer Portfolio

Selamat datang di repositori portofolio web **Raynova**. Website ini dibangun dengan mengutamakan standar **Aksesibilitas Web (WCAG 2.1 AA)**, struktur **HTML5 Semantik**, serta **CSS Modular** tanpa ketergantungan pada *framework* CSS atau JavaScript eksternal.

---

## 📌 Fitur Utama & Keunggulan

* **HTML5 Semantik Ketat**: Memanfaatkan tag semantik seperti `<header>`, `<nav>`, `<main>`, `<article>`, `<aside>`, dan `<footer>` sesuai peruntukan untuk mempermudah pemindaian oleh *screen reader*.
* **Aksesibilitas WCAG 2.1 AA**:
  * **Satu Tag `<h1>`**: Hanya terdapat satu tag `<h1>` sebagai penanda judul utama dokumen pada Hero Section.
  * **Hierarki Heading Terstruktur**: Seluruh elemen `<article>` dilengkapi judul semantik (`<h2>`, `<h3>`, `<h4>`) sehingga lulus validasi W3C tanpa *warning*.
  * **Keyboard Navigation**: Dilengkapi dengan *Skip Link* (`.skip-link`) untuk melompat langsung ke konten utama serta indikator fokus (`:focus-visible`) yang kontras.
  * **Aria Attributes**: Memanfaatkan `aria-label` dan `aria-hidden="true"` pada ikon dekoratif dan tombol nav.
* **CSS Modular (Tunggal)**: Pembagian blok CSS yang terisolasi dengan baik menggunakan *CSS Variables (Custom Properties)* dan *Comment Sectioning* di file `css/style.css`.
* **Layout Modern & Responsif**: Memanfaatkan **CSS Grid** dan **Flexbox** untuk tampilan galeri portofolio dan kartu layanan yang adaptif di berbagai ukuran layar.
* **Performa Tinggi**: Optimasi aset gambar dengan *lazy loading* (`loading="lazy"`) serta pencegahan keterlambatan rendering.

---

## 📁 Struktur Direktori Proyek

Proyek ini menggunakan struktur pohon direktori yang rapi dan terisolasi:

```text
pemweb-tugas1-[NIM]/
├── index.html          <-- Dokumen HTML5 semantik utama
├── css/
│   └── style.css       <-- Seluruh styling CSS modern (Box Model, Flexbox, Grid, RWD)
├── assets/
│   ├── images/         <-- Berkas gambar yang telah dioptimasi (.webp / .jpg / .png)
│   └── icons/          <-- Berkas ikon pendukung (.svg diutamakan & favicon)
└── README.md           <-- Dokumentasi proyek, deskripsi fitur, & informasi proyek