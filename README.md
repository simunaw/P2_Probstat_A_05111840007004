## P2_Probstat_A_05111840007004

# No 1

## a) Standar Deviasi

x = c (78,75,67,77,70,72,78,74,77)

y = c (100,95,70,90,90,90,89,90,100)

selisih = y-x

data <- data.frame(x,y1)

## a) Standart Defiasi

varian = var(selisih)

sd = sqrt(varian)

sd

![Getting Started](https://user-images.githubusercontent.com/58022238/170868044-0d8fb33f-dca1-4e4b-801f-dd98095a81e7.png)


## b) Nilai t (p-value)

t = t.test (x, y)

t

![image](https://user-images.githubusercontent.com/58022238/170868173-ccbed65c-ed25-45e2-94ad-4d0530860c96.png)


## c) pengaruh

 Hipotesis
 
H0 : “tidak ada pengaruh yang signifikan secara statistika dalam hal kadar saturasioksigen , sebelum dan sesudah melakukan aktivitas 𝐴”

H1 : “Ada pengaruh yang signifikan secara statistika dalam hal kadar saturasioksigen , sebelum dan sesudah melakukan aktivitas 𝐴”

dengan menggunakan alfa 5% didapatkan bahwa tolak H0 karena nilai alpha>p-value dapat disimpulkan bahwa tidak ada pengaruh 


# No 2

## a) Iya setuju

## b) maksud output yang dihasilkan

![image](https://user-images.githubusercontent.com/58022238/170868631-b646c4c0-4755-4a29-914d-44c691b60023.png)

#output diatas didapatkan nilai z = 60.256 dan p-value <= alpha (5%). dan selang kepercayaan berada pada 22858 sampai tak hingga.

## c) Kesimpulan

kesimpulan berdasarkan P-Value yang dihasilkan

H0 : "rata-rata jarak tempuh mobil <= 20000 kilometer.

# N0 3

## a) H0 dan H1

Hipotesis 

H0 : Tidak ada perbedaan rata-rata saham antara kota Bandung dan Bali

H1 : Ada perbedaan rata-rata saham antara kota Bandung dan Bali

## b) Hitung Sample Statistik

tsum.test (

  mean.x = 3.64,
  
  s.x = 1.67,
  
  n.x = 19,
  
  alternative = "greater"
  
  var.equal = TRUE
  
  )
  
![image](https://user-images.githubusercontent.com/58022238/170878857-d8899622-1de3-4a56-8157-f438f3f8f75c.png)

## c) Uji Statistik

plotDist(dist='t', df=2, col="blue")

![image](https://user-images.githubusercontent.com/58022238/170879787-0d1c9a1e-7871-4e0d-a950-5f9b5bc2f4aa.png)

## d) Nilai Kritikan 

## e) Keputusan

Didapatkan nilai p-value<= alpha (5%)

## f) Kesimpulan 

Adanya perbedaan rata-rata dari perhitungan saham antara Bandung dan Bali

# No 4

## a) Membuat jenis spesies

## b) Nilai p yang didapatkan

## c) Model Linier

## d) Nilai p dan kesimpulan

## e) Verifikasi

## f) Visualisasikan

# No 5

## a) Membuat Plot

Read.csv("direktori")
read.csv("GTL.csv")
head(GTL)



