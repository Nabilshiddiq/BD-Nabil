# STRUKTUR AWAL
```
ALTER Table mobil  ADD batas_peminjaman varchar(10) AFTER peminjam;
```
Ini adalah untuk membuat kolom baru
## Hasil
![[IMG-20240423-WA0021.jpg]]

## Kesimpulan

# UPDATE 
## STRUKTUR QUERY
```
UPDATE mobil Set batas_peminjaman = "2024-04-24" where peminjam is not NULL ;
```
## Hasil
![[IMG-20240423-WA0023.jpg]]
## Kesimpulan

# Mengubah nama kolom
## Struktur query
```
ALTER TABLE mobil RENAME COLUMN batas_peminjaman TO deadline;
```
## Hasil
![[IMG-20240423-WA0025 1.jpg]]

## Kesimpulan

# mengubah tipe data kolom
## Struktur query
```
ALTER TABLE mobil MODIFY deadline DATE;
```
## Hasil
![[IMG-20240423-WA0024.jpg]]
## Kesimpulan


#

