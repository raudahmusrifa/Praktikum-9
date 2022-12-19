# Praktikum-9

**Nama : Raudah Musrifa**

**Nim : 312210020**

# Contoh dan Penjelasan Modul Praktikum 13

**1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.**

![9 1](https://user-images.githubusercontent.com/115474431/208325679-32b2a6d7-6bec-45ba-81da-af0f0fff00c1.png)

**Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... AssertionError artinya terjadi error pada pernyataan assert.**

**2. Contoh ini untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.**

![9 2](https://user-images.githubusercontent.com/115474431/208325698-f8090b51-2d0d-42d8-b4af-5b3050448b29.png)

**Hasilnya :**

    Written content in the file successfully

**Hasilnya seperti ini karena else akan dijalankan ketika try adalah True**

**3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.**

![9 3](https://user-images.githubusercontent.com/115474431/208325714-34a7a4fa-5f7d-46be-bc50-7c2845a2a770.png)

    **Mengapa hasilnya error?**

**r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.**

**4. Contoh keempat**

![9 4](https://user-images.githubusercontent.com/115474431/208325740-9c05544c-6dfe-43f4-8174-429763de0d1d.png)

**Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.**

**5. Contoh single exception**

![9 5](https://user-images.githubusercontent.com/115474431/208325758-38bb83d3-3ad2-429d-b68b-628581d52d40.png)

**Hasilnya :**

		The argument does not contain numbers 

		invalid literal for int() with base 10: 'xyz'

**ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.**

**6. Contoh dan penjelasan keenam**

![9 6](https://user-images.githubusercontent.com/115474431/208325807-2b545b12-fac9-4c01-9ff0-68aa42034458.png)

**Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.**

**Selesai**




