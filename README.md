# Lab-Mobile-2025

# Repositori Tugas Pemrograman Mobile 2025

## Requirements:
1. Buat akun GitHub (https://github.com/)
2. Download Git (https://git-scm.com/)

## Alur pengumpulan tugas ke repositori ini:

1. **Fork** repositori ini

2. **Clone** repositori hasil **fork** anda

   ```sh

   git clone https://github.com/YOUR_USERNAME/Lab-Mobile-03-2025.git

   ```

3. Setelah anda **clone**, masuk ke folder hasil **clone** tersebut lalu buat **branch** dengan nama **NIM** anda

   ```sh

   cd Lab-Mobile-3-2025
   git branch NIM_ANDA
   git checkout NIM_ANDA
   git config user.name USERNAME_GITHUB
   git config user.email EMAIL_GITHUB

   ```

4. Setelah anda pindah ke **branch** yang telah anda buat, buat sebuah folder dengan nama **NIM** anda dan masuk ke folder tersebut.
   ```sh

   mkdir NIM_ANDA
   cd NIM_ANDA

   ```


5. Didalam folder tersebut, buat sebuah folder dengan nama **Praktikum-n**, **n** = praktikum keberapa
   ```sh

   mkdir "Praktikum-n"
   cd "Praktikum-n"

   CATATAN: n DI SINI ADALAH NOMOR PRAKTIKUM KE BERAPA
   CONTOH: Praktikum-1

   ```

7. Semua _file_ untuk tugas praktikum ke-**n**, disimpan kedalam folder **Praktikum-n**
8. Setiap membuat _file_ atau melakukan perubahan, lakukan proses **commit** dengan pesan yang deskriptif

   ```sh

   git add . #perintah ini memilih seluruh file sekaligus
   # atau
   git add "NIM/Praktikum n/FileYangBerubahAtauDitambahkan" #perintah ini memilih file tertentu

   git status untuk mengecek apakah file sudah ter add atau tidak.
   Jika file yang ingin di add sudah berwarna hijau lanjut ke commit.
   Jika file yang ingin di add berwarna merah lakukan add terlebih dahulu

   git commit -m "pesan mengenai penambahan atau perubahan apa yang anda lakukan"

   ```

8. Setelah asistensi dan tugas anda disetujui, **push** seluruh _file_ jawaban yang telah anda buat

   ```sh

   # pastikan proses commit telah selesai terhadap setiap file
   git push origin NIM_ANDA

   ```

   Jika sebelumnya anda belum pernah menghubungkan Git di komputer anda dengan akun GitHub anda, maka anda akan diminta untuk mengisi username dan password untuk
   melakukan push ke repo GitHub anda.
   ```sh

   # username = username anda
   # password = persocal access token anda

   ```

   Cara membuat personal access token:
   ```sh

   #1. Klik profile anda pada pojok kanan atas GitHub
   #2. Pilih menu settings
   #3. Scroll ke bagian bawah dan pilih menu Developer settings
   #4. Pilih Personal access tokens
   #5. Pilih Generate new tokens
   #6. Tuliskan note untuk token anda (ex: Token for Lab-Mobile-2024)
   #7. Atur waktu expiration token anda (sesuai keinginan anda)
   #8. Pada select scope, ceklis box repo
   #9. Klik generate new token
   #10. Pastikan untuk meng-copy token anda dan menyimpannya, karena token hanya bisa diliat sekali (*Jika hilang, buat token baru)

   ```

9. Masuk ke akun GitHub anda, dan buka repo yang telah anda **fork** dan **clone**. Lihat perubahan yang terjadi pada repo tersebut dan pastikan bahwa tugas yang
   telah anda **push** sesuai dan berada pada repo tersebut.

10. Pilih menu **Pull request** dan lakukan **pull request** pada tugas praktikum anda.
