### Git Reset Mode

```sh
git reset <mode> hash (ex: 34567c...)

1. --soft, memindahkan HEAD pointer namun tidak melakukan perubahan apapun di Staging Index
dan Working directory.
(TODO: perubahan sebelumnya tersimpan di staging index)

2. --mixed (default), memindahkan HEAD pointer, mengubah staging index menjadi sama seperti
dengan repository, namun tidak mengubah apapun di working directory
(TODO: perubahan sebelumnya akan pindah ke working directory)

3. --hard, memindahkan HEAD pointer, dan mengubah Staging index dan working directory sehingga
sama seperti repository.
(TODO: semua perubahan akan hilang dari working directory dan staging index dengan catatan
belum ada commit baru)
```
