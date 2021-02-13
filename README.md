# Jawaban-Test-Bootcamp
Berikut adalah jawaban-jawabannya
---
1. DevOps merupakan singkatan dari dua kata yaitu Development dan Operation. Di mana kedua kata tersebut bermakna menggabungkan proses development/pengembangan dari sebuah sistem/aplikasi dengan operation/operasional. Dan merupakan sebuah prinsip dimana tugas seorang DevOps untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien. Adanya DevOps dalam perusahaan tentu akan sangat penting karena dapat mengurangi jumlah kesalahan, recovery lebih cepat dan deploy lebih banyak sehingga menjadi lebih efisien. Link Gambar -> [Gambar 1](https://drive.google.com/file/d/1Rxj-Cwm2ffKIsoOTbaDOr-8RzDHNEAum/view?usp=sharing)


2.
| Offered   Services  | AWS                      | OpenStack           |
|---------------------|--------------------------|---------------------|
| Virtual Servers     | EC2                      | Nova   Instance     |
| Dockers             | ECS                      | Magnum              |
| Scalability         | AWS   Scaling            | Heat   with Scaling |
| Load Balancing      | Elastic   Load Balancing | LBaas               |
| API                 | EC2   API                | OpenStack   API     |
| GUI                 | Console                  | Horizon             |
| Storage Object      | S3                       | Swift               |
| Block Storage       | EBS                      | Cinder              |
| Networking          | Networking               | Neutron             |
| Compute             | VM                       | Instance            |
| Security/ Identity  | I   AM                   | KeyStone            |
| Orchestration       | CloudFormation           | Heat                |
| Archiving           | Glacier                  | Swift               |
| Image Templates     | Amazon   Machine Images  | Glance              |
| DNS Management      | Route   53               | Designate           |
| Relational Database | RDS                      | Trove               |

3. Git adalah sebuah Version Control System (VCS) yang membantu kita menjaga agar ada pembedaan masing-masing file, sehingga file tetap di jalur yang sama ketika dalam penyimpanan ulang. Cara kerja sederhananya yaitu membuat repository dengan 'git init' di folder lokal, setelah itu ketik 'git add .' untuk menambahkan semua file yang ada di lokal dan dikirimkan ke github repository, lalu tambahkan commit untuk menambahkan keterangan dengan mengetik perintah 'git commit -m "(Keterangan commit)".


4. CI/CD diperlukan karena berguna dalam membantu developer dan tester dalam melakukan rilis dan update aplikasi atau software dengan lebih cepat dan aman, terutama karena CI/CD dilakukan dalam ‘environment’ yang terstruktur. [Gambar 4](https://drive.google.com/file/d/1Jh2rinauB6P0PjfWXkDd3vsD-OR4pGtd/view?usp=sharing)


5.
| Perbedaan                   | Ansible                                                                                                                                                                                                                                                                                                                                | Puppet                                                                                                                                                                                                                                                                                                                                                                                      | Terraform                                                                                                                                                                                                                                                                                                                                                                                   |
|---------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Manajemen   dan Penjadwalan           | Di Ansible, penerapan instan   dimungkinkan karena server mendorong konfigurasi ke node. Dalam hal   penjadwalan, Ansible Tower, versi perusahaan, memiliki kemampuan saat tidak   ada dalam versi gratis.                                                                                                                             | Puppet berfokus terutama pada   konfigurasi dorong dan tarik, di mana klien menarik konfigurasi dari server.   Konfigurasi harus ditulis dalam bahasa Puppet. Ketika datang ke penjadwalan,   pengaturan default Puppet memungkinkan untuk memeriksa semua node untuk   melihat apakah mereka dalam keadaan yang diinginkan.                                                                | Di Terraform, penjadwal sumber   daya bekerja sama seperti penyedia yang mengaktifkannya untuk meminta sumber   daya dari mereka. Dengan demikian, ini tidak terbatas pada penyedia fisik   seperti AWS, yang memungkinkan penggunaannya dalam lapisan. Terraform dapat   digunakan untuk menyediakan ke kisi terjadwal, serta menyiapkan infrastruktur   fisik yang menjalankan penjadwal. |
|                                       |                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                                                                                                                                                                                                                                                             |                                                                                                                                                                                                                                                                                                                                                                                             |
| Kemudahan   Pengaturan dan Penggunaan | Ansible lebih sederhana untuk   diinstal dan digunakan. Ia memiliki master tanpa agen, berjalan di mesin   klien. Fakta bahwa itu tanpa agen berkontribusi secara signifikan terhadap   kesederhanaannya. Ansible menggunakan sintaks YAML, yang ditulis dalam bahasa   Python, yang hadir di sebagian besar penerapan Linux dan Unix. | Puppet lebih digerakkan oleh   model, dimaksudkan untuk administrator sistem. Server boneka dapat diinstal   pada satu atau lebih server, sedangkan agen boneka membutuhkan instalasi pada   semua node yang membutuhkan manajemen. Model dengan demikian adalah model   client-server atau agent-master. Waktu penginstalan dapat memakan waktu   sekitar sepuluh hingga tiga puluh menit. | Terraform juga lebih sederhana   untuk dipahami dalam hal penyiapan serta penggunaannya. Bahkan memungkinkan   pengguna untuk menggunakan server proxy jika diperlukan untuk menjalankan   penginstal.                                                                                                                                                                                      |
| Ketersediaan                          | Ansible memiliki node sekunder   jika node aktif jatuh.                                                                                                                                                                                                                                                                                | Puppet memiliki satu atau lebih   master jika master aslinya gagal.                                                                                                                                                                                                                                                                                                                         | Tidak Berlaku dalam kasus   Terraform.                                                                                                                                                                                                                                                                                                                                                      |
| Skalabilitas                          | Skalabilitas lebih mudah   dicapai                                                                                                                                                                                                                                                                                                     | Skalabilitas kurang mudah   dicapai                                                                                                                                                                                                                                                                                                                                                         | Skalabilitas relatif mudah   dicapai                                                                                                                                                                                                                                                                                                                                                        |
| Modul                                 | Repositori atau pustaka Ansible   disebut Ansible Galaxy. Ini tidak memiliki kemampuan penyortiran terpisah dan   memerlukan intervensi manual.                                                                                                                                                                                        | Repositori atau perpustakaan   puppet disebut Puppet Forge. Ini berisi hampir 6000 modul. Pengguna dapat   menandai modul boneka sebagai disetujui atau didukung oleh Puppet, menghemat   banyak waktu.                                                                                                                                                                                     | Dalam kasus Terraform, modul   memungkinkan pengguna untuk mengabstraksi bagian apa pun yang dapat digunakan   kembali. Komponen ini dapat dikonfigurasi sekali dan digunakan di mana saja.   Dengan demikian memungkinkan pengguna untuk mengelompokkan sumber daya, serta   menentukan variabel input dan output.                                                                         |
| GUI                                   | Yang kurang berkembang adalah   GUI Ansible, pertama kali diperkenalkan sebagai alat baris perintah saja.   Meskipun versi perusahaan menawarkan UI, itu masih jauh dari harapan yang   menderita masalah sinkronisasi dengan baris perintah.                                                                                          | GUI Puppet lebih unggul dari   Ansible, mampu melakukan banyak tugas kompleks. Digunakan untuk mengelola,   melihat, dan memantau aktivitas secara efisien.                                                                                                                                                                                                                                 | Hanya GUI pihak ketiga yang   tersedia untuk Terraform. Misalnya, Terraform GUI Codeherent.                                                                                                                                                                                                                                                                                                 |
| Support                               | Ansible juga menyertakan dua   tingkat dukungan profesional untuk versi perusahaannya. Selain itu,   AnsibleFest, yang merupakan pertemuan besar pengguna dan kontributor,   diadakan setiap tahun. Komunitas di belakangnya lebih kecil jika dibandingkan   dengan Puppet.                                                            | Puppet memiliki portal dukungan   khusus, bersama dengan basis pengetahuan. Selain itu, ada dua tingkat   dukungan profesional; Standar dan Premium. Laporan "keadaan DevOps"   diproduksi setiap tahun oleh komunitas Puppet.                                                                                                                                                              | Terraform menyediakan akses   langsung ke saluran dukungan HashiCorp melalui portal web.                                                                                                                                                                                                                                                                                                    |
|                                       | [Gambar 5a :   Ansible](https://drive.google.com/file/d/1Zpd5m6-PGW1C37jewnQ9svnl0Nw3s-Z7/view?usp=sharing)                                                                                                                                                                                                                            | [Gambar 5b :   Puppet](https://drive.google.com/file/d/1v8lMTkVMPnq9xR7UE--kTOtZhMPzeHI1/view?usp=sharing)                                                                                                                                                                                                                                                                                  | [Gambar 5c :   Terraform](https://drive.google.com/file/d/10DQ8GGR5pPs2C1cdr4CVHWnDA_QnoI4x/view?usp=sharing)                                                                                                                                                                                                                                                                               |
   
6. Cara Kerja dari HTTP : client terlebih dahulu melakukan permintaan data kepada server, lalu kemudian server mengirimkan respon berupa file HTML yang ditampilkan dalam browser, ataupun data lainnya yang diminta oleh klien. [Gambar 6a : HTTP](https://drive.google.com/file/d/1Irpm2JV8OlYwzzKNg_239donVkwQ1uUx/view?usp=sharing)

Cara Kerja dari load balance : Saat 4 Client melakukan request data kepada server maka Load Balancer akan membagi beban tersebut menjadi sebagian, client 1 dan client 2 akan dilayani oleh server1 sementara client 3 dan client 4 akan dilayani oleh server2. Sama seperti dengan analogi kue, bila kue adalah data request dari client dan pemakan merupakan server maka kue tersebut akan dibagi sebagian agar kue tersebut habis.[Gambar 6b : Load Balance](https://drive.google.com/file/d/11RSTiPADgwoPDHInHogkC6P2dghk48g6/view?usp=sharing)
   

7. Nagios Core [Gambar 7a](https://drive.google.com/file/d/1wgRuHl_kx6fJuirE5RsMYIpI4AaXEm5W/view?usp=sharing)

   Ganglia [Gambar 7b ](https://drive.google.com/file/d/11PD-kzT-zvazG-AEmsJfcqnAd0fAvPfR/view?usp=sharing)
   
   DataDog [Gambar 7c](https://drive.google.com/file/d/1L8eh3vrVX0aic-DbL_jRnZ1a6-B0lVox/view?usp=sharing)


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
   
  [Project Hugo](https://jouzu1.github.io)
  [Repository Hugo](https://github.com/jouzu1/jouzu1.github.io.git)
  
  *Keterangan :
  OS---> Windows 10
  
  
Referensi :
https://blogs.masterweb.com/tool-monitoring-kinerja-server/

https://phoenixnap.com/blog/ansible-vs-terraform-vs-puppet

https://www.jagoanhosting.com/tutorial/glossary/http#:~:text=Secara%20singkat%2C%20cara%20kerja%20HTTP,menunggu%20respon%20dari%20server%20tersebut.

https://www.jagoanhosting.com/blog/belajar-banyak-tentang-server-kamu-harus-tahu-arti-load-balancing/

https://jihadt-a.blogspot.com/2019/09/pengertian-cara-kerja-load-balance.html

https://indosystem.com/blog/lebih-jauh-tentang-load-balancer/

https://www.hostinger.co.id/tutorial/tutorial-git-dasar-cara-menggunakan-git/

https://www.gangboard.com/blog/aws-vs-openstack

https://medium.com/purwadhikaconnect/mengapa-devops-penting-27dd08115ad3#:~:text=Adanya%20DevOps%20dalam%20perusahaan%20tentu,%2C%20multi%2Dtenant%20dan%20cloud.

                         
