# Eks-Cent Documentation Website 🚀

Website dokumentasi resmi untuk framework **Eks-Cent**. Dibangun menggunakan Eks-Cent itu sendiri untuk menunjukkan kemampuannya dalam membangun aplikasi web yang cepat, aman, dan ringan.

## ✨ Fitur Website

- **Glassmorphism Design**: Antarmuka modern dengan efek blur dan transparansi.
- **Dynamic SEO**: Meta tags OpenGraph, Favicon, robots.txt, dan sitemap.xml yang dihasilkan secara dinamis.
- **Fast Rendering**: Menggunakan Eksa-Server sebagai engine server performa tinggi.
- **Responsive Layout**: Optimal untuk perangkat mobile dan desktop.

## 🚀 Memulai

### Prasyarat
- Ruby (>= 3.0)
- Gem `eks-cent` dan `eksa-server`

### Instalasi Lokal
1. Install dependensi:
   ```bash
   bundle install
   ```
2. Jalankan server:
   ```bash
   ekscentup
   ```
3. Buka di browser: `http://localhost:3000`

## 🛡 Deployment (Railway)

Proyek ini siap untuk di-deploy ke [Railway](https://railway.app/).
1. Pilih repositori GitHub Anda di Railway.
2. Railway akan otomatis menggunakan `Procfile` dan `Gemfile` yang tersedia.
3. Pastikan port diatur ke dynamic `$PORT`.

## 📄 Lisensi

Eks-Cent Documentation didistribusikan di bawah [Lisensi MIT](LICENSE).
