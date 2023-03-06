### Create Repository Local

```sh
# Init
$ git init  => di folder yang akan ditambahkan ke github
$ git add [file] / . (jika semua)  => untuk pindahkan ke staging index
$ git commit -m "biasanya sih initial commit" => memindah ke repository perubahannya

# Working directory
untuk mengecek keadaan git sekarang
$ git status

Jika ingin menghapus dan membatalkan semua perubahan di working directory
$ git clean -f

Membatalkan perubahan file
$ git restore namafile.extension

Membatalkan penghapusan file
$ git restore namafile.extension

# Staging index
Membatalkan dari staging index (turunkan ke working directory)
$ git restore --staged namafile.extension
```
