## Deskripsi  
Sistem Penjualan dan Pengelolaan Stok Berbasis Web untuk Toko Bangunan

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/logo.jpg" width="250" height="300">

FAJAR PRATAMA (2211310026)

TEKNOLOGI INFORMASI
FAKULTAS TEKNIK
KELAS PAGI (A)

## NO 1. Jelaskan permasalahan yang ingin diselesaikan dalam proyek perangkat lunak yang Anda kembangkan. Berikan analisis mendalam mengenai penyebab utama permasalahan tersebur dan dampaknya pada pengguna atau sistem Kemudian, usulkan solusi yang dapat diterapkan dengan teknologi perangkat lunak, serta bagaimana solusi tersebut dapat memenuhi kebutunan pengguna

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

## NO 2. Deskripsikan metode pengujian (black/white testing) yang Anda gunakan untuk memastikan perangkat lunak berfungsi dengan balk, Jelaskan jenis pengujian yang diterapkan (misalnya, unit testing integration testing systern testing atau user acceptance testing), hasil pengujian yang diperoleh, dan kesimpulan dari pengujian tersebut

**Metode Pengujian Perangkat Lunak**  

Dalam proyek **Sistem Penjualan dan Pengelolaan Stok Berbasis Web**, metode pengujian yang digunakan adalah **Black Box Testing**, yang berfokus pada pengujian fungsionalitas tanpa melihat kode sumber.  

### **Jenis Pengujian yang Diterapkan**  
1. **Unit Testing** – Menguji setiap modul secara terpisah, seperti modul login, transaksi, dan pengelolaan stok, untuk memastikan bahwa setiap bagian berfungsi dengan baik.  
2. **Integration Testing** – Menguji bagaimana modul-modul tersebut bekerja bersama, seperti proses login yang terhubung dengan manajemen pengguna atau transaksi yang mempengaruhi stok barang.  
3. **System Testing** – Menguji sistem secara keseluruhan untuk memastikan bahwa semua fitur berjalan sesuai dengan spesifikasi yang telah ditentukan.  
4. **User Acceptance Testing (UAT)** – Menguji sistem dengan pengguna akhir (admin toko) untuk memastikan bahwa sistem mudah digunakan dan memenuhi kebutuhan bisnis mereka.  

### **Hasil Pengujian**  
- **Unit Testing**: Semua modul berfungsi dengan baik tanpa error yang mengganggu.  
- **Integration Testing**: Tidak ditemukan masalah dalam interaksi antara modul, seperti transaksi yang langsung memperbarui stok.  
- **System Testing**: Sistem dapat berjalan dengan lancar di berbagai perangkat dan browser.  
- **User Acceptance Testing**: Pengguna merasa sistem lebih mudah digunakan dibandingkan metode manual sebelumnya.  

### **Kesimpulan**  
Berdasarkan hasil pengujian, sistem telah memenuhi standar fungsionalitas dan keandalan. Semua fitur berjalan sesuai dengan yang diharapkan, dan pengguna merasa terbantu dengan sistem ini. Namun, perbaikan kecil dapat dilakukan untuk meningkatkan pengalaman pengguna, seperti optimalisasi tampilan dan kecepatan akses.

## NO 3. Jelaskan bahasa pemrograman yang dipilih untuk pengembangan proyek anda, termasuk alasan pemilihannya berdasarkan karakteristik proyek dan keunggulan bahasa tersebut. Sebutkan juga platfunt pengembangan (misalnya, aplikasi berbasis web, mobile, atau desktop) serta perangkat lunak pendukung yang digunakan selama pengembangan

**Bahasa Pemrograman dan Platform Pengembangan**  

### **Bahasa Pemrograman yang Digunakan**  
Proyek **Sistem Penjualan dan Pengelolaan Stok Berbasis Web** dikembangkan menggunakan **PHP** sebagai bahasa pemrograman utama untuk backend dan **MySQL** sebagai database.  

### **Alasan Pemilihan PHP**  
1. **Mudah Digunakan** – PHP memiliki sintaks yang sederhana dan mudah dipelajari, sehingga cocok untuk pengembangan aplikasi web.  
2. **Kompatibilitas Tinggi** – PHP dapat berjalan di berbagai sistem operasi dan dapat dengan mudah diintegrasikan dengan database MySQL.  
3. **Performa yang Baik** – PHP memiliki eksekusi yang cukup cepat untuk aplikasi skala kecil hingga menengah seperti sistem penjualan ini.  
4. **Dukungan Komunitas yang Luas** – PHP memiliki komunitas besar yang menyediakan banyak referensi, dokumentasi, dan library tambahan.  

### **Platform Pengembangan**  
Proyek ini dikembangkan sebagai **aplikasi berbasis web**, sehingga dapat diakses melalui browser tanpa perlu instalasi tambahan di perangkat pengguna.  

### **Perangkat Lunak Pendukung**  
- **Visual Studio Code** – Digunakan sebagai text editor utama untuk menulis kode PHP dan HTML.  
- **XAMPP** – Digunakan sebagai server lokal yang menjalankan Apache, PHP, dan MySQL untuk kebutuhan pengujian dan pengembangan.  
- **Bootstrap** – Digunakan untuk meningkatkan tampilan antarmuka agar lebih responsif dan mudah digunakan.  
- **MySQL** – Digunakan sebagai sistem manajemen basis data untuk menyimpan data barang, transaksi, dan pengguna.  

Dengan kombinasi teknologi ini, sistem dapat berjalan dengan efisien, mudah dikembangkan, dan memenuhi kebutuhan pengguna dalam pengelolaan toko bangunan.

##  NO 4. Buatlah rancangan teknis perangkat lunak yang meliputi

A. Skema Hardware: Jelaskan perangkat keras yang dibutuhkan untuk menjalankan sistem

B. Skema Software: Berikan spesifikasi sistem operasi, framework, library, dan bahasa pemrograman yang digunakan

C. Skema Database: Gambarkan class diagram atou ERD untuk mendeskripsikan struktur data yang digunakan.

D. Skema Actor Buatlah use cose diagram, sequence diagram, dan activity diagram untuk menjelaskan olur sistem yang melibatkan pengguna dan interaksi antar komponen sistem

Sertakan diagram yong relevan dalam laporan Anda

**Rancangan Teknis Perangkat Lunak**  

### **A. Skema Hardware**  
Untuk menjalankan **Sistem Penjualan dan Pengelolaan Stok Berbasis Web**, berikut adalah perangkat keras yang dibutuhkan:  

1. **Server** (Opsional jika menggunakan hosting sendiri)  
   - **Processor**: Intel Core i5 atau lebih tinggi  
   - **RAM**: Minimal 8GB untuk performa optimal  
   - **Storage**: SSD 256GB atau lebih (untuk kecepatan akses data)  
   - **Koneksi Internet**: Stabil dengan bandwidth yang cukup  

2. **Client (Admin atau Pengguna)**  
   - **Device**: Laptop atau PC dengan spesifikasi minimal  
     - **Processor**: Intel Core i3 atau lebih tinggi  
     - **RAM**: 4GB atau lebih  
     - **Storage**: 128GB SSD atau lebih  
   - **Browser**: Google Chrome, Mozilla Firefox, atau Microsoft Edge  
   - **Printer (Opsional)**: Jika diperlukan untuk mencetak invoice atau laporan  

### **B. Skema Software**  
Berikut adalah spesifikasi perangkat lunak yang digunakan:  

1. **Sistem Operasi**  
   - Windows 10/11 atau Linux (Ubuntu/Debian)  
   - Jika menggunakan server, direkomendasikan **Linux Ubuntu 20.04** untuk stabilitas  

2. **Framework dan Library**  
   - **Backend**: PHP (tanpa framework, native PHP)  
   - **Frontend**: Bootstrap untuk tampilan responsif  
   - **Database**: MySQL untuk penyimpanan data  
   - **Library Pendukung**:  
     - **PDO** untuk koneksi database yang lebih aman  
     - **TCPDF** (opsional) untuk pembuatan laporan dalam format PDF  

3. **Bahasa Pemrograman**  
   - **PHP** untuk backend  
   - **HTML dan CSS** untuk tampilan halaman  
   - **SQL** untuk pengelolaan database

### **C. Skema Database**

<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/skema.jpg" width="650" height="500">

 
## Hubungan Antar Tabel

## a.	Tabel Utama:

Tabel utama adalah barang, kategori, dan member, karena data ini menjadi pusat untuk mencatat transaksi dan informasi lain.

## b.	Relasi Penting:

1. Barang ke Kategori: Setiap barang memiliki kategori (id_kategori).

2. Penjualan dan Nota ke Barang: Transaksi terkait barang yang dijual.

3. Penjualan dan Nota ke Member: Transaksi juga mencatat pelanggan yang melakukan pembelian.

4. Login ke Member: Setiap login hanya berlaku untuk member tertentu.

### **D. Skema Actor**

## -Use Case diagram
 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/actor.jpg" width="600" height="500">


## Penjelasan Diagram

1.	Login: Admin harus login sebelum menggunakan sistem.
   
2.	Mengelola Data Barang: Admin dapat menambah, mengedit, atau menghapus barang yang ada di sistem.
   
3.	Mengelola Stok Barang: Admin menambah atau mengurangi stok barang yang tersedia.
   
4.	Melakukan Penjualan: Admin memilih barang yang dijual, memproses checkout, dan mencetak invoice.
   
5.	Melihat Laporan Penjualan: Admin dapat melihat laporan penjualan secara berkala.
    
6.	Melihat Riwayat Transaksi: Admin dapat melihat transaksi yang sudah terjadi untuk keperluan pencatatan.

## -Sequence Diagram

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

## -Activity Diagram
 
<img src="https://raw.githubusercontent.com/fajar1231/pos/master/assets/img/user/activity.jpg" width="500" height="450">

Dengan rancangan ini, sistem dapat berjalan secara optimal dan memenuhi kebutuhan pengelolaan penjualan serta stok di toko bangunan.

## NO 5. Gambarkan proses implementasi sistem yang Anda kembangkan, mulai dari persiapan lingkungan kerja hingga penerapan komponen-komponen perangkat lunak. Jelaskan langkah-langkah Anda dalam mengintegrasikan hardware, software, database, dan antarmuka pengguna sehingga sistem dapat berjalan sesuai desain

### **Proses Implementasi Sistem**  

Implementasi **Sistem Penjualan dan Pengelolaan Stok Berbasis Web** dilakukan melalui beberapa tahapan, mulai dari persiapan lingkungan kerja hingga integrasi komponen-komponen perangkat lunak. Berikut langkah-langkahnya:  

---

### **1. Persiapan Lingkungan Kerja**  
Sebelum memulai pengembangan, dilakukan persiapan perangkat keras dan lunak yang dibutuhkan:  
- **Perangkat Keras**: Laptop atau PC dengan spesifikasi minimal (Intel i3, RAM 4GB, SSD 128GB).  
- **Perangkat Lunak**:  
  - Instalasi **XAMPP** (Apache, MySQL, PHP) untuk server lokal.  
  - Instalasi **Visual Studio Code** sebagai code editor.  
  - Instalasi **MySQL Workbench** (opsional) untuk manajemen database.  
  - Instalasi **Git** untuk version control (opsional).  

---

### **2. Pengembangan dan Integrasi Komponen Sistem**  

#### **a. Pembuatan Database MySQL**  
1. **Membuat database** di **phpMyAdmin** dengan nama `toko_bangunan_pos`.  
2. **Membuat tabel utama**, seperti:  
   - `barang` (menyimpan data produk).  
   - `kategori` (kategori produk).  
   - `penjualan` (mencatat transaksi).  
   - `user` (data admin toko).  
3. **Menjalankan query SQL** untuk mengisi data awal.  

#### **b. Pengembangan Backend dengan PHP**  
1. **Membuat koneksi database** menggunakan **PDO** untuk keamanan.  
2. **Membuat modul utama**:  
   - Modul **Login**: Otentikasi admin sebelum mengakses sistem.  
   - Modul **Manajemen Barang**: CRUD (Create, Read, Update, Delete) untuk stok produk.  
   - Modul **Penjualan**: Proses transaksi dan pengurangan stok secara otomatis.  
   - Modul **Laporan**: Menampilkan dan mencetak laporan transaksi.  

#### **c. Pengembangan Frontend dengan Bootstrap**  
1. **Membuat template halaman** dengan **Bootstrap** untuk tampilan responsif.  
2. **Membuat navigasi utama**: Dashboard, Data Barang, Transaksi, Laporan.  
3. **Menghubungkan frontend dengan backend** menggunakan form dan request **POST/GET** di PHP.  

---

### **3. Pengujian dan Debugging**  
1. **Unit Testing**: Menguji setiap fitur secara terpisah (login, transaksi, laporan).  
2. **Integration Testing**: Memastikan modul bekerja dengan baik saat terhubung.  
3. **User Acceptance Testing (UAT)**: Admin mencoba sistem dan memberikan masukan.  

---

### **4. Implementasi dan Penerapan Sistem**  
1. **Deploy ke Server** (jika digunakan hosting online) atau tetap menggunakan **XAMPP** untuk lokal.  
2. **Migrasi Data**: Memasukkan data produk awal ke dalam database.  
3. **Training Admin**: Memberikan panduan penggunaan sistem kepada pengguna.  
4. **Monitoring dan Maintenance**: Mengecek sistem secara berkala untuk memastikan tidak ada bug.  

---

Dengan mengikuti langkah-langkah ini, sistem berhasil berjalan sesuai dengan desain dan dapat digunakan untuk membantu pengelolaan penjualan serta stok di toko bangunan.

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
