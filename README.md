# Praktikum-9

Nama : Raudah Musrifa

Nim : 312210020

# Contoh dan Penjelasan Modul Praktikum 13

1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.

Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... AssertionError artinya terjadi error pada pernyataan assert.

2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.

Hasilnya :

Written content in the file successfully

Hasilnya seperti ini karena else akan dijalankan ketika try adalah True

3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.

Mengapa hasilnya error?

r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.

4. Contoh keempat

Hasilnya :

The argument does not contain numbers 
invalid literal for int() with base 10: 'xyz'
ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.
6. Contoh dan penjelasan keenam
prak 9-5

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.
Selesai

Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.

5. Contoh single exception

Hasilnya :
The argument does not contain numbers 
invalid literal for int() with base 10: 'xyz'

ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.
6. Contoh dan penjelasan keenam
prak 9-5

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.

Selesai




