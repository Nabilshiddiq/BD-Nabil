## penjelasan
Property `grid-row-start` digunakan dalam CSS Grid Layout untuk menentukan baris pertama tempat suatu item grid akan ditempatkan. Properti ini bekerja bersama dengan `grid-column-start` untuk menentukan posisi awal suatu item dalam grid.

Beberapa hal yang perlu diingat tentang `grid-row-start`:

1. **Nilai Angka**: Anda dapat menetapkan nilai angka untuk `grid-row-start`, yang menunjukkan nomor baris pertama di mana item akan ditempatkan.
    
2. **Keyword**: Selain nilai angka, Anda juga dapat menggunakan kata kunci seperti `span`, yang menentukan jumlah baris yang akan ditempati oleh suatu item.
    
3. **Menentukan Rentang Baris**: Anda juga bisa menggunakan `grid-row-start` untuk menentukan rentang baris di mana suatu item akan ditempatkan. Misalnya, `grid-row-start: span 2;` akan membuat item menempati dua baris.

## kode program
Html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-row-start Example</title>
  <link rel="stylesheet" href="Grid-row-start.css">
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
  grid-row-start: 1; /* Item dimulai dari baris ke-1 */
}

.item:nth-child(2) {
  grid-row-start: 2; /* Item dimulai dari baris ke-2 */
}

.item:nth-child(3) {
  grid-row-start: 1; /* Item dimulai dari baris ke-1 */
}

.item:nth-child(4) {
  grid-row-start: 3; /* Item dimulai dari baris ke-3 */
}

.item:nth-child(5) {
  grid-row-start: 2; /* Item dimulai dari baris ke-2 */
}

.item:nth-child(6) {
  grid-row-start: 3; /* Item dimulai dari baris ke-3 */
}
```
## Hasil

![[3.jpg.jpg]]
