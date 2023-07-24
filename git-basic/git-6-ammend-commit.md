### Git Ammend Commit

```sh
- kadang ketika sudah melakukan commit kita lupa, ada beberapa hal yang terlupakan
- biasanya kita akan reset menggunakan mode --soft lalu tambahkan perubahan
- hal tersebut bisa dilakukan tanpa manual reset menggunakan :
```

```sh
$ git commit --amend
note: ammend akan mengubah hash commit karena data perubahan yang dicommit akan bertambah

$ git commit --amend -m "nama commit"
```
