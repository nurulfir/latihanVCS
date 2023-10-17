CARA MENGGUNAKAN GIT

Deskripsi

File README.md ini berisi panduan tentang cara menggunakan Git, sistem kontrol versi yang populer dan digunakan secara luas dalam pengembangan perangkat lunak. Dalam panduan ini, kami akan menjelaskan langkah-langkah yang perlu Anda ikuti untuk menggunakan Git dengan efektif.

Langkah-langkah

Instalasi Git:
1. Pastikan Git sudah terinstal di komputer Anda. Jika belum, Anda dapat mengunduhnya melalui situs web resmi Git di https://git-scm.com/
![alt text](https://github.com/nurulfir/latihanVCS/blob/nurulfir-patch-1/Gambar1.jpg?raw=true)
2. Ikuti instruksi instalasi yang disediakan oleh installer Git.

1. Login GitHub:

Login GitHub ke website https://github.com/
![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-17%20at%2018.56.32_af1ef305.jpg?raw=true)

2. Selanjutnya Anda bisa melakukan login awal pada Git menggunakan Command Prompt (Windows) Git Bash

$ git config --global user.name "UsernameAnda"

$ git config --global user.email "EmailAnda@gmail.com"

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-18%20at%2000.11.10_32ad7fd0.jpg?raw=true)
3. Buat Repository

Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-18%20at%2000.14.22_d430e05a.jpg?raw=true)

4. Buat Folder

Selanjutnya, Anda perlu membuat folder pada local disk komputer Anda. Fungsinya adalah untuk menyimpan update file dari repository GitHub yang telah Anda buat.

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-17%20at%2022.12.02_1e8b0c0d.jpg?raw=true)

5. Buka Folder Menggunakan Git Bash

Setelah berhasil membuat folder pada local disk komputer Anda,  buka folder tersebut dengan cara klik kanan lalu pilih Git Bash Here. Setelah itu, Command Prompt akan muncul seperti di bawah ini.

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-17%20at%2022.18.47_36bd0e61.jpg?raw=true)

6. Ubah Folder Menjadi Repository

Setelah itu, ubah folder tersebut menjadi repository menggunakan perintah berikut:

$ git init

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-17%20at%2022.24.52_bddab21c.jpg?raw=true)

7. Tambahkan File ke Repository

Buka GitBash lalu masukkan perintah berikut:

$ git add README.md

![alt text](https://github.com/nurulfir/latihanVCS/blob/main/WhatsApp%20Image%202023-10-17%20at%2022.32.00_43605292.jpg?raw=true)

8. Buat Commit

Selanjutnya, Anda perlu membuat Commit. Commit berfungsi untuk menambahkan update file serta komentar. Jadi setiap kontributor bisa memberikan konfirmasi update file di proyek yang sedang dikerjakan. Masukkan perintah berikut untuk membuat Commit:

$ git commit -m "pesan commit"

9. Remote Repository Github
Remote repository berfungsi untuk mengupload file yang telah Anda buat sebelumnya di local disk. Masukkan perintah berikut ini untuk melakukan remote repository:

$ git remote add origin https://github.com/UserNameGit/NamaRepository.git

10. Push ke GitHub 
Langkah terakhir adalah push ke GitHub Push ini berfungsi untuk mengupload hasil akhir dari langkah-langkah di atas. Masukkan perintah berikut untuk melakukan push ke GitHub:

git push -u origin master

Perintah di atas akan menampilkan pop up sign in GitHub. Anda perlu login untuk melanjutkan proses push ke GitHub.
