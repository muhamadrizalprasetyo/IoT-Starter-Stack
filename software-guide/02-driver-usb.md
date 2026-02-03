# 🔌 Driver USB (Koneksi Hardware)

Banyak pemula bingung karena alatnya tidak muncul di komputer. Biasanya, itu karena **Driver** belum terinstal. Driver adalah software yang memberitahu laptopmu: *"Hei, ada ESP32/Arduino yang dicolok!"*

### 1. Driver CH340
Paling sering digunakan oleh perangkat IoT versi ekonomis (Lolin, NodeMCU V3, Arduino Clone).
* **Ciri-ciri:** Chip di dekat port USB berbentuk kotak kecil datar.
* **[Link Download Driver CH340](https://sparks.gogo.co.nz/ch340.html)** (Cari tombol download untuk Windows).

### 2. Driver CP210x (Silicon Labs)
Biasanya digunakan oleh ESP32 atau NodeMCU versi yang lebih berkualitas (V2).
* **Ciri-ciri:** Chip di dekat port USB berbentuk kotak kecil dengan tulisan "SiLabs".
* **[Link Download Driver CP210x](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)** (Pilih bagian "Downloads" dan ambil VCP Windows).

### 💡 Tips Penting:
1. Setelah instal, **restart** laptop kamu.
2. Gunakan **kabel USB yang bisa transfer data**, jangan pakai kabel charger HP murahan karena biasanya hanya bisa mengisi daya tapi tidak bisa mengirim kode.
3. Untuk cek apakah sudah terinstal, buka *Device Manager* di Windows dan lihat di bagian **Ports (COM & LPT)**.

---
[⬅️ Kembali ke Utama](../README.md)
