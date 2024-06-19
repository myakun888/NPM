# dependecies management
#npm 

salah satu fitur yang sangat berguna dari NPM adalah dendencie management,
saat kita membuat project kita mungkin perlu library atau module , kita tidak perlu membuat secara manual jika module / library yang kita perluakan ada di npmjs.com kita tinggal download saja, atau pun jika ada update kita tinggal update saja,tidak perlu secara manual


## ada dua cara untuk menginstal library /module 
#### 1. dengan menambahkan pada pacakage json nya
kita masuk ke pacake json nya
tambahakan library yang kita mau (pastikan nama nya benar, silahkan liaht di npmjs terlebih dahulu),  dalam hal ini misal nya lodash
```json
"dependecies" : {
"lodash" :"5.7.21"
}
```
setelah di masukan di dalam json , library / module yang kita perlukan , lanjut kita install / download
jalankan perintah pada termanal

```cmd
npm install
```
maka library telah di install


#### 2. langsung pada terminal

cara kedua ini lebih banyak di gunakan caranya yaitu

```cmt
npm namalibrary
```
ini akan menginstal library dengan versi terakir, jika ingin menginstal dengan versi tertentu kita bisa menuliskan versinya

```cmd
npm namalibrary@1.1.1
```
