# Ujian Data base

## Index html
1. **Deklarasi Tipe Dokumen (`<!DOCTYPE html>`):**
    
    - Mendefinisikan tipe dokumen HTML yang digunakan, dalam hal ini HTML5.
2. **Elemen `<html>`:**
    
    - Merupakan elemen utama yang mengelilingi seluruh konten halaman web.
3. **Elemen `<head>`:**
    
    - Berisi informasi-informasi terkait dokumen seperti judul halaman (didefinisikan di dalam tag `<title>`).
4. **Elemen `<title>`:**
    
    - Menetapkan judul halaman, dalam hal ini "Order".
5. **Elemen `<body>`:**
    
    - Berisi semua konten yang akan ditampilkan di halaman web.
6. **Elemen-elemen `<h1>`, `<form>`, `<input>`, `<select>`, `<textarea>`, `<radio>`, `<checkbox>`, `<submit>`, `<reset>`:**
    
    - `<h1>`: Menampilkan judul utama "Pesan Bunga".
    - `<form>`: Mendefinisikan sebuah form untuk mengumpulkan informasi dari pengguna.
    - `<input>`: Untuk mengumpulkan input teks, baik untuk nama, maupun input tanpa label lainnya.
    - `<select>`: Untuk menyediakan pilihan dalam bentuk dropdown menu, dalam hal ini untuk memilih jenis bunga.
    - `<textarea>`: Untuk mengumpulkan input teks yang lebih panjang, seperti alamat pengiriman.
    - `<radio>`: Untuk memungkinkan pengguna memilih satu opsi dari beberapa yang tersedia (dalam hal ini, jenis pembayaran).
    - `<checkbox>`: Untuk memungkinkan pengguna memilih beberapa opsi dari beberapa yang tersedia (dalam hal ini, waktu pengiriman).
    - `<submit>` dan `<reset>`: Tombol untuk mengirimkan atau menghapus data yang dimasukkan dalam formulir.
7. **Elemen-elemen `<a>`:**
    
    - Mengandung tautan ke halaman lain dalam situs web atau ke URL eksternal.

Program ini memungkinkan pengguna untuk memasukkan informasi seperti nama, jenis bunga yang ingin dipesan, metode pembayaran, alamat pengiriman, dan waktu pengiriman yang diinginkan. Setelah itu, pengguna dapat mengirimkan pesanan atau menghapus informasi yang dimasukkan melalui tombol yang disediakan. Terdapat juga tautan untuk melihat daftar bunga yang tersedia dan kembali ke halaman utama.



## list bunga html

Dokumen dimulai dengan tag yang menunjukkan bahwa ini adalah dokumen HTML5.
Selanjutnya, terdapat elemen <html> yang mengandung seluruh isi halaman.
Di dalam <html>, terdapat elemen <head> yang berisi informasi tentang dokumen, seperti judul halaman.
Elemen <body> berisi konten yang akan ditampilkan kepada pengguna.
Konten:

Terdapat judul halaman yang ditampilkan di tab browser: <title>Order</title>.
Ada sebuah judul utama yang menggunakan elemen <h1>: "Pesan Bunga".
Kemudian, ada sebuah formulir yang berisi beberapa elemen input dan pilihan:
Nama: Input teks.
Jenis Bunga: Pilihan dalam bentuk dropdown menggunakan elemen <select>.
Jenis Pembayaran: Pilihan menggunakan elemen <input type="radio"> untuk tunai dan transfer.
Alamat Pengiriman: Input teks area menggunakan elemen <textarea>.
Waktu Pengiriman: Pilihan menggunakan elemen <input type="checkbox"> untuk waktu pagi, siang, sore, dan malam.
Tombol submit dan reset untuk mengirimkan dan menghapus formulir.
Ada juga tautan untuk melihat daftar bunga dan kembali ke halaman utama.
Kesalahan Ketik:

Terdapat beberapa kesalahan penulisan pada elemen <label>,yang seharusnya ditulis sebagai <label> bukan <lebel>.
Tag <hr> juga ditutup tanpa pembukaan tag.
Overall, ini adalah sebuah formulir sederhana untuk memesan bunga dengan opsi untuk memilih jenis bunga, metode pembayaran, alamat pengiriman, dan waktu pengiriman.

### order_bunga.html
Deklarasi jenis dokumen HTML.

<html>: Elemen utama dari dokumen HTML. <head>: Berisi meta-informasi tentang dokumen HTML, termasuk judul. <title>: Menetapkan judul halaman web yang muncul di tab browser. <body>: Konten utama dari dokumen HTML. <table>: Mendefinisikan tabel untuk mengorganisir konten. border="0": Menghapus batas tabel. width="100%" dan height="100%": Menetapkan lebar dan tinggi tabel menjadi 100% dari tampilan. <tr>: Mewakili baris tabel. <th>: Mewakili sel kepala tabel. align="left", bgcolor="yellow", colspan="2", height="50": Atribut gaya untuk sel kepala. <tr> lain dengan <th> untuk judul utama. <tr> lain dengan <td> untuk menampilkan gambar. <img>: Menampilkan gambar dengan lebar dan tinggi tertentu. <tr> lain dengan <td> untuk tombol yang terhubung ke "u.html" untuk memesan bunga. <a>: Membuat hyperlink. <input>: Mendefinisikan bidang input (dalam hal ini tombol). type="submit": Menentukan jenis tombol. value="order bunga": Menetapkan teks tombol. <tr> lain dengan <td> untuk dua hyperlink berturut-turut dengan warna latar belakang yang berbeda. Setiap hyperlink didefinisikan menggunakan <a> dalam <td>. Secara keseluruhan, kode ini membuat halaman web sederhana dengan header, judul utama, gambar, tombol untuk memesan bunga, dan dua hyperlink untuk melihat daftar bunga dan memesan bunga secara langsung. Gaya dicapai menggunakan atribut HTML.

Deklarasi Tipe Dokumen (<!DOCTYPE html>):

Menetapkan tipe dokumen HTML yang digunakan, yaitu HTML5.
Elemen <html>:

Merupakan elemen utama yang mengelilingi seluruh konten halaman web.
Elemen <head>:

Berisi informasi-informasi terkait dokumen seperti judul halaman (didefinisikan di dalam tag <title>).
Elemen <title>:

Menetapkan judul halaman, dalam hal ini "List".
Elemen <body>:

Berisi semua konten yang akan ditampilkan di halaman web.
Elemen-elemen <h1>, <table>, <tr>, <td>, <ul>, <li>, <img>, <a>:

<h1>: Menampilkan judul utama "List Bunga".
<table>: Mendefinisikan tabel untuk menampilkan daftar bunga.
<tr>: Merepresentasikan baris dalam tabel.
<td>: Merepresentasikan sel dalam tabel.
<ul> dan <li>: Digunakan untuk membuat daftar dengan informasi bunga (asal, keharuman, harga).
<img>: Menampilkan gambar bunga.
<a>: Tautan untuk memesan bunga dan kembali ke halaman utama.
Atribut-atribut:

Terdapat penggunaan atribut-atribut seperti border, width, bgcolor, dan colspan untuk mengatur tampilan dan struktur tabel.
Program ini menampilkan daftar bunga beserta informasi-informasi seperti asal, keharuman, dan harga. Terdapat juga tautan untuk memesan bunga (ke halaman "u.html") dan kembali ke halaman utama (ke halaman "hi.html").










