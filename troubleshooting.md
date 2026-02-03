# 🛠️ Solusi Error yang Sering Muncul (Troubleshooting)

Jangan panik! Kalau kamu nemu error pas lagi ngulik, coba cek solusi di bawah ini:

## ❌ 1. Error: "Failed to connect to ESP32: Timed out waiting for packet header"
* **Penyebab:** ESP32 gagal masuk ke mode *bootloader*.
* **Solusi:** Pas tulisan "Connecting..." muncul di layar, **tekan dan tahan tombol BOOT** di modul ESP32 kamu sampai proses *uploading* jalan.

## ❌ 2. Error: "Board at COMx not found"
* **Penyebab:** Kabel data rusak atau driver belum terinstal.
* **Solusi:** 1. Pastikan pakai kabel data (bukan kabel charger HP biasa).
    2. Install driver **CP210x** atau **CH340** (tergantung chip di ESP32 kamu).

## ❌ 3. Error: "WiFi.h: No such file or directory"
* **Penyebab:** Library belum terinstal atau salah pilih board.
* **Solusi:** Pastikan di Arduino IDE, kamu sudah pilih **Tools > Board > ESP32 Dev Module**.

## ❌ 4. Lampu Tidak Menyala (Padahal Kode Benar)
* **Penyebab:** Pemasangan kaki LED terbalik atau lupa pasang Resistor.
* **Solusi:** Kaki LED yang panjang adalah **Positif (+)**. Jangan lupa pakai resistor 220 ohm biar LED nggak putus.

---
💡 **Punya error lain?** Tulis di bagian [Issues](link-ke-tab-issues-kamu) ya, nanti kita bahas bareng!
