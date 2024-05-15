#  Pengenalan Basis Data

## Definisi Basis Data

_Basis_ : Adalah tempat berkumpul, markas, gudang, wadah suatu data

_Data_ : Adalah sekumpulan fakta sebuah objek

_Kesimpulan_ : _Basis data_ adalah kumpulan informasi yg disimpan di dalam komputer secara sistematik

## Peranan Basis Data

Bank: Bank merupakan salah satu organisasi yang sangat tergantung kepada sistem basis data. Data nasabah, transaksi yang dilakukan, dan data keuangan lainnya disimpan di sistem basis data. Sistem ini memungkinkan layanan kepada nasabah bank dapat dilakukan dengan baik.

# Data base

## Contoh tabel database
![300](Asetdatabase/Hirarki.jpg)

## Struktur Tabel Dalam Basis Data
Struktur/Hirarki DataBase adalah struktur organisasi data dalam database yang mengatur hubungan antara entitas atau tabel data.Di dalam hirarki database,data diorganisir dalam bentuk pohon dengan satu entitas induk atau tabel utama yang memiliki beberapa entitas tabel yang terkait.

Database saya anggap seperti Liga Inggris yang dimana Dia Menampung Club" Seperti MU,MC, yg di dalamnya Mempunyai Pemain Yang berbeda beda Sama Seperti Database dimana Dia Menampung File" Yg berbeda beda di dalamnya Contohnya: Ada 4 Club yg saya Ambil 1 saya Uraikan DiMana 4 Club itu ada Manchester United, Manchester city, Tottenham, Aston Villa. Yang saya Uraikan Manchester City dalam bentuk Tabel.
## Struktur database
| No | Nama  | Alamat             | Hobi           |
| -- | ----- | ------------------ | -------------- |
| 1  | Nabil | Jl. Muh jufri4     | Baca komik     |
| 2  | Fadil  | Jl. Kalumpang      | Main minecraft |
| 3  | Bombon  | Jl. Galangan kapal | Baca komik     |
| 4  | Angga | Jl. Traktor4       | Nonton anim    |
### Tabel
Tabel adalah sebuah struktur dasar yang menyimpan data dalam format terstruktur. Setiap tabel memiliki kolom yang mewakili atribut dan baris yang mewakili catatan. Contoh seperti di bawah berikut

- Baris merupakan deretan horizontal yang terdiri dari kata, angka, data atau objek lainnya, contoh di atas contoh untuk baris seperti. 1, Fatir, jl. Muh jufri4, baca komik, , 2, Daud, jl. Kalumpang, main minecraft, , Dan seterusnya. 
- Kolom merupakan deretan vertikal contoh di atas untuk kolom seperti. 1, 2, 3, 4, Ahmad Fatir, daud, Dan seterusnya. 
- untuk isinya itu merupakan sebuah item data atau karakter yang di masukkan ke dalam tabel.

### Database

Database (basis data) adalah kumpulan data yang terorganisir dengan cara tertentu untuk memudahkan pengelolaan, penyimpanan, dan pengambilan informasi. Dalam sebuah database, data disimpan dalam tabel yang terdiri dari baris dan kolom. Setiap baris dalam tabel mewakili sebuah catatan atau entitas, sedangkan kolom menyimpan. Di database juga memiliki komponen utama seperti.

1. **Tabel:** Struktur dasar yang menyimpan data dalam format terstruktur. Setiap tabel memiliki kolom yang mewakili atribut dan baris yang mewakili catatan.
    
2. **Baris atau Record:** Masing-masing baris dalam tabel berisi data untuk satu entitas atau catatan tertentu.
    
3. **Kolom atau Field:** Masing-masing kolom dalam tabel menyimpan informasi tentang atribut tertentu, seperti nama, alamat, atau nomor telepon.
    
4. Item Data atau Karakter: merupakan isian dari baris dan kolom.
# instalasi mySQL
## menggunakan termux
1. Buka termux
2. Ketik ``termux-setup-storage``
3. Klik izinkan/allow access
4. Lakukan update dan upgrade paket.ketik ``pkg update && upgrade``
5. Jika ada konfirmasi untuk melanjutkan instalasi ketik aja ``Y``
6. Install applikasi mariadb dengan mengetik``pkg install mariadb``
7. Ketika proses nya berhenti dan ada pilihan ketik saja ``Y`` untuk melanjutkan proses penginstalannya. 
8. Ketik ``mysqld_safe`` untuk memberi keamanan
9. Untuk menghentikan proses ``ctrl+z``
10. Masuk ke akun admin ``mysql -u root`` 
11. Buatlah data base dengan ketik ``create database xi_rpl_1;``
12. Kalo mau menampilkan data basenya ketik ``show databases;``
13. Kalo mau menghapus data basenya ketik ``drop database [nama database];
14. Kalo mau menggunakan data basenya ketik ``use [nama database];``

## referensi youtube
https://youtu.be/JojQd-l7fEE?si=OPIB01q45A2FmY1x
# penggunaan awal MySQL
## Query
``<mysql -u root -p>``
## hasil
![250](Asetdatabase/Mysqroot.jpg)
## Analisis kesimpulan
- `<mySQL>` Salah satu aplikasi database server dengan bahasa pemrograman structured query languange `(SQL)` yang berfungsi untuk mengelola data secara terstruktur dan sistematis.
- `<-u root>` Bagian ini mengeset pengguna (user) yang akan digunakan saat terhubung ke server  MYSQL. Dalam contoh ini, pengguna yang digunakan adalah `"root"`. Pengguna `"root"` biasanya memiliki hak akses penuh ke server MYSQL dan dapat melakukan tindakan administratif.
- `<-p>` Opsi ini digunakan untuk meminta kata sandi (password) setelah perintah dijalankan ini adalah langkah keamanan yang umum digunakan untuk memastikan hanya pengguna yang sah yang dapat mengakses server MYSQL. Setelah kita menekan Enter setelah perintah ini, kita akan diminta memasukkan kata sandi untuk pengguna `"root"`.




# data base
Database (basis data) adalah kumpulan terstruktur dari informasi yang disimpan secara elektronik dalam sistem komputer. Database dirancang untuk menyimpan, mengatur, dan mengelola data dengan cara yang efisien dan dapat diakses.
## buat data base
- `CREATE DATABASE` adalah perintah untuk membuat database baru.
- ``[XI_RPL_1]`` adalah nama yang Anda pilih untuk database baru Anda. Tanda kurung siku `<("[]")>` digunakan di sini untuk menghindari kesalahan jika nama database mengandung karakter spesial atau spasi. Namun, perlu dicatat bahwa tidak semua DBMS mengizinkan penggunaan tanda kurung siku dalam nama database, jadi pastikan untuk menyesuaikan sintaksdengan DBMS yang Anda gunakan.
### Query
``create database xi_rpl_1;``

### Hasil:
![300](Asetdatabase/Buatdatabase.jpg)
### Analisis kesimpulan :
- CREATE DATABASE adalah perintah untuk membuat database baru.
- XRPL 1 adalah nama yang Anda pilih untuk database baru Anda. Tanda kurung siku '<("{}")>'digunakan di sini untuk menghindari kesalahan jika nama database mengandung karakter spesial atau spasi. Namun, perlu dicatat bahwa tidak semua DBMS mengizinkan penggunaan tanda kurung siku dalam nama database, jadi pastikan untuk menyesuaikan sintaksdengan DBMS yang Anda gunakan.
## Tampilkan data base
`SHOW DATABASE` digunakan untuk menampilkan daftar database yang ada dalam sistem manejemen basis data (DBMS). Perintah ini dapat digunakan di beberapa DBMS seperti MYSQL, PostgreSQL, dan beberapa DBMS lainnya. Namun, perintahnya dapat sedikit berbeda tergantung
### Query 
``show databases;``

### Hasil:
![250](Asetdatabase/Showdatabase.jpg)
### Analisis kesimpulan :

`SHOW DATABASE` digunakan untuk menampilkan daftar database yang ada dalam sistem manejemen basis data (DBMS). Perintah ini dapat digunakan di beberapa DBMS seperti MYSQL, PostgreSQL, dan beberapa DBMS lainnya. Namun, perintahnya dapat sedikit berbeda tergantung
## hapus database
``<DROP DATABASE [nama_database]>`` digunakan dalam sistem manajemen basis data (DBMS) untuk menghapus sebuah database beserta semua objek yang terkait dengan database tersebut, seperti tabel, indeks, tampilan, prosedur tersimpan, dan lain-lain.
### Query
``drop database xi_rpl_1``
### Hasil:
![300](Asetdatabase/Dropdata.jpg)
### Analisis kesimpulan
`DROP DATABASE` nama database digunakan dalam sistem manajemen basis data (DBMS) untuk menghapus sebuah database beserta semua objek yang terkait dengan database tersebut, seperti tabel, indeks, tampilan, prosedur tersimpan, dan lain-lain.
## gunakan data base
``USE [nama_database]`` digunakan dalam sistem manajemen basis data (DBMS) untuk beralih atau memilih database yang akan digunakan. Ketika Anda menggunakan perintah ``<USE>`` diikuti dengan nama database, DBMS akan mengarahkan semua perintah dan operasi selanjutnya pada database yang ditentukan.
### Query
`` use xi_rpl_1; ``
### Hasil:
![300](Asetdatabase/Usedata.jpg)
### Analisis kesimpulan :
`Use [nams database]` digunakan dalam sistem manajemen basis data (DBMS) untuk beralih atau memilih database yang akan digunakan. Ketika Anda menggunakan perintah uses diikuti dengan nama database, DBMS akan mengarahkan semua perintah dan operasi selanjutnya pada database yang ditentukan.
# tipe data
## angka
- Int (integer) tipe data ini digunakan untuk merepresentasikan bilangan bulat tanpa bagian desimal.Contoh: 0, 42, -10
- **DECIMAL**: Digunakan untuk menyimpan nilai desimal presisi tinggi, cocok untuk perhitungan finansial atau keuangan.
- **FLOAT dan DOUBLE**: Digunakan untuk menyimpan nilai desimal dengan presisi floating-point. DOUBLE memiliki presisi lebih tinggi dibandingkan FLOAT.
- **TINYINT , SMALLINT , MEDIUMINT , dan BIGINT**: Tipe data ini menyimpan bilangan bulat dengan ukuran yang berbeda-beda.

## teks
-  **CHAR(N)**: Menyimpan string karakter tetap dengan panjang N. Contoh: CHAR(10) akan menyimpan stringdengan panjang tepat 10 karakter.

- **VARCHAR(N)**: Menyimpan string karakter dengan panjang variabel maksimal N. Misalnya,VARCHAR(255) dapat menyimpan string hingga 255 karakter, tetapi sebenarnya hanya menyimpan panjang yang diperlukan plus  beberapa overhead.

- **TEXT**: Digunakan untuk menyimpan teks dengan panjang variabel, tanpa batasan panjang tertentu. Cocok untukdata teks yang panjangnya tidak terduga.

- **ENUM**: Memungkinkan Anda mendefinisikan set nilai yang mungkin dan membatasi kolom hanya dapat mengambil salah satu dari nilai tersebut.

- **SET**: Mirip dengan ENUM, namun dapat menyimpan satu atau lebih nilai dari himpunan yang telah ditentukan.
## tanggal
- `Date` digunakan untuk menyimpan informasi tentang tanggal, biasanya terdiri dari hari, bulan, dan tahun seperti 30 Januari 2024
- `Time` digunakan untuk menyimpan informasi tentang waktu dalam sehari, biasanya terdiri dari jam, menit, detik, dan milidetik seperti 14:30:45.500
- `DateTime` menggabungkan informasi tanggal dan waktu dalam satu objek, biasanya terdiri dari hari, bulan, tahun, jam, menit, detik, dan milidetik seperti 30 Januari 2024 14:30:45.500
- **TimeStamp**: Sama seperti DATETIME, tetapi dengan kelebihan diatur secara otomatis saat data dimasukkan atau diubah.
## boolean

- **BOOL / BOOLEAN / TINYINT**: Digunakan untuk menyimpan nilai boolean, yang dapat mewakili kebenaran (true) atau kesalahan (flase). 

## TIPE DATA PILIHAN
### ENUM
Menyimpan satu nilai dari daftar nilai yang ditentukan.

### SET 
Menyimpan beberapa nilai dari daftar nilai yang ditentukan 
# Table
## Buat Table

Analisis Kesimpulan
Perintah `"CREATE TABLE"` digunakan dalam SQL untuk membuat sebuah tabel baru dalam basis data. Berikut adalah penjelasan mengenai sintaks dan bagaimana menggunakan perintah `"CREATE TABLE"`.

### **Struktur Query**:
```sql
CREATE TABLE [nama_table] ( 
nama_kolom1 tipe_data(ukuran) [tipe_constraint] 
nama_kolom2 tipe_data(ukuran) [tipe_constraint] 
nama_kolom3 tipe_data(ukuran) [tipe_constraint] );
```

### Contoh Query
```sql
CREATE TABLE Pelanggan (
id_pelanggan int(4) PRIMARY KEY NOT NULL,
nama_depan varchar(25) NOT NULL,
nama_belakang varchar(25) NOT NULL,
no_telp char(12) UNIQUE );
```

### Hasil
![400](Asetdatabase/Struktur.jpg)
### Analisis:
1. **CREATE TABLE Pelanggan:**
    
    - Ini adalah perintah SQL untuk membuat sebuah tabel baru dengan nama "Pelanggan".
    
2. **id_pelanggan int(4) PRIMARY KEY NOT NULL:**
    
    - Kolom "id_pelanggan" dibuat sebagai tipe data integer dengan panjang maksimal 4 digit.
    - PRIMARY KEY menandakan bahwa kolom ini adalah kunci utama (primary key) yang unik dan tidak boleh kosong (NOT NULL).
    - Ini menunjukkan bahwa setiap baris dalam tabel akan diidentifikasi oleh nilai unik dalam kolom "id_pelanggan".
    
3. **nama_depan varchar(25) NOT NULL:**
    
    - Kolom "nama_depan" dibuat sebagai tipe data string (varchar) dengan panjang maksimal 25 karakter.
    - NOT NULL menunjukkan bahwa kolom ini tidak boleh kosong.
    
4. **nama_belakang varchar(25) NOT NULL:**
    
    - Kolom "nama_belakang" dibuat sebagai tipe data string (varchar) dengan panjang maksimal 25 karakter.
    - NOT NULL menunjukkan bahwa kolom ini tidak boleh kosong.
    
5. **no_telp char(12) UNIQUE:**
    
    - Kolom "no_telp" dibuat sebagai tipe data karakter (char) dengan panjang tepat 12 karakter.
    - UNIQUE menandakan bahwa setiap nilai dalam kolom ini harus unik, tidak boleh ada duplikat.

### Kesimpulan :
tabel "Pelanggan" memiliki struktur yang terorganisir dengan baik. Setiap entri dalam tabel akan memiliki id_pelanggan sebagai identitas unik, serta informasi nama depan, nama belakang, dan nomor telepon pelanggan. Nomor telepon harus unik dalam tabel ini. Dengan struktur yang jelas seperti ini, database akan dapat menyimpan informasi pelanggan secara efisien dan memastikan integritas data yang baik.

## Tampilkan Struktur Tabel
### **Struktur Query**:
```sql
desc [nama_table];`

```
### **Contoh Query**:

```sql
desc Pelanggan;

```

### Hasil
![300](Asetdatabase/Struktur.jpg)

### Analisis
`desc pelanggan;`:dapat melihat secara detail karakteristik dari setiap kolom dalam tabel tersebut, termasuk nama kolom, tipe data, panjang maksimum (jika berlaku), dan konstrain khusus seperti PRIMARY KEY, UNIQUE, atau NOT NULL yang diterapkan pada setiap kolom.
### Kesimpulan
perintah tersebut memberikan gambaran tentang bagaimana tabel "Pelanggan" telah didefinisikan dalam basis data.

## Menampilkan Daftar Tabel
**Struktur Query**:
```sql
show tables;
```

**Contoh** Query: 
```sql
show tables;
``````

### Hasil
![300](Asetdatabase/Showtable.jpg)

### **Analisis**:
`show tables;`:untuk menampilkan semua tabel yang ada dalam database yang sedang aktif.

### **Kesimpulan**:
memiliki peran penting dalam memberikan visibilitas awal terhadap struktur database, yang menjadi dasar untuk pekerjaan lebih lanjut dalam pengelolaan dan penggunaan data.
## QnA
>[! Faq] Mengapa hanya kolom id_pelanggan yang menggunakan constraint PRIMARY KEY?
> > Untuk membedakan id Pelanggan  yang sama, mencegah duplikasi, dan mempermudah pencarian data.


> [! Faq] Mengapa pada kolom no_telp yang menggunakan tipe data chat bukan varchar?
> > Tipe data char menyimpan data dalam karakter panjang lebih efisien. pencarian pada kolom tipe data `CHAR` dapat lebih cepat


> [! Faq] Mengapa hanya kolom no_telp yang menggunakan constraint UNIQUE?
> > Karna no_telp tidak ada yang sama semua pasti berbeda dan nilainya unik maka menggunakan constrains unique artinya data dalam tabel id_telpon berbeda tidak ada yang sama. 


> [! Faq] Mengapa kolom no_telp tidak memakai constraint NOT NULL, sementara kolom lainnya menggunakan constraint tersebut?
> > Nomor telpon dianggap opsional. nomor telepon hanya menjadi wajib saat pengguna melakukan langkah-langkah tertentu, Anda mungkin tidak ingin mengharuskan pengguna mengisinya pada tahap awal.


> [! Faq] Perbedaan PK & UNIQUE
> > PRIMERY KEY untuk membedakan data yang sama dan hanya boleh 1 dan tidak boleh tidak ada. 
Kalau UNiQUE sebuah kolom yang memiliki data yang berbeda atau tidak sama unique boleh 1,2,3 Dan seterusnya dan boleh tidak ada.



# insert
## insert 1 data

### struktur
```SQL
Insert into pelanggan
Values(1,fadil,dil,0821772842)
```
### Contoh
```MySQL
MariaDB [rental_fatir]> insert into PELANGGAN
    -> VALUES(813,"Nabil","Shiddiq","082163626");
```

### Hasil
![300](Asetdatabase/Insert1data.jpg)
### analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `values (1,"Nabil","Shiddiq","08500000")`: Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.
### Kesimpulan 
mencoba untuk memasukkan data baru ke dalam tabel "Pelanggan".
## Insert >1 Data
### Struktur
```sql
Insert into [nama_table]
Values (nilai1, nilai2, nilai3, nilai4)
       (nilai1, nilai2, nilai3, nilai4)
       (nilai1, nilai2, nilai3, nilai4)
```
### Contoh
```sql
Insert into pelanggan
Values (2, "Nabil", "Shiddiq", "0890000"), (3,"muh", "fadil", "0870000" ), (4, "Abd", "Rahman", "08100000");
```
### Hasil
![300](Asetdatabase/Insertlebihdarisatu.jpg)
### Analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `Values (2, "Nabil", "Shiddiq", "0890000"), (3,"muh", "Fadil", "0870000" ), (4, "abd", "Rahman", "08100000");`:Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.

### Kesimpulan
data telah dimasukkan ke dalam tabel Pelanggan dengan masing-masing nilai kolom sesuai dengan urutan yang diberikan

## Menyebut kolom
### struktur
```Mysql
Insert into pelanggan
(Nama_depan, id)value
("Stuwja",6);
```

### Contoh
```sql
insert into Pelanggan
(id_pelanggan,nama_depan,nama_belakang)
values (813,"Nabil","Shiddiq");
```
### Hasil
![300](Asetdatabase/Select.jpg)
### Analisis
- `insert into Pelanggan`: Ini adalah perintah untuk memasukkan baris data ke dalam tabel "Pelanggan".
- `(id_pelanggan,nama_depan,nama_belakang)`:yang diberikan nilai, sedangkan kolom lainnya akan diisi dengan nilai default jika diperbolehkan atau NULL jika tidak diizinkan.
- `values (813,"Nabil","Shiddiq")`:Ini adalah nilai yang akan dimasukkan ke dalam tabel "Pelanggan". Urutannya sesuai dengan kolom-kolom pada tabel tersebut.
### Kesimpulan
sebuah entri baru telah dimasukkan ke dalam `tabel Pelanggan`,Tidak ada kolom lain yang diberikan nilai dalam perintah INSERT, sehingga kolom-kolom yang tidak disebutkan akan menggunakan nilai default atau NULL.
# select
## seluruh data
### Struktur
```sql
select * from [nama_table];
```
### Contoh
```sql
Select * from pelanggan;
```
### Hasil
![300](Asetdatabase/Select.jpg)
### Analis 
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `*` artinya semua kolom yang ada di table akan di tampilkan 
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
### Kesimpulan
program akan mengambil dan menampilkan semua data yang tersimpan dalam tabel Pelanggan, termasuk setiap kolom dan setiap baris yang ada dalam tabel tersebut.
## Data kolom tertentu
### Struktur
```Mysql
Select [nama_kolom1], [nama_kolom2], [nama_kolom_n]
From[nama_tabel];
```
### contoh
```sql
Select nama_depan From pelanggan;
```
### Hasil
![300](Asetdatabase/Klom.jpg)
### Analisis
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `nama_depan` nama kolom dalam tabel database yang mungkin menyimpan informasi tentang nama depan dari pelanggan.
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
### Kesimpulan 
Hasilnya akan berupa daftar `nama_depan` dari semua pelanggan yang terdaftar dalam tabel tersebut.
## kalusa WHERE
### Struktur
```sql
Select [nama_kolom] From [nama_tabel] Where[kondisi];
```
### Contoh
```sql
Select nama_depan From pelanggan
Where id=813;
```
### Hasil
![300](Asetdatabase/Where1.jpg)

### Analisis
- `Select` merupakan query yang digunakan untuk menampilkan hasil `insert` 
- `id_pelanggan,nama_depan` nama kolom dalam tabel database yang mungkin menyimpan informasi tentang nama depan dari pelanggan.
- `from` query yang digunakan untuk memberikan penanda bahwa table mana yang akan di tampilkan
- `pelanggan` merupakan nama table yang isi nya akan di tampilkan
- `where` untuk menyaring baris data berdasarkan kondisi tertentu.
- `id_pelanggan=1` hanya baris-baris data di mana nilai kolom 
### Kesimpulan 
hasilnya akan berisi ID dan nama depan pelanggan yang memiliki ID tertentu
# update
## struktur
```sql
Update nama_table set nama_kolom where kondisi;
```
## contoh
```sql
Update Pelanggan set no_telp="085326690" where id_pelanggan="813";
```

## hasil
![300](Asetdatabase/Update.jpg)
## Analisis
- `UPDATE pelanggan`: Ini adalah klausa yang menentukan tabel mana yang akan diperbarui. Dalam kasus ini, tabel yang diperbarui adalah "pelanggan".
- `SET no_telp="085358639358"`: Ini adalah klausa yang menentukan kolom mana yang akan diperbarui dan nilai baru yang akan diberikan. Dalam hal ini, kolom yang diperbarui adalah "no_telp" dan nilainya diubah menjadi "085358639358".
- `WHERE id_pelanggan="1"`: Ini adalah klausa opsional yang digunakan untuk membatasi baris mana yang akan diperbarui. Dalam hal ini, perubahan hanya akan diterapkan pada baris dengan nilai "id_pelanggan" yang sama dengan "1".
## Kesimpulan
nomor telepon (no_telp) dari pelanggan dengan ID "1" akan diubah menjadi "085358639358". Perintah tersebut mengupdate data pada tabel "pelanggan" dan mengaplikasikan perubahan hanya pada baris dengan nilai "id_pelanggan" yang sama dengan "1".
# Delete
## struktur
```sql
Delete from nama_table where kondisi;
```
## contoh
```sql
delete from Pelanggan where id_pelanggan="6";
```
## hasil
![300](Asetdatabase/Delete.jpg)
## Analisis
- `DELETE FROM pelanggan`: Ini adalah klausa yang menentukan tabel mana yang akan dihapus datanya. Dalam kasus ini, data akan dihapus dari tabel "pelanggan".
- `WHERE id_pelanggan="2"`: Ini adalah klausa opsional yang digunakan untuk membatasi baris mana yang akan dihapus. Dalam hal ini, baris dengan nilai "id_pelanggan" yang sama dengan "2" akan dihapus.

## kesimpulan
menghapus baris table kalian bisa menggunakan query delete dengan struktur yaitu delete from nama_table where kondisi;
