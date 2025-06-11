<p align="center"><img src="https://imgur.com/cXtB87y.png" width="500"></p>

# 🩺 Sipograf - Sistem Informasi Posyandu dengan KMS

> Sipograf adalah aplikasi yang digunakan untuk pencatatan data balita dan visualisasi KMS (Kartu Menuju Sehat) dalam bentuk grafik pertumbuhan, guna mendukung pemantauan gizi secara efisien dan akurat di Posyandu.


## 🛠 Tools yang Digunakan

- **Python** untuk antarmuka pengguna
- **MySQL** sebagai basis data


## 📌 Cara Menggunakan Aplikasi

1. Clone repositori ini ke komputer kamu.

2. Buat database MySQL baru dengan nama sipograf_db.

3. Import file sipograf_db.sql yang tersedia di folder database/ ke dalam database tersebut melalui phpMyAdmin atau command line.

4. Edit konfigurasi koneksi database di file config.py sesuai dengan pengaturan MySQL kamu (host, user, password, dan nama database).

5. Install semua dependensi Python menggunakan perintah pip install -r requirements.txt.

6. Jalankan aplikasi dengan menjalankan file main.py.

7. Setelah aplikasi terbuka, login sebagai petugas dan mulai mengelola data balita, memasukkan data pengukuran, serta melihat grafik pertumbuhan KMS.


## 📂 Struktur Proyek 

- **`index.html`** – File utama untuk menjalankan aplikasi

- **`connection.php`** – Pengaturan koneksi database

- **`dbsipograf.sql`** – File SQL untuk membuat database dan tabel

- **`img/`** – Folder untuk gambar/icon

- **`css`** – Berisi file stylesheet untuk mengatur tampilan antarmuka aplikasi
  
-**`penimbangan`** – Berisi data atau logika aplikasi terkait proses penimbangan balita

## ⚙️ Fitur Utama
- Login petugas Posyandu

- Input, edit, dan hapus data balita

- Pencatatan data pengukuran balita (tinggi dan berat badan)

- Visualisasi grafik pertumbuhan berdasarkan KMS

- Cetak grafik atau laporan jika diperlukan


## 📃 Lisensi

Proyek ini dirilis di bawah [MIT License](https://opensource.org/licenses/MIT).  
Bebas digunakan untuk keperluan pribadi maupun komersial dengan atribusi yang sesuai.
