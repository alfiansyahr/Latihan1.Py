# Latihan1.Py
Digunakan untuk mengerjakan tugas Python

# PERTEMUAN KE 6 - Bahasa Pemrograman
**Repository ini dibuat untuk memenuhi tugas bahasa pemrograman pertemuan ke-6**

 **==================================================** <br>
**Nama      : Alfiansyah Rambe**<br>
**NIM       : 312010338**<br>
**Kelas     : TI.20.B2**<br>
 **==================================================**

DAFTAR ISI <br>
| No | Description | Link |
| ----- | ----- | ---- |
| 1 | Tugas pertemuan 5 | [Click Here](#pertemuan-5---tugas-bahasa-pemrograman)
| 2 | Tugas pertemuan 6 Lab 1 | [Click Here](#pertemuan-6---lab-1)
| 3 | Tugas pertemuan 6 Lab 1.2 | [Click Here](#pertemuan-6-lab-12)
| 4 | Tugas pertemuan 6 Lab 2 | [Click Here](#pertemuan-6---lab-2)
<br>

# PERTEMUAN 5 - TUGAS BAHASA PEMROGRAMAN

     
Pada pertemuan ke-5 Bahasa pemrograman, saya diberi tugas oleh dosen untuk membuat aplikasi biodata dengan Python (seperti dibawah ini)

![input gambar](picture/tugas5.PNG)<br>

Saat ini saya akan menjelaskan hasil dari tugas tersebut <br>
Berikut *source code* nya atau klik link berikut : <br>

```python
print("Please enter full name : ")
fullname=input()

print("please insert your Nickname : ")
nickname=input()

print("please enter your NPM : ")
NPM=input()

print("please enter your Born place : ")
bornplace=input()

print("please insert your age : ")
age=input()

print("please enter your home address : ")
address=input()

print("please enter your phone number : ")
phonenumber=input()

print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n") 
``` 

<br>
Berikut penjelasanya : <br>

```python
print("Please enter full name : ")
```
Source Code ini berfungsi untuk mencetak hasil atau output berupa ***"Please enter full name"*** seperti gambar dibawah ini :<br>

Untuk menampilkan output String, saya menggunakan *tanda petik dua*, contohnya :

```python
print("Nama saya adalah ...")
print(12345)
```

![input gambar](picture/fullname1.PNG)<br>

* Untuk source kode berikutnya adalah inputan atau membuat variabel, seperti syntax dibawah ini

```python
Fullname=input()
```
Keterangan<br>
1. Variabel adalah sebuah penyimpanan data pada program yang akan digunakan selama program ini berjalan. Yang berfungsi sebagai variabel dalam source code diatas adalah **Fullname**. <br>
2. Fungsi **input()** adalah untuk memasukan nilai dari layar consol di command prompt, lalu kemudian mengembalikan nilai saat kita menekan tombol Enter
 *(newline)*<br>

![input gambar](picture/fullname2.PNG)<br>

Pada gambar diatas, hasil dari inputan tersebut berwarna *hijau*<br>

* Untuk perintah masukan yang lain seperti *nickname, NPM, ... dst, masukan perintah yang sama seperti memasukan *fullname*

* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen,<br>
output pertama yang diminta Dosen adalah menampilkan salam, yaitu dengan mengetikan syntax/ source code dibawah ini :

```python
print("\nAssalamualaikum Wr, Wb.")
```
Keterangan :<br>
1. Fungsi ***\n*** pada source code diatas adalah untuk memberi barisan baru / Enter / *newline*
2. Fungsi print(), seperti dijelaskan pada point *output* diatas<br>

![input gambar](picture/fullname2.PNG)<br>

Pada gambar diatas, hasil dari inputan tersebut berwarna *hijau*<br>

* Untuk perintah masukan yang lain seperti *nickname, NPM, ... dst, masukan perintah yang sama seperti memasukan *fullname*

* Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen,<br>
output pertama yang diminta Dosen adalah menampilkan salam, yaitu dengan mengetikan syntax/ source code dibawah ini :

```python
print("\nAssalamualaikum Wr, Wb.")
```
Keterangan :<br>
1. Fungsi ***\n*** pada source code diatas adalah untuk memberi barisan baru / Enter / *newline*
2. Fungsi print(), seperti dijelaskan pada point *output* diatas<br>

Hasil dari source code diatas adalah seperti gambar dibawah ini : 

* Langkah terakhir adalah untuk menampilkan semua inputan diatas dengan mengetikan source code berikkut :

```python
print("\nAssalamualaikum Wr, Wb.")
print(f"\nLet me introduce my self. My name is {fullname}, but you can call me {nickname}. My NPM is {NPM}. I was Born in {bornplace} and i am {age} years old. I am very glad if you want to invite my house in {address}. So, don't forget to call me before with the number {phonenumber}.")
print("\nThank you.")
print("\n")
```
Keterangan :<br>
1. Fungsi huruf    ***f***  pada perintah ***print(f"...)*** adalah fungsi print yang dapat memudahkan programer untuk mencetak statement dalam satu baris dibandingkan dengan metode lama yaitu memisahkan string dan variabel dengan tanda koma ( , ) atau ( + ) <br>
2. Sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variabel<br>

Hasil dari output tersebut adalah :

![input gambar](picture/Hasil.PNG)<br>

<br>
<br>
<br>

# Pertemuan 6 - Lab 1

Pada tugas pertemuan ke-6 lab 1 saya diberikan tugas oleh Dosen yaitu mempelajari Aritmatika menggunakan bahasa pemrograman python. Berikut source code yang diberikan oleh dosen :

![input gambar](picture/lab1.PNG)

```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
```
<br>
Kali ini saya akan menjelaskan materi yang diterima dari Dosen. <br><br>