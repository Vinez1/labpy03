# labspy03

**Nama   : Fery Affandi** <br>
**NIM    : 312010018** <br>
**Kelas  : TI.20.A.1** <br>

-------------

## TUGAS PPT KE 3

Pada pertemuan 7 di PPT3 ini saya diberikan beberapa tugas diantaranya yaitu: <br>

![tuga3-1](foto/tugas31.png)

## Latihan 1

![latihan3-1](foto/latihan3-1.png)

untuk mengerjakannya kalian perlu memasukan sytax berikut

```python
import random
print(40*"=")
print("Bilangan random yang lebih kecil dari 0,5")
print(40*"=")
jum = int( input("Masukan nilai n : "))
i = 0
for i in range(jum):
    i += 1
    angkaDec = random.uniform(0, 0.5)
    print("Data ke", i, " = ", angkaDec)
```

Maka hasil yang didapat dari syntax tersebut adalah <br>

![hasil1](foto/hasil1.png)

## Latihan 2

![latihan2](foto/latihan2.png)

Untuk mengerjakan soal diatas maka kita perlu memasukan atau menginput datanya terlebih dahulu baru setelah itu bisa terlihat data mana yang terbesar denagn syntax.

```python
N=int(input("silahkan masukan jumlah bilangan ="))
if N>0:
    i=1
    x=int(input("masukan bilangan "+str(i)+"="))
    max=x;total=x
    for i in range(2,N+1):
        x=int (input("masukan bilangan "+str(i)+"="))
        total+=x
        if max<x:
            max=x

    print("bilangan terbesar =",max)
```

Setelah itu bisa langsung kalian "RUN" untuk dapat memasukan data yang sesuai dengan yang ada di soal seperti dibawah ini

![hasil2](foto/hasil2.png)

## program1.py

![program1](foto/program1.png)
![program1](foto/program1(2).png)

* Buka text editor seperti PyCharm, Visual Studio Code, dan lain lain. Kemudian salon kode berikut

```python
a = 100000000
for x in range (1,9):
    if (x>=1 and x<=2):
        b=a*0
        print("laba bulan ke-",x,": ",b)
    if (x>=3 and x<=4):
        c=a*0.1
        print("laba bulan ke-",x,": ",c)
    if (x>=5 and x<=7):
        d=a*0.5
        print ("laba bulan ke-",x,": ",d)
    if (x==8):
        e=a*0.2
        print("laba bulan ke-",x,"; ",e)
total=b+b+c+c+d+d+d+e
print("\Total : ",total)
```

Penjelasannya sebagai berikut :

* Variable a = 100.000.000 yaitu modal awalnya.
* Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.
* Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai bulan 8.
* Bulan pertama dan kedua laba adalah 0.
* Bulan ke 3 dan bulan ke 4 mendapatkan laba sebesar 1% sehingga modal di kali 1% = keuntungan.
* Bulan ke 5 mendapatkan laba  sebesar 5% sehingga modal dikali dengan 5% = keuntungan.
* Bulan ke 8 mendapatkan laba sebesar 2% sehingga keuntungan mulai menurun dari bulan sebelumnya, modal dikali dengan 2% = keuntungan
* Mengitung jumlah total laba dengan mmenjumlahkan keuntungan dari bulan ke 1 sampai bulan ke 8, maka hasilnya adalah total keuntungan yang di dapat adalah
``` total=b+b+c+c+d+d+d+e```
* ``` print("\Total : ",total) ``` , untuk menampilkan hasil keseluruhan laba dari bulan ke 1 sampai bulan ke 8. 

### Output :

![hasiloutout](foto/outputpy.png)




# **Sekian Terimakasih**





