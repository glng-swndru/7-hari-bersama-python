**Hari 1: Pengenalan Python**
**Program Pertama: Hello World**

Ketika seseorang belajar pemrograman, tradisi yang biasa dilakukan adalah memulai dengan program Hello, World. Program sederhana ini memverifikasi bahwa Anda telah menginstal alat Python dengan benar.
1. Dari panel navigasi di IDE, buat file baru dengan nama `hello_world.py`.
2. Di dalam file tersebut, masukkan kode berikut:

    ```python
    print("Hello, World")
    ```
3. Untuk menyimpan file, pilih File > Save.
4. Di bagian atas jendela IDE, pilih tombol Run (Play).
5. Di panel bawah IDE, pastikan program mencetak kata "Hello, World".

Selamat! Anda telah menulis program Python pertama Anda.

**Menjalankan Python di VSCode**

1. Buka Visual Studio Code (VSCode).
2. Pastikan Anda telah menginstal ekstensi Python di VSCode.
3. Buka terminal di VSCode (View > Terminal).
4. Jalankan perintah berikut untuk memastikan Python terinstal dengan benar:
    ```sh
    python --version
    ```

**Komentar**

Komentar digunakan untuk menambahkan catatan dalam kode Anda yang tidak akan dieksekusi oleh Python. Komentar ditandai dengan simbol `#`.
Contoh:
```python
# Ini adalah komentar
print("Hello, World")  # Ini juga komentar
```

**Variabel**

Variabel digunakan untuk menyimpan data yang dapat digunakan kembali di dalam program.
Contoh:
```python
nama = "Gilang"
umur = 23
print(nama)
print(umur)
```

**Konstanta**

Konstanta adalah variabel yang nilainya tidak berubah. Dalam praktiknya, Python tidak memiliki konstanta bawaan, tetapi Anda bisa menggunakan huruf besar untuk menandai bahwa variabel tersebut harus diperlakukan sebagai konstanta.
Contoh:
```python
PI = 3.14
GRAVITASI = 9.8
```
**Tipe Data**
Python memiliki beberapa tipe data dasar:
- *String*:Teks, dikelilingi oleh tanda kutip.
```python
teks = "Hello"
```