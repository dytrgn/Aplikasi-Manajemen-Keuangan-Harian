Aplikasi Manajemen Keuangan Harian ini adalah aplikasi web sederhana untuk melacak pemasukan dan pengeluaran harian, serta membantu lo mengontrol saldo dan dana makan. Aplikasi ini menggunakan HTML, Bootstrap 5 untuk styling, dan Vanilla JavaScript untuk logika, dengan penyimpanan data di LocalStorage peramban.

Fitur Utama

Pelacakan Transaksi Dasar Input Uang Masuk: Lo bisa catat nominal pemasukan dan akan langsung menambah Total Saldo lo. Input Uang Keluar: Lo bisa catat pengeluaran lengkap dengan Nominal, Kategori (Makan, Jajan, Lain-lain), dan Keterangan Tambahan. Cek Saldo Otomatis: Sistem akan menolak transaksi pengeluaran kalo Total Saldo lo gak cukup (balance check).

Ringkasan Keuangan Instan Total Saldo: Menampilkan total uang yang lo punya saat ini. Rata-rata Keluar Harian: Menghitung rata-rata pengeluaran lo per hari sejak transaksi pertama.

Quick Review Pengeluaran Harian & Mingguan Menampilkan total pengeluaran secara cepat untuk: Kemarin Hari Ini Minggu Ini (Dihitung dari Senin sampai hari ini).

Pengelolaan Dana Uang Makan Lo bisa menambahkan Total Dana khusus untuk uang makan. Sistem akan melacak Dana Terpakai dan Sisa Dana makan secara terpisah setiap lo mencatat pengeluaran dengan kategori "Makan". Memberikan notifikasi warning jika pengeluaran makan melebihi sisa dana yang tersedia.

Fitur Cek Balance (Uang Nyata vs. Sistem) Memungkinkan lo memasukkan jumlah Uang Nyata yang lo pegang. Menghitung Selisih antara Saldo Sistem dan Uang Nyata. Menampilkan hasil dengan status: BALANCE (Cocok), DEFISIT (Uang Nyata kurang), atau SURPLUS (Uang Nyata lebih).

Riwayat Transaksi & Rekap Bulanan Riwayat Uang Masuk: Menampilkan daftar nominal dan waktu semua transaksi masuk. Riwayat Uang Keluar: Menampilkan daftar nominal, kategori, keterangan, dan waktu semua transaksi keluar. Rekap Rata-rata Keluar Harian per Bulan: Menampilkan ringkasan pengeluaran bulanan, termasuk Total Keluar dan Rata-rata Harian yang dihitung berdasarkan hari unik dengan transaksi di bulan tersebut.

Fitur Utility Penyimpanan Data Lokal: Data lo disimpan di LocalStorage (browser), jadi data lo aman dan otomatis dimuat saat aplikasi dibuka lagi. Reset Data: Tombol untuk menghapus semua data transaksi, saldo, dan riwayat. Notifikasi Toast: Memberikan feedback cepat dan jelas berupa notifikasi (pop-up) setelah setiap aksi (masuk, keluar, balance check).


