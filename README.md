# Jawaban-Test-Bootcamp
Berikut adalah jawaban-jawabannya
---
1. DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna menggabungkan proses development/pengembangan dari sebuah sistem/aplikasi dengan operation/operasional. Dan merupakan sebuah prinsip dimana tugas seorang DevOps untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien. Link Gambar -> [Gambar 1](https://drive.google.com/file/d/1Rxj-Cwm2ffKIsoOTbaDOr-8RzDHNEAum/view?usp=sharing)


2.

3.


4. CI/CD diperlukan karena berguna dalam membantu developer dan tester dalam melakukan rilis dan update aplikasi atau software dengan lebih cepat dan aman, terutama karena CI/CD dilakukan dalam ‘environment’ yang terstruktur. [Gambar 4](https://drive.google.com/file/d/1Jh2rinauB6P0PjfWXkDd3vsD-OR4pGtd/view?usp=sharing)


5. Public Cloud adalah layanan Cloud Computing yang disediakan untuk masyarakat umum. Kita sebagai user tinggal mendaftar ataupun bisa langsung memakai layanan yang ada. Banyak layanan Public Cloud yang gratis, dan ada juga yang perlu membayar untuk bisa menikmati layanannya. Contoh Public Cloud : Windows Live Mail, Skype, Bing.
   Private Cloud adalah layanan Cloud Computing yang disediakan untuk memenuhi kebutuhan internal dari organisasi/perusahaan. Biasanya departemen IT akan berperan sebagai Service Provider (penyedia layanan) dan departemen lain menjadi user (pengguna). Sebagai Service Provider, tentu saja Departemen IT harus bertanggung jawab agar layanan dapat berjalan dengan baik sesuai dengan standar kualitas layanan yang telah ditentukan oleh perusahaan, baik infrastruktur, platform, maupun aplikasi yang ada. Contoh Private Cloud : IBM, Hewlett Packard Enterprise, IDCloudHost Indonesia. [Gambar 5 : Perbedaan Private Cloud vs Public Cloud](https://drive.google.com/file/d/14H4o12eODf3UR2yxFIpo-TcO54XLoUWm/view?usp=sharing)
   
6. Perintah-perintah Git :
-git clone
  Ini ditujukan untuk menyalin sebuah repository publik ke lokal. Misalnya repository milik orang lain yang berisi source code dan bersifat publik
  
-git branch
  Perintah ini digunakan untuk membuat cabang/branch bru agar developer/contributor dpat berkesperimen dengan kodinganya masing-masing.
  
-git push
  Untuk mengirimkan perubahan file setelah di commit ke remote repository.
  
7. Reverse Proxy pada sistem operasi Linux bertindak sebagai penghubung antara host (client) dan server. Reverse proxy membawa request client dan menyalurkannya ke server lain. Akhirnya, mengantarkan respon server pada client, seolah muncul dari proxy server itu sendiri. Cara kerjanya adalah Reverse proxy berjalan di port 80 untuk melayani rekues Http. Di port 80 Reverse Proxy tidak menggantikan fungsi Web Server, melainkan dia akan melanjutkan rekues Http tersebut ke Web Server untuk diolah. Dan apabila Web Server telah selesai mengolah permintaanya tersebut, Web Server akan mengembalikan kembali ke Reverse Proxy. Sebelum Reverse Proxy mengirim kembali rekues Http tersebut ke client sebagai respons (HTTP Response), Reverse Proxy akan menyimpan respon Http tersebut kedalam media penyimpanan sekunder. Sehingga, apabila ada rekues Http yang sama kembali, Reverse Proxy akan mengambil langsung response Http tersebut tanpa meneruskan rekues Http tersebut ke Web Server. [Gambar 7](https://drive.google.com/file/d/1a4aR7l0Ylek-qIhi0FbJKrLRufVit70d/view?usp=sharing)

8. Langkah-langkah membuat app statis Hugo :
a) Pertama buat sebuaf folder dimana foler tersebut berisi 2 sub folder seperti berikut [Gambar 8](https://drive.google.com/file/d/19Z6eDw0fsIsp7zgDStjRAhi8dHiFZWBv/view?usp=sharing)
b) Lalu pergi ke [link ini](https://github.com/gohugoio/hugo/releases) untuk mendownload hugo dengan versi yang sesuai dengan OS nya.
c) Setelah itu download dan extract file tersebut di dalam subfolder yang akan ditempatkan sebagai file projek Hugo. [Gambar 9](https://drive.google.com/file/d/1NNyRNZ_Lmt-EOAv9b7wNwp7Ye7BnMXv9/view?usp=sharing)

d) Setelah itu di install.
e) Lalu tentukan environment path nya sesuai dengan file projek Hugo berada seperti pada gambar berikut. [Gambar 10](https://drive.google.com/file/d/1qvMSDT3LRdQGHH7QmINF-APNsLnCD_Zg/view?usp=sharing)

f) Setelah buka IDE dan ketik perintah di terminal (Command Line/Bash) untuk membuat direktori projek Hugo, dan jangan lupa harus berada di direktori projek yang dimaksud. [Gambar 11](https://drive.google.com/file/d/1SEqI945UsY74jeTC3CL-Bd4BgzBvSsX8/view?usp=sharing).

g) Setelah itu akan terbentuk direktori baru sesuai dengan apa yang dibuat. Lalu langkah selanjutnya adalah mencari tema yang sesuai dengan style yang di inginkan.
h) Untuk mencari tema dapat dicari pada link berikut ini (https://themes.gohugo.io/)
i) Lalu klik pada tema dan klik download, lalu extract file tersebut ke dalam folder theme yang berada pada direktori yang sudah dibuat. [Gambar 11](https://drive.google.com/file/d/112ae-lx5Fx2g_5ymIqyR9d-QCAW3QLVb/view?usp=sharing)

j) Lalu masukkan nama tema yang sesuai dengan tema yang telah di download seperti gambar ini. [Gambar 12](https://drive.google.com/file/d/1MyU8P1iljh3cI8cvZNv6fRjf-SX1TRRz/view?usp=sharing)

k) Setelah itu buat konten berformat markdown. Buka kembali terminal lalu ketik "hugo new konten.md" (tanpa tanda petik). konten.m adalah file yang saya buat sendiri, dapat diberi nama sesuka hati.

l) Lalu isi konten tersebut seperti gambar berikut. [Gambar 13](https://drive.google.com/file/d/1jvYtYBc99GZVkrN7-iEh2jo_ZIQHg4UF/view?usp=sharing)
m) Apabila sudah selesai mengisi konten, jangan lupa membuka terminal kembali dan ketik perint hugo server -D. Setelah itu buka browser dan ketik localhost:1313 dan berikut adalah tampilan webnya. [Gambar 14}(https://drive.google.com/file/d/1nJeoXGiabLQNO8yoFacYjdzk0V3MZ0V-/view?usp=sharing)

n) Setelah selesai membuat web static langkah selanjutya adalah mengupload ke Github pages untuk mengikut langkah-langkah (https://pages.github.com)
o) Buka terminal (harus berada di direktori projek Hugo kita) dan ketik perintah berikut agar aplikasi bisa di upload di Github pages
   -git clone (nama url repository)
   -git add --all
   -git commit -m "(Bebas mau commit apa aja)"
   -git push -u origin main
   
  jouzu1.github.io
  
  *Keterangan :
  OS---> Windows 10
  Referensi yang di pakai------------>(https://platinum-computer.com/apa-itu-public-private-dan-hybrid-cloud/)
                         ------------>(https://idcloudhost.com/apa-itu-private-cloud-pengertian-fungsi-keunggulan-dan-kelebihannya/)
                         ------------>(https://www.jagoanhosting.com/blog/implementasi-ci-cd-pipeline/#:~:text=CI%2FCD%20juga%20berguna%20dalam,dalam%20'environment'%20yang%20terstruktur.)
                         ------------>(https://idcloudhost.com/pengertian-dan-manfaat-git-bagi-developer/#:~:text=Git%20push%20%3A%20untuk%20mengirimkan%20perubahan,yang%20aktif%20dengan%20branchyang%20dipilih)
                         ------------>(https://www.hostinger.co.id/tutorial/nginx-reverse-proxy/#:~:text=Reverse%20Proxy%20pada%20sistem%20operasi,dari%20proxy%20server%20itu%20sendiri.)
                         ------------>(https://gist.github.com/alfafahmi/3223ea5d91ba9cd77add886ef63781a0)
                         ------------>(https://www.kompasiana.com/mboi.coy/54febc6fa33311d31a50f940/lebih-lanjut-mengenai-reverse-proxy)
                         ------------>(https://www.dicoding.com/blog/apa-itu-devops/)
                         Hugo------------>(https://www.youtube.com/watch?v=0GZxidrlaRM&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3&index=6)
                         
