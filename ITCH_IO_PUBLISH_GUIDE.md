# Panduan Publikasi Aplikasi "Perbendaharaan Rahasia" di Itch.io Secara Gratis

Itch.io adalah platform gratis yang luar biasa untuk mempublikasikan game, alat (tools), dan aplikasi kreatif. Dengan file `index.html` (Landing Page & Web Demo) dan file APK Android yang telah kita siapkan, Anda bisa mempublikasikan aplikasi ini dengan cara yang sangat interaktif dan profesional:

1. **Pengunjung bisa mencoba Simulasi Tasbih Digital dan membaca Hikmah Sufi langsung di browser laptop/HP mereka** melalui demo web `index.html`.
2. **Pengunjung bisa langsung mengunduh file APK Android rilis** melalui tombol unduh gratis yang disediakan di halaman yang sama.

---

## Langkah 1: Persiapkan Berkas (Files) Anda

Sebelum masuk ke Itch.io, siapkan 2 file ini di komputer Anda:
1. **File APK Rilis:**
   * Di Google AI Studio, klik **Settings (Ikon Gigi)** atau menu ekspor di sebelah kanan atas.
   * Pilih **Generate APK** (atau unduh APK hasil kompilasi).
   * Simpan file `.apk` tersebut di komputer Anda (contoh nama: `Perbendaharaan_Rahasia.apk`).
2. **File ZIP Landing Page:**
   * Ambil file `index.html` yang telah kita buat di root direktori ini.
   * Kompres file `index.html` tersebut menjadi sebuah file `.zip` (misalnya diberi nama `index.zip` atau `web_demo.zip`). 
   * *Catatan: Pastikan file `index.html` berada langsung di tingkat teratas di dalam file ZIP tersebut (tidak terbungkus folder lain).*

---

## Langkah 2: Buat Akun & Proyek Baru di Itch.io

1. Kunjungi [Itch.io](https://itch.io/) dan buat akun secara gratis (jika belum punya).
2. Setelah masuk, klik tombol **"Dashboard"** di kanan atas.
3. Klik tombol **"Create New Project"**.

---

## Langkah 3: Konfigurasi Halaman Proyek (Project Settings)

Isi formulir pembuatan proyek dengan pengaturan berikut agar web demo dan APK Android berjalan bersamaan dengan sempurna:

### 1. Informasi Dasar (Basic Info)
* **Title (Judul):** `Perbendaharaan Rahasia - Bimbingan Batin & Hikmah Sufi`
* **Project URL:** Itch.io akan membuatkan url otomatis secara gratis (contoh: `https://username.itch.io/perbendaharaan-rahasia`).
* **Short Description:** `Aplikasi bimbingan batin, rahasia nafas, asmaul husna, huruf hijaiyah, dan Tasbih Digital Hening.`
* **Classification:** Pilih **Games** atau **Tools**.
* **Kind of project (SANGAT PENTING):** Pilih **HTML** (You have a ZIP or HTML file that will be played in the browser). Ini akan mengaktifkan landing page interaktif kita agar bisa dijalankan langsung oleh pengunjung!

### 2. Harga (Pricing)
* **Pricing:** Pilih **No payment** (jika ingin 100% gratis) atau **Download & donate** (agar gratis, namun pengguna yang menyukainya bisa memberikan donasi sukarela seikhlasnya).

### 3. Unggah Berkas (Upload Files)
Di bagian ini, unggah kedua berkas yang telah Anda siapkan di Langkah 1:

1. **Unggah file `index.zip` (Web Demo):**
   * Klik **Upload Files**, pilih file `index.zip`.
   * Setelah selesai terunggah, beri centang pada kotak **"This file will be played in the browser"**.
2. **Unggah file `Perbendaharaan_Rahasia.apk` (Aplikasi Android):**
   * Klik **Upload Files**, pilih file `Perbendaharaan_Rahasia.apk`.
   * Beri nama tampilan yang jelas (contoh: `Unduh Aplikasi Android (.APK)`).
   * Centang kotak berlogo **Android** agar sistem mendeteksinya sebagai file APK Android.

### 4. Pengaturan Tampilan Demo (Embed Info)
Karena kita memilih jenis proyek HTML, atur dimensi canvas agar landing page kita terlihat luas dan responsif:
* **Viewport Dimensions:** Atur **Width** ke `100%` atau `1000px` dan **Height** ke `700px` atau `750px`.
* **Mobile Friendly:** Beri centang pada opsi **"Mobile friendly"** (agar bisa dimainkan dengan baik lewat browser HP).
* **Auto-start:** Centang **"Automatically start on page load"** agar simulasi Tasbih dan wejangan hikmah langsung aktif saat halaman dibuka.
* **Scrollbars:** Centang **"Enable scrollbars"** (agar pengunjung bisa menggulir halaman ke bawah untuk membaca panduan instalasi APK).

### 5. Detail Deskripsi (Description)
Tulis deskripsi singkat yang menarik mengenai aplikasi Anda di bagian kotak teks editor. Contoh:
> **Perbendaharaan Rahasia** adalah aplikasi bimbingan rohani Islam esoteris (Tasawuf) yang memuat khazanah hikmah Wali Songo, rahasia Nafas, keutamaan Asmaul Husna, dan dilengkapi fitur Tasbih Digital Hening yang interaktif.
> 
> *Silakan coba simulator Tasbih Digital dan baca Hikmah Sufi langsung di atas pada halaman web ini! Jika Anda ingin membawanya di saku Anda, unduh file APK Android gratis di bagian unduhan di bawah ini untuk dipasang di HP Anda.*

---

## Langkah 4: Kustomisasi Visual Halaman (Theme)

Setelah menyimpan draf proyek Anda, klik tombol **"Theme"** atau **"Customize Page"** di bagian atas halaman untuk menyesuaikan tampilan latar belakang agar serasi dengan suasana mistis, tenang, dan spiritual:
* **Background Color:** Ubah ke warna gelap gulita/biru malam seperti `#070b13` atau `#0b0f19`.
* **Text Color:** Ubah ke warna putih keabu-abuan atau emas muda seperti `#f4f6fa` atau `#dfb743`.
* **Link Color:** Ubah ke warna emas berkilau seperti `#dfb743`.
* **Header / Banner:** Anda bisa mengunggah gambar latar belakang bertema spiritual untuk bagian atas halaman jika diinginkan.

---

## Langkah 5: Publikasikan! (Publish)

1. Klik tombol **Save** di bagian paling bawah halaman pengaturan.
2. Di bagian atas halaman, klik tautan pratinjau proyek Anda untuk memastikannya berjalan dengan baik.
3. Jika semuanya sudah sesuai dan Anda siap meluncurkannya ke publik, kembali ke halaman edit, gulir ke bawah ke bagian **Visibility**, lalu ubah status dari **Draft** menjadi **Public**.
4. Klik **Save** sekali lagi! Tautan proyek Itch.io Anda kini sudah aktif dan siap dibagikan ke teman, keluarga, jamaah, atau komunitas Anda secara gratis!
