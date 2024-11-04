# BIODATA

### NAMA  = ADINDA AULIA NABILA PUTRI

### KELAS = TI.24.A.4

### NIM   = 312410309

# Latihan 1 
   ![Screenshot (34)](https://github.com/user-attachments/assets/680a4d3f-6977-47a9-9918-9465ffe0d82f)

```PYTHON
import random
n = int(input("Masukkan nilai N: "))

for i in range(1, n + 1):
    angka_acak = random()
    if angka_acak < 0.5:
        print(f"data ke: {i} => {angka_acak}")
    else:
        while angka_acak >= 0.5:
            angka_acak = random()
        print(f"data ke: {i} => {angka_acak}")

print("Selesai")
````


```PYTHON
import random
````

baris ini yang berisi fungsi-fungsi untuk menghasilkanangka acak.

```PYTHON
(n = int(input("Masukkan nilai N: ")))
````

pengguna diminta untuk memkasukkan nilai integer n yang menentukan berapa bnayk angka acak yang akan dihasilkan. 

```PYTHON
(for i in range(1, n + 1):)
````

for adalah perulangan yang akan berjalan sebanyak nN kali range (1, n + 1) menghasilkan urutan angka mulai dari 1 hingga N (termasuk N), yang digunakan untuk menentukan jumlah angka acak yang akan dihasilkan.


# Berikut Screenshot Pemrograman dan Hasil dari Visual Studio Code 

   ![Screenshot (52)](https://github.com/user-attachments/assets/2cbc0478-5f7b-4247-b10c-a116127692b6)


   ![Screenshot (43)](https://github.com/user-attachments/assets/0ab31218-9cea-448f-a3cd-fc52a761cedd)

# Latihan 2 

   ![Screenshot (44)](https://github.com/user-attachments/assets/42f9b7b4-6327-4784-b308-fbfa0a237e2e)
    
```PYTHON
# inisial modal awal
modal_awal = 100000000

# inisial daftar laba untuk setiap bulan laba
laba = [0, 0, 0, 0, 0, 0, 0, 0]

# Menghitung laba untuk setiap bulan
laba [2] = modal_awal * 0.01 # Laba bulan ke-3 sebesar 1%
laba[4] = laba[2] * 1.05     # Laba bulan ke-5 meningkat 5% dari bulan ke-3
laba[7] = laba[4] * 0.98     # Laba bulan ke-8 turun 2% dari bulan ke-5

# Menghitung total laba
total_laba = sum(laba)

# Mencetak hasil
print("Laba bulan ke-1 sebesar:", laba[0])
print("Laba bulan ke-2 sebesar:", laba[1])
print("Laba bulan ke-3 sebesar:", laba[2])
print("Laba bulan ke-4 sebesar:", laba[3])
print("Laba bulan ke-5 sebesar:", laba[4])
print("Laba bulan ke-6 sebesar:", laba[5])
print("Laba bulan ke-7 sebesar:", laba[6])
print("Laba bulan ke-8 sebesar:", laba[7])
print("Total laba adalah:", total_laba)
````
```PYTHON
laba = [0, 0, 0, 0, 0, 0, 0, 0]
````

array laba dibuat untuk menyimpan laba bulanan selama 8 bulan, dengan nilai awal 0 untuk semua bulan.

```PYTHON
laba [2] = modal_awal * 0.01 # Laba bulan ke-3 sebesar 1%
laba[4] = laba[2] * 1.05     # Laba bulan ke-5 meningkat 5% dari bulan ke-3
laba[7] = laba[4] * 0.98
````
laba dihitung sebesar 1% dari modal_awal, yaitu 1 juta rupiah, laba meningkat sebesar 5% dari laba bulan ke-3. Nilai menjadi 1,05 juta rupiah, laba mengalami penurunan sebesar 2% dari laba bulan ke-5. Nilai laba bulan ke-8 adalah 1,029 juta rupiah. 

# Berikut Screenshot Pemrograman dan Hasil dari Visual Studio Code 

   ![Screenshot (47)](https://github.com/user-attachments/assets/196331b9-2742-4bf8-864b-b31369530adf)

   ![Screenshot (49)](https://github.com/user-attachments/assets/3df82fa6-eed9-4159-b66b-3c96e7c088ad)


# Latihan 3 

![Screenshot (45)](https://github.com/user-attachments/assets/c63e88b0-78c6-4a2d-92bf-ff3a4375774e)

```PYTHON
saldo = 1000000

while true
   print(f"Saldo saat ini: Rp {saldo}")
   print("1. Tarik Uang")
   print("2. Keluar)

   pilihan = input("Pilih menu (1/2): ")

   if pilihan == "1":
      Jumlah = int(input("Masukkan jumlah penarikan: "))
      if jumlah <= saldo:
         saldo -= jumlah
         print("Penarikan berhasil!")
     else:
       print("Saldo tidak cukup!")
     elif pilihan == "2":
       print("Terima kasih telah menggunakan ATM BTN!")
       break
     else:
       print("Pilihan tidak valid!")
````

```PYTHON
 print(f"Saldo saat ini: Rp {saldo}")
   print("1. Tarik Uang")
   print("2. Keluar)
````
setiap kali loop berjalan, saldo saat ini akan ditampilkan, bersama dengan dua pilihan menu: Tarik Uang (1) atau Keluar (2).

```PYTHON
if pilihan == "1":
      Jumlah = int(input("Masukkan jumlah penarikan: "))
````

pengguna akan diminta memasukkan jumlah uang yang akan ditarik, kemudian memeriksa apakah jumlah yang diminta kurang dari atau sama dengan saldo saat ini. 

```PYTHON
elif pilihan == "2":
       print("Terima kasih telah menggunakan ATM BTN!")
       break
````

jika pengguna memilih "2", pesan Terima Kasih telah menggunaka aTM BTN! akan ditampilkan, dan program akan keluar dari loop dengan perintah break. 


# Berikut Screenshot Pemrograman dan Hasil dari Visual Studio Code 

  ![Screenshot (51)](https://github.com/user-attachments/assets/eb44be6b-475c-4dad-bf6a-c1535403d9fe)

  ![Screenshot (50)](https://github.com/user-attachments/assets/0efa6bf3-2957-4731-bb0a-0ed5df4d53c5)


