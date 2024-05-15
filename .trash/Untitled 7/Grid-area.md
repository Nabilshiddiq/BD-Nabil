## Penjelasan
Property grid-area adalah bagian dari CSS Grid Layout Module yang digunakan untuk menentukan letak dan ukuran dari sebuah grid item di dalam sebuah grid container. Property ini menggabungkan properti grid-row-start, grid-column-start, grid-row-end, dan grid-column-end menjadi satu deklarasi singkat.

Dengan menggunakan grid-area, kita dapat menentukan nama area yang akan diduduki oleh sebuah grid item di dalam grid container, sehingga memudahkan pengaturan layout secara lebih terstruktur dan mudah dibaca. 

## kode program
Html
```
<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Grid Area Example</title> <link rel="stylesheet" href="styles.css"> </head> <body> <div class="container"> <div class="item1">1</div> <div class="item2">2</div> <div class="item3">3</div> <div class="item4">4</div> </div> </body> </html>
```
Css
```
.container {
  display: grid;
  grid-template-columns: 100px 100px;
  grid-template-rows: 100px 100px;
  gap: 10px;
}

.item1 {
  grid-area: 1 / 1 / 2 / 3;
}

.item2 {
  grid-area: 1 / 2 / 3 / 3;
}

.item3 {
  grid-area: 2 / 1 / 3 / 2;
}

.item4 {
  grid-area: 2 / 2 / 3 / 3;
}

/* Styling untuk visualisasi */
.container > div {
  background-color: #ccc;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 24px;
}
```
## Hasil

![[7.jpg.jpg]]
