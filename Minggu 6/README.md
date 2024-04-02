<div align="center">
  <h1 style="font-weight: bold">Proses dan Manajemen Proses
Sistem Operasi Minggu 6</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="tex-align: center;">
    Hazel Mangadaralam Pratama Rayes (3123500024)<br>
  </p>
  <h3 style="text-align: center;line-height: 1.5">Program Studi Teknik Informatika<br>Departemen Teknik Informatika Dan Komputer<br>Politeknik Elektronika Negeri Surabaya<br>2023/2024</h3>
  <hr>
</div>

## Daftar isi

1. [Jawaban Tugas Pendahuluan](#tugas-pendahuluan)
2. [Laporan Hasil Percobaan](#percobaan)

### Percobaan 5 : Menghentikan dan Memulai Kembali Job

1. Perintah `yes > /dev/null`

    <img src="img/5_1.png" alt="">

   <br>
   Analisa :

   <br>

2. Perintah `fg`

    <img src="img/5_2.png" alt="">

   <br>
   Analisa :

   <br>

3. Perintah `bg`

    <img src="img/5_3.png" alt="">

   <br>
   Analisa :

   <br>

4. Perintah `yes &`

    <img src="img/5_4.png" alt="">

   <br>
   Analisa :

   <br>

5. Perintah `fg %2, bg %2 atau %2`

    <img src="img/5_5.png" alt="">

   <br>
   Analisa :

   <br>

6. Perintah `fg`

    <img src="img/5_6.png" alt="">

   <br>
   Analisa :

   <br>

7. Perintah `ps -fae`

    <img src="img/5_7.png" alt="">

   <br>
   Analisa :

   <br>

### Percobaan 6 : Percobaan dengan Penjadwalan Prioritas

1. Login sebagai root

2. Buka tiga terminal,tampilkan pada screen yang sama

   <img src="img/6_1.png" alt="">

   <br>

3. Pada setiap terminal, ketik `PS1 = ” \w:”` diikuti Enter. `\w` menampilkan path pada direktori home.

   <img src="img/6_2.png" alt="">
 
    <br>
4. Karena login sebagai root, maka akan ditampilkan `~:` pada setiap terminal. Untuk setiap terminal ketik `pwd` dan tekan Enter untuk melihat bahwa Anda sedang berada pada direktori `/root`.

    <img src="img/6_3.png" alt="">
  
  <br>
5. Buka terminal lagi (keempat), atur posisi sehingga keempat terminal terlihat pada screen

   <img src="img/6_4.png" alt="">
  
  <br>

6. Pada terminal keempat, ketik `top` dan tekan *Enter*. Maka program `top` akan muncul. Ketik `i`. Top akan menampilkan proses yang aktif. Ketik `lmt`. `Top` tidak lagi menampilkan informasi pada bagian atas dari screen. Pada percobaan ini, terminal ke empat sebagai jendela `Top`.


