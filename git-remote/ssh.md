```sh
-   SSH merupakan singkatan dari secure shell
-   ssh merupakan protokol jaringan untuk komunikasi jaringan yang aman dan terenkripsi
-   pengguna sistem linux atau mac biasanya sudah familiar dengan ssh
-   ssh merupakan aplikasi berbasis terminal

-   git sendiri memiliki beberaopa mekanisme untuk berkomunikasi denga git server, seperti
    http dan ssh
```

### SSH Key

```sh
- membuat ssh key
- ssh key merupakan kunci yang digunakan untuk autentikasi ke ssh server
- untuk membuat ssh key, kita bisa gunakan perintah ssh-keygen di terminal
- setelah selesai, maka secara otomatis akan terdapat 2 key local, private key dan public key
- kita bisa melihatnya didalam folder .ssh di Home Directory kita
- File **id_rsa** adalah private key, dan **id_rsa.pub** adalah public key
```

### SSH Public Key

```sh
- setelah kita membuat ssh key, selanjutnya kita perlu meregistrasikan SSH public key ke github
- hal ini dilakukan, agar ketika nanti terkoneksi ke Git server di github, kita tidak perlu
  melakukan autentikansi lagi
- https://github.com/settings/keys
```

### Test SSH ke Github

```sh
- gunakan perintah ssh -T git@github.com
```
