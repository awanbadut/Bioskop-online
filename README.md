# Movie Laravel

Proyek ini adalah aplikasi berbasis Laravel yang berfungsi untuk mengelola data film. Aplikasi ini menyediakan fitur CRUD (Create, Read, Update, Delete) untuk model Movie, serta fitur pencarian berdasarkan kriteria tertentu.

## Fitur

- **CRUD Movie**: Pengguna dapat menambah, mengedit, dan menghapus data film.
- **Pencarian Movie**: Pengguna dapat mencari film berdasarkan judul, genre, atau tahun rilis.

## Pembaruan Terkini

- **Refactor Fungsi `edit` dan `store`**: Fungsi untuk mengedit dan menyimpan data film telah diperbarui untuk meningkatkan efisiensi dan pengelolaan validasi. Perubahan ini bertujuan untuk memperbaiki alur logika dan mempermudah pengelolaan kode.
  
- **Penambahan Helper**: Sebuah helper baru telah ditambahkan untuk memudahkan penggunaan fungsi yang sering digunakan, seperti manipulasi data dan pengecekan validasi. Helper ini diharapkan dapat mengurangi duplikasi kode dan meningkatkan keterbacaan.

## Persyaratan Sistem

- PHP >= 7.4
- Laravel >= 8.x
- Composer
- MySQL atau database lain yang kompatibel dengan Laravel

## Instalasi

Ikuti langkah-langkah berikut untuk menjalankan aplikasi ini di lingkungan lokal:

### 1. Clone Repository

Clone repository ini ke mesin lokal Anda:
```bash
git clone https://github.com/awanbadut/movie-laravel.git
