---
layout: post
title: Impor Data dari SAS, SPSS, atau Stata ke R
categories: data
city: Depok
---
Buat teman-teman yang ingin mengimpor data dari format SAS, SPSS, atau Stata ke R, dapat dilakukan secara mudah menggunakan _packages_ haven. Cukup ketikkan perintah: 

`install.packages("haven")`

Setelah haven terinstal, tinggal panggil library haven,

`library(haven)`

kemudian ketikkkan format sesuai data apa yang ingin diimpor. Misal:

`
read_sas("namafile.sas7bdat")

read_sav("namafile.sav")

read_dta("namafile.dta")
`

Mudah, kan?

`Referensi: https://haven.tidyverse.org/ diakses pada 3 Oktober 2021`
