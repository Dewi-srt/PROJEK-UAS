# PROYEK (API-SEDERHANA)
Create(GET)
Read(POST)
Update(PUT)
Delete(DEL)

## Teknologi
* PHP 8.1
* Server Apache (via XAMPP)
* MySQL / MariaDB

## Instalasi
1.  Clone repository ini: `git clone https://...`
2.  Letakkan folder proyek di dalam `www` pada direktori Laragon Anda.
3.  Buat database baru di phpMyAdmin dengan nama `db_chataibackend2`.
4.  Import file `database.sql` (jika ada) ke dalam database tersebut.
5.  Sesuaikan koneksi database di dalam file `config.php`.
6.  Jalankan server Apache dan MySQL melalui laragon Control Panel.
7.  API siap diakses melalui `http://localhost/apisederhana/`.

## Daftar Endpoint

### 1. Lihat Semua Pengguna
* **Method:** `GET`
* **Endpoint:** `/users`
  ![Screenshot 2025-06-09 100631](https://github.com/user-attachments/assets/4c52701d-25fd-4c78-9932-e27309eb8481)

### 2. Tambah Pengguna Baru
* **Method:** `POST`
* **Endpoint:** `/users`
  ![Screenshot 2025-06-09 101247](https://github.com/user-attachments/assets/927986ed-046b-41ff-b45a-178293c91eec)

  Tampilan user baru yang sudah ditambahkan
  ![Screenshot 2025-06-09 101352](https://github.com/user-attachments/assets/dc9069dd-e76b-4441-b6e7-f6f8e2314a40)

### 3. Edit Data Pengguna
* **Method:** `PUT`
* **Endpoint:** `/users`
![Screenshot 2025-06-09 101745](https://github.com/user-attachments/assets/6755f925-42e8-4726-9de2-0a1ad3cd6f7d)
![Screenshot 2025-06-09 101827](https://github.com/user-attachments/assets/3c4762d3-7fe0-49bb-859d-cc4ed9f03709)

### 4. Hapus Data Pengguna
* **Method:** `DELETE`
* **Endpoint:** `/users`
  ![Screenshot 2025-06-09 101949](https://github.com/user-attachments/assets/07fda924-86d5-42fb-bcb6-a513933f4680)
  ![Screenshot 2025-06-09 102017](https://github.com/user-attachments/assets/b26b1db3-8d2f-4780-bad5-50217b8ea5b1)





  

  


