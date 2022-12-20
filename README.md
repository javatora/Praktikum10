# Praktikum10
## LATIHAN
### Latihan 1

```
# Hitung jumlah karakter
txt = 'Hello World'
print("Menghitung Jumlah Karakter : ", len(txt))

#Ambil Karakter Terakhir
length = len(txt)
last = txt[length-1]
print(last)

#Ambil Karakter ke-2 sampai index ke-4(llo)
print(txt[2:4], txt[2:5])

#Hilangkan spasi pada text tersebut (HelloWorld)
print('Hilangkan Spasi pada Hello World : ' + txt.replace(" ", ''))

#Ubah text menjadi huruf besar
print("ubah text jadi huruf besar : ", txt.upper())

#Ubah text menjadi huruf kecil
print("ubah text jadi huruf kecil : ", txt.lower())

#ganti karakter H jadi J
print("ganti karakter H jadi J : ", txt.replace('H', 'J'))
```


> Berikut hasilnya :

<img width="796" alt="Screen Shot 2022-12-20 at 19 05 30" src="https://user-images.githubusercontent.com/115475424/208663305-aaeced41-41b8-4ed6-8552-662958743820.png">



### Latihan 2

```
umur = 24
txt = "Hello, nama saya John, dan umur saya adalah {0} tahun "
print(txt.format(umur))
```

> Berikut Hasilnya

<img width="548" alt="Screen Shot 2022-12-20 at 23 21 10" src="https://user-images.githubusercontent.com/115475424/208715187-02f531c8-38c5-4ebd-aea7-c01d2348b850.png">


# Selesai
