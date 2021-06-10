Tugas kelompok dari :
- Jonathan Steven Iskandar (203400006)
- Margareta Yezitesa Marlin (203400009)

Dosen Pengampu dari MatKul Sistem Operasi :
- Stephanus Surijadarma Tandjung, A.Md., S.T., M.T., Ph.D (Dosen Ilmu Infomatika)

Buku yang digunakan : Sistem Operasi Operating System Concepts Essentials 2nd Edition[Conflict]

Soal yang dikerjakan Exercise 5.43, adalah sebagai berikut :
5.43.) Exercise 4.22 asked you to design a multithreaded program that estimated π using the Monte Carlo technique.
In that exercise, you were asked to create a single thread that generated random points, storing the result in a global variable.
Once that thread exited, the parent thread performed the calcuation that estimated the value of π.
Modify that program so that you create several threads, each of which generates random points and determines if the points fall within the circle.
Each thread will have to update the global count of all points that fall within the circle.
Protect against race conditions on updates to the shared global variable by using mutex locks.

Tugas jawaban dosen dari pembahasan soal diatas, adalah sebagai berikut :
Soal ke-1.) Untuk apakah tujuan program ini? 
Soal ke-2.) Section berapa yang me jelaskan program ini?
Soal ke-3.) Jelaskan logika program ini!
Soal ke-4.) Apa guna source code ini?
Soal ke-5.) File penjelasan dan source code dimasukkan ke github

Note/Catatan untuk soal nomer 5 :
Kelompok kami berusaha merubah program kemarin ke bentuk mutex, tetapi masih ada kendala di Cygwin dan kesalahan masih sama seperti kemarin.
Setelah itu kami mencoba program tersebut di coba compailer online. 
Saat kami mencoba compailer Programiz itu tidak bisa, tetapi saat mencoba compailer lainnya (bernama, OnlineGDB) itu berhasil.
Link compailer : https://www.onlinegdb.com/online_c_compiler
