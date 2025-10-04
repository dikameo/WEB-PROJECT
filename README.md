# WEB-PROJECT


# Company Website CRUD Laravel

## Deskripsi Proyek
Proyek ini merupakan pengembangan website sederhana untuk perusahaan menggunakan framework Laravel dengan fitur CRUD (Create, Read, Update, Delete) untuk mengelola data seperti profil perusahaan, produk, dan kontak. Proyek ini dikembangkan secara kolaboratif oleh 4 anggota tim untuk mempelajari best practices dalam pengembangan web full-stack menggunakan Laravel.

Proyek ini mencakup:
- Halaman utama (Home) dengan informasi perusahaan.
- Dashboard admin untuk CRUD data.
- Integrasi database MySQL untuk menyimpan data.
- Autentikasi user menggunakan Laravel Breeze.

## Fitur Proyek
Proyek ini dirancang sebagai website sederhana untuk perusahaan dengan fokus pada operasi CRUD (Create, Read, Update, Delete). Berikut adalah daftar fitur utama yang telah diimplementasikan:

### Fitur Utama
- **Halaman Utama (Home)**: Menampilkan informasi umum perusahaan, seperti deskripsi, visi-misi, dan galeri gambar. Responsif untuk desktop dan mobile.
- **Dashboard Admin**: Antarmuka khusus untuk admin dengan navigasi mudah untuk mengelola semua data.
- **Autentikasi User**: Sistem login/register menggunakan Laravel Breeze, termasuk middleware untuk proteksi route admin.
- **CRUD Profil Perusahaan**: 
  - Buat/edit/hapus data profil (nama, alamat, deskripsi).
  - Tampilkan data secara dinamis di halaman home.
- **CRUD Produk**:
  - Kelola daftar produk (nama, harga, deskripsi, gambar).
  - Galeri produk dengan pagination dan search sederhana.
- **CRUD Kontak**:
  - Tambah/edit/hapus info kontak (email, telepon, alamat cabang).
  - Form kontak visitor yang terintegrasi dengan email notification (menggunakan Mail Laravel).
- **Integrasi Database**: Menggunakan MySQL untuk penyimpanan data, dengan migration dan seeder untuk setup awal.

### Fitur Tambahan
- **Validasi Input**: Form validasi lengkap untuk mencegah data invalid (misalnya, email format, ukuran file gambar).
- **Upload Gambar**: Dukungan upload file untuk produk dan profil, disimpan di storage Laravel.
- **Search dan Filter**: Pencarian sederhana di dashboard untuk data produk dan kontak.
- **Responsive Design**: Menggunakan Tailwind untuk tampilan yang adaptif di berbagai perangkat.
- **Error Handling**: Penanganan error global dengan logging ke file.
- **Optimasi Dasar**: Caching route dan query untuk performa lebih baik.
  


### CATATAN PENTING
1. ERROR ENV BELUM ADA
- Copy file .env.example ke .env
- php artisan key:generate

2. ERROR DATABSE.SQLITE
- jalankan perintah terminal
type nul > database\database.sqlite
- php artisan migrate




## Anggota Tim
Proyek ini dikerjakan oleh 4 orang dengan pembagian tugas sebagai berikut:

| Nama Anggota | NIM | Tugas Utama |
|--------------|-----------------|-------------|
| Wahyu Andika | 202310370311075 | - |
| Ahmad Nur Mu'minin | 202310370311089 | - |
| Yogi Aditya Narotama | 202310370311069 | - |
| Feri Yusgiantoro | 202310370311101 | - |

## Versi Tools dan Dependencies
Proyek ini dibangun menggunakan stack teknologi berikut:

- **Laravel**: Versi 12.32.5
- **PHP**: Versi 8.2.12
- **Composer**: Versi  2.8.1 

Pastikan versi tools Anda sesuai untuk menghindari konflik.


