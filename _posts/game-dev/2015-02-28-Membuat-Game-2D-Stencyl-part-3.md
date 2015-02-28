---
title: Membuat Game 2D dengan Stencyl (Space Shooter Part 3) 
subnav: blog
layout: post
type: single_post
categories: game-dev
summary: "Membuat, memasukkan Sounds dan menambahkan Background"
---
## Membuat (memasukkan) Sounds / Suara

Pada halaman **Dashboard** buka bagian **Sounds** kemudian pilih **Create New** untuk membuat sebuah suara. Berikan nama dengan **bg_music** (atau apapun nama yang anda inginkan).

![](https://farm9.staticflickr.com/8661/16671296125_ae8fe8a382_z_d.jpg)

![](https://farm9.staticflickr.com/8630/16048969174_6f02998cdd_z_d.jpg)

Langkah selanjutnya adalah memasukkan file suara yang kita inginkan, dalam assets yang telah anda unduh terdapat file **music.mp3** yang akan kita gunakan. Dikarenakan game kali ini yang akan kita buat adalah tipe **Flash** maka dianjurkan kita menggunakan suara dengan tipe **mp3**. Pilih **Import MP3** untuk mengimport, setelah file berhasil di import maka tanda centang berwarna hijau akan muncul dibawah pilihan import tadi. Anda dapat mencoba memainkan suara yang baru saja anda masukkan dengan memilih tombol play pada bagian **Sound Player** dibagian bawah sebelah kiri. Langkah terakhir adalah mengubah **Sound Type** menjadi **Music**.

`Jika pada saat melakukan import terdapat pesan peringatan **Sounds Contain Metadata** anda dapat mengubah atau menghapus metadata dari file tersebut dengan menggunakan aplikasi editor suara. Namun pada bagian ini saya biarkan tetap seperti itu`


![](https://farm9.staticflickr.com/8629/16671295695_e672c7a897_z_d.jpg)

![](https://farm9.staticflickr.com/8621/16670264512_5a39c5dc90_z_d.jpg)

![](https://farm9.staticflickr.com/8649/16463988267_c4ee76f73a_o_d.png)

![](https://farm9.staticflickr.com/8649/16463988267_c4ee76f73a_o_d.png)

![](https://farm9.staticflickr.com/8675/16051347603_6e3b9b35df_z_d.jpg)

## Membuat (Menambahkan) Background atau Gambar Latar

Pada halaman **Dashboard** buka bagian **Backgrounds** kemudian pilih **Create New** untuk membuat sebuah background. Berikan nama dengan **bg_scn** (atau apapun nama yang anda inginkan).

![](https://farm9.staticflickr.com/8586/16670364982_1ebb2435f6_z_d.jpg)

![](https://farm9.staticflickr.com/8619/16483810048_802cb4bb5a_z_d.jpg)

Lalu pada halaman **bg_scn** pilih **Click here to add a frame** untuk memilih gambar yang ingin dijadikan gambar latar.

![](https://farm9.staticflickr.com/8591/16670010981_b21522151d_z_d.jpg)

![](https://farm9.staticflickr.com/8677/16670364352_5f9ef8a0a2_z_d.jpg)

Langkah terakhir adalah dengan memberi nilai **true** atau memberikan centang pada bagian **Repeat Background** dengan tujuan untuk melakukan pengulangan pada gambar latar yang baru saja kita tambahkan agar jika nantinya **scene** yang kita buat melebihi ukuran gambar latar yang baru saja kita buat akan tetap menyesuaikan dengan ukuran **scene** tersebut (melakukan pengulangan hingga ukuran gambar sesuai dengan ukuran scene)

![](https://farm9.staticflickr.com/8578/16051452253_e17b37d7b0_z_d.jpg)

Pada bagian selanjutnya kita akan memulai membuat sebuah **Scene**, kemudian menambahkan **Background** kedalamnya beserta beberapa **Actor**