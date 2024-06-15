#npm  #js 
untuk menjalankan npm sama seperti node js yaitu

```cmd

node namafile.js
```

secara default npm akan menjalankan atau mengecek file json ny terlebih dahulu jika ada script yang di eksekusi baru ke node ny

### script pada npm

npm memiliki fitur script yang memudahkan kita dalam menjalankan npm
beberapa sricpt di npm diantaranya
* start
* run
* test 
dan lainya

setting npm script pada package json
```js
"scripts":{
"run" :" node datas.js"
"start": "node data.js"
}
```


### menjalankan script
perintah cmd nya

`npm run-script namascript`

```cmd
npm run-script run

```

### node juga memiliki spescial script

artinya npm dapat menjalanakan hanya dengan namanya saja
diantara nya special script , dimana special script tidak harus menggunakan kata run-script
`start, run, install, uninstall `


```cmd

npm start
```

di karenakan kita sudah menyeting perintah npm start , jadi kita tidak perlu lagi menulis 
node data.js


scirpt bisa digunakan untuk menjadi perintah pada node yang jika perintah nya panjang kita bisa mengguanakn script