## Deskripsi  
Sistem Penjualan dan Pengelolaan Stok Berbasis Web untuk Toko Bangunan

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/logo.jpg" width="250" height="300">

AHMAD KHAERUN MAKNUN (2211310004)

FAJAR PRATAMA (2211310026)

MARLINDA (2211310086)

TEKNOLOGI INFORMASI
FAKULTAS TEKNIK
KELAS PAGI (A)


## Pendahuluan

1.1 Latar Belakang 

Toko bangunan memiliki berbagai macam barang seperti semen, cat, paku, dan material lainnya yang sangat dibutuhkan untuk konstruksi. Dalam operasional sehari-hari, pencatatan penjualan, pengelolaan stok, dan pembuatan laporan masih sering dilakukan secara manual. Proses ini seringkali menyebabkan kesalahan dalam pencatatan, keterlambatan dalam pembaruan stok, dan sulitnya melakukan pelacakan transaksi.
Dengan kemajuan teknologi, penerapan sistem penjualan berbasis website menjadi solusi yang dapat membantu toko bangunan dalam mengelola data barang, transaksi, dan laporan secara efisien. Sistem ini diharapkan mampu mempermudah pengelolaan usaha, meningkatkan akurasi data, dan mempercepat proses operasional.

1.2 Identifikasi Masalah
1. Kesalahan pencatatan transaksi secara manual, seperti total pembayaran atau stok barang.
2. Kesulitan dalam mengetahui stok barang secara real-time.
3. Proses pembuatan laporan yang memakan waktu karena dilakukan secara manual.
4. Risiko kehilangan data akibat tidak adanya sistem terpusat.
5. Kurangnya efisiensi dalam pengelolaan data barang dan transaksi.

1.3 Rumusan Masalah 
1. Bagaimana merancang sistem penjualan berbasis website untuk mempermudah pencatatan transaksi di toko bangunan?
2. Bagaimana sistem ini dapat membantu memantau stok barang secara real-time?
3. Bagaimana cara mengintegrasikan pembuatan laporan otomatis ke dalam sistem?
4. Bagaimana memastikan keamanan dan akurasi data dalam sistem penjualan berbasis website?
1.4 Skema Hardware
- Laptop anggota kelompok

1.5 Skema Software
- MySQL
- PHP
- Visual Studio Code
- Visual paradigm

1.6 Skema Database
 
Hubungan Antar Tabel
a.	Tabel Utama:
Tabel utama adalah barang, kategori, dan member, karena data ini menjadi pusat untuk mencatat transaksi dan informasi lain.
b.	Relasi Penting:
-Barang ke Kategori: Setiap barang memiliki kategori (id_kategori).
-Penjualan dan Nota ke Barang: Transaksi terkait barang yang dijual.
-Penjualan dan Nota ke Member: Transaksi juga mencatat pelanggan yang melakukan pembelian.
-Login ke Member: Setiap login hanya berlaku untuk member tertentu.

1.7 Skema Actor
- Use Case diagram
 


Penjelasan Diagram
1.	Login: Admin harus login sebelum menggunakan sistem.
2.	Mengelola Data Barang: Admin dapat menambah, mengedit, atau menghapus barang yang ada di sistem.
3.	Mengelola Stok Barang: Admin menambah atau mengurangi stok barang yang tersedia.
4.	Melakukan Penjualan: Admin memilih barang yang dijual, memproses checkout, dan mencetak invoice.
5.	Melihat Laporan Penjualan: Admin dapat melihat laporan penjualan secara berkala.
6.	Melihat Riwayat Transaksi: Admin dapat melihat transaksi yang sudah terjadi untuk keperluan pencatatan.














- Sequence Diagram

 



Deskripsi Sequence Diagram:
Aktor:
Admin 
Entitas website Sistem Penjualan:
-Database
-Modul Login
-Modul Barang
-Modul Penjualan
-Modul Laporan
Skema Interaksi:
Admin Login:
-Admin memasukkan username dan password.
-Sistem memverifikasi kredensial di database.
-Sistem memberikan akses jika berhasil.
Mengelola Barang:
-Admin menambah/mengedit/menghapus data barang.
-Sistem menyimpan perubahan di database.
Melakukan Penjualan:
-Admin memilih barang untuk dijual.
-Admin memasukkan jumlah barang yang dijual.
-Sistem menghitung total harga dan menyimpan data transaksi.
Melihat Laporan:
-Admin meminta laporan penjualan.
-Sistem mengambil data dari database dan menampilkan laporan.
- Activity Diagram
 






## Tampilan
- Login
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/login.png">

- Dashboard 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/dashboard.png">

- Data Barang
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/databarang.png">

- Kategori
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/kategori.png">

- Keranjang 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/keranjang.png">

- Laporan 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/laporan.png">

- Pengaturan Toko 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/pengaturan.png">

- Edit User 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/edituser.png">
