# Pedoman Publikasi Aplikasi Android Secara Gratis

Dokumen ini berisi panduan lengkap untuk mempublikasikan dan mendistribusikan aplikasi Android Anda ke pengguna secara **100% gratis** tanpa harus membayar biaya pendaftaran developer Google Play Store (yang membutuhkan biaya satu kali sebesar \$25).

---

## 1. Persiapan File APK (Rilis)

Sebelum mendistribusikan aplikasi, Anda harus membuat file APK rilis yang optimal dan aman.

### Langkah Pembuatan APK di Google AI Studio:
1. Anda dapat mengunduh file APK langsung melalui menu **Settings / Ekspor** di platform Google AI Studio Build.
2. Pilih opsi **Generate APK** untuk mengkompilasi aplikasi dalam mode rilis (`release`).
3. Simpan file `.apk` tersebut di komputer Anda dan beri nama yang representatif (contoh: `Perbendaharaan_Rahasia_v1.0.apk`).

---

## 2. Pilihan Platform Publikasi Gratis Terbaik

Berikut adalah beberapa platform terbaik untuk meng-host dan membagikan aplikasi Android Anda secara gratis:

### Opsi A: GitHub Releases (Sangat Direkomendasikan)
GitHub adalah platform gratis terbaik untuk menyimpan kode dan membagikan aplikasi secara langsung kepada publik.

* **Kelebihan:** 100% gratis, tepercaya, aman, dan memiliki fitur pelacakan versi (versioning) yang sangat baik.
* **Cara Publikasi:**
  1. Buat akun di [GitHub](https://github.com/) jika belum punya.
  2. Buat repositori baru (pilih opsi **Public**).
  3. Unggah kode sumber aplikasi Anda atau biarkan kosong jika hanya ingin membagikan APK.
  4. Pergi ke tab **Releases** di sisi kanan halaman repositori Anda.
  5. Klik **Draft a new release**.
  6. Tentukan tag versi (contoh: `v1.0.0`) dan judul rilis.
  7. Seret dan lepas (drag-and-drop) file `.apk` Anda ke kotak aset rilis.
  8. Klik **Publish release**. Anda kini memiliki tautan langsung yang aman untuk dibagikan ke pengguna!

---

### Opsi B: Amazon Appstore
Amazon memiliki toko aplikasi sendiri yang sudah terpasang di jutaan perangkat Fire OS dan dapat diinstal di semua perangkat Android standar.

* **Kelebihan:** 100% gratis untuk mendaftar sebagai developer, jangkauan global, dan alternatif Play Store paling tepercaya.
* **Cara Publikasi:**
  1. Daftar akun developer gratis di [Amazon Developer Portal](https://developer.amazon.com/).
  2. Masuk ke Dashboard, lalu pilih **Add a New App** -> **Android**.
  3. Isi informasi metadata (Nama aplikasi, Deskripsi, Kategori).
  4. Unggah file `.apk` rilis Anda.
  5. Unggah aset visual seperti ikon aplikasi dan tangkapan layar (screenshot).
  6. Tentukan wilayah distribusi dan klik **Submit**. Aplikasi akan ditinjau oleh tim Amazon (biasanya 24-48 jam) sebelum aktif secara publik.

---

### Opsi C: Itch.io
Meskipun awalnya dikenal sebagai platform game indie, Itch.io kini menjadi tempat populer untuk mempublikasikan berbagai utilitas, aplikasi seni, dan proyek kreatif.

* **Kelebihan:** 100% gratis, proses peninjauan instan, dan memungkinkan pengguna memberikan donasi sukarela (sukarela membayar).
* **Cara Publikasi:**
  1. Buat akun di [Itch.io](https://itch.io/).
  2. Klik **Create new project** dari dashboard Anda.
  3. Isi judul aplikasi dan buat halaman deskripsi yang indah.
  4. Ubah klasifikasi proyek menjadi **Book** atau **Tool/App**.
  5. Pilih jenis harga: **No payment** atau **Download & Donate** (pengguna bisa mengunduh gratis atau mendonasikan uang jika mereka menyukainya).
  6. Unggah file `.apk` Anda.
  7. Klik **Save & View Page**, lalu ubah visibilitas menjadi **Public**.

---

### Opsi D: Google Drive / Dropbox / Telegram (Distribusi Langsung)
Jika Anda hanya ingin membagikan aplikasi kepada komunitas terbatas atau rekan kerja dengan cepat.

* **Cara Publikasi:**
  1. Unggah file `.apk` ke Google Drive atau Dropbox Anda.
  2. Ubah hak akses tautan menjadi **"Siapa saja yang memiliki tautan dapat melihat/mengunduh"**.
  3. Bagikan tautan tersebut melalui media sosial, WhatsApp, atau grup Telegram.
  4. Anda juga bisa langsung mengirimkan file `.apk` tersebut di dalam chat Telegram atau WhatsApp sehingga pengguna dapat langsung mengkliknya untuk menginstal.

---

## 3. Cara Menginstal APK di Handphone Pengguna

Karena aplikasi ini didistribusikan di luar Google Play Store, sistem Android akan mengidentifikasinya sebagai sumber tidak dikenal (Sideloading). Berikan petunjuk singkat ini kepada calon pengguna Anda:

1. **Unduh file APK** dari tautan rilis Anda.
2. Klik file APK yang telah diunduh untuk memulai instalasi.
3. Jika muncul peringatan keamanan *"Blocked by Play Protect"* atau *"Install unknown apps"*:
   * Klik **Settings / Setelan** pada pop-up tersebut.
   * Aktifkan opsi **"Allow from this source" / "Izinkan dari sumber ini"** untuk browser atau file manager yang Anda gunakan.
4. Kembali ke halaman instalasi, lalu klik **Install**.
5. Aplikasi siap dibuka dan digunakan dengan aman!

---

## 4. Tips Tambahan Agar Aplikasi Anda Tepercaya

Meskipun didistribusikan secara gratis dan mandiri, pastikan aplikasi Anda tetap terlihat profesional:
* **Sertakan Kebijakan Privasi (Privacy Policy):** Anda dapat menggunakan generator gratis seperti *TermsFeed* atau *App Privacy Policy Generator* dan menyimpannya di GitHub Pages.
* **Gunakan Nama Rilis yang Jelas:** Selalu sertakan nomor versi di nama file APK (contoh: `SufiSec_v1.0.3_Release.apk`) agar pengguna tahu jika ada pembaruan.
* **Keamanan Kode:** Semua APK yang dihasilkan melalui Google AI Studio telah dioptimalkan secara otomatis dan bebas dari malware, sehingga aman untuk didistribusikan langsung.
