
# grid-column-start

## Penjelasan
Property grid-column-start
dalam CSS digunakan untuk menentukan awal dari suatu grid item di dalam grid container pada sumbu horizontal. Properti ini mengatur posisi awal grid item berdasarkan garis grid di sepanjang sumbu horizontal, dimulai dari garis pertama (1) hingga garis terakhir (tergantung dari jumlah kolom yang telah didefinisikan). Anda bisa menggunakan nilai numerik atau nama dari garis grid sebagai nilai dari properti ini. Misalnya, jika Anda ingin sebuah item grid dimulai dari garis kedua, Anda dapat menetapkan nilai grid-column-start: 2;


## kode program
Html

```html<html lang="en">
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
```css.container {
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


# grid-column-end

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

# grid-row-start
## penjelasan
Property `grid-row-start` digunakan dalam CSS Grid Layout untuk menentukan baris pertama tempat suatu item grid akan ditempatkan. Properti ini bekerja bersama dengan `grid-column-start` untuk menentukan posisi awal suatu item dalam grid.

Beberapa hal yang perlu diingat tentang `grid-row-start`:

1. **Nilai Angka**: Anda dapat menetapkan nilai angka untuk `grid-row-start`, yang menunjukkan nomor baris pertama di mana item akan ditempatkan.
    
2. **Keyword**: Selain nilai angka, Anda juga dapat menggunakan kata kunci seperti `span`, yang menentukan jumlah baris yang akan ditempati oleh suatu item.
    
3. **Menentukan Rentang Baris**: Anda juga bisa menggunakan `grid-row-start` untuk menentukan rentang baris di mana suatu item akan ditempatkan. Misalnya, `grid-row-start: span 2;` akan membuat item menempati dua baris.

## kode program
Html
```html<!DOCTYPE html>
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
```css.container {
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

# grid-row-end
## penjelasan
Property grid-row-end digunakan dalam CSS Grid Layout untuk menentukan baris terakhir tempat suatu item grid akan ditempatkan. Properti ini bekerja bersama dengan grid-row-start untuk menentukan rentang baris yang diinginkan untuk suatu item.

Beberapa hal yang perlu diingat tentang grid-row-end:

1.Nilai Angka: Anda dapat menetapkan nilai angka untuk grid-row-end, yang menunjukkan nomor baris terakhir di mana item akan ditempatkan.

2.Keyword: Selain nilai angka, Anda juga dapat menggunakan kata kunci seperti span, yang menentukan jumlah baris yang akan ditempati oleh suatu item.

3.Menentukan Rentang Baris: Anda juga bisa menggunakan grid-row-end untuk menentukan rentang baris di mana suatu item akan ditempatkan. Misalnya, grid-row-end: span 2; akan membuat item menempati dua baris.
## kode program
Html
```html<!DOCTYPE html>
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
```css.container {
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


# grid column
## penjelasan
Property grid-column adalah shorthand property dalam CSS Grid Layout yang digunakan untuk menentukan baik grid-column-start maupun grid-column-end secara bersamaan dalam satu aturan CSS. Ini memungkinkan untuk mengatur posisi horizontal suatu item dalam grid dengan lebih mudah.

Nilai yang diterima oleh grid-column bisa berupa:

Single Number: Menentukan kolom di mana item akan ditempatkan. Ini setara dengan menentukan baik grid-column-start maupun grid-column-end dengan nilai yang sama.

Two Numbers: Menentukan grid-column-start dan grid-column-end secara terpisah.

Single Keyword: Menentukan kata kunci seperti span untuk menentukan jumlah kolom yang akan ditempati oleh suatu item.

Two Keywords: Kombinasi dari dua kata kunci yang menentukan span untuk grid-column-start dan grid-column-end.

## kode program
Html
```html<!DOCTYPE html>
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
```css.container {
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

# grid row
## penjelasan
  Property grid-row adalah shorthand property dalam CSS Grid Layout yang digunakan untuk menentukan baik grid-row-start maupun grid-row-end secara bersamaan dalam satu aturan CSS. Ini memungkinkan untuk mengatur posisi vertikal suatu item dalam grid dengan lebih mudah.

Nilai yang diterima oleh grid-row bisa berupa:

Single Number: Menentukan baris di mana item akan ditempatkan. Ini setara dengan menentukan baik grid-row-start maupun grid-row-end dengan nilai yang sama.

Two Numbers: Menentukan grid-row-start dan grid-row-end secara terpisah.

Single Keyword: Menentukan kata kunci seperti span untuk menentukan jumlah baris yang akan ditempati oleh suatu item.

Two Keywords: Kombinasi dari dua kata kunci yang menentukan span untuk grid-row-start dan grid-row-end

## kode program
Html
```html<!DOCTYPE html>
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
```css.container {
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

# grid area
## penjelasan
Property grid-area adalah bagian dari CSS Grid Layout Module yang digunakan untuk menentukan letak dan ukuran dari sebuah grid item di dalam sebuah grid container. Property ini menggabungkan properti grid-row-start, grid-column-start, grid-row-end, dan grid-column-end menjadi satu deklarasi singkat.

Dengan menggunakan grid-area, kita dapat menentukan nama area yang akan diduduki oleh sebuah grid item di dalam grid container, sehingga memudahkan pengaturan layout secara lebih terstruktur dan mudah dibaca. 

## kode program
Html
```html
<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8"> <meta name="viewport" content="width=device-width, initial-scale=1.0"> <title>Grid Area Example</title> <link rel="stylesheet" href="styles.css"> </head> <body> <div class="container"> <div class="item1">1</div> <div class="item2">2</div> <div class="item3">3</div> <div class="item4">4</div> </div> </body> </html>
```
Css
```css
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


# justify-self
## penjelasan
Property justify-self adalah bagian dari CSS Grid Layout Module yang digunakan untuk mengatur penempatan horizontal (justify) dari sebuah grid item di dalam sebuah grid cell. Property ini mengontrol posisi horizontal dari grid item di dalam sel grid yang dimilikinya.

Nilai yang dapat diberikan kepada justify-self antara lain:

`start`: Grid item akan diposisikan di sisi awal (kiri) dari sel grid yang dimilikinya.
`end`: Grid item akan diposisikan di sisi akhir (kanan) dari sel grid yang dimilikinya.
`center`: Grid item akan diposisikan di tengah-tengah secara horizontal di dalam sel grid yang dimilikinya.
`stretch (default)`: Grid item akan meregang secara horizontal untuk mengisi sel grid yang dimilikinya.

## kode program
Html
```html
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
```css
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


# align-self
## penjelasan
Property align-self adalah bagian dari CSS Grid Layout Module yang digunakan untuk mengatur penempatan vertikal (align) dari sebuah grid item di dalam sebuah grid cell. Property ini mengontrol posisi vertikal dari grid item di dalam sel grid yang dimilikinya.

Nilai yang dapat diberikan kepada align-self antara lain:

start: Grid item akan diposisikan di sisi awal (atas) dari sel grid yang dimilikinya.
end: Grid item akan diposisikan di sisi akhir (bawah) dari sel grid yang dimilikinya.
center: Grid item akan diposisikan di tengah-tengah secara vertikal di dalam sel grid yang dimilikinya.
stretch (default): Grid item akan meregang secara vertikal untuk mengisi sel grid yang dimilikinya
## kode program
Html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Align Self Example</title>
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
```css
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
  align-self: start;
}

.item2 {
  align-self: end;
}

.item3 {
  align-self: center;
}

.item4 {
  /* menggunakan nilai default, yaitu stretch */
}
```
## hasil

![[9.jpg.jpg]]



# place-self
## penjelasan
Property place-self adalah singkatan dari kombinasi dua property CSS Grid Layout, yaitu align-self dan justify-self. Property ini digunakan untuk secara bersamaan mengatur penempatan vertikal dan horizontal dari sebuah grid item di dalam sebuah grid cell.

Nilai yang dapat diberikan kepada place-self mirip dengan nilai yang dapat diberikan kepada align-self dan justify-self. Beberapa nilai umumnya antara lain:

start start: Grid item akan diposisikan di sisi awal (atas dan kiri) dari sel grid yang dimilikinya.
end end: Grid item akan diposisikan di sisi akhir (bawah dan kanan) dari sel grid yang dimilikinya.
center center: Grid item akan diposisikan di tengah-tengah secara vertikal dan horizontal di dalam sel grid yang dimilikinya.
stretch stretch (default): Grid item akan meregang secara vertikal dan horizontal untuk mengisi sel grid yang dimilikinya.

## kode program
Html
```html
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
```css
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

