---
layout: post
author: Wildan Fauzy
date: 2020-11-28 14:36:00 +0700
title: 'Mencoba Tema Jekflix '
subtitle: 'Tema jekflix tampilan terinspirasi netflix '
description: Tema jekyll satu ini memang menarik dan menawan di tampilan mobile atau
  desktop sangat resposive dan menerapkan struktur tema yang adaptif sesuau gadget
  yang digunakan, namanya jekflix mirip netflix
image: assets/images/theme17_nlndhx_oibw2z.jpg
optimized_image: https://res.cloudinary.com/nadliw45/image/upload/c_scale,w_380/c_scale,w_380/v1606485056/theme17_nlndhx_oibw2z.jpg
category: jekyll
tags:
- jekflix
title: 
subtitle: 
date: '2020-11-00'
thumb_img_path: images/
content_img_path: images/
excerpt: >-
 sub.
template: post
---
Kerjaan hanya scroll timeline twitter tanpa ada perbincangan hanya silent rider, hubungan juga semakin rumit, menuju jalan kehampaan.

Lalu membuka email, sangat jarang sekali mengecek email, memang alamat surel gmail sudah tercemari.

Makanya membuat email khusus pribadi dan email publik menggunakan gmail, untuk melakukan aktifitas atau transaksi di internet.

Alhasil isi pesan email hanya penawaran promo dan iklan, malas rasanya menghapus satu-satu.

Akhirnya mengecek pesan masuk satu per satu, melihat folder spam, lalu ada email dari github tentang daily digist explore.

Langsung mengklik menuju tan explore ada beberapa repositori yang mungkin kalian suka dan juga berdasarkan minat atau topik yang sering dicari.

Menemukan salah satu repository milik thiago rossener, menemukan tema jekyll baru bernama jekflix, membaca readme. md dan melihat demo website sepertinya tertarik.

Langsung saja mengfork repositori milik rossener, membaca panduan cara instalasi, ada dua pilihan bisa menggunakan repo secara private atau publik.

![](https://res.cloudinary.com/nadliw45/image/upload/v1606550351/jekflix-capa_vfhuzh_ij4ab2.png)Jika ingin private, ada pilihan use template di repo jekflix, dan mendeploy dengan netlify starter secara gratis dengan limit 300 menit built, lumayan pertama kali deploy satu menit selanjutnya hanya membutuhkan 26 detik.

Memang tidak secepat build time dengan hugo, tapi tidak separah yang menggunakan framework javascript hehe, lama bet walaupun beberapa menit tapi build time segini lama.

Cara kedua dengan mengfork repositori jekflix dan mendeploy dengan github pages, cara ini paling mudah, setelah mengfork lalu clone repositori mengedit configurasi yang dibutuhkan lalu membuat brach baru dengan git checkout - b.

Tapi ada salah satu fitur yang tidak bisa digunakan yaitu netlifycms dimana membutuhkan identity, tidak apa-apa masih ada cms seperti forestry.io atau cara tradisional dengan git push setiap kali menerbitkan tulisan.

Sudah disediakan script initpost.sh menggenerate font matter post otomatis tinggal menulis dengan editor kesukaan.

Tema ini membutuhkan gulp, jika hendak mendeploy dengan netlify gunakan build comman gulp build tidak perli dengan jekyll build, agar bisa menggunakan fitur yang sudah tersedia di tema ini.

silakan kunjungi repositori jekflix template milik thiago rossener [disini](https://github.com/thiagorossener/jekflix-template "jekflix themes")