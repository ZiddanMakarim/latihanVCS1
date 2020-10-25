# latihanVCS1

**NAMA : Ziddan Makarim** <br>
**KELAS : TI.20 A.1** <br>
**NIM : 312010063** <br>
**TUGAS : Membuat Repository** <br>

# Langkah-langkah penggunaan git
* Download Git terlebih dahulu, dengan link berikut ini : [click here](https://git-scm.com) <br>

![git-scm](gambarR/GitScm.png) <br>

* Setelah file terdownload, silahkan lakukan instalasi dengan referensi berikut ini : [Git Installation Guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

![installing](gambarR/installing.png)

* Setelah installasi selesai, buka software GitBash pada menu di Windows, dan lakukan pengecekan versi, dengan mengetik syntax berikut :

![Version](gambarR/version.png)

* Jika muncul tampilan git version, berarti Git sudah berhasil di install dan bisa digunakan. Langkah pertama kita harus mengkonfigurasi user nama dan email di Git, dengan mengetikkan syntax berikut : <br>
`git config --global user.name "masukan nama anda` <br>
`git config --global user.email "masukan email anda`
![user](gambarR/user.png)

* Setelah diisi, silahkan lakukan pengecekan user nama dan email, dengan mengetikkan perintah berikut : <br>
`git config --global user.name` <br>
`git config --global user.email`
![name](gambarR/name.png)

* Buat akun di GitHub,seperti contoh dibawah ini.Dan lakukan Verifikasi akun melalui email yang sudah terdaftar.

* Jika akun GitHub sudah selesai dibuat dan di verifikasi,proses selanjutnya silahkan buat Repository seperti gambar dibawah ini: Penjelasan
* `Repository Name : (Silahkan isi nama repository yang diinginkan, seperti contoh saya ingin membuat repository LatihanVCS)`
* `Description : (Isi dengan deskripsi atau penjelasan tentang repository Anda)`
* `Public / Private : (PIlih salah satu jenis repository akan bisa dilihan sama semua orang atau tidak)`
* `Add a README.md file : Centang pada bagian ini jika Anda menginginkan file README.md ada di repository Anda`
* `Add .gitignore : Merupakan sebuah file yang berisi daftar nama-nama file dan direktori yang akan diabaikan oleh Git.`
* `Choose a license : Silahkan centang jika Anda memiliki lisensi pada repository yang akan dibuat Kemudian tekan tombol Create Repository untuk menyimpan`
![buat](gambarR/buat.png)
 
* Jika repository sudah dibuat maka akan muncul tampilan seperti dibawah ini :

![hasil](gambarR/hasil.png)

* Pembuatan akun dan repository pada Github telah selesai, saat ini akan kita lakukan untuk me-remote repository Github pada GitBash Lokal. Bagaimana caranya? Langkah pertama kita harus menyalin link URL git kita di Github, dengan cara tekan tombol Code lalu klik Copy.

![code](gambarR/code.png)

* Setelah Link URL git kita tercopy, Silahkan buka File Explorer pada Windows, kemudian pilih folder dimana kita akan mendownload Repository dari Github ke lokal. Kemudian Klik Kanan, Pilih Git Bash Here.

![GitBash](gambarR/GitBash.png)

* Pop Up Command Prompt (CMD) akan terbuka. Pada proses ini kita akan melakukan download file repository yang tadi dibuat, dengan mengetikkan syntax berikut : <br>
`git clone [URL] pada contohnya, saya akan memasukan git clone`

https://github.com/ZiddanMakarim/latihanVCS1.git <br>

![clone](gambarR/clone.png)

* Setelah proses cloning selesai, pada saat ini kita masih pada folder awal (master), kita harus masuk kedalam folder yang telah dicloning tadi yaitu LatihanVCS dengan mengetikkan syntax berikut :
`cd latihanVCS1/`
![cd](gambarR/cd.png)





