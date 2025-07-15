# Tugas-pert14_24110310078_Siti-Adawiah_2A-BD
1. Pengembangan Aplikasi
Deskripsi:
   Aplikasi ini merupakan sistem toko sepatu berbasis CLI (Command Line Interface) dengan dua peran utama: penjual dan pembeli. Aplikasi ini dibangun menggunakan bahasa Python dan bersifat interaktif.
#Fitur yang diimplementasikan:
-Implementasi lengkap sistem inventori (sepatu, stok, harga)
-Penambahan fitur tambahan:
-Laporan pemasukan
-Riwayat pembelian
-Data pembeli
#Optimisasi kode:
-Struktur modular (fungsi khusus untuk penjual dan pembeli)
-Menghindari duplikasi kode
-Menggunakan struktur data efisien (dictionary dan list)
#Contoh fitur utama:
-Penjual dapat menambahkan sepatu baru, mengatur stok, melihat pemasukan, dan mengecek data pembeli.
-Pembeli dapat melihat stok, memesan sepatu, dan mendapatkan rincian total harga secara otomatis.

2. Dokumentasi Teknis
Dokumen Spesifikasi Sistem:
#Aplikasi dijalankan berbasis CLI.
#Terdapat 2 peran pengguna:
-Penjual: Memiliki akses penuh terhadap data, stok, dan transaksi.
-Pembeli: Hanya dapat melihat stok dan melakukan pembelian.
#Setiap sepatu memiliki atribut:
-Nama sepatu
-Jumlah stok
-Harga satuan
Code Documentation:
# Fungsi menu_penjual():
# Menyediakan fitur untuk melihat pemasukan, mengelola stok sepatu, dan melihat data transaksi serta pembeli.

# Fungsi menu_pembeli():
# Menyediakan antarmuka bagi pembeli untuk melihat stok dan melakukan pemesanan sepatu.

# Struktur data utama:
# stok_sepatu = {nama_sepatu: {"stok": jumlah, "harga": harga}}
# riwayat_pembelian = [ {nama_pembeli, nama_sepatu, jumlah, total_harga}, ... ]
# data_pembeli = [nama_pembeli1, nama_pembeli2, ...]

Diagram Alur Kerja (bisa digambarkan atau ditulis deskripsi):

[ Main Menu ]
   ├──> Penjual
   │     ├── Lihat Pemasukan
   │     ├── Tambah Stok Sepatu
   │     ├── Lihat Stok
   │     ├── Riwayat Pembelian
   │     └── Data Pembeli
   └──> Pembeli
         ├── Lihat Stok
         └── Pesan Sepatu

3. User Manual
Panduan Instalasi dan Konfigurasi:
1. Install Python (minimal versi 3.8)
2. Simpan file program sebagai toko_sepatu.py
3. Jalankan melalui terminal atau command prompt:
python toko_sepatu.py
Tutorial Penggunaan Aplikasi:
-Setelah menjalankan program, pengguna akan diminta memilih peran: penjual atau pembeli.
-Jika masuk sebagai Penjual, tersedia pilihan untuk menambah stok, melihat pemasukan, dan mengakses riwayat.
-Jika masuk sebagai Pembeli, pengguna dapat melihat stok sepatu dan memesan dengan jumlah tertentu.
-Semua interaksi dilakukan melalui input teks di terminal.
FAQ dan Troubleshooting Guide:
Q: Apakah stok akan otomatis berkurang setelah pembelian?
A: Ya, stok akan berkurang sesuai jumlah pembelian.

Q: Bagaimana jika sepatu tidak ditemukan saat pembelian?
A: Akan muncul pesan "Sepatu tidak ditemukan".

Q: Apakah sistem menyimpan data setelah program ditutup?
A: Tidak. Ini versi sederhana tanpa database. Untuk versi lanjutan bisa ditambahkan penyimpanan ke file JSON/CSV.

4. Pengujian dan Evaluasi
Test Suite yang Komprehensif:
-Input pembeli dengan jumlah valid → stok berkurang sesuai
-Input pembeli dengan jumlah melebihi stok → sistem menolak pembelian
-Penjual menambahkan sepatu baru → muncul di daftar stok
-Data pembeli dan riwayat transaksi tercatat
Laporan Hasil Pengujian:
| Fitur               | Input                          | Output yang Diharapkan             | Status |
| ------------------- | ------------------------------ | ---------------------------------- | ------ |
| Tambah Stok Sepatu  | Sepatu baru, 5 pcs, 200.000    | Sepatu muncul di daftar stok       | ✅      |
| Pembelian Sepatu    | Nama: Ana, Sepatu: Puma, 2 pcs | Total harga muncul, stok berkurang | ✅      |
| Lihat Riwayat       | -                              | Menampilkan riwayat pembelian      | ✅      |
| Invalid Jumlah Beli | Beli 20 padahal stok 5         | Muncul pesan stok tidak mencukupi  | ✅      |

-Analisis Kinerja dan Optimisasi:
-Aplikasi sangat ringan karena berbasis CLI dan tidak bergantung pada library eksternal.
-Menggunakan loop dan struktur dict efisien untuk akses data.
-Bisa dikembangkan lebih lanjut menjadi versi GUI dengan Tkinter atau web-based dengan Flask/Django.



