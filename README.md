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

## Nomor 6
Agar dapat tetap dihubungi ketika DNS Server Yudhistira bermasalah, buat juga Werkudara sebagai DNS Slave untuk domain utama.
	Diperlukan allow-transfer dahulu

## Nomor 7
Seperti yang kita tahu karena banyak sekali informasi yang harus diterima, buatlah subdomain khusus untuk perang yaitu baratayuda.abimanyu.yyy.com dengan alias www.baratayuda.abimanyu.yyy.com yang didelegasikan dari Yudhistira ke Werkudara dengan IP menuju ke Abimanyu dalam folder Baratayuda.

## Nomor 8
Untuk informasi yang lebih spesifik mengenai Ranjapan Baratayuda, buatlah subdomain melalui Werkudara dengan akses rjp.baratayuda.abimanyu.yyy.com dengan alias www.rjp.baratayuda.abimanyu.yyy.com yang mengarah ke Abimanyu.

## Nomor 9
Arjuna merupakan suatu Load Balancer Nginx dengan tiga worker (yang juga menggunakan nginx sebagai webserver) yaitu Prabakusuma, Abimanyu, dan Wisanggeni. Lakukan deployment pada masing-masing worker.
No 9 sudah di rombak untuk nomer 10, perbedaannya dari no 10 diberikan port pada belakang contoh : nomer 9 = lynx 192.183.1.1 pada wisanggeni pada nomer 10 menjadi lynx 192.183.1.1:8003

## Nomor 10
Kemudian gunakan algoritma Round Robin untuk Load Balancer pada Arjuna. Gunakan server_name pada soal nomor 1. Untuk melakukan pengecekan akses alamat web tersebut kemudian pastikan worker yang digunakan untuk menangani permintaan akan berganti ganti secara acak. Untuk webserver di masing-masing worker wajib berjalan di port 8001-8003.

## Nomor 11
Selain menggunakan Nginx, lakukan konfigurasi Apache Web Server pada worker Abimanyu dengan web server www.abimanyu.yyy.com. Pertama dibutuhkan web server dengan DocumentRoot pada /var/www/abimanyu.yyy

## Nomor 12
Setelah itu ubahlah agar url www.abimanyu.yyy.com/index.php/home menjadi www.abimanyu.yyy.com/home.

## Nomor 13
Selain itu, pada subdomain www.parikesit.abimanyu.yyy.com, DocumentRoot disimpan pada /var/www/parikesit.abimanyu.yyy

## Nomor 14
Pada subdomain tersebut folder /public hanya dapat melakukan directory listing sedangkan pada folder /secret tidak dapat diakses (403 Forbidden).

## Nomor 15
Buatlah kustomisasi halaman error pada folder /error untuk mengganti error kode pada Apache. Error kode yang perlu diganti adalah 404 Not Found dan 403 Forbidden.

## Nomor 16
Buatlah suatu konfigurasi virtual host agar file asset www.parikesit.abimanyu.yyy.com/public/js menjadi 
www.parikesit.abimanyu.yyy.com/js

## Nomor 17
Agar aman, buatlah konfigurasi agar www.rjp.baratayuda.abimanyu.yyy.com hanya dapat diakses melalui port 14000 dan 14400.

## Nomor 18
Untuk mengaksesnya buatlah autentikasi username berupa “Wayang” dan password “baratayudayyy” dengan yyy merupakan kode kelompok. Letakkan DocumentRoot pada /var/www/rjp.baratayuda.abimanyu.yyy.

## Nomor 19
Buatlah agar setiap kali mengakses IP dari Abimanyu akan secara otomatis dialihkan ke www.abimanyu.yyy.com (alias)

## Nomor 20
Karena website www.parikesit.abimanyu.yyy.com semakin banyak pengunjung dan banyak gambar gambar random, maka ubahlah request gambar yang memiliki substring “abimanyu” akan diarahkan menuju abimanyu.png.
