---
title: Cara Memasang Instant Click Di Jekyll
subtitle: Pengalaman menggunakan ssg
date: '2020-11-25'
thumb_img_path: images/pexels-george-becker-374918_ggutup.jpg
content_img_path: images/pexels-george-becker-374918_ggutup.jpg
excerpt: >-
 Pengalaman menggunakan ssg seperti jekyll dan hugo membuat banyak pelajaran yang saya dapat, sebelumnya di wordpress sangat malas sekali buat yang namanya mengedit kode, semuanya dimanjakan dengan namanya plugin, yah apa yang kalian butuhkan ada plugin-nya
template: post
---
Pengalaman menggunakan ssg seperti jekyll dan hugo membuat banyak pelajaran yang saya dapat, sebelumnya di wordpress sangat malas sekali buat yang namanya mengedit kode, semuanya dimanjakan dengan namanya plugin, yah apa yang kalian butuhkan ada plugin-nya.

Dari yang simple sampai yang rumit semua tersedia, gratis sampai berbayar pun tersedia banyak, setelah menggunakan blog static untuk blog pribadi akhirnya mulai menjelajahi beberap baris kode yang sudah lama tidak menemuinya.

Sebelumnya telah memasang instant click pada blog wordpress hanya dengan mencentang yes di plugin litespeed, mencoba untuk menerapkan di jekyll butuh beberapa sentuhan.

Pertama melihat sumber kode di blog wordpress darimana sumber kode tersebut setelah mencari akhirnya menemukan website instantclick.io dan mencoba menerapkannya di jekyll.

Caranya cukup mudah kalian bisa mendownload lansung kode javascript instantclick di websitenya langsung [disini](http://instantclick.io/v3.1.0/instantclick.min.js "instant cick") lalu memasang seperti ini.

    ...
    <script src="instantclick.min.js" data-no-instant></script>
    <script data-no-instant>InstantClick.init();</script>
    </body>
    </html>

Selanjutnya masuk di repository github kalian yang menhost github page, upload di folder asset kalian, biasanya di folder assets/js upload kode instantclick  disana.

Selanjutnya memesang kode instantclick di bagian default.html, biasanya terdapat pada folder _layouts/default.html masang di bagian footer sebelum </body>.

Cara kedua dengan memasang dari script library external seperti cdnjs.

    <script src="https://cdnjs.cloudflare.com/ajax/libs/instantclick/3.1.0/instantclick.min.js" integrity="sha512-K0LA7hRSqNt0GOikeLRmpKEecaOy7uizFEA/b3SMMyGycCy1qRLoezkVbuXQUFVq6pwEjCszMCn3TT4dRRie+g==" crossorigin="anonymous"></script>

Sama taroh di bagian footer, selamat mencoba :)