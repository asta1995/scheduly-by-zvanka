# Scheduly – Jadwal & Catatan Tim Clandy's & Umum

**Scheduly** adalah aplikasi berbasis Progressive Web App (PWA) yang dirancang khusus untuk memudahkan pengelolaan shift operasional, rekap kehadiran, catatan penting, serta penanggalan Hijriah & Hari Libur Nasional. Aplikasi ini menyediakan dua lembar kerja utama: **Jadwal Tim Clandy's** (dengan fitur login berbasis konter & PIN server) dan **Jadwal Umum**.

---

## ✨ Fitur Utama

### 🛒 1. Portal Konter & Autentikasi Tim Clandy's *(Eksklusif)*
* **Pilihan Konter Spesifik:** Mendukung pemisahan data berdasarkan unit konter (KASIR, Konter Susu, Konter Baby, Konter Market).
* **Keamanan Berbasis PIN Server:** Setiap konter diamankan menggunakan PIN unik (misal: `sususu`), memastikan hanya anggota dalam satu tim/server yang dapat saling sinkronisasi.
* **Hak Akses Admin & Anggota:**
  * **👑 Admin:** Memiliki akses penuh untuk mengelola shift, menghapus baris staf, dan menambahkan nama staf baru ke dalam proyek konter.
  * **👤 Anggota Tim:** Digunakan untuk melihat jadwal dan mengirimkan *request* perubahan shift secara instan kepada Admin.
* **Pendaftaran Staf Otomatis:** Nama akun yang digunakan saat login pertama kali akan langsung terdaftar ke dalam tabel staf di server konter tersebut.

### 📅 2. Manajemen Lembar Kerja & Shift Fleksibel
* **Dua Mode Lembar Kerja:** Beralih dengan mudah antara Jadwal Tim Clandy's (dengan tema khas *pinky*) dan Jadwal Umum.
* **Indikator Shift Lengkap:** Mendukung berbagai format shift (FULL, P, So, P(s), Pc, PS, OFF, C) dengan rekapitulasi jam kerja otomatis di ujung tabel.
* **Undo & Redo Riwayat:** Memungkinkan pembatalan atau pengulangan tindakan penyuntingan secara instan.

### 💾 3. Penyimpanan Multi-Folder & Ekspor
* **Penyimpanan Draft Lokal:** Simpan sesi lembar kerja aktif ke dalam direktori utama atau buat folder kustom sendiri.
* **Ekspor Laporan:** Unduh rekap bulanan dalam berbagai format file pilihan (Excel, Word, CSV, PDF).

### 🌙 4. Penanggalan Ganda & Hari Besar
* Konversi otomatis penanggalan Hijriah.
* Informasi hari libur nasional dan hari besar Islam yang diperbarui secara dinamis sesuai bulan yang aktif.

---

## 🚀 Cara Menjalankan
1. Clone atau unduh repositori ini.
2. Buka file `index.html` menggunakan browser modern apa pun (Chrome, Firefox, Edge, Safari).
3. Pilih menu **Jadwal & Catatan Tim Clandy's**, lalu masukkan data login, konter, dan PIN server Anda untuk mulai bekerja.
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
