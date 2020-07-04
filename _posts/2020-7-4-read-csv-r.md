---
layout: post
title: Impor CSV di R Menggunakan read_csv
categories: data
city: Depok
---
Jika kita mengambil kelas [pemrograman R](https://www.coursera.org/learn/r-programming) di Coursera, pasti akan menjumpai fungsi read_csv untuk mengimpor file _comma-separated values_ (CSV). Fungsi tersebut berbeda dengan read.csv (perhatikan perbedaan tanda _ dan .) yang biasanya sudah tersedia di R. Kelebihan read_csv dibanding read.csv diantaranya dapat memuat file lebih cepat, dapat menjadikan kolom sebagai _lists_ , dll ([lihat selengkapnya](https://medium.com/r-tutorials/r-functions-daily-read-csv-3c418c25cba4)).

read_csv merupakan bagian dari paket readr yang merupakan bagian dari tidyverse, jadi untuk memakainya kita panggil _library_ tidyverse terlebih dahulu di _console_ R menggunakan:.

  library(tidyverse)

Jika sudah, read_csv siap digunakan. Berbagai contoh penggunaannya ada di [link ini](https://r4ds.had.co.nz/data-import.html).



