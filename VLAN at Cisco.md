# VLAN (Virtual Area Network)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/3b69bcac-c0c6-46ef-a077-3be4e213a83a)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/40c80f1c-2b4e-4e66-b488-572c084c9be4)  

Tujuan
Bagian 1: Verifikasi Konfigurasi VLAN Default    
Bagian 2: Konfigurasikan VLAN  
Bagian 3: Tetapkan VLAN ke Port  

Latar belakang  
VLAN berguna dalam administrasi grup logis, memungkinkan anggota grup dengan mudah dipindahkan, diubah, atau ditambahkan. Kegiatan ini berfokus pada pembuatan dan penamaan VLAN, serta penetapan port akses ke VLAN tertentu.  

# PART 1: Lihat Konfigurasi VLAN Default  
Langkah 1: Tampilkan VLAN saat ini.  
Langkah 2: Verifikasi konektivitas antar PC di jaringan yang sama.  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/974545a6-6735-4030-b771-b89845df4b08)  

# PART 2 : Konfigurasikan VLAN  
Langkah 1: Buat dan beri nama VLAN di S1.
A. Buat VLAN berikut. Nama peka huruf besar-kecil dan harus sama persis dengan persyaratan:

· VLAN 10: Fakultas/Staf

Buka jendela konfigurasi

S1#(konfigurasi)#vlan 10

S1#(config-vlan)# nama Fakultas/Staf

B. Buat VLAN yang tersisa.

`· VLAN 20: Siswa

· VLAN 30: Tamu (Default)

· VLAN 99: Manajemen & Asli

· VLAN 150: SUARA`

Langkah 2: Verifikasi konfigurasi VLAN.

Langkah 3: Buat VLAN di S2 dan S3.
Gunakan perintah yang sama dari Langkah 1 untuk membuat dan memberi nama VLAN yang sama pada S2 dan S3.

Langkah 4: Verifikasi konfigurasi VLAN.  
S1  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/a3bdbee6-1cbb-4354-adf3-85881a0f403f)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/948f776c-1f73-4448-829c-8294aa9909ce)  

S2  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/da7a116f-f4cd-4583-9734-9034964be976)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/853be1a2-7d53-4860-aae7-565eff5ce99e)  

S3  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/642aed6e-5a76-4bd5-b32a-4a9386801ced)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/6c744e94-1b27-4018-8e70-8df5034147a0)  

# PART 3 : Tetapkan VLAN ke Port
Langkah 1: Tetapkan VLAN ke port aktif di S2.  
A. Konfigurasikan antarmuka sebagai port akses dan tetapkan VLAN  
B. Tetapkan port yang tersisa ke VLAN yang sesuai.  
Langkah 2: Tetapkan VLAN ke port aktif di S3.  
Langkah 3: Tetapkan VOICE VLAN ke FastEthernet 0/11 di S3.  
S2   
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/46d8c303-6502-475d-a2a7-1ecf99249551)  

S3  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/3a07f087-1e0a-4e0d-a5c5-f40b9dd4213d)   

# Part 4 : Verifikasi hilangnya konektivitas.
Sebelumnya, PC yang berbagi jaringan yang sama dapat berhasil melakukan ping satu sama lain.  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/4d81c847-acac-4d42-85a0-4204ef0b8f0b)    

Tutup jendela konfigurasi


