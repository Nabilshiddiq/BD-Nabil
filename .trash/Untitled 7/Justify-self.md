## penjelasan
Property justify-self adalah bagian dari CSS Grid Layout Module yang digunakan untuk mengatur penempatan horizontal (justify) dari sebuah grid item di dalam sebuah grid cell. Property ini mengontrol posisi horizontal dari grid item di dalam sel grid yang dimilikinya.

Nilai yang dapat diberikan kepada justify-self antara lain:

start: Grid item akan diposisikan di sisi awal (kiri) dari sel grid yang dimilikinya.
end: Grid item akan diposisikan di sisi akhir (kanan) dari sel grid yang dimilikinya.
center: Grid item akan diposisikan di tengah-tengah secara horizontal di dalam sel grid yang dimilikinya.
stretch (default): Grid item akan meregang secara horizontal untuk mengisi sel grid yang dimilikinya.

## kode program
Html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Justify Self Example</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <div class="item item1">1</div>
    <div class="item item2">2</div>
    <div class="item item3">3</div>
    <div class="item item4">4</div>
  </div>
</body>
</html>
```
Css
```
.container {
  display: grid;
  grid-template-columns: repeat(2, 100px);
  grid-template-rows: repeat(2, 100px);
  gap: 10px;
}

.item {
  background-color: #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 24px;
}

.item1 {
  justify-self: start;
}

.item2 {
  justify-self: end;
}

.item3 {
  justify-self: center;
}

.item4 {
  /* menggunakan nilai default, yaitu stretch */
}
```
## hasil


![[8.jpg.jpg]]
