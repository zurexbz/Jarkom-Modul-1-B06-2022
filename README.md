# Jarkom-Modul-1-B06-2022

### Kelompok 10 Kelas B

| **No** | **NRP** | **Nama** | 
| ------------- | ------------- | --------- |
| 1 | 5025201100 | Hansen Idden | 
| 2 | 5025201109 | Mohammad Firman Fardiansyah |
| 3 | 5025201167 | William Zefanya Maranatha |

## Soal 1

## Soal 2

## Soal 3

## Soal 4

## Soal 5
### Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!
Menggunakan command filter `tcp.srcport == 443` untuk menampilkan semua paket yang memiliki protokol TCP yang berasal dari port 443. Sehingga hasil yang dikeluarkan adalah sebagai berikut:
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/83849481/192074898-2158836a-b6d6-462f-b730-9bb9389cefac.png">

## Soal 6
### Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id!
Langkah pertama mengecek IP dari lipi.go.id dengan ping lipi.go.id pada command prompt (CMD) jika menggunakan windows. Kemudian didapatkan IP dari lipi.go.id sebagai berikut:

<img width="332" alt="image" src="https://user-images.githubusercontent.com/83849481/192074959-1fafa3ef-fb1a-424e-bdc6-aa4b920e7615.png">

Setelah itu gunakan display filter `ip.dst==203.160.128.158` untuk menampilkan paket yang menuju lipi.go.id dan hasilnya sebagai berikut:
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/83849481/192075007-29f7bf61-9778-426f-93d6-59e51f1b08e9.png">

## Soal 7
### Filter sehingga wireshark hanya mengambil paket yang berasal dari IP kalian!
Langkah pertama yaitu mengecek IP sendiri menggunakan ipconfig pada command prompt (CMD) jika menggunakan windows

<img width="365" alt="image" src="https://user-images.githubusercontent.com/83849481/192094875-952c0e92-b95f-475c-95c4-11124923eead.png">

Setelah itu gunakan capture filter `src host [ip kalian]` untuk mengambil paket yang berasal dari IP kalian

<img width="1027" alt="image" src="https://user-images.githubusercontent.com/83849481/192094945-62979b4a-4664-41b3-8c10-61baa848bed1.png">

Sehingga hasil yang didapat adalah sebagai berikut:
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/83849481/192094830-12fe4094-886e-4da5-a10d-8836ffff6f72.png">

## Soal 8

## Soal 9

## Soal 10
