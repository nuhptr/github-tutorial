### Github remote repository

```sh
- ketika kita membuat git project, secara default, git tidak tahu tentang remote repository
- kita perlu memberitahu ke git project yang sudah kita buat tentang lokasi git repository
```

## Menambah Remote Repository

```sh
$ git remote add nama ssh_url

- salah satu kebiasaan git, biasanya memberi nama untuk remote repository dengan origin
```

## Melihat remote Repository

```sh
- untuk melihat remote repository yang ada di git project, kita bisa gunakan perintah
$ git remote

- untuk melihat URL detail remote repository, kita bisa gunakan perintah
$ git remote get-url nama
```

## Menghapus Remote Repository

```sh
- untuk menghapus remote repository, kita bisa gunakan perintah:
rm = remove
$ git remote rm nama
```
