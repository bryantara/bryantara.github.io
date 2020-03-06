---
layout: post
title: Dasar-Dasar Pemrograman R
categories: data
city: Depok
---

Setelah selesai [menginstal RStudio](https://bryantara.com/instalasi-r-windows/), mari kita mengenal bagian-bagian dari alat yang akan kita pergunakan ini. 

![Kuadran RStudio](https://raw.githubusercontent.com/bryantara/bryantara.github.io/master/images/kuadran-r.jpg)

### Tampilan RStudio

RStudio memiliki beberapa _quadrant_ (kuadran). Secara umum, tampilannya seperti gambar di atas. Namun, isinya bisa kita ganti dengan cara mengeklik _View - Panes - Pane Layout_. 

Pembagian kuadran tersebut adalah sebagai berikut:
- Q1: berisi skrip kode, data, juga perintah untuk menjalankan kode
- Q2: berisi environment, history, dan connection
- Q3: berisi console, terminal, job
- Q4: berisi file, package, help, dan lain-lain

Sebagai awalan, tidak perlu memusingkan istilah-istilah di atas. Jika sering berlatih, pasti akan paham dengan sendirinya.

### Perintah Sederhana di RStudio

Mari kita memulai menjalankan perintah sederhana di RStudio. Kita akan melakukannya di kuadran 3. Pada baris paling bawah, kita akan menjumpai tanda > (kurang dari). Baris ini disebut dengan _command line_ atau baris perintah, sedangkan kode yang kita tulis pada baris perintah ini disebut dengan _command_ atau perintah.

Misal, kita mengetik perintah 2+3 pada baris perintah di kuadaran 3. Maka akan muncul sebagai berikut:

```
> 2+3
[1] 5
```
Mungkin ada yang bertanya mengapa ada [1] sebelum hasil penjumlahan angka 3. Tanda tersebut menunjukkan nilai pertama dari hasil perintah yang kita buat. Contoh lain, misal kita mengetik 50:100 untuk menghasilkan deretan bilangan bulat dari 50 sampai 100.

```
> 50:100
 [1]  50  51  52  53  54  55  56  57  58  59  60  61  62  63  64  65  66  67  68
[20]  69  70  71  72  73  74  75  76  77  78  79  80  81  82  83  84  85  86  87
[39]  88  89  90  91  92  93  94  95  96  97  98  99 100
```

Perintah di atas menghasilkan 51 nilai yang terbagi dalam tiga baris, dengan 
- nilai pertama [1] adalah 50
- nilai kedua puluh [20] adalah 69
- nilai ketiga puluh sembilan [39] adalah 88. 

Itulah fungsi dari angka-angka di dalam tanda kurung siku tersebut.



Referensi: [BasicBasics 1](https://rladiessydney.org/courses/ryouwithme/01-basicbasics-1/), [2 The Very Basics](https://rstudio-education.github.io/hopr/basics.html), [R for Beginners](https://cran.r-project.org/doc/contrib/Paradis-rdebuts_en.pdf)
