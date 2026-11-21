# TaskFlow — Full-stack Task Management

[![Build frontend](https://github.com/hilman-devop/task-management/actions/workflows/frontend-build.yml/badge.svg)](https://github.com/hilman-devop/task-management/actions/workflows/frontend-build.yml)
> Aplikasi manajemen tugas full-stack dengan Laravel API, React, board kanban, drag-and-drop, dan autentikasi token.

**Stack:** Laravel 11 · React 18 · Vite · Sanctum

![Preview](https://raw.githubusercontent.com/hilman-devop/task-management/main/img/img1.png)

## Ringkasan

Aplikasi manajemen tugas full-stack dengan Laravel API, React, board kanban, drag-and-drop, dan autentikasi token.

## Fitur utama

- Register, login, dan logout dengan Sanctum
- Board kolom bergaya kanban
- Drag-and-drop task
- CRUD task dan kolom
- Prioritas dan due date
- Frontend dan backend terpisah

## Menjalankan secara lokal

~~~bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve
cd ../frontend
npm install
npm run dev
~~~

## Keamanan dan batasan

Credential demo hanya untuk development. Ganti secret, akun seed, CORS, dan URL API sebelum deployment.

Jangan commit API key, password, token, session ID, data pribadi, atau credential deployment.

## Status

Project portfolio aktif oleh **Hilman Arifin Ilham**. Verifikasi ulang dependency dan konfigurasi sebelum deployment production.

## Lisensi

Belum ada lisensi open-source yang dinyatakan. Hubungi pemilik repository sebelum menggunakan ulang atau mendistribusikan kode.

---

Dibuat oleh [Hilman Arifin Ilham](https://github.com/hilman-devop).
