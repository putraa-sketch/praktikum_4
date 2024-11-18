# PRAKTIKUM 4

## Step 1
mulai dengan membuat list kosong bernama data_mahasiswa. List ini akan berfungsi sebagai wadah untuk menyimpan semua data yang akan dimasukkan oleh pengguna.

![Screenshot 2024-11-18 130744](https://github.com/user-attachments/assets/948b9dfe-19ee-44dc-a659-64cb6aa4fd40)

## Step 2
Menggunakan sebuah perulangan while True untuk meminta pengguna memasukkan data secara berulang. Perulangan ini akan terus berjalan sampai pengguna memutuskan untuk berhenti. Di dalam perulangan, program akan menampilkan pesan untuk memasukkan data mahasiswa.

![Screenshot 2024-11-18 130914](https://github.com/user-attachments/assets/614dd565-e5cc-4a34-b31d-54323bcfb3e9)

## Step 3
Pada bagian ini, program akan meminta pengguna untuk menginput nama mahasiswa, nilai tugas, nilai UTS, dan nilai UAS. Nilai tugas, UTS, dan UAS dimasukkan sebagai angka desimal (float) untuk memungkinkan input nilai dengan angka pecahan (misalnya 85.5).

Setelah pengguna memasukkan data, program akan menghitung nilai akhir mahasiswa. Rumus yang digunakan untuk menghitung nilai akhir adalah sebagai berikut:

* 30% dari nilai tugas
* 35% dari nilai UTS
* 35% dari nilai UAS

![Screenshot 2024-11-18 131300](https://github.com/user-attachments/assets/bdf5ac2d-b50b-445b-a365-1898a0586dcc)

## Step 4
Setelah nilai akhir dihitung, program menyimpan semua informasi yang sudah dimasukkan (nama, nilai tugas, UTS, UAS, dan nilai akhir) ke dalam list data_mahasiswa. Data tersebut disimpan dalam bentuk dictionary agar lebih terstruktur.

![Screenshot 2024-11-18 131622](https://github.com/user-attachments/assets/8c722a16-d80e-4e97-8050-aa499dbb820e)

## Step 5
Setiap kali data mahasiswa baru ditambahkan, program akan menanyakan apakah pengguna ingin menambahkan data mahasiswa lain. Jika pengguna menjawab 'y', program akan kembali ke awal perulangan dan meminta input data lagi. Namun, jika pengguna menjawab 't', program akan keluar dari perulangan dan mulai menampilkan daftar data yang sudah dikumpulkan.

![Screenshot 2024-11-18 131826](https://github.com/user-attachments/assets/8becc085-1fdf-4523-8437-af4de5049b9a)

## Step 6
Setelah keluar dari perulangan, program akan mencetak daftar seluruh mahasiswa beserta nilai-nilai mereka dalam format tabel. Program menggunakan perulangan for untuk membaca setiap elemen dalam list data_mahasiswa dan menampilkannya satu per satu.

![Screenshot 2024-11-18 131942](https://github.com/user-attachments/assets/38779678-ca69-4f77-993e-5c6be1da812f)

# OUTPUT
Maka, program akan menghasilkan output seperti berikut:

<img width="376" alt="image" src="https://github.com/user-attachments/assets/fb41082f-77a2-43cd-9464-b4887b4cb4d5">

# Flowchart

## Step 1 : Start
Titik Mulai:

<img width="116" alt="image" src="https://github.com/user-attachments/assets/8daec912-6ee1-4496-98eb-cb89c834b7e5">


## Step 2 : Input Data Mahasiswa
Buatkan Input Data Mahasiswa dengan mencangkup Nama, Nim, Nilai Tugas, Nilai UTS, Nilai UAS :

<img width="217" alt="image" src="https://github.com/user-attachments/assets/65446ad8-b89c-4280-b473-5b44169d2554">


## Step 3 : Lakukan Seleksi
Langkah selanjutnya yaitu buatkan decision atau seleksi berupa pertanyaan Menambahkan Data Mahasiswa (Y/T?), jika Ya maka kemabli ke Input Data mahasiswa, jika Tidak maka lanjut ke langkah selanjutnya :

<img width="248" alt="image" src="https://github.com/user-attachments/assets/f64af659-32ed-42f7-a6ab-0a6b33a34ec5">


## Step 4 : Proses Perhitungan
Langkah ini untuk memproses Nilai Akhir dari Input nilai nilai yang telah dimasukan :

![ss11](https://github.com/user-attachments/assets/54c1c0e0-8f3a-4b2e-b984-40852ea21a48)


## Step 5 : Output Nilai Akhir
Masuk kelangkah Akhir yaitu menampilkan Nilai Akhir dari Data Mahasiswa yang telah diinputkan dan sudah dihitung :

![ss12](https://github.com/user-attachments/assets/78bc7ae5-a0b4-4669-b49e-930112d101df)


## Step 6 : End
Titik Berhenti :

![ss13](https://github.com/user-attachments/assets/953a7b0d-17a9-49b0-9c84-8a12631743e2)


# KESIMPULAN :
Kesimpulan dari Laporan Praktikum ini adalah penggunaan append yaitu dapat menambahkan element lain, jika kita perhatikan penggunaan perulangan sangat membantu untuk memastikan jika ada tambahan data yang diinputkan, namun dari semua itu semua adalah kelas dari sebuah List dari tema praktikum kali ini. Penggunaan List berguna untuk mengetahui apa saja yang ada di dalam data, List mampu menampung beberapa element berbeda.




