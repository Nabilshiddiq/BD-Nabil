## penjelasan
Property grid-row adalah shorthand property dalam CSS Grid Layout yang digunakan untuk menentukan baik grid-row-start maupun grid-row-end secara bersamaan dalam satu aturan CSS. Ini memungkinkan untuk mengatur posisi vertikal suatu item dalam grid dengan lebih mudah.

Nilai yang diterima oleh grid-row bisa berupa:

Single Number: Menentukan baris di mana item akan ditempatkan. Ini setara dengan menentukan baik grid-row-start maupun grid-row-end dengan nilai yang sama.

Two Numbers: Menentukan grid-row-start dan grid-row-end secara terpisah.

Single Keyword: Menentukan kata kunci seperti span untuk menentukan jumlah baris yang akan ditempati oleh suatu item.

Two Keywords: Kombinasi dari dua kata kunci yang menentukan span untuk grid-row-start dan grid-row-end

## kode program
Html
```<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-row Example</title>
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
  grid-row: 1; /* Item dimulai dari baris ke-1 dan berakhir di baris ke-1 */
}

.item:nth-child(2) {
  grid-row: 2 / 4; /* Item dimulai dari baris ke-2 dan berakhir di baris ke-4 */
}

.item:nth-child(3) {
  grid-row: span 2; /* Item menempati 2 baris (sama dengan grid-row-start: span 2;) */
}

.item:nth-child(4) {
  grid-row: 3; /* Item dimulai dari baris ke-3 dan berakhir di baris ke-3 */
}

.item:nth-child(5) {
  grid-row: span 2 / 4; /* Item dimulai dari baris dengan tinggi 2 dan berakhir di baris ke-4 */
}

.item:nth-child(6) {
  grid-row: 3 / span 2; /* Item dimulai dari baris ke-3 dan menempati 2 baris ke depan */
}
```
## Hasil
![[6.jpg.jpg]]
