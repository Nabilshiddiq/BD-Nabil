# Select lanjutan
Menetapkan kritering data yang ingin di cari pada tabel " mobil"
AND,OR,BETWEEN,NOT BETWEEN <=,>=

## AND
 Semua kriteria wajib/harus terpenuhi kodenya sbg berikut:
 MariaDB [rental_Nabil]> select warna,pemilik from mobil where warna= "hitam" And pemilik="ibrahim" ;
  **Hasil**. :
![[IMG-20240220-WA0026 1.jpg]]


## OR
semua atau salah satu kriteria terpenuhi kode sbg berikut:
MariaDB [rental_Nabil]> select warna,pemilik from mobil where warna="hitam" OR pemilik="ibrahim";

**Hasil** :
![[IMG-20240220-WA0027 1.jpg]]


## Between
Akan mengambil data antara "data 1" dan "data 2" dibantu dengan AND, kodenya ialah : 
* Select * from mobil where harga_rental BETWEEN 100000 AND 200000;

Hasil:
![[IMG-20240220-WA0030 1.jpg]]


## Not Between

## In

![[IMG-20240227-WA0356.jpg]]
