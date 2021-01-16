---
layout: post
author: Wildan Fauzy
categories:
- javascript
- jekyll
title: Cara Memasang Instant Click Di Jekyll
image: assets/images/pexels-george-becker-374918_ggutup.jpg
date: 2020-11-25T23:14:00.000+07:00
category: jekyll
subtitle: " menggunakan ssg seperti jekyll dan hugo membuat banyak pelajaran"
description: sumber kode tersebut setelah mencari akhirnya menemukan website instantclick.io
  dan mencoba menerapkannya di jekyll.
optimized_image: https://res.cloudinary.com/nadliw45/image/upload/c_scale,w_380/v1606486223/pexels-george-becker-374918_ggutup.jpg
title: 
subtitle: 
date: '2020-11-00'
thumb_img_path: images/
content_img_path: images/
excerpt: >-
 sub.
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