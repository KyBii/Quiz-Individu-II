# Quiz-Individu-II
## 1. Penjelasan versi pada gambar download python dibawah

![a](https://user-images.githubusercontent.com/92983457/138550932-7bf92031-635b-408a-9985-a94df02b722d.png)

- [x] **3.** adalah revisi besar yang terjadi pada python, seperti penambahan syntax, perubahan cara deklarasi dsb dalam gambar tersebut python telah melakukan revisi besar sebanyak 3 kali
- [x] **10.** adalah revisi kecil seperti perbaikan bug atau perubahan pada function python yg sudah ada
- [x] **0** adalah nomor build 

## 2.Penjelasan tools pada vsc
* **Explorer**
untuk menampilkan list file dalam sebuah folder
```
Tutorial
klik file dipojok kiri atas kemudian pilih open folder maka window baru akan muncul, pilih folder yang dituju kemudian klik open folder di pojok kanan bawah
maka akan tambil list file dalam folder tersebut
```
![1](https://user-images.githubusercontent.com/93004722/138714398-e718a0cc-cee5-4dc7-9d8c-8fbccbf2d250.PNG)

* **Search**
Digunakan untuk mencari baris kode dengan mengetikkan keywords pada kolom seperti di gambar

![2](https://user-images.githubusercontent.com/93004722/138714757-4e0b6b5b-46b8-4ab9-acd7-b96cff10b54d.PNG)

* **Replace**
berada dibawah kolom Search, digunakan untuk mengganti teks yang diketik pada kolom search dengan teks yang diketik pada kolom replace
 secara keseluruhan atau individu
 ```
 Tutorial
 ketikkan text yang anda ingin ganti, disini saya mengetikkan 'moment'(merah) untuk diganti dengan 'datetime'(putih)
 pilih baris yang ingin teks nya diganti dengan 'datetime' kemudian arahkan cursor pada simbol di `b^c` atau tekan ctrl+shift+1 pada keyboard
 ```
 ![3](https://user-images.githubusercontent.com/93004722/138715065-45f679de-9e3a-4ee6-b06e-33d3e0377b6d.PNG)
 
 * **Source control**
 digunakan untuk mengontrol versi program yang kita upload ke github dari VSCode jika anda punya git repository
 ```
 Tutorial
 kalau anda punya repository github di package handler tinggal klik initialize repository, pada gambar dibawah saya belum bikin
 ```
 ![image](https://user-images.githubusercontent.com/92983457/138576550-219c7de8-39d2-4c87-a236-e7a37971dbad.png)

* **Debug and run**
berfungsi untuk melakukan proses re-check pada kode, apakah sudah sesuai yang seperti yang diinginkan atau belum
```js
// Tutorial 
// Saya memiliki kode sebagai berikut :
let panjang = 5;
let lebar = 5;

for(var i = 1; i<=panjang; i++){
    let paragraf = "";
    for(var b = 1; b<lebar; b++){
        paragraf +="⭐";
    }
    console.log(paragraf)
}
// maksud saya ingin print 5 bintang sebanyak 5 baris tapi saat melakukan debug yang keluar hanya 4 bintang 5 baris saja, maka diketahui salahnya ada di bagian loop yang kedua
for(var b = 1; b <lebar; b++){
    //code...
//harus nya menjadi

for(var b = 1; b <= lebar; b++){
    //code...
```    
![image](https://user-images.githubusercontent.com/92983457/138577146-1c9eb8a0-4786-4429-afb2-32a553f4317d.png)

* **Extension**
Adalah macam - macam fitur tambahan yang bisa ditambahkan ke IDE visual studio code

tutorial
* klik pada tombol extension di sebelah kiri atau tekan **ctrl+shift+X** pada keyboard
* ketikkan nama extension yang anda cari maka akan keluar list seperti dibawah 

![image](https://user-images.githubusercontent.com/92983457/138580363-bfcb1e4e-14fc-4739-bb5b-fa87c593cde4.png)

* Pilih  dan klik pada extension yang ingin dipasang, maka anda akan menuju halaman install
* klik install dan tunggu sampai proses selesai 

![image](https://user-images.githubusercontent.com/92983457/138580475-8e25cfd8-db84-4862-bf56-8dc58562cabf.png)

## 3. Penjelasan serta contoh penerapan extension pada VSCode
**Extension** pada vscode adalah sebuah tools untuk mengatur fitur tambahan yang bisa dipasangkan ke VSCode untuk memudahkan pekerjaan, extension tidak terbatas pada tcode debugger, formatting, dan lint saja tapi bisa juga pada tema warna vscode, dan vscode behaviour

* **Contoh extension**
Saya memakai Bracket colorized untuk memberikan warna pada tanda kurung `()` `{}` `[]` bertujuan sebagai penanda awal dan akhir dari _bracket_(kurung) agar lebih mudah,
penerapan pada vscode dibawah ini 

![image](https://user-images.githubusercontent.com/92983457/138580096-572f83f4-fc85-4b88-bc33-bd0632911955.png)

pada gambar tersebut bisa dilihat warna tanda kurung pada vsc jadi bermacam-macam ketika di klik pada salah satu kurung maka kan ada warna lagi yang mengarahkan ke ujung bracket seperti ini 

![image](https://user-images.githubusercontent.com/92983457/138580161-4c61b19a-d364-43af-86dd-90b74b23f1e1.png)


