---
title: "Menjalankan Aplikasi Windows Via Wine"
subnav: blog
layout: post
type: single_post
categories: ngoprek
summary: "Aplikasi Windows yang bertabrakan dengan Window Manager GNU/Linux"
---

Berikut adalah cara menjalankan beberapa aplikasi Windows di **GNU/Linux** via *Wine* yang kadang bermasalah dengan Window manager di **GNU/Linux**.
![](https://farm9.staticflickr.com/8601/16243261411_a5bb1bb778_z_d.jpg)
Pertama-tama silahkan simpan file yang akan kita jalankan disebuah directory (folder) yang mudah kita akses. Sebagai contoh saya akan menyimpan file yang ingin saya buka di directory **/tmp/anu/**

Selanjutnya buka Wine Configuration dari menu, atau dari konsol dengan perintah
{% highlighting bash %}
winecfg
{% endhighlighting %}
![](https://farm8.staticflickr.com/7473/16243242751_7287f96b5e_o_d.png)
Lalu pilih **Add Application** kemudian cari file yang akan dijalankan lalu tambahkan.
![](https://farm8.staticflickr.com/7536/16057563108_68aeb0c5e6_z_d.jpg)
Setelah itu, pada bagian **Windows Version** silahkan rubah ke versi windows yang anda inginkan (saya memilih Windows XP).
![](https://farm9.staticflickr.com/8609/16058969349_7cab4fa55b_z_d.jpg)
Setelah itu tetap pada applikasi yang kita tambahkan buka tab **Graphics** kemudian hilangkan semua centang tab tersebut, kemudian OK atau Apply.
![](https://farm9.staticflickr.com/8673/16245107385_bac6c2d04d_o_d.png)
Setelah itu coba buka aplikasi yang tadi, maka aplikasinya akan berjalan dengan lebih baik walaupun tidak 100% sempurna.
![](https://farm8.staticflickr.com/7529/16057715930_265144bdd3_z_d.jpg)
*Jika pada saat menjalankan aplikasi masih bertabrakan dengan window manager silahkan tekan tombol 'Tab'