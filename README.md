# Configure Initial Switch Settings  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/667b508b-b9cc-47fb-937b-50658eceea48)  

Berikut adalah langkah-langkah detail untuk setiap bagian dari tutorial konfigurasi switch menggunakan Cisco Packet Tracer:  

`INSTRUKSI`     
Part 1: Verify the Default Switch Configuration  
`Step 1: Enter privileged EXEC mode.`  
1. Buka aplikasi Cisco Packet Tracer dan buka proyek dengan switch yang ingin Anda konfigurasi.  
    Klik dua kali pada switch untuk membuka jendela konfigurasi.  
    Pastikan semua konfigurasi default sesuai dengan yang diharapkan sebelum melanjutkan ke langkah berikutnya.
   Klik `Open`  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/8040da18-cb4f-4671-b5fc-3da4b1543090)

    Lalu akan tampil seperti gambar dibawah ini :  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/5ef82314-9a55-41fa-addf-3907f6c2a39a)

2. Klik S1 dan kemudian tab CLI. Tekan enter.  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/54db350c-4a42-42ca-a044-a7cc68eeb21d)

3. Masuk ke mode EXEC istimewa dengan memasukkan perintah aktifkan:  
   Buka Jendela Konfigurasi untuk S1
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/58dce751-87ed-4838-92ab-1e72b4a1b89d)

4. Switch> enable  
   ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/366f79fe-9285-4908-af97-60e9a3e39049)  

`Step 2: Examine the current switch configuration.`    
Enter the show running-config command.  
Switch# show running-config
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/755e52f0-33f5-48e1-9d16-ef58bfdc52bb)  

Part 2: Create a Basic Switch Configuration  
`Step 1: Assign a name to a switch.`  
Untuk mengonfigurasi parameter pada sakelar, Anda mungkin diminta untuk berpindah di antara berbagai mode konfigurasi.  
Perhatikan bagaimana perintah berubah saat Anda menavigasi saklar.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/1ac9deb4-1922-491b-be5f-1938d7b2af49)  

`Step 2: Secure access to the console line.`  
Untuk mengamankan akses ke jalur konsol, akses mode baris konfigurasi dan atur kata sandi konsol ke azza.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/ff4da588-7db0-457c-b9ad-461d075f26b2)  

Mengapa perintah login diperlukan?  

`Step 3: Verify that console access is secured.`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/071253f9-9248-4009-94e9-a38e9fc38afb)  
Catatan: Jika switch tidak meminta kata sandi kepada Anda, berarti Anda tidak mengonfigurasi parameter login pada Langkah 2.   

`Step 4: Secure privileged mode access.`  
Setel kata sandi pengaktifan ke azza123. Kata sandi ini melindungi akses ke mode istimewa.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/242fb07b-7095-41e2-8c18-4932c10adca5)  

`Step 5: Verify that privileged mode access is secure.`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/073fbca2-ae6a-4da1-89c8-83094368720e)  

`Step 6: Configure an encrypted password to secure access to privileged mode.`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/567175dc-5ec9-42d5-a7b2-2e7f17a6ba40)  

`Step 7: Verify that the enable secret password is added to the configuration file.`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/17c04794-482f-4ff0-bee4-c7318b920c82)  

`Step 8: Encrypt the enable and console passwords.`  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/a2e97a30-b28e-4a70-a9e2-cd82172ce8de)  

Part 3: Configure a MOTD Banner  
`Step 1: Configure a message of the day (MOTD) banner.`  

Lampirkan teks spanduk dalam tanda kutip atau   
gunakan pembatas yang berbeda dari karakter apa pun yang muncul dalam string MOTD.  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/d21c026c-03e6-4308-b508-155d0c4aae71)  

Kapan spanduk ini akan ditampilkan?  

Mengapa setiap switch harus memiliki banner MOTD?  

Part 4: Save and Verify Configuration Files to NVRAM  
Step 1: Verify that the configuration is accurate using the show run command.  
Simpan file konfigurasi.   
Anda telah menyelesaikan konfigurasi dasar switch.  
Sekarang buat cadangan file konfigurasi yang sedang berjalan ke NVRAM   
untuk memastikan bahwa perubahan yang dilakukan tidak hilang jika sistem di-boot ulang atau kehilangan daya.  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/d42e2c9f-ef00-4e24-9acb-e9480f3864f5)  

Part 5: Configure S2  
Anda telah menyelesaikan konfigurasi pada S1.  
Anda sekarang akan mengkonfigurasi S2. Jika Anda tidak dapat mengingat perintahnya, lihat Bagian 1 hingga 4 untuk bantuan.  
Konfigurasikan S2 dengan parameter berikut:

A. Nama perangkat: S2  

B. Lindungi akses ke konsol menggunakan kata sandi azza.  

C. Konfigurasikan kata sandi pengaktifan c1$c0 dan kata sandi rahasia pengaktifannya.  

D. Konfigurasikan pesan yang sesuai untuk mereka yang masuk ke switch.  

e. Enkripsi semua kata sandi teks biasa.  

F. Pastikan konfigurasinya benar.  

G. Simpan file konfigurasi untuk menghindari kehilangan jika saklar dimatikan.  









        




    
  



   

