# L1 – OOP PHP Dasar

**Jenis:** Individu | **Tenggat:** Minggu 2 | **Bobot:** 15%

## Tujuan
Memahami konsep class, object, property, method, constructor, dan encapsulation di PHP 8+.

## Skenario
Buat program CLI (dijalankan lewat terminal) **sistem inventaris/perpustakaan mini**. Pilih salah satu domain:
- Perpustakaan: `Buku`, `Anggota`, `Peminjaman`
- Toko: `Produk`, `Keranjang`, `Pesanan`
- Helpdesk: `Tiket`, `Pengguna`

## Persyaratan Teknis
1. Minimal **3 class** dalam file terpisah di folder `src/`, dengan *namespace* dan *autoload* PSR-4 lewat Composer.
2. Memakai **constructor** (boleh *constructor property promotion*), *typed properties*, dan *return type*.
3. **Encapsulation:** property bersifat `private`/`protected`, diakses lewat getter/setter yang memvalidasi data (misalnya stok tidak boleh negatif).
4. Minimal satu **static method/property** dan satu **konstanta class**, dengan alasan penggunaannya.
5. Minimal satu **exception kustom** untuk kondisi error (misalnya `StokTidakCukupException`).
6. File `index.php` yang mensimulasikan skenario penggunaan (membuat objek, memanggil method, menangani exception).
7. Minimal **5 unit test** sederhana memakai PHPUnit (atau pengujian manual terdokumentasi jika PHPUnit belum dikuasai).

## Yang Dikumpulkan
- Folder `l1-oop-dasar/` dengan `composer.json`.
- `README.md`: penjelasan rancangan, **diagram kelas** (Mermaid `classDiagram` atau gambar), cara menjalankan, contoh keluaran.

## Kriteria Keberhasilan
Class dirancang dengan tanggung jawab jelas, encapsulation benar, autoload berfungsi, ada penanganan error dan diagram kelas.
