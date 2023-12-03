# Jarkom-Modul-4-A14-2023

## Pembagian subnet
Berikut ini adalah pembagian subnet kami, nilai netmask sendiri dihitung dengan menggunakan rumus berikut $32-ceil(\log{_2}(jumlah IP + 2))$   

![pembagian subnet](images/pembagian-rute.png)

## VLSM
Pada VLSM, setiap subnet akan dialokasikan sejumlah ip tertentu untuk digunakan keseluruhan subnet. Berikut ini adalah cara kami dalam membagikan IP dengan metode VLSM  
![tree pembagian IP VLSM](images/VLSM.png)  
Sehingga pembagian IP yang ada adalah seperti berikut  
![pembagian IP VLSM](images/pembagian-ip-vlsm.png)  

## CIDR
Pada CIDR, subnet-subnet akan digabung gabungkan hingga akhirnya akan didapatkan 1 subnet besar yang mencakup seluruh topologi  
![Penggabungan subnet CIDR](images/penggabungan-1.png)  
![Penggabungan subnet CIDR](images/penggabungan-2.png)  
![Penggabungan subnet CIDR](images/penggabungan-3.png)  
![Penggabungan subnet CIDR](images/penggabungan-4.png)  
![Penggabungan subnet CIDR](images/penggabungan-5.png)  
![Penggabungan subnet CIDR](images/penggabungan-6.png)  
![Penggabungan subnet CIDR](images/penggabungan-7.png)  
![Penggabungan subnet CIDR](images/penggabungan-8.png)  
Dengan penggabungan-penggabungan tersebut, berikut ini adalah ilustrasi tree yang ada  
![tree pembagian IP CIDR](images/CIDR.png)  
Sehingga pembagian IP yang ada adalah seperti berikut  
![Pembagian IP CIDR](images/pembagian-ip-cidr.png)  
