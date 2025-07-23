# 🇮🇩 Template Website HUT RI ke-80 Indonesia

<p align="center">
  <img src="https://img.shields.io/badge/Indonesia-80th_Independence-red?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjEyIiBmaWxsPSIjRkYwMDAwIi8+CjxyZWN0IHk9IjEyIiB3aWR0aD0iMjQiIGhlaWdodD0iMTIiIGZpbGw9IiNGRkZGRkYiLz4KPC9zdmc+" alt="Indonesian Flag">
  <img src="https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
</p>

<p align="center">
  <strong>Template website modern dan responsif untuk peringatan HUT RI ke-80</strong><br>
  Cocok untuk RT, RW, Kelurahan, Desa, dan komunitas di seluruh Indonesia
</p>

## 🌟 Fitur Utama

### 🎨 **Design & UI/UX**
- ✅ **100% Mobile Responsive** - Optimal di semua perangkat
- ✅ **Tailwind CSS** - Framework modern untuk styling cepat
- ✅ **Font Awesome Icons** - 1000+ ikon profesional
- ✅ **AOS Animations** - Smooth scroll animations yang menarik
- ✅ **Modern Hover Effects** - Interaksi yang responsif

### 🔍 **SEO & Performance**
- ✅ **SEO Optimized** - Meta tags lengkap, Open Graph, Twitter Cards
- ✅ **Fast Loading** - Optimasi gambar dan resource
- ✅ **Progressive Web App Ready** - Dapat diinstall di mobile
- ✅ **Lighthouse Score 90+** - Performance tinggi

### 📱 **Konten Lengkap**
- ✅ **Jadwal Kegiatan** - Perlombaan 17 Agustus & Jalan Sehat
- ✅ **Struktur Panitia** - Sistem manajemen panitia lengkap
- ✅ **Anggaran Transparan** - Tabel anggaran detail dan pembagian
- ✅ **Interactive Maps** - Lokasi kegiatan dengan Leaflet.js
- ✅ **Galeri Foto** - Grid galeri dengan lightbox modal
- ✅ **YouTube Integration** - Embed channel dan video
- ✅ **Contact Forms** - WhatsApp dan social media integration

### ⚙️ **Sistem Konfigurasi**
- ✅ **No-Code Configuration** - Ubah semua data dari file config
- ✅ **Multi-Organization Support** - RT, RW, Kelurahan, Desa
- ✅ **Dynamic Content** - Auto-generate berdasarkan config
- ✅ **Budget Calculator** - Hitung otomatis total anggaran

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/username/indonesia-independence-template.git
cd indonesia-independence-template
```

### 2. Konfigurasi Data
Edit file `config.js` atau langsung di dalam HTML pada bagian `SITE_CONFIG`:

```javascript
const SITE_CONFIG = {
    organization: {
        name: "RW 05 Makmur Jaya",          // Ganti dengan nama organisasi Anda
        type: "RW",                          // RT, RW, Kelurahan, Desa
        number: "05",
        area: "Makmur Jaya"
    },
    
    contact: {
        address: "Jl. Kemerdekaan No. 17",   // Alamat lengkap
        city: "Surakarta",                   // Kota
        province: "Jawa Tengah",             // Provinsi
        phone: "0271-123-4567",              // Nomor telepon
        email: "info@example.com",           // Email
        coordinates: {
            lat: -7.5759,                    // Latitude untuk maps
            lng: 110.8267                    // Longitude untuk maps
        }
    },
    
    // ... konfigurasi lengkap lainnya
};
```

### 3. Sesuaikan Konten
- **Panitia**: Update `committee` section dengan data panitia Anda
- **Anggaran**: Ubah `budget` section sesuai rencana anggaran
- **Kegiatan**: Sesuaikan `events` dengan jadwal dan lokasi
- **Kontak**: Update informasi kontak dan social media

### 4. Deploy
Upload ke hosting favorit Anda:
- **GitHub Pages** (Gratis)
- **Netlify** (Gratis) 
- **Vercel** (Gratis)
- **Shared Hosting** (Berbayar)

## 📁 Struktur File

```
indonesia-independence-template/
├── index.html              # File utama website
