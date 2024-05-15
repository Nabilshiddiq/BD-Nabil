## Penjelasan
Property grid-row-end digunakan dalam CSS Grid Layout untuk menentukan baris terakhir tempat suatu item grid akan ditempatkan. Properti ini bekerja bersama dengan grid-row-start untuk menentukan rentang baris yang diinginkan untuk suatu item.

Beberapa hal yang perlu diingat tentang grid-row-end:

1.Nilai Angka: Anda dapat menetapkan nilai angka untuk grid-row-end, yang menunjukkan nomor baris terakhir di mana item akan ditempatkan.

2.Keyword: Selain nilai angka, Anda juga dapat menggunakan kata kunci seperti span, yang menentukan jumlah baris yang akan ditempati oleh suatu item.

3.Menentukan Rentang Baris: Anda juga bisa menggunakan grid-row-end untuk menentukan rentang baris di mana suatu item akan ditempatkan. Misalnya, grid-row-end: span 2; akan membuat item menempati dua baris.
## kode program
Html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-row-end Example</title>
  <link rel="stylesheet" href="styles.css">
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
  grid-row-end: 2; /* Item berakhir di baris ke-2 */
}

.item:nth-child(2) {
  grid-row-end: 4; /* Item berakhir di baris ke-4 */
}

.item:nth-child(3) {
  grid-row-end: span 2; /* Item menempati 2 baris */
}

.item:nth-child(4) {
  grid-row-end: 3; /* Item berakhir di baris ke-3 */
}

.item:nth-child(5) {
  grid-row-end: span 2; /* Item menempati 2 baris */
}

.item:nth-child(6) {
  grid-row-end: 4; /* Item berakhir di baris ke-4 */
}
```
## Hasil
![[4.jpg.jpg]]
