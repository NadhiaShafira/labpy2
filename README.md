# laporan praktikum 2
Nama: Indah Wafikah

nim: 312410559

dosen pengampu: Angung Nugroho, s.kom.,M.Kom,

Mata kuliah: bahasa programan

# latihan 1 menentukan nilai akhir
![foto](https://github.com/Indahwakifa/Flow-chart/blob/147f451e43ba671dfa5eefc117c3f0481a904ad3/ff30c325-7379-4aff-b391-0b29e684f2d1.jpg)
```python
nama = input("Masukkan nama: ")
uts = input("Masukkan nilai UTS: ")
uas = input("Masukkan nilai UAS: ")
tugas = input("Masukkan nilai Tugas: ")

akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"

print("\nNama       :",nama)
print("Nilai UTS    :",uts)
print("Nilai UAS    :",uas)
print("Nilai Tugas  :",tugas)
print("Nilai Akhir  :",akhir)
print("\nNilai Huruf    :",huruf)
print("Keterangan   :",keterangan)
```
# penjelasan kode proram
```python
nama = input("Masukkan nama: ")
uts = input("Masukkan nilai UTS: ")
uas = input("Masukkan nilai UAS: ")
tugas = input("Masukkan nilai Tugas: ")
```
Program meminta pengguna memasukkan nama, nilai UTS, nilai UAS, dan nilai tugas

```python
akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uas) * .4)
```

Menghitung nilai akhir dengan menggunakan bobot: 20% untuk tugas, 40% untuk UTS, dan 40% untuk UAS.

```python

keterangan = ("TIDAK LULUS", "LULUS")[akhir > 60.0]
```

Jika akhir lebih dari 60.0, maka keterangan akan menjadi "LULUS", jika tidak, "TIDAK LULUS".

```python

if akhir > 80:
    huruf = "A"
elif akhir > 70:
    huruf = "B"
elif akhir > 50:
    huruf = "C"
elif akhir > 40:
    huruf = "D"
else:
    huruf = "E"
```

Berdasarkan nilai akhir, program menentukan nilai huruf:

A jika lebih dari 80

B jika lebih dari 70

C jika lebih dari 50

D jika lebih dari 40

E jika di bawah atau sama dengan 40

```python

print("\nNama :", nama)
print("Nilai UTS :", uts)
print("Nilai UAS :", uas)
print("Nilai Tugas :", tugas)
print("Nilai Akhir :", akhir)
print("\nNilai Huruf :", huruf)
print("Keterangan :", keterangan)
```
Program mencetak nama, nilai UTS, UAS, tugas, nilai akhir, nilai huruf, dan keterangan lulus atau tidak lulus.

# hasil kode program
![foto](https://github.com/Indahwakifa/Flow-chart/blob/7d36a872b432def6b1e8cdfe8b8e1a2690e06689/5b966518-3e2d-4062-b496-715ae4384991.jpg)


# latihan 2 menentukan nilai akhir
![foto](https://github.com/Indahwakifa/Flow-chart/blob/b825cf2b3127bf107e82f3466c50c312662cadcf/WhatsApp%20Image%202024-10-28%20at%2009.44.01.jpeg)

```python
gaji = int(input("Masukkan gaji :"))
berkeluarga = (False, True)[input("sudah berkeluarga? (Y/T)") == "Y"]
punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]

if gaji > 3000000:
    print ("Gaji sudah diatas UMR")
    if berkeluarga:
        print ("Wajib ikutan asuransi dan menabung untuk pensiun")
    else:
        print ("tidak perlu ikutan asuransi")

    if punya_rumah:
        print("wajib bayar pajak rumah")
    else:
        print ("tidak wajib bayar pajak rumah")
else:
    print ("Gaji belum UMR")
```
# penejelasan kode program
```python
gaji = int(input("Masukkan gaji :"))
```
 Mengambil input gaji dari pengguna dan mengonversinya menjadi integer

 ```python
berkeluarga = (False, True)[input("sudah berkeluarga? (Y/T)") == "Y"]

punya_rumah = (False, True)[input("Punya rumah? (Y/T)") == "Y"]
```
Mengambil input status keluarga (Y untuk "sudah berkeluarga" atau T untuk "belum berkeluarga") dan kepemilikan rumah (Y untuk "punya rumah" atau T untuk "tidak punya rumah") dari pengguna, dan mengonversinya menjadi True atau False

   ```python
if gaji > 3000000
```
Mengecek apakah gaji lebih besar dari 3000000.

Jika benar, mencetak "Gaji sudah diatas UMR

```python
if berkeluarga
print ("wajib ikutan asuransi dan menabung untuk pensiun")
else
print("tidak per ikutan asuransi")
```
Jika berkeluarga bernilai True, maka mencetak "Wajib ikutan asuransi dan menabung untuk pensiun", jika tidak mencetak "tidak perlu ikutan asuransi".

```python
if punya_rumah:
print("wajib bayar pajak rumah")
else
print("tidak wajib bayar pajak rumah")
```
Jika punya_rumah bernilai True, mencetak "wajib bayar pajak rumah", jika tidak mencetak "tidak wajib bayar pajak rumah".

```python
print("gaji belum umr")
```
Jika gaji kurang dari atau sama dengan 3000000, mencetak "Gaji belum UMR".

# hasil kode program
![foto](
# latihan 3 menentukan nilai akhir
![foto](https://github.com/Indahwakifa/Flow-chart/blob/c090b38084843b415b765f1a0e27cfeae18a3ba3/7858bf1d-749b-49ed-b309-7a66bc89f57b.jpg)
