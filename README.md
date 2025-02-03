## Deskripsi  
Sistem Penjualan dan Pengelolaan Stok Berbasis Web untuk Toko Bangunan

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/logo.jpg" width="250" height="300">

FAJAR PRATAMA (2211310026)

TEKNOLOGI INFORMASI
FAKULTAS TEKNIK
KELAS PAGI (A)

## NO 1
Jelaskan permasalahan yang ingin diselesaikan dalam proyek perangkat lunak yang Anda kembangkan. Berikan analisis mendalam mengenai penyebab utama permasalahan tersebur dan dampaknya pada pengguna atau sistem Kemudian, usulkan solusi yang dapat diterapkan dengan teknologi perangkat lunak, serta bagaimana solusi tersebut dapat memenuhi kebutunan pengguna seranjuπηγα masukkan seluruh permasalahan ke dalam file readme.md Github dengan nama repository yaitu LUAS-PokAhmadRoihan-PPL, dan berikan tautannya di jawaban

### **1. Permasalahan yang Ingin Diselesaikan**  
Toko bangunan umumnya masih mengandalkan pencatatan manual dalam mengelola transaksi dan stok barang. Hal ini menyebabkan beberapa permasalahan utama:  

1. **Kesalahan pencatatan transaksi** – Kesalahan dalam menghitung total pembayaran atau pencatatan stok sering terjadi akibat metode manual.  
2. **Ketidaktepatan dalam pemantauan stok** – Tanpa sistem yang terkomputerisasi, stok barang sulit diperbarui secara real-time, yang dapat menyebabkan kekurangan atau kelebihan persediaan.  
3. **Proses pembuatan laporan yang lambat** – Laporan penjualan dan stok harus dibuat secara manual, yang memakan waktu dan berisiko terjadi kesalahan.  
4. **Risiko kehilangan data** – Tidak adanya sistem penyimpanan digital membuat data transaksi mudah hilang atau rusak.  
5. **Kurangnya efisiensi dalam pengelolaan toko** – Pengelolaan barang dan transaksi secara manual tidak efektif, terutama jika volume penjualan tinggi.  

### **2. Analisis Penyebab Utama**  
- **Metode manual yang masih digunakan** menyebabkan kemungkinan human error tinggi.  
- **Kurangnya sistem terpusat** membuat data tidak terorganisir dengan baik.  
- **Proses pembaruan stok yang tidak real-time** menyebabkan keterlambatan dalam pengambilan keputusan.  
- **Tidak adanya pencatatan digital** meningkatkan risiko kehilangan data akibat faktor eksternal seperti kehilangan buku catatan atau kesalahan input.  

### **3. Dampak pada Pengguna atau Sistem**  
- Pemilik dan admin toko kesulitan dalam mengelola stok dan transaksi.  
- Pelanggan dapat mengalami keterlambatan atau ketidakpastian dalam ketersediaan barang.  
- Proses bisnis berjalan lambat karena administrasi yang kurang efisien.  

### **4. Solusi dengan Teknologi Perangkat Lunak**  
Solusi yang diusulkan adalah **Sistem Penjualan dan Pengelolaan Stok Berbasis Web**, yang memiliki fitur:  
1. **Manajemen transaksi otomatis** – Sistem akan menghitung total pembayaran secara otomatis, mengurangi kesalahan perhitungan.  
2. **Pemantauan stok secara real-time** – Setiap transaksi akan memperbarui stok barang langsung dalam database.  
3. **Pembuatan laporan otomatis** – Admin dapat melihat laporan transaksi dan stok tanpa perlu menghitung secara manual.  
4. **Penyimpanan data terpusat** – Semua data tersimpan dalam database MySQL yang lebih aman dan mudah diakses.  
5. **Efisiensi dalam pengelolaan toko** – Proses pencatatan, pemantauan stok, dan laporan menjadi lebih cepat dan akurat.  

Dengan solusi ini, sistem dapat memenuhi kebutuhan pengguna, meningkatkan efisiensi operasional, serta mengurangi kesalahan pencatatan dan risiko kehilangan data.

## Pendahuluan

## 1.1 Latar Belakang 

Toko bangunan memiliki berbagai macam barang seperti semen, cat, paku, dan material lainnya yang sangat dibutuhkan untuk konstruksi. Dalam operasional sehari-hari, pencatatan penjualan, pengelolaan stok, dan pembuatan laporan masih sering dilakukan secara manual. Proses ini seringkali menyebabkan kesalahan dalam pencatatan, keterlambatan dalam pembaruan stok, dan sulitnya melakukan pelacakan transaksi.

Dengan kemajuan teknologi, penerapan sistem penjualan berbasis website menjadi solusi yang dapat membantu toko bangunan dalam mengelola data barang, transaksi, dan laporan secara efisien. Sistem ini diharapkan mampu mempermudah pengelolaan usaha, meningkatkan akurasi data, dan mempercepat proses operasional.

## 1.2 Identifikasi Masalah

1. Kesalahan pencatatan transaksi secara manual, seperti total pembayaran atau stok barang.
   
2. Kesulitan dalam mengetahui stok barang secara real-time.
   
3. Proses pembuatan laporan yang memakan waktu karena dilakukan secara manual.
   
4. Risiko kehilangan data akibat tidak adanya sistem terpusat.
   
5. Kurangnya efisiensi dalam pengelolaan data barang dan transaksi.

## 1.3 Rumusan Masalah 

1. Bagaimana merancang sistem penjualan berbasis website untuk mempermudah pencatatan transaksi di toko bangunan?
   
2. Bagaimana sistem ini dapat membantu memantau stok barang secara real-time?
 
3. Bagaimana cara mengintegrasikan pembuatan laporan otomatis ke dalam sistem?
   
4. Bagaimana memastikan keamanan dan akurasi data dalam sistem penjualan berbasis website?

## 1.4 Skema Hardware
- Laptop anggota kelompok
  
## 1.5 Skema Software
- MySQL
  
- PHP
  
- Visual Studio Code
  
- Visual paradigm

## 1.6 Skema Database

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/skema.jpg" width="650" height="500">

 
## Hubungan Antar Tabel

## a.	Tabel Utama:

Tabel utama adalah barang, kategori, dan member, karena data ini menjadi pusat untuk mencatat transaksi dan informasi lain.

## b.	Relasi Penting:

1. Barang ke Kategori: Setiap barang memiliki kategori (id_kategori).

2. Penjualan dan Nota ke Barang: Transaksi terkait barang yang dijual.

3. Penjualan dan Nota ke Member: Transaksi juga mencatat pelanggan yang melakukan pembelian.

4. Login ke Member: Setiap login hanya berlaku untuk member tertentu.

## 1.7 Skema Actor

## - Use Case diagram
 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/actor.jpg" width="600" height="500">


## Penjelasan Diagram

1.	Login: Admin harus login sebelum menggunakan sistem.
   
2.	Mengelola Data Barang: Admin dapat menambah, mengedit, atau menghapus barang yang ada di sistem.
   
3.	Mengelola Stok Barang: Admin menambah atau mengurangi stok barang yang tersedia.
   
4.	Melakukan Penjualan: Admin memilih barang yang dijual, memproses checkout, dan mencetak invoice.
   
5.	Melihat Laporan Penjualan: Admin dapat melihat laporan penjualan secara berkala.
    
6.	Melihat Riwayat Transaksi: Admin dapat melihat transaksi yang sudah terjadi untuk keperluan pencatatan.

## - Sequence Diagram

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/sequence.jpg" width="800" height="800">

## Deskripsi Sequence Diagram:

Aktor:

- Admin 

Entitas website Sistem Penjualan:

- Database

- Modul Login

- Modul Barang

- Modul Penjualan

- Modul Laporan

## Skema Interaksi:

Admin Login:

1. Admin memasukkan username dan password.

2. Sistem memverifikasi kredensial di database.

3. Sistem memberikan akses jika berhasil.

Mengelola Barang:

1. Admin menambah/mengedit/menghapus data barang.

2. Sistem menyimpan perubahan di database.

Melakukan Penjualan:

1. Admin memilih barang untuk dijual.

2. Admin memasukkan jumlah barang yang dijual.

3. Sistem menghitung total harga dan menyimpan data transaksi.

Melihat Laporan:

1. Admin meminta laporan penjualan.

2. Sistem mengambil data dari database dan menampilkan laporan.

## - Activity Diagram
 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/activity.jpg" width="500" height="450">

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
