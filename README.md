# Tugas-pert14_24110310078_Siti-Adawiah_2A-BD
# Laporan Tugas Praktikum – Sistem Toko Sepatu
1. Bikin Program Aplikasinya
   Pada bagian ini, saya membuat sebuah program sederhana menggunakan bahasa pemrograman Python yang berfungsi untuk mengelola aktivitas jual beli di toko sepatu. Aplikasi ini berbasis terminal dan terbagi menjadi dua peran utama, yaitu penjual dan pembeli.
# Penjual dapat:
* Menambahkan data sepatu baru ke dalam stok.
* Memperbarui stok dan harga sepatu yang sudah ada.
* Melihat total pemasukan dari hasil transaksi.
* Melihat daftar pembeli dan riwayat pembelian.
# Pembeli dapat:
* Melihat daftar sepatu yang tersedia lengkap dengan harga dan jumlah stok.
* Memesan sepatu dalam jumlah tertentu.
* Melihat total harga yang harus dibayar berdasarkan jumlah yang dipesan.
   Semua data disimpan sementara di memori (tidak menggunakan database atau file), sehingga sistem berjalan cepat dan ringan. Program ini sepenuhnya interaktif dan bisa dijalankan langsung melalui terminal.
  
2. Dokumentasi Teknis (Komentar Penjelasan per Blok Kode)
   Untuk memudahkan pemahaman bagi programmer lain, saya menambahkan komentar-komentar penjelas di dalam setiap bagian penting dalam kode.
* Setiap fungsi seperti menu_penjual() dan menu_pembeli() dijelaskan di atas definisinya agar mudah diketahui apa tujuan fungsi tersebut.
* Di bagian struktur data, seperti dictionary stok_sepatu, diberikan komentar yang menjelaskan bagaimana data sepatu disimpan dan dikelola.
* Untuk pengambilan keputusan menggunakan if, juga ditambahkan komentar agar alur logika bisa dipahami secara cepat.
* Selain itu, bagian-bagian seperti perhitungan total harga, validasi stok, dan penambahan transaksi ke riwayat juga diberi       penjelasan singkat agar jelas bagaimana sistem bekerja.
   Dengan dokumentasi teknis berupa komentar per blok ini, siapa pun yang membaca kodenya bisa mengerti maksud setiap bagian tanpa harus menebak atau membaca keseluruhan program terlebih dahulu.

3. Buat User Manual (Untuk Pengguna Awam)
   User manual ini ditujukan untuk orang awam yang ingin menjalankan aplikasi, tanpa harus tahu cara kerja teknisnya. Berikut panduan dasarnya:
# Cara menjalankan aplikasi:
* Pastikan Python sudah terinstal di komputer.
* Jalankan file Python lewat terminal atau command prompt:
   python toko_sepatu.py
# Jika memilih sebagai penjual, pengguna bisa:
* Menambahkan sepatu baru dan stoknya.
* Melihat stok semua sepatu yang tersedia.
* Memperbarui harga sepatu.
* Melihat total pemasukan.
* Melihat daftar pembeli dan riwayat transaksi.
# Jika memilih sebagai pembeli, pengguna bisa:
* Melihat sepatu yang tersedia.
* Memesan sepatu dan memasukkan jumlah yang diinginkan.
* Mendapatkan informasi total harga yang harus dibayar.
# Contoh notifikasi/peringatan:
* Jika pembeli memasukkan jumlah lebih banyak dari stok, sistem akan menampilkan pesan: "Stok tidak mencukupi".
* Jika sepatu yang dicari tidak ada, sistem akan memberi tahu: "Sepatu tidak ditemukan."

4. Pengujian dan Evaluasi Performa (Jalanin Semua Programnya)
   Pengujian dilakukan dengan menjalankan semua fitur dari aplikasi secara langsung. Saya mencoba beberapa skenario untuk memastikan program berjalan dengan benar.
# Beberapa hal yang diuji:
* Penambahan sepatu baru ke dalam stok.
* Pemesanan sepatu dengan jumlah yang valid.
* Simulasi pembelian dengan jumlah melebihi stok (hasilnya: sistem menolak dan memberi peringatan).
* Melihat laporan pemasukan dan riwayat transaksi.
* Mengetes input tidak valid (misalnya, sepatu yang tidak ada dalam daftar).
# Hasil evaluasi:
* Semua fitur berjalan sesuai fungsinya.
* Program cukup ringan dan cepat dijalankan.
* Tidak ada error fatal saat diuji dengan input yang bermacam-macam.
* Sistem memberi feedback yang jelas ketika terjadi kesalahan input.
  Aplikasi ini terbukti stabil dan efisien untuk kebutuhan sistem sederhana seperti pengelolaan toko sepatu. Ke depannya, sistem ini masih bisa dikembangkan lagi, misalnya dengan menyimpan data ke file atau menambahkan antarmuka grafis (GUI).

