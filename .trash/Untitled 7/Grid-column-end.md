## Penjelasan
Property `grid-column-end` digunakan dalam CSS Grid Layout untuk menentukan kolom terakhir tempat suatu item grid akan ditempatkan. Properti ini bekerja bersama dengan `grid-column-start` untuk menentukan rentang kolom yang diinginkan untuk suatu item.

Beberapa hal yang perlu diingat tentang `grid-column-end`:

1. **Nilai Angka**: Anda dapat menetapkan nilai angka untuk `grid-column-end`, yang menunjukkan nomor kolom terakhir di mana item akan ditempatkan.
    
2. **Keyword**: Selain nilai angka, Anda juga dapat menggunakan kata kunci seperti `span`, yang menentukan jumlah kolom yang akan ditempati oleh suatu item.
    
3. **Menentukan Rentang Kolom**: Anda juga bisa menggunakan `grid-column-end` untuk menentukan rentang kolom di mana suatu item akan ditempatkan. Misalnya, `grid-column-end: span 2;` akan membuat item menempati dua kolom.
    

## kode program
Html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-column-end Example</title>
  <link rel="stylesheet" href="Grid-column-end.Css">
</head>
<body>
  <div class="container">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
    <div class="item">5</div>
    <div class="item">6</div>
  </div>
</body>
</html>
```
Css
```.container {
  display: grid;
  grid-template-columns: repeat(3, 100px);
  grid-gap: 10px;
}

.item {
  background-color: #ccc;
  padding: 20px;
  text-align: center;
}

.item:nth-child(1) {
  grid-column-start: 1;
}

.item:nth-child(2) {
  grid-column-start: 2;
}

.item:nth-child(3) {
  grid-column-start: 3;
}

.item:nth-child(4) {
  grid-column-start: 1;
}

.item:nth-child(5) {
  grid-column-start: 2;
}

.item:nth-child(6) {
  grid-column-start: 3;
}
```
## hasil
![[2.jpg.jpg]]
