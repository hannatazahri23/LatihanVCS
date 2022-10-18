# GIT

## Apa itu git?
* Git adalah salah satu sistem pengontrol versi (Version Control System) pada proyek perangkat lunak yang diciptakan oleh Linus Torvalds.

* VCS atau Version Control System merupakan sebuah sistem yang merekam perubahan-perubahan dari sebuah berkas atau sekumpulan berkas dari waktu ke waktu sehingga Anda dapat melihat kembali setiap perubahannya. Dan Salah satu DVCS (Distributed Version Control System) yang sangat populer saat ini adalah <b>git</b>.

* Pengontrol versi bertugas mencatat setiap perubahan pada file
proyek yang dikerjakan oleh banyak orang maupun sendiri.


## Tutorial Git

### Installasi Git
* Download <b>Git</b> di website resminya melalui link ini (https://git-scm.com/downloads).

* Kemudian unduh Git sesuai dengan arsitektur dan OS komputer kita.

* Setelah itu install Git dengan settingan default saja.

* Selamat!! Git sudah terinstall di PC kalian :smile:, untuk mengetahui Git sudah terpasang atau belum silahkan buka <b>CMD</b> atau <b>Power Shell</b> pada PC kalian, dan ketikan perintah ``` git --version ```.

(Taroh gambar BP_P4-1)

### Perintah Dasar Git

* `git init`, perintah untuk membuat repository local
* `git add`, perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
* `git commit`, perintah untuk menyimpan perubahan kedalam database git.
* `git push -u origin master`, perintah untuk mengirim perubahan pada repository local menuju server repository.
* `git clone [url]`, perintah untuk membuat working directory yang diambil dari repositry sever.
* `git remote add origin [url]`, perintah untuk menambahkan remote server/reopsitory server pada local repositry ``(working directory)``
* `git pull`, perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository

### Praktikum

1. Buatlah Repository Local, dengan cara bu






























### Menambahkan Global Config
* Pada saat pertamakali menggunakan Git, kita perlu melakukan konfigurasi <b>user.name</b> dan <b>user.email</b>. Konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.

* Apabila belum dilakukan konfigurasi, akan mengakibatkan terjadinya kegagalan saat menjalankan perintah <b>git commit</b>

* Cara melakukan konfigurasinya dengan memasukan dua perintah ini pada Git yang sudah kita install. Buka <b>Git Bash</b> dan masukan perintah ini ``` git config --global user.name "nama_username" ``` dan ``` git config --global user.email "alamat_email" ```.

(Taroh gambar BP_P4-2)

### Mem