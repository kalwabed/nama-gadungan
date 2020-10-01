<img src="https://img.shields.io/codecov/c/github/rizafahmi/nama-gadungan?style=flat-square" />  <img src="https://img.shields.io/github/repo-size/rizafahmi/nama-gadungan?style=flat-square" />  ![npm](https://img.shields.io/npm/dm/nama-gadungan?style=flat-square)  ![GitHub](https://img.shields.io/github/license/rizafahmi/nama-gadungan?style=flat-square)  ![GitHub Hacktoberfest combined status](https://img.shields.io/github/hacktoberfest/2020/rizafahmi/nama-gadungan?style=flat-square)

# nama-gadungan

Pustaka kecil yang dapat membantu kamu untuk mendapatkan nama acak untuk data gadungan atau data _dummy_ yang dapat digunakan untuk aplikasi dan database. Pustaka ini bertujuan untuk eksperimen bagi yang ingin belajar berkontribusi ke proyek opensource. Lihat proses pembuatannya di [youtube](https://www.youtube.com/playlist?list=PLTY2nW4jwtG_5wjvX1hFqgRe_QbcLVsWS).

## Daftar isi

* [Permulaan](#permulaan)
  * [Prasyarat](#prasyarat)
  * [Instalasi](#instalasi)
* [Penggunaan](#penggunaan)
* [Cara kontribusi](#cara-berkontribusi)
* [Todo](#todo)

## Permulaan
### Prasyarat
* [Node.js](https://nodejs.org) versi terbaru / stabil (lts)
 ## Instalasi
 ### Menggunakan npm / yarn
```
npm install nama-gadungan
```
```
yarn add nama-gadungan
```
### Menggunakan CDN

```
<script src="https://unpkg.com/nama-gadungan@1.0.0/dist/bundle.js" type="module"></script>
```
## Penggunaan

### Node.js
```javascript
const { random } = require('nama-gadungan');

const name = random();
console.log(name);
```

### Browser

```html
<!doctype html -->
<html>
  <head>
    <title>Contoh Penggunaan Nama Gadungan</title>
  </head>
  <body>

    <script src="https://unpkg.com/nama-gadungan@1.0.0/dist/bundle.js" type="module"></script>
    <script type="module">
      import { random } from './bundle.js';

      console.log(random());
    </script>
  </body>
</html>
```

## Cara Berkontribusi

* Fork repositori ini
* Clone repositori
* Lakukan perubahan atau perbaikan
* Buat test case
* Push dan buat Pull Request

## TODO
- [x] Ganti license di package.json
- [ ] Lengkapi README
- [x] Tambah file LICENSE
- [ ] Bahasa Indonesia dan Bahasa Inggris
