
# Anatomi CSS
## Penjelasan
- `Selector`: Apa yang ingin di modifikasi
- `Property`: Bagian apa yang ingin dimodifikasi
- `Property value`: bentuk modifikasinya seperti apa
Contoh diatas, yang ingin di modifikasi adalah seluruh tag `<p>` pada komponen warna teksnya menjadi warna merah. 
- `p` merupakan selector yang dimana selector adalah sebuah penanda yang digunakan untuk memberikan tanda terhadap tag html yang ingin di modifikasi
- `color` merupakan property yang di mana property digunakan untuk menambahkan atau mengatur ukuran teks, jenis font, warna teks, warna background, dan sebagainya
- `red` adalah nilai dari property
**Kode**
```CSS

    p {
      color : red ; 
    }
```
**Hasil**
![gambar](asetCSS/PP.JPG)
**Penjelasan**
- `Selector`: Apa yang ingin di modifikasi
- `Property`: Bagian apa yang ingin dimodifikasi
- `Property value`: bentuk modifikasinya seperti apa
Contoh diatas, yang ingin di modifikasi adalah seluruh tag `<p>` pada komponen warna teksnya menjadi warna merah. 
Contoh lain, yang ingin dimodifikasi adalah seluruh jendela pada komponen kusennya menjadi terbuka. 
**Hasil**
![gambar](asetCSS/ACCS.JPG)

# Percobaan Pertama
## Penjelasan
- `<!DOCTYPE html>`: Mendefinisikan jenis dokumen HTML yang digunakan, dalam hal ini HTML5.
- `<html>`: Elemen utama yang memuat seluruh konten dokumen.
-  `<head>`: Bagian yang berisi informasi tambahan tentang dokumen, seperti judul dan link ke stylesheet eksternal.
- `<title>`: Menentukan judul halaman web yang akan ditampilkan di tab browser.
- `<style>`: Bagian di mana Anda dapat menambahkan aturan CSS untuk mengubah tampilan elemen HTML di halaman.
- `p { color: red; }`: Aturan CSS yang mengubah warna teks pada semua elemen `<p>` menjadi merah.
- `<body>`: Bagian yang berisi konten aktual halaman web, seperti teks, gambar, atau elemen lainnya.
- `<p>Welcome CSS</p>`: Elemen paragraf dengan teks "Welcome CSS", yang akan ditampilkan dengan warna merah karena aturan CSS yang telah ditentukan sebelumnya.
**Kode**
```HTMl
<!Doctype html>
<html>
  <head>
    <style> 
    p {
      color : red ; 
    }
    </style>
   </head>
   <body>
    <p> WELCOME CSS </p>
    <p> WELCOME CSS </p>
     </body>
</html>

```
### Hasil
![gambar](asetCSS/PP.JPG)
#  Percobaan Kedua
## Kode CSS
```
button{
Width:150px;
Height:50px;
Color: white;
text-align: right ;
margin-top :50px;
}
```
## Color
### Before
![gambar](asetCSS/WRN.JPG)
### After 

![gambar](asetCSS/WRN.W.jpg)Color adalah memberikan warna kepada tulisan yang dimana sebelum di kasih color atau warna tulisan nya berwarna hitam. setelah dikasih color atau warna tulisan klik aku berwarna putih
## TEXT-ALIGN

### Before
![gambar](asetCSS/WRN.jpg)
### After 

![gambar](asetCSS/RGHT.jpg)
Text-align adalah memberikan perataan kepada teks dimana saat kita menggunakan text-align = right  membuat posisi teks lebih ke samping kanan. 
## margin-top 
### Before
![Gambar](asetCSS/WRN.JPG)
### After

![gambar](asetCSS/MRGN.JPG)
Margin top digunakan untuk menentukan jarak antara batas atas suatu elemen dengan elemen di atasnya.

# Pemanggilan CSS
### Inline 
**Penjelasan**
Tag `<p>` yang memiliki gaya inline yang diterapkan langsung ke dalam elemen tersebut. Gaya tersebut adalah `font-size: 48px;`, yang berarti teks di dalam paragraf akan ditampilkan dengan ukuran font 48 piksel. Gaya ini diterapkan menggunakan atribut style pada elemen `<p>`.
```HTML
<!DOCTYPE html>
<html>
  <head>
    
  </head>
  <body>
    <p style="font-size: 48px;">Welcome CSS!</p>
    
  </body>
  
</html>

```
**Hasil**
![gambar](asetCSS/I.JPG)
### Internal
**Penjelasan**
- `h1`: Menetapkan warna teks biru dan margin atas sebesar `10000 pixel` untuk semua elemen `<h1>` dalam dokumen.
- `.merah`: Menetapkan warna teks merah untuk semua elemen yang memiliki kelas "merah".
- `.biru`: Menetapkan warna teks biru untuk semua elemen yang memiliki kelas "biru".
- `.kuning`: Menetapkan warna teks kuning untuk semua elemen yang memiliki kelas "kuning".
- `#hijau`: Menetapkan warna teks hijau untuk elemen dengan `ID "hijau"`.
- `.teks-besar`: Menetapkan ukuran font sebesar 60 piksel untuk semua elemen yang memiliki kelas "teks-besar".

```CSS
h1 {
  color : blue ;
  margin-top : 10000px ;


}

 .merah { 
  color : red ;
}

.biru{
  color : blue ;
}

.kuning{
  color : yellow ;
}

#hijau {
  color :green ;
}

.teks-besar{
  font-size :60px;
}
```
**Hasil**
![gambar](asetCSS/INC.JPG)
### External
**Penjelasan**
`<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
     </body>
  
</html>
```
**Hasil**
![gambar](asetCSS/E.JPG)
# Selektor CSS
### Elemen Selector 
**Penjelasan**
`h1`: Ini adalah elemen selector yang menargetkan semua elemen `<h1>` dalam dokumen HTML untuk menerapkan aturan gaya tertentu, seperti warna teks biru dan margin atas sebesar 10000 piksel.
**Code**
```HTML
<h1>Halo RPL 1</h1>
h1 {
  color: blue;
  margin-top: 10000px;
}


```
**Hasil**
![gambar](asetCSS/ES.JPG)
### Class Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- `<p class="biru"> ini warna biru </p>`: Elemen ini hanya memiliki satu kelas CSS, yaitu "biru". Oleh karena itu, elemen tersebut akan menerapkan gaya yang telah ditentukan untuk kelas "biru" dalam file CSS atau dalam bagian gaya internal/inline yang berkaitan dengan kelas tersebut. Dan memberikan warna biru. 

**Code**
```HTML
 <!DOCTYPE html>
 <html>
  <head>
    <title>CSS</title>
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    
    
    <p class="biru" >ini warna biru </p>
    
     </body>
  
</html>


```
**Hasil**
![gambar](asetCSS/BR.jpg) 



### ID Selector
**Penjelasan**
- `<!DOCTYPE html>`: Mendefinisikan tipe dokumen sebagai HTML versi 5. 
- `<html>`: Menandakan awal dan akhir dari dokumen HTML.
- `<head>`: Berisi informasi tambahan tentang dokumen HTML, seperti judul dan tautan ke file CSS.    
- `<title>CSS</title>`: Menentukan judul dokumen yang akan ditampilkan di tab browser.
- `<link rel="stylesheet" href="Style.CSS">`: Menautkan dokumen HTML dengan file CSS eksternal bernama "Style.CSS", sehingga dokumen HTML dapat menerapkan gaya yang didefinisikan dalam file CSS tersebut.
- `<body>`: Berisi konten yang akan ditampilkan kepada pengguna.  
- Elemen `<p id="hijau"> ini warna hijau </p>` memiliki atribut `id` yang menentukan identitas uniknya dalam dokumen HTML. Dengan demikian, fungsi dari atribut `id` ini adalah untuk memberikan cara yang unik untuk merujuk atau menargetkan elemen tersebut dalam CSS. Dan memberikan warna hijau pada teks. 
**Code**
```HTML
<!DOCTYPE html>
<html>
  <head>
    <title>CSS</title>
    
    <link rel="stylesheet" href="Style.CSS">
    
  </head>
  <body>
    <p style="font-size: 48px;">Welcome CSS!</p>
    <h1>Halo RPL 1</h1>
    
    <p id="hijau" > ini warna hijau </p>
  </body>
  
</html>

```
**Hasil**
![gambar](asetCSS/HJ.jpg)

# TEXT 

## Text align Left 
`text-align` dengan nilai `left` digunakan untuk mengatur teks agar tersusun sejajar dengan sisi kiri dari elemen tempat teks tersebut berada.
## Text align Right
`text-align` dengan nilai `right` digunakan untuk mengatur teks agar tersusun sejajar dengan sisi kanan dari elemen tempat teks tersebut berada. 
## Text justify
`text-align` dengan nilai `justify` digunakan untuk mengatur teks agar terlihat rata di kedua sisi (baik kiri maupun kanan) dari elemen tempat teks tersebut berada.
### Penjelasan
`text-align` dengan nilai `center` digunakan untuk mengatur teks agar terletak di tengah dari elemen tempat teks tersebut berada.berarti teks akan diatur agar berada di tengah secara horizontal dalam elemen tersebut, dengan ruang yang sama di sisi kiri dan kanan.
### Kode
```
 <p> selamat datang</p>
 p{
  text-align : center ;
  }
```
### Hasil
**Before**
![gambar](asetCSS/AC.JPG)
**After**
![gambar](asetCSS/BC.JPG)
### Kesimpulan
Selamat datang" yang terdapat dalam elemen `<p>` akan diatur menjadi rata tengah secara horizontal di dalam elemen tersebut, karena properti CSS text-align: center; diterapkan pada elemen `<p>`. 

## TEXT decoration
### None
`text-decoration: none`; digunakan untuk menghilangkan dekorasi teks, seperti garis bawah atau garis tengah. Ini berarti teks yang terdapat di dalam elemen tersebut tidak akan memiliki dekorasi tambahan seperti garis bawah, garis tengah, atau gaya lain yang biasanya ditampilkan secara default oleh browser.
### Overline
`Text-decoration: overline;`adalah properti CSS yang digunakan untuk menambahkan garis di atas teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis di atasnya.
### Line-throught
`Text-decoration: line-through`; adalah properti CSS yang digunakan untuk menambahkan garis tengah di tengah teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis yang melintasi di tengahnya.

### Penjelasan
`Text-decoration: underline`; adalah properti CSS yang digunakan untuk menambahkan garis di bawah teks. Ketika properti ini diterapkan pada sebuah elemen teks, teks tersebut akan memiliki garis di bawahnya.
### Code
```
text-decoration : underline;
```

### Hasil
**Before**
![gambar](asetCSS/AC.JPG)
**After**
![gambar](asetCSS/BU.JPG)
### Kesimpulan
Selamat datang" Dan Terima kasih yang terdapat dalam elemen `<p>` akan membuat tulisan mempunyai garis bawah di teks. karena properti CSS text-decoration : underline ; diterapkan pada elemen `<p>`. 

## Text-Transform
## Text-transform lowercase
`Text-transform: lowercase;` adalah properti CSS yang digunakan untuk mengubah teks menjadi huruf kecil (huruf kecil). Ketika properti ini diterapkan pada sebuah elemen teks, semua karakter huruf dalam teks tersebut akan diubah menjadi huruf kecil.
## text-transform capitalize
`Text-transform: capitalize`; adalah properti CSS yang digunakan untuk mengubah teks agar setiap kata dalam teks tersebut dimulai dengan huruf kapital. Ketika properti ini diterapkan pada sebuah elemen teks, huruf pertama dari setiap kata dalam teks tersebut akan diubah menjadi huruf kapital, sedangkan huruf lainnya akan tetap dalam format huruf kecil.
## text-transform none
`Text-transform: none;`adalah properti CSS yang mengembalikan teks ke format aslinya tanpa transformasi apapun. Ini berarti teks akan ditampilkan sesuai dengan format yang sudah ditulis dalam elemen HTML tanpa adanya perubahan pada huruf besar atau huruf kecilnya.

### Penjelasan
`Text-transform: uppercase;` adalah properti CSS yang digunakan untuk mengubah teks menjadi huruf besar (kapital). Ketika properti ini diterapkan pada sebuah elemen teks, semua karakter huruf dalam teks tersebut akan diubah menjadi huruf kapital.
### Kode
```
p{
  
  text-transform : uppercase ;
  
 }
```

### Hasil
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
teks yang ada di dalam elemen `<p>` akan diubah menjadi huruf kapital semua. Dengan menerapkan properti `text-transform: uppercase;`, semua huruf dalam teks tersebut akan diubah menjadi huruf besar (uppercase).

## Text-indent
`Text-indent` adalah properti CSS yang digunakan untuk mengatur jarak atau indentasi awal dari paragraf atau teks di dalam sebuah elemen
## Letter Spacing
Letter spacing adalah properti CSS yang digunakan untuk mengatur jarak antara karakter (huruf) dalam teks.
### Kode
```
.halaman-1{
       letter-spacing : 100 px ;
       }
```
### Hasil
**Before**
![gambar](asetCSS/BC.JPG)
**After**
![gambar](asetCSS/LT.JPG)
### Kesimpulan
teks di dalam elemen yang memiliki kelas "halaman-1" akan memiliki jarak antar huruf yang sangat besar. Dengan menerapkan properti letter-spacing: 100px;, spasi antara huruf-huruf dalam teks akan diperbesar menjadi 100 piksel.

## Line-height
Line height adalah properti CSS yang digunakan untuk mengatur tinggi baris di dalam sebuah elemen teks.

## Word Spacing
Word spacing adalah properti CSS yang digunakan untuk mengatur jarak antara kata-kata dalam teks

# Background
## Background-color
Background-color adalah properti CSS yang digunakan untuk mengatur warna latar belakang dari sebuah elemen HTML contoh warna aqua.

### Kode program
```
.halaman-1{
    
       Background-color :aqua ;
       }
```

### Hasil
**Before**
![gambar](asetCSS/BGH.JPG)**After**
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
`Background-color: aqua;`, di gunakan untuk membuat latar belakang dari elemen tersebut akan diubah menjadi warna aqua.

## Background-image
Background-image adalah properti CSS yang digunakan untuk menentukan gambar yang akan digunakan sebagai latar belakang dari sebuah elemen HTML.
### Kode Program
```
.halaman-1{
    
       background-image: url("Camera/F.png"); 
       }
```
### Hasil
**Before**
![gambar](asetCSS/BI.JPG)
### Kesimpulan
elemen yang memiliki kelas "halaman-1" akan memiliki gambar latar belakang yang ditentukan oleh URL "Camera/F.png".

## Background-repeat
Background-repeat adalah properti CSS yang digunakan untuk mengatur bagaimana gambar latar belakang akan diulang (repeated) jika ukuran gambar tersebut lebih kecil dari ukuran elemen yang ditetapkan.
## Background-attachment fixed
`background-attachment: fixed;` adalah properti CSS yang digunakan untuk mengontrol apakah gambar latar belakang akan tetap diam atau bergulir bersama konten saat pengguna menggulir halaman.
### Kode program
```
.halaman-1{
    
     background-attachment: fixed ;
       }
```

### Hasil

### Kesimpulan
elemen yang memiliki kelas "halaman-1" akan tetap diam relatif terhadap jendela browser.
## Background-Size
Background-size adalah properti CSS yang digunakan untuk mengatur ukuran dari gambar latar belakang sebuah elemen HTML.
### Kode Program
```
.halaman-1{
    
     background-size: 100%;
       }
```
### Hasil

### Kesimpulan
properti `background-size: 100%;`, ukuran gambar latar belakang akan diatur sedemikian rupa sehingga seluruh area latar belakang elemen tersebut tercakup oleh gambar tersebut.
## Background-Posetion
Background-position adalah properti CSS yang digunakan untuk menentukan posisi awal atau titik referensi dari gambar latar belakang yang diterapkan pada sebuah elemen HTML.
### Kode program
```
.halaman-1{
    
     background-position: 50px;
       }

```

### Hasil

### Kesimpulan
properti `background-position: 50px;`, gambar latar belakang akan dimulai dari posisi 50 piksel dari sisi kiri elemen tersebut dan tetap berada di posisi vertikal tengah secara default.

# Font
## Font Size
Font-size adalah properti CSS yang digunakan untuk mengatur ukuran font teks dalam sebuah elemen HTML.

### Kode Program
```
.halaman-1{
    
     font-size : 100px;
       }
```
### Hasil

### Kesimpulan
properti font-size: 100px;, ukuran font dalam elemen tersebut akan diperbesar menjadi 100 piksel.
## Font-style italic
Font-style adalah properti CSS yang digunakan untuk menentukan gaya huruf (font style) dari sebuah teks.
italic: Menampilkan teks dalam gaya miring (italic), jika font tersebut mendukung.
### Kode program
```
.halaman-1{
    
     font-style: italic ;
       }
```

### Hasil
**After**
![gambar](asetCSS/FI.JPG)
**Before**
![gambar](asetCSS/BUP.JPG)
### Kesimpulan
properti `font-style: italic;`, teks dalam elemen tersebut akan ditampilkan dengan gaya huruf miring.

## Font-weight Bold
`font-weight: bold;` dalam CSS, teks dalam elemen yang diberi aturan tersebut akan ditampilkan dengan ketebalan huruf yang lebih tebal dari biasanya. 
### Kode program
```
.halaman-1{
    
     font-weight: bold ;
       }
    

```
### Hasil

### Kesimpulan
`font-weight: bold;`, teks dalam elemen tersebut akan memiliki gaya huruf tebal.

## Font-family justify
`Font-family justify`properti ini mengatur teks agar rata di kedua sisi, sehingga ruang antara kata-kata disesuaikan untuk mengisi seluruh lebar elemen dengan cara yang seragam. 

# Box Model
## Border-Width
`Border-wkdth`digunakan untuk menentukan lebar border dari sebuah elemen.

## Border-style solid
`border-style: solid;` adalah properti CSS yang mengatur gaya border menjadi garis lurus dan solid.
### Kode program
```
img{
   ​​​​border-style: solid;
    }
```
### Hasil
![gambar](asetCSS/BSS.JPG)
### Kesimpulan
`border-style: solid;` adalah properti CSS yang mengatur gaya border menjadi garis lurus dan solid.

## Border-color orangered
`border-color: orangered`; adalah properti CSS yang mengatur warna border dari sebuah elemen menjadi oranye merah (orangered). 
## Kode program
```
.F{
      border-color: orangered;
      }
```
## Hasil 
**Before**
![gambar](asetCSS/BCO.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
Mengatur warna atau memberikan warna orangered pada pinggiran  border 
# Padding
## Padding-left
`padding-left` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kiri konten dalam sebuah elemen. 
### Kode Program
```
F{
    
    padding-left: 29px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PL.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian kiri sebesar 29 piksel.  Dan membuat tulisan klik disini tidak terlalu ke kiri. 
## Padding-bottom
`padding-bottom` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian bawah konten dalam sebuah elemen. 
### Kode Program
```
.F{

    padding-bottom: 25px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PB.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
 elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian bawah sebesar 25 piksel.  Dan membuat tulisan klik disini tidak terlalu ke bawah. 
## Padding-Right
`padding-right` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kanan konten dalam sebuah elemen. 
### Kode Program
```
.F{
    
    padding-right: 29px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PR.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian kanan sebesar 29 piksel.  Dan membuat tulisan klik disini tidak terlalu ke kanan. 
## Padding-top
`padding-top`adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian atas konten dalam sebuah elemen.
### Kode program
```

.F{
    
    padding-top: 20px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/PT.JPG)
**After**
![gambar](asetCSS/BBCO.JPG)
### Kesimpulan
elemen HTML yang memiliki kelas "F" akan memiliki ruang tambahan di bagian atasnya sebesar 20 piksel.  Dan membuat tulisan klik disini tidak terlalu ke atas. 
# Margin
## Margin-Left
`margin-left`adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kiri dari sebuah elemen terhadap elemen lain di sekitarnya. 
### Kode Program
```
img{
    
    margin-left: 600px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/ML.JPG)
**After**
![gambar](asetCSS/AML.JPG)
## Margin-Top
`margin-top` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian atas dari sebuah elemen terhadap elemen lain di atasnya.
### Kode Program
```
img{
    
    margin-top: 50px;
    }
```
### Hasil
**Before**
![gambar](asetCSS/MT.JPG)

**After**
![gambar](asetCSS/AML.JPG)
### Kesimpulan
atura gaya ini memengaruhi tata letak (layout) elemen-elemen HTML dengan tag "F" dengan menambahkan margin di bagian atas sebesar 60 piksel.
## Margin-Right
`margin-right` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di sebelah kanan dari sebuah elemen terhadap elemen lain di sekitarnya.
### Kode program
```
F{
    
    margin-right: 60px;
    }
```
### Hasil

![gambar](asetCSS/AML.JPG)
### Kesimpulan
elemen-elemen HTML dengan tag "F" akan memiliki jarak atau spasi tambahan sebesar 60 piksel di sebelah kanan. 
## Margin-Bottom
`margin-bottom` adalah properti CSS yang digunakan untuk menentukan jarak atau ruang tambahan di bagian bawah dari sebuah elemen terhadap elemen lain di bawahnya. 

### Kode program
```
.F{

    Margin-bottom: 90px
}

```
### Hasil
**Before**
![gambar](asetCSS/MB.JPG)
**After**
![gambar](asetCSS/AML.JPG)
### Kesimpulan
elemen-elemen yang memiliki kelas "F" akan memiliki jarak atau spasi sebesar 90 piksel di bagian bawahnya.
# Pseudo-classes

##  Hover
- `button:hover`: adalah pseudo-class selector yang menargetkan tombol (button) ketika pengguna mengarahkan kursor ke atasnya (hover) atau diklik. 
- `background-color: red;`: Properti ini menetapkan warna latar belakang tombol menjadi merah ketika tombol sedang di-hover.
- `color: white;`: Properti ini menetapkan warna teks pada tombol menjadi putih ketika tombol di-hover.
- `height: 100px;`: Properti yang digunakan untuk membuat  tinggi (height) tombol menjadi 100 piksel ketika tombol di-hover.
- `width: 100px;`: Properti yang digunakan untuk membuat lebar (width) tombol menjadi 100 piksel ketika tombol di-hover.
### Kode program
```
button:hover{
  background-color:red;
  color:white;
  height:100px;
  
  width:100px;

}
```
### Hasil
![gambar](asetCSS/PA.JPG)
### Kesimpulan
Setiap property memberikan perubahan yang berbeda dari hover akan memberikan perubahan saat di klik, width dan height untuk mengatur lebar dan tinggi, background-color red memberikan warna merah ketika diklik, dan color white digunakan untuk memberikan warna putih pada teks. 

## Active
`button:active`: adalah pseudo-class selector yang menargetkan tombol (`button`) ketika tombol tersebut sedang dalam keadaan "active", atau tombol sedang ditekan. 
`color: yellow;`: Properti memberikan warna kuning pada teks ketika tombol sedang active atau tombol sedang ditekan. 
### Kode program
```
button:active{
  color: yellow ;
}
```
### Hasil
![gambar](asetCSS/PAK.JPG)
### Kesimpulan
Teks klik akan berganti warna menjadi kuning jika ditekan dan berputar. 

# Transition 
### Penjelasan
+ `Transition`:  untuk mengatur pertunjukan perubahan, mengubah penampilan elemen dari satu keadaan ke keadaan lain, memberikan dinamika visual yang menarik dalam desain web Anda.
+ `Transition-delay`: properti ini memberikan momen kejutan atau antisipasi sebelum perubahan yang dijanjikan terjadi, menambah dramatisasi pada tampilan elemen.
- `Transition-duration`: menentukan lamanya waktu ketika elemen berubah, memungkinkan Anda untuk mengatur seberapa lama penonton (pengguna) menikmati perubahan tersebut.
- `Transition-property`: menentukan apa yang akan berubah, seperti warna, ukuran, atau posisi, menciptakan efek transisi yang beragam dan menarik.
- `Transition-timing-function`:  properti ini mengatur ritme perubahan, menentukan apakah transisi akan bergerak dengan lembut dan halus seperti aliran air, atau tiba-tiba dan dramatis seperti petir yang menyambar.
### Kode program
```
button:hover{
  
  transition:all 0.9s ease-in;
  
}
```

# Transform 
### Penjelasan
- `transform: scale(0.5);`= Mengubah ukuran elemen menjadi setengah dari ukuran aslinya.
- `transform: scalex(0.5);`= Hanya mengubah skala elemen secara horizontal menjadi setengah dari ukuran aslinya.
- `transform: rotate(45deg);`= Memutar elemen sebesar 45 derajat searah jarum jam.
- `transform: skewX(-25deg);`= Membengkokkan elemen secara horizontal sebesar -25 derajat (ke arah kiri).
- `transform: skew(25deg,5deg);`= Membengkokkan elemen sebesar 25 derajat secara horizontal (ke kanan) dan 5 derajat secara vertikal (ke atas).
- `transform: translate(50px,52px);`= Menggeser elemen sebesar 50 piksel ke kanan dan 52 piksel ke bawah.
- `transform: matrix(0.7,-0.5,0.5,0.4,0.5,0.7);`= Menggambarkan transformasi menggunakan matriks 2D den
### Kode Program
```
button:active{
  
  transform:matrix(0.7,-0.5,0.5,0.4,0.5,0.7);
  }
```
### Hasil
![gambar](asetCSS/TRANS.JPG)

### Kesimpulan
Setiap properti transform mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 

# Flexbox 
## Flex Container
### Display Flex
`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya dengan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan lain-lain.

### Kesimpulan
`display: flex`, kita dapat dengan mudah mengatur tata letak elemen-elemen di dalamnya menggunakan properti-properti seperti `flex-direction`, `justify-content`, `align-items`, dan properti lainnya yang terkait dengan model tata letak flexbox.


### Flex-Direction
- `flex-direction: column;`: Mengatur tata letak dari flex container menjadi vertikal, sehingga flex items diatur dari atas ke bawah.
- `flex-direction: column-reverse;`: Mengatur tata letak dari flex container menjadi vertikal terbalik, sehingga flex items diatur dari bawah ke atas.
- `flex-direction: row;`: Mengatur tata letak dari flex container menjadi horizontal, sehingga flex items diatur dari kiri ke kanan.
- `flex-direction: row-reverse;`: Mengatur tata letak dari flex container menjadi horizontal terbalik, sehingga flex items diatur dari kanan ke kiri.
### Kode Program
```
.box-container{
  
  flex-direction: column;
  
}
```
## Hasil
![gambar](asetCSS/JCY.JPG)
### Kesimpulan
Setiap properti flex-direction mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`column` untuk tata letak vertikal dari atas ke bawah.
`column-reverse` untuk tata letak vertikal terbalik dari bawah ke atas. `row` untuk tata letak horizontal dari kiri ke kanan.`row-reverse` untuk tata letak horizontal terbalik dari kanan ke kiri.
### Align-Items
- `align-items: center;`: Flex items akan diatur di tengah-tengah sumbu silang dari flex container.
- `align-items: flex-start;`: Flex items akan diatur pada awal sumbu silang dari flex container.
- `align-items: flex-end;`: Flex items akan diatur pada akhir sumbu silang dari flex container.
- `align-items: baseline;`: Flex items akan diatur sedemikian rupa sehingga garis dasar dari teks pada masing-masing item berada pada level yang sama.
- `align-items: stretch;`: Flex items akan diperpanjang untuk mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.
### Kode Program
```
.box-container{
  
  align-items:center ;
  
}
```
### Hasil
![gambar](asetCSS/FIY.JPG)
### Kesimpulan
Setiap properti align-items mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`center` untuk menempatkan flex items di tengah-tengah sumbu silang.`flex-start` untuk menempatkan flex items di awal sumbu silang.`flex-end` untuk menempatkan flex items di akhir sumbu silang.`baseline` untuk menempatkan flex items sehingga garis dasar teks masing-masing item berada pada level yang sama.`stretch` untuk memperpanjang flex items sehingga mencapai tinggi maksimal flex container, mengisi ruang kosong di sepanjang sumbu silang.
### Justify-Content
 - `justify-content: flex-start;`: Mengatur fleks item ditempatkan di bagian awal (mulai) dari sumbu utama flex container.
- `justify-content: flex-end;`: Mengatur fleks item ditempatkan di bagian akhir (akhir) dari sumbu utama flex container.
- `justify-content: center;`: Mengatur fleks item ditempatkan di tengah-tengah sumbu utama flex container.
- `justify-content: space-around;`: Mengatur fleks item didistribusikan secara merata di sekitar sumbu utama flex container, dengan ruang yang sama di antara mereka.
- `justify-content: space-between;`: Mengatur fleks item didistribusikan secara merata di sepanjang sumbu utama flex container, dengan ruang yang sama di antara fleks item pertama dan terakhir, tetapi tidak ada ruang di antara fleks item yang berdekatan.
### Kode Program
```
.box-container{
  
  justify-content: center ;
}
```
### Hasil
![Gambar](asetCSS/JCY.JPG)

### Kesimpulan
Setiap properti justify-Content mengubah tampilan elemen dengan cara yang berbeda-beda sesuai dengan property. 
Contoh`flex-start` untuk menempatkan flex items di awal (mulai) sumbu utama.`flex-end` untuk menempatkan flex items di akhir (akhir) sumbu utama.`center` untuk menempatkan flex items di tengah-tengah sumbu utama.`space-around` untuk mendistribusikan flex items secara merata di sekitar sumbu utama dengan ruang yang sama di antara mereka.`space-between` untuk mendistribusikan flex items secara merata di sepanjang sumbu utama dengan ruang yang sama di antara flex items pertama dan terakhir, tetapi tidak ada ruang di antara flex items yang berdekatan.

## Flex Items

### Penjelasan HTML
- Tag `<DOCTYPE html>` memberitahu web bahwa dokumen HTML adalah versi 5
- Tag pembuka `<html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`
- Tag pembuka `<head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>` ,biasanya dalam tag head terdapat tag `<title>` untuk memberikan informasi judul halaman HTML
- Apapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil di web browser.
- `<title>`: Menentukan judul halaman.
- `<link rel="stylesheet" href="Tugassbox.css">`: Menghubungkan dokumen dengan stylesheet eksternal.
- `<body class="main-container">`: Memulai konten utama halaman dengan kelas "main-container".
- `<div class="hero-container">`: Kontainer utama untuk semua konten.
- `<div class="box-container">`: Kontainer untuk setiap kotak konten.
- `<h1 class="item box-item-1">Selamat Datang</h1>`: Teks "Selamat Datang" dengan kelas "item" dan "box-item-1".
- `<h1 class="item box-item-2">di <b>Web Fadhil</b></h1>`: Teks "di Web Fadhil" dengan kelas "item" dan "box-item-2", kata "Web Fadhil" ditebalkan.
- `<div class="item box-item-3">`: Kontainer untuk tombol "Klik disini" dengan kelas "item" dan "box-item-3".
- `<button class="F">Klik disini</button>`: Tombol dengan teks "Klik disini" dan kelas "F".
- `<div class="item-box">`: Kontainer untuk gambar.
- `<img src="camera/F.png">`: Gambar "F.png" dari direktori "camera".
## Penjelasan CSS
- `body`: Mengatur latar belakang seluruh halaman menjadi warna ungu (purple).
- `.main-container`: Memberikan latar belakang warna ungu (purple) pada elemen dengan kelas "main-container". Ini mungkin digunakan sebagai wadah utama untuk konten.
- `.box-item-1 dan .box-item-2`: Mengatur tampilan teks pada elemen-elemen dengan kelas "box-item-1" dan "box-item-2". Ini termasuk mengatur ukuran font menjadi 50px, warna putih, dan memberikan jarak atas sejauh 10px.
- `.F:hover`: Mengatur tampilan tombol dengan kelas "F" saat kursor berada di atasnya (hover). Saat tombol di-hover, ukurannya diperbesar, warna dan border berubah, dan posisinya digeser ke kiri dengan transisi animasi selama 0.9 detik.
- `button:active`: Memberikan efek transformasi rotasi sebesar 45 derajat pada tombol ketika tombol sedang aktif (ditekan).
- `img`: Mengatur tampilan gambar dengan lebar dan tinggi masing-masing 250px, dengan sudut melingkar sebesar 200px, serta menetapkan margin kiri sejauh 400px dan margin atas sejauh -400px. Hal ini dapat mempengaruhi posisi dan tata letak gambar dalam halaman.

### Kode Program
```HTML
<!DOCTYPE html>
<html>
<head>
    <title>Belajar CSS3</title>
    <link rel="stylesheet" href="Tugassbox.css">
</head>
<body class="main-container">
    <div class="hero-container">
    <div class="box-container">
    <h1 class="item box-item-1">
    Selamat Datang
    </h1>
    
    <h1 class="item box-item-2">
    di <b>Web Fadhil</b>
    </h1>
    <div class="item box-item-3">
    <button class="F">Klik disini</button>
    </div>
    </div>
    
    <div class="box-container">
    <div class="item-box">
    <img src="camera/F.png">
    </div>
        </div>
    </div>
</body>
</html>

```

```CSS
body{
  background-color:purple;
}
.main-container {
    background-color: purple;
}
.box-item-1{
    font-size: 50px;
    color: white;
    margin-top:10px;
    }
.box-item-2{
   font-size: 50px;
    color: white;
    margin-top:10px;
}

.F:hover {
    background-color: purple;
    margin-left:200px;
    padding-left:29px;
    padding-top:20px;
    padding-bottom:25px;
    padding-right:29px;
    color: orangered;
    border-color:orangered;
    margin-top: 50px; 
    margin-right:60px;
    margin-bottom:90px;
   transition:all 0.9s ease-in; 
}
 button:active{ 
  transform:rotate(45deg);
  }
img{
    width: 250px;
    height: 250px;
    border-radius: 200px;
    border-color: white;
    border-style: solid;
    margin-left: 400px;
    margin-top: -400px;
}

```
### Hasil
![gambar](asetCSS/TCSS.JPG)

# Position
## Position Relative
### Penjelasan
- `background-color: aqua;`: Memberikan warna latar belakang elemen menjadi aqua. 
- `position: relative;`: Menetapkan posisi elemen relatif terhadap posisi defaultnya. 
- `top: 20px;`: Menggeser elemen 20 piksel ke bawah dari posisi defaultnya.
- `left: 30px;`: Menggeser elemen 30 piksel ke kanan dari posisi defaultnya. 
### Kode Program
```
box-1{
  background-color:aqua;
  position:relative;
  top:20px;
  left:30px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PRBA.JPG)
### Kesimpulan
elemen dengan kelas "box-1" mengatur latar belakang menjadi warna aqua dan menggeser elemen 20 piksel ke bawah dan 30 piksel ke kanan dari posisi defaultnya.
## Position Absolute
### Penjelasan

- `background-color: purple;`: Mengatur latar belakang elemen menjadi warna ungu (purple).
- `position: absolute;`: Menetapkan elemen ke dalam konteks posisi yang dihitung relatif terhadap elemen induk yang memiliki posisi non-static. 
- `top: 15px;`: . elemen 15 piksel dari atas relatif terhadap posisi elemen induk yang ditetapkan dalam konteks posisi absolut.
- `left: 10px;`: Menggeser elemen 10 piksel dari kiri relatif terhadap posisi elemen induk yang ditetapkan dalam konteks posisi absolut.
### Kode Program
```
.box-2{
  background-color:purple;
  position:absolute;
  top:15px;
  left:10px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PAP.JPG)
### Kesimpulan
kelas "box-2" menetapkan latar belakangnya menjadi warna ungu (purple) dan mengatur posisinya secara absolut,dimana elemen digeser 15 piksel dari atas dan 10 piksel dari kiri.

## Position Fixed
### Penjelasan
- `top: 50px;`: Menggeser elemen 50 piksel ke bawah dari posisi defaultnya.
- `left: 30px;`: Menggeser elemen 55 piksel ke kanan dari posisi defaultnya. 
- `background-color: aqua;`: Mengatur latar belakang elemen menjadi warna aqua.
- `position: fixed;`: Mengatur elemen dalam posisi tetap, yang berarti elemen akan tetap berada pada lokasi yang sama saat kita scroll. 
### Kode Program
```
box-1{
  background-color:aqua;
  position:Fixed;
  top:50px;
  left:55px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PF.JPG)
### Kesimpulan
position: fixed, elemen akan tetap berada pada posisinya yang ditentukan jika discrool.properti top dan left digunakan untuk menentukan jarak elemen dari tepi atas dan kiri. 

## Position Sticky
### Penjelasan
- `background-color: aqua;`: Mengatur latar belakang elemen menjadi warna aqua.
- `Position: sticky;`: Mengatur elemen dalam posisi "sticky", yang berarti elemen akan berperilaku seperti posisi relatif sampai mencapai posisi tertentu saat discrool kemudian akan tetap berada di tempat.elemen akan "melekat" pada posisi yang telah ditentukan saat jarak scroll mencapai nilai tertentu.
 - `top: 50px;`: Menggeser elemen sejauh 50 piksel dari atas elemen induk yang memiliki posisi tetap.
- `left: 55px;`: Menggeser elemen sejauh 55 piksel dari sisi kiri elemen induk yang memiliki posisi tetap.
### Kode Program
```
box-1{
  background-color:aqua;
  position:Sticky;
  top:50px;
  left:55px; 
}
```
### Hasil 
**BEFORE**
![gambar](asetCSS/P.JPG)
**AFTER**
![gambar](asetCSS/PS.JPG)
### Kesimpulan
`position: sticky`, elemen akan seperti posisi relatif sampai jarak scroll mencapai nilai tertentu. elemen akan tetap berada pada posisi yang telah ditentukan saat jarak scroll mencapai nilai tertentu, sambil tetap mengikuti pergeseran scroll di bawahnya.

#  Bootstrap
## Apa Itu Bootstrap?
Bootstrap adalah salah satu dari banyak framework front-end yang ada di web development. Framework-front end menyediakan serangkaian alat dan gaya bawaan untuk mempercepat proses pengembangan web dengan menyediakan komponen-komponen UI siap pakai dan sistem grid yang responsif. Bootstrap khususnya, terkenal dengan kemampuannya dalam menciptakan tata letak yang responsif dan komponen-komponen UI yang seragam.
## Instalasi Bootstrap
## Cara instalasi Bootstrap secara online / CDN.
sekarang kita akan menjelaskan bagaimana cara menginstall bootstrap secara online. Berikut langkah-langkahnya:

1. Masuklah ke website resmi Bootstrap dengan mengunjungi situs web resmi di https://getbootstrap.com/.
2. Di laman utama web Bootstrap, cari dan klik menu "Introduction" yang terletak pada sisi sebelah kiri website.
3. Pada bagian "Starter Template" di halaman Introduction, kita akan melihat kode yang dapat kita gunakan untuk menghubungkan website kita yang mau diterapkan Bootstrap.
4. Klik tombol "Copy" untuk menyalin seluruh kode tersebut.
5. Buatlah file baru dengan nama index.html atau nama yang kita inginkan menggunakan teks editor atau editor HTML yang kita biasa pakai.
6. Tempelkan(paste) kode yang telah kita salin dari langkah sebelumnya ke dalam file html yang baru kita buat. dengan menempelkan kode tersebut maka bootstrap kita sudah terhubung namun harus secara online.
7. kita dapat mulai memberikan gaya pada tag-tag atau elemen dalam file HTML tersebut dengan menggunakan kelas-kelas Bootstrap. kita dapat melihatnya pada website resmi Bootstrap untuk mempelajari lebih lanjut tentang kelas-kelas yang tersedia dan cara penggunaannya.
8. Untuk melihat hasilnya, buka file html tadi menggunakan web browser kita.
9. Halaman web yang ditampilkan akan menggunakan Bootstrap untuk gaya dan fungsionalitasnya

## Mengunduh dan menginstal Bootstrap secara lokal.
Untuk menginstal Bootstrap secara offline, kita perlu mengunduh file Bootstrap dan menyimpannya di folder proyek kita. Berikut adalah langkah-langkah untuk menginstal Bootstrap secara offline:
1. **Unduh File Bootstrap:** Kunjungi situs web resmi Bootstrap di https://getbootstrap.com/ dan cari tautan unduhan untuk versi Bootstrap yang diinginkan. Klik atau ikuti instruksi untuk mengunduh file ZIP Bootstrap.
2. **Ekstrak File Bootstrap:** Setelah mengunduh file ZIP Bootstrap, temukan file tersebut di komputer kita dan ekstrak isi file ZIP ke folder proyek kita. kita dapat menggunakan aplikasi pengarsipan file atau ekstraksi bawaan (Archiver, 7zip, dll) pada sistem operasi kita untuk mengekstrak file ZIP . Setelah diekstrak, kita akan memiliki folder Bootstrap yang berisi berkas-berkas Bootstrap yang diperlukan.
3. **Hubungkan Berkas Bootstrap pada Halaman HTML:** Buka file HTML proyek kita menggunakan teks editor atau editor HTML yang biasa kita gunakan. Di dalam tag pada halaman HTML , tambahkan tautan ke berkas CSS Bootstrap dan skrip JavaScript Bootstrap. Gunakan tag link di dalam tag head untuk tautan CSS dan tag script di dalam tag body untuk javascript. Berikut contoh tautan yang umum di bootstrap:
```html
<link href="path/to/bootstrap.min.css" rel="stylesheet">
// tautan bootstrap CSS
<script src="path/to/bootstrap.bundle.min.js"></script>
// tautan bootstrap Javascript
```
dengan menuliskan script diatas, maka kita telah menghubungkan antara file html kita dengan bootstrap yang kita unduh tadi.
4. **Gunakan Kelas Bootstrap:** Setelah tautan Bootstrap ditambahkan, Kita dapat menggunakan kelas-kelas Bootstrap dalam elemen HTML proyek Kita untuk menerapkan gaya dan fungsionalitas yang disediakan oleh bootstrap kita. Kita dapat masuk ke web resmi Bootstrap untuk mempelajari lebih lanjut tentang kelaskelas yang tersedia dan cara penggunaannya.
5. **Jalankan File HTML:** Setelah Kita selesai menghbungkan tautan dan menggunakan kelas Bootstrap, Kita dapat menjalankan halaman HTML kita di web browser Kita untuk melihat hasilnya. Buka file HTML menggunakan web browser Kita dan lihat hasilnya
## Komponen-Komponen Bootstrap
Bootstrap menyediakan berbagai komponen yang siap pakai untuk membangun tampilan website yang responsif dan menarik. Berikut adalah beberapa komponen utama yang disediakan oleh Bootstrap:
## Grid System
Grid system Bootstrap adalah sistem layout yang responsif dan fleksibel. kita dapat membagi halaman menjadi baris(rows) dan kolom(columns) yang membentuk grid. Grid terdiri dari 12 kolom, yang dapat kita susun sesuai kebutuhan. Dengan menggunakan kelas CSS yang disediakan oleh Bootstrap, kita dapat dengan mudah menentukan berapa banyak kolom yang akan digunakan oleh setiap elemen di halaman web kita. Grid system ini sangat berguna dalam menciptakan tata letak yang responsif dan dapat menyesuaikan diri dengan berbagai ukuran layar
## Typography
Komponen typography Bootstrap menyediakan gaya dan kelas CSS yang konsisten untuk tipografi di halaman web kita. kita dapat dengan mudah mengatur ukuran teks, gaya huruf, dan pengaturan lainnya menggunakan kelas-kelas yang telah ditentukan. Ini memastikan bahwa teks di halaman web kita memiliki tampilan yang konsisten dan mudah dibaca di berbagai perangkat.
## Button
Komponen tombol Bootstrap memungkinkan kita dengan mudah membuat tombol dengan tampilan yang menarik dan responsif. kita dapat menggunakan kelas-kelas Bootstrap untuk mengatur berbagai gaya tombol, termasuk ukuran (large, small), warna (default, primary, secondary, dll.), dan variasi lainnya. Tombol-tombol ini dapat digunakan untuk tindakan seperti mengirim formulir, memuat ulang halaman, atau memicu tindakan lainnya di aplikasi web kita.
## Forms
Bootstrap menyediakan komponen form yang mudah digunakan untuk membuat form input. Ini termasuk input teks, area teks, kotak centang (checkbox), tombol radio, dropdown, dan lain-lain. Komponen form Bootstrap telah dirancang dengan tampilan yang responsif dan mudah dikustomisasi. kita dapat dengan mudah menambahkan validasi form dan mengatur tampilan form kita dengan menggunakan kelas-kelas Bootstrap yang telah ditentukan.
## Navbar
Komponen navbar Bootstrap memungkinkan kita membuat navigasi yang responsif dan mudah dikustomisasi di halaman web. kita dapat menambahkan logo, menu, tombol, dan komponen lainnya ke navbar dengan mudah. Navbar Bootstrap juga menyediakan fitur seperti menu dropdown, navigasi yang terlipat untuk perangkat mobile, dan tata letak yang fleksibel.
## Cards
Cards adalah komponen yang digunakan untuk menampilkan informasi dalam format yang terstruktur. Komponen kartu Bootstrap memungkinkan kita untuk membuat kolom dengan gambar, teks, tombol, dan komponen lainnya. cards ini dapat digunakan untuk menampilkan artikel, produk, profil pengguna, atau konten lainnya dengan tampilan yang menarik.
## Modal
Komponen modal Bootstrap digunakan untuk menampilkan jendela pop-up yang tumpang tindih dengan konten utama halaman. Modal ini berfungsi untuk menyoroti konten tambahan, pesan, atau form yang membutuhkan fokus pengguna. kita dapat menyesuaikan tampilan modal, mengatur ukuran, menambahkan judul, dan mengatur perilaku saat modal ditampilkan atau ditutup.
## Carousel
Carousel adalah komponen Bootstrap yang digunakan untuk membuat tampilan slide gambar atau konten lainnya. kita dapat menambahkan gambar, teks, tombol navigasi, dan indikator slide untuk membuat tampilan yang menarik dan interaktif. Carousel Bootstrap mendukung navigasi otomatis, kontrol manual, dan animasi transisi yang halus.
## Icons
Bootstrap sendiri menggunakan ikon dari Font Awesome, yang merupakan kumpulan ikon vektor yang sangat populer dan kaya akan fitur. kita dapat dengan mudah menambahkan ikon ke elemen seperti tombol, tautan, dan elemen lainnya menggunakan class-class ikon Bootstrap. Ini berfungsi untuk memperindah halaman web kita.
## Jumbotron
Jumbotron adalah komponen Bootstrap yang digunakan untuk menyoroti konten utama di halaman web. Biasanya ditempatkan di bagian atas halaman dengan judul besar danTerima kasih atas klarifikasinya.Komponen carousel Bootstrap digunakan untuk membuat tampilan slide yang interaktif. kita dapat menambahkan gambar, teks, dan tombol navigasi ke dalam carousel. Carousel Bootstrap mendukung navigasi otomatis, kontrol manual, dan animasi transisi. 

kita dapat menemukan daftar komponen lengkap dan dokumentasi resmi di situs web Bootstrap (https://getbootstrap.com/docs/).
## Contoh Penerapan Komponen Bootstrap
## Typography
1. Buka situs resmi Bootstrap di [getboostrap.com](getbootstrap.com)
	![[btc-1.png]]
2. Klik "Read the docs". Maka kita akan diarahkan pada halaman web yang berisi berbagai macam Typografi (class Bootstrap).
	![[btc-2.png]]
3. Misalnya kita akan membuat sebuah teks quotes seperti di bawah ini:
	![[btc-3.png]]
4. Ketikan "Typography" di kolom search lalu enter. Maka kita akan masuk ke halaman berikut:
	![[btc-4.png]]
5. Carilah Subbab "Alignment":
	![[btc-5.png]]
6. Salinlah kode yang tertera, lalu tempelkan di tag body pada halaman html yang telah kita hubungkan dengan Bootstrap kita
```html
<figure class="text-center">
<blockquote class="blockquote">
<p>A well-known quote, contained in a blockquote element.</p>
</blockquote>
<figcaption class="blockquote-footer">
Someone famous in 
<cite title="Source Title">Source Title </cite>
</figcaption>
</figure>
```
![btc-6.png](btc-6.png)
7. Hasilnya akan terlihat seperti berikut:
	![[btc-7.png]]
8. Kita bisa mengganti kata kata nya dengan cara mengganti teks yang ada di dalam tag p dan untuk teks kecil bagian bawah kita ganti pada bagian dalam tag figcaption
```html
<figure class="text-center">
  <blockquote class="blockquote">
    <p>Sebenarnya otak kita sama aja, yang <br>
    membedakan hanya siapa yang <br>
    mulai belajar duluan dan siapa yang <br>
    belajar terus menerus </p>
  </blockquote>
  <figcaption class="blockquote-footer">
    Dea Afrizal Doroboka<cite title="Source Title">Doroboka</cite>
  </figcaption>
</figure>
```
Hasilnya adalah sebagai berikut:
![[btc-8.png]]
*Keterangan :*
1. ==`text-center`== pada ==`<figure>`==: Kelas ini diterapkan pada elemen ==`<figure>`== , yang mengakibatkan kontennya, termasuk elemen ==`<blockquote>`== dan ==`<figcaption>`== , akan diatur menjadi ketengah halaman maupun kontainer.
2. blockquote pada ==`<blockquote>`== : Kelas ini memberikan gaya khusus pada elemen ==`<blockquote>`== . Elemen ini digunakan untuk merinci sebuah kutipan atau teks yang dianggap signifikan. Penggunaan kelas ini dari Bootstrap mungkin memberikan tampilan tertentu, seperti memodifikasi gaya margin atau padding, untuk memberikan estetika yang lebih baik.
3. blockquote-footer pada ==`<figcaption>`== : Kelas ini memberikan gaya khusus pada elemen ==`<figcaption>`== yang berada di dalam ==`<figure>`== . Elemen ini kemungkinan berisi informasi tambahan atau keterangan terkait elemen-elemen lain dalam ==`<figure>`==.
	- **`Dea Afrizal Doroboka`**: Ini adalah teks yang berada di dalam elemen ==`<figcaption>`==, memberikan informasi tambahan atau keterangan terkait dengan kutipan atau elemen-elemen lain dalam ==`<figure>`==.
	-  **`<cite title="Source Title">Doroboka / cite>`**: Ini adalah elemen ==`<cite>`== yang memberikan judul sumber ("Source Title"). Penggunaan kelas `blockquote-footer` dari Bootstrap mungkin menyusun elemen ini dengan tata letak dan gaya tertentu, seperti menetapkannya sebagai teks kaki atau memberikan gaya yang konsisten dengan elemen lain dalam kelompok ==`<figure>`==.
*Keterangan*: 
Untuk bagian "Dea Afrizal" adalah nama seseorang yang mengatakan quotes tersebut dan "Doroboka" adalah sumber dimana orang tersebut mengatakn kata-kata itu. Kata- kata yang dituliskan yaitu berada dalam tag ==`p`== .
## Navbar
1. Bukalah Kembali [getbootstrap.com](getbootstrap.com) lalu ketik "navbar" dikolom "search" dan klik enter
	![[btc-15.png]]
2. Carilah jenis navbar yang diinginkan.
	![[btc-16.png]]
3. Jika misalnya kita telah menemukan jenis navbar yang kita inginkan, maka, salinlah kode program yang ada dibawah gambar contoh navbar tersebut
	![[btc-17.png]]
```html
<nav class="navbar navbar-expand-lg bg-body-tertiary">
    <div class="container-fluid">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link" href="#">Pricing</a>
                </li>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                        Dropdown link
                    </a>
                    <ul class="dropdown-menu">
                        <li><a class="dropdown-item" href="#">Action</a></li>
                        <li><a class="dropdown-item" href="#">Another action</a></li>
                        <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                </li>
            </ul>
        </div>
    </div>
</nav>

```
4. Tempelkanlah kode program yang terlah kita salin ke dalam tag body di file html kita. Jangan lupa untuk menautkan file html kita dengan bootstrap seperti pada langkah-langkah sebelumnya
	![[btc-18.png]]
5. Jalankanlah file html yang sudah ditempeli kode program bootstrap tadi melalui web browser. Maka lihatlah hasilnya
	![[btc-19.png]]
6. Misalnya kita ingin memberikan warna hijau pada background navbar kita. Pertama ketiklah "background" di kolom search
	![[btc-20.png]]
7. Carilah Warna yang kita inginkan. Misalnya dalam praktek ini adalah warna hijau
	![[btc-21.png]]
	![[btc-22.png]]
	Terdapat banyak jenis warna dalam bootstrap.
8. Karena kita ingin mengkostumisasi warna background kita menjadi hijau maka kita akan memakai bg-succes . ketikkan bg-succes pada class tag pembuka seperti di bawah ini
	![[btc-23.png]]
	*Keterangan*:
	Karena kita akan memberikan warna background pada navbar maka untuk menerapkannya, langsung terapkan class tag yang membungkus semua eleme-elemen yang ada pada tag tersebut.
9. Jika sudah maka hasilnya akan seperti ini:
	![[btc-24.png]]
10. Sekarang kita akan mengubah warna font yang ada pada navbar. Langkah pertama klik "Colors" pada bagian Utilities
	![[btc-25.png]]
11. Maka kita akan diarahkan pada halaman yang memuat berbagai macam warna font
	![[btc-26.png]]
12. Carilah warna font yang kita inginkan. Misalnya pada kostumisasi navbar ini. Kita akan menggunakan warna font putih
	![[btc-27.png]]
13. Karena kita ingin menggunakan warna font putih maka perintah yang digunakan adalah "text-white"
14. Masuklah kembali ke dalam file html kita
15. pada bagian class sebuah tag yang membungkus text yang akan kita ganti warna, ketiklah text-white . Contohny ada pada gambar berikut:
	![[btc-28.png]]
16. Hasilnya akan terlihat seperti di gambar ini:
	![[btc-29.png]]
17. Terapkanlah Text-White diseluruh class pada tag yang membungkus text-text itu seperti halnya pada text navbar tadi
	![[btc-30.png]]
18. Jika file html dijalankan, hasilnya adalah sebagai berikut
	![[btc-31.png]]
19. Sekarang kita akan mengganti text yang ada di navbar tersebut. Caranya sangat mudah, yaitu cukup kita ganti text-text tadi dengan kata kata yang kita inginkan. Misalnya adalah sebagai berikut:
	![[btc-32.png]]
20. Maka hasilnya adalah sebagai berikut:
	![[btc-33.png]]
21. Sekarang kita akan menambahkan kolom search pada navbar kita. pada bagian navbar di [getbootstrap.com](getbootstrap.com) Scroll ke bawah hingga menemukan seperti pada gambar
	![[btc-34.png]]
22. Salin kodenya lalu tempelkan di bagian bawah kode navbar kita tadi. Jadi jangan disatukan ke dalam kode navbar tadi.
```html
<nav class="navbar bg-body-tertiary">
    <div class="container-fluid">
        <form class="d-flex" role="search">
            <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
            <button class="btn btn-outline-success" type="submit">Search</button>
        </form>
    </div>
</nav>
```
![[btc-35.png]]

*Keterangan*:
1. ==`navbar`== : Kelas ini menunjukkan bahwa elemen ==`<nav>`== adalah bagian dari komponen navbar. Navbar adalah bagian dari Bootstrap yang menyediakan navigasi di bagian atas halaman web. Dengan memberikan kelas navbar , kita memberitahu Bootstrap untuk menerapkan gaya dan tata letak khusus yang terkait dengan navigasi.
2. ==`bg-body-tertiary`== : Kelas ini memberikan warna latar belakang pada navbar. Dalam hal ini, warna latar belakangnya diberi warna sesuai dengan warna "hijau" Warna latar belakang ini dapat disesuaikan sesuai kebutuhan desain.
3. ==`container-fluid`== : Kelas ini diterapkan pada elemen ==`<div>`== yang membungkus elemen-elemen dalam navbar. Kelas ini memberikan padding yang sesuai dan membuat elemen-elemen di dalamnya menjaga lebar penuh dari layar (menggunakan grid system Bootstrap). Dengan kata lain, kontennya akan merespons secara baik pada berbagai lebar perangkat.
4. ==`d-flex`== : Kelas ini mengubah elemen ==`<form>`== menjadi kontainer flex. Flexbox adalah teknik tata letak yang kuat di CSS yang memudahkan pengaturan dan penataan elemen dalam satu atau dua dimensi. Dengan memberikan kelas d-flex , elemen form dan anak-anaknya dapat disusun secara fleksibel.
5. ==`form-control`== : Kelas ini diterapkan pada elemen ==`<input>`== untuk memberikan gaya yang konsisten pada elemen formulir. Di sini, elemen input diberi gaya Bootstrap standar untuk mengubahnya menjadi kontrol formulir yang responsif dan berada dalam baris yang sesuai.
6. ==`me-2`== : Ini adalah kelas Bootstrap yang memberikan margin kanan sebesar 2 pada elemen yang memilikinya. Dalam codingan ini, kelas ini diterapkan pada elemen input untuk memberikan jarak margin kanan.
7. ==`btn`== dan ==`btn-outline-success`== : Kelas ini memberikan gaya pada elemen ==`<button>`== . Kelas btn mengindikasikan bahwa ini adalah elemen tombol Bootstrap, sedangkan btn-outline-success memberikan gaya tombol dengan warna tepi hijau ("success" dalam Bootstrap).
8. ==`type="submit"`== pada tombol: Ini menentukan bahwa tombol tersebut bertindak sebagai tombol submit dalam formulir. Ketika ditekan, formulir akan dikirim.
9. Maka hasilnya adalah seperti berikut:
	![[btc-36.png]]
10. Untuk membuat agar navbar tersebut terlihat menyatu, berikan background-color yang sama pada navbar diatasnya, yaitu menggunakan kode bg-succes . Letakkan di class tag yang membungkus seluruh elemen search tadi.
	![[btc-37.png]]
11. Maka hasil yang muncul akan seperti ini
	![[btc-38.png]]
## Buttons
Pada praktek sebelumnya kita sudah mengatur navbar dan juga menambahkan kolom search. Namun ada masalah dengan tombolnya. Karena tombolnya memiliki warna yang sama dengan warna background yang digunakan yaitu hijau, Maka tombol tersebut tidak terlihat akibat warnanya menyatu. Pada bagian kali kita akan membahas cara mengatur sebuah tombol di bootstrap. Berikut caranya:

1. Permasalahan tadi ialah background color tombolnya yang menyatu dengan warna backgriund navbarnya. Untuk mengatur warna tombol, pertama di situs getbootstrap.com, carilah bagian "buttons" di Components
	![[btc-39.png]]
2. Jika sudah menemukan klik bagian tersebut, maka kita akan diarahkan pada bagian buttons seperti pada gambar
	![[btc-40.png]]
3. Scroll lah ke bawah hingga menemukan bagian "Outlines Buttons"
	![[btc-41.png]]
4. Saat ini kita akan menggunakan jenis warna putih agar tidak lagi menyatu dengan warna background nava

#Grid For Responsive Web/Layouting
Bootstrap memiliki sistem tata letak yang kuat yang bernama grid. Grid berguna untuk membuat tata letak yang responsif di halaman web kita. Sistem grid Bootstrap berdasarkan konsep kolom yang dapat diatur dalam baris. Berikut adalah beberapa hal penting yang perlu kita ketahui tentang grid dan layouting di Bootstrap:

1. **KONTAINER (Container)**
	Grid Bootstrap harus ditempatkan dalam elemen kontainer. Terdapat dua jenis kontainer yang tersedia, yaitu .container dan .container-fluid. .container memiliki lebar terbatas dan akan disesuaikan dengan lebar layar. .container ini digunakan ketika kita ingin membuat tata letak yang terpusat dan terbatas pada lebar tertentu. .container-fluid memiliki lebar penuh dan akan mengisi seluruh lebar layar. Kontainer ini digunakan ketika kita ingin membuat tata letak yang menyesuaikan dengan lebar layar penuh.
2. **BARIS (Row)**
	Baris digunakan untuk mengelompokkan kolom-kolom dalam tata letak. kita dapat menambahkan class .row pada elemen yang berfungsi sebagai wadah kolom. Baris ini akan memastikan bahwa kolom-kolom di dalamnya akan diatur secara horizontal.
3. **KOLOM (Column):**
	Kolom adalah bagian dasar dari sistem grid Bootstrap. Kolom- kolom ditempatkan di dalam baris dan digunakan untuk membagi horizontal ruang dalam grid. Setiap baris dipecah menjadi 12 kolom, yang dapat kita bagi sesuai kebutuhan.

	**Catatan**: kita dapat menggunakan kelas seperti .col- , .col-sm- , .col-md- , .col-lg- , atau .col-xl- untuk menentukan bagaimana kolom akan berperilaku di berbagai ukuran perangkat. Misalnya, .col-sm-6 akan membuat kolom tersebut memiliki lebar setengah dari baris pada ukuran layar kecil. kita dapat menggabungkan kelas kolom untuk ukuran layar yang berbeda untuk menciptakan tata letak yang responsif. Misalnya, .col-md-6 .col-lg-4 akan membuat kolom tersebut memiliki lebar setengah dari baris pada ukuran layar medium, dan memiliki lebar sepertiga dari baris pada ukuran layar besar.
4. **OFFSET**
	Kita dapat menggunakan kelas offset untuk memindahkan kolom ke samping. Misalnya, .offset-md-2 akan memindahkan kolom 2 satuan ke kanan pada layar dengan ukuran medium. Offset digunakan ketika Kita ingin membuat ruang kosong di antara kolom-kolom.
5. **Perilaku pada Ukuran Layar yang Berbeda**
	Kita dapat menggunakan kelas-kelas grid Bootstrap yang berbeda untuk mengontrol tampilan kolom pada ukuran layar yang berbeda. Misalnya, Kita dapat menggunakan .colsm- untuk ukuran layar kecil, .col-md- untuk ukuran layar medium, dan sebagainya. Dengan cara ini, Kita dapat membuat tata letak yang responsif untuk berbagai perangkat.
6. **NESTING**
	Nesting memungkinkan Kita menempatkan baris dan kolom di dalam kolom lainnya. Dengan cara ini, Kita dapat membuat tata letak yang lebih kompleks dengan komponen-komponen yang terkait. Misalnya, Kita dapat menempatkan sebuah baris di dalam kolom yang ada di dalam baris lainnya
7. **ORDER**
	Kita dapat menggunakan kelas .order- untuk mengubah urutan kolom pada ukuran layar tertentu. Misalnya, .order-first akan memindahkan kolom ke posisi pertama, dan .orderlast akan memindahkan kolom ke posisi terakhir. Dengan menggunakan kelas ini, Kita dapat mengatur ulang urutan kolom untuk mencapai tata letak yang diinginkan pada berbagai ukuran layar.

Itu adalah beberapa konsep penting dalam sistem grid Bootstrap. Dengan menggunakan sistem grid ini, kita dapat membuat tata letak yang responsif dan menyesuaikan tampilan elemen-elemen pada berbagai ukuran layar dengan mudah.
## Contoh Penggunaan dan Penjelasannya
Sekarang kita akan mencoba penggunaan grid yang dengan bantuan Bootstrap. Berikut langkah-langkahnya:

1. Masuklah kembali ke web getbootstrap.com.
	![[btc-52.png]]
2. carilah "Grid" di Kolom search lalu klik enter. Maka kita akan diarahkan pada halaman web yang berisi tentang grid.
	![[btc-53.png]]
3. Carilah layout atau tata letak grid yang kita inginkan. Misalnya pada praktek kali ini, kita akan menggunakan layout "Row columns".
	![[btc-54.png]]
4. Salinlah kode program yang terletak di kode bawah contohnya.
```html
<div class="container text-center">
    <div class="row row-cols-2">
        <div class="col">Column</div>
        <div class="col">Column</div>
        <div class="col">Column</div>
        <div class="col">Column</div>
    </div>
</div>
```
5. Tempelah pada file html yang tentunya telah dihubungkan dengan tautan bootstrap, baik secara offline maupun online.
	![[btc-55.png]]
6. Maka hasilnya akan seperti berikut:
	![[btc-56.png]]
	*Keterangan:*
	Jadi tulisan "Column" adalah isi konten yang sudah teratur dalam grid ini. kita bisa mengganti "konten" ini dengan konten yang kita inginkan
7. Untuk mengganti kontennya hapuslah tulisan "Column" lalu gantilah dengan kontent yang kita inginkan.
