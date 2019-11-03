  #Latihan1

# Cara penggunaan git
# Apa Itu Git ?
* Git adalah salah satu sistem pengontrol versi(Version Control System) pada proyek perangkat lunak yang diciptakan Linus Torvalds.
* Pengontrol versi bertugas memcatat setiap perubahan pada file proyek yang dikerjakan oleh banyak orang maupun sendiri.
* Git dikenal juga dengan distributed revision control (VCS terdistribusi), artinya penyimpanan database Git tidak hanya berada dalam satu tempat saja.
# Instalasi Git
* Download **Git**, Buka website resminya [git-scm.com](https://git-scm.com).
* Kemudian unduh Git sesuai dengan arsitektur komputer kita, Kalau
menggunakan 64bit, unduh yang 64bit. Begitu juga kalau
menggunakan 32bit.

![downloadgit](https://user-images.githubusercontent.com/56913656/67956393-9a592100-fc26-11e9-97f0-bd09cbf62134.png)
		
* Selamat, Git sudah terinstal di Windows. Untuk mencobanya,
		silahkan buka CMD atau PowerShell, kemudian ketik perintah
		``git --version``
		
 ![0](https://user-images.githubusercontent.com/57052780/68079037-11eca300-fe15-11e9-8e78-4b1d3782192f.png)
 
# Menambahkan Global Config
* Pada saat pertama kali menggunakan git, perlu dilakukan konfigurasi
*user.name dan user.email*
* konfigurasi ini bisa dilakukan untuk global repostiry atau individual
repository.
* apabila belum dilakukan konfigurasi, akan mengakibatkan terjadi
kegagalan saat menjalankan perintah ``git commit``
* Config Global Repository
		
  ![1](https://user-images.githubusercontent.com/57052780/68079121-d7840580-fe16-11e9-91df-1d48756222db.png)


# Perintah Dasar Git
* ``git init`` , perintah untuk membuat repository local.
* ``git add`` , perintah untuk menambahkan file baru, atau perubahan pada file pada staging sebelum proses commit.
* ``git commit`` , perintah untuk menyimpan perubahan kedalam database git.
* ``git push -u origin master`` , perintah untuk mengirim perubahan pada repository local menuju server repository.
* ``git clone [url]``, perintah untuk membuat working directory yang diambil dari repositry sever.
* ``git remote add origin [url]`` , perintah untuk menambahkan remote server/reopsitory server pada local repositry (working directory)
* ``git pull`` , perintah untuk mengambil/mendownload perubahan terbaru dari server repository ke local repository.
# Membuat Reposiory Local
* Buka direktory aktif, misal: ``d:\labs_pemrograman1`` (bukamenggunakan Windows Explorer)
* klik kanan pada direktory aktif tersebut, dan pilih menu ``Git Bash``,sehingga muncul git bash commad
* Buat direktory project praktikum pertama dengan nama **latihan1**		 
* Sehingga terbentuk satu direktori baru dibawahnya, selanjutnyamasuk kedalam direktori tersebut dengan perintah cd *(changedirectory)*
* direktory aktif menjadi: ``d:\labs_pemrograman1\latihan1``

  ![mkdir](https://user-images.githubusercontent.com/57052780/68079201-78bf8b80-fe18-11e9-8391-e2de3df313a5.png)

# Membuat Reposiory Local
* Jalankan perintah git init, untuk membuat repository local.
* Repository baru berhasil di inisialisasi, dengan terbentuknya satudirektori hidden dengan nama **.git**
* Pada direktori tersebut, semua perubahan pada *working directory* akan disimpan.
		
  ![git init](https://user-images.githubusercontent.com/57052780/68079229-377bab80-fe19-11e9-989b-4550e9522d64.png)

		
# Menambahkan File baru pada repository
* Untuk membuat file dapat menggunakan text editor, lalu menyimpafilenya pada direktori aktif (repository)
* disini kita akan coba buat satu file bernama README.md (text file) ``$ echo “#Latihan 1” >> README.md``
		
  ![2](https://user-images.githubusercontent.com/57052780/68079237-6abe3a80-fe19-11e9-8093-53278ef8f5ef.png)


File ``README.md`` berhasil dibuat.
# Menambahkan File baru pada repository
* Untuk menambahkan file yang baru saja dibuat tersebut gunakanperintah ``git add.``
* File README.md berhasil ditambahkan. ``$ git add README.md``

  
![4](https://user-images.githubusercontent.com/57052780/68079262-d1435880-fe19-11e9-9264-b3729bac9f80.png)

# Commit (Menyimpan perubahan ke database)
* Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah ``$ git commit -m “komentar commit”``

  ![3](https://user-images.githubusercontent.com/57052780/68079246-8fb2ad80-fe19-11e9-9c77-cf8e9983dcab.png)
  
* Perubahan berhasil disimpan
# Membuat repository server
* Server reopsitory yang akan kita gunakan adalah [github.com](https://github.com)
* Anda harus membuat akun terlebih dahulu.
* Pada laman github, klik tombol start a project, atau Dari menu (icon +) klik New Repository

 ![5](https://user-images.githubusercontent.com/57052780/68079388-11efa180-fe1b-11e9-9bb6-a1679c6cd742.png)
  
# Membuat repository server
* Isi nama repositorynya, **misal: labpy1.**
* lalu klik tombol **Create repository**

  ![6](https://user-images.githubusercontent.com/57052780/68079395-377cab00-fe1b-11e9-85fc-a9df7a9723ff.png)
  
# Menambahkan Remote Repository
* Remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user.
* Untuk menambahkan remote repository server, gunakan perintah ``git remote add origin [url]``

 ![Unteitled](https://user-images.githubusercontent.com/57052780/68079408-77dc2900-fe1b-11e9-9171-46d4c108165b.png)

  
# Melihat hasilnya pada server repository
* Buka laman ``github.com``,arahkan pada repositori- nya.
* Maka perubahan akan terlihat pada laman tersebut.

 ![6](https://user-images.githubusercontent.com/57052780/68079414-93473400-fe1b-11e9-927c-1536b9423eaf.png)

  
**FINISH**............................

  
  


