# Lab8
Tugas Praktikum  Mata Kuliah Program Komputer dan Praktek
==========================================================================================================================

**Deskripsi**
Program ini merupakan aplikasi berbasis teks untuk mengelola data mahasiswa menggunakan pendekatan **Object-Oriented Programming (OOP)**. 

Program ini memiliki kemampuan untuk menambahkan, menampilkan, menghapus, dan mengubah data mahasiswa.

**Fitur Program**

Menambahkan Data Mahasiswa

> Pengguna dapat memasukkan nama dan nilai mahasiswa untuk disimpan.

Menampilkan Data Mahasiswa
    
> Program akan mencetak daftar semua mahasiswa beserta nilainya.

Menghapus Data Mahasiswa

> Pengguna dapat menghapus data mahasiswa berdasarkan nama.

Mengubah Data Mahasiswa

> Pengguna dapat memperbarui nilai mahasiswa berdasarkan nama.

Menu Interaktif

> Program menggunakan menu interaktif untuk memudahkan navigasi pengguna.

**Struktur Kelas**
Class Mahasiswa

Class ini bertanggung jawab untuk mengelola data mahasiswa.

Atribut:

**__data_mahasiswa**: List privat untuk menyimpan data mahasiswa.

Metode:
**tambah(nama, nilai)**: Menambahkan data mahasiswa baru.

**tampilkan()**: Menampilkan semua data mahasiswa.

**hapus(nama)**: Menghapus data mahasiswa berdasarkan nama.

**ubah(nama, nilai_baru)** : Mengubah nilai mahasiswa berdasarkan nama.

__find_by_name(nama): Metode privat untuk mencari data mahasiswa berdasarkan nama.

**Class Menu**

Class ini bertanggung jawab untuk menyediakan antarmuka pengguna.

Atribut:

mahasiswa: Objek dari kelas Mahasiswa.

Metode:

tampilkan_menu(): Menampilkan menu utama dan menangani input pengguna.

__menu_tambah(): Menangani input untuk menambahkan data mahasiswa.

__menu_hapus(): Menangani input untuk menghapus data mahasiswa.

__menu_ubah(): Menangani input untuk mengubah data mahasiswa.

Cara Menjalankan Program

Pastikan Python sudah terinstall pada sistem Anda.

Simpan kode dalam file Python (misalnya main.py).

Jalankan file menggunakan perintah:
Tugas Lab 8.py

Pilih opsi pada menu utama sesuai kebutuhan Anda:

1: Tambah Data

2: Tampilkan Data

3: Hapus Data

4: Ubah Data

5: Keluar

**Diagram Class**

![diagram class](https://github.com/user-attachments/assets/b39bd0c5-60c0-48a2-8a15-a622b7e0312b)


**FlowChart**

![Flowchart](https://github.com/user-attachments/assets/e9131640-a2e0-4870-bace-478b3bd37aae)


**Code Program**

![Lab 8 1](https://github.com/user-attachments/assets/a4bdb9f7-9c1d-4015-8b7f-500249acb340)

![Tugas Lab 8 2](https://github.com/user-attachments/assets/3a357ae4-3fb3-4ab4-bedd-c01c78da080e)


**Hasil Program**

![Hasil Lab 8](https://github.com/user-attachments/assets/057824da-9e5c-4193-8beb-730316537bef)
