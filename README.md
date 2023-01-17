# praktikum-10

## Nama : Sinta Hardianti Wijaya

## NIM : 312210342

## Kelas : TI.22.A3

## DAFTAR ISI <br>
|No|Description|Link|
|----|----|----|
|1|Python String|[Click Here](#Python-String)|
|2|Latihan 1|[Click Here](#Latihan1)|
|3|Latihan 2|[Click Here](#Latihan2)|

## Python String

  - String adalah jenis yang paling populer di Python.
  - Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
  - Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
  - Membuat string semudah memberi nilai pada sebuah variabel.
  
# Latihan 1
![image](https://user-images.githubusercontent.com/115516473/212881620-c5e4d4f4-ac13-400b-980d-ee53be0ca15a.png)

## Penjelasan :

- Untuk menghitung jumlah karakter, gunakan fungsi ```len()```

```
# Menghitung jumlah karakternya
print(len(txt))
```

- Cara mengambil satu karakter pada string yaitu dengan menggunakan kurung siku ```[ ]``` dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY dan menggunakan titik dua lalu masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan index [-1]. Sedangkan untuk mengambil karakter index ke-2 sampai ke-4, gunakan index [2:5].

```
# Mengambil karakter terakhir
print(txt[-1])
# Mengambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])
```

- Jika ingin menghilangkan spasi pada string, gunakan method ```replace().``` Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.
- Di dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan ```(txt.replace(" ", ""))``` dan kedua dengan cara ```(txt.replace(txt[5], "")).```

```
# Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))
```

- Untuk mengubah huruf menjadi besar, gunakan method ```upper().``` Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method ```lower().```

```
# Mengubah text menjadi huruf besar
print(txt.upper())
# Mengubah text menjadi huruf kecil
print(txt.lower())
```

- Untuk mengganti karakter ```'H'``` dengan karakter ```'J'```, gunakan method ```replace().```

```
# Mengganti karakter H dengan karakter J
print(txt.replace("H", "J"))
print()
```

## Output :

![prak 10-latihan1](https://user-images.githubusercontent.com/115516473/212885200-cb49ed16-a255-4b4f-8b8d-8e3c43dec0ff.png)

# Latihan 2

![image](https://user-images.githubusercontent.com/115516473/212885396-1499dd2e-283d-469c-b467-0fbcd37a23fd.png)

## Penjelasan :

- Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal ```{} untuk menempatkan variable sebelumnya.```

```
  umur = 24
  txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

  print(txt.format(umur))
```

## Output :

![prak 10-latihan2](https://user-images.githubusercontent.com/115516473/212886058-ed36e819-0249-4f8d-97c2-bd36a04a3869.png)

# Selesai ^_^
