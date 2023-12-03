# Lab9Web

# Nama : Naza Sefti Prianita

# NIM : 312210306

# Kelas : TI.22.A3

# Instruksi Praktikum 

   1. Persiapkan editor teks misalnya VSCode
   2. Buat folder baru dengan nama lab9_php_modular pada docroot webserver(htdocs)
   3. Ikuti langkah-langkah praktikum

# Jalankan XAMPP dan akses http://localhost/phpmyadmin/untuk membuat database.

# ![image](https://github.com/Nazasefti/Lab9Web/assets/115772516/21f6cec8-4c5e-456e-8797-3dc2e063a70f)

# Buat file lab9_php_modular pada direktori root server web (c:\xampp\htdocs)

# ![image](https://github.com/Nazasefti/Lab9Web/assets/115772516/89b052be-b422-4fec-a453-f5af57df3719)

# Buat file baru dengan nama header.php

         <!DOCTYPE html>
         <html lang="en">
         <head>
             <meta charset="UTF-8">
             <title>Contoh Modularisasi</title>
             <link href="style.css" rel="stylesheet" type="text/stylesheet"media="screen" />
         </head>
         <body>
             <div class="container">
                 <header>
                     <h1>Modularisasi Menggunakan Require</h1>
                 </header>
                 <nav>
                     <a href="home.php">Home</a>
                     <a href="about.php">About</a>
                     <a href="kontak.php">Kontak</a>
                 </nav>
# Buat file baru dengan nama footer.php

         <footer>
             <p>&copy; 2023, Informatika, Universitas Pelita Bangsa</p>
         </footer>
         </div>
         </body>
         </html>

# Buat file baru dengan nama home.php

         <?php require('header.php'); ?>
         
         <div class="content">
             <h2>Ini Halaman Home</h2>
             <p>Ini adalah bagian content dari halaman.</p>
         </div>
         
         <?php require('footer.php'); ?>

# Buat file baru dengan nama about.php 

         <?php require('header.php'); ?>
         
         <div class="content">
             <h2>Ini Halaman About</h2>
             <p>Ini adalah bagian content dari halaman.</p>
         </div>
         
         <?php require('footer.php'); ?>

         
