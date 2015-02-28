---
title: Membuat Game 2D dengan Stencyl (Space Shooter Part 2) 
subnav: blog
layout: post
type: single_post
categories: game-dev
summary: "Membuat Actor (Player, Enemies, Lasers)"
---
## Membuat Actor Players

Pada halaman **Dashboard** stencyl, silahkan memilih **Actor Type** kemudian buat sebuah Actor dengan nama Player (atau dengan nama yang anda inginkan).

![](https://farm9.staticflickr.com/8662/16483309400_f1ba8042e7_z_d.jpg)

Selanjutkan akan terbuka secara otomatis halaman **Appearance** dari Actor yang baru kita buat. Pada bagian ini, kita mampu membuat sebuah animasi dari Actor yang saat ini kita buat. Namun, kali ini kita hanya akan menambahkan sebuah frame dikarenakan Actor yang kita buat tidak memiliki animasi apapun. 

![](https://farm9.staticflickr.com/8591/16050786223_c7ec93f5e5_z_d.jpg)

Langkah berikutnya adalah membuat sebuah animasi dengan cara memilih *Click here to add an animation* atau dengan cara memilih tombol tambah pada bagian paling bawah sebelah kiri dari halaman **Appearance**.

![](https://farm9.staticflickr.com/8630/16669704582_596894764a_z_d.jpg)

Pada bagian *Name* silahkan isi dengan nama animasi yang akan anda gunakan, kali ini saya menggunakan nama **ready**. Perlu diketahui, bahwa pada bagian *Looping* bernilai benar atau tercentang yang memiliki maksud bahwa jika animation ini memiliki frame lebih dari satu maka akan secara otomatis berulang dari awal sehingga membuat animasi berjalan secara terus menerus, frame demi frame.

Selanjutnya menambahkan sebuah gambar menjadi sebuah frame dengan memilih *Click here to add a frame*. Pada jendela **Import Frames from Image Strip** silahkan memilih gambar dari karakter yang akan dijadikan sebagai **Player**. Dari assets yang telah anda sebelumnya, terdapat banyak sekali karakter yang dapat anda gunakan. Pada kesempatan kali ini saya akan menggunakan *playerShip3_red.png*

![](https://farm9.staticflickr.com/8659/16644789186_2aa1a4fa41_z_d.jpg)

![](https://farm9.staticflickr.com/8680/16463433287_f2d72a2c28_z_d.jpg)

![](https://farm9.staticflickr.com/8644/16670738405_65520f59c4_z_d.jpg)

![](https://farm9.staticflickr.com/8665/16050799243_9ba5881f9f_z_d.jpg)

Selanjutnya kita akan mengatur agar **Actor** yang baru saja kita buat tidak terpengaruh dengan **Gravity** dan tidak dapat melakukan **Rotasi** secara bebas. Buka tab **Physics** lalu pada bagian *Rotate* dan *Gravity* ubah menjadi **No**.

![](https://farm9.staticflickr.com/8619/16050805823_6626259870_z_d.jpg)

Sekarang kita akan memasukkan **Actor** yang baru saja kita buat ke dalam **Group** *Players*. Dengan cara buka tab **Groups** kemudian pada bagian **Choose Group** ubah menjadi *Players*. Hal ini nantinya akan sangat berguna untuk penggunaan **Actor** agar lebih mudah, seperti contohnya pada bagian **Collision** atau bersentuhan dengan **Actor** lainnya.

![](https://farm9.staticflickr.com/8656/16048433974_3377fc877f_z_d.jpg)

## Membuat Groups Enemies dan Lasers

Buka jendela **Settings** melalui menu ataupun toolbar di Stencyl. Lalu pada jendela **Settings** pilih dan buka tab **Groups**. Kemudian buat sebuah group dengan nama **Enemies** kemudian buat lagi sebuah group dengan nama **Lasers** lalu pada group **Lasers** pilih *Collides With* **Enemies**.

![](https://farm9.staticflickr.com/8600/16671077245_b4d548a5f3_z_d.jpg)

![](https://farm9.staticflickr.com/8581/16484923789_118dbb989e_z_d.jpg)

![](https://farm9.staticflickr.com/8581/16484923789_118dbb989e_z_d.jpg)

![](https://farm9.staticflickr.com/8670/16483666900_2c6ce017a7_o_d.png)

![](https://farm9.staticflickr.com/8650/16483666840_1f8b015df0_z_d.jpg)

