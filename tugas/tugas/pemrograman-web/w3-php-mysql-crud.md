# W3 – PHP Native + MySQL (CRUD)

**Jenis:** Individu | **Tenggat:** Minggu 6 | **Bobot:** 25%

## Tujuan
Membangun aplikasi web dinamis dengan PHP dan MySQL yang aman dan terstruktur.

## Skenario
Buat aplikasi pengelolaan data sederhana (pilih satu): inventaris barang, data pelanggan, daftar tiket/helpdesk, atau katalog produk. Boleh terinspirasi dari kebutuhan di tempat prakerin.

## Persyaratan Teknis
1. **Database** minimal 2 tabel berelasi (misalnya `kategori` dan `barang`), dengan *primary key* dan *foreign key*. Sertakan file `database.sql`.
2. **CRUD lengkap** untuk tabel utama: tambah, tampil (dengan pencarian dan paginasi), ubah, hapus (dengan konfirmasi).
3. **Koneksi memakai PDO** dan **prepared statement** untuk semua query yang menerima input. Dilarang menyambung string SQL dengan variabel langsung.
4. **Keamanan dasar:**
   - Escape output dengan `htmlspecialchars()`.
   - Validasi input di sisi server.
   - Password (bila ada login) disimpan dengan `password_hash()`.
   - Konfigurasi database dipisah di `config.example.php`; `config.php` masuk `.gitignore`.
5. **Login & sesi:** halaman login admin dan proteksi halaman CRUD memakai `session`.
6. Struktur folder rapi, misalnya `config/`, `includes/` (header, footer), `pages/`, `assets/`. Tidak menumpuk semua kode dalam satu file.
7. Pesan sukses/gagal ditampilkan kepada pengguna (*flash message*).

## Yang Dikumpulkan
- Folder `w3-crud-php/` beserta `database.sql`.
- `README.md`: deskripsi, ERD sederhana (gambar atau Mermaid), cara instalasi (XAMPP/Laragon), akun login contoh, tangkapan layar tiap halaman utama.

## Kriteria Keberhasilan
CRUD berjalan, query aman dari SQL injection, struktur kode terpisah, dokumentasi memungkinkan orang lain menjalankan aplikasi dalam 10 menit.
