1. tidak bisa dihindari kadang programmer akan melakukan perubahan pada kode file
yang sama dibranch yang berbeda
2. dan biasanya ketika melakukan merge, akan terjadi yang namanya conflict
3. hal ini disebabkan, satu file diubah di branch yang berbed, sehingga ketika merge
kita perlu melakukan yang namanya merge conflict

- membatalkan conflict
yang gagal akan masuk ke working directory
kita bisa gunakan perintah :
// git merge --abort

- memperbaiki conflict
memperbaikinya secara manual tidak ada cara otomatis
jika sudah diperbaiki lakukan commit ulang