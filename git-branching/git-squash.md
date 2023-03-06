### Git Squash

```sh
- saat kita melakukan merge / rebase, semua commit history akan tetap ada

- jadi kita di branch tersebut melakukan commit sebanyak 10x ,
ketika kita lakukan merge / rebase, maka 10 commit tersebut akan tetap ada

- kadang ada kasus dimana kita ingin melakukan penggabungan commit
tersebut menjadi 1 commit saja, hal ini dinamakan SQUASH

- squash akan membuat 10 commit history tersebut menjadi 1 commit, dimana
semua 10 perubahan tersebut akan digabungkan menjadi 1 commit saja
```

### Melakukan Squash

```sh
- squash bisa dilakukan ketika merge / rebase
- untuk melakukan squash ketika merge, kita bisa gunakan perintah
$ git merge --squash namabranch
```
