# Think Ap Java

## Panduan dalam kolaborasi

Berikut ini adalah langkah-langkah yang harus kamu lakukan untuk bisa berkolborasi dalam proyek penterjemaahan ini
1. Install LaTex pada komputer lokal
2. Install LaTex Editor (saya merekomendasikan TeXstudio) pada komputer loka
3. Install Git pada komputer lokal
4. Buat account github
5. Fork Repositor ini (TJBOOK)
6. Buat sebuah direktori di komputer lokal dengan naba TJBOOK
7. masuk ke Direktori yang telah dibuat lewat command line
8. Setelah masuk, ketikkan perintah "git init" pada Command line
9. Tambahkan alamat remote forking repositori pada komputer lokal, dengan mengetikan perintah " git remote add [shortname] [url]" pada command line. contoh  "git remote add thinkjava ttps://github.com/USERNAMEKAMU/TJBOOK.git", dimana thinkjava adalah nama alias untuk url yang ditambahkan, kamu bisa membuat nama alias yang lain.
6. Setelah melakukan Forking, maka kamu dapat menarik seluruh berkas yang telah kamu Fork ke komputer lokal kamu. Perintah untuk melakukan hal ini adalah "git pull https://github.com/USERNAMEKAMU/TJBOOK.git" pada command line.
7. Setelah melakukan perintah pull, maka kamu dapat melakukan proses penterjemahan di komputer lokal kamu. Silahkan liat panduanpenterjemahan di bagian bawah.
10. Jangan lupa untuk selalu commit ketika menambahkan perubahan ke repository lokal mu (silahkan cari sendiri cara untuk melakukan commit pada git)
11. Setelah bab yang diterjemahkan selesai (pastikan telah di commit), maka kamu dapat mengunggah setiap perubahan yang telah kamu buat ke github lewat perintah git push [nama alias remote repositori] pada command line. Contoh "git push thinkjava".
12. Untuk menggabungkan hasil terjemahan kamu ke repositori utama (repositori ini). Maka kamu dapat menekan tombol "New pull request" yang terdapat pada halaman fork repositori di github kamu.



## Panduan dalam menterjemahkan

Berikut ini adalah panduan dalam melakukan penterjemahan dengan menggunakan LaTex:
1. Buka program LaTex Editor yang telah kamu install
2. Buka berkas main.tex, berkas ini merujuk ke berkas latex untuk masing-masing bab. 
3. Jika ingin menterjemahkan sebuah bab baru, yang belum ditambahkan, maka kamu dapat membuat berkas baru tersebut dengan format 'Bab-XX.tex' diman XX adalah nomor bab nya (contoh : Bab-5.tex). 
4. Setelah itu, kamu dapat menambahkan referensi dari berkas yang baru kamu buat ke berkas main.tex dengan cara mengetikkan baris "\include{NAMABERKAS}". Sebagai contoh, jika kamu ingin menambahkan referensi Bab-5.tex maka kamu harus menambahkan baris \include{Bab-5}. Perhatikan penulisan nama berkasnya tanpa akhiran .tex.

Selamat menterjembahkan
