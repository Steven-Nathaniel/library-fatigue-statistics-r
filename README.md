# Analisis Statistik Keletihan Belajar Mahasiswa di Perpustakaan UMN

Penelitian kuantitatif tentang pengaruh gangguan lingkungan belajar di perpustakaan terhadap tingkat keletihan mahasiswa Sistem Informasi, dianalisis dengan **R**.

Proyek kelompok (3 orang), mata kuliah **Probability and Statistics**, Universitas Multimedia Nusantara, 2025.

## Variabel

- **X (independen):** gangguan lingkungan belajar di perpustakaan, misalnya kebisingan dan aktivitas pengunjung lain
- **Y (dependen):** tingkat keletihan mahasiswa

## Data

Survei kuesioner kepada **54 responden valid** mahasiswa Sistem Informasi yang rutin belajar di perpustakaan kampus.

Nama responden sudah **dianonimkan** menjadi kode `R01`–`R54` di [`data/survei_anonim.csv`](data/survei_anonim.csv).

## Langkah analisis

1. Pembersihan data dan pemilihan responden valid
2. Statistik deskriptif, histogram, dan diagram batang (jenis kelamin, status jenuh)
3. Uji normalitas (Shapiro-Wilk)
4. Analisis korelasi
5. Regresi linear sederhana beserta uji asumsinya

## Hasil utama

- Model regresi memiliki **R² = 0,356**: sekitar 35,6% variasi tingkat keletihan dapat dijelaskan oleh gangguan lingkungan belajar.
- Hubungannya cukup berarti, tetapi masih ada faktor lain di luar model. Penelitian berikutnya bisa menambahkan variabel independen lain.

## Tools

R · R Markdown · dplyr · ggplot2 · psych · car · nortest · lmtest · corrplot

## Cara menjalankan

Buka `analisis_keletihan_mahasiswa.Rmd` di RStudio, lalu klik **Knit**. Paket yang dibutuhkan akan terpasang otomatis.

## Dokumen dan Bukti Pengerjaan

| File | Isi |
|---|---|
| [`laporan/jurnal_analisis_keletihan.pdf`](laporan/jurnal_analisis_keletihan.pdf) | Jurnal ilmiah ringkasan penelitian |
| [`laporan/laporan_analisis_keletihan.pdf`](laporan/laporan_analisis_keletihan.pdf) | Laporan penelitian lengkap (Bab I sampai V) |

> Data pribadi anggota tim (nama, NIM, email) sudah dihapus dari dokumen.
