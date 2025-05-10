# SC-SPAM-WA

**SC-SPAM-WA** adalah script PHP sederhana yang memungkinkan pengiriman spam pesan ke nomor WhatsApp secara otomatis. Script ini dibuat untuk **tujuan edukasi**, eksperimen, dan pembelajaran mengenai pengiriman request HTTP.

> ⚠️ **Peringatan:** Gunakan hanya untuk tujuan edukasi dan uji coba pada nomor WhatsApp yang Anda miliki. Penggunaan untuk spam atau aktivitas ilegal lainnya sangat dilarang.

---

## 🚀 Fitur Utama

- Kirim spam pesan WhatsApp secara otomatis
- Penggunaan yang mudah melalui terminal (CLI)
- Tidak memerlukan database atau dependensi lainnya
- Bisa dijalankan di berbagai platform (Windows, Linux, Termux)

---

## 📥 Instalasi dan Penggunaan

### 🪟 **Menjalankan di Windows**

1. **Install PHP**
   - Download dan install PHP dari [PHP Windows Downloads](https://windows.php.net/download/).
   - Ekstrak PHP ke dalam folder (misalnya `C:\php`).
   - Tambahkan folder `C:\php` ke dalam **PATH** environment variables pada sistem Windows Anda.

2. **Verifikasi Instalasi PHP**
   - Buka **CMD** atau **PowerShell**, lalu ketik perintah:
     ```bash
     php -v
     ```
   - Jika PHP terinstal dengan benar, versi PHP akan ditampilkan.

3. **Clone Repositori**
   - Buka CMD atau PowerShell dan jalankan perintah:
     ```bash
     git clone https://github.com/ZERO63-HECK/SC-SPAM-WA.git
     cd SC-SPAM-WA
     ```

4. **Jalankan Script**
   - Setelah berada di dalam folder `SC-SPAM-WA`, jalankan script dengan perintah:
     ```bash
     php spam.php
     ```

   - Ikuti instruksi untuk memasukkan nomor WhatsApp dan jumlah pesan yang ingin dikirim.

---

### 📱 **Menjalankan di Termux (Android)**

1. **Install PHP dan Git di Termux**
   - Buka aplikasi **Termux** di Android, lalu jalankan perintah berikut untuk menginstal PHP dan Git:
     ```bash
     pkg update && pkg upgrade
     pkg install php git -y
     ```

2. **Clone Repositori**
   - Setelah PHP dan Git terinstal, clone repositori dengan perintah:
     ```bash
     git clone https://github.com/ZERO63-HECK/SC-SPAM-WA.git
     cd SC-SPAM-WA
     ```

3. **Jalankan Script**
   - Setelah berada di dalam folder `SC-SPAM-WA`, jalankan perintah:
     ```bash
     php spam.php
     ```

   - Script akan meminta input nomor WhatsApp dan jumlah pesan yang ingin dikirimkan.

---

## ⚙️ **Struktur File**

| File          | Keterangan                                           |
|---------------|------------------------------------------------------|
| `spam.php`    | Script utama untuk mengirim spam pesan WhatsApp      |
| `pam.php`     | File pendukung yang diperlukan untuk beberapa fungsi|
| `version.txt` | Menyimpan informasi versi dari script               |

---

## 🛠 **Pengaturan dan Penggunaan**

1. **Jalankan Script**
   - Untuk menjalankan script, cukup ketik:
     ```bash
     php spam.php
     ```

2. **Input**
   - Script akan meminta input berupa:
     - **Nomor WhatsApp** yang ingin Anda spam (gunakan format `62xxxxxxxxxx`).
     - **Jumlah pesan** yang ingin Anda kirimkan.

---

## ⚠️ **Penting!**

- **Gunakan hanya untuk uji coba pada nomor milik sendiri.**
- **Tidak boleh digunakan untuk spam atau kegiatan ilegal lainnya.**
- **Jangan mengirimkan pesan tanpa izin kepada orang lain.**
- Jika mengalami error "Permission Denied" saat menjalankan script, coba berikan hak akses pada file:
  ```bash
  chmod +x spam.php
