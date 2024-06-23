# Igonre file

ignore pada npm , sama seperti pada gitignore , yaitu agar file tersebut tidak ikut di publish saat kita melakukan publisch fiel

untuk cara nya sama seperti giginore

buat file dengan eksternsi `.npmingnore`

### cara kerja
secara default saat packge lock json berjalan, npm akan memeriksa pada package apakah ada file .npmignore , maka akan di eksusi jika ada nama file / folder yang di masukan dalam .npmignore
jika tidak ada baru npm akan memeriksa gitigonre

> *maka dari itu secara teknis jika kita sudah membuat file .gitigore kita tidak harus membuat .npmignore* , kecuali memang ingin memisahkan berdasarkan kan , .npmignore dan .gitognre


### membuat .npmignore

 * setelah di buat file dengan nama `.npmignore`
 * lalu buka file tersbut dan tuliskan , nama file / folder file yang ingin kita ignore
```.npmignore
modul.txt
berkas
```
contoh seperti diatas
artinya
file dengan nama ***modul.txt*** dan ***folder berkas*** , itu tidak di publish (perlu di ingat jika kita memasukan nama folder, maka semua yang ada di dalam folder tersebut juga otomatis di ignore)