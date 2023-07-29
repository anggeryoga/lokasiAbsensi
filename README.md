# Absensi Lokasi - Aplikasi Web
## Demo

Silakan lihat demo aplikasi [di sini](https://anggeryoga.github.io/lokasiAbsensi/).


## Deskripsi

Absensi Lokasi adalah aplikasi web sederhana yang memungkinkan pengguna melakukan absensi menggunakan lokasi. Aplikasi ini akan memeriksa apakah pengguna berada dalam radius lokasi yang diizinkan, dan kemudian mencatat kehadiran beserta jam kedatangan ke dalam Google Sheets.

## Fitur

- Pengguna dapat memasukkan nama dan nomor absensi.
- Aplikasi akan memeriksa apakah lokasi pengguna berada dalam radius yang diizinkan.
- Jika pengguna berada dalam radius yang diizinkan, kehadiran mereka akan dicatat bersama dengan jam kedatangan.
- Jika pengguna berada di luar radius yang diizinkan, kehadiran mereka tidak akan dicatat, dan mereka akan menerima notifikasi.
- Aplikasi mengirim data formulir (termasuk latitude dan longitude) ke skrip Google Sheets untuk mencatat kehadiran.

## Demo

![Absensi Lokasi Demo](demo.gif)

## Instalasi

1. Clone repositori ke mesin lokal Anda:

```javascript
git clone [https://github.com/anggeryoga/lokasiAbsensi.git](https://github.com/anggeryoga/lokasiAbsensi.git)
```
## Cara Kerja
1. Aplikasi menggunakan API Geolocation untuk mendapatkan lokasi saat ini dari pengguna.
2. Lokasi pengguna dibandingkan dengan latitude dan longitude lokasi yang diizinkan untuk memeriksa apakah berada dalam radius yang diizinkan.
3. Jika pengguna berada dalam radius yang diizinkan, formulir kehadiran akan dikirimkan secara otomatis, dan data akan dikirimkan ke Google Sheets menggunakan URL skrip.
4. Jika pengguna berada di luar radius yang diizinkan, formulir kehadiran tidak akan dikirimkan, dan notifikasi akan ditampilkan.

## Teknologi yang Digunakan
- HTML
- CSS
- JavaScript
- Google Sheets API

  ## Kontak
Jika ada pertanyaan atau kendala bisa langsung menghubungi saya 

- **Email**: [anggerajiprayogokusuma@gmail.com](mailto:anggerajiprayogokusuma@gmail.com)
- **LinkedIn**: [anggeraji](https://www.linkedin.com/in/anggeraji)
- **Website**: [anggeraji.my.id](https://www.anggeraji.my.id)

Jangan ragu untuk menghubungi saya melalui salah satu platform di atas. Saya senang mendengar dari Anda dan siap untuk berkolaborasi dalam proyek yang menarik!
