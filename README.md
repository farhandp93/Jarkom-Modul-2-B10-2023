# Laporan Jarkom-Modul-2-B10-2023

Kelompok B10 :
Farhan Dwi Putra - 5025211093 
Yusuf Hasan Nazila - 5025211225 

Topologi :
![Screenshot (84)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/73d1433c-7985-433e-9056-cd6036d025e3)

## Nomor 1
Yudhistira akan digunakan sebagai DNS Master, Werkudara sebagai DNS Slave, Arjuna merupakan Load Balancer yang terdiri dari beberapa Web Server yaitu Prabakusuma, Abimanyu, dan Wisanggeni.
![Screenshot (93)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/b69e466d-ff33-4328-9f34-bf3ab3a47f68)
![Screenshot (94)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/5f2efcce-8a38-4b0e-a120-a4e4f307bf5e)

## Nomor 2
Buatlah website utama pada node arjuna dengan akses ke arjuna.yyy.com dengan alias www.arjuna.yyy.com dengan yyy merupakan kode kelompok.
![Screenshot (89)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/5b59d47e-ab39-493d-95a4-4d032bb3d4c8)
![Screenshot (90)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/e73d3f41-68f6-4a20-b0c0-c75bc5765261)
![Screenshot (85)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/0fd05ecd-949b-4bfc-be79-af18b4a64cae)

## Nomor 3
Dengan cara yang sama seperti soal nomor 2, buatlah website utama dengan akses ke abimanyu.yyy.com dan alias www.abimanyu.yyy.com.
![Screenshot (89)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/62b43182-a5b9-4120-8fb8-e31878e6bb45)
![Screenshot (91)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/068a2ab8-46ff-457b-8f4d-3a23a33a66a3)
![Screenshot (86)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/a6b62bb5-7841-4721-9d5c-ae84c2fa6c20)

## Nomor 4
Kemudian, karena terdapat beberapa web yang harus di-deploy, buatlah subdomain parikesit.abimanyu.yyy.com yang diatur DNS-nya di Yudhistira dan mengarah ke Abimanyu.
![Screenshot (91)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/474172ee-5cc5-4bb1-9d18-cb7792b57bec)
![Screenshot (87)](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/128909158/41ee0420-0c88-4524-a6b3-d30406f89aee)

## Nomor 5
Buat juga reverse domain untuk domain utama. (Abimanyu saja yang direverse)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/eb796c13-faf1-4c3e-a8cf-0fea4344804a)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/e009b640-cb83-45fc-a672-4636c5833d83)
Hasil :
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/ac4cd1ee-6aed-4651-958e-240d899c9897)



## Nomor 6
Agar dapat tetap dihubungi ketika DNS Server Yudhistira bermasalah, buat juga Werkudara sebagai DNS Slave untuk domain utama.
Diperlukan allow-transfer dahulu
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/6e57fbc0-b6c2-4bc6-8348-9508b16bcc94)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/d1af4292-1df6-4f7a-a231-adb8eaa810d0)



## Nomor 7
Seperti yang kita tahu karena banyak sekali informasi yang harus diterima, buatlah subdomain khusus untuk perang yaitu baratayuda.abimanyu.yyy.com dengan alias www.baratayuda.abimanyu.yyy.com yang didelegasikan dari Yudhistira ke Werkudara dengan IP menuju ke Abimanyu dalam folder Baratayuda.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/03c00ff3-26d5-476c-92bb-b60fdfb0865b)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/a0dbc924-5722-42f4-bf91-4648cc7b8aa9)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/8f70b51a-3c72-4512-af45-13a62ea78b95)



## Nomor 8
Untuk informasi yang lebih spesifik mengenai Ranjapan Baratayuda, buatlah subdomain melalui Werkudara dengan akses rjp.baratayuda.abimanyu.yyy.com dengan alias www.rjp.baratayuda.abimanyu.yyy.com yang mengarah ke Abimanyu.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f9878b6b-c411-452e-a486-300d3c053447)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/913c8616-75a6-4cce-bb98-e6536a3d121f)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/78bd68b1-83ad-479b-a21f-8d3e3c6b3de3)


## Nomor 9
Arjuna merupakan suatu Load Balancer Nginx dengan tiga worker (yang juga menggunakan nginx sebagai webserver) yaitu Prabakusuma, Abimanyu, dan Wisanggeni. Lakukan deployment pada masing-masing worker.
No 9 sudah di rombak untuk nomer 10, perbedaannya dari no 10 diberikan port pada belakang contoh : nomer 9 = lynx 192.183.1.1 pada wisanggeni pada nomer 10 menjadi lynx 192.183.1.1:8003
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/33dc2d3d-c71f-4c5a-974b-f053d5efe9aa)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/764af39a-2996-436c-9499-548052f45c42)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/1fa6ba60-9164-4cc2-81c6-a8166a7359dd)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/2dec6535-9ee7-440f-bde1-8bdae657b2e2)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/48f7aba5-0c60-42eb-87df-9f9cb32d2d28)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/54e956b6-2d3a-4d97-98b0-4b4a82321275)


## Nomor 10
Kemudian gunakan algoritma Round Robin untuk Load Balancer pada Arjuna. Gunakan server_name pada soal nomor 1. Untuk melakukan pengecekan akses alamat web tersebut kemudian pastikan worker yang digunakan untuk menangani permintaan akan berganti ganti secara acak. Untuk webserver di masing-masing worker wajib berjalan di port 8001-8003.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f2106094-2a7e-42d7-85bd-0d88ddef8281)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/82e539c0-b44d-4eb0-bbaf-8937fa01f3f1)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f5a5a1bb-44fc-41fc-b98a-54b101975310)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/e20480ff-a95e-42d5-b240-b4eeac062d98)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/d29b004e-559f-4723-b567-ce41af586bbd)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f2610374-2306-4736-9f54-b51efc1fec1b)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/9eddabab-a82f-4be6-b30e-099040fc4b19)


## Nomor 11
Selain menggunakan Nginx, lakukan konfigurasi Apache Web Server pada worker Abimanyu dengan web server www.abimanyu.yyy.com. Pertama dibutuhkan web server dengan DocumentRoot pada /var/www/abimanyu.yyy
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/a17b63ab-e2e6-409d-9f45-8e8ec3d10f33)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/885fe765-eb46-44cc-abdd-bffe2c2e0170)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f8fc757e-24aa-42cb-aec1-57805745d7b9)



## Nomor 12
Setelah itu ubahlah agar url www.abimanyu.yyy.com/index.php/home menjadi www.abimanyu.yyy.com/home.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/e8644ed9-86a5-4a4c-877f-08af6b56aefd)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/2732a9b5-f333-4c5d-8f6f-52175391995b)


## Nomor 13
Selain itu, pada subdomain www.parikesit.abimanyu.yyy.com, DocumentRoot disimpan pada /var/www/parikesit.abimanyu.yyy
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/b8dd411b-e869-4f18-87ad-feba4c992f72)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/12b299d3-274c-4b4e-8a33-1a89788cde95)

## Nomor 14
Pada subdomain tersebut folder /public hanya dapat melakukan directory listing sedangkan pada folder /secret tidak dapat diakses (403 Forbidden).
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/14dc573a-58fd-436e-a8b9-c4d5b2bc99b4)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/879e4cba-0351-44d4-acd9-f1afecd0acaf)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/73cbcab2-903a-49c2-bb68-7a625d8001fb)

## Nomor 15
Buatlah kustomisasi halaman error pada folder /error untuk mengganti error kode pada Apache. Error kode yang perlu diganti adalah 404 Not Found dan 403 Forbidden.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/1cec5d44-2693-4cef-afff-c791b0e003ba)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/f801fb7e-d7d1-4de6-b190-147ae8fe8d25)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/6242acbd-e988-480f-ba9a-2a685699ea98)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/ccf8e180-0bd6-42de-bd78-103f98dabdec)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/3a5f2c7e-3a12-4a07-a0b9-3eab8d348624)

## Nomor 16
Buatlah suatu konfigurasi virtual host agar file asset www.parikesit.abimanyu.yyy.com/public/js menjadi 
www.parikesit.abimanyu.yyy.com/js
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/b5497a57-6cb7-4be8-a22c-473e0909c18e)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/091e57dd-f1c8-4336-959b-9596c4b50752)

## Nomor 17
Agar aman, buatlah konfigurasi agar www.rjp.baratayuda.abimanyu.yyy.com hanya dapat diakses melalui port 14000 dan 14400.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/7d2160b5-6c17-4c80-8dc6-4ae1689135cf)
Port 14000
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/6bc6851e-04b9-4e51-8dd4-bc6ece28eb07)
Uji Coba Port 13000
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/2c5b239d-7108-43c4-8ea1-7972ff26a8be)

## Nomor 18
Untuk mengaksesnya buatlah autentikasi username berupa “Wayang” dan password “baratayudayyy” dengan yyy merupakan kode kelompok. Letakkan DocumentRoot pada /var/www/rjp.baratayuda.abimanyu.yyy.
 ![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/7f9f9b9f-6f70-47be-aab5-8e968a3bbf74)

Jika Password salah
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/b894e90a-b6c2-4462-8f4f-8e1a0f92bfbb)

Password : baratayudaB10 
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/fe954d2e-6b31-4247-b6bf-ee8ffed68136)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/7a79ee28-1393-441b-ab26-7cc921a6c9dd)

## Nomor 19
Buatlah agar setiap kali mengakses IP dari Abimanyu akan secara otomatis dialihkan ke www.abimanyu.yyy.com (alias)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/720e7b94-41e6-4eb6-8351-51475e0952bb)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/649a5219-0ee3-4d2c-b2fe-a80c402d766c)

## Nomor 20
Karena website www.parikesit.abimanyu.yyy.com semakin banyak pengunjung dan banyak gambar gambar random, maka ubahlah request gambar yang memiliki substring “abimanyu” akan diarahkan menuju abimanyu.png.
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/77f40d44-44ac-4fdb-878d-9babe75b4f71)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/5e73cc61-3472-48ca-9622-e3d6e7ee6925)
![image](https://github.com/farhandp93/Jarkom-Modul-2-B10-2023/assets/114125438/bf993a1a-3c12-4646-a810-3b01f468cf6f)
