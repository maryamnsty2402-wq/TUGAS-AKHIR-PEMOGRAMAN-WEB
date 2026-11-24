# Ruang Lingkup

Sistem Pemesanan Buket Berbasis Web ini dibuat untuk membantu pelanggan dalam melakukan pemesanan buket secara online dan membantu penjual dalam mengelola produk, pesanan, serta pembayaran. Adapun ruang lingkup sistem yang akan dikembangkan adalah sebagai berikut.

## A. Ruang Lingkup Halaman Pelanggan

1. **Beranda**  
   Menampilkan halaman utama website yang berisi informasi mengenai usaha buket, produk unggulan, serta navigasi menuju halaman lainnya.

2. **Katalog Buket**  
   Menampilkan daftar buket yang tersedia beserta informasi produk dan harga agar pelanggan dapat memilih buket sesuai kebutuhan.

3. **Detail Produk**  
   Menampilkan informasi lebih lengkap mengenai buket yang dipilih, seperti nama produk, gambar, harga, deskripsi, serta informasi produk yang diperlukan sebelum melakukan pemesanan.

4. **Keranjang**  
   Menampilkan produk yang telah dipilih pelanggan, jumlah produk, harga, dan total harga pesanan. Pelanggan juga dapat mengatur jumlah produk atau menghapus produk dari keranjang.

5. **Checkout**  
   Menyediakan formulir pemesanan yang harus diisi pelanggan, meliputi nama, nomor WhatsApp, email (opsional), alamat pengiriman, serta tanggal pengiriman. Pelanggan dapat memeriksa detail pesanan sebelum melanjutkan.

6. **Pembayaran**  
   Menampilkan informasi pembayaran yang harus dilakukan pelanggan berdasarkan total pesanan serta menyediakan fasilitas untuk mengunggah bukti pembayaran.

7. **Konfirmasi Pesanan**  
   Menampilkan informasi bahwa pesanan berhasil dibuat, termasuk kode pesanan yang digunakan pelanggan untuk mengidentifikasi dan melacak pesanan.

8. **Lacak Pesanan**  
   Menyediakan fitur untuk melihat perkembangan pesanan dengan memasukkan kode pesanan dan nomor WhatsApp yang digunakan saat pemesanan. Halaman ini menampilkan informasi dan status pesanan pelanggan.

## B. Ruang Lingkup Halaman Admin

1. **Dashboard Admin**  
   Menampilkan ringkasan informasi pengelolaan website, seperti jumlah produk, pesanan, dan informasi transaksi yang diperlukan admin.

2. **Kelola Produk**  
   Menyediakan fasilitas bagi admin untuk menambah, melihat, mengubah, dan menghapus data produk buket yang ditampilkan pada katalog website.

3. **Kelola Pesanan**  
   Menampilkan data pesanan pelanggan serta menyediakan fasilitas untuk memeriksa detail pesanan dan memperbarui status pesanan sesuai proses pengerjaan.

4. **Kelola Pembayaran**  
   Menampilkan informasi pembayaran dan bukti pembayaran yang diunggah pelanggan, serta menyediakan fasilitas bagi admin untuk memeriksa dan memverifikasi pembayaran.

## C. Batasan Pengembangan Sistem

1. Website berfokus pada pemesanan buket dan pengelolaan pesanan secara online.
2. Pelanggan tidak perlu membuat akun atau login untuk melakukan pemesanan.
3. Data pelanggan yang diperlukan dalam pemesanan meliputi nama, nomor WhatsApp, alamat pengiriman, tanggal pengiriman, dan email jika pelanggan ingin mengisinya.
4. Pelacakan pesanan dilakukan menggunakan kode pesanan dan nomor WhatsApp yang digunakan saat pemesanan.
5. Pembayaran dilakukan melalui metode pembayaran yang disediakan pada website dan bukti pembayaran diunggah oleh pelanggan untuk diperiksa admin.
6. Pengelolaan produk, pesanan, dan pembayaran dilakukan melalui halaman admin yang hanya dapat diakses setelah admin login.
7. Website dikembangkan menggunakan PHP, MySQL/MariaDB, HTML, CSS, dan JavaScript.
8. Selama proses pengembangan dan pengujian, website dijalankan menggunakan lingkungan lokal XAMPP.
