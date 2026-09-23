# 📅 Scheduly • Platform Penjadwalan & Catatan Tim

**Scheduly** adalah aplikasi web modern berbasis cloud yang dirancang khusus untuk memudahkan pengelolaan jadwal shift operasional konter, kasir, pramuniaga, hingga manajemen jadwal umum secara komprehensif, cepat, dan terstruktur.

---

## 🚀 Fitur Utama

* **🔐 Portal Konter & Akses Sesi Multi-Peran:**
  * **Admin:** Memiliki akses penuh untuk mengatur jadwal, menambah/menghapus staf, menyetujui/menolak *request* shift, serta mengelola penyimpanan folder.
  * **Anggota (Member):** Dapat masuk menggunakan PIN server konter untuk melihat jadwal dan mengajukan *request* perubahan shift secara mandiri.
* **☁️ Sinkronisasi Real-time Cloud (Firebase):** Terhubung langsung dengan Firebase Realtime Database agar perubahan data antar perangkat tersimpan secara otomatis dan sinkron seketika.
* **📂 Manajemen Folder & Penyimpanan Draft:**
  * Fitur direktori multi-folder (sub-folder) untuk mengarsipkan *draft* lembar kerja bulanan.
  * Dilengkapi fitur multi-pilih untuk memindahkan, menyalin, atau menghapus file draft dan folder dengan mudah.
* **🗓️ Deteksi Hari Libur & Kalender Otomatis:**
  * Deteksi otomatis hari libur nasional Masehi serta hari besar Islam (Hijriah) langsung pada header tabel kalender bulanan.
* **📋 Log Aktivitas & Request Jadwal:**
  * Pencatatan riwayat aksi otomatis serta sistem *Approval* (Terima/Tolak) bagi Admin untuk menyetujui pengajuan shift dari anggota tim.
* **↩️ / 🔄 Riwayat Perubahan (Undo & Redo):** Memungkinkan Anda melacak atau mengembalikan perubahan data pada lembar kerja secara fleksibel.
* **💡 Catatan Dinamis & Hari Penting:** Kotak catatan manual dengan tombol **"Selesai ✓"** yang muncul secara dinamis saat diketik dan otomatis tersimpan.
* **📤 Ekspor Laporan Bersih:** Mendukung ekspor lembar kerja dan catatan penting ke format **Excel (.xlsx)**, **Word (.docx)**, **PDF (.pdf)**, dan **CSV (.csv)** dengan filter dokumen bersih.
* **🎬 Panduan & Pusat Bantuan:** Dilengkapi dengan modal tutorial interaktif (*autoplay*) serta panduan manual lengkap.

---

## 🛠️ Teknologi yang Digunakan

* **Frontend:** HTML5, Tailwind CSS (Styling & Responsif)
* **Font:** Google Fonts (Inter & Pacifico)
* **Backend / Database:** Firebase SDK (Compat v9) Realtime Database
* **Penyimpanan Lokal:** LocalStorage (untuk preferensi bahasa, sesi, dan cache draft)

---

## ⚙️ Cara Menjalankan

1. Clone atau unduh repositori ini ke komputer Anda.
2. Buka file `index.html` menggunakan browser modern (Chrome, Edge, Firefox, Safari).
3. Konfigurasi kredensial Firebase Anda pada bagian objek `firebaseConfig` di dalam tag `<script>` jika ingin menggunakan database cloud sendiri.
