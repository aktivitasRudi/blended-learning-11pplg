# L2 – OOP Lanjut: Inheritance, Polymorphism, Abstract, Interface, Trait

**Jenis:** Individu | **Tenggat:** Minggu 4 | **Bobot:** 20%

## Tujuan
Menerapkan pilar OOP secara lengkap dan memahami kapan memakai masing-masing konsep.

## Skenario
Kembangkan salah satu: **sistem pembayaran** (Tunai, Transfer, E-Wallet), **sistem notifikasi** (Email, SMS, WhatsApp), atau **sistem diskon/pajak** untuk toko.

## Persyaratan Teknis
1. **Abstract class** sebagai kerangka dengan minimal satu abstract method.
2. **Interface** minimal satu (misalnya `Dapat_Dikirim`/`Payable`), diimplementasikan oleh beberapa class.
3. **Inheritance:** minimal 3 level atau 3 subclass, dengan `parent::` dan *method overriding*.
4. **Polymorphism:** satu fungsi/class memproses berbagai objek melalui tipe interface/abstract (*type hinting*), tanpa `if/else` per jenis.
5. **Trait** minimal satu untuk perilaku yang dipakai ulang (misalnya `MencatatLog`).
6. **Dependency Injection** sederhana lewat constructor (kelas bergantung pada interface, bukan implementasi konkret).
7. **Enum** PHP 8.1+ untuk status/jenis.
8. Penerapan prinsip **SOLID**: pilih minimal 2 prinsip (misalnya S dan O) dan jelaskan di README bagaimana kodemu menerapkannya.
9. Minimal 8 pengujian (PHPUnit atau skenario manual).

## Yang Dikumpulkan
- Folder `l2-oop-lanjut/`.
- `README.md`: diagram kelas, penjelasan tiap konsep OOP dan letaknya di kode (nama file dan baris), contoh keluaran.
- Jawaban singkat: **(a)** apa beda abstract class dan interface, dan kapan memilih masing-masing? **(b)** apa masalah jika polymorphism diganti rantai `if/else`?

## Kriteria Keberhasilan
Seluruh konsep terpakai secara wajar (bukan sekadar menempel), desain mudah diperluas, penjelasan konseptual benar.
