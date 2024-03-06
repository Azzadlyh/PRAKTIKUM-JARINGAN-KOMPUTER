# PRAKTIKUM-JARINGAN-KOMPUTER  
# Wireshark  
HAI THIS IS TUTORIAL HOW TO MAKE "QUALITY of SERVICE WIRESHARK"  
Let's to try !!  

Yang dibutuhkan Quality of Service :  
1. Install Wireshark APP
2. IP ADDRESS
3. Match Conection Network

Langkah - Langkah  :  
1. Klik `WI-FI` pada home wireshark  
![image](https://github.com/Azzadlyh/Wireshark/assets/126213404/44bb2baf-25c3-4482-b738-ff88badafe1b)

note : Contoh IP ADDRESS user lain 
![image](https://github.com/Azzadlyh/Wireshark/assets/126213404/25b1ce10-985c-43b7-a543-c5b1d129e9d3)  

2. Masukkan IP ADDRESS user lain pada Wireshark.  
![image](https://github.com/Azzadlyh/Wireshark/assets/126213404/e2dd55b2-e4a9-468f-bd0d-25082a2a8e69)  

  Tunggu sekitar 5-10 menit IP address yg digunakan untuk melakukan aktivitas dan     akan terkumpul jumlah packetnya, kemudian buka bagian statistic.  
  ![image](https://github.com/Azzadlyh/Wireshark/assets/126213404/6df1fab7-00d8-43e0-bf1a-a349828a4ec3)  

  ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/f26152cd-759b-48c5-9948-850ded2f330a)  

3. Buka bagian details Statistics  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/3de0a966-db6f-456e-836c-7c6e7822f3aa)  

4. Kemudian lakukan perhitungan untuk menghitung hasil bytes (Throughtput)  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/597833a9-95ed-4e1b-bcc8-120c8f8d2691)  

5. Pehitungan Packet Loss  
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/53abdb2b-7d1b-4d12-8932-1e90cd93b51a)

6. Klik `File` - `Export Packet Dissections` - `As CSV`
![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/531ddadf-0415-45a4-ace6-a90ee961791f)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/91ce4bb5-0797-46ab-ac6e-7f48a33804e8)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/985e218f-b8e1-44cf-b1ce-b3aad3924e4a)  ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/658ed073-2eee-4f59-abf8-74c57e40d0c6)  ![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/5759e5c4-eef8-4bc1-a420-2d0c580f39ae)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/7d6e0f74-70d3-4726-894b-5d21273d8f4a)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/61fa7146-bd3b-409c-a4e9-409202cd0e0b)  

`Rumus Perhitungan Delay`  
  Time 2 - Time 1 = Hasil Delay  

`Perhitungan Hasil Delay`  
  Total Delay = SUM(Blok semua hasil delay) Enter  
  
`Perhitungan Rata-rata Delay`  
  Rata-rata Delay =(Total Delay/Jumlah Paket) Enter 

`Rumus Menghitung Jitter`   
  Jitter           = Delay2 - Delay1  
  Total Jitter     =SUM(Blok semua hasil jitter) Enter  
  Rata-rata Jitter =(Total jitter/jumlah paket lalu) Enter  


