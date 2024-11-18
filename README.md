# Praktikum-ke-6

### Nama : Arifin Syahrul Azhadi Harahap

### NIM : 352310965

### Kelas : IE.23.C.13

### Mata Kuliah : Program Komputer + Praktek

### Dosen : Agung Nugroho, S.Kom., M.Kom.
_________________________________________________________________________________________________________________________________________________________________________________________

## "Membuat program sederhana pada pyhton menggunakan "List"

## A. Algoritma Program

1. Start

2. Inisialisasi:
  Buat sebuah daftar kosong data_mahasiswa untuk menyimpan data mahasiswa.

3. Perulangan:
   
-Tampilkan pesan: "Masukkan data mahasiswa:"
   
-Input:

   => nama → masukkan nama mahasiswa.

   => nim → masukkan NIM mahasiswa.

   => nilai_tugas → masukkan nilai tugas.

   => nilai_uts → masukkan nilai UTS.

   => nilai_uas → masukkan nilai UAS.
   
4. Hitung nilai akhir:
   
Gunakan rumus:

nilai_akhir=(nilai_tugas×0.3)+(nilai_uts×0.35)+(nilai_uas×0.35)

5. Simpan data ke daftar data_mahasiswa:

Data yang disimpan mencakup: nama, nim, nilai_tugas, nilai_uts, nilai_uas, dan nilai_akhir.
  
6. Tanya pengguna:

=> "Tambah data lagi (y/t)?"

=> Jika jawabannya "y", ulangi langkah input data.

=> Jika jawabannya "t", keluar dari perulangan.

7. Tampilkan data mahasiswa dalam bentuk tabel:
   
=> Cetak header tabel: No | Nama | NIM | Tugas | UTS | UAS | Akhir.

=> Gunakan perulangan untuk mencetak data dari daftar data_mahasiswa.

8. End

## B. Gambar Flowchart Program 

![Flowchart 6 drawio](https://github.com/user-attachments/assets/9739e8c1-f9d5-4b7c-b9ba-d014b0af6169)

## C. Menampilkan Penjelasan Program Yang telah dibuat menggunakan program "Perulangan" dan "List"

![Gambar Program](https://github.com/user-attachments/assets/b3fc1010-49cd-4931-a74e-eff8776b99e1)

Berikut Penjelasan Programnya

1. Fungsi hitung_nilai_akhir

![image](https://github.com/user-attachments/assets/01e3fef4-7e05-444e-99e0-563b874f9aad)

Fungsi ini digunakan untuk menghitung nilai akhir mahasiswa berdasarkan bobot: Tugas: 30%, UTS: 35%, UAS: 35%.

Fungsi menerima tiga parameter: tugas, uts, dan uas, lalu mengembalikan nilai akhir yang dibulatkan hingga dua desimal.

2. Variabel data_mahasiswa

![image](https://github.com/user-attachments/assets/390e172d-0c9a-4e9b-ab8e-001bf938fd4e)

Sebuah list kosong yang digunakan untuk menyimpan data semua mahasiswa. Setiap data mahasiswa akan dimasukkan ke dalam list ini dalam bentuk dictionary.

3. Perulangan untuk Input Data

![image](https://github.com/user-attachments/assets/586c651f-e9f0-404d-ba53-cee2f10b99bf)

Program memasukkan data mahasiswa satu per satu, termasuk:

=> Nama (nama),

=> NIM (nim),

=> Nilai tugas (nilai_tugas),

=> Nilai UTS (nilai_uts),

=> Nilai UAS (nilai_uas).

Input untuk nilai tugas, UTS, dan UAS dikonversi ke tipe float agar bisa dilakukan perhitungan matematika.

4. Hitung Nilai Akhir

![image](https://github.com/user-attachments/assets/07462448-55cf-470e-a41b-bfe797821c30)

Nilai akhir dihitung menggunakan fungsi hitung_nilai_akhir.

5. Simpan Data ke dalam List

![image](https://github.com/user-attachments/assets/7838298c-d3c4-4acb-b03e-37310acbe753)

Data mahasiswa disimpan dalam dictionary dengan struktur:

=> Nama: Nama mahasiswa,

=> NIM: NIM mahasiswa,

=> Tugas: Nilai tugas,

=> UTS: Nilai UTS,

=> UAS: Nilai UAS,

=> Akhir: Nilai akhir.

Dictionary tersebut ditambahkan ke dalam list data_mahasiswa.

6. Periksa Input Tambahan

![image](https://github.com/user-attachments/assets/bb5db9f8-9143-4b43-99ce-7c63418f008e)

Program menanyakan apakah pengguna ingin menambahkan data lagi:

=> Jika pengguna menjawab "y", program mengulangi langkah input data.

=> Jika pengguna menjawab selain "y" (misalnya "t"), program keluar dari perulangan.

7. Cetak Tabel Data Mahasiswa

![image](https://github.com/user-attachments/assets/1b10883a-f03e-4ce2-9d05-46e101a2a611)

Program mencetak header tabel dengan kolom:

=> No: Nomor urut,

=> Nama: Nama mahasiswa,

=> NIM: NIM mahasiswa,

=> Tugas: Nilai tugas,

=> UTS: Nilai UTS,

=> UAS: Nilai UAS,

=> Akhir: Nilai akhir.

=> Garis "=" digunakan untuk membuat tabel lebih rapi.

8. Tampilkan Data Mahasiswa

![image](https://github.com/user-attachments/assets/19e1e734-09d2-46ab-8fc0-537a41ed0a51)

Menggunakan for loop untuk mencetak data setiap mahasiswa dari list data_mahasiswa:

=> i: Nomor urut mahasiswa.

=> mahasiswa: Dictionary berisi data mahasiswa.

Data ditampilkan sesuai dengan kolom di header tabel.

9. Akhiri Program
   
Setelah semua data dicetak, program selesai.

## D. Hasil Program yang telah dijalankan dengan mengklik "Run"

![Gambar Hasil Program](https://github.com/user-attachments/assets/833288c8-3f40-4c5e-ac8b-7fba876b4e20)








