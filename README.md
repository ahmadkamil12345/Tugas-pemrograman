# Lab 2 latihan 1
soal
pada lab 2 latihan 1 saya diberi soal sebagai berikut :

![img](Gambar/soal1.png)

Untuk mengerjakannya saya memasukan syntax di bawah

    N=int(input("banyaknya data = "))
    if N>0:
        i=1
        x=int(input("data ke -"+str(i)+"="))
        max=x;total=x
        for i in range(2,N+1):
            x=int (input("data ke -"+str(i)+"="))
            total+=x
            if max<x:
                max=x

        print("bilangan terbesar =",max)

Dari proses diatas saya menggunakan output

![img](Gambar/Lab2latihan1.png)

lab 2 latihan 2
soal
pada lab 2 latihan 2 saya diberi soal sebagai berikut

![img](Gambar/soal2.png)

untuk mengerjakana saya memasukan syntax dibawah

    data = []
    for i in range (5):
        x =int(input("masukan bilangan : "))
        data.append(x)
    print('data sebelum diurutkan: ',data)
    list.sort(data)
    print('data setelah diurutkan: ',data)

Dari proses diatas saya mendapatkan output

![img](Gambar/Lab2latihan2.png)

lab 3 latihan 1
soal
pada lab 3 latihan 1 saya diberi soal

![img](Gambar/soal3.png)

untuk mengerjakan soal saya memasukan syntex dibawah ini

    baris = 10
    kolom = baris

    for bar in range(baris):
        for col in range(kolom):
            tab = bar+col
            print("{0:>5}".format(tab), end='')
        print()

Dari proses diatas saya mendapatkan output

![img](Gambar/Lab3latihan1.png)

lab 3 latihan 2
soal
pada lab 3 latihan 2 saya diberi soal

![img](Gambar/soal4.png)

untuk mengerjakan soal diatas saya menggunakan syntax dibawah

    import random
    print(40*"=")
    print("Bilangan acak yang lebih kecil dari 0,5")
    print(40*"=")
    jum = int( input("Masukan nilai n : "))
    i = 0
    for i in range(jum):
        i += 1
        angkaDec = random.uniform(0, 0.5)
        print("Data ke", i, " = ", angkaDec)

Dari proses diatas saya mendapat output dibawah

![img](Gambar/Lab3latihan2.png)

Terima Kasih


