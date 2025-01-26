# UAS
## Nama : Sovy Aprianti
## NIM : 312410344
## Kelas :TI.24.A4

# SOAL
![400202552-862dfee8-c230-4ac6-9a50-dc4c934d534a](https://github.com/user-attachments/assets/10645445-a239-4014-89d4-fc72f940eb4e)

# Program
![v1](https://github.com/user-attachments/assets/18d156f2-f71e-4a03-9cac-deded8ae19ec)

![v2](https://github.com/user-attachments/assets/65b26acd-bd91-402d-87b3-c2fa0e8d9a89)

![v3](https://github.com/user-attachments/assets/59fc40e7-5fe9-436b-828a-e2cfeb117f5a)

## Penjelasan Fungsi program tersebut

Berikut adalah penjelasan fungsi-fungsi utama dalam program penilaian data siswa tersebut:

### 1. Fungsi dalam Class DataSiswa
   - **__init__(self)**: 
     - Fungsi ini adalah konstruktor yang dipanggil ketika objek dari class DataSiswa dibuat. Ia menginisialisasi list self.siswa yang digunakan untuk menyimpan data siswa.
   
   - **tambah_siswa(self, nama, nilai)**: 
     - Fungsi ini digunakan untuk menambahkan data siswa baru (nama dan nilai) ke dalam list siswa. Data siswa disimpan dalam bentuk dictionary yang berisi pasangan kunci nama dan nilai.

### 2.Fungsi dalam Class Proses
     - **validasi_nilai(nilai)**:
     - Fungsi ini memvalidasi input nilai yang dimasukkan oleh pengguna. 
     - Pertama, input nilai diubah menjadi tipe float.
     - Kemudian, fungsi memeriksa apakah nilai berada dalam rentang 0 hingga 100. 
     - Jika nilai valid, fungsi mengembalikan nilai tersebut. Jika tidak, fungsi akan melemparkan *ValueError* dengan pesan kesalahan yang sesuai.
     - Fungsi ini menggunakan konsep *eksepsi* untuk menangani input yang tidak valid (misalnya, jika nilai tidak berupa angka atau berada di luar rentang yang ditentukan).

### 3.Fungsi dalam Class Tampilan
   - **tampilkan_hasil(siswa)**:
     - Fungsi ini digunakan untuk menampilkan daftar siswa dan nilainya dalam format tabel yang terstruktur.
     - Fungsi ini menerima parameter siswa, yang merupakan list data siswa yang telah dimasukkan.
     - Fungsi mencetak header tabel, dan kemudian menampilkan data setiap siswa dalam format yang rapi, dengan kolom untuk nomor urut, nama siswa, dan nilai siswa.

### 4.Fungsi main() (Program Utama)
   - **main()**:
     - Fungsi utama yang menjalankan program dan menangani interaksi dengan pengguna.
     - Menyediakan menu dengan tiga opsi: 
       1. Menambah data siswa.
       2. Menampilkan data siswa.
       3. Keluar dari program.
     - Fungsi ini mengelola alur utama program dengan meminta input dari pengguna, memanggil fungsi-fungsi dalam class Proses untuk validasi input, dan memanggil fungsi dalam class Tampilan untuk    menampilkan data siswa dalam format tabel.
     - Jika pengguna memilih untuk menambah data siswa, input nama dan nilai akan diminta. Nilai akan divalidasi menggunakan fungsi validasi_nilai().
     - Jika memilih untuk menampilkan data siswa, fungsi tampilkan_hasil() akan dipanggil untuk menampilkan data yang telah dimasukkan.
   
### Ringkasan Fungsi:
1. **__init__(self)**: Inisialisasi data siswa.
2. **tambah_siswa(self, nama, nilai)**: Menambahkan data siswa ke dalam list.
3. **validasi_nilai(nilai)**: Memvalidasi input nilai siswa.
4. **tampilkan_hasil(siswa)**: Menampilkan data siswa dalam format tabel.
5. **main()**: Fungsi utama yang menjalankan alur program dan mengelola interaksi dengan pengguna.

Dengan pemisahan fungsi-fungsi ini, program menjadi lebih terstruktur, modular, dan mudah dikembangkan atau diperbaiki di masa depan.







