|  | Pemrograman Berbasis Framework 2024 |
|--|--|
| NIM |  2341728027|
| Nama |  Andi Fadhil Akbar Syahbana |
| Kelas | TI - 3A |

Praktikum 1

Pada file pages yang dibuat sesuai pada soal terdapat beberapa yang perlu di ubah sehingga menampilkan hasil nya.
 button tersebut ketika diklik akan mengeluarkan tampilan berikut 
![week4](image/week%206,%201.png)

Praktikum 2

selanjutnya pada halaman login menggunakan redux, dengan mengklik tombol login maka akan ditampilkan seperti ini :
![week4](image/week%206,%202.png)

lalu jika parse yang dihapus maka hanya akan menampilkan button login saja 

![week4](image/week%206,%203.png)

Praktikum 3 

pada counter naik turun yang telah dibuat, kita dapat mengklik plus dan minus untuk melihat apakah counter dapat berjalan

![week4](image/week%206,%204.png)

Soal :

1. Apa kegunaan dari kode ini import { useEffect } from "react"; Pada file pages/_app.tsx? jelaskan

useEffect adalah hooks yang digunakan untuk melakukan side effect pada functional component, sehingga useEffect akan dijalankan setiap kali komponen di render

2. Jika pada file pages/_app.tsx kita tidak menggunakan useEffect (menghapus baris 3, dan baris 9-11, apa yang akan terjadi?

Jika useEffect dihapus, maka bootstrap tidak akan berjalan karena useEffect digunakan untuk memanggil bootstrap.min.js yang berfungsi untuk menjalankan javascript dari bootstrap. Sehingga bootstrap tidak akan berjalan dan tampilan akan berubah.

3. Mengapa di react/nextjs penulisan tag html untuk class, harus diganti menjadi className ?

Karena class jika kita menggunakan class pada tag html, maka akan terjadi error. Sehingga kita harus mengganti class menjadi className 

4. Apakah store pada nextjs bisa menyimpan banyak redux reducer?
Jelaskan kegunaan dari file store.js!

Bisa, dikarenakn store pada nextjs bisa menyimpan banyak redux reducer dimana Redux reducer adalah fungsi yang digunakan untuk mengubah state pada store

5. Pada file pages/login.tsx, apa maksud dari kode ini ?

store.js adalah file yang digunakan untuk membuat store pada nextjs dimana Store ini merupakan tempat penyimpanan state pada nextjs.

6. const { isLogin } = useSelector((state) => state.auth);
Pada file pages/counter.tsx, apa maksud dari kode ini?

Kode diatas digunakan untuk mengambil state isLogin dari store redux dan useSelector adalah hooks yang digunakan untuk mengambil state dari store redux

7. const {totalCounter} = useSelector((state) => state.counter);
Pada file pages/counter.tsx, apa maksud dari kode ini?

Kode diatas digunakan untuk mengambil state totalCounter dari store redux dan useSelector adalah hooks yang digunakan untuk mengambil state dari store redux.