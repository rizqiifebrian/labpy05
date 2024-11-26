# praktikum5.py

Nama : Rizqi febrian arrahman <p>
NIM : 312410544 <p>
Kelas : TI.24.A.5 <p>
Mata kuliah : Bahasa Pemrograman <p>

# program input nilai
flowcahrt

![flowchart](https://github.com/user-attachments/assets/d5fe20aa-c731-4f25-9f4f-ac4f15651803)

# penjelasan perogram
1. judul perogram

![judul perogram](https://github.com/user-attachments/assets/df1886ea-40f0-4edc-84d5-7735b804fc9f)

Baris ini mencetak judul program dan garis pemisah untuk memberikan konteks kepada pengguna.

2. Kelas Student

![class student](https://github.com/user-attachments/assets/38e6df2a-6784-4834-9ae4-72301280c378)

Kelas Student: Kelas ini digunakan untuk merepresentasikan seorang mahasiswa
__init__ Method: Ini adalah konstruktor yang dipanggil saat objek Student dibuat. Ini menerima NIM, nama, nilai tugas, UTS, dan UAS sebagai parameter. Nilai akhir dihitung dengan memanggil metode calculate_final_grade.

![bagian class student 2](https://github.com/user-attachments/assets/d12ce765-b99b-4d61-965c-9059a661a431)

calculate_final_grade Method: Metode ini menghitung nilai akhir berdasarkan bobot yang ditentukan untuk tugas, UTS, dan UAS, kemudian membulatkannya hingga dua desimal.

3.fungsi display_menu

![desplay menu](https://github.com/user-attachments/assets/f97ca246-89d6-4d54-bf79-f789153e0a47)

Fungsi ini menampilkan menu pilihan kepada pengguna untuk melihat, menambah, mengubah, menghapus, atau mencari data mahasiswa.

4.Fungsi display_students

![display student](https://github.com/user-attachments/assets/b17fadf2-b79f-4e3c-8160-8afa2222313b)

Fungsi ini menampilkan daftar mahasiswa dalam format tabel. Jika tidak ada mahasiswa, akan menampilkan pesan "TIDAK ADA DATA".

5. Fungsi find_student_index

![find student index](https://github.com/user-attachments/assets/87f83a42-537e-489f-a9e9-29d63162af9c)

Fungsi ini mencari indeks mahasiswa berdasarkan NIM. Jika ditemukan, mengembalikan indeksnya; jika tidak, mengembalikan None

6. Fungsi main

![fungsi main](https://github.com/user-attachments/assets/84b81da9-306f-471b-ac97-4f4d1cdace15)

Fungsi main adalah titik masuk program. Ini menginisialisasi daftar mahasiswa dan memasuki loop untuk menerima input dari pengguna.

Menangani Pilihan Pengguna
Tambah Mahasiswa ('t'):

Meminta input NIM, nama, dan nilai, kemudian menambahkan objek Student ke dalam daftar students.
Lihat Mahasiswa ('l'):

Memanggil fungsi display_students untuk menampilkan daftar mahasiswa.
Ubah Mahasiswa ('u'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin diubah, dan jika ditemukan, meminta input baru dan memperbarui data mahasiswa.
Hapus Mahasiswa ('h'):

Menampilkan daftar mahasiswa, meminta NIM mahasiswa yang ingin dihapus, dan jika ditemukan, menghapus data mahasiswa dari daftar.
Cari Mahasiswa ('c'):

Meminta NIM mahasiswa yang dicari dan menampilkan detailnya jika ditemukan.
Keluar ('k'):

Menghentikan loop dan keluar dari program.
Pilihan Tidak Valid:

Jika pilihan tidak dikenali, menampilkan pesan bahwa pilihan tidak valid.

7. Menjalankan Program

![menjalankan perogram](https://github.com/user-attachments/assets/0d5ae079-b362-413e-aaa9-d1c1cff536ff)

 Baris ini memastikan bahwa fungsi main hanya akan dijalankan jika file ini dieksekusi sebagai program utama, bukan jika diimpor sebagai modul.

# hasil perogram
1. Menjalankan Program Setelah menjalankan program, Anda akan melihat output awal seperti ini:


![hasil 1](https://github.com/user-attachments/assets/18a44cdf-ef9d-480d-9cb3-a24f1c1e6d16)

2. Menampilkan Menu Program akan menampilkan menu pilihan:

![menampilkan menu](https://github.com/user-attachments/assets/9fdc938a-9a3d-4b30-a613-2af026754118)

3. Menambah Mahasiswa Jika Anda memilih untuk menambah mahasiswa dengan memasukkan 'T', program akan meminta Anda untuk memasukkan data:

![3](https://github.com/user-attachments/assets/0b5e1b7f-4d33-4b4d-a658-d1030ae5b672)


   
4. Melihat Daftar Mahasiswa Jika Anda memilih 'L', program akan menampilkan daftar mahasiswa:

![l](https://github.com/user-attachments/assets/27d97645-a62f-425a-8539-d4d7dfd55fac)


   
5. Mengubah Data Mahasiswa Jika Anda memilih 'U' dan memasukkan NIM mahasiswa yang ingin diubah:

![u](https://github.com/user-attachments/assets/852df702-1479-402f-8a3f-7b29d571dd76)


 
6. Melihat Daftar Mahasiswa Setelah Diubah Memilih 'L' lagi untuk melihat daftar mahasiswa setelah perubahan:

![hasil u](https://github.com/user-attachments/assets/18e01475-42a0-48e6-95a3-e374842da9bc)



7. Menghapus Mahasiswa Jika Anda memilih 'H' untuk menghapus mahasiswa:

![Screenshot 2024-11-26 144205](https://github.com/user-attachments/assets/d4102d0f-4f1a-44f9-b1c2-4a8d465c6a5c)



8. Mencari Mahasiswa Jika Anda memilih 'C' untuk mencari mahasiswa:

![Screenshot 2024-11-26 144235](https://github.com/user-attachments/assets/3b5b958e-86c9-4e9a-acee-2bc38dadb6a1)



9. Keluar dari Program Jika Anda memilih 'K', program akan berhenti:

![Screenshot 2024-11-26 144243](https://github.com/user-attachments/assets/320f25e6-a4a3-4ce3-a18c-3c57b11ccbfb)

