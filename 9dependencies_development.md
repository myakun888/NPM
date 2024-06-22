# Development Dependencies 

pada package lock json , sebenarnya ada dua dependencies
1. dependencies production
2. dependencies development

untuk dependencies production ini yang sudah di bahas sebelumnnya pada pada materi [[7dependencies_management]]


### pengertian develompent dependencies / devDependecines

adalah dependesi yang diugunakan saat proseses develoment saja , tidak harus kita upload pada aplikasi kita
berbeda dengan dependencie production itu wajib karena itu yang akan berjalan dengan apliksi kita

contoh beberapa devdependcie seperti module unit test, dll


### cara instal devdependecies

pada packakge json nya cukup tambahkan properti `devDependecies`

sebagai berikut

*  **cara 1**
```json

"dependencies" : {
"lodash ": "1.2.1"
}
"devDependencies": {  
"jest":"1.3.1"
}

//jest adalah devdependencies ny
```

setelah di tambahkan di package ny 
lalu jalankan di terminal perintah `npm install` untuk mendonwload atau menginstal nya


*   **cara 2**
cara dua langsung pada terminal
ketikan perintah `npm install namapacakge --sev-dev`
contoh

```cmd
npm install jest --sev-dev
```

\
### cara install dependencies tanpa development

secara default saat kita melakukan perintah `npm install`, semua dependencies akan terinstall termasuk development

jika kita ingin menginstal tanpa development 
caranya adalah

```cmd
npm install --production
```