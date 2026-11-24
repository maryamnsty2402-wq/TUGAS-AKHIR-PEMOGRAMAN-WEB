# Analisis Kebutuhan Nonfungsional

Kebutuhan nonfungsional merupakan kebutuhan yang berkaitan dengan kualitas, keamanan, kemudahan penggunaan, dan kinerja sistem. Kebutuhan ini digunakan sebagai acuan agar Sistem Pemesanan Buket Berbasis Web dapat digunakan dengan nyaman dan sesuai dengan tujuan yang telah direncanakan.

## 1. Kemudahan Penggunaan (Usability)

1. Website memiliki tampilan yang sederhana, rapi, dan mudah dipahami oleh pelanggan maupun admin.
2. Navigasi website disusun dengan jelas agar pengguna dapat menemukan halaman yang dibutuhkan.
3. Proses pemesanan dibuat sesederhana mungkin agar pelanggan tidak kesulitan saat melakukan transaksi.
4. Informasi produk, harga, pesanan, dan pembayaran ditampilkan dengan jelas.

## 2. Keamanan (Security)

1. Halaman admin hanya dapat diakses oleh admin yang memiliki data login yang sesuai.
2. Password admin disimpan menggunakan metode hashing, bukan dalam bentuk teks biasa.
3. Sistem melakukan validasi terhadap data yang dimasukkan pengguna.
4. Sistem membatasi akses pelanggan terhadap halaman pengelolaan admin.
5. Sistem melakukan pemeriksaan terhadap file bukti pembayaran yang diunggah agar file yang tidak sesuai dapat ditolak.

## 3. Kinerja (Performance)

1. Website dapat menampilkan halaman dan informasi produk dengan waktu pemuatan yang wajar pada lingkungan pengujian.
2. Sistem dapat memproses data pesanan, keranjang, dan pembayaran sesuai fungsi yang tersedia.
3. Tampilan dan proses website tidak menggunakan elemen yang berlebihan sehingga tetap nyaman digunakan.

## 4. Kompatibilitas (Compatibility)

1. Website dapat diakses melalui browser modern seperti Google Chrome.
2. Website dirancang agar dapat digunakan melalui perangkat laptop, komputer, maupun ponsel.
3. Tampilan halaman menyesuaikan ukuran layar perangkat yang digunakan.

## 5. Keandalan Data (Data Reliability)

1. Data pesanan disimpan dalam database agar dapat diakses kembali ketika diperlukan.
2. Sistem menampilkan informasi pesanan berdasarkan data yang tersimpan.
3. Sistem menjaga keterkaitan data pesanan, pelanggan, produk, dan pembayaran agar informasi tidak tercampur.
4. Perubahan status pesanan dan pembayaran dilakukan berdasarkan proses yang dijalankan admin.

## 6. Pemeliharaan (Maintainability)

1. Struktur file dan kode website disusun secara teratur agar lebih mudah dipahami dan dikembangkan.
2. Kode program dipisahkan sesuai fungsi, seperti konfigurasi, halaman pelanggan, halaman admin, CSS, dan JavaScript.
3. Dokumentasi proyek disimpan di GitHub agar proses pengembangan dapat ditelusuri dan dilanjutkan oleh anggota kelompok.
