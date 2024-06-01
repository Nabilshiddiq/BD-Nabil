# Program

```html
<!DOCTYPE html>

<html>

<head>
    <link rel="stylesheet" href="pesonaindonesiaa.css">
    <title>Pesona Indonesia</title>
</head>
<style>
  .box1{
    background-image: url('bg.jpg');
  }
</style>
<body>
   <div class="container">
        
        <div class="kotak">
                    <div class="tulisan">
                        <h4 class="teksnavbar">&nbsp;&nbsp;&nbsp;&nbsp;Beranda&nbsp;&nbsp;&nbsp;Berita&nbsp;&nbsp;&nbsp;About&nbsp;&nbsp;&nbsp;&nbsp;</h4>
                        
                    </div>
        </div>

        <div class="box1">
            <h1 class="teks2">Selamat Datang di Indonesia!</h1>
             <p class="teks3">Inilah webite yang berisi Keindahan Alam Indonesia.<br>Selamat menikmati Keindahan Indonesia teman-teman :D</p>
             <button class="tombol2">Klik disini!</button>
        </div>

        <div class="box2">
            <h1 class="judul" align="center">Berita</h1>
              <div class="berita">
                    <img src="pantai kuta.jpg" class="gambar">
                    <h2 class="tk">Pantai Kuta</h2> <br>
                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                        dan berada di antara daratan benua Asia
                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                    <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                    <img src="kebun tetta.jpg" class="gambar">
                    <h2 class="tk">Kebun Tetta</h2> <br>
                    <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                        atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                        adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                        dan berada di antara daratan benua Asia
                        dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                    <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                <img src="gunung bromo.jpg" class="gambar">
                <h2 class="tk">Gunung Bromo</h2> <br>
                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia
                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                <button class="tombol1">Baca selengkapnya >></button>
              </div>

              <div class="berita">
                <img src="jekada.jpg" class="gambar">
                <h2 class="tk">Jekadah!</h2> <br>
                <p class="teks33">Indonesia, dikenal dengan nama resmi Republik Indonesia 
                    atau lebih lengkapnya Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia
                    dan Oseania sehingga dikenal sebagai negara lintas benua.</p>
                <button class="tombol1">Baca selengkapnya >></button>
              </div>
        </div>

       

        <div class="box3">
        <h1 class="about">About</h1>
        <div class="teks4">
                <img src="orang.jpg" class="gambar1">
                <p class="teks5">Indonesia, dikenal dengan nama resmi Republik Indonesia
                    atau lebih lengkapnya <br> Negara Kesatuan Republik Indonesia,
                    adalah negara kepulauan di Asia Tenggara yang <br> dilintasi garis khatulistiwa
                    dan berada di antara daratan benua Asia dan Oseania <br> sehingga dikenal sebagai negara lintas benua.</p>
            </div>
        </div>

   </div>
</body>
</html>
```

``` css
.container{



    width: auto;



    height: auto;

}



 .container >.kotak{

    width: 100%;

    height: 15%;

    position: fixed;

    background-color: white;

    margin-top: -1%;

    z-index: 1;

}



.box  >.tulisan{

    margin-left: 38%;

    font-size: 18px;

    padding-top: 40px;

   font-family: 'Segoe UI';

}



.logo{

    width: 100px;

    height: 50px;

    float: left;

}



.teksnavbar {

  margin-left: 15px;

  margin-top: 40px;

}



.samadengan{

  width: 30px;

  height: 15px;

  margin-left: 220px;

  float: left;

  margin-top: -36px;



}



.box1{

    padding-bottom: 20%;

    padding-top: 10%;

    background-image: url(hero-image.jpg);

    width: 100%;

    height: 18%;

    margin-bottom: 40px;

    background-size:cover ;

}



.teks3{

    text-align: center;

    font-size: 15px;

    font-family: 'Segoe UI';

    margin-top: -10px;

}



.teks33{

    text-align: center;

    font-size: 15px;

    font-family: 'Segoe UI';

    margin-top: -5px;

    margin-right: 7px;

}



.teks2{

    margin-top: 150px;

    text-align: center;

    font-family: 'Segoe UI';

}



.teks2{

  color: white;

  text-align: center;

  font-family: 'Segoe UI';

}



.tombol2 {

  color: white;

  background-color: blue;

  width: 110px;

  height: 50px;

  margin-left: 45%;

  border-radius: 5px;

  box-shadow: 2px 2px 2px 2px blue;

  border: none;

  position: flex -15px;

}



.tombol2:hover {

  background-color: burlywood;

  color: black;

  box-shadow: 2px 3px 2px 3px gray;

  transition: all 0.5s ease-in;

}



.berita {

  margin-top: 150px;

    width: 275px;

    height: 520px;

    border-radius: 15px;

    box-shadow: 5px 4px 10px 4px #c7c1c1;

    float: left;

    margin: 16px;

    font-size: 15px;

    padding: 10px 0px 20px 20px;

  }



.tk{

    color: blue;

    font-family: 'Segoe UI';

   margin-bottom: 1px;

   margin-left: 3px;

  }



.gambar{

   width: 265px;

   border-radius: 20px;

   height: 170px;

  }



.tombol1{

    border: none;

    background-color: blue;

    width: 194px;

    height: 50px;

    color:white;

    box-shadow: 2px 3px 2px 3px #4c86df;

    border-radius: 10px;

    margin-top: 1px;

    margin-left: 30px;

  }



.tombol1:hover {

    background-color: burlywood;

    color: black;

    box-shadow: 2px 3px 2px 3px gray;

    transition: all 0.3s ease-in;

  }



  /*.tetx{

    margin-top: -1px;

    padding: 10px 20px 20px 20px;

    font-family: 'Segoe UI';

  }*/



.box3{    

    margin-top: 100px;

    background-color: blue;

    height: 360px;

    width: 100%;

    display: flex;

    flex-direction: column;

  }



.teks4 {

    display: flex;

    flex-direction: row;

}



.gambar1{

    width: 200px;

    height: 200px;

    border-radius: 100px;

    margin-left: 15%;

    margin-top: 50px;

    filter: grayscale(100%);

    margin-top: 0px;

}



.about{

    color: white;

    text-align: center;

    font-family: 'Segoe UI';

    padding-top: 35px;

    margin-top: -5px;

    margin-left: -10px;

  }



.teks5{

    text-align: justify;

    margin-top: 50px;

    font-family: 'Segoe UI';

    color: white;

    margin-left: 5%;

    display: flex;

    flex-direction: column;

  }

  

  .tambahan {

    margin-top: 650px;

    background-color: cadetblue;

    height: 500px;

    width: 100%;

    display: flex;

    flex-direction: row;

    justify-content: space-around;

  }



.tambahan > h1 {

    color: black;

    font-family: 'Segoe UI';

    padding-top: 25px;

    padding-left: 30%;

  }



  .judultambahan {

    margin-left: -645 px;

    margin-right: 10%;

    margin-top: 5px;

    color: white;

    text-align: center;

    position: relative;

    left: 350px;

  }



  .kesatuu {

    margin-top: 150px;

      width: 270px;

      height: 300px;

      border-radius: 15px;

      font-size: 15px;

      padding: 10px 0px 20px 20px;

      margin-top: 130px;

      margin-left: 35px;

      margin-bottom: -60px;

      position: relative;

      left: -380px;

      right: -350px;

    }

  

  .peta1{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 0px;

     margin-left: -15px;

     text-align: center;

    }



    .peta2{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 1px;

     margin-left: -15px;

     text-align: center;

    }



    .peta3{

      color: white;

      font-family: 'Segoe UI';

     margin-bottom: 0px;

     margin-left: -15px;

     text-align: center;

    }

  

  .kesatu{

     width: 265px;

     border-radius: 20px;

     height: 170px;

     margin-top: 10px;

     margin-right: 20px;

    }

  

  .tomboltambahan{

      border: none;

      background-color: blue;

      width: 194px;

      height: 50px;

      color:white;

      box-shadow: 2px 3px 2px 3px #4c86df;

      border-radius: 10px;

      margin-top: 20px;

      margin-left: 35px;

    }

  

  .tomboltambahan:hover {

      background-color: burlywood;

      color: black;

      box-shadow: 2px 3px 2px 3px gray;

      transition: all 0.5s ease-in;

    }











/*@media (max-width: 701px){

    .tombol2 {

      margin-left: 275px;

    }



    .logo {

      margin-left: 150px;

    }



    .tulisan {

      margin-left: 150px;

    }



    .gambar1 {

      margin-left: 20px;

    }



    .teks5 {

      margin-top: 25px;

      margin-right: 30px;

    }

}



/*.{

    width: 145px;

    height: 200px;

    border-radius: 200px;

    margin-left: -150%;

    margin-top: 10px;

   display: flex;

   margin-top: 100px;   

   align-items: center;

  }



.deskripsi{

    margin-left: -350%;

    text-align: center;

    margin-top: 40px;

    font-family: 'Segoe UI';

    color: white;

    border: 10px;

    border-color: white;

    border-radius: 15px;

  }



  .satu {

    width: 100px;



  }



  .dua {

    width: 100px;

    float: left;

  }



  .tiga {

    width: 100px;

    float: left;

  }*/
```

# Hasil
![[Pesona.jpg.jpg]]




# Analisis 
## Html
Struktur Umum:

Program dimulai dengan tag <!DOCTYPE html> yang menunjukkan jenis dokumen HTML yang digunakan.
Di dalam tag <html>, ada bagian <head> yang berisi informasi tentang dokumen, seperti judul halaman dan referensi ke file CSS.
Bagian utama konten dimulai di dalam tag <body>.
CSS:

Gaya (CSS) didefinisikan baik dalam tag <head> sebagai file eksternal (pesonaindonesiaa.css) dan secara internal menggunakan tag <style>.
Konten:

Ada tiga bagian utama yang terlihat: navigasi, berita, dan bagian "About".
Navigasi terdiri dari tautan menu seperti "Beranda", "Berita", dan "About".
Bagian berita menampilkan gambar dan deskripsi singkat tentang tempat-tempat wisata di Indonesia, seperti Pantai Kuta dan Gunung Bromo.
Bagian "About" berisi deskripsi umum tentang Indonesia, dilengkapi dengan gambar.
HTML Elements:

Beberapa elemen HTML yang digunakan termasuk <div>, <h1>, <p>, <img>, dan <button>.
Setiap elemen digunakan untuk menentukan struktur dan tampilan halaman web.
Tombol dan Tautan:

Ada tombol yang mengarah pada lebih banyak informasi dengan teks "Baca Selengkapnya".
Ada juga tautan yang mungkin digunakan untuk navigasi di situs web.



