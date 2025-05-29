<p align="center"><img src="https://imgur.com/HTnIUB4.png" width="350"></p>

# 🩺 Sipograf - Sistem Informasi Posyandu dengan KMS

> Sipograf adalah aplikasi yang digunakan untuk pencatatan data balita dan visualisasi KMS (Kartu Menuju Sehat) dalam bentuk grafik pertumbuhan, guna mendukung pemantauan gizi secara efisien dan akurat di Posyandu.

## 🛠 Teknologi yang Digunakan

- Python + Kivy untuk antarmuka pengguna
- MySQL sebagai basis data


## 📌 Cara Menggunakan Aplikasi

1. Clone repositori ini ke komputer kamu.

2. Buat database MySQL baru dengan nama sipograf_db.

3. Import file sipograf_db.sql yang tersedia di folder database/ ke dalam database tersebut melalui phpMyAdmin atau command line.

4. Edit konfigurasi koneksi database di file config.py sesuai dengan pengaturan MySQL kamu (host, user, password, dan nama database).

5. Install semua dependensi Python menggunakan perintah pip install -r requirements.txt.

6. Jalankan aplikasi dengan menjalankan file main.py.

7. Setelah aplikasi terbuka, login sebagai petugas dan mulai mengelola data balita, memasukkan data pengukuran, serta melihat grafik pertumbuhan KMS.

## 📂 Struktur Proyek 

- main.py – File utama untuk menjalankan aplikasi

- config.py – Pengaturan koneksi database

- database/sipograf_db.sql – File SQL untuk membuat database dan tabel

- screens/ – Folder untuk tampilan dan logika per layar

- assets/ – Folder untuk gambar/icon

- requirements.txt – Daftar dependensi Python

## ⚙️ Fitur Utama
- Login petugas Posyandu

- Input, edit, dan hapus data balita

- Pencatatan data pengukuran balita (tinggi dan berat badan)

- Visualisasi grafik pertumbuhan berdasarkan KMS

- Cetak grafik atau laporan jika diperlukan

## 📃 Lisensi

Proyek ini dirilis di bawah [MIT License](https://opensource.org/licenses/MIT).  
Bebas digunakan untuk keperluan pribadi maupun komersial dengan atribusi yang sesuai.
