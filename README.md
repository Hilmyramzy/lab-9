Nama:Hilmy syaddad ramzy nurfauzan

NIM:312210162


TI22A1

-Exception Handling

Exception (eksepsi) merupakan suatu kesalahan (error) yang terjadi saat proses eksekusi program sedang berjalan,
Kesalahan ini akan menyebabkan program berakhir dengan tidak normal.

-Handling

Penanganan file adalah bagian penting dari aplikasi apa pun.

-Assertion

Assertion(pernyataan) adalah kewajaran program yang kamu bisa aktif/nonaktifkan ketika kamu selesai menjalankan program.

-The Assert Statement

Saat menemukan pernyataan, Python mengevaluasi ekspresi yang menyertainya, yang mana semoga benar. Jika ekspresi salah, Python memunculkan pengecualian AssertionError.

Sintaks untuk pernyataan yaitu :
assert Expression[, Arguments]

Jika pernyataan gagal, Python menggunakan ArgumentExpression ArgumentExpression sebagai argumen argumen untuk AssertionError AssertionError. Pengecualian AssertionError Pengecualian AssertionError dapat ditangkap dan ditangani ditangani seperti pengecualian lainnya menggunakan try- kecuali pernyataan, tetapi jika dibiarkan, mereka akan menghentikan program dan menghasilkan backtrace.

Contohnya

Berikut adalah fungsi fungsi yang mengubah suhu dari derajat Kelvin menjadi derajat Fahrenheit.Karena nol derajat Kelvin dingin, fungsi fungsi menyimpannya jika melihat negatif negatif suhu.

Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:
![idle 1](https://user-images.githubusercontent.com/115677769/208601324-f40532d0-95de-4c56-9265-668607ffbad7.png)

Menangani Pengecualian
Jika Anda memiliki beberapa kode mencurigakan yang mungkin mengeluarkan pengecualian, Anda dapat mempertahankan program Anda letakkan kode yang mencurigakan di *try: blok. Setelah coba: blok, sertakan pernyataan sertakan *except: statemen, diikuti oleh blok kode yang menangani masalah seanggun mungkin.

Contoh
Contoh-contoh ini membuka file, menulis konten file, dan keluar dengan aman karena ada tidak masalah

Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:

![idle 2](https://user-images.githubusercontent.com/115677769/208601674-becab60a-5f8a-46b7-b441-0c0b3ecc7126.png)

Contoh ini mencoba membuka file yang Anda tidak memiliki izin menulis, sehingga membuat file pengecualian![idle 3](https://user-images.githubusercontent.com/115677769/208601769-db699b2f-a220-4b31-9d13-a35ea5529c44.png)

Fasal kecuali tanpa Pengecualian
Anda juga dapat menggunakan pernyataan exception tanpa exception yang didefinisikan sebagai berikut:
try: You do your operations here; ...................... except: If there is any exception, then execute this block. ...................... else: If there is no exception then execute this block.

Pernyataan coba-kecuali jenis ini menangkap semua pengecualian pengecualian yang terjadi. Menggunakan percobaan seperti try-expect pernyataan tidak dianggap sebagai praktik pemrograman yang baik, karena mereka menangkap semuanya pengecualian tetapi tidak membuat programmer mengidentifikasi kemungkinan penyebab masalah terjadi

Klausa kecuali dengan Berbagai Pengecualian
Anda juga dapat menggunakan pernyataan exception yang sama untuk menangani beberapa exception sebagai berikut:
try: You do your operations here; ...................... except(Exception1[, Exception2[,...ExceptionN]]]): If there is any exception from the given exception list, then execute this block. ...................... else: If there is no exception then execute this block.

Klausa coba-akhirnya
Contoh
Jika Anda tidak memiliki izin untuk membuka file dalam mode tulis yang dapat ditulis, maka ini akan menghasilkan hasil berikut: 

![idle 4](https://user-images.githubusercontent.com/115677769/208601996-bf40849c-1f76-41ce-877d-a2d43791663d.png)
![idle 5](https://user-images.githubusercontent.com/115677769/208602117-4f9160bd-d9c8-49ef-96a4-78e85a0dd3fc.png)

Argumen Pengecualian

Contoh
Berikut adalah contoh untuk satu pengecualian
Ketika kode di bawah dijalankan, menghasilkan hasil sebagai berikut:
![idel 6](https://user-images.githubusercontent.com/115677769/208602235-01f903dd-a22f-4e81-8cf9-5d3916348ef5.png)

Melempar Pengecualian
contoh
![idle 7](https://user-images.githubusercontent.com/115677769/208602351-1831583b-d50f-4d4c-a2b2-134ab1606dda.png)


Pengecualian yang Ditetapkan Pengguna
Python juga memungkinkan Anda membuat pengecualian sendiri dengan menurunkan kelas-kelas dari yang standar pengecualian bawaan.
Berikut adalah contoh-contoh yang terkait dengan RuntimeError. Di sini, kelas dibuat yang merupakan subkelas dari subkelas RuntimeError. Ini berguna saat Anda perlumenampilkan tampilan informasi yang lebih spesifik saat e pengecualian tertangkap.
Di blok coba, pengecualian yang ditentukan pengguna dimunculkan dan ditangkap di blok kecuali. Itu variabel e digunakan untuk membuat instance dari kelas Networkerror.
![idle 8](https://user-images.githubusercontent.com/115677769/208602558-42d62283-d7b4-4250-a45e-b1f3e3f6293d.png)


-------------------------------------SELESAI---------------------------------------

