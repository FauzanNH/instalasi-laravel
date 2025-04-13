 # PERSIAPAN INSTALASI LARAVEL 11 MENGGUNAKAN COMPOSER

1. Sebelum Instalasi Framework Laravel, pastikan dulu sudah terinstall Web server seperti laragon atau XAMPP 
2. Setelah itu download dan install COMPOSER di [composer-setup.exe](https://getcomposer.org/Composer-Setup.exe) dan jalankan file instalasi. agar bisa menajalan kan composer di terminal atau command Prompt
3. buka aplikasi web server seperti laragon atau XAMPP, lalu buka menu terminal atau shell
![shell](images/shell.png)
![terminal](images/terminal.png)

4. ketik di bawah ini untuk memastikan composer terinstall
~~~~~~~~
composer --version
~~~~~~~~ 

![cek composer](images/cek-composer.png)



## INSTALASI LARAVEL

5. ketik di bawah ini untuk XAMPP 
~~~~~~~~
cd htdocs
~~~~~~~~

 ketik untuk laragon,
~~~~~~~~
cd www
~~~~~~~~ 

namun saya di sini pakai XAMPP, Jadi sesuaikan kalian pakai web server dari laragon atau XAMPP.


6. ketik Promt ini untuk download laravel
~~~~~~~~
composer create-project --prefer-dist laravel/laravel nama_project_kamu
~~~~~~~~ 

atau lebih spesifik versi 11 atau lainnya :
~~~~~~~~
composer create-project laravel/laravel:^11.0 nama_project_kamu
~~~~~~~~ 

![laravel step1](images/lrv1.png)

7. tunggu instalasi laravel hingga success dan jika sudah berhasil di download laravel nya gambar nya sebagai berikut:
![laravel step2](images/lrv2.png)

8. masuk ke direktori nama folder project yang tadi di buat dengan ketik
~~~~~~~~
cd nama_project_kamu
~~~~~~~~ 

9. Ketik promnt ini untuk membuka text editor untuk memulai project kamu
~~~~~~~~
code .
~~~~~~~~ 
![laravel step3](images/lrv3.png)


10.Untuk menjalankan projek laravel pastikan telah menyalakan Apache atau NginX dan Mysql
11.Ketik promt ini untuk menjalan kan projek laravel 

~~~~~~~~
php artisan serve
~~~~~~~~ 

![laravel step4](images/lrv4.png)


12. Dan laravel sudah selesai di jalankan dan siap di build sesuai kebutuhan project...
![laravel step5](images/lrv5.png)




 
