---
title: Membuat Game 2D dengan Stencyl (Space Shooter Part 4) 
subnav: blog
layout: post
type: single_post
categories: game-dev
summary: "Membuat dan mengelola Scene"
---
## Membuat dan Mengelola Scene

Pada halaman **Dashboard** buka bagian **Scene** kemudian pilih **Create New** untuk membuat sebuah scene. Berikan nama dengan **playing_scn** (atau apapun nama yang anda inginkan). Pada bagian width, height kita akan menggunakan tiles sebagai ukuran. Dan silahkan masukkan ukuran tinggi dan lebar yang anda inginkan. Begitu pula dengan warna background, anda dapat memilih sesuai dengan keinginan atau kebutuhan anda. Pada kesempatan kali ini saya akan menggunakan pengaturan yang telah ada secara otomatis.

![](https://farm9.staticflickr.com/8656/16651000316_e5bdbe637f_z_d.jpg)

![](https://farm9.staticflickr.com/8630/16489361718_c2fbbd4d19_z_d.jpg)

Langkah selanjutnya adalah memasukkan background. Kita akan membuat sebuah layer (lapisan) dengan tipe background layer. Tekan Klik kanan tetikus (mouse) pada Layer 0 disebelah kanan bawah pada bagian kolom **Layers** lalu kemudian pilih **New Background Layer**. Atau bisa juga dengan memilih tombol tambah pada bagian bawah kolom **Layers**. Setelah itu anda dapat memilih **Background** yang telah anda buat sebelumnya. Kemudian, buat agar Layer 0 tetap berada pada lapisan paling atas dengan cara klik kanan tetikus (mouse) pada layer background yang baru saja kita tambahkan kemudian pilih **Send Layer Back**.

![](https://farm9.staticflickr.com/8627/16489529190_4f049901f4_z_d.jpg)

![](https://farm9.staticflickr.com/8598/16651000076_e0e127a7ff_z_d.jpg)

![](https://farm9.staticflickr.com/8567/16057006763_1b8344733c_o_d.png)

Selanjutnya kita akan memasukkan beberapa **Actor** kedalam **Scene** yang baru saja kita buat. Terdapat sebuah kolom di atas kolom **Tiles** | **Actor**, buka kolom **Actor** dan anda akan menemukan **Actor** yang telah anda buat sebelumnya. Kemudian Pilih **Player** lalu tempatkan didalam **Scene** pada bagian bawah. Begitu pula dengan **Enemies** namun tempatkan pada bagian atas.

![](https://farm9.staticflickr.com/8655/16489388418_605f93c58b_z_d.jpg)

![](https://farm9.staticflickr.com/8602/16489555820_0664d87161_z_d.jpg)

![](https://farm9.staticflickr.com/8589/16676965495_a6a86d8496_z_d.jpg)

Sekarang mari kita lakukan uji coba pada **Scene** yang baru saja kita buat dengan cara memilih **Test Game** pada bagian atas sebelah kanan dan memilih Flash (Player)

![](https://farm9.staticflickr.com/8633/16489555550_deae9fa496_o_d.png)

![](https://farm9.staticflickr.com/8587/16054638244_9fec201274_z_d.jpg)

Pada bagian selanjutnya kita akan memulai membuat agar si **Player** bisa bergerak kiri kanan, dan menembakkan sebuah Laser.