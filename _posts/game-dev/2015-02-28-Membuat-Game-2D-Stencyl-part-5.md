---
title: Membuat Game 2D dengan Stencyl (Space Shooter Part 5) 
subnav: blog
layout: post
type: single_post
categories: game-dev
summary: "Menambahkan Logika pada Player"
---
## Membuat Player dapat bergerak

Kali ini kita akan membuat agar **Player** dapat bergerak ke kiri dan ke kanan. Buka kembali **Actor** **Player** lalu masuk kebagian **Events**. Lalu tambahkan sebuah **Event** **Basic** kemudian pilih **When Updating**. Event ini akan kita gunakan untuk melakukan cek input keyboard.

![](https://farm9.staticflickr.com/8611/16676165292_79b2616ac9_z_d.jpg)

![](https://farm9.staticflickr.com/8591/16489769540_ea5277f15c_z_d.jpg)

Sebelum terlalu jauh, mari kita pahami logika yang akan kita masukkan nantinya. Logikanya adalah sebagai berikut:

`Jika tombol kiri pada keyboard ditekan, maka kecepatan player searah dengan x akan ditambahkan dengan kebalikan 20 (negate 20). Sedangkan jika tombol kanan pada keyboard ditekan, maka kecepatan player searah dengan x akan ditambahkan dengan nilai 20. Sedangkan jika tidak menekan tombol kiri dan kanan pada keyboard maka kecepatan player searah dengan x akan diberikan nilai 0 agar player tidak melakukan pergerakan kekiri ataupun kekanan.`

Nah, setelah cukup paham dengan logika yang akan kita gunakan diatas sekarang saatnya kita memasukkannya kedalam event yang baru saja kita buat.

* Buat sebuah percabangan if, pada halaman event klik kanan pada tetikus (mouse) kemudian pilih **Place a Block** kemudian pilih **Flow** kemudian pilih kondisi if

![](https://farm9.staticflickr.com/8570/16054853824_1736459f3d_z_d.jpg)

* Masukkan logika jika tombol kiri pada keyboard ditekan dengan cara pada bagian if yang telah kita tambahkan tadi pilih kotak kosong ditengahnya kemudian akan terdapat beberapa pilihan block. Kita akan menggunakan block **User Input** kemudian pilih **Control is down**. Setelah dimasukkan, pilih kata control pada block tersebut lalu pilih **Choose Control** untuk memilih kontrol apa yang kita inginkan (kali ini adalah kiri berarti left).

![](https://farm9.staticflickr.com/8597/16491109369_3bcfc57f08_o_d.png)

![](https://farm9.staticflickr.com/8574/16057237343_88c3656e2b_z_d.jpg)

![](https://farm9.staticflickr.com/8616/16489769080_3d327e5fbf_o_d.png)

![](https://farm9.staticflickr.com/8623/16489601058_bf2b860760_z_d.jpg)

* Selanjutnya kita akan menambahkan block **Motion** -> **set x-speed**, block ini akan kita gunakan untuk mengatur kecepatan player searah dengan X. Kemudian untuk nilai, sesuai dengan logika kita. Tombol kiri akan menambah kebalikan dari 20. Maka terlebih dahulu tambahkan sebuah block negate. Dapat anda temukan di jajaran block pada bagian sebelah kanan **Numbers & Text** -> **negate**. Lalu masukkan block tersebut kedalam block **x-speed** yang baru saja kita buat.

![](https://farm9.staticflickr.com/8610/16470060387_5f5de97002_o_d.png)

![](https://farm9.staticflickr.com/8602/16489798318_bef8d01ab7_o_d.png)

![](https://farm9.staticflickr.com/8651/16677377075_5a1759b4e8_o_d.png)

* Terakhir adalah menambahkan logika untuk tombol kanan, dan juga pada saat tidak menekan tombol apapun. 

![](https://farm9.staticflickr.com/8585/16677176845_2b40565794_z_d.jpg)