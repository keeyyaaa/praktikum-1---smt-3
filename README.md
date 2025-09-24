# praktikum-1-smt3
## Praktikum 1 Pemrograman Web - HTML Dasar

Nama: Ica Rizqiah

NIM: 312410554

Kelas: TI.24.A.5

### Membuat file baru ```lab1_tag_dasar.html```
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230008.png)

### ```hasil```
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230035.png)

#### Penjelasan
1. ```<!DOCTYPE html>```

adalah deklarasi yang ditempatkan di baris pertama sebuah dokumen HTML. Fungsinya untuk memberi tahu browser bahwa dokumen tersebut menggunakan standar HTML5. Dengan adanya deklarasi ini, browser dapat menampilkan halaman web sesuai aturan yang berlaku.

2. ```html```
Tag ```<html>``` merupakan tag utama yang membungkus seluruh isi dokumen HTML. Semua elemen, baik bagian <head> maupun ```<body>```, harus berada di dalam tag ini. Bisa dibilang, ```<html>``` adalah pondasi atau kerangka besar dari sebuah halaman web.

3. ```<head> ... </head>```
Tag ```<head>``` berisi informasi tentang halaman web, bukan isi konten yang ditampilkan ke pengguna. Di bagian ini biasanya terdapat:

```<title>``` → untuk menampilkan judul halaman di tab browser.

```<meta>``` → menyimpan informasi tambahan seperti karakter encoding.

```<link>``` → menghubungkan dokumen dengan file CSS.

```<script>``` → menambahkan atau menghubungkan kode JavaScript.

4. ```<title> ... </title>```
Tag ```<title>``` berada di dalam ```<head>```. Isinya akan tampil sebagai judul pada tab browser. Walaupun tidak muncul langsung di isi halaman, tag ini penting karena juga memengaruhi SEO (Search Engine Optimization) dan memudahkan identifikasi halaman.

5. ```<body> ... </body>```
Tag ```<body>``` berisi seluruh konten utama halaman web yang terlihat oleh pengguna di browser. Semua teks, paragraf, gambar, hyperlink, tabel, maupun elemen interaktif lainnya ditulis di dalam tag ini.

### Membuat modul praktikum Pemrograman web
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230258.png)

### Hasil
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230310.png)

## 1. Membuat paragraf
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230812.png)
```html
<!-- Ini adalah paragraf pertama --> 
<p>Halo ini kia, kami sedang belajar HTML dasar, pada matakuliah Pemrograman Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p> 
<!-- Ini adalah paragraf kedua --> 
<p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan tag dasar html.</p>
```

### ```hasil```
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20230800.png)
#### ```Penjelasan```
1. Tag dasar ```<p>``` adalah untuk menambahkan paragraf.

2. Fungsi Komentar ```<!-- ... -->```
Fungsi utama komentar adalah:

- Memberi catatan atau penjelasan tambahan di dalam kode, supaya lebih mudah dipahami ketika dibaca ulang.

- Menyembunyikan bagian kode sementara tanpa harus menghapusnya, biasanya dilakukan saat proses uji coba.

- Memudahkan kerja tim (jika ada), karena setiap orang bisa paham maksud dari potongan kode tertentu lewat catatan yang ditulis.
  
### Mencoba atribut paragraf
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231035.png)

### Hasil
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231013.png)

#### Penjelasan atribut
```html
<h3>Perataan Teks</h3>

<p align="left">Ini teks rata kiri.</p>
<p align="right">Ini teks rata kanan.</p>
<p align="center">Ini teks rata tengah.</p>
<p align="justify">
    Ini teks rata kiri-kanan. Kalau kalimatnya panjang, 
    maka tepinya akan terlihat lurus di kiri dan kanan.
</p>
```

## 2. Menambahkan judul
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231410.png)

```html
<!-- judul paragraf pertama --> 
<h1>Belajar Dasar HTML</h1> 
<!-- judul paragraf kedua --> 
<h2>Paragraf pada HTML</h2>
```
### Hasil
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231358.png)

#### Penjelasan atribut

Dalam HTML, heading digunakan untuk membuat judul dan subjudul pada sebuah halaman web. Heading ini ditandai dengan tag ```<h1>``` sampai ```<h6>```, di mana:

```<h1>``` adalah judul utama (paling besar).

```<h2>``` adalah subjudul dari ```<h1>```.

```<h3>``` adalah subjudul dari ```<h2>```, dan seterusnya sampai ```<h6>```.

Semakin besar angka pada tag heading, semakin kecil ukuran teks yang ditampilkan di browser.

## 3. Memformat teks
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231927.png)

### Hasil
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20231940.png)

#### Penjelasan
Pemformatan Teks pada HTML

Pemformatan teks dalam HTML digunakan untuk memberikan gaya khusus pada tulisan sehingga lebih jelas dan mudah dipahami. Beberapa tag yang sering dipakai antara lain:

1. ```<b>``` → membuat teks menjadi tebal.

2. ```<strong>``` → menandai teks yang dianggap penting (biasanya juga tebal).

3. ```<i>``` → membuat teks miring.

4. ```<em>``` → menandai teks yang diberi penekanan (biasanya miring).

5. ```<u>``` → menambahkan garis bawah pada teks.

6. ```<mark>``` → memberi efek highlight pada teks (seperti stabilo).
   
## 4. Menyisipkan gambar
![foto](https://github.com/keeyyaaa/praktikum-1---smt-3/blob/main/Screenshot%202025-09-24%20233652.png)

![foto](

### Hasil
![foto]()

### Mengubah ukuran gambar
![foto](

### Hasil
![foto]()

## 5. Menambahkan hyperlink
