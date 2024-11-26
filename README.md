# praktikum-5-
Nama :muhamad valentino tamzi <p>
NIM : 312410454 <p>
Kelas : TI.24.A.5 <p>
Mata kuliah : Bahasa Pemrograman <p>

# program input nilai
flowcahrt

![flowchart](https://github.com/user-attachments/assets/d5fe20aa-c731-4f25-9f4f-ac4f15651803)

# penjelasan program
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


![image](https://github.com/user-attachments/assets/0af140d8-6d72-4bae-8e57-123df2657f56)



2. Menampilkan Menu Program akan menampilkan menu pilihan:

![image](https://github.com/user-attachments/assets/bb48bd3d-9da8-4bde-9247-c07475de3914)




3. Menambah Mahasiswa Jika Anda memilih untuk menambah mahasiswa dengan memasukkan 'T', program akan meminta Anda untuk memasukkan data:

![image](https://github.com/user-attachments/assets/633e0950-5040-4727-aa4a-5d2884c7baec)



   
4. Melihat Daftar Mahasiswa Jika Anda memilih 'L', program akan menampilkan daftar mahasiswa:

![image](https://github.com/user-attachments/assets/1276e3f9-4147-493b-bae1-285773f44dcf)



   
5. Mengubah Data Mahasiswa Jika Anda memilih 'U' dan memasukkan NIM mahasiswa yang ingin diubah:

![image](https://github.com/user-attachments/assets/c8e7be11-756a-43b8-a262-3a887f670697)



 
6. Melihat Daftar Mahasiswa Setelah Diubah Memilih 'L' lagi untuk melihat daftar mahasiswa setelah perubahan:

![image](https://github.com/user-attachments/assets/a134bf82-d77e-4998-801d-6ea94ff0df9e)




7. Menghapus Mahasiswa Jika Anda memilih 'H' untuk menghapus mahasiswa:

![image](https://github.com/user-attachments/assets/24bdc578-7ddb-42a5-bc64-70e81ab69833)



8. Mencari Mahasiswa Jika Anda memilih 'C' untuk mencari mahasiswa:

![image](https://github.com/user-attachments/assets/2f471f4d-7741-453e-add3-f74c0d41737f)



9. Keluar dari Program Jika Anda memilih 'K', program akan berhenti:

![image](https://github.com/user-attachments/assets/e1df6e24-c7e8-4d86-b294-a6fb9def417e)



