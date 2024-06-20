# Pengenalan Web
## Sejarah
Sejarah ==web development== yaitu pada tahun 1990-an seorang insinyur bernama tim barnestly dia nyetir suatu konsep yg memungkinkan sebuah dokumen bisa terhubung satu sama lain melalui internet.
Protokol http yg menjadi jembatan antara server dan client untuk saling mengirim data bisa disebut perantara/jembatan.
Karena data yg dikirim berupa teks mentah akan lebih mudah membaca dokumen yang diformat makanya dia ciptain html untuk teks jadi lebih rapi dan lebih bertekstur.
file html akan dianggap sebagai satu halaman atau satu tubuh setiap halaman akan dimulai dengan teks.
html ini kayak ganti background atau ganti ukurannya tapi semakin banyak tag dan stylingnya di html tersebut semakin berantakan juga kode yang kita buat.
Pada tahun 1994 diciptakanlah ==CSS== oleh pak Hakon Wiyung Lee tujuannya agar tapi dan struktur htmlnya terpisah dan jadi lebih mudah untuk dipertahankan.
Di ==CSS== kita bisa hias misalkan teks ingin Menganti warnanya dan backgroundnya atau gambar yg ingin memper besar ukurannya bisa style di ==CSS==.

**Kesimpulan** :Web development pada tahun 1990-an seorang insinyur bernama tim barnes lee dia nyetir suatu konsep dokumen bisa terhubung satu sama lain melalui internet.Protokol http yg menjadi jembatan antara server dan client untuk saling mengirim data.Karena data yg dikirim berupa teks mentah makanya dia ciptain html untuk teks jadi lebih rapi dan lebih bertekstur.jika html banyak tag dan stylingnya maka semakin berantakan kodenya, diciptakanlah CSS pada tahun 1994 oleh pak Hakon Wiyung Lee agar struktur htmlnya terpisah dan mudah, di CSS kita bisa menghias program kita misal ingin menganti warna teks atau backgroundnya dan gambar.

# Deskripsi Gambar
![Aaa](Asettt/Aaa.png)
Di atas ==HTML== bagaikan kerangka rumah yg belum mempunyai hiasan apapun.
Di atas ==CSS== rumahnya sudah memiliki hiasan seperti sudah mempunyai seng, cerobong asap, jendela dan cet berwarna.
Di atas ==JAVASCRIPT== rumahnya ada sebuah interaksi seperti cerobong asap yg mengeluarkan asap dikarenakan memasak maupun membakar kayu, di jendela terlihat ada cahaya dikarenakan didalam rumah itu menyalakan lampu pakai saklar dan pintu yg tertutup dikarenakan pintu itu bisa dibuka dan ditutup.
#  Belajar HTML
## Struktur Dasar HTML 
Struktur dasar HTML adalah kerangka dasar yang digunakan untuk membuat halaman web.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  
  <body>
    <p>No Body</p>
  </body>
</html>
```

**Hasil**:
![hasil_html](Asettt/Dasar.png)

**Penjelasan**:
- Tag `<!DOCTYPE html>` memberitahukan web browser bahwa dokumen HTML adalah versi 5.
- Tag pembuka `<html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`.
- Tag pembuka `<head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>`, biasanya dalam tag head terdapat tag `<titel>` untuk memberikan informasi judul halam HTML.
- apapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil di web browser.
## Anatomi Elemen HTML
Anatomi elemen HTML terdiri dari tag pembuka, tag penutup, dan konten

**Contoh**:
```html
<a href="https://www.google.com">Klik Goggle</a>
```

**Hasil**:
![A|250x500](Asettt/A.jpg)

**Penjelasan**:
- Tag pembuka `<a>` tag yang menandakan awalan dan `</a>` akhir URL/link.
-  atribut `href` digunakan untuk menentukan halaman web URL/link. Contoh nilai atribut https://www.google.com.
- isi konten itu untuk masuk ke URL/link yang sudah kita buat di atribut `href` yaitu "klik google"
### Tag Pembuka dan Tag Penutup
Tag pembuka dan tag penutup adalah dua bagian dari suatu elemen dalam HTML yang digunakan untuk menentukan awal dan akhir dari elemen tersebut. Tag pembuka dimulai dengan nama elemen yang diapit oleh tanda kurung sudut ("<" dan ">"). Tag penutup serupa dengan tag pembuka, tetapi memiliki karakter garis miring tambahan ("/") sebelum nama elemennya. contoh ini, `<p>` adalah tag pembuka, dan `</p>` adalah tag penutup
### Atribut Tag
Atribut tag merujuk pada informasi tambahan yang diberikan kepada elemen HTML untuk memberikan rincian atau pengaturan tertentu. Atribut dapat ditambahkan ke sebagian besar tag HTML dan berfungsi untuk mengontrol perilaku atau tampilan elemen tersebut. Contohnya, pada tag `<a>` (hipertaut), atribut `href` digunakan untuk menentukan URL tujuan. Begitu juga, pada tag `<img>`(gambar), atribut src menunjukkan sumber gambar. 
### Isi/Konten Tag
Isi atau konten tag merujuk pada teks, elemen, atau informasi yang ditempatkan di antara tag pembuka dan tag penutup dalam markup HTML. Contoh sederhana adalah tag paragraf `<p>`, di mana isi tag tersebut adalah teks yang ingin dimuat dalam paragraf. Contoh "Ini adalah contoh isi atau konten dalam tag paragraf." adalah isi atau konten yang akan ditampilkan atau diinterpretasikan oleh browser web ketika halaman HTML di-render.
## Tag Dasar
### Heading
Heading (judul) dalam HTML digunakan untuk menandai tingkatan atau level judul pada halaman web.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  
  <body>
    <h1>kata kata hari ini</h1>
    <h2>word of the day</h2>
    <h3>今日の単語</h3>
    <h4>ك4لمة اليوم</h>
    <h5>Từ trong ngày</h5>
    <h6>오늘의 단어</h6>
  </body>
</html>
```

**Hasil**:
![H1-H6](Asettt/H1-H6.png)

**Penjelasan**:
- Tag `<h1>` Digunakan untuk judul utama atau level judul tertinggi
- Tag `<h2>` Menunjukkan tingkatan judul yang lebih rendah dari `<h1>` atau subjudul
- Tag `<h3>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h2>`
- Tag `<h4>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h3>`
- Tag `<h5>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h4>`
- Tag `<h6>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h5>` 
### Paragraf
Paragraf adalah unit terkecil dalam penulisan yang terdiri dari satu atau lebih kalimat.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  
  <body>
    <p>nama saya</p>
    <br>
    <p><b>kelas saya</b></p>
    <hr>
    <p><u>No Body</u></p>
    <p><i>tidak ada yang tahu</i></p>
  </body>
</html>
```

**Hasil**:
![p_b_u_i_br_hr|](Asettt/Paragraf.png)

**Penjelasan**:
- Tag `<p>`digunakan untuk menandai paragraf pada halaman web dan di akhiri `</p>`. Ini memberikan jarak antara paragraf.
- Tag `<b>` digunakan untuk membuat teks menjadi tebal (bold) dan di akhiri `</b>`.
- Tag `<u>` digunakan untuk memberi garis bawah pada teks dan di akhiri `</u>`. 
- Tag `<i>` digunakan untuk membuat teks menjadi miring (italic) dan di akhiri `</i>`.
- Tag `<br>` digunakan untuk membuat jeda baris atau perpindahan ke baris berikutnya tanpa membuat paragraf baru.
- Tag `<hr>` digunakan untuk membuat garis horizontal, yang sering digunakan pemisah visual di antara bagian-bagian pada halaman web.
### Atribut Align
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <p align="right">orang yg belum tahu</p>
    <p align="center">orang berbakat tidak pernah gagal</p>
    <p align="left">orang yg sudah tahu</p>
  </body>
</html>
```
![Align|250x500](Asettt/Align.jpg)
- Atribut `align="right"` Teks dalam paragraf ini akan diatur agar terletak di sebelah kanan.
- Atribut `align="center"` Teks dalam paragraf ini akan diatur agar berada di tengah.
- Atribut `align="left"` Teks dalam paragraf ini akan diatur agar berada di sebelah kiri.
### Komentar
Komentar dalam konteks pemrograman adalah catatan atau informasi tambahan yang ditambahkan ke dalam kode sumber untuk memberikan pemahaman lebih lanjut kepada pembaca atau programmer lainnya. 

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <!--ini komentar, tidak akan tampil di browser -->
    <p>ini bukan komentar, dan akan tampil di browser</p>
  </body>
</html>
```

**Hasil**:
![komentar|250x500](Asettt/Komentar.jpg)

**Penjelasan**:
- untuk membuat komentar di HTML menggunakan awalan `<!--` dan akhiran `-->`. Komentar ini tidak akan ditampilkan di browser dan digunakan untuk menyisipkan catatan atau keterangan yang hanya ditujukan bagi pengembang.
### List
List adalah struktur data yang digunakan dalam pemrograman untuk menyimpan sejumlah elemen atau nilai secara terurut.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <ul>List Tidak Berurut
      <li>sapu</li>
      <li>meja</li>
      <li>papan tulis</li>
      <li>kipas</li>
    </ul>
    <ol>List Berurut
      <li>Abd Rahman</li>
      <li>Ahmad Anugrah</li>
      <li>Ahsan</li>
    </ol>
  </body>
</html>
```

**Hasil**:
![List|250x500](Asettt/List.jpg)

**Penjelasan**:
- Tag `<ul>` (Unorderet List) digunakan untuk mendefinisikan awal dari daftar tak berurut dan diakhiri `</ul>`.
- Tag `<Li>` daftar atau list item, bisa digunakan dalam kombinasi tag `<ul>` dan `<ol>` di akhiri `</Li>`.
- Tag `<ol>` (Onderet List) digunakan untuk mendefinisikan awal dari daftar berurut dan di akhiri `</ol>`.
### Link
Link, atau tautan, adalah elemen dalam teks atau dokumen yang merujuk atau mengarahkan ke lokasi lain, baik dalam dokumen yang sama maupun dokumen terpisah.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <a href="https://www.google.com" target="_blank">Klik disini untuk ke google</a>
    <br>
     <a href="Belajar_JS.html">Klik disini untuk ke halaman lain yang saya buat</a>
  </body>
</html>
```

**Hasil**:
![Link|250x500](Asettt/Link.jpg)

**Penjelasan**:
- Tag pembuka `<a>` tag yang menandakan awalan dan `</a>` akhir URL/link.
-  atribut `href` digunakan untuk menentukan halaman web URL/link. Contoh nilai atribut https://www.google.com.
- isi konten itu untuk masuk ke URL/link yang sudah kita buat di atribut `href` yaitu "klik google".kita juga bisa masuk ke halaman lain yg kita buat.
Link dapat ditemukan di hampir semua balaman web. Link/tautan memungkinkan sebuah teks yang ketika di klik akan pindah ke haleman lainnya. HTML menggunakan tag ``<a>``untuk kepeduan ini. Link ditulis dengan ``<a>``yang merupakan singkatan card anchor (jangkar).
### Multimedia
#### Gambar
Gambar adalah representasi visual dari objek, scene, atau informasi.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <img src="Agis.jpg" alt="Logo" width="200" height="250">
  </body>
</html>
```

**Hasil**:
![img1|250x500](Asettt/Foto.jpg)
**File gambar**:
![img2](Asettt/File.png)
**Penjelasan**:
Dalam HTML, gambar didefinisikan dengan tag ing) Tag <ing adalah tag kosong. hanya berisi atribut saja, dan tidak memiliki tag penutup.

==Atribut src setidaknya mesti ada dalam tag ini untuk menentukan URL (alamat web) dari gambar yang ingin ditampilkan.==

Atribut alt menyediakan teks alternatif untuk gambar, jika pengguna karena beberapa alasan tidak dapat melihatnya (karena koneksi lambat, kesalahan pada atribut are, atau jika web browser telah disetting untuk tidak menampilkan gambar). Jika browser tidak dapat menemukan gambar, maka akan muncul nilai pada atribut

Dalam tag ``<img>`` terdapat juga atribut width dan height untuk mengatur ukuran gambar, pada versi HTML5 standar satuan ukuran gambar adalah pixel.

- Misalnya dalam folder root terdapat file gambar bernama logo.png. Untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut src, contohnya src="logo.png"
- Untuk menampilkan gambar dari internet carilah link gambar yang akan ditampilkan lalu masukkan dalam nilai atribut src, contohnya https://namasitus.com/gambar.png.
#### Video
Video adalah representasi visual dan audio yang bergerak, biasanya disajikan dalam format digital.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <video controls width="250px" height="125px">
      <source src="split.mp4" type="video/mp4">
    </video>
  </body>
</html>
```

**Hasil**:
![Video1](Asettt/Video1.png)

**File Video**:
![video2](Asettt/Video2.png)

**Penjelasan**:
dalam HTML, video didefinisikan dengan tag `<video>`, tag `<video>` adalah tag yang digunakan untuk memasukkan video kedalam web, di tag `<video>` terdapat tag khusus yang dimana tag ini tidak memiliki tag penutup yaitu `<source>` yang Digunakan untuk menyediakan beberapa sumber video dan memberi browser pilihan format yang sesuai.

Dalam tag `<video>` terdapat juga atribut   `controls` yang digunakan untuk Menambahkan kontrol pemutaran standar seperti play, pause, dan volume, dan juga di tag `<video>` ada atribut `width` dan `height` yang digunakan untuk mengatur ukuran video, pada versi HTML 5 standar satuan ukuran video adalah pixel, dan juga di dalam nya juga terdapat atribut `type` yang di gunakan untuk menentukan tipe MIME (Multipurpose Internet Mail Extensions) dari file video yang disematkan.

misalnya dalam folder root terdapat file video bernama video.mp4. untuk menampilkan video tersebut kita hanya perlu mengisi nama video beserta jenis ekstensi file video didalam tag `<source>` dan didalamnya atribut `src` terus juga didalam tag `<source>` kita beri juga didalamnya atribut `type` untuk menetukan tipe MIME(Multipurpose Internet Mail Extensions) di file video yang di sematkan.
#### Audio
Audio adalah bentuk data yang berisi informasi suara atau sinyal audio.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
   <audio controls>
     <source src="Ara.mp3" type="audio/mp3">
   </audio>
  </body>
</html>
```

**Hasil**:
![audio1](Asettt/Audio1.png)

**File Audio**:
![audio2](Asettt/File.png)

**Penjelasan**:
Di HTML, tag `<audio>` digunakan untuk menyematkan dan memainkan file audio di halaman web. Tag ini memungkinkan pengembang web menyertakan file audio langsung di dalam dokumen HTML, memungkinkan pemutaran langsung di halaman tanpa perlu mengarahkan pengguna ke halaman terpisah atau menggunakan pemutar audio eksternal. di dalam tag `<audio>` juga memiliki atribut yaitu `src` ,  `controls` , `type` yang memiliki fungsi masing masing

- `src` digunakan untuk menentukan URL atau path ke file media yang akan dimainkan.
- `controls` yang digunakan untuk Menambahkan kontrol pemutaran standar seperti play, pause, dan volume.
- `type` digunakan untuk menentukan tipe MIME (Multipurpose Internet Mail Extensions) dari file audio yang disematkan.
- `<source>` Digunakan untuk menyediakan beberapa sumber audio dan memberi browser pilihan format yang sesuai.
#### Halaman Web Lain
Halaman web lain merujuk pada laman atau situs web yang berbeda dan terpisah dari halaman web yang sedang diakses.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <iframe src="https://www.y2mate.com/id814" width="400px" height="1000px"></iframe>
  </body>
</html>
```

**Hasil**:
![web|250x500](Asettt/Lain.jpg)

**Penjelasan**:
Elemen `<iframe>` dapat digunakan untuk menampilkan dokumen html lain dalam sebuah website. Mudahnya, bsa dibilang website dalam website.

Contoh penggunaannya seperti ini. jika kita mempunyai website sekolah, lalu di website tersebut ingin menampilkan alamat alamat dalam google maps sekolah. Agar memudahkan pengunjung website, kita bsia langsung tampilan saja halaman sekolah yang ada di google maps

Dalam tag `<iframe>` ada beberapa atribut yang penting seperti:

- `src` , untuk mencari sumber halaman html atau web yang akan ditampilkan di dalam frame
-  `width` dan `height` , untuk mengatur ukuran panjang dan lebar dari frame
### Table
Tabel adalah struktur data dalam HTML yang digunakan untuk mengorganisir dan menampilkan data secara terstruktur dalam bentuk baris dan kolom.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>table</title>
  </head>
  <body>
    <table border="1">
      <tr>
        <th align="center" width="50" rowspan="2">No</th>
        <th align="center" width="100" rowspan="2">Nama</th>
        <th colspan="2" align="center" width="200">Siswa</th>
      </tr>
      <tr>
        <th>Asal Sekolah</th>
        <th>Kelas</th>
      </tr>
      <tr>
        <td align="center">1</td>
        <td>Muhammad Agis</td>
        <td>SMKN 7 Makassar</td>
        <td align="center">XI</td>
      </tr>
      <tr>
        <td align="center">2</td>
        <td>Muh Nur Rezki Al Fatir</td>
        <td>SMKN 7 Makassar</td>
        <td align="center">XI</td>
      </tr>
      <tr>
        <td align="center">3</td>
        <td>Muh Daud Rezky Jayadi</td>
        <td>SMKN 7 Makassar</td>
        <td align="center">XI</td>
      </tr>
    </table>
  </body>
</html>
```

**Hasil**:
![table](Asettt/Table.png)

**Penjelasan**:
- Tag`<table>`sering kali merujuk pada struktur data yang disusun dalam bentuk tabel, tabel memiliki baris dan kolom yang mengorganisir data secara terstruktur.
- Setiap baris tabel didefinisikan dengan tag `<tr>`
- Header (judul) tabel didefinisikan dengan tag `<th>`. secara default, header tabel memiliki teks tebal dan beraada di tengah
- Data tabel/sel didefinisikan dengan tag `<td>` . Karena sel merupakan bagian terkecil dari tabel maka dari itu tag selalu berada di dalam tag `<tr>` .
- atribut `border`digunakan untuk mengatur ketebalan batas (garis tepi) dari elemen HTML.
- atribut `rowspan` digunakan untuk menggabungkan sel-sel (cells) dalam baris tabel.
- atribut `colspan` digunakan untuk menggabungkan sel-sel dalam satu kolom tabel.
- atribut `width` digunakan untuk lebar suatu elemen HTML / atribut `height` digunakan untuk tinggi suatu elemen HTML.
- atribut `Align` untuk mengatur letak paragraf, `right`=kanan, `left`=kiri, dan `center`=tengah.
- atribut `bgcolor` biasanya digunakan untuk menentukan warna latar belakang (background) suatu elemen.
### Form 
Form dalam HTML digunakan untuk mengumpulkan data dari pengguna.

**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>From</title>
  </head>
  <body>
    <from>
      <label for="nama">nama:</label>
      <input type="teks" id="nama" required>
      <br><br>
     <label for="alamat">alamat:</label>
      <input type="teks" id="alamat">
      <br><br>
      <label for="password">password:</label>
      <input type="password" id="password" required>
      <br><br>
      
      <label>jeis kelamin:</label>
      <input type="radio" name="jk">
      <label>laki-laki</label>
      <input type="radio" name="jk">
      <label>perempuan</label>
      <br><br>
      
      <label>Keahlian yg dikuasai:</label>
      <input type="checkbox" name="bahasa">web
      <input type="checkbox" name="bahasa">mobile
      <input type="checkbox" name="bahasa">desktop
      <br><br>
      
      <label>Asal Kota:</label>
      <select>
        <option>Makassar</option>
        <option>Palu</option>
        <option>Surabaya</option>
        <option>Bandung</option>
        <option>Semarang</option>
        <option>Jakarta</option>
        <option>Yogyakarta</option>
      </select>
      <br><br>
      
      <label for="pesan">pesan:</label>
      <textarea id="pesan" name="pesan" cols="25" rows="5"></textarea>
      
      <br><br>
      <input type="submit" value="kirim">
      <input type="reset" value="ulang">
      
    </from>
  </body>
</html>
```

**Hasil**:
![from|250x500](Asettt/From.jpg)

**Penjelasan**:
Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan  untuk mengumpulkan inputan dari penggunaan website. Tag ini digunakan untuk mengoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

>[!tip] dengan kata lain tag `<form>`  merepsentikasikan sebuah "formulir" di mana satu formulir bisa dimiliki banyak kolom isian. 

Form HTML berikan elemen-elemen `form` lainnya. Elemen `<form>` digunakan untuk menampung macam-macam  elemen yang berkaitan dengan sebuah `form`, seperti `text` `fields`, `checkbox`, `radio button`, tombol `submit`, dan  banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user.
Umumnya, sebuah website selalu memiliki fitur form, contoh paling umum yang sering kita temui adalah seperti form login, form sign up, form komentar di suatu blog/media.

1. **Input** 
Elemen `<input>` adalah elemen `form`yang paling penting. Elemen `<input>` dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut `type` yang digunakan. Berikut adalah beberapa contoh nilai dari atribut type: 
- `text` digunakan untuk mengambil isian berupa teks. Contohnya seperti nama. 
- `password` digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat. 
- `radio` digunakan sebagai kolom isian bertipe pilihan yang menawarkan beberapa opsi kepada user namun tetapi hanya satu opsi saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama. 

>[!tip] Perlu diperhatikan bahwa untuk penggunaan tipe `radio` yang berkategori set pilihan yang sama mengharuskan nilai `name` -nya juga sama. 

Opsi default dapat dilakukan dengan menambahkan atribut `checked` pada elemen opsi yang dijadikan sebagai opsi default. 

- `checkbox` digunakan untuk memberikan daftar pilihan dalam satu set opsi. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu `radio` yang hanya memungkinkan user untuk memilih satu pilhan saja. Contoh penggunaan `checkbox` seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.

>[!tip] Perlu diperhatikan bahwa untuk penggunaan tipe `checkbox` yang berkategori set pilihan yang sama mengharuskan nilai `name`-nya juga sama.
>

- `number` digunakan untuk membatasi isian user hanya pada karakter numerik saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian. 
Beberapa atribut untuk tipe number: 
- min - menentukan angka minimal 
- max - menentukan angka maksimal 
- step - menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah 1) 

- `date` digunakan untuk memberikan isian berupa tanggal. Atribut `min`dan `max` dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai `min` dan `max` tersebut ditulis dengan format: `YYYY-MM-dd`.
- `file` digunakan untuk memungkinkan pengguna memuat file. Atribut `accept` juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut `accept` yaitu: 
- `accept="image/png,image/jpg, image/jpeg"` - untuk file gambar seperti png, jpg, atau jpeg 
- `accept=".pdf` - untuk file pdf
- `accept=".doc, .docx"` - untuk file `doc` atau `docx`
- `accept=".ppt, .pptx"` - untuk file `ppt` atau `pptx`

- `submit` ditampilkan dalam bentuk tombol untuk mengirim data pada `<form>` yang menjadi pembungkusnya. Atribut `value` digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.
- `reset` berguna untuk mengembalikan state (keadaan) atau data dari suatu form ke nilai awalnya. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.
- `button` berguna untuk membuat inputan berupa sebuah tombol. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.

2. **Label**
Elemen `<label>` memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan. 
Fungsi lain dari tag `<label>` adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>` dan `<input>` dengan atribut for untuk label, dan atribut id pada `<input>` dengan nilai untuk kedua atribut tersebut mesti sama persis.

Elemen `<select>` berguna dalam mendefinisikan sebuah tombol **dropdown** yang dimana user dapat memilih salah satu dari banyak pilihan. 

>[!Info]  Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi. 

Elemen `<select>` hampir mirip fungsinya dengan `<input type ="radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type ="radio">` lebih baiknya untuk digunakan jika user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
 
Penting untuk diketahui bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu `<option>` yang ingin dijadikan sebagai opsi default.

4 . **Text Area**
Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat lebih dari satu baris. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `<textarea>` bisa diisi lebih dari satu baris dengan menekan enter.

Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.

5 . **Button**
Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.

Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:
- `name` - digunakan sebagai nama variabel yang akan diproses oleh web server (contoh menggunakan PHP).
- `required` - digunakan untuk memastikan bahwa pengguna harus memasukkan nilai pada input tersebut sebelum dapat melakukan proses submit formulir.
- `placeholder` - menuliskan teks pada elemen input. Placeholder sangat bermanfaat untuk memberikan teks bantuan kepada user untuk inputan _form_ yang kompleks.
- `value` - menentukan nilai awal dari sebuah elemen input.
- `disabled` - digunakan untuk menonaktifkan inputan pada elemen yang diberi atribut ini.

#### **Bagaimana Cara Memproses Form?**

Ketika sebuah `<form>` disubmit, baik menggunakan elemen `<button>` mau pun `<input type="submit">`, browser akan mengirimkan data tersebut kepada URL yang didefinisikan pada atribut `action` di dalam tag `form`.

Ada pun jika atribut `action` tidak didefinisikan, maka *browser* akan menggunakan URL sekarang sebagai tujuan pengiriman data.

Contoh:

```html

**<form** action**=**"/proses-pendaftaran"**>**
  ...
**</form>**
```

Pada contoh di atas, ketika form di-*submit*, *browser* akan mengirimkan data yang ada  menuju URL `/proses-pendaftaran`.

**Apa yang terjadi pada URL `/proses-pendaftaran`?**

Pada URL tersebut terdapat sebuah aplikasi/program yang berjalan di *server* (bukan di *browser*). Tugas dari program tersebut adalah mengelola data yang dikirim seperti misalnya menyimpan data tersebut ke dalam sebuah *database*.

Bahasa yang umum digunakan di dalam server adalah python, nodejs, PHP, dan lain sebagainya.

Untuk mendapatkan gambaran lebih jelas, sebenarnya akan dijelaskan pada modul selanjutnya yang berkaitan dengan materi PHP atau juga bisa dengan membaca tutorial berikut:

[Link Jago Ngoding](https://jagongoding.com/web/php/web-dinamis/membuat-dan-menangani-form/)

### Div & Span
#### Div
**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Div And Span</title>
  </head>
  <body>
    <div>ini dibuat menggunakan div</div>
    <div>ini juga menggunakan div</div>
  </body>
</html>
```

**Hasil**:
![a](Asettt/Div.png)

**Penjelasan**:
tag div merupakan tag yang digunakan untuk membuat layer yang dimana itu akan memudahkan seorang devoloper untuk membuat layout sesuai dengan desain yang diinginkan.
#### Span
**Contoh**:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Div And Span</title>
  </head>
  <body></body>
    <span>ini dibuat menggunakan span</span>
    <span>ini juga menggunakan span</span>
  </body>
</html>
```

**Hasil**:
![a](Asettt/Span.png)

**Penjelasan**:
Mirip seperti DIV, span adalah tag HTML yang tidak punya makna apa-apa ketika berdiri sendiri. Ia berguna untuk memberi aksi atau hiasan pada sebuah atau sekelompok elemen HTML.