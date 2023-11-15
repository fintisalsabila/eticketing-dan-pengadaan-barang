**Deskripsi Aplikasi:**
Aplikasi ini dikembangkan menggunakan kerangka kerja CodeIgniter, dirancang untuk mengelola sistem e-ticketing dan pengadaan barang. Aplikasi mencakup modul e-ticketing untuk acara dan kegiatan, serta modul pengadaan barang untuk kebutuhan organisasi atau perusahaan.

**Persyaratan Sistem:**
1. Server web yang mendukung PHP (direkomendasikan Apache).
2. MySQL Database.
3. PHP 7.x
4. CodeIgniter 3.x.

**Instalasi:**
1. Clone repositori ini ke dalam direktori web server Anda:
   ```bash
   git clone https://github.com/fintisalsabila/repo-eticketing-pengadaan.git
   ```

2. Buat database MySQL baru untuk aplikasi ini.

3. Salin file `application/config/database.php.example` ke `application/config/database.php` dan sesuaikan konfigurasi database dengan pengaturan MySQL Anda.

   ```bash
   cp application/config/database.php.example application/config/database.php
   ```

4. Salin file `application/config/config.php.example` ke `application/config/config.php` dan atur konfigurasi dasar seperti base_url.

   ```bash
   cp application/config/config.php.example application/config/config.php
   ```

5. Jalankan skrip SQL di file `database.sql` untuk membuat skema basis data:

   ```bash
   mysql -u username -p database_name < database.sql
   ```

   Gantilah `username` dan `database_name` sesuai dengan pengaturan MySQL Anda.

**Konfigurasi Tambahan:**
1. Jika perlu, sesuaikan konfigurasi lainnya di file `application/config/config.php` dan `application/config/autoload.php`.

2. Anda dapat mengganti logo dan tata letak aplikasi dengan menyunting file di direktori `assets`, serta mengonfigurasi tema atau tata letak dengan memodifikasi file tata letak dan gaya CSS.

**Menjalankan Aplikasi:**
Buka aplikasi melalui web browser:

   ```bash
   http://localhost/namauser/repo-eticketing-pengadaan
   ```

Pastikan Anda sudah menyesuaikan URL berdasarkan struktur folder dan nama repositori di server Anda.

**Penggunaan Aplikasi:**
1. Akses aplikasi melalui URL yang telah diatur.

2. Daftar sebagai pengguna baru atau masuk jika sudah memiliki akun.

3. Pilih modul E-Ticketing atau Pengadaan Barang.

4. Gunakan fitur-fitur yang disediakan sesuai dengan kebutuhan.

**Dukungan dan Kontribusi:**
Jika Anda menemui masalah atau memiliki pertanyaan, buat *issue* di repositori ini. Kontribusi dalam bentuk *pull request* selalu dipersilakan.

**Lisensi:**
Aplikasi ini dilisensikan di bawah [MIT License](LICENSE). Anda bebas menggunakan, mengubah, dan mendistribusikan aplikasi ini sesuai dengan ketentuan lisensi.
