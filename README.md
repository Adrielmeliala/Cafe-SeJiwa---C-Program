# 💻 Cafe Management System in C Language
Sistem manajemen cafe sederhana berbasis bahasa pemrograman C. Program ini menyediakan dua role utama, yaitu Admin dan Customer, dengan fitur interaktif berbasis menu di terminal. Data menu dan transaksi disimpan dalam file .txt untuk memastikan keberlangsungan data antar sesi.

## 🎯 Fitur Utama

### 🔐 Role Admin
- Login menggunakan akun khusus admin
- Menambahkan item baru ke daftar menu cafe
- Mengedit item menu yang sudah ada
- Data menu tersimpan di file menu.txt secara permanen

### 👥 Role Customer
- Login menggunakan akun customer
- Melihat daftar menu minuman/produk yang tersedia
- Melakukan pembelian produk
- Sistem secara otomatis menampilkan struk pembelian yang berisi rincian item yang dibeli, harga, dan total pembayaran

### 📂 Struktur File
- main.c — File utama berisi alur utama program
- menu.txt — File untuk menyimpan daftar menu cafe
- struk.txt (opsional) — Menyimpan salinan struk pembelian (jika diimplementasikan)

### 🛠 Teknologi
- Bahasa C standar (C89/C99)
- File I/O (read/write ke file .txt)
- Struktur data dasar (array, struct)

### 📌 Catatan
- Pastikan file menu.txt sudah ada di direktori program atau akan dibuat secara otomatis saat admin pertama kali menyimpan menu.
- Program dijalankan via terminal/command prompt.
