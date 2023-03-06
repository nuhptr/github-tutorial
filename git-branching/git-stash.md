### GIT STASH

```sh
- kadang ada keadaan dimana kita sedang melakukan perubahan disebuah branch,
namun perubahannya belum disimpan di repository, misal masih di working / staging index
- lalu kita butuh secepatnya melakukan perubahan di branch lain
- jika perubahan tersebut belum siap kita commit, kita bisa menyimpan semua perubahan tersebut di Stash
- STASH adalah sebuah tempat dimana kita bisa menyimpan perubahan di working / staging index
secara sementara agar branch saat ini menjadi bersih kembali, sehingga kita bisa pindah ke branch lain

# Menyimpan perubahan ke Stash
- untuk menyimpan perubahan ke Stash, kita bisa gunakan perintah
$ git stash push -m 'message stash'

- untuk melihat semua Stash, kita bisa gunakan perintah
$ git stash list

- untuk melihat perubahan yang terjadi di stash, kita bisa gunakan perintah
$ git stash show stashId

* stashId adalah reference perubahan yang disimpah tash terakhir kali

# Mengambil perubahan di stash
- untuk mengambil perubahan di stash, kita bisa gunakan perintah
$ git stash apply stashId

- untuk menghapus stash, kita bisa gunakan perintah
$ git stash drop stashId

- untuk menghapus semua stash, kita bisa gunakan perintah
$ git stash clear
```
