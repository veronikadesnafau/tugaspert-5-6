# TUGAS PERTEMUAN 5 DAN 6 BESERTA PENJELASANNYA

**Nama	  : Veronika Desna Ernayanti Fau** <br>
**Nim	   : 312010333** <br>
**Kelas	 : TI.20.A2** <br>
**Matkul	: Bahasa Pemrograman** <br>

## Tugas Pertemuan 5

![soalBiodata](https://user-images.githubusercontent.com/72775624/97995202-cc442b00-1e18-11eb-9e6c-95133999be3a.PNG)

#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
 ``` python
#Biodata veronika Desna Ernayanti Fau - 312010333

#mengambil input
namaLengkap = input ("nama lengkap:")
namaPendek = input ("nama panggilan:")
nim = input ("nim:")
tempatLahir = input ("tempat lahir:")
umur = input ("umur:")
alamat = input ("alamat:")
noHp = input ("no Hp:")

#menampilkan output
print("", end='\n')
print ("Assalamualaikum")
print ("Let me introduce my self.","My name is",namaLengkap,"but you can call me",namaPendek, ". My NIM is",nim, end='\n')
print ("I was born in",tempatLahir,"and i am",umur,"years old", end='\n')
print ("I am very glad if you want to invite my house in",alamat,".","So don't forget to call me before with the number",noHp)
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas

![outputBiodata]

#### ANALISIS
•	Variabel adalah merupakan tempat untuk menyimpan data yang data-data tersebut dapat diambil/dipanggil kembali apabila dibutuhkan.
Pada syntak diatas namaLengkap, namaPendek, nim, tempatLahir, umur, alamat, dan noHp merupakan variabel. <br>
•	Pada program diatas kita akan menginputkan data yang akan disimpan di variabel pada #mengambil input menggunakan syntax seperti  <br>
``` pyhton
namaLengkap = input (“nama lengkap :”)
```
Pada syntax diatas namaLengkap merupakan variabel, yang isinya akan diinput dengan perintah = input (“nama lengkap: ”) . <br>

•	Pada #menampilkan output untuk syntax dibawah ini
``` pyhton
print("", end='\n')
```
Fungsi print digunakan untuk mencetak output. <br>
Fungsi (“”, end =’\n’) digunakan untuk memberi jarak/garis baru/enter. <br>

•	Pada syntax
``` python
print ("Assalamualaikum")
print ("Let me introduce my self.","My name is",namaLengkap,"but you can call me",namaPendek, ". My NIM is",nim, end='\n')
print ("I was born in",tempatLahir,"and i am",umur,"years old", end='\n')
print ("I am very glad if you want to invite my house in",alamat,".","So don't forget to call me before with the number",noHp)
```
Bagian yang berada didalam tanda kutip seperti “My name is” akan ditampilkan/dicetak sama seperti statement tersebut, sedangkan pada ,namaLengkap, digunakan untuk memanggil data dari variabel namaLengkap yang telah diinputkan.
