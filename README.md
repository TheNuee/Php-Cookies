# Php-Cookies
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(34).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(35).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(36).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(37).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(38).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(39).png)
![alt text](https://github.com/TheNuee/Php-Cookies/blob/master/Screenshot%20(40).png)
1).Cookies:
1. Cookies dapat disimpan di sisi user
2. Cookies tidak aman bagi klien karena cookies dapat disisipi program yang tidak diketahi user
Karena cookies tidak aman maka browser user dapat di-set untuk menghapus cookies dan bahkan men-disable fungsi cookies. Menurut sumber lain cookies juga tidak aman bagi sisi server karena cookies dapat di-edit oleh user.
3. Data yang disimpan ke dalam metode cookies dapat bertahan lebih lama dan dapat diatur waktu expired-nya
Session:
1. Dapat disimpan disisi server
2. Lebih aman karena tidak ada file yang dimasukan ke sisi user
3. Setelah web browser user dimatikan maka data yang disimpan metode session akan hilang dan waktu expired juga tidak dapat diatur.

2)1. Pilih tools menu pada bagian atas browser mozilla, Click “Tools” -> “Options”
2. Pilih “Privacy” pada menu.
3. Pada bagian Firefox will pilih “Use custom settings for history”
4. Pilih “Show Cookies”
5. Pilih Cookies yang terdapat pada list yang muncul kemudian klik “Remove Cookies” untuk menghapus cookies pada list satu persatu namun untuk dapat menghapus semua cookies yang terdaftar anda dapat memilih “Remove All Cookies”
6. Pilih “OK atau Close”

CARA CEPAT = Tekan (Ctrl + Shift + Del)
[INI UNTUK MOZILLA]

3)1. $_SESSION[‘nama_variabel’] = ” ” untuk memberikan atau mengganti nilai dari variabel session menjadi null atau kosong.
2. unset ($_SESSION[‘nama_variabel’]) untuk menghapus sebuah variabel session.

<?php
// Untuk menghapus session tertentu
unset($_SESSION['Try']);

3.  session_destroy() untuk menghapus semua variabel session yang mungkin ada banyak variabel session yang dibuat. Fungsi session destroy tidak memerlukan argumen dalam penggunaanya.

// Untuk menghapus semua session
session_destroy;
?>
