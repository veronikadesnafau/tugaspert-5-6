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
#Biodata Veronika Desna Ernayanti Fau - 312010333

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

![outputBiodata]![2](https://user-images.githubusercontent.com/73016496/98121974-93708880-1ee2-11eb-910a-fecdb47a4c43.png)

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


### Pertemuan 6 Lab 1

![Syntaxlab1](https://user-images.githubusercontent.com/72775624/97995262-dcf4a100-1e18-11eb-86ce-194b86aacc27.PNG)

### PENGGUNAAN END
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan end
print ('A', end='')
print ('B', end='')
print ('C', end='')
print ( )
print ('X')
print ('Y')
print ('Z')
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas



#### ANALISIS
•	Perintah end berguna untuk memberi garis baru/newline namun apabila value dari end maka statement yang dicetak tidak akan memberi garis baru seperti output diatas.

### PENGGUNAAN SEPARATOR
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print (w, x, y, z)
print (w, x, y, z, sep=',')
print (w, x, y, z, sep='')
print (w, x, y, z, sep=':')
print (w, x, y, z, sep='------')
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas



#### ANALISIS
•	Perintah separator berfungsi untuk memberi pemisah seperti koma( , ), titik dua( : )dan lain sebagainya seperti pada syntax diatas.

### PENGGUNAAN STRING
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#penggunaan string 
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**6)
print(7, 10**7)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas



#### ANALISIS
•	Penggunaan string ** pada syntax diatas berfungsi untuk mencetak hasil pangkat, mulai dari 10 pangkat 0 sampai 10 pangkat 10

### PENGGUNAAN STRING FORMAT
#### SYNTAX
berikut merupakan syntax untuk menampilkan program diatas
``` python
#string format
print ('{0:>3} {1:>16}'.format(0, 10**0))
print ('{0:>3} {1:>16}'.format(1, 10**1))
print ('{0:>3} {1:>16}'.format(2, 10**2))
print ('{0:>3} {1:>16}'.format(3, 10**3))
print ('{0:>3} {1:>16}'.format(4, 10**4))
print ('{0:>3} {1:>16}'.format(5, 10**5))
print ('{0:>3} {1:>16}'.format(6, 10**6))
print ('{0:>3} {1:>16}'.format(7, 10**7))
print ('{0:>3} {1:>16}'.format(8, 10**8))
print ('{0:>3} {1:>16}'.format(9, 10**9))
print ('{0:>3} {1:>16}'.format(10, 10**10))
```

#### OUTPUT
Dibawah ini merupakan hasil output dari syntax diatas



#### ANALISIS
•	Untuk angka pada statement {0:<3} {1:<16} berfungsi untuk memberi jarak, lalu untuk tanda < dan > untuk memberikan rata kanan dan rata kiri. <br>
•	Untuk statement .format(0, 10** 0)) berfungsi untuk mencetak angka 0 dan hasil dari 10 pangkat 0 
