# How to Remote Repository in GitHub??

before we talk to far, you should to know what is remote? what is repository?, what is push or pull? what is commit? and another about git!

but in this article, wen jus't will only discuss how to remote a repository, so here we go! 

_article will be continue in bahasa indonesia_

## Pastikan sudah menginstall git di computer

cara untuk memastikannya adalah dengan membuka __terminal__ atau __CMD di Windows__ > lalu ketikan `git -v` jika tampil seperti dibawah ini maka telah menginstall git, namun jika belum maka keterangan versi tersebut tidak akan muncul, maka dari itu silahkan download git pada halaman berikut ini
- GIt for Windows https://git-scm.com/download/win
- Git for Mac OS https://git-scm.com/download/mac
  

<img width="399" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/995910fb-c7c8-46a3-948f-3b5d14fbe331">

__gambar 0.__ install git 

jika  sudah berhasil menginstall git kedalam sistem operasi anda, maka selanjutnya dapat lakukan  konfigurasi secara global nama dan email anda yang tehubung ke github
dengan melakakukan perintah :

```git
git config --global user.name "Nama Anda"
git config --global user.email "email@example.com"
```
atau seperti gambar dibawah ini :

<img width="558" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/f9418e44-d828-47c3-b5a4-c8891dc6b2f9">

__gambar 0.1.__ install git 

jika sudah berhasil maka anda dapat melihat konfigurasi anda pada list configurasi dengan perintah :

```git
git config --list
```


## Pastikan sudah mempunyai repository di github


<img width="1135" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/14c4c6b4-c3ec-4183-aa07-fa9a44d184db">




___gambar 1.__ repository in github_ 


## Buka Project File pada Code Editor Visual Studio Code

<img width="1200" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/70e074fc-ac2d-4fb4-be44-7162102c7dff">

___gambar 2.__ open project folder to code editor_ 


## Buka Terminal Pada Code Editor Visual Studio Code
untuk membka terminal pada visual studio code anda dapat memilih __menu terminal__ > pilih __new terminal__

<img width="1253" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/2763dd3e-e7be-46ec-ae8d-b1d53df29a2e">


___gambar 3.__ open terminal_

## Clonning Repository
- untuk clonning repository anda dapat copy link bagian https (pada gambar 4)
  
<img width="418" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/4d51b822-ec18-48f4-b690-663963a7145a">

___gambar 4.__ open terminal_

- masukan perintah berikut (ganti repository_url dengan link repository yang sudah anda copy sebelumnya) :

  ```bash
  git init
  git remote add origin <repositori_url>
  git pull origin mater
  git add .
  git commit -m "message"
  git push -u origin master
  ```
  
<img width="977" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/da7d94a6-f96e-474a-b142-f7fe994d8675">


___gambar 5.__ terminal script_


and here we go! sudah berhasil push di github

<img width="927" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/97644a13-bd2e-4734-90fb-5de1d040ff2c">


___gambar 6.__ done upload to github_


## Mau tau cara yang lebih mudah?

misalnya begini :
saya sudah memperbarui kode saya seperti dibawah ini, secara otomatis visual studio code bisa mengenali perubahan yang terjadi

<img width="1104" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/7db7701c-ad77-4fbc-ad11-0476910192e3">

___gambar 7.__ update code_


selanjutnya silahkan klik saya pada tab source control tersebut, lalu anda bisa lakukan commit secara langsung

<img width="368" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/91531987-c748-48d1-b1d7-0d2eef386eed">

___gambar 8.__ commit without write script_

dan terakir lakukan push ke branch master

<img width="370" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/a889c47f-7bfb-43f9-befe-81ab3ddf9836">

___gambar 9.__ push to branch_


## License

[mirfanlutfi](https://github.com/irfanltf)
