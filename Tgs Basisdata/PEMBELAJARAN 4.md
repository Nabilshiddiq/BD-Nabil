# SELECT LANJUTAN 
## AND 
select AND ini akan menampilkan data dengan  "nilai1" dan "nilai2".
STRUKTUR:
```MYSQL
select [nama_kolom],[nama_kolom] FROM [nama_tabel] WHERE [nama_kolom]=["nama_data"] AND [nama_kolom]=["nama_data"];
```
CONTOH:
```MYSQL
 select warna,pemilik FROM mobil WHERE warna="hitam" AND pemilik="ibrahim";
```

HASIL:
![GAMBAR](GAMBARBASDAT/and.png)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **WARNA** adalah sebuah nama kolom pada tabel mobil.
- **PEMILIK** adalah sebuah nama kolom juga pada tabel mobil.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **hitam** adalah nama data pada sebuah kolom
- **AND** adalah sebuah perintah query DAN menujukkan bahwa pemilihan data nya lebih dari 1.
- **ibrahim** adalah nama data pada sebuah kolom

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom warna dengan data "hitam" dan kolom pemilik dengan data "ibrahim"


## OR 
select OR ini akan menampilkan data dengan  "nilai1"  atau "nilai2".

```mysql
select [nama_kolom],[nama_kolom] FROM [nama_tabel] WHERE [nama_kolom]=["nama_data"] OR [nama_kolom]=["nama_data"];
```
CONTOH:
```MYSQL
 select warna,pemilik FROM mobil WHERE warna="hitam" OR pemilik="ibrahim";
```

HASIL:
![GAMBAR](GAMBARBASDAT/OR.PNG)
ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **WARNA** adalah sebuah nama kolom pada tabel mobil.
- **PEMILIK** adalah sebuah nama kolom juga pada tabel mobil.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **hitam** adalah nama data pada sebuah kolom
- **OR** adalah sebuah perintah query ATAU menujukkan bahwa pemilihan data yang ditampilkan adalah salah satu dari syarat yang  ditentukan.
- **ibrahim** adalah nama data pada sebuah kolom

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom warna dengan data "hitam" atau kolom pemilik dengan data "ibrahim" jadi hanya data hitam dan ibrahim lah yang akan tampil.

##  BETWEEN- AND
select between-and ini akan menampilkan data antara "nilai1" dan "nilai2".karena didukung dengan AND.

```mysql
 select * FROM [nama_tabel] WHERE [nama_kolom] BETWEEN [nilai_data1] AND [nilai_data2];
```
CONTOH:
```MySQL
 select * FROM mobil WHERE harga_rental BETWEEN 100000 AND 200000;
```

HASIL:
![GAMBAR](GAMBARBASDAT/BETWEENAND.png)

KESIMPULAN:

- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **MOBIL** adalah sebuah nama tabel.
- **BETWEEN** adalah sebuah perintah query ANTARA menujukkan bahwa pemilihan data yang ditampilkan adalah DI ANTARA salah satu data  dari syarat yang  ditentukan.
- **AND** adalah sebuah perintah query DAN menujukkan bahwa pemilihan data nya lebih dari 1.
- **harga_rental** adalah sebuah nama kolom.
- **100000** adalah nama data pada sebuah kolom.
- **200000** adalah nama data pada sebuah kolom.

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom *harga rental* dengan data antara "100000" dan  data "200000"  jadi hanya data dengan jumlah **100000** sampai dengan **200000** yang akan tampil.

## NOT BETWEEN 
untuk NOT BETWEEN ini akan menampilkan  yang bukan antara "nilai1" dan "nilai2".
STRUKTUR:
```MYSQL
SELECT * FROM [nama_tabel] WHERE [nama_kolom] NOT BETWEEN [nama_data] AND [nama_data];
```
CONTOH:
```MYSQL
SELECT * FROM mobil WHERE harga_rental NOT BETWEEN 100000 AND 200000;
```

HASIL:
![gambar](GAMBARBASDAT/notbetween.png)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **MOBIL** adalah sebuah nama tabel.
- **NOT BETWEEN** adalah sebuah perintah query ANTARA menujukkan bahwa pemilihan data yang ditampilkan adalah  TIDAK DI ANTARA salah satu data  dari syarat yang  ditentukan.
- **AND** adalah sebuah perintah query DAN menujukkan bahwa pemilihan data nya lebih dari 1.
- **harga_rental** adalah sebuah nama kolom.
- **100000** adalah nama data pada sebuah kolom.
- **200000** adalah nama data pada sebuah kolom.

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom *harga rental* dengan data tidak di antara "100000" dan  data "200000"  jadi hanya data  dengan jumlah **100000** sampai dengan **200000** yang tidak akan tampil.


## <= 
untuk **<=** ini akan menampilkan **"data"** yang lebih kecil atau sama dengan **"nilai_data** yang telah ditentukan.

STRUKTUR:
```MYSQL
SELECT * FROM [nama_tabel] WHERE [nama_kolom] <= [nama_data];
```
CONTOH:
```mysql 
SELECT * FROM mobil WHERE harga_rental <= 50000;
```

HASIL:
![gambar](GAMBARBASDAT/kecilsama.png)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **MOBIL** adalah sebuah nama tabel.
- **harga_rental** adalah sebuah nama kolom.
- **500000** adalah nama data pada sebuah kolom.
- **<=** adalah perintah query yang betugas menentukan syarat *kurang dari atau sama dengan*.

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom *harga rental* dengan data *KURANG DARI ATAU SAMA DENGAN*  **500000**  jadi hanya data  dengan jumlah kurang dari 500000 atau setara dengan 500000 yang akan ditampilkan.

## >= 
untuk **>=** ini akan menampilkan **"data"** yang lebih besar atau sama dengan **"nilai_data** yang telah ditentukan.

STRUKTUR:
```MYSQL
SELECT * FROM [nama_tabel] WHERE [nama_kolom] >= [nama_data];
```
CONTOH:
```mysql
SELECT * FROM mobil WHERE harga_rental >= 50000;
```

HASIL:
![gambar](GAMBARBASDAT/besarsama.png)
ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **MOBIL** adalah sebuah nama tabel.
- **harga_rental** adalah sebuah nama kolom.
- **500000** adalah nama data pada sebuah kolom.
- **>=** adalah perintah query yang betugas menentukan syarat *lebih dari atau sama dengan*.

KESIMPULAN:
query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom *harga rental* dengan data *LEBIH DARI ATAU SAMA DENGAN*  **500000**  jadi hanya data  dengan jumlah lebih dari 50000 atau setara dengan 500000 yang akan ditampilkan.

## <> atau != 
untuk **<>atau !=** ini akan menampilkan **"data"** yang tidak  sama dengan **"nilai_data** yang telah ditentukan.
STRUKTUR:
```MYSQL
SELECT * FROM [nama_tabel] WHERE [nama_kolom] <> [nama_data];
```
CONTOH:
```mysql
SELECT * FROM mobil WHERE harga_rental <> 50000;
```

HASIL:
![gambar](GAMBARBASDAT/tidaksama.png)
ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **MOBIL** adalah sebuah nama tabel.
- **harga_rental** adalah sebuah nama kolom.
- **500000** adalah nama data pada sebuah kolom.
- **<>** adalah perintah query yang betugas menentukan syarat *kurang dari atau lebih dari *.

KESIMPULAN: query diatas adalah perintah untuk menampilkan sebuah data dari tabel mobil yang bertujukan pada kolom *harga rental* dengan data *LEBIH DARI ATAU  KURANG DARI  **500000**  jadi hanya data  dengan jumlah lebih dari 50000 atau kurang dari  500000 yang akan ditampilkan (selain dari nilai 500000 yang akan ditampilkan).

## Tantangan
Untuk tantangan saya akan mengambil nama pemilik "baim" dengan cara memanggilnya dengan syarat nomor pelatnya yaitu "B 1611 QC" lalu hasilnya akan seperti berikut :
![GAMBAR](GAMBARBASDAT/tantangan.png)

## IN 

STRUKTUR:
```MYSQL 
 select * from nama_tabel where nama_kolom in ("nama_data","nama_data");
```

CONTOH:
```MYSQL 
 select * from data_mobil where warna in ("silver","merah");
```

HASIL:
![GAMBAR](GAMBARBASDAT/IN.PNG)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WARNA** adalah sebuah nama kolom.
- **SILVER DAN MERAH** adalah nama data pada sebuah kolom.
- **IN** adalah perintah query yang betugas menentukan seluruh data yang sesuai dengan kondisi ditentukan, menghindari penulisan berulang query dengan kondisi yang sama.

KESIMPULAN: query diatas adalah perintah untuk menampilkan sebuah data dari tabel  data mobil yang bertujukan pada kolom *warna* dengan data yang hanya **silver dan merah**  jadi hanya data silver dan merah yang akan ditampilkan (tanpa menggunaka query dengan kondisi yang sama).

## IN+AND

STRUKTUR:
```MYSQL
 select * from data_mobil
    -> where nama_kolom IN ("nama_data","nama_data")
    -> AND nama_kolom = nama_data;
```

CONTOH:
```mySQL
	select * from data_mobil
    -> where warna IN ("hitam","silver")
    -> AND harga_rental = 50000;
```

HASIL:
![GAMBAR](GAMBARBASDAT/INAND.PNG)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WARNA** adalah sebuah nama kolom.
- **HITAM DAN SILVER** adalah nama data pada sebuah kolom.
- **IN** adalah perintah query yang betugas menentukan seluruh data yang sesuai dengan kondisi ditentukan, menghindari penulisan berulang query dengan kondisi yang sama.
- **AND** adalah sebuah perintah query DAN menujukkan bahwa pemilihan data nya lebih dari 1
- **HARGA_RENTAL** adalah sebuah nama kolom.
- **50000** adalah nama data pada sebuah kolom.

KESIMPULAN:query di atas adalah perintah untuk menampilkan sebuah data yang berkondisikan data warna hitam,silver dan memiliki harga rental 50000.

## IN+OR

STRUKTUR:
```MYSQL
 select * from data_mobil
    -> where nama_kolom IN ("nama_data","nama_data")
    -> OR nama_kolom = nama_data;
```

CONTOH:
```mySQL
	select * from data_mobil
    -> where warna IN ("hitam","silver")
    -> OR harga_rental = 50000;
```

HASIL:
![GAMBAR](GAMBARBASDAT/INOR.PNG)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WARNA** adalah sebuah nama kolom.
- **HITAM DAN SILVER** adalah nama data pada sebuah kolom.
- **IN** adalah perintah query yang betugas menentukan seluruh data yang sesuai dengan kondisi ditentukan, menghindari penulisan berulang query dengan kondisi yang sama.
- **OR** adalah sebuah perintah query ATAU menujukkan bahwa pemilihan dari salah satu data 
- **HARGA_RENTAL** adalah sebuah nama kolom.
- **50000** adalah nama data pada sebuah kolom.

KESIMPULAN:query di atas adalah perintah untuk menampilkan sebuah data yang berkondisikan data warna hitam,silver atau yang memiliki harga rental 50000.

## IN+AND+OPERATOR 

STRUKTUR:
```MYSQL
 select * from nama_tabel
    -> where nama_kolom in ("nama_data","nama_data")
    -> and nama_kolom > nama_data;
    ```

```mysqL
 select * from nama_tabel
    -> where nama_kolom in ("nama_data","nama_data")
    -> and nama_kolom < nama_data;
```

CONTOH:
```mySQL
select * from data_mobil
    -> where  warna in ("hitam","silver")
    -> and harga_rental > 50000;
```

```MYSQL
select * from data_mobil
    -> where  warna in ("hitam","silver")
    -> and harga_rental < 100000;
```

HASIL:
![GAMBAR](GAMBARBASDAT/INOPERATOR.PNG)

ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WARNA** adalah sebuah nama kolom.
- **HITAM DAN SILVER** adalah nama data pada sebuah kolom.
- **IN** adalah perintah query yang betugas menentukan seluruh data yang sesuai dengan kondisi ditentukan, menghindari penulisan berulang query dengan kondisi yang sama.
- **DAN** adalah sebuah perintah query DAN menujukkan bahwa kondisi yang ditentukan lebih dari 1 
- **HARGA_RENTAL** adalah sebuah nama kolom.
- **>** adalah peritah lebih dari data yang ditentukan.
- **<** adalah perintah kurang dari data yang ditentukan
- **50000** adalah nama data pada sebuah kolom.
- **100000** adalah nama data pada sebuah kolom.

KESIMPULAN:
1. query pertama di atas adalah perintah untuk menampilkan  kondisi dengan data warna hitam,silver dan yang memiliki harga rental lebih dari 50000.
2. query kedua diatas adalah perintah untuk menampikan kondisi dengan data warna hitam,silver dan yang memiliki harga rental kurang dari 100000.

## LIKE 

1. MENCARI AWALAN
STRUKTUR:
```MYSQL 
 select * from nama_tabel
    -> where nama_kolom like 'nama_pola';
```
CONTOH:
```MYSQL
 select * from data_mobil
    -> where pemilik like 'ib%';
```
HASIL:
![GAMBAR](GAMBARBASDAT/LIKEAWAL.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMILIK** adalah sebuah nama kolom.
- **LIKE** adalah perintah query yang betugas menentukan hasil berdasarkan pola teks tertentu.
- **IB%** adalah sebuah pola awalan tertentu yang ingin ditampilkan.
KESIMPULAN: query diatas adalah perintah untuk menampilkan data pada kolom pemilik yang berpola ib% artinya data dengan awalan ib pada kolom pemilik yang akan ditampilkan.

2.  MENCARI AKHIRAN 
STRUKTUR:
```MYSQL 
 select * from nama_tabel
    -> where nama_kolom like 'nama_pola';
```
CONTOH:
```MYSQL
 select * from data_mobil
    -> where pemilik like '%M';
```
HASIL:
![GAMBAR](GAMBARBASDAT/LIKEAKHIR.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMILIK** adalah sebuah nama kolom.
- **LIKE** adalah perintah query yang betugas menentukan hasil berdasarkan pola teks tertentu.
- **%M** adalah sebuah pola akhiran tertentu yang ingin ditampilkan.
KESIMPULAN: query diatas adalah perintah untuk menampilkan data pada kolom pemilik yang berpola %m artinya data dengan akhiran M pada kolom pemilik yang akan ditampilkan.

3. MENCARI AWALAN DAN AKHIRAN
STRUKTUR:
```MYSQL 
 select * from nama_tabel
    -> where nama_kolom like 'nama_pola';
```
CONTOH:
```MYSQL
 select * from data_mobil
    -> where pemilik like 'B%M';
```
HASIL:
![GAMBAR](GAMBARBASDAT/LIKEAWALAKHIR.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMILIK** adalah sebuah nama kolom.
- **LIKE** adalah perintah query yang betugas menentukan hasil berdasarkan pola teks tertentu.
- **B%M** adalah sebuah pola awalan dan akhiran tertentu yang ingin ditampilkan.
KESIMPULAN: query diatas adalah perintah untuk menampilkan data pada kolom pemilik yang berpola b%m artinya data dengan awalan B dan akhiran M pada kolom pemilik yang akan ditampilkan.

4. MENCARI BERDASARKAN TOTAL KARAKTER
STRUKTUR:
```MYSQL
select * from nama_tabel
    -> where nama_kolom like 'nama_pola';
```
CONTOH:
```MYSQL
select * from data_mobil
    -> where pemilik like 'i__';
```
HASIL:
![GAMBAR](GAMBARBASDAT/LIKEKARAKTER.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMILIK** adalah sebuah nama kolom.
- **LIKE** adalah perintah query yang betugas menentukan hasil berdasarkan pola teks tertentu.
- **'I__'** adalah pola karakter tertentu yang ingin ditampilkan.
KESIMPULAN:
query adalah perintah untuk menampilkan data pada kolom pemilik yang berawalan i dan memiliki 2 karakter yang lainnya(hanya menampilkan nama pemilik dengan 3 kata dan berawalan i).

5. KOMBINASI 
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL
-> WHERE NAMA_KOLOM LIKE 'NAMA_POLA';
```
CONTOH:
```MYSQL
SELECT * FROM DATA_MOBIL
-> WHERE PEMILIK LIKE '__R%';
```
HASIL:
![GAMBAR](GAMBARBASDAT/LIKEKOMBINASI.PNG)
ANALISIS:
- **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMILIK** adalah sebuah nama kolom.
- **LIKE** adalah perintah query yang betugas menentukan hasil berdasarkan pola teks tertentu.
- **'__R%'** adalah pola karakter tertentu dari salah satu data yang ingin ditampilkan.
KESIMPULAN:
query adalah perintah untuk menampilkan data pada kolom pemilik yang  huruf ketiganya adalah R  .

6. NOT LIKE
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL WHERE NAMA_KOLOM NOT LIKE 'NAMA_POLA'
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL WHERE PEMINJAM NOT LIKE 'A%';
```
HASIL:
![GAMBAR](GAMBARBASDAT/NOTLIKE.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **NOT LIKE** adalah perintah query yang betugas menentukan hasil yang tidak sesuai berdasarkan pola teks tertentu.
- **'A%'** adalah pola yang tidak boleh ditampilkan.
KESIMPULAN:
query adalah perintah untuk menampilkan data pada kolom peminjam yang tidak memiliki huruf A pada datanya.

## NULL & NOT NULL
1. MENCARI DATA KOSONG 
STRUKTUR:
```MYSQL
 SELECT * FROM NAMA_TABEL WHERE NAMA_KOLOM IS NOT NULL;
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL WHERE PEMINJAM IS NOT NULL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/NULL.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **IS  NULL** adalah perintah query yang betugas menampilkan suatu kolom yang  memiliki  data.
KESIMPULAN:
query adalah perintah untuk menampilkan tabel yang pada kolom peminjamnya tidak memiliki data atau NULL.

2. NOT NULL 
STRUKTUR:
```MYSQL
 SELECT * FROM NAMA_TABEL WHERE NAMA_KOLOM IS NOT NULL;
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL WHERE PEMINJAM IS NOT NULL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/NOTNULL.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **IS NOT NULL** adalah perintah query yang betugas menampilkan suatu kolom yang  memiliki nilai .
KESIMPULAN:
query adalah perintah untuk menampilkan tabel yang pada kolom peminjamnya 
terdapat sebuah data atau NOT NULL.

## ORDER BY LIMIT

1. ASC
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL ORDER BY NAMA_KOLOM ASC;
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL ORDER BY PEMILIK ASC;
```
HASIL:
![GAMBAR](GAMBARBASDAT/ASC.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **ORDER BY** adalah sebuah perintah query yang  untuk mengurutkan pemanggilan berdasarkan nilai.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **ASC** adalah perintah query yang betugas menampilkan suatu data secara berurutan ke atas.
KESIMPULAN:
query adalah perintah untuk menampilkan tabel dengan data pada kolom peminjam sesuai dengan alfabet dari A-Z.

2. DESC
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL ORDER BY NAMA_KOLOM DESC;
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL ORDER BY PEMILIK DESC;
```
HASIL:
![GAMBAR](GAMBARBASDAT/DESC.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **ORDER BY** adalah sebuah perintah query yang  untuk mengurutkan pemanggilan berdasarkan nilai.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **DESC** adalah perintah query yang betugas menampilkan suatu data secara berurutan ke bawah .
KESIMPULAN:
query di atas adalah perintah untuk menampilkan tabel dengan data pada kolom peminjam sesuai dengan alfabet dari Z-A.

3. LIMIT 
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL ORDER BY NAMA_KOLOM ASC;
```
CONTOH:
```MYSQL
 SELECT * FROM DATA_MOBIL ORDER BY PEMILIK ASC;
```
HASIL:
![GAMBAR](GAMBARBASDAT/ASC.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **ORDER BY** adalah sebuah perintah query yang  untuk mengurutkan pemanggilan berdasarkan nilai.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **PEMINJAM** adalah sebuah nama kolom.
- **ASC** adalah perintah query yang betugas menampilkan suatu data secara berurutan ke atas.
KESIMPULAN:
query adalah perintah untuk menampilkan tabel dengan data pada kolom peminjam sesuai dengan alfabet dari A-Z.

3. LIMIT 
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL WHERE NAMA_KOLOM="NAMA_DATA" ORDER BY NAMA_KOLOM ASC LIMIT 2;
```

CONTOH:
```MYSQL

SELECT * FROM DATA_MOBIL WHERE WARNA="HITAM" ORDER BY HARGA_RENTAL ASC LIMIT 2;
```

HASIL:
![GAMBAR](GAMBARBASDAT/LIMIT.PNG)
ANALISIS:
 - **SELECT** adalah sebuah perintah query yang tugas memilih.
- **FROM** adalah sebuah perintah query yang tugas nya untuk pemanggilan dari.
- **ORDER BY** adalah sebuah perintah query yang  untuk mengurutkan pemanggilan berdasarkan nilai.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **PEMINJAM & WARNA** adalah sebuah nama kolom.
- **ASC** adalah perintah query yang betugas menampilkan suatu data secara berurutan ke atas.
- **HITAM** adalah nama data pada sebuah kolom.
- **LIMIT 2** adalah perintah untuk membatasi jumlah baris yang ingin ditampilkan.

KESIMPULAN:
Query di atas adalah perintah untuk menampilkan tabel dengan data hitam pada kolom warna yang sesuai dengan alfabet A-Z  tapi ditampilkan hanya 2 baris .

## DISTINCT 

STRUKTUR:
```MYSQL 
SELECT DISTINCT(NAMA_KOLOM) FROM NAMA_TABEL;
```

CONTOH:
```MYSQL
SELECT DISTINCT(PEMILIK) FROM DATA_MOBIL;
```

HASIL:
![GAMBAR](GAMBARBASDAT/DISTINCT.PNG)

ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **DISTINCT** adalah perintah untuk mengembalikan nilai unik dari hasil query.
- **PEMILIK** adalah sebuah nama kolom.
- **FROM** adalah sebuah pemanggilan dari data yang ditujukan.
- **DATA_MOBIL** adalah sebuah nama tabel.

KESIMPULAN:
query di atas perintah ini akan mengembalikan setiap nilai yang berbeda dari kolom "PEMILIK", tanpa adanya duplikasi. Ini berguna untuk melihat daftar pemilik mobil yang berbeda yang terdapat dalam tabel tersebut.

## CONCAT,CONCAT_WS,AS

1. CONCAT
STRUKTUR:
```MYSQL
SELECT CONCAT(NAMA_TABEL,NAMA_KOLOM) FROM NAMA_TABEL;
```

CONTOH:
```MYSQL
SELECT CONCAT(PEMILIK,WARNA) FROM DATA_MOBIL;
```

HASIL:
![GAMBAR](GAMBARBASDAT/CONCAT.PNG)
ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **CONCAT** adalah perintah untuk menggabungkan sebuah kolom untuk ditampilkan.
- **PEMILIK & WARNA** adalah sebuah nama kolom.
- **FROM** adalah sebuah pemanggilan dari data yang ditujukan.
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menggabungkan kolom pemilik dan warna untuk ditampilkan

2. CONCAT_WS
STRUKTUR:
```MYSQL
SELECT CONCAT_WS ("PEMISAH",NAMA_KOLOM,NAMA_KOLOM,NAMA_KOLOM) FROM NAMA_TABEL;
```

CONTOH:
```MYSQL
SELECT CONCAT_WS ("-",NO_PLAT,NO_MESIN,ID_MOBIL) FROM DATA_MOBIL;
```

HASIL:
![GAMBAR](GAMBARBASDAT/CONCAT_WS.PNG)
ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **CONCAT_WS** adalah perintah untuk menggabungkan nilai nilai sebuah kolom dan memiliki pemisah tertentu untuk ditampilkan.
- **NO_PLAT,NO_MESIN,ID_MOBIL** adalah sebuah nama kolom.
- **"-"** adalah pemisah dari kolom yang di satukan.
- **FROM** adalah sebuah pemanggilan dari data yang ditujukan.
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menggabungkan kolom no_plat,no_mesin,id_mobil menggunakan "-" sebagai pemisah untuk ditampilkan.

3. AS
STRUKTUR:
```MYSQL
SELECT CONCAT_WS ("PENGHUBUNG",NAMA_KOLOM,NAMA_KOLOM) FROM NAMA_TABEL;
```

CONTOH:
```MYSQL
SELECT CONCAT_WS ("+",PEMILIK,PEMINJAM) FROM DATA_MOBIL;
```

HASIL:
![GAMBAR](GAMBARBASDAT/AS.PNG)
ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **CONCAT_WS** adalah perintah untuk menggabungkan nilai nilai sebuah kolom dan memiliki pemisah tertentu untuk ditampilkan.
- **PEMILIK,PEMINJAM** adalah sebuah nama kolom.
- **"+"** adalah penghubung dari kolom yang di satukan.
- **FROM** adalah sebuah pemanggilan dari data yang ditujukan.
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menggabungkan kolom pemilik dan peminjam menggunakan "+" sebagai penghubung untuk ditampilkan.

## VIEW
1. MEMBUAT TABEL VIRTUAL
STRUKTUR:
```MYSQL
CREATE VIEW NAMA_TABEL_VIRTUAL AS
SELECT NAMA_KOLOM,NAMA_KOLOM,NAMA_KOLOM,NAMA_KOLOM
FROM NAMA_TABEL
WHERE NAMA_KOLOM="NAMA_DATA";
```

CONTOH:
```MYSQL
CREATE VIEW INFO_NO_PLAT AS
SELECT ID_MOBIL,NO_PLAT,PEMILIK,PEMINJAM
FROM DATA_MOBIL
WHERE PEMILIK="IBRAHIM";
```

HASIL:
![GAMBAR](GAMBARBASDAT/BUATTABELVIRTUAL.PNG)
ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **CREATE VIEW** adalah perintah untuk membuat sebuah tabel virtual
- **ID_MOBIL,NO_PLAT,PEMILIK,PEMINJAM** adalah sebuah nama kolom.
- **FROM** adalah sebuah pemanggilan dari data yang ditujukan.
- **DATA_MOBIL** adalah sebuah nama tabel.
- **WHERE** adalah sebuah perintah query yang tugas untuk menentukan pemanggilan yang mana ditujukannya.
- **IBRAHIM** adalah nama data pada suatu kolom
KESIMPULAN:
query diatas adalah perintah untuk membuat sebuah tabel virtual yang ditampilkan adalah kolom id_mobil,no_plat,pemilik,peminjam yang sesuai dengan data ibrahim pada kolom pemilik.

2. MENAMPILKAN TABEL VIRTUAL 
STRUKTUR:
```MYSQL
SELECT * FROM NAMA_TABEL_VITUAL;
```

CONTOH:
```MYSQL
SELECT * FROM INFO_NO_PLAT;
```

HASIL:
![GAMBAR](GAMBARBASDAT/TABELVIRTUAL.PNG)
ANALISIS:
- **SELECT** adalah perintah query yang tugas nya memilih.
- **FROM** adalah perintah query dari.
- **INFO_NO_PLAT** adalah sebuah nama tabel virtual yang telah dibuat
KESIMPULAN:
query di atas adalah perintah untuk menampilkan tabel virtual yang dibuat tadi.

3. MENGHAPUS TABEL VIRTUAL 
STRUKTUR:
```MYSQL
DROP VIEW NAMA_TABEL_VITUAL;
```

CONTOH:
```MYSQL
DROP VIEW INFO_NO_PLAT;
```

HASIL:
![GAMBAR](GAMBARBASDAT/DROPVIRTUAL.PNG)
ANALISIS:
	query di atas adalah perintah untuk menghapus tabel yang telah dibuat tadi.

## AGREGASI 
1. MENGHITUNG TOTAL
STRUKTUR:
```MYSQL
SELECT SUM(NAMA_KOLOM) AS NAMA_KOLOM FROM NAMA_TABEL
```
CONTOH:
```MYSQL
SELECT SUM(HARGA_RENTAL) AS TOTAL_HARGA FROM DATA_MOBIL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/SUM.PNG)
ANALISIS:
- **SELECT** adalah perintah untuk memilih suatu kolom 
- **SUM** adalah perintah untuk menghitung semua total jumlah
- **HARGA_RENTAL** adalah sebuah nama kolom
- **AS** adalah perintah untuk memberikan nama lain dari perintah tersebut.
- **TOTAL_HARGA** nama lain dari kolom pada perintah tersebut
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menghitung total data dari kolom harga rental dan diubah nama nya menjadi total harga
2. MENGHITUNG JUMLAH BARIS
STRUKTUR:
```MYSQL
SELECT COUNT(NAMA_KOLOM) AS NAMA_KOLOM FROM NAMA_TABEL
```
CONTOH:
```MYSQL
SELECT COUNT(PEMILIK) AS JUMLAH_PEMILIK FROM DATA_MOBIL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/COUNT.PNG)
ANALISIS:
- **SELECT** adalah perintah untuk memilih suatu kolom 
- **COUNT** adalah perintah untuk menghitung semua jumlah baris.
- **JUMLAH_PEMILIK** adalah sebuah nama kolom
- **AS** adalah perintah untuk memberikan nama lain dari perintah tersebut.
- **PEMILIK** nama lain dari kolom pada perintah tersebut
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menghitung jumlah data pada kolom pemilik.

3. MENGHITUNG NILAI TERENDAH
STRUKTUR:
```MYSQL
SELECT MIN(NAMA_KOLOM) AS NAMA_KOLOM FROM NAMA_TABEL
```
CONTOH:
```MYSQL
SELECT MIN(HARGA_RENTAL) AS MINIMUM FROM DATA_MOBIL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/MIN.PNG)
ANALISIS:
- **SELECT** adalah perintah untuk memilih suatu kolom 
- **MIN** adalah perintah untuk menghitung jumlah data yang paling terkecil.
- **HARGA_RENTAL** adalah sebuah nama kolom
- **AS** adalah perintah untuk memberikan nama lain dari perintah tersebut.
- **MINIMUM** nama lain dari kolom pada perintah tersebut
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menghitung jumlah data  terkecil dari kolom harga rental dan ditampilkan dengan kolom baru yaitu MINIMUM.
4. MENGHITUNG NILAI TERTINGGI 
STRUKTUR:
```MYSQL
SELECT MAX(NAMA_KOLOM) AS NAMA_KOLOM FROM NAMA_TABEL
```
CONTOH:
```MYSQL
SELECT MAX(HARGA_RENTAL) AS MAXIMUM FROM DATA_MOBIL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/MAX.PNG)
ANALISIS:
- **SELECT** adalah perintah untuk memilih suatu kolom 
- **MAX** adalah perintah untuk menghitung data yang paling tinggi.
- **HARGA_RENTAL** adalah sebuah nama kolom
- **AS** adalah perintah untuk memberikan nama lain dari perintah tersebut.
- **MAXIMUM** nama lain dari kolom pada perintah tersebut
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menghitung jumlah data tertinggi dari kolom harga rental dan ditampilkan dengan kolom baru yaitu MAXIMUM.
5. MENAMPILKAN NILAI RATA RATA
STRUKTUR:
```MYSQL
SELECT AVG(NAMA_KOLOM) AS NAMA_KOLOM FROM NAMA_TABEL
```
CONTOH:
```MYSQL
SELECT AVG(HARGA_RENTAL) AS RERATA FROM DATA_MOBIL;
```
HASIL:
![GAMBAR](GAMBARBASDAT/SUM.PNG)
ANALISIS:
- **SELECT** adalah perintah untuk memilih suatu kolom 
- **AVG** adalah perintah untuk menghitung jumlah rata rata
- **HARGA_RENTAL** adalah sebuah nama kolom
- **AS** adalah perintah untuk memberikan nama lain dari perintah tersebut.
- **RERATA** nama lain dari kolom pada perintah tersebut
- **DATA_MOBIL** adalah sebuah nama tabel.
KESIMPULAN:
query di atas adalah perintah untuk menghitung rata rata jumlah data dari kolom harga rental dan ditampilkan dengan kolom baru yaitu RERATA.
