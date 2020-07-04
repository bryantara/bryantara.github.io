---
layout: post
title: Impor CSV di R Menggunakan read_csv
categories: data
city: Depok
---
Jika kita mengambil kelas [pemrograman R](https://www.coursera.org/learn/r-programming) di Coursera, pasti akan menjumpai fungsi `read_csv` untuk mengimpor file _comma-separated values_ (CSV). Fungsi tersebut berbeda dengan `read.csv` yang biasanya sudah tersedia di R (perhatikan perbedaan antara tanda _ dan .). 

Kelebihan `read_csv` dibanding `read.csv` diantaranya dapat memuat file lebih cepat, dapat menjadikan kolom sebagai _lists_ , [dan sebagainya](https://medium.com/r-tutorials/r-functions-daily-read-csv-3c418c25cba4).

`read_csv` merupakan bagian dari paket `readr` yang merupakan bagian dari `tidyverse`, jika belum memasang paket `tidyverse`, install terlebih dahulu dengan:

`install.packages("tidyverse")`

Setelah `tidyverse` terpasang, panggil _library_ `readr` untuk dijalankan di sesi ini:

  `library(readr)`

Jika sudah, `read_csv` siap digunakan. 

Berbagai contoh penggunaannya ada di [link ini](https://r4ds.had.co.nz/data-import.html).
