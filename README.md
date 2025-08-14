# LAB-15-DHCP-DNS-INTERNET
tanggal 14 agustus 2025
# konfigurasi DHCP dan DNS pada mikrotik

![m](pppp.png)

1. masuk ke mikrotik via winbox pilih  
   menu: IP > DHCP CLIENT  
   klik tanda +  
   Setting DHCP Client agar Mikrotik terhubung ke intrnet melalui ether1 yang terhubung ke ISP.  

![I](kull1.PNG)

2. buat ip static buat ether2 di  
   menu: IP > Address  
   klik +  
   seting address untuk interface ether2  

![I](kull2.PNG)

3. membagikan IP ke client secara otomatis.  
   menu: IP > DHCP server > DHCP setup  
   lalu klik next hingga selesai  
   
![I](kull3.PNG)

4. Setting DNS, masukan DNS google.  
   menu: IP > DNS  

![I](kull4.PNG)

5. Setting IP Firewall NAT agar client bisa mengakses ke internet.  
   menu: IP > Firewall > NAT  
   pilih menu sesui gambar di bawah   

![I](kull5.PNG)

6. Pindah ke PC Client untuk setting  obtain auto di IPv4.    

![I](kull8.PNG)

7. pengujian dengan cara cek detail di laptop client.
         
Laptop 1  

![I](kulpc1.PNG)

Laptop 2  

![I](fshuehsiuby-,.045.PNG)

# kesimpulan
Dengan DHCP Server, pembagian alamat IP, gateway, dan DNS ke perangkat klien dilakukan secara otomatis, sehingga meminimalkan kesalahan konfigurasi manual dan menghemat waktu.  


   
