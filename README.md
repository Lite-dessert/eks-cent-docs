# Eks-Cent Documentation Website v4.0.0 🚀

Website dokumentasi resmi untuk framework **Eks-Cent**. Dibangun menggunakan **Eks-Cent v4.0.0** itu sendiri untuk mendemonstrasikan kekuatan arsitektur modern, kecepatan tinggi, dan sistem keamanan yang tangguh.

## ✨ Fitur Website

- **Glassmorphism Design**: Antarmuka modern yang dikurasi dengan efek transparansi dan blur (Tailwind CSS).
- **v4 Architecture Showcase**: Mengimplementasikan fitur **URL Mapping** dan **Application Cascading** untuk pengelolaan rute yang modular.
- **Dynamic SEO Suite**: Meta tags OpenGraph (v4 branded), Favicon khusus, `robots.txt`, dan `sitemap.xml` yang dapat dibaca mesin pencari dengan sempurna.
- **Eks-Server Power**: Ditenagai oleh **EKSA Server v1.1** untuk performa tinggi dengan dukungan *multi-threading* dan *auto-reload*.
- **Full Responsive**: Tata letak yang dioptimalkan untuk mobile dengan navigasi *hamburger* dan *horizontal scroll* pada sidebar dokumentasi.

## 🚀 Memulai

### Prasyarat
- **Ruby (>= 3.0)**: Direkomendasikan menggunakan versi terbaru.
- **Gem**: `eks-cent (~> 4.0)` dan `eksa-server (~> 1.1)`.

### Instalasi Lokal
1. **Clone & Install**:
   ```bash
   bundle install
   ```
2. **Jalankan Server (Mode Development)**:
   Gunakan flag `-R` untuk mengaktifkan fitur *Auto-Reload* saat ada perubahan file:
   ```bash
   ekscentup -R
   ```
3. **Buka di Browser**: Kunjungi [http://localhost:3000](http://localhost:3000).

## 🗺 Arsitektur Projek

Website ini menggunakan struktur standar v4:
- `config.eks`: Gerbang utama aplikasi, berisi konfigurasi middleware dan *mapping* rute.
- `views/layout.erb`: Template induk dengan sistem **Auto-Layout** v4.
- `views/docs.erb`: Konten dokumentasi teknis yang dinamis.
- `public/`: Direktori aset statis (logo, favicon, sitemap.xsl).

## 📄 Lisensi

Eks-Cent Documentation didistribusikan di bawah [Lisensi MIT](LICENSE).