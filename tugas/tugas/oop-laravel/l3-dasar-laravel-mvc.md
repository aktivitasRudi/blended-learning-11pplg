# L3 – Dasar Laravel: Routing, Controller, Blade (MVC)

**Jenis:** Individu | **Tenggat:** Minggu 6 | **Bobot:** 20%

## Tujuan
Memahami arsitektur MVC Laravel dan siklus request-response.

## Instruksi
Buat proyek Laravel baru (repositori terpisah) bertema **"Katalog" sederhana** (produk, artikel, atau layanan DUDI fiktif) dengan data statis/array dulu, belum database.

## Persyaratan Teknis
1. **Routing:** minimal 6 route (GET, POST), memakai *named route*, *route parameter*, dan *route group*. Jelaskan fungsi `php artisan route:list`.
2. **Controller:** minimal 2 controller, satu di antaranya **resource controller**. Logika tidak ditulis langsung di route.
3. **Blade:** layout induk (`@extends`/`@yield` atau komponen Blade), minimal 3 halaman, `@foreach`, `@if`, `@include`/komponen, dan helper `route()` dan `asset()`.
4. **Form & validasi:** satu form dengan `@csrf` dan validasi menggunakan **Form Request** atau `$request->validate()`, menampilkan pesan error per kolom dan `old()`.
5. **Middleware:** buat satu middleware kustom (misalnya pembatasan akses berdasarkan parameter/sesi sederhana) dan daftarkan pada route.
6. **Penerapan OOP:** satu *service class* (misalnya `KatalogService`) yang disuntikkan ke controller lewat *dependency injection* bawaan Laravel.
7. Tampilan memakai Vite/asset pipeline bawaan dengan CSS (boleh Tailwind/Bootstrap).

## Yang Dikumpulkan
- Tautan repositori GitHub proyek Laravel.
- `README.md` proyek: deskripsi, cara instalasi (`composer install`, `.env`, `php artisan key:generate`, dst.), daftar route (tabel), tangkapan layar.
- Penjelasan singkat (1 paragraf) tentang alur satu request dari browser hingga tampil, menyebut route, middleware, controller, view.

## Kriteria Keberhasilan
Struktur MVC dipatuhi, validasi dan CSRF berfungsi, service diinjeksi dengan benar, `.env` tidak ikut ter-commit.
