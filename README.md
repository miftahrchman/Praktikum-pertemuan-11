# Latihan
Ubahlah kode dibawah ini menjadi fungsi menggunakan lambda. import math

def a(x): return x**2

def b(x, y): return math.sqrt(x2 + y2)

def c(*args): return sum(args)/len(args)

def d(s): return "".join(set(s))

PROGRAM LATIHAN

![Latihan ](https://github.com/user-attachments/assets/92aa1b41-57db-43a6-bd56-be3e0effb719)

HASIL PROGRAM LATIHAN

![Hasil latihan](https://github.com/user-attachments/assets/8b8ca7d6-689a-4164-ab3b-c05509d607e1)

PENJELESAN LATIHAN


    Fungsi a:
        Menghitung kuadrat dari x.
        Diubah menjadi: a = lambda x: x**2

    Fungsi b:
        Menghitung akar kuadrat dari jumlah kuadrat x dan y.
        Diubah menjadi: b = lambda x, y: math.sqrt(x**2 + y**2)

    Fungsi c:
        Menghitung rata-rata dari argumen yang diberikan.
        Diubah menjadi: c = lambda *args: sum(args) / len(args)

    Fungsi d:
        Menghapus karakter duplikat dari string dan menggabungkannya kembali.
        Diubah menjadi: d = lambda s: "".join(set(s))


# PRAKTIKUM 
Buat program sederhana dengan mengaplikasikan penggunaan fungsi
yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
• Fungsi tambah() untuk menambah data
• Fungsi tapilkan() untuk menampilkan data
• Fungsi hapus(nama) untuk menghapus data berdasarkan nama
• Fungsi ubah(nama) untuk mengubah data berdasarkan nama

• Buat flowchart dan penjelasan programnya pada README.md.
• Commit dan push repository ke github

PROGRAM PRAKTIKUM

![Praktikum](https://github.com/user-attachments/assets/beb14ea3-1c9f-4dc5-aaad-5faaa2dcca12)

HASIL PROGRAM PRAKTIKUM

![Hasil Praktikum](https://github.com/user-attachments/assets/ced8f7e7-cbc8-4c79-b0ca-e9a9d28c45f1)

PENJELASAN PROGRAM PRAKTIKUM


    Daftar Mahasiswa:
        Program ini menggunakan list bernama mahasiswa untuk menyimpan data mahasiswa. Setiap elemen dalam list adalah dictionary yang berisi nama dan nilai mahasiswa.

    Fungsi tambah(nama, nilai):
        Fungsi ini digunakan untuk menambahkan data mahasiswa ke dalam list mahasiswa.
        Parameter:
            nama: Nama mahasiswa yang akan ditambahkan.
            nilai: Nilai mahasiswa yang akan ditambahkan.
        Fungsi ini menambahkan dictionary baru ke list dan mencetak pesan konfirmasi bahwa data telah berhasil ditambahkan.

    Fungsi tampilkan():
        Fungsi ini digunakan untuk menampilkan semua data mahasiswa yang ada dalam list.
        Jika list mahasiswa kosong, fungsi akan mencetak pesan bahwa tidak ada data mahasiswa.
        Jika ada data, fungsi akan mencetak daftar nama dan nilai setiap mahasiswa.

    Fungsi hapus(nama):
        Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan nama.
        Fungsi ini menggunakan list comprehension untuk membuat list baru yang hanya berisi mahasiswa yang namanya tidak cocok dengan nama yang diberikan.
        Setelah menghapus, fungsi mencetak pesan konfirmasi bahwa data mahasiswa telah berhasil dihapus.

    Fungsi ubah(nama, nilai_baru):
        Fungsi ini digunakan untuk mengubah nilai mahasiswa berdasarkan nama.
        Fungsi ini mencari mahasiswa dalam list berdasarkan nama. Jika ditemukan, nilai mahasiswa diubah menjadi nilai_baru, dan fungsi mencetak pesan konfirmasi.
        Jika nama tidak ditemukan dalam list, fungsi akan mencetak pesan bahwa data mahasiswa tidak ditemukan.

  FLOWCHART 
  
  ![image](https://github.com/user-attachments/assets/1641e93a-7e16-4083-bd30-db6b73a3d0f7)





