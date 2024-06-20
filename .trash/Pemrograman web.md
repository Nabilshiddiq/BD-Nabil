# Struktur Html

!DOCTYPE html>
```html
<head>
<tittle> ini adalah judul </tittle>
</head>
<body>
<p> ini adalah paragraf yang akan ditampilkan di browser </p>
</body>
</html>
```
Tag `<!DOCTYPE html>` memberitahukan web browser bahwa dokumen HTML adalah versi 5
- Tag pembuka `<html>` menandai awal sebuah dokumen HTML sampai dengan tag penutup `</html>`
- Tag pembuka `<head>` berisi informasi tentang halaman HTML sampai dengan tag penutup `</head>`, biasanya dalam tag head terdapat tag `<titel>` untuk memberikan informasi judul halam HTML
- apapun tag yang berada di antara tag pembuka `<body>` sampai dengan tag penutup `</body>` akan tampil di web browser


# Anatomi elemen Html
<!DOCTYPE html>

```
<html>
<head>
 <title> ini adalah judul </title>
</head>
<body>
<p> Untuk login ke instagram saya klik link di bawah ini :) </p>
 <b> Terima kasih </b>

</body>
</html>
<a href= "https://www.instagram.com/nbil_ji/" > klik link Ig gua
```




![[Screenshot_2024-01-17-14-47-21-72.png]]








# Tag dasar

## Heading

<!DOCTYPE 
<html>​
```<body>
    <h1>kata kata hari ini</h1>
    <h2>word of the day</h2>
    <h3>今日の単語</h3>
    <h4>ك4لمة اليوم</h>
    <h5>Từ trong ngày</h5>
    <h6>오늘의 단어</h6>
    <p>No Body</p>
    <p>tidak ada yang tahu</p>
    <a href="https://www.google.com">Klik Goggle</a>
  </body>
</html>
```

**Hasil program

![[IMG-20240121-WA0051.jpg]]

**Penjelasan Heading
- Tag `<h1>` Digunakan untuk judul utama atau level judul tertinggi
- Tag `<h2>` Menunjukkan tingkatan judul yang lebih rendah dari `<h1>` atau subjudul
- Tag `<h3>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h2>`
- Tag `<h4>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h3>`
- Tag `<h5>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h4>`
- Tag `<h6>` Menunjukkan tingkatan judul yang lebih rendah atau subjudul dari `<h5>`


## Paragraf html



<!DOCTYPE html>

```<html>
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
    <a href="https://www.google.com">Klik Goggle saya biar tahu</a>
  </body>

</html>
```

**Hasil program

![[IMG-20240121-WA0053.jpg]]

**Penjelasan paragraf
- Tag `<p>`digunakan untuk menandai paragraf pada halaman web dan di akhiri `</p>`. Ini memberikan jarak antara paragraf.
- Tag `<b>` digunakan untuk membuat teks menjadi tebal (bold) dan di akhiri `</b>`.
- Tag `<u>` digunakan untuk memberi garis bawah pada teks dan di akhiri `</u>`. 
- Tag `<i>` digunakan untuk membuat teks menjadi miring (italic) dan di akhiri `</i>`.
- Tag `<br>` digunakan untuk membuat jeda baris atau perpindahan ke baris berikutnya tanpa membuat paragraf baru.
- Tag `<hr>` digunakan untuk membuat garis horizontal, yang sering digunakan pemisah visual di antara bagian-bagian pada halaman web.



## Tag pembuka dan tag penutup



Tag pembuka dan tag penutup adalah dua bagian dari suatu elemen dalam HTML yang digunakan untuk menentukan awal dan akhir dari elemen tersebut. Tag pembuka dimulai dengan nama elemen yang diapit oleh tanda kurung sudut ("<" dan ">"). Tag penutup serupa dengan tag pembuka, tetapi memiliki karakter garis miring tambahan ("/") sebelum nama elemennya. contoh ini, `<p>` adalah tag pembuka, dan `</p>` adalah tag penutup

**Atribut tag :
Isi atau konten tag merujuk pada teks, elemen, atau informasi yang ditempatkan di antara tag pembuka dan tag penutup dalam markup HTML. Contoh sederhana adalah tag paragraf `<p>`, di mana isi tag tersebut adalah teks yang ingin dimuat dalam paragraf. Contoh "Ini adalah contoh isi atau konten dalam tag paragraf." adalah isi atau konten yang akan ditampilkan atau diinterpretasikan oleh browser web ketika halaman HTML di-render







## Komentar
Komentar tidak akan ditampilkan pada halaman website namun programmer biasanya menggunakan `komentar` untuk memperjelas kode program.


## List
`List` adalah fungsi dalam HTML yang digunakan untuk menampilkan daftar dari sesuatu. Dalam HTML, tag list dari 2 jenis, ``<ol>`` ordered list (berurutan) dan ``<ul>`` unordered list (tidak berurutan). Ordered list akan ditampilkan dengan angka tau huruf, sedangkan unordered list adalah bulatan atau kotak ataupun simbol lainnya.

Untuk menampilkan list dalam HTML dapat menggunakan tag ``<li>`` ... ``</li>`` namun perlu dengan menyisipkan elemen ``<ol>``...``</ol>`` atau ``<ul>``...``</ul>`` ke dalam elemen ``<li>`` tersebut untuk membuat daftar list.

## Link
`Link` dapat ditemukan di hampir semua halaman web. Link/tautan memungkinkan sebuah teks yang ketika di klik pindah ke halaman lainnya. HTML menggunakan tag ``<a>`` untuk keperluan ini. Link ditulis dengan ``<a>`` yang merupakan singkatan cari `anchor (jangkar)`.

>[! faq]- href
> Setiap tag `<a>` setidaknya memiliki sebuah atribut `href`.  Dimana `href` berisi alamat yang dituju. `href` adalah singkatan dari hypertext reference.

Atribut penting lainnya dari tag ``<a>`` adalah ``target``. Atribut target menentukan tempat untuk membuka dokumen yang ditautkan. Atribut ``target`` memiliki beberapa nilai salah satunya ``_blank`` yang berfungsi untuk membuka tautan di tab baru.
## Multimedia

![[IMG-20240124-WA0003.jpg]]

![[IMG-20240124-WA0004 1.jpg]]

*Penjelasan*:
• Dalam HTML, gambar   didefinisikan dengan tag ing) Tag <ing adalah tag kosong. hanya berisi atribut saja, dan tidak memiliki tag penutup.
• ==Atribut src setidaknya mesti ada dalam tag ini untuk menentukan URL (alamat web) dari gambar yang ingin ditampilkan.==
• Atribut alt menyediakan teks alternatif untuk gambar, jika pengguna karena beberapa alasan tidak dapat melihatnya (karena koneksi lambat, kesalahan pada atribut are, atau jika web browser telah disetting untuk tidak menampilkan gambar). Jika browser tidak dapat menemukan gambar, maka akan muncul nilai pada atribut
• Dalam tag ``<img>`` terdapat juga atribut width dan height untuk mengatur ukuran gambar, pada versi HTML5 standar satuan ukuran gambar adalah pixel.
• - Misalnya dalam folder root terdapat file gambar bernama logo.png. Untuk menampilkan gambar tersebut kita hanya perlu mengisi nama gambar beserta jenis ekstensi file gambar ke dalam atribut src, contohnya src="logo.png"
• Untuk menampilkan gambar dari internet carilah link gambar yang akan ditampilkan lalu masukkan dalam nilai atribut src, contohnya https://namasitus.com/gambar.png.

*Program*
<!DOCTYPE html>
 
```<html>
  <head>
    <title>ini adalah judul</title>
  </head>
  <body>
    <img src="Nbl.jpg" alt="Logo" width="150" height="150">
  </body>
</html>
```






## Tabel Html




![[IMG-20240129-WA0008.jpg]]


## Form



Elemen "form" HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

Dengan kata lain tag "form" merepresentasikan sebuah "formulir" di mana satu formulir bisa memiliki banyak kolom isian.

Form HTML berisikan elemen-elemen form lainnya. Elemen <form> digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah form, seperti text fields, checkbox, radio button, tombol submit, dan banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user.

Umumnya, sebuah website selalu memiliki fitur form, contoh paling umum yang sering kita temui adalah seperti form login, form sign up, form komentar di suatu blog/media.

Perlu diperhatikan bahwa untuk penggunaan tipe checkbox yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

number digunakan untuk membatasi isian user hanya pada karakter numerik saja. Browser akan menambahkan dua buah tombol atas dan bawah untuk mengubah angka isian.

Beberapa atribut untuk tipe number:

min - menentukan angka minimal

max - menentukan angka maksimal

step - menentukan kelipatan (nilai yang tidak sesuai kelipatan tidak bisa di-input, dan default dari atribut ini adalah 1)

date digunakan untuk memberikan isian berupa tanggal. Atribut min dan max dapat pula difungsikan pada tipe ini untuk mengatur tanggal minimal dan tanggal maksimal yang diinginkan. Nilai min dan max tersebut ditulis dengan format: YYYY-MM-dd

file digunakan untuk memungkinkan pengguna memuat file. Atribut accept juga dapat disisipkan pada tipe ini dengan maksud untuk mengatur file apa saja yang boleh di-upload. Beberapa contoh value dari atribut accept yaitu:

accept="image/png,image/jpg, image/jpeg" untuk file gambar seperti png, jpg, atau jpeg

accept=".pdf" - untuk file pdf

accept-".doc, .docx" untuk file doc atau docx

accept=".ppt, .pptx untuk file ppt atau pptx

submit ditampilkan dalam bentuk tombol untuk mengirim data pada <form> yang menjadi pembungkusnya. Atribut value digunakan untuk mengisi teks yang ingin ditampilkan pada tombol.

reset berguna untuk mengembalikan state (keadaan) atau data dari suatu form ke nilai awalnya. Jika nilai awal sebuah input adalah kosong, maka ketika direset ia akan kembali kosong. Tapi jika nilai awalnya sudah terisi sesuatu, maka ketika direset datanya akan kembali seperti yang sudah diset sebelumnya.

button berguna untuk membuat inputan berupa sebuah tombol. Tombol ini nantinya bisa difungsikan sesuai dengan keinginan dari pengembang web.

Untuk bacaan tentang materi ini yang dirasa cukup lengkap dan mudah dipahami, silahkan mengunjungi halaman berikut:

HTML Dasar: Tipe Element Input

Membahas tentang berbagai macam isi dari atribut type pada element input

https://jagongoding.com/web/html/dasar/tipe-element-input/

accept=".pdf" - untuk file pdf

accept-".doc, .docx" untuk file doc atau docx

accept=".ppt, .pptx untuk file ppt atau pptx

1. Input

Elemen <input> adalah elemen form yang paling penting. Elemen <input> dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut type yang digunakan. Berikut adalah beberapa contoh nilai dari atribut type:

text digunakan untuk mengambil isian berupa teks. Contohnya seperti nama.

password digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat.

radio digunakan sebagai kolom isian bertipe pilihan yang menawarkan beberapa opsi kepada user namun tetapi hanya satu opsi saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama.

Perlu diperhatikan bahwa untuk penggunaan tipe radio yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

Opsi default dapat dilakukan dengan menambahkan atribut checked pada elemen opsi yang dijadikan sebagai opsi default.

checkbox digunakan untuk memberikan daftar pilihan dalam satu set opsi. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu radio yang hanya memungkinkan user untuk memilih satu pilhan saja. Contoh penggunaan checkbox seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.

2.Label
  Elemen <label>memiliki fungsi khusus untuk melabeli sebuah kolom inputan, ketika screen reader membaca konten halaman HTML lalu menemukan sebuah inputan ia akan membaca laber yg bersangkutan
  Fungsi lain dari tag <label> ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yg terhubung dengannya. Syaratnya ialah <for>untuk<Label>dan atribut <id>pada <input>
  3. Select
    Elemen `<select>` berguna dalam mendefinisikan sebuah tombol ***dropdown*** yang dimana *user* dapat memilih salah satu dari banyak pilihan. 
    
    <aside>
     Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi.
    
    </aside>
    
    Elemen `<select>` hampir mirip fungsinya dengan `<input type=”radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type=”radio">` lebih baiknya untuk digunakan jika  *user* diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.
    
    Penting untuk diketahui  bahwasanya opsi yang aktif secara *default* adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara *default* dengan menambahkan atribut `selected` pada suatu `<option>` yang ingin dijadikan sebagai opsi *default*. 
    
4. Text Area
    
    Elemen `<textarea>` berguna untuk mengambil inputan *user* berupa teks yang dapat memuat **lebih dari satu baris**. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element `textarea` bisa diisi lebih dari satu baris dengan menekan enter.
    
    Atribut yang dapat digunakan untuk mengatur kuran dari `textarea` yaitu `rows` untuk jumlah baris, sedangkan atribut `cols` untuk lebarnya.
    
5.Button
    
    Elemen `<button>` yang berada di dalam sebuah `form` akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-*submit* `<form>` dapat dilakukan dengan menambahkan atribut `type="button"`.









