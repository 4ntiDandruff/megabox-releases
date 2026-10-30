# Megabox Desktop Workspace

<div align="center">

### Ruang Kerja Multi-Aplikasi Zero-Bloat untuk Linux & Windows
**Buka puluhan aplikasi chat & kerja (WhatsApp, Telegram, Discord, Gmail, ChatGPT, CCTV) dalam satu jendela tanpa bikin komputer lemot.**

[![Platform: Linux & Windows](https://img.shields.io/badge/Platform-Linux%20Wayland%20%26%20Windows-emerald.svg)](#)
[![RAM Frugal](https://img.shields.io/badge/RAM%20Saving-Up%20to%2082%25-purple.svg)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Status: Production Ready](https://img.shields.io/badge/Status-Stable-success.svg)](#)

[Website Resmi](https://megabox.megapass.web.id) • [Unduh Installer Langsung](#matriks-unduhan-biner-resmi-official-releases)

</div>

---

## Kenapa Megabox? (Alternatif Ringan Pengganti Rambox & Ferdium)

Jika Anda sering bekerja membuka banyak tab chat dan aplikasi toko di browser biasa (Chrome/Edge), RAM komputer cepat jebol bergiga-giga dan laptop jadi panas. Aplikasi seperti Rambox atau Ferdi sering kali membatasi tab atau meminta langganan berbayar.

**Megabox hadir sebagai solusi tuntas di meja kerja:**
* **Semua Akun di Satu Jendela**: Buka 3 WhatsApp (Pribadi, Toko, Kantor), Telegram, Gmail, dan ChatGPT berdampingan di sidebar yang rapi.
* **Partisi Terisolasi (Zero Cookie Leak)**: Tiap tab aplikasi berjalan di ruang terpisah. Anda bisa login banyak akun berbeda sekaligus tanpa perlu mode samaran (incognito).
* **Hemat RAM Hingga 82%**: Tab yang ditinggal nganggur otomatis "ditidurkan" untuk mengosongkan memori. Begitu diklik kembali, tab bangun seketika tanpa perlu login ulang.
* **Fitur Layar Terbelah (Dual-Pane Split Screen)**: Balas chat pelanggan di panel kiri sambil pantau dashboard atau spreadsheet di panel kanan (`Alt+S` dan `Alt+Z`).
* **100% Gratis & Mandiri (Local-First)**: Tidak ada biaya bulanan, tidak ada server pihak ketiga yang memata-matai, dan seluruh data tersimpan aman di komputer Anda sendiri.

---

## Matriks Unduhan Biner Resmi (Official Releases)

Silakan pilih paket installer resmi yang sesuai dengan sistem operasi komputer Anda:

| Sistem Operasi | Arsitektur | Format Paket | Tautan Unduhan Langsung | Ukuran | Status |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Windows 10 / 11** | x86-64 (64-bit) | Installer Resmi (NSIS Setup) | [Megabox-Setup-2.1.0.exe](https://github.com/4ntiDandruff/megabox-releases/releases/download/v2.1.0/Megabox-Setup-2.1.0.exe) | 118 MB | Production Ready |
| **Linux (Ubuntu / Mint / Debian)** | x86-64 (64-bit) | Native Package (.deb) | [Megabox-2.1.0-amd64.deb](https://github.com/4ntiDandruff/megabox-releases/releases/download/v2.1.0/Megabox-2.1.0-amd64.deb) | 99 MB | Production Ready |
| **Linux Universal (Semua Distro)** | x86-64 (64-bit) | Standalone Binary (Portabel) | [Megabox-2.1.0-x86_64.AppImage](https://github.com/4ntiDandruff/megabox-releases/releases/download/v2.1.0/Megabox-2.1.0-x86_64.AppImage) | 124 MB | Production Ready |

---

## Checksum Keamanan (SHA-256)
Untuk memastikan berkas installer Anda 100% murni dan aman:
```text
018f38fbcae7b0881754aac8b3326455fdbc77f3fe4f9456fbefa6b97b4fdcae  Megabox-Setup-2.1.0.exe
8f44052ef68cc7c50ecdc61b804674bed6c8fef64b7c0e3f39bece87ecb64dec  Megabox-2.1.0-amd64.deb
8feee3c2e42cb6b269e993857071cf553e3a6dc1c956b2e287e0713829f73457  Megabox-2.1.0-x86_64.AppImage
```

---

## Cara Pasang & Jalankan

### Di Windows:
1. Unduh berkas **`Megabox-Setup-2.1.0.exe`**.
2. Klik dua kali untuk memasang via wizard instalasi resmi.
3. Ikon Megabox akan muncul di Desktop dan Start Menu, siap dipakai.

### Di Linux (Ubuntu / Mint / Kubuntu):
```bash
sudo dpkg -i Megabox-2.1.0-amd64.deb
# Atau klik ganda berkas .deb via Software Manager
```

### Di Linux (Universal AppImage):
```bash
chmod +x Megabox-2.1.0-x86_64.AppImage
./Megabox-2.1.0-x86_64.AppImage
```

---

---

## Penafian Merek Dagang (Trademark Disclaimer)
Seluruh nama produk, logo, merek dagang, dan merek terdaftar yang ditampilkan di dalam aplikasi dan repositori ini (termasuk WhatsApp, Telegram, Discord, Google, Slack, ChatGPT, YouTube, dan lainnya) adalah hak milik dari pemiliknya masing-masing. Penggunaan seluruh nama perusahaan, produk, dan logo di dalam perangkat lunak ini murni ditujukan untuk tujuan identifikasi layanan yang kompatibel (*nominative fair use*). Penggunaan merek-merek tersebut tidak menyiratkan adanya afiliasi, sponsor, maupun dukungan resmi dari pemegang hak merek terkait.

---

## Lisensi & Atribusi Pihak Ketiga
Hak Cipta © 2026 Hizam Nahari (Megapass Intra Solusindo).  
Didistribusikan secara bebas dan terbuka di bawah [Lisensi MIT](LICENSE).

- **Electron Framework**: Copyright © Electron contributors / OpenJS Foundation (Lisensi MIT)
- **Chromium Project**: Copyright © The Chromium Authors (Lisensi BSD-style)
- **Lato Typography**: Copyright © 2010-2015 Lukasz Dziedzic (SIL Open Font License 1.1)
