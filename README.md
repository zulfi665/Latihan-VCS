#  Cara Menggunakan GitHub & Perintah Dasar GitHub
## Pengenalan
Jika kita berbicara tentang version control system, maka ada banyak sekali GIT yang bagus, baik dari sisi relevansi maupun performa. GIT dikembangkan oleh pengembang UNIX, Linus Torvalds, pada tahun 2005 dan hari ini telah digunakan oleh jutaan perusahaan untuk melakukan manajemen efisiensi kode dan kontrol versi untuk project mereka. Software ini bersifat open source dan bisa di-download untuk Linux, Windows, Solaris dan Mac. Informasi lebih lengkap tentang GIT bisa Anda temukan disini. Dalam tutorial ini, kita akan banyak membahas tentang perintah GIT.
## Yang Anda butuhkan
Sebelum memulai, yang Anda butuhkan adalah:

.GIT yang telah ter-install di sistem Anda

# Cara Install Git di Windows
Cara install Git di Windows terdiri dari 10 langkah. Berikut adalah penjelasannya:

## 1. Download File Git
untuk menginstall Git, Anda perlu mengunduh file-nya terlebih dahulu di situs resminya. Download sesuai tipe sistem operasi pada komputer Anda. Apabila tipe sistem operasi komputer Anda 64bit,  pilih Git yang mendukung Windows 64bit. Tujuannya adalah agar tidak terjadi error saat proses instalasi Git.

## 2. Install Git
Setelah selesai mengunduh file Git, buka setup aplikasi Git untuk memulai proses instalasi. Halaman awal setelah Anda membuka setup aplikasi Git adalah tampilan Document License dari Git. Klik Next untuk melanjutkan instalasi.
![Screenshot1](https://user-images.githubusercontent.com/72791776/95842961-60b6f280-0d71-11eb-9f8a-b650ddcef2ac.png)

## 3. Tentukan Lokasi Instalasi Git
Selanjutnya, pilih lokasi untuk install Git pada komputer Anda. Pada tutorial ini kami menginstall di lokasi **C:\Program Files\Git**. Setelah menentukan lokasi instalasi Git, klik Next untuk melanjutkan.
![Screenshot2](https://user-images.githubusercontent.com/72791776/95842968-6280b600-0d71-11eb-844f-f8cb7d5d60c2.png)

## 4. Pilih Komponen Tambahan
Kemudian pilih komponen tambahan untuk install Git. Fungsi komponen ini adalah untuk memperlancar penggunaan Git dan mendukung file dengan kapasitas besar. Sesuaikan komponen tambahan yang dipilih seperti pada gambar di bawah ini. Jika sudah klik Next untuk melanjutkan instalasi.
![Screenshot3](https://user-images.githubusercontent.com/72791776/95842971-63194c80-0d71-11eb-89c9-b1e08e25dfdd.png)

## 5. Tentukan Nama Aplikasi Git
Sebenarnya Anda bebas mengganti nama aplikasi Git yang akan ditampilkan pada Start Menu. Akan tetapi, demi kemudahan saat mencari aplikasi ini, sebaiknya gunakan nama Git saja.
![Screenshot4](https://user-images.githubusercontent.com/72791776/95842976-644a7980-0d71-11eb-8d56-fdc780ef3153.png)

## 6. Tentukan File Editor
Untuk mengedit script melalui Git, Anda memerlukan file editor. Anda bebas menggunakan file editor apa pun untuk dikombinasikan dengan Git. Pada tutorial ini, kami menggunakan Vim Editor. Klik Next apabila Anda sudah menentukan file editor yang akan Anda gunakan.
![Screenshot5](https://user-images.githubusercontent.com/72791776/95842994-690f2d80-0d71-11eb-966f-0833872483df.png)

## 7. Atur Path Environment
Selanjutnya adalah pengaturan Path Environment. Path Environment berfungsi untuk mengeksekusi perintah perintah pada Git. Pilih Git from the command line and also from 3rd-party software agar saat menjalankan perintah Git dapat dikenali di Command Prompt (CMD) pada Windows.
![Screenshot_6](https://user-images.githubusercontent.com/72791776/95843066-7a583a00-0d71-11eb-99ca-83068ecdadce.png)

## 8. Pilih Aplikasi SSH
Kemudian untuk mengeksekusi SSH, Anda bisa menggunakan aplikasi dari Git atau  dari platform lain seperti PuTTY dan Bitvise. Pada tutorial ini kami menggunakan Use OpenSSH, aplikasi default SSH dari Git. Klik Next untuk melanjutkan instalasi.
![Screenshot_7](https://user-images.githubusercontent.com/72791776/95843073-7c21fd80-0d71-11eb-9331-cfdf5cddc0f4.png)

## 9. Pilih Line Ending
Selanjutnya, Anda perlu memilih pengaturan line ending. Pada tutorial ini kami memilih Checkout Windows-style, commit Unix-style line endings. Klik Next untuk melanjutkan instalasi.
![Screenshot_8](https://user-images.githubusercontent.com/72791776/95843089-7f1cee00-0d71-11eb-816d-6ea9fc5941b7.png)

## 10. Pilih Emulator Terminal
Setelah itu, Anda perlu memilih emulator terminal yang akan digunakan. Anda bisa menggunakan Command Prompt atau MinTTY. Karena ingin menggunakan Command Prompt, pada tutorial ini kami memilih Use Windows’ default console windows. Klik Next untuk melanjutkan instalasi.
![Screenshot_9](https://user-images.githubusercontent.com/72791776/95843092-804e1b00-0d71-11eb-93ab-7d0589638264.png)

## 11. Tentukan Opsi ekstra
Terdapat beberapa opsi ekstra yang bisa Anda pilih. Pertama, pilih Enable File System Caching agar Git memiliki fungsi system caching. Kedua, pilih Enable Git Credential Manager agar Git bisa dikombinasikan dengan aplikasi lain seperti Visual Studio, Android Studio, dan GitHub. Klik Next untuk melanjutkan instalasi.
![Screenshot_10](https://user-images.githubusercontent.com/72791776/95843097-8217de80-0d71-11eb-81d6-78564207ebbe.png)

## 12. Mulai Proses Instalasi
Setelah menambahkan konfigurasi ekstra pada Git, Anda bisa memulai proses instalasi Git. Klik Install untuk melanjutkan proses.
![Screenshot_11](https://user-images.githubusercontent.com/72791776/95843102-83490b80-0d71-11eb-9bce-82404425ab93.png)
Berikut ini adalah tampilan proses instalasi Git. Tunggu hingga proses selesai dan Anda bisa menggunakan Git pada Windows.
![Screenshot_12](https://user-images.githubusercontent.com/72791776/95843110-8643fc00-0d71-11eb-8e1c-fd6442addd1b.png)

## 13. Cek Versi Git
Setelah proses instalasi selesai, Anda perlu mengecek apakah instalasi Git berhasil atau tidak. Anda bisa mengeceknya melalui Command Prompt. Klik Win+R lalu ketik CMD untuk membuka Command Prompt seperti di bawah ini.
![Screenshot_13](https://user-images.githubusercontent.com/72791776/95843126-8a701980-0d71-11eb-94eb-d265f7bb253f.png)

# Cara Penggunaan Git
Pada tulisan kali ini saya akan berbagi informasi tentang git. Mungkin bukan sesuatu hal yang baru karena teknologi ini sudah sering dipakai oleh para developer. Tapi ini merupakan hal yang baru dipelajari oleh saya dan mungkin akan berguna untuk para pemula yang sedang belajar tentang git. Selain untuk berbagi informasi tulisan ini juga merupakan sebuah tugas yang diberikan oleh mentor di tempat saya mengikuti boothcamp dan pelatihan programming. Oke skip dengan curhatnya dan mulai ke materi.
## Pengertian Git
GIT merupakan sebuah Version Control System (VCS) yang digunakan dalam tim pengembangan perangkat lunak untuk bekerja bersama. Version Control maksudnya sistem Git akan mencatat setiap perubahan yang terjadi pada source code kita sehingga memungkinkan untuk mengambil kembali source code lama jika suatu saat kita ingin kembali ke versi berapapun dari aplikasi yang pernah kita tulis.(http://www.tutorial-webdesign.com)
Dari pengertian diatas dapat ditarik kesimpulan bahwa git ini digunakan sebagai tempat untuk menyimpan dan merekam history dari program yang telah dibuat. Semua perubahan dapat terlihat ketika menggunakan git. Selain itu penggunaan git sangat membantu saat beberapa developer membuat aplikasi web secara bersamaan. Misalkan ada yang membuat bagian back-end dan ada yang membuat bagian front-end ketika pembuatan nya dilakukan secara terpisah lalu kemudian di gabungkan dapat menggunakan git.
Program tersebut akan di simpan kedalam repository git atau istilah nya adalah commit. Setiap melakukan satu perubahan berarti kita melakukan satu commit. Walaupun kita melakukan perubahan sampai 10 kali versi aselinya tidak akan hilang. Yang perlu diingat adalah setiap kita melakukan commit maka kita harus membuat commit yang representatif agar bisa dibaca oleh orang lain dan tidak membingungkan kita sendiri.
Commit yang telah dilakukan hanya akan disimpan pada repository lokal yang ada di komputer. Agar dapat diakses bersama-sama oleh developer lain maka dibutuhkan suatu repository central. Sesuai dengan saya pelajari web yang menyediakan jasa repository central untuk git adalah Github.com. Mungkin ada web yang lain yang menyediakan jasa repository central seperti Github misalkan gitlab atau tfs. Tapi dalam tulisan kali ini saya hanya akan menjelaskan penggunaan git dan Github saja.

# Membuat akun di Github
Sebelum menggunakan git kita sebaiknya membuat akun github terlebih dahulu karena akun github ini yang akan dijadikan sebagai repository central nya. Untuk sign up di github sangat mudah seperti sign up di instagram atau media sosial lainnya. Yang penting jangan sampai lupa email, username dan password nya. Kita tinggal masuk ke website www.github.com.
# Install Git
Selanjutnya download software git di http://git-scm/downloads, sesuaikan dengan sistem operasi yang digunakan, disini saya menggunakan operasi windows. Setelah di download maka lakukan instalasi software seperti instalasi pada umunya sampai selesai.

# Penggunaan Dasar Git
Setelah terinstall kita ujicoba terlebih dahulu fungsi dasar yang ada di git. Ada berapa fungsi dasar yang terdapat dalam git. Untuk penggunaan git pertama masuk ke folder yang akan digunakan. Klik kanan dan pilih Git Bash here.
![2_qJJEt_32_tJHhGX8_66trw](https://user-images.githubusercontent.com/72791776/96332668-93bdf680-108f-11eb-9e37-766df85f71ee.png)
Setelah muncul maka dilakukan configurasi antara git dengan akun github yg telah dibuat dengan menulis perintah :
git config --global example@gmail.com
git config --global "name"
![3_ufJpgwG-n5jmZwt8Sj3UlQ](https://user-images.githubusercontent.com/72791776/96332669-94568d00-108f-11eb-9724-ca32186d7ebb.png)
Penggunaan git mungkin sama seperti cmd kalo di windows kalo yang memakai linux mungkin lebih terbiasa. Beberapa perintah dasar di git adalah :
mkdir <nama folder> #untuk membuat folder
cd <nama folder>    #Untuk masuk masuk kedalam folder
cd ..               #Untuk mundur ke folder sebelumnya
ls                  #Untuk melihat file yang ada di dalam folder
ls-al               #Untuk melihat folder yang ada dan di hidden
touch               #Untuk menambah folder baru
Vim                 #Untuk nulis ke file
Esc lalu shift+w    #Untuk save hasil yang telah ditulis
Esc lalu shift+x    #Untuk save dan keluar folder
Cat                 #Untuk print di git bash nya
Rm                  #Untuk utk hapus file
Mv                  #Untuk mindahin isi dan ganti file
code/code .         #Untuk membuka file .py atau coding yang dibuat
Rm - r              #Untuk hapus directory
Rm -f               #Untuk hapus paksa

# Penggunaan Git pada Visual Studio Code
Setelah mengetahui penggunaan dasar dari git. Maka selanjutnya saya akan menggunakan perintah git tersebut di visual studio code. Sebenarnya bisa saja untuk commit code di git nya langsung tetapi karena waktu belajar saya langsung menggunakan visual studio code maka git bashnya hanya digunakan untuk membuka code dan selanjutnya untuk commit akan dilakukan di visual studio code.
Pertama buka git bash kemudian masuk ke folder yang akan dimasukan ke repository git dengan perintah yang telah dipelajari. Setelah itu buka dengan perintah code<spasi><titik>. Karena kalo hanya git repository nya lokal maka saya masukan dulu code yang telah dibuat ke github agar masuk ke repository central dan dapat dilihat oleh developer lain.
Memasukan code ke dalam Github
Pertama login dengan email dan password yang telah di daftarkan. Kemudian buat repository dengan mengklik tanda + dan pilih new repository.
![4_0DdCCZ9Cvg0_dLvaX4e9Fw](https://user-images.githubusercontent.com/72791776/96332670-94568d00-108f-11eb-8522-97a442db7831.png)
Setelah itu masukan nama repository yang akan dijadikan sebagai tempat code yang telah dibuat .
![5_FkbCp_Q6cIVf4Q9UaSxHSw](https://user-images.githubusercontent.com/72791776/96332672-94ef2380-108f-11eb-975a-c4fa4899442c.png)
Kalo sudah diisi nama repository nya lalu create repository. Maka akan muncul seperti gambar dibawah ini.
![6_4uIOLB01ABB2EHh6mhDppQ](https://user-images.githubusercontent.com/72791776/96332673-9587ba00-108f-11eb-9b6e-80025c5ac82f.png)
Kemudian setelah dibuat di github respository nya lalu kembali lagi ke visual studio code. Kemudian buat repository di git dengan memasukan perintah :
git init
![7_R-_S_QWzHmUC8ixcgOjPfA](https://user-images.githubusercontent.com/72791776/96332674-96b8e700-108f-11eb-96e4-abcced6e92ac.png)
Perintah ini akan membuat repository dengan nama git dan akan tersembunyi file nya. Yang harus diperhatikan yaitu apabila sudah pernah membuat git di folder tersebut maka tidak bisa lagi membuat git karena akan saling menimpa dsan akan konflik. Lalu perintah selanjutnya yaitu :

git add .

Perintah ini merupakan perintah yang akan menambah file ke github. Selanjutnya yaitu :

git commit -m "initialization commit"

Perintah diatas sebagai commit yang pertama . Untuk penambahan commit harus diperhatikan karena akan menjadi history setiap perubahan. Selanjutnya yaitu ;

git remote add origin https://github.com/cecepaf18/Tugas-2.git

Perintah diatas yaitu perintah untuk dapat menghubungkan dari repository lokal ke repository central yaitu github. Yang terkahir yaitu :

git push origin master 

Perintah ini yang akan memasukan program yang telah dibuat dan tersimpan di git repository lokal ke repository central yaitu github dan bisa diakses oeh developer yang lain. Tunggu hingga proses pengiriman file berhasil dan 100% terkirim semuanya.
![8_DuTFkdlvL2W9DvwlLH7WbA](https://user-images.githubusercontent.com/72791776/96332675-96b8e700-108f-11eb-8aa4-cfe892fe7863.png)
Apabila telah selesai dan mencapai 100% maka lihat ke github nya kalo berhasil maka semua file akan ada di dalam github. Seperti gambar di bawah ini.
![9_nATajGhdlQwXJaD_gr-xQw](https://user-images.githubusercontent.com/72791776/96332676-9882aa80-108f-11eb-9d19-26658ecb52d1.png)
Karena belum di tambahkan README maka kita tambah kan dengan menekan tombol Add a README. README ini merupakan keterangan mengenai program yang telah dibuat. Caranya bisa menambahkan secara langsung atau juga bisa ditambahkan di visual code nya dengan menambahkan file README.md
Setelah dibuat README di visual studio code maka selanjutnya yaitu kita upload ke github dengan dengan perintah yang sama.

git add .
git commit -m "edit commit"
git push origin master
![10_AJq6C3UN6cXWb5aqHie4qA](https://user-images.githubusercontent.com/72791776/96332679-99b3d780-108f-11eb-968b-b99a8a9479eb.png)
Yang perlu diperhatikan yaitu ketika sudah merubah code maka harus di save terlebih dahulu agar bisa tampil di github. Ketika kita akan banyak melakukan perubahan kita bisa membuat branch lain agar tidak langsung merubah di master nya. Perintah untuk membuat branch baru yaitu :

git branch <name>
atau 
git checkout -b <nama branch lain> #untuk menambah branch

Untuk penulisan nama bebas tapi kalo ada dua suku kata maka harus dipisahkan dengan ( _ ) garis bawah. Untuk mengecek ada berapa banyak branch perintahnya yaitu:

git branch
![11_ETPKqnoMIHBhxgznRs6vJQ](https://user-images.githubusercontent.com/72791776/96332681-9b7d9b00-108f-11eb-9b2e-23ef1eb780b4.png)
Terdapat 2 buah branch karena tadi sudah ditambahkan satu buah branch lain. Untuk pindah ke branch lain perintah nya yaitu :

git checkout <nama branch lain>
![12_LKutBUmJdNsm57WBpVzBCQ](https://user-images.githubusercontent.com/72791776/96332682-9c163180-108f-11eb-8e22-523e69210b58.png)
Gambar diatas merupakan perpindahan dari branch master ke branch edit_cecep. Lalu kita rubah README nya dan lakukan langkah — langkah sebelumnya untuk merubah atau commit.
![13_vBP4wTk9sl6sEtuzLxQsvg](https://user-images.githubusercontent.com/72791776/96332683-9caec800-108f-11eb-853c-7382992e005c.png)
Bisa dilihat pada bagian bawah telah dirubah dengan ditambahkan kata-kata lain. Selain itu saya mencoba untuk membuat branch lain dengan nama edit. Kemudian mengedit dengan menambahkan beberapa kalimat dan di commit.
![14_gLJ_XEux_tFoS3St6NYmEA](https://user-images.githubusercontent.com/72791776/96332685-9ddff500-108f-11eb-8902-bc026c80030b.png)
Kedua branch tersebut diibaratkan dikerjakan oleh dua developer yang berbeda maka ketika selesai maka akan di jadikan satu dengan perintah :

git merge <nama branch>

Misalkan kan tadi terdapat 2 buah branch yang pertama yaitu edit_cecep dan yang kedua yaitu yaitu edit. Ketika akan melakukan merge maka kita pindah dulu dari branch edit ke branch edit_cecep kemudian masukan perintah diatas. Maka branch edit_cecep akan di merge dengan branch edit.
![15_b9938H9jl85o9g6rOLW78g](https://user-images.githubusercontent.com/72791776/96332686-9e788b80-108f-11eb-8c37-43252cc7cae7.png)
Kalo ingin merge ke master juga sama saja caranya dengan yang tadi. Dengan pertama checkout ke master lalu merge dari edit_cecep ke master.
![16_aau03IGv6r9Juj97zx8AIw](https://user-images.githubusercontent.com/72791776/96332688-a0424f00-108f-11eb-8f22-4aba1a7b6892.png)
Yang terakhir yaitu perintah untuk membuat clone dari projek yang telah dibuat:
git clone <https://github.com/repo-name/proj-name.git> #http yang ada di github sesuai dengan program yang di remote
