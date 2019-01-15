---
title: "Mudah Install Driver Canon Lbp6030 Di Linux"
date: 2019-01-08T20:30:46+07:00
draft: false
---
## Download driver
Driver untuk canon LBP 6030 dapat anda dapatkan melalui website resmi mereka di https://support-asia.canon-asia.com/contents/ASIA/EN/0100595001.html. Jika anda menggunakan sistem operasi linux, web tersebut sudah langsung memilihkan driver yang tepat untuk anda.
Klik tombol download, kemudian anda akan mendownload file bernama linux-UFRIILT-drv-v150-uken.tar.gz.
![Download driver printer](/imgpost/download-driver.png)

## Instalasi driver printer
Ekstrak file yang telah anda download tadi menggunakan aplikasi bawaan dari linux, melalui desktop anda cukup klik kanan file -> pilih extract here.

Masuk ke dalam direktori yang telah anda ekstrak tadi melalui terminal dan jalankan perintah :
```
sudo ./install.sh
```
![Instalasi Driver](/imgpost/install.sh.png)

Setelah proses selesai, instaler akan secara otomatis melakukan restart service cups dan menampilkan informasi pilihan printer yang anda gunakan. Pada tahap ini, anda memilih port yang digunakan oleh printer.

![Memilih port printer](/imgpost/milih-printer.png)

Proses instalasi selesai, anda dapat menguji printer.


