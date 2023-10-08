# Lab2web

# Nama : Taufik Eka Albani
# Kelas: TI.22.A3
# Nim  : 312210347

# Praktikum 2: CSS Dasar

1. Buka VSCode.
2. Buat file baru dengan nama lab2_css_dasar.html
3. Membuat dokumen HTML
4. Buatlah dokumen HTML seperti berikut
```py
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>CSS Dasar</title>
</head>
<body>
<header>
<h1>CSS Internal dan <i>Inline CSS</i></h1>
</header>
<nav>
<a href="lab2_css_dasar.html">CSS Dasar</a>
<a href="lab2_css_eksternal.html">CSS Eksternal</a>
<a href="lab1_tag_dasar.html">HTML Dasar</a>
</nav>
<!-- CSS ID Selector -->
<div id="intro">
<h1>Hello World</h1>
<p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>Pemrograman
Web</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
dan CSS.</p>
<!-- CSS Class Selector -->
<a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
</div>
</body>
</html>
```
5. Selanjutnya buka pada browser
![Screenshot (18)](https://github.com/taufikalbani13/Lab1web/assets/115517181/b6873791-e8e6-432c-9598-f39eadf4a884)
6. Mendeklarasikan CSS Internal
7. Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.
```py
<head>
<title>CSS Dasar</title>
<style>
body {
font-family:'Open Sans', sans-serif;
}
header {
min-height: 80px;
border-bottom:1px solid #77CCEF;
}
h1 {
font-size: 24px;
color: #0F189F;
text-align: center;
padding: 20px 10px;
}
h1 i {
color:#6d6a6b;
}
</style>
</head>
```
8. save perubahan lalu buka pada browser
![Screenshot (19)](https://github.com/taufikalbani13/Lab1web/assets/115517181/ea39f7a4-1621-4997-abe7-3748ad06fbfa)
9. Menambahkan Inline CSS
10. Kemudian tambahkan deklarasi inline CSS pada tag <p> seperti berikut.
```py
<p style="text-align: center; color: #ccd8e4;">
```
11. Save perubahan lalu buka pada browser
![Screenshot (21)](https://github.com/taufikalbani13/Lab1web/assets/115517181/2dc033d6-bd1d-4c82-bcaf-b24fa3c032da)
12. Membuat CSS Eksternal
13. Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
```py
nav {
background: #20A759;
color:#fff;
padding: 10px;
}
nav a {
color: #fff;
text-decoration: none;
padding:10px 20px;
}
nav .active,
nav a:hover {
background: #0B6B3A;
}
```

15. Kemudian tambahkan tag <link> untuk merujuk file css yang sudah dibuat pada bagian <head>
```py
<head>
<!-- menyisipkan css eksternal -->
<link rel="stylesheet" href="style_eksternal.css" type="text/css">
</head>
```
16. Save perubahan lalu buka pada browser
![Screenshot (22)](https://github.com/taufikalbani13/Lab1web/assets/115517181/590a1eb9-b998-4c4a-8598-14e0cbaeebc1)
17. Menambahkan CSS Selector
18. Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file
style_eksternal.css, tambahkan kode berikut.
```py
/* ID Selector */
#intro {
background: #418fb1;
border: 1px solid #099249;
min-height: 100px;
padding: 10px;
}
#intro h1 {
text-align: left;
border: 0;
color: #fff;
}
/* Class Selector */
.button {
padding: 15px 20px;
background: #bebcbd;
color: #fff;
display: inline-block;
margin: 10px;
text-decoration: none;
}
.btn-primary {
background: #E42A42;
}
```
19. Save perubahan lalu buka pada browser
![Screenshot (23)](https://github.com/taufikalbani13/Lab1web/assets/115517181/642a3232-259b-418b-a6c9-c220aacd5bc1)


