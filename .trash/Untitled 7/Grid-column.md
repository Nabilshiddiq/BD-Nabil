## penjelasan
Property grid-column adalah shorthand property dalam CSS Grid Layout yang digunakan untuk menentukan baik grid-column-start maupun grid-column-end secara bersamaan dalam satu aturan CSS. Ini memungkinkan untuk mengatur posisi horizontal suatu item dalam grid dengan lebih mudah.

Nilai yang diterima oleh grid-column bisa berupa:

Single Number: Menentukan kolom di mana item akan ditempatkan. Ini setara dengan menentukan baik grid-column-start maupun grid-column-end dengan nilai yang sama.

Two Numbers: Menentukan grid-column-start dan grid-column-end secara terpisah.

Single Keyword: Menentukan kata kunci seperti span untuk menentukan jumlah kolom yang akan ditempati oleh suatu item.

Two Keywords: Kombinasi dari dua kata kunci yang menentukan span untuk grid-column-start dan grid-column-end.

## kode program
Html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-column Example</title>
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
  grid-column: 1; /* Item dimulai dari kolom ke-1 dan berakhir di kolom ke-1 */
}

.item:nth-child(2) {
  grid-column: 2 / 4; /* Item dimulai dari kolom ke-2 dan berakhir di kolom ke-4 */
}

.item:nth-child(3) {
  grid-column: span 2; /* Item menempati 2 kolom (sama dengan grid-column-start: span 2;) */
}

.item:nth-child(4) {
  grid-column: 3; /* Item dimulai dari kolom ke-3 dan berakhir di kolom ke-3 */
}

.item:nth-child(5) {
  grid-column: span 2 / 4; /* Item dimulai dari kolom dengan lebar 2 dan berakhir di kolom ke-4 */
}

.item:nth-child(6) {
  grid-column: 3 / span 2; /* Item dimulai dari kolom ke-3 dan menempati 2 kolom ke depan */
}
```
## Hasil

![[5.jpg.jpg]]
