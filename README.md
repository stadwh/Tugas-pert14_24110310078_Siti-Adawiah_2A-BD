# Tugas-praktikum toko sepatu
1. Pengembangan Aplikasi
   Pada tahap ini, saya membuat sebuah aplikasi sederhana untuk mengelola toko sepatu. Sistem ini berjalan melalui terminal (text-based) dan bisa digunakan oleh dua jenis pengguna, yaitu penjual dan pembeli. Masing-masing punya fungsi yang berbeda: penjual bisa menambahkan sepatu baru, mengatur stok dan harga, melihat pemasukan dari penjualan, serta mengecek riwayat pembelian dan data pembeli. Sedangkan pembeli bisa melihat daftar sepatu yang tersedia dan melakukan pemesanan sesuai dengan kebutuhan mereka.
   Aplikasi ini juga saya lengkapi dengan fitur tambahan seperti pencatatan riwayat pembelian secara otomatis dan laporan pemasukan penjualan. Supaya sistem tetap ringan dan efisien, saya memisahkan fungsi untuk penjual dan pembeli, serta memakai struktur data Python seperti dictionary dan list. Dengan cara ini, sistem jadi mudah dikembangkan lagi ke depannya.
   
2. Dokumentasi Teknis
   Untuk dokumentasi teknisnya, saya menambahkan dokumentasi teknis berupa komentar langsung di dalam kode Python. Komentar ini bertujuan untuk menjelaskan cara kerja setiap bagian program, sehingga memudahkan programmer lain dalam memahami dan mengembangkan aplikasi ini.
   Sebagai contoh, pada bagian awal kode terdapat struktur data stok_sepatu yang disimpan dalam dictionary. Setiap sepatu memiliki atribut seperti nama, jumlah stok, dan harga. Kemudian ada list riwayat_pembelian dan data_pembeli yang digunakan untuk mencatat transaksi dan informasi pembeli.
   Selain itu, fungsi-fungsi utama seperti menu_penjual() dan menu_pembeli() juga diberi komentar. Fungsi menu_penjual() menangani fitur-fitur seperti melihat pemasukan, menambah stok, dan mengecek riwayat pembelian, sementara menu_pembeli() melayani proses pemesanan sepatu oleh pembeli. Komentar juga ditambahkan di setiap bagian logika pengambilan keputusan (if/else) untuk menjelaskan maksud dan alurnya.
   Dokumentasi ini penting agar kode tidak hanya bisa dijalankan, tapi juga mudah dibaca, dipelajari, dan dikembangkan oleh siapa pun yang membacanya.

3. Panduan Penggunaan (User Manual)
   Cara menggunakan aplikasi ini cukup mudah. Pertama, pastikan sudah menginstal Python versi terbaru. Setelah itu, file program cukup dijalankan lewat terminal. Saat dijalankan, pengguna akan langsung diminta memilih peran: sebagai penjual atau pembeli.
   Jika memilih sebagai penjual, pengguna bisa menambah stok sepatu, memperbarui harga, melihat pemasukan penjualan, serta mengecek riwayat pembelian. Sebaliknya, jika sebagai pembeli, pengguna bisa melihat stok sepatu yang tersedia lengkap dengan harganya, lalu memesan sepatu sesuai kebutuhan. Sistem akan langsung menghitung total harga dan mengurangi stok secara otomatis.
   Kalau terjadi kesalahan, misalnya pembeli memesan sepatu lebih banyak dari stok yang tersedia, maka sistem akan menampilkan pesan peringatan. Begitu juga kalau nama sepatu tidak ditemukan, sistem akan memberikan respon yang jelas. Intinya, aplikasi ini dibuat agar mudah digunakan dan tetap informatif walaupun hanya berjalan lewat terminal.

4. Pengujian dan Evaluasi
   Sebelum aplikasi dianggap selesai, saya melakukan berbagai pengujian untuk memastikan semua fitur berfungsi dengan baik. Beberapa skenario pengujian yang saya lakukan antara lain: menambahkan sepatu baru ke stok, melakukan pembelian, menguji jika pembelian melebihi stok, serta memastikan data pembeli dan transaksi tercatat dengan benar.
   Hasilnya, semua fitur berjalan seperti yang diharapkan. Penambahan sepatu berhasil, transaksi tercatat otomatis, stok berkurang sesuai jumlah pembelian, dan sistem memberikan peringatan jika ada kesalahan input.
