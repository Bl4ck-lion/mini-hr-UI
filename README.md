# Mini HR System – Organisasi Mahasiswa

Proyek ini adalah prototipe **Mini HR System berbasis web** untuk mendukung manajemen organisasi mahasiswa.  
Sistem terdiri dari dua tampilan utama, yaitu **Dashboard Ketua/Admin** dan **Dashboard Anggota**.

---

## 📂 Struktur File
- `ketua.html` → Tampilan dashboard untuk Ketua/Admin organisasi.
- `anggota.html` → Tampilan dashboard untuk Anggota organisasi.

---

## ✨ Fitur Utama

### 1. Dashboard Ketua/Admin (`ketua.html`)
- **Dashboard Statistik**  
  Menampilkan total anggota, persentase kehadiran, jumlah tugas tertunda, dan jumlah SP aktif.
- **Manajemen Anggota**  
  Tambah, edit, hapus, dan kelola data anggota.
- **Jadwal Kegiatan**  
  Kalender organisasi dengan fitur tambah jadwal dan pengingat.
- **Manajemen Tugas**  
  Membuat, memantau, dan mengatur status tugas anggota.
- **Kehadiran**  
  Pencatatan absensi digital dengan status hadir, terlambat, atau tidak hadir.
- **Reward & Surat Peringatan (SP)**  
  Memberikan penghargaan atau SP kepada anggota sesuai kinerja/disiplin.
- **Automasi WhatsApp**  
  Integrasi Fonnte API untuk mengirim reminder otomatis (jadwal, tugas, reward, SP).
- **Laporan**  
  Menyediakan grafik kehadiran, rekap tugas, dan laporan anggota.
- **Pengaturan Sistem**  
  Konfigurasi organisasi, tahun akademik, notifikasi, hingga sistem SP otomatis.

---

### 2. Dashboard Anggota (`anggota.html`)
- **Dashboard Pribadi**  
  Menampilkan profil anggota, total poin, persentase kehadiran, dan jumlah tugas yang sudah diselesaikan.
- **Profil Saya**  
  Data pribadi, bio, status, serta pencapaian/sertifikat.
- **Jadwal Saya**  
  Kalender kegiatan khusus anggota.
- **Tugas Saya**  
  Daftar tugas yang diberikan, status penyelesaian, serta prioritas tugas.
- **Kehadiran Saya**  
  Rekap kehadiran anggota dalam kegiatan organisasi.
- **Reward & SP Saya**  
  Daftar reward dan SP yang diterima oleh anggota.
- **Pengaturan Akun**  
  Pengaturan notifikasi (email/WhatsApp) dan preferensi bahasa.

---

## 🛠️ Teknologi yang Digunakan
- **HTML5** & **CSS3**
- **Bootstrap 5** – framework UI responsif
- **Font Awesome** – ikon
- **Google Fonts (Poppins)** – tipografi modern
- **Chart.js** (direncanakan) – grafik laporan/statistik
- **Fonnte API (Opsional)** – integrasi WhatsApp

---

## 🚀 Cara Menjalankan
1. Download atau clone repository.
2. Buka file `ketua.html` atau `anggota.html` menggunakan browser modern (Chrome, Edge, Firefox).
3. Semua tampilan berbasis **frontend statis**, sehingga tidak memerlukan server backend.  
   Namun untuk integrasi API (WhatsApp, database anggota, dll) perlu implementasi tambahan.

---

## 📌 Catatan
- File ini masih berupa **prototipe statis (mockup)**, sehingga data ditampilkan secara dummy.
- Integrasi API (Fonnte, database, autentikasi) perlu dikembangkan lebih lanjut untuk membuat sistem berjalan penuh.
- Desain UI sudah responsif untuk desktop dan mobile.

---

## 👨‍💻 Pengembang
Proyek ini dikembangkan sebagai bagian dari mata kuliah **Manajemen Sumber Daya Manusia** Universitas Negeri Surabaya.  
Tim:  
- Rama Agung Supriyadi (25051214179)  
- Felix Agam (25051214172)  
- Muhammad Galang Insan S (25051214200)  
- Muhammad Fathur Rozaq (25051214203)  
- Fatta Daud Rahman (25051214192)  

---

