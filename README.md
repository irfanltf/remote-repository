# How to Remote Repository in GitHub??

before we talk to far, you should to know what is remote? what is repository?, what is push or pull? what is commit? and another about git!

but in this article, wen jus't will only discuss how to remote a repository, so here we go! 

_article will be continue in bahasa indonesia_

## Pastikan sudah menginstall git di computer

cara untuk memastikannya adalah dengan membuka __terminal__ atau __CMD di Windows__ > lalu ketikan `git -v` jika tampil seperti dibawah ini maka telah menginstall git, namun jika belum maka keterangan versi tersebut tidak akan muncul, maka dari itu silahkan download git pada halaman berikut ini
- GIt for Windows https://git-scm.com/download/win
- Git for Mac OS https://git-scm.com/download/mac
  
<img width="322" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/5ca289e0-45a5-4446-a5f0-b62ed9748770">

___gambar 0.__ install git 

## Pastikan sudah mempunyai repository di github


<img width="1096" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/dcc77c2f-1bdc-44cf-b9b7-1d0f56814144">

___gambar 1.__ repository in github_ 


## Buka Project File pada Code Editor Visual Studio Code

<img width="1264" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/34a0d80b-7029-4a1b-917b-001ebd87fcbf">

___gambar 2.__ open project folder to code editor_ 


## Buka Terminal Pada Code Editor Visual Studio Code
untuk membka terminal pada visual studio code anda dapat memilih __menu terminal__ > pilih __new terminal__

<img width="1191" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/ca7d0d33-d5b9-4925-8c10-769dcc7a898a">


___gambar 3.__ open terminal_

## Clonning Repository
- untuk clonning repository anda dapat copy link bagian https (pada gambar 4)
  
<img width="412" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/5d18ad37-7693-44c7-8b76-1773a20e66a5">

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
  
<img width="970" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/a0fd5f95-af95-45d3-a088-457a9c78781c">


___gambar 5.__ terminal script_


and here we go! sudah berhasil push di github

<img width="934" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/96dc353d-5051-4608-8247-b2e768bfd58e">


___gambar 6.__ done upload to github_


## Mau tau cara yang lebih mudah?

misalnya begini :
saya sudah memperbarui kode saya seperti dibawah ini, secara otomatis visual studio code bisa mengenali perubahan yang terjadi

<img width="808" alt="Screenshot 2023-09-07 at 19 58 15" src="https://github.com/irfanltf/remote-repository/assets/48278734/41493e3c-199d-42d1-bdde-0d5fefee11d2">

___gambar 7.__ update code_


selanjutnya silahkan klik saya pada tab source control tersebut, lalu anda bisa lakukan commit secara langsung

<img width="553" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/b386dd02-6fd4-4204-9885-aff515668854">

___gambar 8.__ commit without write script_

dan terakir lakukan push ke branch master

<img width="461" alt="image" src="https://github.com/irfanltf/remote-repository/assets/48278734/d1699260-cfc9-4ec4-8db1-05017d936397">

___gambar 9.__ push to branch_


## License

[mirfanlutfi](https://github.com/irfanltf)
