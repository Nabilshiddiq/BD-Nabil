## Penjelasan
Property grid-column-start
dalam CSS digunakan untuk menentukan awal dari suatu grid item di dalam grid container pada sumbu horizontal. Properti ini mengatur posisi awal grid item berdasarkan garis grid di sepanjang sumbu horizontal, dimulai dari garis pertama (1) hingga garis terakhir (tergantung dari jumlah kolom yang telah didefinisikan). Anda bisa menggunakan nilai numerik atau nama dari garis grid sebagai nilai dari properti ini. Misalnya, jika Anda ingin sebuah item grid dimulai dari garis kedua, Anda dapat menetapkan nilai grid-column-start: 2;


## kode program
Html

```<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Grid-column-start Example</title>
  <link rel="stylesheet" href="Grid-column-star.Css">
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

## Hasil

![[1.jpg.jpg]]
