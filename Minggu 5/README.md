<div align="center">
  <h1 style="font-weight: bold">Proses dan Manajemen Proses
Sistem Operasi Minggu 5</h1>
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

## Tugas Pendahuluan

Jawablah pertanyaan-pertanyaan di bawah ini :

1. Apa yang dimaksud dengan proses ?
2. Apa yang dimaksud perintah untuk menampilkan status proses :
   `ps`, `pstree`.
3. Sebutkan opsi yang dapat diberikan pada perintah ps
4. Apa yang dimaksud dengan sinyal ? Apa perintah untuk mengirim sinyal ?
5. Apa yang dimaksud dengan proses foreground dan background pada job control ?
6. Apa yang dimaksud perintah-perintah penjadwalan prioritas :
   `top`, `nice`, `renice`

## Percobaan

1. Login sebagai user.
2. Download program C++ untuk menampilkan bilangan prima yang bernama
   primes.
3. Lakukan percobaan-percobaan di bawah ini kemudian analisa hasil percobaan.
4. Selesaikan soal-soal latihan.

### Percobaan 1 : Status Proses

1. Pindah ke command line terminal (tty2) dengan menekan Ctrl+Alt+F2
   dan login ke terminal sebagai user

2. Instruksi `ps`

   <img src="img/ps.png" alt="">
    
    <br>
   Analisa :

    <br>

3. Instruksi `ps -u`

   <img src="img/ps-u.png" alt="">

   <br>
   Analisa :

   <br>

4. Instruksi `ps -u <user>`

   <img src="img/ps-user.png" alt="">

   <br>
   Analisa :

5. Instruksi `ps -a`

   <img src="img/ps-a.png" alt="">

   <br>
   Analisa :

6. Instruksi `ps -au`

    <img src="img/ps-au.png" alt="">

   <br>
   Analisa :

### Percobaan 2 : Menampilkan Hubungan Proses Parent dan Child

1. Instruksi `ps -eH`

   <img src="img/2_1.png" alt="">

   <br>
   Analisa :
    
    <br>

2. Perintah `ps -e f`

    <img src="img/2_2.png" alt="">

   <br>
   Analisa :

   <br>

3. Perintah ` pstree`

    <img src="img/2_3.png" alt="">

    <br>
   Analisa :

   <br>

4. Perintah `pstree | grep mingetty`

    <img src="img/2_4.png" alt="">

    <br>
   Analisa :

   <br>

5. Perintah `pstree –h`

   <img src="img/2_5.png" alt="">

   <br>
   Analisa :

   <br>

### Percobaan 3 : Menampilkan Status Proses dengan Berbagai Format

1. Perintah ` ps –e | more`

   <img src="img/3_1.png" alt="">

   <br>
   Analisa :

   <br>

2. Perintah `ps ax | more`

   <img src="img/3_2.png" alt="">

   <br>
   Analisa :

   <br>

3. Perintah `ps ef | more`

    <img src="img/3_3.png" alt="">

   <br>
   Analisa :

   <br>

4. Perintah `ps –eo pid,cmd | more`

     <img src="img/3_4.png" alt="">

   <br>
   Analisa :

   <br>

5. Perintah `ps –eo pid,ppid,%mem,cmd | more`

   <img src="img/3_5.png" alt="">

   <br>
   Analisa :

   <br>

### Percobaan 4 : Mengontrol proses pada shell

1. Perintah `yes`

   <img src="img/yes.png" alt="">
   <br>
   <img src="img/4_1.png" alt="">

   <br>
   Analisa :

   <br>

2. Perintah `yes > /dev/null`

    <img src="img/4_2.png" alt="">

    <br>
   Analisa :

   <br>

3. Perintah ` yes > /dev/null &`

   <img src="img/4_3.png" alt="">

   <br>
   Analisa :

   <br>

4. Perintah `jobs`

    <img src="img/4_4.png" alt="">

   <br>
   Analisa :

   <br>
5. Perintah `kill %(nomor job) contoh : kill %1`

    <img src="img/4_5.png" alt="">

   <br>
   Analisa :

   <br>  
6. Perintah `jobs`
    
    <img src="img/4_6.png" alt="">

   <br>
   Analisa :

   <br>  



