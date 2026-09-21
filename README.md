# 📅 Scheduly – Jadwal & Catatan Tim

**Scheduly** adalah aplikasi web berbasis *Progressive Web App* (PWA) yang dirancang khusus untuk memudahkan pengelolaan shift kerja tim (seperti pramuniaga dan kasir di Clandy's) maupun operasional umum secara komprehensif. Dilengkapi dengan manajemen folder multi-direktori, catatan bulanan, sorotan hari libur nasional otomatis, serta fitur ekspor laporan yang lengkap.

---

## ✨ Fitur Utama

- **Dual Lembar Kerja (Worksheet):**
  - **Jadwal Tim (Clandy's):** Pilihan shift khusus seperti `FULL`, `P`, `So`, `P(s)`, `Pc`, `PS`, `OFF`, dan `C` (Cuti).
  - **Jadwal Umum:** Shift operasional standar seperti `Pagi`, `Siang`, `Mid`, `Sore`, `Malam`, `Split`, `FULL`, `OFF`, dan `CUTI`.
- **Manajemen Folder & Penyimpanan Lokal:** Simpan sesi aktif ke dalam direktori utama (*Root*) atau buat folder kustom sendiri. Mendukung fitur salin, pindah, dan *Trash Bin* (pemulihan arsip hingga 30 hari).
- **Ekspor Laporan & Cetak PDF:** Unduh jadwal bulanan dengan mudah ke format **Excel (`.xlsx`)**, **Word (`.docx`)**, **CSV (`.csv`)**, atau cetak langsung / **PDF (`.pdf`)** dengan orientasi *landscape*.
- **Otomatisasi & Riwayat (Undo/Redo):** Setiap perubahan langsung tersimpan secara otomatis (*Auto-save*) ke *Local Storage* browser dengan fitur *Undo* dan *Redo* yang mulus.
- **Hari Libur Nasional Otomatis:** Deteksi otomatis hari libur nasional Indonesia dan akhir pekan pada kalender.
- **Multibahasa:** Tersedia dalam **Bahasa Indonesia** dan **English (Inggris)**.

---

## 🚀 Memulai (Cara Penggunaan)

Karena Scheduly dibangun menggunakan pendekatan *Single-File HTML* berbasis web murni dengan CDN eksternal (Tailwind CSS), Anda tidak memerlukan instalasi *Node.js* yang rumit untuk menjalankannya:

1. Unduh atau salin kode sumber (`index.html`) dari proyek ini.
2. Simpan file dengan nama `index.html`.
3. Buka file tersebut langsung menggunakan browser modern apa saja (Google Chrome, Mozilla Firefox, Microsoft Edge, dll).

---

## 🛠️ Teknologi yang Digunakan

- **HTML5 & CSS3** (Struktur dan Desain Antarmuka)
- **Tailwind CSS** (Kerangka kerja CSS via CDN)
- **Google Fonts** (Inter & Pacifico)
- **JavaScript (Vanilla ES6+)** (Logika aplikasi, manajemen lokal, dan ekspor dokumen)
- **Web App Manifest & Service Worker** (Dukungan PWA untuk instalasi aplikasi web)

---

## 📄 Lisensi

Distribusi di bawah lisensi [MIT License](LICENSE).
