### Cherry Pick

```sh
merupakan fitur yang digunakan untuk mengambil commit dari branch manapun
dan kita merge ke dalam branch saat ini.

- misal sekarang kita ingin melakukan merge branch feature/4, namun kita tidak ingin
merge semua perubahan
- misal saja kita hanya ingin melakukan merge perubahan di file cherry-pick.txt dan merge-conflict.txt
- maka kita bisa melakukan cherry pick untuk commit perubahan tersebut,
caranya gunakan perintah :

$ git cherry-pick commitId

>> commitId adalah id commit pada branch sekarang
```
