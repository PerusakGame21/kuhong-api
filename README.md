# Selamat Datang Di Rest Api Github! <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Hi.gif" width="50px">
<img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Developer.gif" width="500px">

## Apikey? Chat Admin <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/happy.gif" width="30px">
[`Kontak Saya`](https://wa.me/62895337278647?text=Bang%20Minta%20Apikey%20Kuhong-Api%20)
Apikeynya Gratis kok gan,, tenang aja ;D

## Contoh Kode <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Medal.gif" width="30px">

### Untuk Teks (Non-Media)
```bash
$ npm install axios
```
```js
const axios = require('axios') // Module yg dibutuhkan untuk menscrap website

axios.get('https://raw.githubusercontent.com/RC047/kuhong-api/main/contoh.json').then((res) => { // Scrap web
 let random = Math.floor(Math.random() * res.data.length) // Acak objek
 let data = res.data[random] // Setelah diacak arahkan ke teks respon sesuai nama diweb
   console.log(data.result) // Ta Daa
})



// Note : Link harus teks raw (https://raw.githubusercontent.com)
```
### Untuk Gambar/Video (Media)
```bash
$ npm install axios
$ npm install image-to-base64
```
```js
const imageToBase64 = require('image-to-base64') // Untuk mengubah menjadi gambar
const axios = require('axios') // Module yg dibutuhkan untuk menscrap website

axios.get('https://raw.githubusercontent.com/RC047/kuhong-api/main/contoh_gambar.json').then((res) => { // Scrap web
 let random = Math.floor(Math.random() * res.data.length) // Acak objek
 let data = res.data[random] // Setelah diacak arahkan ke teks respon sesuai nama diweb
  imageToBase64(data.gambar).then((result) => { // Ubah menjadi gambar
   let hasil = Buffer.from(result, 'base64') // Konversi teks base64 ke gambar/video
     console.log(hasil) // Ta Daa
   })
})

// Note : Respon akan berupa teks buffer,, gunakan alat seperti media sender agar merespon menjadi media gambar/video
```

## Dokumentasi <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/coin.gif" width="25px">

| Nomor | Nama | Deskripsi | Status | Link |
| :-: | :-----------------: | :-----------------: | :-------: | :-------: |
| 1 | Test API Teks | Pratinjau Contoh Respon API Teks | - | [`Klik Disini`](https://raw.githubusercontent.com/RC047/kuhong-api/main/contoh.json)|
| 2 | Test API Media | Pratinjau Contoh Respon API Media | - | [`Klik Disini`](https://raw.githubusercontent.com/RC047/kuhong-api/main/contoh_gambar.json)|
| 3 | Anime | Mengirimkan Gambar Anime | Aktif  | [`Klik Disini`](https://tinyurl.com/4pk8n3ka)|
| 4 | Asupan | Megirimkan Video Penyegar Timeline | Aktif | [`Klik Disini`](https://tinyurl.com/uzmk2ytz)|
| 5 | Berita | Mengirimkan Informasi Berita Terkini | Aktif | [`Klik Disini`](https://tinyurl.com/3rxhkzve)|
| 6 | BTS | Mengirimkan Gambar BTS | Aktif | [`Klik Disini`](https://tinyurl.com/uyd3kw74)|
| 7 | Black Pink | Mengirimkan Gambar BlackPink | Aktif | [`Klik Disini`](https://tinyurl.com/2mz7s5p7)|
| 8 | Bokep | Mengirimkan Gambar 18+ | Aktif | [`Klik Disini`](https://tinyurl.com/p8xf5e6s)|
| 9 | Bucin | Mengirimkan Kata Bucin | Aktif | [`Klik Disini`](https://tinyurl.com/2mz7s5p7)|
| 10 | Cak Lontong | Mengirimkan Soal Cak Lontong | Aktif | [`Klik Disini`](https://tinyurl.com/9u6vmeyw)|
| 11 | Cantik Cek | Menentukan Seberapa Cantiknya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/bp6rmrjm)|
| 12 | Cecan | Mengirimkan Gambar Cewek Cantik | Aktif | [`Klik Disini`](https://tinyurl.com/y6cd972d)|
| 13 | Cogan | Mengirimkan Gambar Cowok Ganteng | Aktif | [`Klik Disini`](https://tinyurl.com/55zkyvsw)|
| 14 | Dadu | Permainan Dadu | Aktif | [`Klik Disini`](https://tinyurl.com/RC047)|
| 15 | Dadu Gambar | Permainan Dadu Versi Gambar | Aktif | [`Klik Disini`](https://tinyurl.com/35m7xnac)|
| 16 | Dark Jokes | Mengirimkan Gambar Meme Gelap | Aktif | [`Klik Disini`](https://tinyurl.com/h3htsafa)|
| 17 | EXO | Mengirimkan Gambar EXO | Aktif | [`Klik Disini`](https://tinyurl.com/nufwzm5u)|
| 18 | Family 100 | Mengirimkan Soal Family 100 | Aktif | [`Klik Disini`](https://tinyurl.com/2sz8umxa)|
| 19 | Ganteng Cek | Menentukan Seberapa Gantengnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/ysnm3knb)|
| 20 | Gay Cek | Menentukan Seberapa Gaynya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/k4cu97p9)|
| 21 | Gombal | Mengirimkan Kata Gombalan | Aktif | [`Klik Disini`](https://tinyurl.com/rn5saa75)|
| 22 | IQ Test | Menentukan Seberapa Pintarnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/r6ufaue6)|
| 23 | Meme Indo | Mengirimkan Gambar Meme Indonesia | Aktif | [`Klik Disini`](https://tinyurl.com/nbctte33)|
| 24 |Pantun | Mengirimkan Kata Pantun | Aktif | [`Klik Disini`](https://tinyurl.com/2j2r5jwx)|
| 25 | Puisi | Mengirimkan Kata Puisi | Aktif | [`Klik Disini`](https://tinyurl.com/5ay36eyw)|
| 26 | Quotes | Mengirimkan Kata Quotes | Aktif | [`Klik Disini`](https://tinyurl.com/3xkmt3bw)|
| 27 | Simsimi | Simsimi Menemani Anda Mengobrol | Aktif | [`Klik Disini`](https://tinyurl.com/5bmsrzna)|
| 28 | Syair | Mengirimkan Kata Syair | Aktif | [`Klik Disini`](https://tinyurl.com/y8z932xm)|
| 29 | Tebak Gambar | Mengirimkan Soal Tebak Gambar | Aktif | [`Klik Disini`](https://tinyurl.com/vew8855a)|
| 30 | Tolol Cek | Menentukan Seberapa Tololnya Anda | Aktif | [`Klik Disini`](https://tinyurl.com/28evtju2)|







# Media Sosial <img src="https://github.com/TheDudeThatCode/TheDudeThatCode/blob/master/Assets/Earth.gif" width="30px">

#### YouTube : [`RC047`](https://www.youtube.com/c/RC047)
#### Instagram : [`@rendycraft047`](https://www.instagram.com/rendycraft047)
#### Kontak : [`WhatsApp`](https://wa.me/62895337278647)
#### Donasi : [`Seikhlasnya :)`](https://saweria.co/RC047)
#### Creator : [`RC047`](https://Github.com/RC047)
