HEAD
HEAD
HEAD
HEAD

# SeatMovies

Platform pembelian tiket bioskop sederhana menggunakan laravel, php, reactjs, TailwindCSS, MySQL.

# Sea Cinema 📽️

# SeaFlashTix 📽️

HEAD
HEAD
33b1051 (Update README.md)

Sea Cinema adalah aplikasi pemesanan tiket bioskop secara online yang memudahkan pengguna untuk mencari, memilih, dan memesan tiket bioskop dengan mudah melalui website. Dengan Sea Cinema, pengguna dapat memesan tiket bioskop yang diinginkan tanpa harus antri di loket bioskop. Aplikasi ini dibuat menggunakan framework [Laravel](https://laravel.com).

SeaFlashTix adalah aplikasi pemesanan tiket bioskop secara online yang memudahkan pengguna untuk mencari, memilih, dan memesan tiket bioskop dengan mudah melalui website. Dengan Sea Cinema, pengguna dapat memesan tiket bioskop yang diinginkan tanpa harus antri di loket bioskop. Aplikasi ini dibuat menggunakan framework [Laravel](https://laravel.com).
7f03488 (Update README.md)

SeaFlashTix adalah aplikasi pemesanan tiket bioskop secara online yang memudahkan pengguna untuk mencari, memilih, dan memesan tiket bioskop dengan mudah melalui website. Dengan SeaFlashTix, pengguna dapat memesan tiket bioskop yang diinginkan tanpa harus antri di loket bioskop. Aplikasi ini dibuat menggunakan framework [Laravel](https://laravel.com).
e3fa06e (Update README.md)

## Tools Requirement

Sebelum menjalankan projek ini, ada beberapa aplikasi/software yang perlu di-install dalam PC atau perangkat anda.

1. [Composer](https://getcomposer.org/download/), package manager PHP.
2. [XAMPP](https://www.apachefriends.org/), local hosting & database management (pastikan unduh XAMPP terbaru dengan versi PHP minimal 8.1).
3. [Git](https://git-scm.com/downloads), version control system lokal.

## Running Project

HEAD

HEAD

1. Clone project ke local.

Sebelum menjalankan langkah-langkah dibawah ini, jalankan terlebih dahulu MySQL dan Apache melalui XAMPP control panel yang sudah ter-install.

Sebelum menjalankan langkah-langkah dibawah ini, jalankan terlebih dahulu MySQL dan Apache melalui XAMPP control panel yang sudah ter-install. Jalankan perintah-perintah di bawah ini dengan menggunakan terminal Git Bash.

e03434e (Update README.md)

1. Clone project ke local PC anda dengan menggunakan terminal Git Bash.
   d9efd63 (Update README.md)

```
git clone https://github.com/ilhamydn17/seaAcd23.git
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

HEAD

5. Menjalakan migration

6. Menjalakan migration, ketik 'yes' jika setelah menjalankan perintah ini muncul permintaan untuk membuat database baru.

> > > > > > > d9efd63 (Update README.md)

```
php artisan migrate
```

6. Menjalankan seeder untuk generate data aplikasi

```
php artisan db:seed
```

HEAD

7. Menjalankan aplikasi -> pastikan telah menjalankan MySQL dan Apache pada melalui XAMPP control panel terlebih dahulu.

8. Menjalankan aplikasi, setelah menjalankan perintah ini akan muncul alamat host yang sedang berjalan, copy alamat host tersebut dan buka di browser anda.
   d9efd63 (Update README.md)

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

HEAD
f60e249 (Update README.md)

e905036 (Update README.md)

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

HEAD
HEAD

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

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

-   **[Vehikl](https://vehikl.com/)**
-   **[Tighten Co.](https://tighten.co)**
-   **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
-   **[64 Robots](https://64robots.com)**
-   **[Cubet Techno Labs](https://cubettech.com)**
-   **[Cyber-Duck](https://cyber-duck.co.uk)**
-   **[Many](https://www.many.co.uk)**
-   **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
-   **[DevSquad](https://devsquad.com)**
-   **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
-   **[OP.GG](https://op.gg)**
-   **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
-   **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

# If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

e905036 (Update README.md)

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

# 6f7987f (initialize Repo)

<p align="center">The Laravel framework is open-sourced software licensed under the <a href="https://opensource.org/licenses/MIT">MIT license</a>.</p>
7131587 (Update README.md)

Hello, World!
88c89b4 (First commit)
