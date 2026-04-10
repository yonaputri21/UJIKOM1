LANGKAH UJIKOM 1 JARINGAN TEKNOLOGI
1. Buka VirtualBox lalu jalankan ubuntu
2. Login dan masukan password
3. Ketik sudo nano /etc/asterisk/sip.conf
4. Lalu ganti extension menjadi 4 angka NIM (0015)
5. Ketik sudo nano /etc/astersik/extensions.conf
6. Scrool sampe bawah lalu dibagian exten sesuaikan dengan ekstensi tadi
7. Ketik sudo systemctl restart asterisk
8. Lalu ketik ip a untuk melihat ip
9. Ke Zoiper lalu masukan username dan password, lalu dibagian hostname isi dengan ip yang didapatkan ini merupakan bagian di device 1 dan lakukan hal yang sama di device 2
10. Lakukan panggilan dari device 1 ke device 2 dan jangan lupa untuk memberikan nama untk penerima
Hasilnya:
![alt text](<Hasil UJIKOM1.png>)