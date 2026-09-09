
#            FORMAT SPASI OTOMATIS


Deskripsi
---------
Program Python sederhana untuk mengubah sebuah kalimat
menjadi format dengan:

- 1 spasi di antara setiap huruf.
- 3 spasi di antara setiap kata.
- Hasil otomatis disalin ke clipboard.
- Isi clipboard ditampilkan kembali sebagai verifikasi.


Contoh
------

Input:

Masukkan kalimat: hai kalian lagi apa


Output:

h a i   k a l i a n   s e d a n g   a p a


Cara Kerja
----------

1. Pengguna memasukkan sebuah kalimat.
2. Program memisahkan kalimat menjadi beberapa kata.
3. Setiap kata dipisahkan menjadi karakter-karakter.
4. Setiap karakter diberikan 1 spasi.
5. Setiap kata diberikan 3 spasi.
6. Hasil ditampilkan di terminal.
7. Hasil otomatis disalin ke clipboard.
8. Program menampilkan kembali isi clipboard sebagai verifikasi.


Persyaratan
-----------

Program ini membutuhkan:

- Python 3
- Library pyperclip


Instalasi Library
-----------------

Sebelum menjalankan program, install pyperclip dengan
perintah berikut:

pip install pyperclip


Cara Menjalankan
---------------

1. Simpan kode Python dengan nama, misalnya:

format_spasi.py


2. Buka Terminal atau Command Prompt pada folder program.

3. Jalankan program:

python format_spasi.py


4. Masukkan kalimat yang ingin diformat.

5. Hasil akan otomatis disalin ke clipboard.


Contoh Penggunaan
-----------------

Input:

saya sedang belajar python


Output:

s a y a   s e d a n g   b e l a j a r   p y t h o n


Catatan
-------

Program menggunakan fungsi:

pyperclip.copy()

untuk menyalin hasil ke clipboard.


Program juga menggunakan:

pyperclip.paste()

untuk memastikan bahwa teks berhasil disalin ke clipboard.


Author
------

Dibuat menggunakan Python.
==================================================
