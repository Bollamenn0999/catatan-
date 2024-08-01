# Instalasi Git Bash
## 1.download Git pada browser ketik 'git-scm'
![asest|500x500](penginstalan1.JPG)

## 2.Lalu klik Git Hub yang telah di instal

## 3.Lalu akan muncul tampilan seperti gambar
![asest](penginstalan2.JPEG)

## 4.Maka klik 'next' terus hingga mendapatkan tampilan seperti gambar
![asest](penginstalan3.JPEG)

# Login Akun Github

1. Buka aplikasi github di browser 

2. Lalu lakukan sign up pada github
![asest](sigin1.JPG)

3. Jika sudah memiliki akun langsung masukkan password dan username yang ada
![asest](sigin2.JPG)

4. Jika tidak memiliki akun klik tambahkan akun
![asest](sigin3.JPG)

5. Setelah buat akun maka akan tampil seperti gambar
![](sigin4.JPG)

# Buat Repositori GitHub Baru:
   - Login ke akun GitHub Anda.
   - Klik tombol "New" untuk membuat repositori baru.
![asest](repositori1.JPG)
   - Berikan nama repositori, pilih apakah akan bersifat publik atau privat, lalu klik "Create repository".
![asest](repositori2.JPG)

# Konfigurasi Git Lokal:
   - Buka git di laptop/komputer anda.
   - Jalankan perintah berikut untuk mengatur identitas Anda:

```bash
     git config --global user.name "Nama Anda"
     git config --global user.email "email@example.com"
```

 

    Note: untuk melihat apakah sudah terhubung konfigurasi git nya silakan ketik 
         git config --list
 contohnya: 

 ![asest](git_config.png)
![[null]]
# Akses folder proyek di git bash
 Gunakan perintah  cd (change directory) sampai ke folder yang kalian tuju.


```shell
cd
```

Contohnya:
![asest](cd_obsidian.png)
# Inisialisasi Git Lokal:
   -  Buat direktori baru untuk proyek Anda dan navigasikan ke direktori tersebut menggunakan Git bash. Kemudian, inisialisasi Git di direktori tersebut dengan menjalankan perintah:
```shell
     git init
   
```


 contohnya:
![asest](git_init.png)

# Hubungkan ke Repositori GitHub:
   - Jalankan perintah berikut untuk menghubungkan repositori lokal Anda ke repositori GitHub yang telah Anda buat sebelumnya:
```bash
     git remote add origin https://github.com/username/nama-repository.git
```

   
   Ganti username dan nama-repository dengan nama pengguna GitHub Anda dan nama repositori yang Anda buat.Jika Sudah ada tulisan (master),berarti sudah terhubung ke repositori Githubnya
   
contohnya:
![](git_remote.png) 




# Tambahkan file ke repositori: 
   - Perintah ini akan menambahkan semua file di direktori saat ini ke repositori.
   - Tambahkan file yang ingin Anda simpan di repositori Git dengan menjalankan perintah:
```shell
git add .
```


 
contohnya:
![[MATERI GIT/asest/git_add.png]]

# *Buat Commit:*
   - Jalankan perintah berikut untuk membuat commit dengan pesan yang jelas:
   - Perintah git commit -m *"Pesan commit"* digunakan untuk menyimpan perubahan yang telah dilakukan pada repositori Git dengan menambahkan pesan
     cs
     git commit -m "Pesan commit"
     
     *contohnya:*
     ![[commit-m.PNG]]]
   Unggah ke GitHub   (git push origin master):
   Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:

# *Unggah ke GitHub*:
   - Terakhir, jalankan perintah berikut untuk mengunggah kode Anda ke GitHub:
     cs
     git push -u origin master
     
     *contohnya:*
     ![[git_push (1).png]]
     maka akan tetampil bgini,berarti anda disuruh untuk login akun github mu yang sudh kamu buat 
     ![[git_push (2).png]]
   Perintah ini akan mengunggah kode Anda ke repositori GitHub. Setelah ini, setiap kali Anda membuat perubahan pada kode, Anda dapat mengulangi langkah 4, 5,6 dan 7 untuk mengunggah perubahan tersebut ke GitHub.