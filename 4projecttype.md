
#npm #javascript #js
project type dalam nodejs memiliki dua tipe sama commonjs dan modules  
* **commonjs** ini adalah versi module lama dengan extesnion js
* **module** adalah versi dari versi dari javascript baru atau ecmascript 6 keatas dengan ekstension mjs

setiap tipe memiliki cara menggunakan yang beda jika commojs dengan require sedangakan module dengan import / export 

rekomendasi penggunaan js modern adalah type ny module, type module mengguanakn ektension mjs , agar kita dapat menggunakan ekstension js di npm kita harus menggubah type pada seting json ny menjadi module 

```js
'name': 'npm'
'author':'muhammad fajrin saputra,S.Kom'
'type': 'module',

```

ini versi common js
```js
let cekos = require "os"

console.log(cekos)
```


ini versi module
```js
import os from 'node:os'

let cekos = os.cpus()
console.log(cekos)
```
