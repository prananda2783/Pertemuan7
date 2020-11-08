# Pertemuan 7 - labspy
Repository ini dibuat memenuhi tugas pertemuan 7 Bahasa Pemograman (modul praktikum 2) - Teknik Informatika <br><br>

### Menentukan Bilangan Terbesar Dari Nilai Yang Diinputkan 
> pada pertemuan ke-7 ini saya mendapatkan tugas dari dosen bahsa pemograman teknik informatika - Universitas Pelita Bangsa. untuk membuat aplikasi yang menentukan bilangan terbesar dari tiga nilai yang clirnt/user inputkan menggunakan bahasa program python.

pada repository ini saya akan menjelaskan *Flowchart* yang telah saya buat dan bisa di liat berikut file nya, [flowchat tugas pertemuan 7 menentukan bilangan yang diinput](flowerchat%20%20PERTEMUAN%207%20.pdf)

>Berikut source code yang saya buat untuk menjadi aplikasi yang bisa menentukan bilangan terbesar
```` python
print("Masukan Bilangan Ke-1 :")
bilangan1=int(input())
print("Masukan Bilangan Ke-2 :")
bilangan2=int(input())
print("Masukan Bilalngan ke-3 :")
bilangan3=int(input())

print("\n")

if (bilangan1 > bilangan2) and (bilangan1 > bilangan3) :
    print("Bilangan Pertama Lebih Besar Dari Bilangan Kedua Dan Ketiga")
elif (bilangan2 > bilangan1) and (bilangan2 > bilangan3) :
    print("Bilangan Kedua Lebih Besar Dari Bilangan Pertama Dan Ketiga ")
elif (bilangan3 > bilangan1) and (bilangan3 > bilangan2) :
    print("Bilangan Ketiga Lebih Besar Dari Bilangan Pertama Dan Kedua")
else:
    print("Semua Bilangan Sama Besar Nya")
````

<br>

> saya tidak akan melanjutkan fungsi print karna sudah saya jelaskan pada tugas sebelumnya. <br>
saya akan menjelaskan langkah-langkah nya:
<br>



