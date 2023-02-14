# UIPath-Sertifikat-otomatis
Sertifikasi otomatis dengan UIPath Studio adalah sebuah teknologi yang menerapkan RPA (Robotic Procession Automation), dimana kita dapat melakukan kegiatan yang berulang-ulang yang akan dilakukan secara otomatis dengan robot. Yaitu tadi dalam aplikasi ini akan mebuatkan secara otomatis sertifikat dan mengirimkan sertifikatnya ke email masing-masing pendaftar secara otomatis. Untuk dapat menggunakan aplikasi ini ada beberapa tools yang harus di siapkan diantaranya :
1.	Akun Orchestrator, kalian bisa daftar dan mendapatkan Trial akses aplikasi.
2.	Intsal UIPath Studio community, bisa kalian unduh jika sudah mendaftar akun [*Orchestrator*](https://www.uipath.com/product/orchestrator).
3.	Format sertifikat yang dibuat. 3
4.	Google chrome yang sudah sync dengan email dan menginstall extension UIPath web Automation.
5.	Links google forms untuk mengambil data pendaftar jika melakukan pendaftaran melalui Google forms (opsional).
6.	File .csv format sebagai daftar nama yang akan dibuatkan sertifikat.
## Panduan penggunaan Aplikasi :
1.	Buat local repository di computer dengan melakukan git clone https://github.com/Angga-Nugraha/UIPath-Sertifikat-otomatis.git
2.	Simpan format file sertifikat dengan format .docs yang akan di buat pada folder sertifikat pada repository kalian.
3.	Untuk format sertifikatnya dan di dalam file yang akan di isi dengan nama, berikan textbox dengan isian “{nama}”. Contoh :

![image](https://user-images.githubusercontent.com/76716099/218665468-cf1da4a8-ceb5-454e-9133-7a5ed33c0395.png)

4.	Simpan file format .csv pada folder request yang berisi daftar nama peserta dengan format kolom file .csv sebagai berikut : 

![image](https://user-images.githubusercontent.com/76716099/218665519-573844a6-dd06-4613-a581-1adc6d7a4f3d.png)

5.	Setelah semua tahap di atas selesai, program siap di jalankan, dengan mengklik “run file” pada menu toolbars di UIPath Studio.

![image](https://user-images.githubusercontent.com/76716099/218665606-d3823937-b0d3-4508-8482-3bfa8db38b34.png)

6.	Setelah program di run, program akan meminta anda untuk menekan shortcut keyboard “Alt + enter” untuk memulai trigger automation-nya.

![image](https://user-images.githubusercontent.com/76716099/218665677-dfaf164e-b05e-4fda-8999-989d2877b9bf.png)

8.	Tunggu sampai program menjalankan tugasnya. Dan jika sudah selesai program akan memberikan message box dengan pesan “Semua sertifikat telah dikirim ke masing-masing email peserta”.
