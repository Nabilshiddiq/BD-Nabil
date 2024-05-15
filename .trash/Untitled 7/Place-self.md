## penjelasan
Property place-self adalah singkatan dari kombinasi dua property CSS Grid Layout, yaitu align-self dan justify-self. Property ini digunakan untuk secara bersamaan mengatur penempatan vertikal dan horizontal dari sebuah grid item di dalam sebuah grid cell.

Nilai yang dapat diberikan kepada place-self mirip dengan nilai yang dapat diberikan kepada align-self dan justify-self. Beberapa nilai umumnya antara lain:

start start: Grid item akan diposisikan di sisi awal (atas dan kiri) dari sel grid yang dimilikinya.
end end: Grid item akan diposisikan di sisi akhir (bawah dan kanan) dari sel grid yang dimilikinya.
center center: Grid item akan diposisikan di tengah-tengah secara vertikal dan horizontal di dalam sel grid yang dimilikinya.
stretch stretch (default): Grid item akan meregang secara vertikal dan horizontal untuk mengisi sel grid yang dimilikinya.

## kode program
Html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Place Self Example</title>
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
  place-self: start start;
}

.item2 {
  place-self: end end;
}

.item3 {
  place-self: center center;
}

.item4 {
  /* menggunakan nilai default, yaitu stretch stretch */
}
```

## Hasil

![[10.jpg.jpg]]
