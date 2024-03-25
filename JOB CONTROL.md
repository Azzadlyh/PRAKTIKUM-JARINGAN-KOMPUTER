# JOB CONTROL  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/8da4ebe3-b22f-4e5b-b171-586e55b0304b)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/bf4a71cf-777b-4031-864e-6e238e504ff5)  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/c536d515-d709-47be-981f-fa01324e0d06)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/a3951bbb-f314-402b-9146-492be267c196)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/4eaeb19c-24ad-4439-8275-3c941ee5f13d)  

B. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :  
/home/stD02001/.bash_profile  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/1371ade7-6c35-4941-bade-bfc5f7358297)  

/home/. stD02001/.bash_login
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/ed91a238-6354-482c-ac76-d1e20d65136f)  

/home/mahasiswa/.profile  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0135ae1b-7354-41e8-8220-00b51eb5ccdc)  

/home/mahasiswa/.bashrc  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/c104c7ef-0297-404c-9c02-8095a866f4d5)  

C. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: 
Merubah file-file menjadi file executeable  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/196f67e4-537f-48b1-8bd9-b3bdd49b3912)  

`su azza`  
`exit`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/039b6c2d-aebc-4256-9349-4361dede8452)  

kemudian gunakan opsi – sebagai berikut :  
`su - azza`
`exit`
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/604fa2f7-5d62-4e79-9912-bf54e87a7c56)  

Jelaskan perbedaan kedua utilitas tersebut.  
Perbedaan  kedua  utilitas  tersebut  yaitu menampilkan  isi  dari file-file  yang  dibuat  pada    direktori    yang  berbeda.  Untuk  direktori  yang  memiliki  banyak  file,  hanya  akan ditampilkan satu buah filenya saja.

2. Prompt String (PS)  
   a. Edit file  .bash_profile, ganti prompt PS1 dengan ‘>’.  
    Instruksi export diperlukan dengan parameter nama variable tersebut, agar perubahan variable PS1 dikenal oleh semua shell
   `$ PS1=“\! > “  
   81 > PS1=”\d > “
   Sen Mar 25 > PS1=”\t > “
   11:38:14 > PS1=”Saya=\u > “
   Saya=mahasiswa > PS1=”\w >”  
   ~ > PS1=\h >”`  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/49b2a4ae-9b37-4607-9baa-16c33224d434)  
   syntax diatas berfungsi untuk menampilkan informasi sesuai dengan option perintah seperti d adalah data (tanggal), t adalah time (waktu), u adalah user (pengguna).

3. Logout  
   Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout  
   `Echo “Terima kasih atas sesi yang diberikan”
   Sleep 5   clear`
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0e649cfc-c141-4bb2-bf49-b890bf670918)  

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0f9879f0-f690-4fa6-88e2-0261efb97225)
   Tampilan layer setelah 5 detik  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/9f838c34-7352-4730-99ae-c8eae0dcc6c7)  
  Untuk mengedit file .bash_logout masuk sebagai user root terlebih dahulu.
Lalu masukkan text edit dengan echo beserta waktu tunggu selama 5 detik (5 sleep) dan juga syntax clear yang berfungsi untuk membersikan layar saat file .bash_logout ditampilkan,
untuk menampilkan file .bash_logout ubah file menjadi executable terlebih dahulu. Jika file tampil, maka ia akan memeberikan output berupa inputan text yang kita masukkan yaitu Terima kasih atas sesi yang diberikan dan layar akan dibersikan setelah 5 detik.

4. Bash script
   Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
   `p1.sh
   #! /bin/bash
   echo “Program p1”
   ls –l`
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/b5afeb95-c434-4d1b-8582-eb433c7705d9)    

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/91d86cd5-1e03-40b2-9256-2278df98c820)  
