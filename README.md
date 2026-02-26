# sinik-pro
Validasi &amp; dekode NIK Indonesia secara real-time — 100% client-side, privacy-first, zero server
# 🔍 SINIK Pro — Sistem Informasi NIK Terpadu

<div align="center">

![SINIK Pro Banner](https://img.shields.io/badge/SINIK-Pro_v2.0-00c8f0?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAyQzYuNDggMiAyIDYuNDggMiAxMnM0LjQ4IDEwIDEwIDEwIDEwLTQuNDggMTAtMTBTMTcuNTIgMiAxMiAyem0tMiAxNWwtNS01IDEuNDEtMS40MUwxMCAxNC4xN2w3LjU5LTcuNTlMMTkgOGwtOSA5eiIvPjwvc3ZnPg==)
![HTML](https://img.shields.io/badge/HTML5-Pure-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Cyberpunk_UI-1572B6?style=for-the-badge&logo=css3)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-00f090?style=for-the-badge)

**Validasi & dekode NIK Indonesia secara real-time — 100% client-side, tanpa kirim data ke server.**

[🚀 Live Demo](https://marcoselvaoknam-wq.github.io/sinik-pro) · [📖 Dokumentasi](#cara-penggunaan) · [🐛 Laporkan Bug](../../issues)

</div>

---

## ✨ Fitur Unggulan

| Fitur | Deskripsi |
|-------|-----------|
| 🗺 **Dekode Wilayah** | Identifikasi Provinsi, Kabupaten/Kota, dan Kecamatan dari kode NIK |
| 👤 **Info Personal** | Tanggal lahir, jenis kelamin, dan usia otomatis |
| ♈ **Astrologi** | Zodiak Barat, Shio Tionghoa, dan profil Generasi |
| 🏢 **Data Kependudukan** | Instansi penerbit, zona waktu, dan panduan baca NIK |
| 🔬 **Raw Data** | Format hex, checksum, checklist validasi lengkap |
| ⚡ **Real-time** | Analisis instan saat mengetik, tanpa tombol submit |
| 🔒 **Privacy-First** | Semua proses di browser, data tidak dikirim ke mana pun |

---

## 🖥 Preview

```
╔══════════════════════════════════════════╗
║  SINIK Pro — Sistem Informasi NIK Terpadu ║
║  ▸ Input NIK 16 digit                    ║
║  ▸ Analisis instan & lengkap             ║
║  ▸ 5 tab informasi detail                ║
╚══════════════════════════════════════════╝
```

> UI bergaya **cyberpunk/terminal** dengan animasi scan beam, grid background, dan dark mode penuh.

---

## 🚀 Cara Penggunaan

### Option 1 — Buka Langsung (Tanpa Install)
```bash
# Download file HTML
# Buka di browser manapun — selesai!
```

### Option 2 — Clone Repository
```bash
git clone https://github.com/marcoselvaoknam-wq/sinik-pro.git
cd sinik-pro
# Buka index.html di browser
```

### Option 3 — GitHub Pages
Akses langsung di: `https://marcoselvaoknam-wq.github.io/sinik-pro`

---

## 📋 Cara Membaca NIK

NIK (Nomor Induk Kependudukan) terdiri dari **16 digit** dengan struktur:

```
XX  XX  XX  XXXXXX  XXXX
│   │   │   │       └── Nomor urut registrasi (0001–9999)
│   │   │   └────────── Tanggal-Bulan-Tahun lahir (wanita: tgl+40)
│   │   └────────────── Kode Kecamatan
│   └────────────────── Kode Kabupaten/Kota
└────────────────────── Kode Provinsi
```

> **Dasar hukum:** UU No. 23 Tahun 2006 tentang Administrasi Kependudukan, direvisi UU No. 24 Tahun 2013.

---

## 🛠 Teknologi

- **HTML5** — Struktur single-file, zero dependencies
- **CSS3** — Custom properties, animasi, grid layout responsif
- **Vanilla JavaScript** — Logika validasi & parsing NIK murni
- **IBM Plex Mono/Sans** — Font via Google Fonts
- **Database lokal** — Kode wilayah BPS terintegrasi

---

## 🔒 Privasi & Keamanan

> ⚠️ **Penting:** Aplikasi ini dibuat untuk tujuan **edukasi dan validasi format NIK** saja.

- ✅ Tidak ada data yang dikirim ke server
- ✅ Tidak ada tracking atau analytics
- ✅ Berjalan 100% offline setelah diload
- ✅ Open source & dapat diaudit siapa saja
- ❌ Bukan untuk mengakses database kependudukan resmi

---

## 📁 Struktur File

```
sinik-pro/
└── validasi-nik-pro.html   # Seluruh aplikasi dalam 1 file
```

---

## 🤝 Kontribusi

Pull request sangat disambut! Untuk perubahan besar, buka issue terlebih dahulu.

1. Fork repository ini
2. Buat branch fitur (`git checkout -b fitur/tambahan-baru`)
3. Commit perubahan (`git commit -m 'Tambah fitur baru'`)
4. Push ke branch (`git push origin fitur/tambahan-baru`)
5. Buka Pull Request

---

## 📄 Lisensi

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">

Made with ❤️ by **marcoselvaoknam-wq**

⭐ Jika project ini bermanfaat, beri bintang ya!

</div>
