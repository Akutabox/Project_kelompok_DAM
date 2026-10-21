# Project_kelompok_DAM

## Anggota Kelompok

| No. | Nama Anggota | NIM |
|-----|--------------|-----|
| 1   | Ahmad Paesol | 2501010143 |
| 2   | Billy Maulana Hasan | 2501010140 |

# Peta & Ulasan Warung Kuliner Denpasar

## 1. Tabel Perbandingan Karakteristik Empat Jenis Data

Membuat tabel perbandingan karakteristik empat jenis data, yaitu teks, gambar, audio, dan spasial, dengan minimal enam atribut pembanding.

## 2. Skenario Akuisisi Data dan Estimasi Storage

Merancang skenario akuisisi data untuk tema Peta & Ulasan Warung Kuliner Denpasar, kemudian menghitung estimasi kebutuhan penyimpanan selama satu tahun dengan asumsi pertumbuhan data sebesar 10% per bulan.

Analisis kebutuhan data mencakup:
- Daftar jenis data yang dibutuhkan.
- Karakteristik setiap jenis data berdasarkan enam pertanyaan kerangka.
- Asumsi jumlah unit data dan ukuran rata-rata setiap unit.
- Estimasi total storage ditambah cadangan sebesar 30%.

## 3. Alasan Multimedia Tidak Disimpan Langsung sebagai BLOB

Alasan Multimedia Tidak Disimpan Langsung sebagai BLOB dalam Basis Data Relasional

BLOB (*Binary Large Object*) adalah tipe data yang digunakan untuk menyimpan data biner, seperti gambar, audio, dan video, secara langsung di dalam basis data. Namun, penyimpanan multimedia sebagai BLOB sebaiknya dihindari jika jumlah dan ukuran berkas cukup besar karena dapat membuat ukuran basis data meningkat, memperlambat proses pencadangan dan pemulihan data, serta membuat pengelolaan berkas menjadi lebih sulit.

Sebagai alternatif, berkas multimedia dapat disimpan secara terpisah, misalnya di Google Drive atau layanan penyimpanan berkas lainnya. Basis data relasional cukup menyimpan informasi terkait, seperti nama berkas, jenis berkas, ukuran, dan lokasi atau URL berkas tersebut. Dengan cara ini, data lebih mudah dikelola dan penggunaan basis data menjadi lebih efisien.

Dalam proyek peta dan ulasan warung kuliner Denpasar, informasi warung, ulasan, dan metadata dapat disimpan dalam basis data, sedangkan foto warung disimpan secara terpisah. GitHub digunakan untuk menyimpan kode program, notebook, dan dokumentasi proyek, bukan sebagai tempat penyimpanan utama untuk seluruh foto berukuran besar.

## Kesimpulan

Analisis kebutuhan data pada proyek Peta & Ulasan Warung Kuliner Denpasar dilakukan untuk mengetahui jenis data yang dibutuhkan, karakteristik setiap jenis data, serta estimasi kapasitas penyimpanan yang diperlukan. Melalui perbandingan data teks, gambar, audio, dan spasial, dapat diketahui bahwa setiap jenis data memiliki karakteristik dan kebutuhan penyimpanan yang berbeda. Perhitungan estimasi storage selama satu tahun dengan asumsi pertumbuhan 10% per bulan dan cadangan sebesar 30% membantu mempersiapkan kapasitas penyimpanan yang memadai. Selain itu, penyimpanan berkas multimedia secara terpisah dari basis data relasional dapat membantu meningkatkan efisiensi pengelolaan data, terutama ketika jumlah dan ukuran berkas semakin besar.
