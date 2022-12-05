<p align="center">
  <a href="https://getstisla.com">
    <img src="https://raw.githubusercontent.com/muhammedia/binasehat/main/image/logo.png" alt="BinaSehat logo" width="75" height="75">
  </a>
</p>

<h1 align="center">BinaSehat</h1>

<span align="center">

**BinaSehat** adalah sebuah program yang dibangun menggunakan framework Laravel 9 dengan tujuan untuk mengetahui suatu informasi sederhana mengenai sistem rumah sakit.

[![](https://img.shields.io/badge/Berikan-Apresiasi-red)](https://trakteer.id/anteikudevs?quantity=1)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/muhammedia/binasehat/blob/main/LICENSE)
[![](https://img.shields.io/badge/Developer%20by-Muham-purple)](https://anteiku.tech/)

</span>

[![BinaSehat preview](https://raw.githubusercontent.com/muhammedia/binasehat/main/image/home.png)](https://muhampedia.tech)

<br>

<h2 align="center">Pendahuluan</h2>

### Sistem Requirement
- [XAMPP](https://www.apachefriends.org/download.html) or [Laragon](https://laragon.org/) with [PHP version 8.1](https://www.php.net/downloads) atau diatasnya.
- Database MySQL or [PHPMyAdmin](https://www.phpmyadmin.net/) **(Rekomendasi)**
- Code editor [Visual Studio Code](https://code.visualstudio.com/) or [Sublime Text](https://www.sublimetext.com/)

### Panduan Instalasi
Berikut ini adalah panduan instalasi pada komputer anda. Klik **Lihat Panduan** untuk mengikuti proses instalasi
<details><summary><b>Lihat Panduan</b></summary>

- Clone repo ini melalui **[git bash](https://git-scm.com/downloads)** : `git clone https://github.com/muhammedia/binasehat.git`
- Ekstrak file **binasehat.zip** yang sudah kalian clone melalui tautan diatas ini
- Done

</details>

Pastikan bahwa anda sudah mengikuti [Panduan Instalasi](#panduan-instalasi) dengan benar.

<h2 align="center">File Konfigurasi</h2>

Sebelum anda memulai menjalankan program, pastikan bahwa sudah memiliki [XAMPP](https://www.apachefriends.org/download.html) atau [Laragon](https://laragon.org/) yang sudah terinstall pada komputer yang anda gunakan.

### Konfigurasi Database

- Jalankan Apache & MySQL pada [XAMPP](https://www.apachefriends.org/download.html) atau [Laragon](https://laragon.org/).
- Akses tautan berikut ini pada browser yang kalian gunakan : `http://localhost/phpmyadmin/`.
- Buat database baru menggunakan nama **db_pas_kelompok9.**
- Buka file `.env` yang terdapat dalam directory root dan isi konfigurasi database pada kode didalam ini. Anda juga dapat mengganti nama database pada kode dibawah ini `DB_DATABASE=db_pas_kelompok9`.

```diff
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=db_pas_kelompok9 //(isi nama database kalian)
DB_USERNAME=root
DB_PASSWORD=
```

### Konfigurasi Sistem

Berikut ini adalah panduan cara menjalankan program pada komputer Anda. Pastikan bahwa anda sudah melakukan konfigurasi dan sudah membuat database yang dibutuhkan. Lihat [Konfigurasi Database](#konfigurasi-database)

<details><summary><b>Lihat Panduan</b></summary>


- Buka folder **binasehat** menggunakan [code editor](#sistem-requirement) kesayangan Anda. Disini saya merekomendasikan untuk menggunakan **Visual Studio Code**.
- Buka **Terminal** pada menu bagian atas **Visual Studio Code** atau anda bisa menggunakan shortcut *CTRL+SHIFT+`*.
- Jalankan perintah berikut `php artisan migrate` setelah berhasil maka jalankan perintah kedua `php artisan db:seed --class AkunSeeder`.
- Jalankan perintah `php artisan serve` dan akses IP `http://127.0.0.1:8000` pada browser yang kalian gunakan.
- Done

</details>


<h2 align="center">Team Developer</h2>

<div align="center">
        <a href="https://muhampedia.tech">
            <img src="https://raw.githubusercontent.com/muhammedia/binasehat/main/image/team/muham.png"
                alt="Muhammad Maghribi" width="75" height="75">
        </a>
        <a href="javascript:void(0)">
            <img src="https://raw.githubusercontent.com/muhammedia/binasehat/main/image/team/novita.png"
                alt="Novita Nanda Sari" width="75" height="75">
        </a>
        <a href="javascript:void(0)">
            <img src="https://raw.githubusercontent.com/muhammedia/binasehat/main/image/team/diana.png"
                alt="Diana Anggi Safitri" width="75" height="75">
        </a>
        <a href="javascript:void(0)">
            <img src="https://raw.githubusercontent.com/muhammedia/binasehat/main/image/team/kayla.png"
                alt="Kayla Zahrani Amadhita" width="75" height="75">
        </a>
    </div>

<hr>

## Disclaimer

Aplikasi ini masih dalam tahap pengembangan! Jika anda berminat untuk ikut serta mengembangkan projek **BinaSehat** silahkan <a href="mailto:muhampedia.id@gmail.com">hubungi kami</a>.

## License

**BinaSehat** dilisensikan di bawah [MIT License](LICENSE)