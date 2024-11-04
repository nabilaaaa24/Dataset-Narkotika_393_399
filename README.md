# Dataset-Narkotika_393_399

## Dataset Putusan Pengadilan Negeri Surabaya: Kasus Narkotika dan Psikotropika (2022-2024)

Dataset ini adalah koleksi 50 putusan Pengadilan Negeri Surabaya antara tahun 2022 hingga 2024 dalam kategori _Pidana Khusus_, yang fokus pada kasus Narkotika dan Psikotropika. Dataset ini berguna untuk eksplorasi dan analisis pola penanganan kasus narkotika yang tidak/belum berkekuatan hukum tetap.

## Struktur Dataset

### Folder Dataset
- **Narkotika.zip**: Berisi 50 dokumen PDF putusan yang dikumpulkan dari website Direktori Putusan Mahkamah Agung RI: https://putusan3.mahkamahagung.go.id/direktori.html. Setiap file memuat informasi rinci mengenai kasus spesifik, termasuk data terdakwa, fakta persidangan, dan putusan akhir. 

### Folder Overview
- **Overview.xlsx**: Ringkasan informasi setiap putusan dalam bentuk tabel untuk memudahkan pencarian dan analisis data. Tabel ini memiliki kolom:
  - **No**: Nomor urut data.
  - **No Putusan**: Nomor referensi dari putusan pengadilan.
  - **Lembaga Peradilan**: Nama pengadilan yang menangani kasus (semua putusan dalam dataset ini berasal dari Pengadilan Negeri Surabaya).
  - **Barang Bukti**: Detail barang bukti yang disita dalam setiap kasus, seperti jenis dan jumlah narkotika.
  - **Amar Putusan**: Rangkuman putusan atau hukuman yang dijatuhkan kepada terdakwa.

## Tujuan dan Potensi Penggunaan

Dataset ini dirancang untuk penelitian dan analisis Temu Kembali Informasi pada konteks hukum. Potensi penggunaannya mencakup:
- **Pengembangan Model IR**: Memungkinkan perancangan dan pengujian sistem temu kembali dokumen yang dapat membantu dalam menemukan putusan berdasarkan kata kunci atau entitas spesifik.
- **Analisis Semantik Putusan**: Mendalami korelasi antara barang bukti dan amar putusan dalam konteks pidana narkotika.
- **Penerapan NLP pada Dokumen Hukum**: Menggunakan teknik _Natural Language Processing_ (NLP) untuk melakukan ekstraksi informasi otomatis seperti entitas, klasifikasi dokumen, atau sentimen putusan.
  
## Langkah Akses dan Penggunaan

1. **Ekstraksi PDF**: Buka dan analisis file PDF di dalam `Narkotika.zip`.
2. **Analisis Data dari Overview.xlsx**: Gunakan data dalam _file .xlsx_ untuk pencarian cepat dan pengelompokan data berdasarkan parameter seperti barang bukti atau putusan.

## Lisensi

Dataset ini tersedia untuk tujuan pendidikan dan penelitian dengan tetap memperhatikan hak cipta dari dokumen resmi pengadilan yang relevan. Penggunaan data ini harus sejalan dengan etika penelitian dan peraturan yang berlaku.
