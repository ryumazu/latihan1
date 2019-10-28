# Lab 1

### Penggunaan end
Di dalam fungsi "**print()**" di dalam bahasa python terdapat parameter "**end**". Parameter "**end**" adalah parameter yang digunakan untuk memasukan **string** atau **karakter** apapun untuk mengakhiri sebuah statement.  Secara default jika kita melakukan print dalam python, output akan dicetak dalam baris baru. Tapi jika kita memasukan fungsi "**end**" maka hasil output tidak akan langsung berada di garis baru.

Contoh kode :

### Penggunaan end
   print('A', end="")
   print('B', end="")
   print('C', end="")
   print()
   print('X')
   print('Y')
   print('Z')

![Output_End](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.1.PNG?raw=true)

### Penggunaan Separator
Separator "**sep**" dalam python digunakan sebagai pembatas antara output yang dihasilkan.

**Contoh Kode :**

    w, x, y, z = 10, 15, 20, 25
    print(w, x, y, z, sep=',')
    print(w, x, y, z, sep='')
    print(w, x, y, z, sep=':')
    print(w, x, y, z, sep='- - - - -')

**Output yang didapat :**


![Output_sep](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.2.PNG?raw=true)

Kita bisa mengisi **sep='isi_disini'** dengan string atau karakter apapun.

### Penggunaan string format
String format digunakan ketika kita ingin mengatur dan memposiskan print output menjadi sedemikian rupa.
**Contoh kode :**

  # String yang belum di format
  print(0, 10 ** 0)
  print(1, 10 ** 1)
  print(2, 10 ** 2)
  print(3, 10 ** 3)
  print(4, 10 ** 4)
  print(5, 10 ** 5)
  print(6, 10 ** 6)
  print(7, 10 ** 7)
  print(8, 10 ** 8)
  print(9, 10 ** 9)
  print(10, 10 ** 10)

**Output :**

![Output_String](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.3.png?raw=true)

Kita akan membuat outputnya menjadi seperti berikut :

![Output_String2](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.5.png?raw=true)

**Dengan Kode :**

   print('{0:>3} {1:>16}'.format(0, 10 ** 0))
   print('{0:>3} {1:>16}'.format(1, 10 ** 1))
   print('{0:>3} {1:>16}'.format(2, 10 ** 2))
   print('{0:>3} {1:>16}'.format(3, 10 ** 3))
   print('{0:>3} {1:>16}'.format(4, 10 ** 4))
   print('{0:>3} {1:>16}'.format(5, 10 ** 5))
   print('{0:>3} {1:>16}'.format(6, 10 ** 6))
   print('{0:>3} {1:>16}'.format(7, 10 ** 7))
   print('{0:>3} {1:>16}'.format(8, 10 ** 8))
   print('{0:>3} {1:>16}'.format(9, 10 ** 9))
   print('{0:>3} {1:>16}'.format(10, 10 ** 10))

Dalam contoh di atas terdapat **{ }** yang berfungsi sebagai ***placeholder*** atau penempat **arguments**.
Argument secara default urutannya adalah **berurutan**. 

![Output_String3](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.4.png?raw=true)

Misalnya dalam contoh di atas, terdapat argument **"0"** dan **"10 ** **0"**** didalam **format(0, 10 ** 0)**, yang dipisah dengan tanda **","** (koma), yang berarti __"0"__ adalah argument  **pertama** dan  __"10**0"__ adalah argument ke **dua**.  Sedangkan angka **0** dan **1** di dalam ***placeholder***, merupakan urutan yang kita masukan. Misalnya ***placeholder*** pada urutan pertama yaitu "{**0**:>3}" dan kita ingin mengganti menjadi "**1**" maka yang akan dicetak di ***placeholder*** pertama adalah output dari "**10 ** 0**".
**Contoh kode :**

    print('{1:>3} {0:>16}'.format(0, 10 ** 0))

**Output yang didapat :**

![Output_String4](https://github.com/ryumazu/latihan1/blob/master/gambar/lab1.6.png?raw=true)

Sedangkan untuk "**:>3**" digunakan untuk menentukan output di cetak pada urutan ke tiga. Urutan yang kosong akan menghasilkan output "**spasi**".


    