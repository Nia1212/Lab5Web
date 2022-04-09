| Nama          | Nia Dwi Rahayu  |
|-------------- | ----------------|
| NIM           | 312010298       |
| Kelas         | TI.20.A2        |
| Matkul        | Pemograman web  |

# Langkah pengenalan JavaScript
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Mengenal JavaScript</title>
</head>

<body>
    <h1>Pengenalan JavaScript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>

</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss1.png)



# Java Script Dasar
## pemakaian Alert sebagai property window.
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>alert box</title>
  </head>
  <body>
    <script language="JavaScript">
      <!--
      window.alert("ini merupakan pesan untuk anda");
      //-->
    </script>
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss2.png)


# Pemakaian method dalam objek
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>alert box</title>
  </head>
  <body>
    <script language="JavaScript">
      <!--
      window.alert("ini merupakan pesan untuk anda");
      //-->
    </script>
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss3.png)

# Pemakaian Prompt
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pemasukan Data</title>
</head>
<body>
    <script language = "javascript">
        <!--
            var nama = prompt("siapa nama anda?","masukan nama anda");
            document.write("hai, " + nama)
            -->
    </script>
</body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss4.png)

# Pembuatan fungsi dan cara pemanggilannya
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>contoh program javascript</title>
    <script language="javascript">
      function pesan() {
        alert("memanggil javascript lewat body onload");
      }
    </script>
  </head>
  <body onload="pesan()"></body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss5.png)

# Dasar Pemrograman Di javascript
## Operasi dasar aritmatika
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>contoh program javascript</title>
    <script lang="javascript">
      function test(val1, val2) {
        document.write("<br>" + "perkalian : val1*val2" + "<br>")
        document.write(val1 * val2);
        document.write("<br>" + "pembagian : val1/val2 " + "<br>")
        document.write(val1 / val2);
        document.write("<br>" + "penjumlahann : val+val2" + "<br>")
        document.write(val1 + val2);
        document.write("<br>" + "pengurangan : val1-val2 " + "<br>")
        document.write(Val1 - val2);
        document.write("<br>" + "modulus : val1%val2" + "<br>");
        document.write(val1 % val2);
      }
    </script>
  </head>
  <body>
    <input
      type="button"
      name="button1"
      value="arithmetic"
      onclick="test(9,4)">
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss6.png)
![Gambar](img/ss7.png)

# Seleksi kondisi (if..else)
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contoh if-else</title>
</head>
<body>
    <script lang="javascript">
<!--
    var nilai = prompt("nilai (0-100): ", 0);
    var hasil = "";
    if (nilai >= 60)
    hasil = "lulus";
    else
    hasil = "tidak lulus";
    document.write("hasil: " + hasil);
    //-->
    </script>
</body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss8.png)

# Penggunaan operator switch untuk seleksi kondisi
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>contoh program javascript</title>
    <script lang="javascript">
      {
          val1=window.prompt("input nilai (1-5): ")
          switch (val1)
          {
              case "1" :
                  document.write("bilangan satu")
                  break
              case "2" :
              document.write("bilangan dua")
                  break
              case "3" :
              document.write("bilangan tiga")
              break
              case "4" :
                  document.write("bilangan empat")
              break
              case "5" :
                  document.write("bilangan lima")
                  break
              default :
              document.write("bilangan lainnya")

          }
      }
    </script>
  </head>
  <body>
    <input type="button" name="button1" value="switch" onclick="test()" />
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss9.png)
![Gambar](img/ss10.png)

# Membuat From
## From Input
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>From Input</title>
    <script lang="javascript">
      function test () {
          var val1=document.kirim.T1.value
          if (aval1%2==0)
          document.kirim.T2.value="bilangan genap"
          else
          document.kirim.T2.value="bilangan ganjil"
      }
    </script>
  </head>
  <body>
    <form method="POST" name="kirim">
      <p>
        Bil <input type="text" name="T1" size="20" /> MERUPAKAN BIL
        <input type="text" name="T2" size="20" />
      </p>
      <p><input type="button" value="TEBAK" name="B1" onclick="test()" /></p>
    </form>
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss11.png)

## Form Button
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>objek document</title>
  </head>
  <body>
    <script lang="javascript">
      <!--
          function ubahWarnaLB(warna) {
              document.bgColor=warna;
          }
          function ubahWarnaLD(warna) {
              document.fgColor=warna;
          }
          //-->
    </script>
    <h1>tes</h1>
    <form>
      <input
        type="button"
        value="Latar Belakang Hijau"
        onclick="ubahWarnaLB('GREEN')"
      />
      <input
        type="button"
        value="Latar Belakang Putih"
        onclick="ubahWarnaLB('WHITE')"
      />
      <input
        type="button"
        value="Teks Kuning"
        onclick="ubahWarnaLD('YELLOW')"
      />
      <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')" />
    </form>
    <script lang="javascript">
      <!--
      document.write("Dimodifikasi terakhir pada " + document.lastModified);
      //-->
    </script>
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
- Latar Belakang Hijau
  ![Gambar](img/ss12.png)
- Latar Belakang Putih
  ![Gambar](img/ss13.png)
- Teks Kuning
  ![Gambar](img/ss14.png)
- Teks Biru
  ![Gambar](img/ss15.png)

# HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Daftar Menu</title>
    <script>
      function hitung(ele) {
        var total = document.getElementById("total").value;
        total = total ? parseInt(total) : 0;
        var harga = 0;
        if (ele.checked0) {
          harga = ele.value;
          total += parseInt(harga);
        } else {
          harga = ele.value;
          if (total > 0) total -= parseInt(harga);
        }
        document.getElementById("total").value = total; 
      }
    </script>
  </head>
  <body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" id="menu1" onclick="hitung(this);"/>Ayam Goreng Rp. 5.000</label><br/>
    <label><input type="checkbox" value="500" id="menu2" onclick="hitung(this);"/>Tempe Goreng Rp. 500</label><br/>
    <label><input type="checkbox" value="2500" id="menu3" onclick="hitung(this);"/>Telur Dadar Rp. 2.500</label><hr/>
    <strong>Total Bayar: Rp. <input id="total" type="text"/></strong>
  </body>
  </body>
  </body>
</html>
```
Ini hasilnya setelah saya jalankan.
![Gambar](img/ss16.png)

# Pertanyaan dan tugas
1. Buat script untuk melakukan validasi pada isian form.
## Jawaban
Membuat validasi nama, Email
1. Nama
   Saya akan memberikan Validasi berupa inputan hanya boleh menggunakan Huruf/Alphabet saja. Contoh: Nia (benar), Nia12 (salah).<br>
   ![Gambar](img/ss18.png)<br>
   Penjelasan<br>
   - Pertama membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai, pesan).
   - Data yang boleh dimasukkan adalah berupa "a-zA-Z".
   - Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"
  ![Gambar](img/ss17.png)<br>

2. Email
   Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: rahayunia811@gmail.com (benar), rahayunia811@gmail. (salah).<br>
   ![Gambar](img/ss19.png)<br>
   Penjelasan<br>
   - membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf,  Angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);
  ![Gambar](img/ss20.png)<br>

  Gambar dibawah adalah penulisan from yang benar<br>
![Gambar](img/ss21.png)<br>