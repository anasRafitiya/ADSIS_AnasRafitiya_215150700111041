# ADSIS_AnasRafitiya_215150700111041

### 1.	Buat direktori dengan nama UAP-Adsis, isi dengan file txt dengan format penamaan catatannya-<nama kamu>.txt, kemudian isi file txt tersebut dengan nama dan NIM kamu. Kemudian atur permission view-only pada file tersebut untuk user biasa. Tunjukkan bukti berupa screenshot yang menunjukkan bahwa file tersebut berhasil diatur permissionnya menjadi view-only untuk user biasa.
  
  -	Membuat direktori baru dengan nama UAP-Adsis
  ![gambar1](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/1139ae1f-dba3-49db-9941-ed753344fd88)
  
  -	Membuat file txt di dalam direktori UAP-Adsis
  ![gambar2](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/25ff4068-f00d-4914-8465-443828ea6342)

  -	Mengisi file txt “catatannya-Anas” dengan nama dan NIM
  ![gambar3](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/868bee99-5297-43f1-9d6c-a2d3edefdb5b)
  ![gambar4](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/1979c261-677d-4b29-bdf2-7e732adffc39)

  -	Mengatur permission view-only pada file txt “catatannya-Anas” untuk user biasa
  ![gambar5](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/6d9a8bf2-1a04-40e9-831c-4571388cb3bb)
  
  ![gambar6](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/1f0a871e-caed-45a1-bcf5-eb2b1ac33d41)
  > File catatannya-AnasR.txt tidak dapat diubah isinya
  
  ### 2.	Lakukan konfigurasi alamat IP address sementara pada sistem dan default gateway, (petunjuk 192.168.56.x | x adalah nomor absen)
  
  -	Konfigurasi alamat IP address sementara
  ![gambar7](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/544f6199-3fc1-4bee-aa72-8bce7a6d6d8f)
 
  -	Konfigurasi default gateway
  ![gambar8](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/6efc021f-a448-405b-b9e5-ebadd8872814)

### 3.	Lakukan instalasi Webmin lalu buatlah user bernama nama anda, lalu buat group Adsis_(kelas masing-masing) dan masukkan nama anda di group
  
  - Bukti instalasi webmin
  ![gambar9](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/c1d922af-21e8-49aa-99e7-9036bd386b4c)

  -	Membuat user bernama “anasRafitiya”
  ![gambar10](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/bba14606-0bc8-43a9-9f23-df6a5e03b029)
  > Klik "create a new user"
  

  ![gambar11](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/1f31ffdd-e88c-4ed8-ae62-db12f3ebe6d1)
  > Tampilan dari halaman "create new user"
  

  ![gambar12](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/ab3389be-5323-4d70-9d49-91b4df634616)
  > User baru telah dibuat, terlihat pada baris terakhir daftar user
  

  -	Membuat group Adsis_E dan memasukkan nama ke group
  ![gambar13](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/04d10ba9-129e-473e-8050-5f519302ecaf)
  > Klik "create a new grup"
  

  ![gambar14](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/2b972eb4-a594-4395-9c78-3eab34e63611)
  > Tampilan dari halaman "create a new grup"
  

  ![gambar15](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/ec329eca-ade8-41cd-a472-86e7f22d3b32)
  > Grup baru telah dibuat, terlihat pada baris terakhir daftar grup
  
  
### 4. Lakukan ping ke alamat ip anda dan coba lakukan reject dan drop di webmin, lalu analisa apa yang terjadi?
  
  - Menambahkan rule drop untuk incoming paket di menu linux firewall
  ![gambar18](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/0604325e-2d6b-40f0-963b-658b47d27a08)

  - Menambahkan rule reject untuk incoming paket di menu linux firewall
  ![gambar19](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/989f8b70-bc7d-429a-90d0-dfc43e8ca6b5)
  
  - Pilih semua rule yang ditambahkan tadi
  ![gambar20](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/f6ea5683-9f2d-4257-a293-edb6fe0e6cc3)
  
  - Klik apply configuration
  ![gambar21](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/ab8f7584-f6cb-4185-84f2-1bc3df2c8bbf)
  
  ![gambar22](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/aba463fe-7d87-4f84-9df7-16b9f5f210e0)
  >Peringatan setelah klik apply configuration
  
  
  - Hasil ping
  ![gambar23](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/5f8c6f95-f0af-496f-8691-82b154a21839)
  
  - Analisa apa yang terjadi
  - Setelah melihat hasil dari menjalankan langkah-langkah di atas, dapat diamati bahwa dengan menambahkan aturan berupa reject dan drop ke dalam incoming packets (INPUT) di firewall, ini berpengaruh terhadap paket yang dikirimkan ke alamat tujuan. Paket yang dikenakan aturan drop seharusnya akan ditolak begitu saja oleh firewall. Sedangkan paket yang dikenakan aturan reject dia akan dikembalikan kepada pengirim berupa pesan bahwa paket ditolak.
  
### 5. Buatlah perintah otomatis yang berfungsi untuk ping www.filkom.ub.ac.id
  
  - menambahkan perintah di crontab agar setiap 2 menit user akan melakukan ping ke www.ub.ac.id
  ![gambar16](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/40343b54-7bcd-4243-ba4e-9b280d350be2)

  - Hasil ping dari perintah di crontab
  ![gambar17](https://github.com/anasRafitiya/ADSIS_AnasRafitiya_215150700111041/assets/125624764/6e445eca-bd86-4cf8-84ed-08bbba27afe9)
  
  
