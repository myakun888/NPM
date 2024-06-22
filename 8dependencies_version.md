#npm

# dependecies version

npm menganut semantic version dalam versi nya 
yaitu
mayor, minor dan path
contoh
versi 10.5.3

ini mayor nya 10,
minor nya 5,
patch nya 3
itu cara membaca semantic version


## dependencies
salah satu kegunaan semantic adalah kita bisa menentukan dengan di namis, artinya kita tidak perlu update, secar manual lagi ( tapi ini adalah opsi)
### menetukan versi 1

berikut simulasi nya


| no  | versi  | keterangan                                                                                          |
| --- | ------ | --------------------------------------------------------------------------------------------------- |
| 1   | x      | artinya donwload versi terbaru, update versi terbaru, baik mayor, minor,patch                       |
| 2   | 1.x    | donwload versi 1,  pada saat update MAJOR tetap 1, MINOR dan PATCH versi terbaru                    |
| 3   | 1.1.x  | donwload versi 1.1, pada saat update MAJOR dan MINOR tetep 1, untuk patch versi terbaru             |
| ==4==   | ==1.1.1==  | ==selalu donwload versi 1.1.1 , tak akan update walau ada versi terbaru==                               |
| ==5==   | ==~1.1.1== | ==download versi 1.1.1, jika ada update lakukan update namun yang di update hanya PATCH yang di rubah== |
| ==6==   | ==^1.1.1== | ==download versi 1.1.1, jika ada update laukan update namun hanya update jika MINOR dan PATCH berubah== |
**perlu di perhatikan**
saat kita membuat aplikasi biasanya dependencie saling berhunbungan jadi bijak dalam menentukan versi, karena bisa menyebabkan akan ada fitur dari module/library tidak berjalan optimal karena sesuai dengan versinya

yang biasa digunakan itu adalah cara penulisan no 4, 5, 6, atau yang di 


untuk simulasi silahkan lihat pada link berikut
[npm semantic version](**[https://semver.npmjs.com/](https://semver.npmjs.com/)**)
