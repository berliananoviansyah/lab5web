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

