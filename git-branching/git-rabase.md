### Git rebase (Mengubah ulang commit master depannya)

## Untuk menggabungkan branch

pindah ke branch yang akan di rebase, berbeda dengan merge yang mengharuskan pergi dari branch
yang akan dimerge, di REBASE kalian harus stay di branch yang akan di rebase.

```sh
- Untuk melakukan rebase, kita bisa lakukan perintah
$ git rebase namabranch

- jika sekarang kita ada di branch feature/rebase, lalu gunakan perintah
$ git rebase master

- artinya kita melakukan rebase semua commit dimaster dari branch feature/rebase (develop)
```

## Merge branch

```sh
- setelah melakukan rebase, bukan berarti branch yang direbase sekarang posisinya ada di branch
yang melakukan rebase, posisinya tetap ada di commit terakhir branch tersebut

- seperti yang terlihat pada gambar Diagram Rebase Branch

- Agar posisinya sama dengan branch yang melakukan rebase, 
kita bisa menggunakan perintah MERGE
```
