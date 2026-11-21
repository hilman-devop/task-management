# TaskFlow — Full-stack Task Management

![Laravel 11](https://img.shields.io/badge/Laravel_11-2f81f7?style=flat) ![React 18](https://img.shields.io/badge/React_18-2f81f7?style=flat) ![Vite](https://img.shields.io/badge/Vite-2f81f7?style=flat) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-2f81f7?style=flat) ![Sanctum](https://img.shields.io/badge/Sanctum-2f81f7?style=flat) ![SQLite](https://img.shields.io/badge/SQLite-2f81f7?style=flat)

> Task board bergaya kanban untuk mengelola kolom, prioritas, deadline, dan tugas secara responsif.

## Tentang proyek

Task board bergaya kanban untuk mengelola kolom, prioritas, deadline, dan tugas secara responsif. Dokumentasi ini dibuat sebagai panduan singkat untuk memahami ruang lingkup proyek, menjalankannya secara lokal, dan membaca batasan penggunaannya.

## Fitur utama

- Autentikasi Laravel Sanctum
- Board kolom dengan drag-and-drop
- CRUD task dan kolom
- Prioritas dan due date
- Optimistic UI update
- Frontend dan backend terpisah

## Teknologi

- Laravel 11
- React 18
- Vite
- Tailwind CSS
- Sanctum
- SQLite

## Menjalankan secara lokal

Prasyarat dan konfigurasi dapat berbeda menurut sistem operasi. Contoh langkah utama:

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

# terminal lain
cd frontend
npm install
npm run dev
```

## Struktur dan pengembangan

Mulai dari entry point dan folder konfigurasi proyek. Pisahkan credential lokal dari source code, tambahkan test untuk perubahan penting, dan gunakan environment variable untuk konfigurasi deployment.

## Keamanan

- Jangan commit API key, password, token, session ID, atau data pribadi.
- Gunakan file environment lokal dan contoh konfigurasi tanpa nilai rahasia.
- Uji perubahan pada environment development sebelum deployment.

## Status

Proyek ini merupakan bagian dari portofolio **Hilman Arifin Ilham** dan dapat dikembangkan sesuai kebutuhan penggunaan.

> **Catatan:** Gunakan credential demo hanya untuk development. Ganti secret dan akun seed sebelum deployment.

## Lisensi

Belum ada lisensi open-source yang dinyatakan di repository ini. Hubungi pemilik repository sebelum menggunakan ulang atau mendistribusikan kode.

---

Dibuat oleh [Hilman Arifin Ilham](https://github.com/hilman-devop).
