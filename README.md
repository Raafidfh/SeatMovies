# SeatMovies

Platform pembelian tiket bioskop sederhana menggunakan laravel, php, reactjs, TailwindCSS, MySQL.

## Tools Requirement

Sebelum menjalankan projek ini, ada beberapa aplikasi/software yang perlu di-install dalam PC atau perangkat anda.

1. [Composer](https://getcomposer.org/download/), package manager PHP.
2. [XAMPP](https://www.apachefriends.org/), local hosting & database management (pastikan unduh XAMPP terbaru dengan versi PHP minimal 8.1).
3. [Git](https://git-scm.com/downloads), version control system lokal.

## Running Project

1. Clone project ke local.

Sebelum menjalankan langkah-langkah dibawah ini, jalankan terlebih dahulu MySQL dan Apache melalui XAMPP control panel yang sudah ter-install.

Sebelum menjalankan langkah-langkah dibawah ini, jalankan terlebih dahulu MySQL dan Apache melalui XAMPP control panel yang sudah ter-install. Jalankan perintah-perintah di bawah ini dengan menggunakan terminal Git Bash.


1. Clone project ke local PC anda dengan menggunakan terminal Git Bash.

```
git clone https://github.com/Raafidfh/SeatMovies.git
```

2. Jalankan Git Bash pada folder repositori project yang sudah di clone, kemudian update composer.

```
composer update /atau/ composer install
```

3. Copy dan buat file .env

```
cp .env.example .env
```

4. Generate application key

```
php artisan key:generate
```

5. Menjalakan migration

6. Menjalakan migration, ketik 'yes' jika setelah menjalankan perintah ini muncul permintaan untuk membuat database baru.

```
php artisan migrate
```

6. Menjalankan seeder untuk generate data aplikasi

```
php artisan db:seed
```

7. Menjalankan aplikasi -> pastikan telah menjalankan MySQL dan Apache pada melalui XAMPP control panel terlebih dahulu.

8. Menjalankan aplikasi, setelah menjalankan perintah ini akan muncul alamat host yang sedang berjalan, copy alamat host tersebut dan buka di browser anda.

```
php artisan serve
```

Note

```
*). Untuk melakukan login:
    username => ilham_
    password => ilham123,
    atau dapat dilihat pada file UserSeeder.php
*). Anda juga dapat melakukan registrasi untuk membuat data akun baru.
```

## Credits

1. [Stisla](https://github.com/stisla/stisla), Bootstrap UI template.
2. [Laravel](https://laravel.com), web aplication framework.


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

-   [Simple, fast routing engine](https://laravel.com/docs/routing).
-   [Powerful dependency injection container](https://laravel.com/docs/container).
-   Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
-   Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
-   Database agnostic [schema migrations](https://laravel.com/docs/migrations).
-   [Robust background job processing](https://laravel.com/docs/queues).
-   [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

