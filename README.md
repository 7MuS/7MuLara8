<h1 align="center"> 7Mū Website - Laravel 8 </h1>

<div align="center">

<img width="200" height="200" src="./resources/images/7mu.jpg" alt="7Mu's Logo"/>

</div>

## Tabel Konten

- [Tentang](#tentang)
- [Dokumentasi](#dokumentasi)
- [Author](#author)

## Tentang 7Mū dan Laravel 8 <a name="tentang"> </a>
7Mū merupakan singkatan dari 7Sins and Mabar United. dan <a href="https://github.com/laravel/laravel">Laravel 8</a> merupakan PHP-Framework yang dikhususkan dalam implementasi <a href="https://en.wikipedia.org/wiki/MVC">MVC-based Website</a>.

## Dokumentasi <a name="dokumentasi"> </a>
Selain menggunakan <a href="https://github.com/laravel/laravel">Laravel 8</a>, project ini akan juga menggunakan <a href="https://tailwindcss.com">TailwindCss</a> sebagai CSS-Frameworknya.

### Inisialisasi Proyek

Pertama fork dulu repository ini.

Kemudian clone repository dengan menggunakan
```bash
git clone https://github.com/kuzunagi/7MuLara8.git 
```

Setelah itu pindah ke direktori 
```bash
cd 7mulara8
```
### Unduh Dependencies

Lakukan `composer install` untuk memulai proses 
pengunduhan

```bash
composer install
```

Setelah selesai lakukan `npm install` 
```bash
npm install
```

### Instalisasi Proyek

Untuk memulai kamu harus menyalin file `.env.example` ke `.env` dengan cara menyalin dan mengubah nama file atau kalian bisa menggunakan perintah
```bash
cp .env.example .env
```
Setelah berhasil lakukan `php artisan key:generate`
```bash
php artisan key:generate
```
Buat database baru dengan nama `7mulara8`, kemudian buka file `.env` dan ubah `DB_HOST`, `DB_PORT`, `DB_DATABASE`, `DB_USERNAME` dan `DB_PASSWORD` sesuai dengan pengaturan yang kalian miliki.

Untuk info lanjutan silahkan kunjungi <a href="https://laravel.com/docs/8.x">Penginstallan Laravel 8</a> dan <a href="https://tailwindcss.com/docs/guides/laravel">Tailwindcss</a>

## Author <a name="author"> </a>

- [@EmptyWork](https://github.com/emptywork) 
- [@kuzunagi](https://github.com/kuzunagi)
