|  Berliana Noviansyah  |   312010373   |
|-----------------------|---------------|
|    Pemrograman Web    |    TI.20.A1   |
|      Pertemuan 6      |  Praktikum 5  |

# Praktikum 5 Pertemuan 6



## 1). Persiapan Membuat Dokmen HTML dengn Nama File lab5_javascript.html.

**Untuk coding dan outputnya adalah sebagai berikut:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal Javascript</title>
</head>
<body>
    <h1>Pengenalan Javascript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```

**Output:**

![Pengenalan_Javascript](img/pengenalan.png)

Untuk console.log tidak ditampilakn pada browser karena bersifat hidden element. Untuk melihatnya klik kanan, pilih inspect lalu buka pada bagian console.

![console](img/console.png)



# Javascript Dasar
## 2). Pemakaian Alert Sebagai Property Window

**Coding dan tampilan output:**

```html
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal Javascript</title>
</head>
<body>
    <h1>Pengenalan Javascript</h1>
    <h3>Contoh document.write dan console.log</h3>
    <script lang="javascipt">
        window.alert("Terdapat sebuah pesan untuk anda")
    </script>
</body>
</html>
```

**Output:**

![Property_Window](img/propertywdw.png)



## 3). Pemakaian Method Dalam Obyek

**Coding:**

```html
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Script Javascript</title>
</head>
<body>
    Percobaan Menggunakan Javascript:<br>
    <script lang="javascript">
        document.write("Belajar Menggunakan Javascript<br>");
        document.write("Good Luck!^^");
    </script>
</body>
</html>
```

**Output:**

![Method_Obyek](img/method.png)



## 4). Pengaplikasian Prompt

**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Script Javascript</title>
</head>
<body>
    Percobaan Menggunakan Javascript:<br>
    <script lang="javascript">
       var nama = prompt("What is your name?","Enter your name here");
       document.write("Hi, "+nama)
    </script>
</body>
</html>
```

**Output:**

![Pengaplikasian_Prompt](img/prompt.png)



## 5). Pembuatan Fungsi dan Cara pengaplikasiannya

**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function pesan(){
            alert ("Memanggil Javascript dengan Body Onload")
        }
    </script>
</head>
<body onload=pesan()>
    
   
</body>
</html>
```

**Outputnya:**

![Fungsi_Onload](img/onload.png)



# Dasar Pemrograman pada Javascript


## 6). Operasi Dasar Aritmatika


**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(4,7)>
</body>
</html>
```


**Output:**

![Aritmatika](img/aritmatika.png)



## 7). Seleksi Kondisi (IF/ELSE)

**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pengaplikasian if-else</title>
</head>
<body>
    <script lang="javascript">
        var nilai = prompt("Nilai (0-100):", 0);
        var hasil = "";
        if (nilai >59)
        hasil = "Lulus";
        else
        hasil = "Tidak Lulus";
        document.write("hasil: "+hasil);
    </script>
</body>
</html>
```


**Output:**

![Seleksi_IfElse](img/if-else1.png)

Karena nilai yang dimasukkan adalah "55" dengan minimal nilai untuk lulus adalah "59", maka hasilnya adalah "Tidak Lulus"

![Hasil](img/if-else2.png)



## 8). Penggunaan Operator Switch untuk Seleksi Kondisi


**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penggunaan Operator Switch</title>
    <script lang="javascript">
        function test ()
        {
            val1=window.prompt("Input Nilai (1-5):")
            switch (val1)
            {
                case "1":
                    document.write("Bilangan Satu")
                    break
                case "2":
                    document.write("Bilangan Dua")
                    break
                case "3":
                    document.write("Bilangan Tiga")
                    break
                case "4":
                    document.write("Bilangan Empat")
                    break
                case "5":
                    document.write("Bilangan Lima")
                    break
                default :
                    document.write("Bilangan Lainnya")
            }
        }

    </script>
    
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

**Output:**

![Operator_Switch](img/operator-switch1.png)


Dengan hasil sebagi berikut:

![Operator_Switch](img/operator-switch2.png)


# Pembuatan Form


## 9). Form Input

**Coding:**

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form input</title>
    <script lang="javascript">
        function test () {
            var val1=document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil"
        }
    </script>
</head>
<body>
    <form action="" method="post" name="kirim">
        <p>BIL <input type="text" name="T1" id="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" id="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```


**Output:**

![Form_Input](img/forminput.png)


## 10). Form Button

**Coding:**

```html

```


**Output:**



# HTML DOM


## 11). Pilihan Menggunakan Checkbox Dengan Perhitungan Otomatis

**Coding:**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar Menu</title>
    <script lang="javascript">
        function hitung(ele) {
            var total=document.getElementById('total').value;
                total=(total?parseInt(total):0)
            var harga=0;

            if(ele.checked) {
                harga=ele.value;
                total+=parseInt(harga);
            } else{
                harga=ele.value;
                if(total>0)
                total-=parseInt(harga);
            }
            document.getElementById('total').value=total;
        }
    </script>
</head>
<body>
    <h1>Daftra Menu Minuman</h1>
    <label><input type="checkbox" value="5000"  name="menu1" id="menu1" onclick="hitung(this);"> Iced Tea Rp. 5.000</label><br>
    <label><input type="checkbox" value="7000"  name="menu2" id="menu2" onclick="hitung(this);"> Choco Milk Rp. 7.000</label><br>
    <label><input type="checkbox" value="4000"  name="menu3" id="menu3" onclick="hitung(this);"> Water Rp. 4.000</label><hr>
    <strong>Total Bayar : Rp. <input type="text" name="total" id="total"></strong>
</body>
</html>
```


**Output:**

![Perhitungan_Otomatis](img/checkboxperhitunganotomatis.png)
