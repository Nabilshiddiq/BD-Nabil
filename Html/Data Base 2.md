# Hasil termux

![[IMG-20240130-WA0012.jpg]]
## Penjelasan Termux


Termux adalah Emulator Terminal untuk Android yang memungkinkan untuk menjalankan lingkungan GNU di perangkat Android. Selain itu, berbagai paket perangkat lunak berbasis linux juga dapat diinstal melalui manajer paket aplikasi.
Bahasa pemrograman: C, Java, C++
Jenis: Emulator Terminal, Antarmuka baris perintah

**Cara penginstalan termux:

1.Buka Termux :                                   Buka aplikasi Termux di                    perangkat Android 
2.memperbarui Paket-paket :             Jalankan perintah `pkgpkg       update && pkg upgradeuntuk     memastikan paket-paket Termux  terbaru.
3.Instal Database (Contoh: MySQL) : Gunakpkg install mysqlbegitu
4.Konfigurasi dan Mulai Database : Setelah instalasi selesai,mysql



# Table

## Struktur tabel
**Struktur query

MariaDB [rental_Nabil]> create table pelanggan
    -> id_pelanggan INT(4) PRIMARY KEY NOT NULL,
    -> nama_depan VARCHAR(25) NOT NULL,
    -> nama_belakang VARCHAR(25) NOT NULL,
    -> no_telp CHAR(12) UNIQUE
    -> );



## contoh tabel

2
![[IMG-20240130-WA0021.jpg]]


## hasil tabel


![[IMG-20240130-WA0020.jpg]]



## Pertanyaan
> [! Question]. 
>Apa perbedaan pk dan unique ?
  PK (Primary Key) ?

> PK adalah sebuah kolom atau kumpulan kolom yang unik mengidentifikasi setiap baris dalam sebuah tabel.
> PK secara otomatis mencegah duplikasi data dalam kolom tersebut.
> 
> **Unique :
>Kolom yang ditandai sebagai "Unique" memastikan bahwa setiap nilai dalam kolom tersebut harus unik, tetapi tidak diharuskan menjadi kunci utama tabel.
    
> [! Question].    
> Mengapa hanya kolom id_pelanggan yg menggunakan  constraint primary key ?
> 
>Dengan menggunakan Primary Key, sistem database dapat mengoptimalkan pencarian dan keterhubungan antar tabel, karena indeks dibangun pada Primary Key.
>Mempermudah proses JOIN dan referensi ke pelanggan dalam tabel-tabel lain.

> [! Question]. 
> Mengapa pada kolom no_telp yg menggukan tipe data char bukan vachar ?

>Penggunaan tipe data CHAR atau VARCHAR untuk kolom nomor telepon biasanya tergantung pada kebutuhan dan preferensi pengembang. CHAR menyimpan data dengan panjang tetap, sementara VARCHAR menyimpan data dengan panjang variabel.

> [!Question]. 
> Mengapa hanya kolom no_telp yang menggunakan contraint unique ?
> 
>Dengan constraint UNIQUE, database akan memastikan bahwa tidak ada nomor telepon yang sama yang terdaftar lebih dari satu kali dalam tabel, sehingga memungkinkan keakuratan dan kekonsistenan data.

> [!Question]. 
> Mengapa colom no_telp tidak memakai constraint NOT NULL, sementara kolom lainnya menggunakan constraint tersebut?

>


## Analisis

**id_pelanggan:**
Tipe data INTEGER dengan panjang maksimum 4 digit. Kolom ini dipilih sebagai PRIMARY KEY yang berarti nilai di dalamnya harus unik dan tidak boleh null.

**nama_depan:**
Tipe data VARCHAR dengan panjang maksimum 25 karakter. Kolom ini tidak boleh null.
nama_belakang: Tipe data VARCHAR dengan panjang maksimum 25 karakter. Kolom ini tidak boleh null.

**no_telp:**
Tipe data CHAR dengan panjang tepat 12 karakter. Kolom ini memiliki constraint UNIQUE yang berarti tidak ada dua nilai yang sama di kolom ini.




## Select

![[IMG-20240213-WA0011 1.jpg]]

**Update data**
Struktur query 
Delete From nama_label where kondisi ;
![[IMG-20240213-WA0013.jpg]]

**Delete data**
Delete From pemilik where id=2;
![[IMG-20240213-WA0014.jpg]]
