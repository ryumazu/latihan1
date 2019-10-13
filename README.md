# latihan 1
## Tutorial Cara menggunakan giter
## Instalasi Git
- pertama download terlebih dahulu git nya di (git-scm.com)
- sesuaikan komputer anda tapi saya saran kan memakai yg 64bit jika kalian bisa
- selamat kalian sudah selesai mengisntal git .

## Menambahkan Config
- pada saat pertama kali menggunakan git,perlu dilakukan konfigurasi username dan email
- konfigurasi ini bisa dilakukan untuk global repostiry atau individual repository.
- jika kalian tidak konfigurasi terlebih dahulu maka akan terjadi error saat menjalan kan perintah git init commit 
- CONFIG GLOBAL REPO
$ git config --global user.name “nama_user”
$ git config --global user.email “nama_user”

![Gitconfig](C:/Users/user/Desktop/New%20folder/Capture11.PNG)

## Perintah dasar

1.git init yaitu perintah untuk membuat respitory local
  1a.setelah mengatur tata letak dimana kita akan menyimpan respitory baru lah kita membuat respitory dengan menulis =$ git init

![Gitinit](C:/Users/user/Desktop/New%20folder/Capture1.PNG)

2.git add yaitu perintah untuk untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload bisa menggunakan perintah tersebut.

![Gitadd](C:/Users/user/Desktop/New%20folder/Capture3.PNG)

3.git commit yaitu perintah untuk menyimpan perubahan kedalam database git.untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar

![gitcommit](C:/Users/user/Desktop/New%20folder/Capture4.PNG)

4.git remote add origin yaitu perintah untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format “.git”, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.

![gitremoteaddorigin](C:/Users/user/Desktop/New%20folder/Capture6.PNG)

5.git push origin “nama branch” yaitu perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online.

![gitpushorigin](C:/Users/user/Desktop/New%20folder/Capture7.PNG)

6. git clone [url], perintah untuk membuat working directory yang diambil dari repositry server alias mendownload file tersebut.

![gitclone](C:/Users/user/Desktop/New%20folder/Capture8.PNG)

## Membuat Repo lokal
-Buka direktory aktif, misal: d:\labs_pemrograman1 (buka menggunakan Windows Explorer) 
-
