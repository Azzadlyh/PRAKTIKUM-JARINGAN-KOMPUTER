# JOB CONTROL  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/090c0dd0-e26a-4d76-8c8c-f80891dccc6f)  

# 1. Eksekusi seluruh profile yang ada :   
   a. Edit file profile /etc/profile dan tampilkan pesan sebagai berikut :   
      `echo “Profile dari /etc/profile”`  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/bf4a71cf-777b-4031-864e-6e238e504ff5)  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/c536d515-d709-47be-981f-fa01324e0d06)  

      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/a3951bbb-f314-402b-9146-492be267c196)  

      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/4eaeb19c-24ad-4439-8275-3c941ee5f13d)  

   b. Asumsi nama anda stD02001, maka edit semua profile yang ada yaitu :  
      /home/stD02001/.bash_profile  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/1371ade7-6c35-4941-bade-bfc5f7358297)  

      /home/. stD02001/.bash_login
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/ed91a238-6354-482c-ac76-d1e20d65136f)  

      /home/mahasiswa/.profile  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0135ae1b-7354-41e8-8220-00b51eb5ccdc)  

      /home/mahasiswa/.bashrc  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/c104c7ef-0297-404c-9c02-8095a866f4d5)  

   c. Jalankan instruksi subtitute user, kemudian keluar dengan perintah exit sebagai berikut: 
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

# 2. Prompt String (PS)  
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

# 3. Logout  
   Edit file .bash_logout, tampilkan pesan dan tahan selama 5 detik, sebelum eksekusi logout  
   `Echo “Terima kasih atas sesi yang diberikan”
   Sleep 5   clear`
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0e649cfc-c141-4bb2-bf49-b890bf670918)  

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/0f9879f0-f690-4fa6-88e2-0261efb97225)
   
   Tampilan layer setelah 5 detik  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/9f838c34-7352-4730-99ae-c8eae0dcc6c7)  

# 4. Bash script
   a. Buat 3 buah script p1.sh, p2.sh, p3.sh dengan isi masing-masing :
   p1.sh
   `#! /bin/bash
   echo “Program p1”
   ls –l`
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/b5afeb95-c434-4d1b-8582-eb433c7705d9)    

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/91d86cd5-1e03-40b2-9256-2278df98c820)

   p2.sh
   `#! /bin/bash
   echo “Program p2”
   who`

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/3fba7dfc-e8bb-4e0e-b405-e58e81b6119f)  

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/68f13600-fccc-4bdf-bb67-7a51212ba744)

   p3.sh
   `#! /bin/bash
   echo “Program p3”
   ps x`

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/9e5d44c4-3738-418f-901d-a4cb94ddc53d)

   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/cac98ce2-007d-41e6-a220-c390a7de92ae)

   b. Jalankan script tersebut sebagai berikut :
      Kita execute file dulu agar bisa dijalankan
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/e615d7ba-e546-43f0-93b3-ef20d79baced)

      `$  ./p1.sh ; ./p3.sh ; ./p2.sh`
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/13001899-737f-45ea-a615-3017b5761b82)
      `$  ./p1.sh &`  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/deb8abdb-f6c7-4fa8-86ca-36358c066999)
      `$  ./p1.sh $ ./p2.sh & ./p3.sh & `  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/e9b6c621-dfbd-48d8-aeed-7a63f2ca0e4d)  
      `$  ( ./p1.sh ; ./p3.sh ) &`  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/6f61e1a4-d86f-41c8-8cc1-301f935b817b)

   # 5. Jobs
      a. Buat shell-script yang melakukan loop dengan nama pwaktu.sh,  setiap 10 detik, kemudian menyimpan tanggal dan jam pada file hasil.
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/8f0f67c5-f1c1-4034-9b9a-35cf61de5ced)  

      b. Jalankan  sebagai  background;  kemudian  jalankan  satu  program  (utilitas  find)  di background sebagai berikut :
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/b453635c-d74b-482f-b805-008f2fc5f988)

      c. Jadikan program ke 1 sebagai foreground, tekan ^Z dan kembalikan program tersebut ke background
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/888c0503-d210-41ba-950e-db3489b38be9)

      d. Stop program background dengan utilitas kil  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/8388ba4b-d118-4459-a7c4-ef7b7ac92cc8)
      
      `$ kill [Nomor PID]`  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/a887ca7c-2a24-4bda-90d8-9c43cff870cf)

   # 6. History   
      a. Ganti nilai HISTSIZE dari 1000 menjadi 20
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/ffea3f4d-7d8d-49cb-9264-e8d33ff7e8fe)  

      b. Gunakan  fasilitas  history  dengan  mengedit  instruksi  baris  ke  5  dari  instruksi  yang terakhir dilakukan
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/1892ec32-9b1b-43f5-b9e9-41afba08cff5)

      c. Ulangi instruksi yang terakhir.  Gunakan juga ^P dan ^N untuk bernavigasi pada history bufer
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/7b665676-b446-40ed-b669-647ada262baa)

      d. Ulangi instruksi pada history bufer nomor 150
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/b33e10eb-05f6-4a7f-8729-6159059dc0c5)

      e. Ulangi instruksi dengan prefix “ls”  
      ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/6df0c839-7551-4289-b9fb-300e1728fdd7)

# Kesimpulan : 
   Percobaan ini menunjukkan bahwa ketelitian sangatlah penting dalam menjalankan percobaan tentang profile, history, dan job control.   
   Bahkan sebuah kesalahan sekecil apapun, seperti kurangnya satu spasi saja, bisa mengakibatkan masuk ke direktori yang berbeda.   
   Selain itu, langkah penting yang harus dilakukan setelah pembuatan program adalah melakukan eksekusi file terlebih dahulu agar memperoleh izin untuk menjalankan program tersebut.  
   
