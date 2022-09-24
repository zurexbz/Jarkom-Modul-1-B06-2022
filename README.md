# Jarkom-Modul-1-B06-2022

### Kelompok 10 Kelas B

| **No** | **NRP** | **Nama** | 
| ------------- | ------------- | --------- |
| 1 | 5025201100 | Hansen Idden | 
| 2 | 5025201109 | Mohammad Firman Fardiansyah |
| 3 | 5025201167 | William Zefanya Maranatha |

## Soal 1
### Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!
Pertama, cari web dengan mengetikkan `http contains “monta.if.its.ac.id”`
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097256-e0d278f0-9150-4b6e-820c-ef48f144d6e0.jpg">
Lalu, pilih salah satu paket yang ada di display. Klik kanan pada paket tersebut dan hover cursor pada follow dan pilih tcp stream.
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097279-a1528397-0ba3-45b2-a0a7-83e8e5a3d78e.jpg">
Lalu setelah itu ketik pada server pada find untuk menampilkan web server yang digunakan.
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097429-37098570-aa62-4814-b18e-29dd7c995943.jpg">
web server yang digunakan ada pada tulisan server yaitu `nginx/1.10.3`
## Soal 2
### Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?
Pertama, cari web yang mengandung detail dengan `http contains “detail”`
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097432-e4a11065-5dbf-4877-8503-5233c88d2b25.jpg">
Lalu, pilih salah satu paket yang ada. Klik kanan pada paket dan hover cursor pada follow, pilih http stream.
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097417-53cc9c68-87e5-443b-a130-47725c30885e.jpg">
Selanjutnya, cari tugas akhir menggunakan find.
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097419-7d4b505f-54de-4844-8d3b-e7d086eb76a3.jpg">
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097421-6bc5ef8a-1dea-4bba-8ee7-0fb39821a9fc.jpg">
Terlihat judul TA yang dibuka oleh Ishaq adalah `Evaluasi unjuk kerja User Space Filesystem`

## Soal 3
### Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!
Cari paket yang menuju ke port 80 dengan cara `tcp.dstport == 80`
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097423-05973228-2f70-4e81-baa3-1d6c15732419.jpg">

## Soal 4
### Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!
Menggunakan command filter `tcp.srcport == 21` untuk menampilkan semua paket yang memiliki protokol TCP yang berasal dari port 21.
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097425-030affee-0d99-4fc3-8ce0-8cec41ccc000.jpg">
<img width="1280" alt="image" src="https://user-images.githubusercontent.com/62301187/192097427-35124b10-61ae-4aef-bfaa-d32e16b1bd49.jpg">

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
