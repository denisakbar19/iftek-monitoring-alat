<p align="center"><strong>IFTEK Monitoring Alat</strong></p>

# Tentang aplikasi

Aplikasi monitoring inspeksi, pending pekerjaan, breakdown, dan kesehatan alat berbasis Laravel.

## Fitur utama

- Login menggunakan nomor induk dan kata sandi
- Dashboard ringkasan kerusakan open dan close
- Inspeksi dan temuan kerusakan alat
- Papan backlog dan pekerjaan pending
- Riwayat kerusakan berdasarkan kode alat
- Catatan jam breakdown mingguan, bulanan, dan tahunan
- Upload foto kerusakan
- Akses publik untuk melihat ringkasan, dengan pencatatan khusus pengguna login

## Persyaratan

- PHP 8.2+
- Composer
- Node.js 18+
- MySQL/MariaDB

## Instalasi

```bash
composer create-project laravel/laravel .
composer require laravel/breeze --dev
php artisan breeze:install blade
npm install
npm run build
cp .env.example .env
php artisan key:generate
```

Atur database pada `.env`, lalu jalankan:

```bash
php artisan migrate
php artisan storage:link
php artisan serve
```
