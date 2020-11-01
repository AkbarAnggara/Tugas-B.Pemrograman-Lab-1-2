#Tugas Pertemuan 6 - Bahasa Pemrograman

Nama : Bangkit Akbar Anggara
NIM : 312010148
Kelas : TI.20.B.1

#Tugas - Pertemuan 5
 
 Saat ini saya akan menjelaskan hasil dari tugas tersebut.
Berikut source code nya

		print("====BIODATA=====")
		print()
		namalengkap=input("Masukan Nama Lengkap Anda : ")
		namapanggilan=input("Masukan Nama Panggilan Anda : ")
		npm=input("Masukan NPM anda : ")
		tempatlahir=input("Tempat Lahir Anda : ")
		tahun=input("Masukan Umur Anda : ")
		telepon=input("Masukkan No.Telepon Anda : ")
		alamat=input("Masukan Alamat Anda : ")

		print("\n\n=====BIODATA ANDA=====")
		print("Assalamu'alaikum")
		print()
		print("Let me introduce my self. My name is" ,namalengkap, " but you can call me" ,namapanggilan, ". My NPM is" ,npm, ". I was born in" ,tempatlahir, "and i am" ,umur, "years old. I am very glad if you want to invite my house in" ,alamat, ". So, don't forget to call me before with the number" ,telepon, ".")
		print()
		print("Thank you")

	Berikut penjelasannya :
		print ("====BIODATA=====")
	Source code diatas berfungsi untuk mencetak hasil / output berupa "====BIODATA=====".
	Untuk menampilkan output string, saya menggunakan tanda petik dua didalam fungsi print()
	Untuk source code berikutnya adalah inputan atau membuat variable. seperti syntax dibawah ini :
		namalengkap=input("Masukan Nama Lengkap Anda : ")
	Keterangan :
	1.Variabel adalah sebuah wadah penyimpanan data pada program yang akan digunakan selama program itu berjalan. Yang berfungsi sebagai variable dalam source code diatas adalah namalengkap .
	2.Untuk memasukkan perintah lain seperti Nickname, NPM, Place Of Birth, Date of Birth, Year of Birth, Phone Number, and Address mengikuti perintah yang sama seperti memasukkan fullname
	3.Untuk menghitung rumus umur saya menggunakan variable DOB yaitu 2020 (Tahun Sekarang) dikurangi dengan Year of Birth, pada source code berikut :
		dob=2020-tahun
	Pada syntax/source code diatas, saya menggunakan variable dob dimana untuk menghitung umur (variable age pada output), yaitu degan rumus pada variable dob=2020-year
	Langkah kali ini saya akan menampilkan output yang diminta oleh Dosen.
	Keterangan :

	1.Fungsi \n pada source code diatas adalah untuk memberi baris baru / enter / (newline)
	2.Langkah terakhir adalah menampilkan semua hasil dari inputan diatas. Dengan mengetikkan source code berikut :
		print("\n\n=====BIODATA ANDA=====")
		print("Assalamu'alaikum")
		print()
		print("Let me introduce my self. My name is" ,namalengkap, " but you can call me" ,namapanggilan, ". My NPM is" ,npm, ". I was born in" ,tempatlahir, "and i am" ,dob, "years old. I am very glad if you want to invite my house in" ,alamat, ". So, don't forget to call me before with the number" ,telepon, ".")
		print()
		print("Thank you")
	Keterangan :
	Sedangkan fungsi , pada output tersebut adalah untuk menampilkan hasilnya
	Hasil dari output tersebut seperti berikut :
	
	Lab 1 - Pertemuan 6
	Pada halaman ini (Tugas Pertemuan 6 - Lab 1) saya diberikan tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan Bahasa Pemrograman Python.
	#Penggunaan End
print("A", end="")
print("B", end="")
print("C", end="")

print()
print("X")
print("Y")
print("Z")

#Penggunaan Separator
w,x,y,z=10,15,20,25
print(w,x,y,z)
print(w,x,y,z,sep=",")
print(w,x,y,z,sep="")
print(w,x,y,z,sep=":")
print(w,x,y,z,sep="-----")
Oke, kali ini saya akan menjelaskan tentang materi yang diberikan oleh Dosen.


Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. Secara default penggunaan end adalah untuk ganti baris.
print("A", end="")
print("B", end="")
print("C", end="")
Penggunaan print() digunakan untuk mencetak output, seperti syntax dibawah ini :

print()
Syntax dibawah ini digunakan untuk menampilkan output berupa string

print("X")
print("Y")
print("Z")
Hasil dari source code tersebut seperti gambar dibawah ini :
Penggunaan Separator Separator adalah pemisah yang berfungsi sebagai tanda pemisah antar objek yang dicetak. Defaultnya adalah tanda spasi.

Pendeklarasian beberapa variable beserta nilainya

w,x,y,z=10,15,20,25
Menampilkan hasil dari variable tiap-tiap variable

print(w,x,y,z)
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah , (koma)

print(w,x,y,z,sep=",")
Menampilkan hasil dari tiap-tiap variable tanpa menggunakan pemisah

print(w,x,y,z,sep="")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)

print(w,x,y,z,sep=":")
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah -----

print(w,x,y,z,sep="-----")
Hasil dari syntax / source code diatas adalah seperti berikut ini :
Pertemuan 6 - Lab 1-2
String Format
String formatting atau pemformatan string memungkinkan kita menyuntikkan item kedalam string daripada kita mencoba menggabungkan string menggunakan koma atau string concatenation.
Penggunaan source code yang diberikan oleh dosen seperti berikut :
#String Format 1
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

print()
print()

#String Format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(0, 10**1))
print('{0:>3} {1:>16}'.format(0, 10**2))
print('{0:>3} {1:>16}'.format(0, 10**3))
print('{0:>3} {1:>16}'.format(0, 10**4))
print('{0:>3} {1:>16}'.format(0, 10**5))
print('{0:>3} {1:>16}'.format(0, 10**6))
print('{0:>3} {1:>16}'.format(0, 10**7))
print('{0:>3} {1:>16}'.format(0, 10**8))
print('{0:>3} {1:>16}'.format(0, 10**9))
print('{0:>3} {1:>16}'.format(0, 10**10))

Saat ini saya akan membahas satu persatu dari syntax yang telah di berikan oleh Dosen.
String Format 1
Pada syntax / source code string format 1 akan menampilkan output berupa 2 outputan.
Yang pertama (sebelah kiri) akan menampilkan angka Urut dari angka 0 hingga angka 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat.
Dengan ketentuan sebagai berikut, operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] )
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10. dengan output sebagai berikut :
String Format 2
Pada syntax atau source code string format 2 akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri)
Dengan ketentuan sebagai berikut :

Alignment, padding, dan precesion dengan .format() dalam kurung kurawal kita dapat menetapkan panjang bidang, rata kanan/kiri, parameter pembulatan dan banyak lagi. Contoh lain seperti berikut :

print('{0:8} | {1:9}'.format('Buah','Jumlah'))
print('{0:8} | {1:9}'.format('Apel', 3.))
print('{0:8} | {1:9}'.format('Jeruk',10))
Hasil dari source code contoh diatas akan seperti berikut :
Secara Default, .format() menggunakan rata teks ke kiri, angka ke kanan. Kita dapat menggunakan opsi opsional <, ^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan .format() sebagai berikut :

print('{:<30}{:^30}{:>30}'.format('Kiri','Tengah','Kanan'))
print('{:<30}{:^30}{:>30}'.format(12,34,56))
Hasil dari source code contoh diatas akan muncul seperti ini :
Untuk hasil dari String Format 2 adalah :
Pertemuan 6 - Lab 2
Konversi Nilai Variable Untuk pembahasan terakhir, kali ini akan menyelesaikan tugas Lab 2 dari Dosen, yaitu Konversi Nilai Variable
Tugas yang diberikan oleh dosen adalah seperti gambar dibawah ini atau bisa di akses ke link Pertemuan 6 - Lab 2 :
a=input("Masukkan Nilai A : ")
b=input("Masukkan Nilai B : ")
print("Variable A : ",a)
print("Variable B : ",b)
print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#Konversi nilai variable
a=int(a)
b=int(b)
print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
Setelah saya menjalankan source code tersebut terdapat error, seperti gambar dibawah ini :
Nah, untuk kali ini kita akan membaca error yang telah terjadi.

TypeError: %d format: a number is required, not str

Pada error tersebut terbaca bahwa variable a adalah string, yang seharusnya dibaca oleh system adalah Number / Interger.
Bagaimana cara memperbaiki error tersebut?
Kita lihat pada baris ke 5 (di notifikasi terbaca bahwa error terletak pada baris ke 5), yaitu pada pemformatan .format() adalah interger, Sedangkan jika berupa string maka akan ada tanda petik dua ("..") pada pemformatan .format()
Kita akan terfokus pada variable a dan b.
Pada line 1 tertulis syntax : a=input("Masukkan Nilai A : ")
Sedangkan pada line 2 tertulis sytax : b=input("Masukkan Nilai B : ")
Untuk membuat inputan berupa interger/angka harus ditambahkan syntax int() pada format input(). Yang seharusnya ditulis adalah :

a=int(input("Masukkan Nilai A : "))
b=int(input("Masukkan Nilai B : "))

Kita akan ulangi semua sintax pada file ini, maka tulis seperti ini :
a=int(input("Masukkan Nilai A : "))
b=int(input("Masukkan Nilai B : "))
print("Variable A : ",a)
print("Variable B : ",b)
print("Hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#Konversi nilai variable
a=int(a)
b=int(b)
print("Hasil penjumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("Hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
Kita akan coba lagi untuk run file tersebut, maka akan muncul seperti gambar dibawah ini :
Setelah semua file berhasil disimpan dan dijalankan berhasil, maka selesai sudah Tugas Pertemuan 6 - Bahasa Pemrograman kali ini.