## penjelasan
Property `justify-items` dalam CSS Grid digunakan untuk mengatur cara elemen anak (child elements) dari sebuah grid kontainer akan diatur secara horizontal di dalam grid cell-nya.

Nilai-nilai yang dapat digunakan untuk property `justify-items` adalah:

- `start`: Menyebabkan elemen anak berada di awal grid cell secara horizontal.
- `end`: Menyebabkan elemen anak berada di akhir grid cell secara horizontal.
- `center`: Menyebabkan elemen anak berada di tengah grid cell secara horizontal.
- `stretch`: Membuat elemen anak memanjang untuk mengisi seluruh lebar grid cell secara horizontal.
- `auto`: Membuat elemen anak mengikuti perilaku default dari browser.

Contoh penggunaan:

cssCopy code

`.grid-container {   display: grid;   grid-template-columns: 100px 100px;   justify-items: center; }  .grid-item {   background-color: lightblue;   border: 1px solid black; }`

Dalam contoh di atas, property `justify-items: center` akan menyebabkan semua elemen anak di dalam `.grid-container` akan diatur secara horizontal di tengah grid cell-nya.

## Program Justify items
### Html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Grid justify-items</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>

<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
</div>

</body>
</html>
### Css
.grid-container {
  display: grid;
  grid-template-columns: 100px 100px;
  justify-items: center;
  gap: 10px;
}

.grid-item {
  background-color: lightblue;
  border: 1px solid black;
  padding: 10px;
  text-align: center;
}

## Hasil


![[IMG-20240403-WA0032.jpg]]
