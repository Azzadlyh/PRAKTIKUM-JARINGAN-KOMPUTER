# SWITCHING 

Network Address Translation (NAT)  
Router digunakan sebagai perantara antara modem ADSL (Asymmetric
Digital Subscr iber Line) dengan jaringan LAN. Karena sebagian besar fungsi ro
uter dapat digantikan oleh modem ADSL (Asymmetric Dig ital Subscriber Line), bagi
mereka yang tidak mau pusing dan cukup dengan feature yang seder hana
disarankan untuk menggunakan router mo dem ADSL. Router Linux terutama
ditujukan bagi mereka yang nantinya ingin mengembangkan diri menguasai system
yang lebih kompleks, terutama menggunakan server internet yang berbasis di linux.
Ada beberapa fungsi router yang sering digunakan, minimalnya adalah :  

● Firewall sederhana, untuk mengatur trafik yang diizinkan maupun tidak
diizinkan ke / dari internet. Pada system operasi linux, apalikasi firewall yang
digunakan biasanya sudah ada di system operasi dan dapat diakses
menggunakan perintah iptables.  
● Network Address Translation (NAT) yang sebetulnya menjadi bagian dari
fungsi/kemampuan firewall yang memungkinkan banyak computer di LAN
membagi (sharing) sambungan akses ke internet yang hanya satu buah /
beberapa buah.  
● Fungsi routing, biasanya memang built in pada system operasi linux. Fungsi
routing dibutuhkan jika kita mempunyai beberapa jaringan LAN yang ingin
tergabung ke internet secar a bersama. Jika hanya ada satu buah jaringan LAN
yang ingin tergabung ke internet, fung si routing yang kompleks tidak
dibutuhkan. Pada system operasi linux aplikasi routing yang digunakan
biasanya sudah ada pada system operasi dapat diakses menggunakan router.  
● DHCP server digunakan untuk memberikan IP address (alamat IP) pada
work-station di LAN agar memperoleh IP address secara automatis.  

Berikut Simulasinya :  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/f30f7417-aa9c-4d17-9380-0d314e80cb4f)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/fb65d749-a373-4eae-ac6b-ea0ba8f9bc7a)  

![image](https://github.com/Azzadlyh/PRAKTIKUM-JARINGAN-KOMPUTER/assets/126213404/56e18278-6df3-48e5-8764-2a99e7cfd53f)  



