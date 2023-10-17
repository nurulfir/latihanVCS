CARA MENGGUNAKAN GIT

Deskripsi

File README.md ini berisi panduan tentang cara menggunakan Git, sistem kontrol versi yang populer dan digunakan secara luas dalam pengembangan perangkat lunak. Dalam panduan ini, kami akan menjelaskan langkah-langkah yang perlu Anda ikuti untuk menggunakan Git dengan efektif.

Langkah-langkah
Instalasi Git:
Pastikan Git sudah terinstal di komputer Anda. Jika belum, Anda dapat mengunduhnya melalui situs web resmi Git di https://git-scm.com/downloads.
![alt text](?raw=true)

Ikuti instruksi instalasi yang disediakan oleh installer Git.
Konfigurasi Awal:
Buka terminal atau command prompt di komputer Anda.
Konfigurasi identitas Anda dengan menjalankan perintah berikut:
 git config --global user.name "Nama Anda" git config --global user.email "email@anda.com" 
Ganti "Nama Anda" dengan nama Anda dan "email@anda.com" dengan alamat email Anda.
Membuat Repositori:
Buka terminal atau command prompt di direktori proyek Anda.
Jalankan perintah berikut untuk membuat repositori baru:
 git init 
Menambahkan File ke Repositori:
Letakkan file-file proyek Anda di direktori repositori.
Jalankan perintah berikut untuk menambahkan file-file tersebut ke repositori:
 git add . 
Membuat Commit:
Jalankan perintah berikut untuk membuat commit dengan pesan deskriptif:
 git commit -m "Pesan commit Anda" 
Ganti "Pesan commit Anda" dengan pesan yang menjelaskan perubahan yang Anda lakukan.
Membuat Branch:
Jalankan perintah berikut untuk membuat branch baru:
 git branch nama-branch 
Ganti "nama-branch" dengan nama branch yang Anda inginkan.
Beralih ke Branch:
Jalankan perintah berikut untuk beralih ke branch yang baru dibuat:
 git checkout nama-branch 
Ganti "nama-branch" dengan nama branch yang ingin Anda gunakan.
Menggabungkan Branch:
Jalankan perintah berikut untuk menggabungkan branch saat ini dengan branch lain:
 git merge nama-branch-lain 
Ganti "nama-branch-lain" dengan nama branch yang ingin Anda gabungkan dengan branch saat ini.
Mengunggah ke Repositori Jarak Jauh:
Buat repositori kosong di platform Git hosting seperti GitHub atau GitLab.
Ikuti instruksi yang disediakan oleh platform untuk menghubungkan repositori lokal Anda dengan repositori jarak jauh.
Jalankan perintah berikut untuk mengunggah perubahan ke repositori jarak jauh:
 git push origin nama-branch 
Ganti "nama-branch" dengan nama branch yang ingin Anda unggah.
