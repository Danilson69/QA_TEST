# Panduan Instalasi dan Menjalankan Aplikasi Web Node.js dengan Express

## 1. Instalasi Node.js

Sebelum menjalankan aplikasi berbasis Node.js dan Express, pastikan Anda telah menginstal Node.js dan npm (Node Package Manager).

### Windows & macOS

1. Unduh Node.js dari situs resminya: https://nodejs.org/
2. Pilih versi LTS (Long-Term Support) untuk kestabilan terbaik.
3. Jalankan installer dan ikuti proses instalasi.
4. Setelah instalasi selesai, buka Command Prompt (CMD) / Terminal dan jalankan perintah berikut untuk memastikan instalasi berhasil:

```sh
node -v
npm -v
```

Jika perintah tersebut menampilkan versi Node.js dan npm, berarti instalasi telah berhasil


## 2. Clone Repositori dari Git

Jika proyek disimpan dalam repositori Git, Anda perlu meng-clone repositori tersebut.

1. Pastikan Git telah terinstal dengan menjalankan perintah berikut:
```sh
git --version
```
2. Clone repositori proyek menggunakan perintah:
```sh
git clone <URL_REPOSITORY>
```
3. Masuk ke direktori proyek yang telah di-clone:
```sh
cd repository
```

## 3. Instalasi Dependencies dan Menjalankan Server

Setelah repositori berhasil di-clone, instal dependencies yang dibutuhkan:

1. Jalankan perintah berikut untuk menginstal semua dependensi dari package.json:
```sh
npm install
```
2. Setelah instalasi selesai, jalankan server dengan perintah:
```sh
npm start
```
atau jika menggunakan nodemon:
```sh
npm run dev
```
3. Jika server berjalan dengan sukses, Anda akan melihat pesan seperti:
```sh
Server running at http://localhost:3000
```
Buka browser dan akses http://localhost:3000 untuk melihat aplikasi berjala