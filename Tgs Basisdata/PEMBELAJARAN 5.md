# ALTER 

MENAMBAH KOLOM
```MYSQL 
ALTER TABLE mobil ADD batas_peminjaman varchar(10) AFTER peminjam
```

- **AFTER** opsional untuk digunakan,jika tidak menggunakan klausa ini maka secara default kolom yang dibuat akan berada di akhir.jika kolom ingin ditaruh pada awal kolom gunakan klausa **FIRST**.
- silahkan tampilkan struktur tabel dan masukkan data ke kolom batas_peminjaman.

HASIL:
![GAMBAR](mengubahalter.png)
Setelah menambahkan kolom kita dapat mengisi kolom tersebut dengan query:
```mysql
 update mobil set batas_peminjam="28-12-2024" where id_mobil>3;
```

HASIL:
![GAMBAR](updatealter.png)

MENGUBAH NAMA KOLOM
```mysql
ALTER TABLE mobil CHANGE batas_peminjam deadline VARCHAR(10);
```

- **RENAME COLUMN:** digunakan pada mysql versi lawas yang mengharuskan menyertakan tipe datanya juga.
HASIL:
![GAMBAR](renamealter.png)

MENGUBAH TIPE DATA KOLOM 
```MYSQL 
ALTER TABLE mobil MODIFY deadline DATE;
```

HASIL:
![GAMBAR](modifydate.png)
MENAMBAHKAN CONSTRAINT
```MYSQL 
ALTER TABLE mobil 
	ALTER deadline SET DEFAULT 'ready';
```

HASIL:
![GAMBAR](constrain.png)
MENGHAPUS CONSTRAINT:
```MYSQL 
ALTER TABLE mobil
	ALTER deadline DROP DEFAULT;
```

HASIL:
![GAMBAR](dropalter.png)

MENGHAPUS KOLOM  
```MYSQL
ALTER TABLE mobil DROP COLUMN deadline;
```

HASIL:
![GAMBAR](dropkolomalter.png)

MENGUBAH NAMA TABEL 
```MYSQL
ALTER TABLE mobil RENAME TO data_mobil;
```

HASIL:
![GAMBAR](renamealter.png)

