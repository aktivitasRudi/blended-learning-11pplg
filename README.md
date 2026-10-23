# Blended Learning Prakerin – Kelas XI PPLG

Repositori pembelajaran *blended* untuk siswa **Kelas XI Pengembangan Perangkat Lunak dan Gim (PPLG)** selama **Praktik Kerja Industri (Prakerin)**.

Selama prakerin, kamu belajar di dunia kerja. Repositori ini adalah **ruang belajar tambahan** agar pengalamanmu terdokumentasi, terukur, dan sekaligus menjadi **portofolio GitHub** pertamamu.

## Tujuan
1. Mendokumentasikan kegiatan prakerin secara rutin dan profesional.
2. Membiasakan alur kerja Git/GitHub (fork, branch, commit, pull request) seperti di industri.
3. Menghubungkan pengalaman di DUDI dengan kompetensi PPLG di sekolah.
4. Menghasilkan portofolio: jurnal, analisis, mini project, dan laporan akhir.

## Daftar Tugas

| No | Tugas | Jenis | Tenggat | Bobot |
|----|-------|-------|---------|-------|
| 1 | [Profil DUDI & Setup Repositori](tugas/tugas-01-profil-dudi.md) | Individu | Minggu 1 | 10% |
| 2 | [Jurnal Harian Prakerin](tugas/tugas-02-jurnal-harian.md) | Individu (rutin) | Tiap Jumat | 25% |
| 3 | [Analisis Teknologi & Alur Kerja](tugas/tugas-03-analisis-teknologi.md) | Individu | Minggu 3 | 15% |
| 4 | [Mini Project / Kontribusi Nyata](tugas/tugas-04-mini-project.md) | Individu | Minggu 6 | 30% |
| 5 | [Laporan Akhir & Refleksi](tugas/tugas-05-laporan-akhir.md) | Individu | Akhir prakerin | 20% |

> Tenggat dalam "minggu" dihitung sejak hari pertama prakerin. Guru dapat menyesuaikan tanggal pastinya di kolom Tenggat.

## Cara Mengumpulkan Tugas (Alur Git)

```bash
# 1. Fork repositori ini lewat tombol "Fork" di GitHub, lalu clone fork-mu
git clone https://github.com/<username-kamu>/blended-learning-11pplg.git
cd blended-learning-11pplg

# 2. Buat folder pribadi dengan format NN-nama-kamu (NN = nomor absen)
#    Salin isi submissions/_contoh-01-nama-siswa sebagai kerangka

# 3. Buat branch untuk tiap tugas
git checkout -b tugas-01-namakamu

# 4. Kerjakan, lalu commit
git add .
git commit -m "tugas-01: tambah profil DUDI"

# 5. Push dan buat Pull Request ke repositori guru
git push origin tugas-01-namakamu
```

Setelah push, buka GitHub dan klik **Compare & pull request**. Isi templat PR yang muncul. Guru akan memberi *review* dan komentar. Perbaiki sesuai komentar, lalu commit lagi ke branch yang sama.

## Aturan Penting
- **Jangan** mengunggah data rahasia perusahaan: kode sumber internal, password, API key, data pelanggan, atau dokumen berlabel *confidential*. Gunakan versi disamarkan atau buatan sendiri. Minta izin pembimbing DUDI bila ragu.
- Tulis dengan bahasa sendiri. Plagiarisme dan salin-tempel dari AI tanpa pemahaman akan menurunkan nilai.
- Gunakan pesan commit yang jelas, misalnya `tugas-02: jurnal minggu 3`.
- Satu tugas = satu branch = satu Pull Request.
- Terlambat mengumpulkan: pengurangan nilai sesuai kesepakatan kelas.

## Penilaian
Rubrik lengkap ada di [templates/rubrik-penilaian.md](templates/rubrik-penilaian.md). Aspek yang dinilai: kelengkapan, kualitas isi, ketepatan waktu, kerapian Git, dan profesionalisme.

## Struktur Repositori
```
blended-learning-11pplg/
├── README.md
├── .github/PULL_REQUEST_TEMPLATE.md
├── tugas/                  # Instruksi tiap tugas
├── templates/              # Templat jurnal, laporan, rubrik
└── submissions/            # Hasil kerja siswa (satu folder per siswa)
```

## Bantuan
Pertanyaan seputar tugas: buka tab **Issues** dan pilih *New issue*, atau tanyakan di grup kelas. Pertanyaan yang baik membantu teman lain juga.

Selamat berprakerin dan selamat belajar! 🚀
