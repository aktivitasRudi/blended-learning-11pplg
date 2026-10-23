# Mapel OOP & Laravel – Kelas XI PPLG

Rangkaian tugas dari konsep **OOP di PHP** hingga **aplikasi Laravel** utuh. Dikerjakan mandiri secara daring selama prakerin.

| No | Tugas | Fokus | Tenggat | Bobot |
|----|-------|-------|---------|-------|
| L1 | [OOP PHP Dasar](l1-oop-dasar.md) | Class, object, encapsulation | Minggu 2 | 15% |
| L2 | [OOP Lanjut](l2-oop-lanjut.md) | Inheritance, polymorphism, abstract, interface, trait | Minggu 4 | 20% |
| L3 | [Dasar Laravel: Routing, Controller, Blade](l3-dasar-laravel-mvc.md) | MVC | Minggu 6 | 20% |
| L4 | [Eloquent, Migration & CRUD](l4-eloquent-crud.md) | Database, relasi | Minggu 8 | 20% |
| L5 | [Proyek Akhir Laravel](l5-proyek-akhir-laravel.md) | Aplikasi utuh | Minggu 10 | 25% |

## Persiapan lingkungan
Ikuti dokumentasi resmi https://laravel.com/docs untuk **versi Laravel stabil terbaru** beserta syarat versi PHP dan Composer-nya. Dokumentasi resmi adalah acuan utama jika ada perbedaan dengan tutorial lama.

## Struktur pengumpulan
```
submissions/NN-nama-kamu/oop-laravel/
├── l1-oop-dasar/
├── l2-oop-lanjut/
└── (L3–L5: repositori Laravel terpisah, tautannya ditulis di README)
```

## Aturan untuk proyek Laravel
- Proyek Laravel (L3–L5) **dibuat sebagai repositori terpisah** di akun GitHub-mu agar ukurannya wajar. Tautkan di `README.md` folder pribadimu dan di Pull Request.
- **Jangan** commit folder `vendor/`, `node_modules/`, dan file `.env`. Sertakan `.env.example`.
- Gunakan branch per fitur (`fitur-login`, `fitur-crud-produk`) dan gabungkan lewat Pull Request di repositorimu sendiri.
- Rubrik: [templates/rubrik-web-laravel.md](../../templates/rubrik-web-laravel.md)
