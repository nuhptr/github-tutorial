### Git Blame

```sh
digunakan untuk mengetahui siapa yang melakukan perubahan baris kode program
dan apa saja yang ditambahkan

=> git blame namafile.extension

example : file configuration.txt
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 1) git config --global user.name "Adi Nugraha Putra"
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 2) git config --global user.email "nugrahaadi733@gmail.com"
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 3)
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 4) - melihat seluruh configuration
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 5) git config --list (di mac saya cuma bisa ini)
cf3aeeca (nuhptr 2022-07-23 21:18:36 +0700 6) atau bisa ditambah --show-origin
```
