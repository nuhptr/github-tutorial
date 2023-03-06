### Git Tag

```sh
- Tag merupakan fitur, dimana kita bisa menandai sebuat commit id
- Sebelumnya kita tahu bahwa head yaitu reference commit terakhir di branch kita saat ini
- Jika kita ingin membuat sebuah reference ke sebuah commit, kita bisa menggunakan TAG
- Dalam pengembangan perangkat lunak, biasanya Tag digunakan sebagai penanda versi rilis aplikasi,
misal tag 1.0.0, tag 1.0.2, dan lain-lain
- karena tag merupakan reference ke commit, jadi tag bisa dilakukan di branch manapun

# Membuat Tag
- Tag bersifat unique jadi gunakan nama yang berbeda
$ git tag tagName commitId

# Menampilkan Tag (pilih salah satu aja)
$ git tag
$ git tag -l
$ git tag --list

# Checkout ke tag jangan lupa dibikin tag di commit id branch lain
$ git checkout tagName
```
