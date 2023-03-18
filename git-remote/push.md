### Git Push

```sh
# push branch
- untuk mengirim perubahan branch ke remote repository dengan nama branch yang sama:
$ git push namaremote localbranch

- untuk mengirim perubahan branch ke remote repository dengan nama branch yang berbeda,
kita bisa gunakan:
$ git push namaremote localbranch:remotebranch

# - push semua branch
- jika kita ingin mengirim semua perubahan di semua branch ke remote repository, kita bisa gunakan:
$ git push origin --all

# - menghapus Branch
- perintah push juga bisa digunakan untuk menghapus branch yang ada di remote repository
- kita bisa gunakan perintah 
$ git push --delete namaremote namabranch

- perlu diingat, menghapus remote branch bukan berarti menghapus branch di local, jadi jika kita ingin hapus
di local, kita harus lakukan dengan manual 
```
