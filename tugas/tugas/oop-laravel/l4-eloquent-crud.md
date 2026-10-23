# L4 – Eloquent, Migration & CRUD

**Jenis:** Individu | **Tenggat:** Minggu 8 | **Bobot:** 20%

## Tujuan
Mengelola database dengan migration, model Eloquent, dan relasi antar tabel.

## Instruksi
Kembangkan proyek L3 (atau proyek baru) menjadi aplikasi **CRUD berbasis database**, misalnya manajemen produk dan kategori, artikel dan penulis, atau tiket helpdesk.

## Persyaratan Teknis
1. **Migration** minimal 3 tabel, dengan *foreign key* dan `onDelete` yang tepat. Gunakan `php artisan migrate:fresh --seed` untuk membuktikan reproduksi.
2. **Model Eloquent** dengan `$fillable`, `casts`, dan **relasi** minimal: satu `hasMany`/`belongsTo` dan satu `belongsToMany` (tabel pivot).
3. **Seeder & Factory** untuk data uji (minimal 20 data per tabel utama) dengan Faker.
4. **CRUD lengkap** untuk entitas utama via resource controller, dengan:
   - *Pagination* dan pencarian.
   - **Eager loading** (`with()`) untuk menghindari masalah N+1. Jelaskan perbedaannya di README.
   - **Form Request** untuk validasi.
   - **Route model binding**.
5. Satu **Query Scope** (misalnya `scopeAktif`) dan satu **accessor/mutator**.
6. **Upload gambar** memakai `Storage` dan `php artisan storage:link`.
7. **Penerapan OOP:** pindahkan logika bisnis ke *service class* atau *action class*. Controller maksimal ±20 baris per method.
8. Minimal 5 **Feature Test** (PHPUnit/Pest): contohnya membuat data, validasi gagal, hapus data.

## Yang Dikumpulkan
- Tautan repositori proyek.
- `README.md`: ERD, daftar fitur, cara instalasi, tangkapan layar, hasil `php artisan test`.

## Kriteria Keberhasilan
Migration dan relasi benar, tidak ada query N+1 pada halaman daftar, validasi dan upload berfungsi, ada pengujian yang lulus.
