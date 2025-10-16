# 📜 Changelog / Catatan Rilis

Lihat riwayat pembaruan dan penambahan fitur pada aplikasi di bawah ini.

---

## 🚀 Rilis Publik

<details open>
  <summary><strong>Cek Detail</strong></summary>

### **Versi 2.10.10** ✨ _(Terbaru)_

<details>
  <summary>Lihat Detail Versi</summary>

#### Fitur Baru
- **Modul Kidung Nyanyian:** Fitur lengkap untuk akses kidung digital, unduhan offline, navigasi keypad, pencarian lirik, zoom gesture, dan bagikan gambar lirik
- **Sistem Notifikasi:** Penjadwalan otomatis, in-app messaging, histori lengkap (akses admin)
- **Stiker & Pengumuman:** Teks berjalan multi-item dengan pengaturan warna dan kecepatan
- **Mode Offline-First:** Cache pintar dengan sinkronisasi otomatis di latar belakang
- **Postingan:** Penambahan beberapa kategori Postingan

#### Perbaikan & Peningkatan
- Perbaikan carousel artikel unggulan, filter kategori, dan sistem cache offline
- Optimisasi performa dan startup aplikasi
- Perbaikan stabilitas (crash PDF, koneksi internet, splash screen)
- Peningkatan antarmuka pengguna dengan desain modern
- Perbaikan warta & PDF dengan prefetch otomatis
- Peningkatan sistem tim dan notifikasi

#### Keamanan & Kompatibilitas
- Firebase App Check untuk proteksi API
- Kompatibilitas penuh Android 15 (API Level 35)
- Migrasi ke Play Integrity API

#### Bug Yang Diketahui
- Notifikasi tidak berkerja (sedang dalam pengerjaan)

</details>

---

### **Versi 2.7.0**

<details>
  <summary>Lihat Detail Versi</summary>

- Ekstensi offline-first ke semua tabel jadwal & Partangiangan
- Konsistensi jadwal & cache offline untuk tabel
- Jadwal Mingguan & Sermon Parhalado: Dukungan cache instan dan update latar belakang
- Info Banner Partangiangan render cache sinkron lebih awal
- Jadwal Ibadah & Jadwal PA/PHD: Caching offline (ambil instan dari Manajemen lalu update di latar belakang)
- Fallback offline pakai cache
- Konversi widget jadwal untuk manajemen cache & pembaharuan instan
- Halaman Home & Jadwal: Pemanggilan diperbarui
- Perubahan konstruktor Jadwal Ibadah bersifat breaking minor
- Masa kedaluwarsa cache jadwal: 7 hari

</details>

---

### **Versi 2.5.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan lag pada saat kali pertama install aplikasi
- Perbaikan postingan blog yang menampilkan simbol-simbol
- Blokir kode iklan web pada tampilan postingan android
- Perbaikan fitur stiker teks berjalan
- Perubahan indikator offline
- Perubahan struktur penampil stiker teks berjalan

</details>

---

### **Versi 2.4.17**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan pengolahan cache yang menyebabkan aplikasi terhenti tiba-tiba
- Peningkatan peforma
- Penyegaran banner informasi
- Penambahan banner untuk keterangan halaman
- Penambahan Stiker informasi teks berjalan dibawah header
- Optimasi pengolahan cache
- Perbaikan beberapa bug
- Pengolahan Stiker dan Banner informasi untuk Admin
- Monitor crash pada user
- Optimasi pengolahan tim untuk jenis devisi
- Optimasi pengolahan pembaca PDF bawaan dan webview

</details>

---

### **Versi 2.4.11**

<details>
  <summary>Lihat Detail Versi</summary>

- Peningkatan keamanan dan logging
- Optimasi kinerja aplikasi
- Penambahan fitur layar tetap menyala saat membaca warta di pengaturan
- Penambahan penampil PDF webview di pengaturan aplikasi
- Penyederhanaan tampilan
- Penjadwalan notifikasi (untuk Admin)
- Optimasi pengelolaan tim dan kategori tim
- Peningkatan stabilitas
- Perubahan UI halaman warta-acara
- Perbaikan widget team yang tiba-tiba berpindah acak
- Cache hanya pada alur internal untuk keamanan

</details>

---

### **Versi 2.4.10**

<details>
  <summary>Lihat Detail Versi</summary>

- Tambah guard ekstra agar tidak ada akses ke controller sebelum siap saat frame awal
- Optimasi pembaca pdf lokal
- Penambahan fitur membuka pdf secara eksternal
- Redesain halaman warta acara
- Otomasi ikon warta acara sesuai jenis file
- Validasi url pdf untuk webview
- Memisahkan cache domain ke box khusus
- Menambah migrasi ringan
- Perbaikan beberapa bug

</details>

---

### **Versi 2.4.1 - 2.4.9**

<details>
  <summary>Lihat Detail Versi</summary>

- Redesign UI Pengaturan
- Otomasi Penghapus cache lebih dari 2 minggu
- Perbaikan beberapa bug dan crash
- Konfigurasi Ulang Team agar konsisten
- Hindari rebuild team jika sudah di kunci oleh Admin
- Perbaikan kategori team yang tiba-tiba hilang
- Penambahan opsi check box untuk tim (admin)
- Redesain pengaturan tim di admin dashboard
- Ganti pemanggilan API usang
- Penghapusan pencatatan log yang tidak diperlukan
- Konsistensi cache untuk semua halaman
- Optimasi pengkompres data untuk sinkronisasi latar belakang
- Redesign indikator offline
- Otomatisasi pengiriman informassi crash pada user
- Perbaikan strukrur penyimpanan tim

</details>

---

### **Versi 2.2.2 - 2.4.0**

<details>
  <summary>Lihat Detail Versi</summary>

- Integrasi dropbox dan google drive untuk penyimpanan online
- Perubahan metode pengambilan postingan
- Fitur edit post khusus mobile
- Fitur pendeteksi perubahan postingan
- Redesign Sidebar Global dan Admin dashboard
- Pemecahan beberapa file menjadi bagian-bagian kecil
- Penguraian kinerja berat menjadi beberapa tahap
- Mengurangi definisi animasi untuk mengurangi beban GPU/CPU
- Optimasi cache, pembersihan PDF, Remote Config fetch, dan priming data awal

</details>

---

### **Versi 2.2.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Integrasi crashlytic untuk non-fatal crash

</details>

---

### **Versi 2.2.0**

<details>
  <summary>Lihat Detail Versi</summary>

- Perubahan struktur metode implementasi Admin
- Sleksi User (untuk Admin)
- Penambahan role contributor untuk admin
- Redesign Profil Admin
- Peningkatan keamanan admin
- Integrasi keamanan google admin

</details>

---

### **Versi 2.1.0** - _19 Agustus 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perubahan arsitektur pengiriman notifikasi
- Penjadwalan notifikasi
- Optimasi dan konsistensi cache setiap halaman
- Menambahkan kompibilitas edge-to-edge
- Mengganti depedensi usang
- Perbaikan bug
- Perubahan struktur header
- Menghapus entri cache korup saat gagal dekompresi
- Redesign layar login
- Perbaikan izin FCM
- Integrasi dengan Github action

</details>

---

### **Versi 1.0.58** - _17 Agustus 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan force close pada versi 1.0.57
- Perbaikan fitur pencarian pada halaman blog
- Optimasi Edge-to-edge
- Penghapusan metode usang
- Perbaikan bug

</details>

---

### **Versi 1.0.57** - _15 Agustus 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan tombol "kembali ke atas"
- Perubahan halaman Tentang aplikasi
- Desain ulang header Aplikasi
- Perbaikan beberapa bug
- Pengoptimalan kode aplikasi
- Penanganan Admin dashboard
- Penambahan fitur ubah password untuk Admin
- Penambahan fitur sinkronisasi Google untuk Admin

</details>

---

### **Versi 1.0.56** - _07 Agustus 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug dan peningkatan performa
- Penambahan metode scrap PDF dari web dan GDrive
- Perubahan UI Blog
- Penambahan Fitur Postingan Unggulan
- Optimasi pembuka PDF
- Optimasi metode unduh PDF
- Perbaikan Cache Info Partangiangan
- Perbaikan beberapa bug

</details>

---

### **Versi 1.0.55** - _02 Agustus 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug dan peningkatan performa
- Penambahan kemampuan memuat gambar pada notifikasi
- Pengoptimalan metode cache
- Penambahan Jadwal Partangiangan Weyk
- Penghapusan sisi samping Penampil PDF
- Pengoptimalan Pembacaan PDF
- Meringankan halaman utama aplikasi
- Penambahan keamanan AppCheck
- Perbaikan Bug
- Perbaikan tombol aksi notifikasi
- Pembaharuan bahasa pendukung

</details>

---

### **Versi 1.0.50** - _20 Juni 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug dan peningkatan performa
- Perbaikan edge-to-edge
- Integrasi Play Integrity
- Dan banyak lagi

</details>

---

### **Versi 1.0.43** - _28 April 2025_

<details>
  <summary>Lihat Detail Versi</summary>

- Fetch Warta Acara dengan Metode Baru mengikuti struktur web
- Penambahan Sistem notifikasi dengan fitur Tombol
- Perbaikan direct sistem notifikasi
- Perbaikan Bug
- Penyimpanan Dokumen tersendiri
- Pengoptimalan Pembuka Pdf

</details>

---

### **Versi 1.0.37 - 1.0.38**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan Bug
- Perbaikan cache lokal
- Perbaikan sinkronasi Jadwal
- Penambahan metode refresh di halaman warta
- Fitur Pengurutan kategori team
- Perbaikan logika halaman info huria
- Fitur Perbaikan sinkronasi Jadwal dan Team dengan firebase

</details>

---

### **Versi 1.0.36 - 1.0.37**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan Bug
- Memperbaiki fitur cache
- Menutup akses pendaftaran user
- Sinkronasi data team dengan firebase

</details>

---

### **Versi 1.0.35 - 1.0.36**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug
- Migrasi penyimpanan dari hive ke hive_ce
- Perbaikan Halaman Dokumen
- Integrasi Dokumen di Halaman Dokumen Dengan ImageKit
- Menetapkan sidebar hanya untuk warta-acara
- Memperbaiki gambar terbalik pada sidebar

</details>

---

### **Versi 1.0.34 - 1.0.35**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug
- Integrasi ImageKit sebagai media utama penyimpanan file
- Perbaikan fitur Analystik
- Perbaikan integrasi firebase

</details>

---

### **Versi 1.0.30 - 1.0.34**

<details>
  <summary>Lihat Detail Versi</summary>

- Meningkatkan stabilitas
- Mengubah metode fetch dokumen dan warta hanya oleh admin
- Pembaharuan otomatis dokumen
- Perbaikan bug
- Penambahan fitur agar dapat di akses dalam mode offline
- Sinkronasi otomatis jika koneksi terdeteksi
- Menambah perijinan perangkat agar dapat mengunduh warta atau dokumen
- Perbaikan halaman blog untuk mengambil dari web
- Merapikan detail isi post pada blog
- Menambahkan Imagekit sebagai penyimpanan online
- Penambahan database warta untuk menangkap dari web
- Memperbaiki metode dokumen
- Filter postingan yang di tangkap dari web pada data dokumen

</details>

---

### **Versi 1.0.25 - 1.0.30**

<details>
  <summary>Lihat Detail Versi</summary>

- Penambahan fitur popup pada foto info huria, fungsionaris, dan tim digital
- Penambahan menu Dokumen pada Sidebar
- Menghapus metode Signup
- Menambah fitur penambahan user hanya oleh Admin
- Perbaikan splash screen terpotong pada Android 14
- Perbaikan bug

</details>

---

### **Versi 1.0.1 - 1.0.25**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan bug
- Pengelompokan halaman warta-acara berdasarkan kegiatan acara
- Metode fetch warta agar dapat mendeteksi postingan terbaru di website

</details>

---

### **Versi 1.0.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Penambahan fitur analistik
- Perbaikan beberapa bug
- Optimisasi halaman warta acara setiap kali dibuka
- Penambahan tabel "hari" dalam jadwal kegiatan
- Peningkatan keamanan
- Penambahan sosial media facebook, youtube, dan instagram di halaman kontak

</details>

---

### **Versi 1.0.0** _(Rilis Awal)_

<details>
  <summary>Lihat Detail Versi</summary>

- Penambahan Halaman: Info Huria, Warta Jemaat, Jadwal Kegiatan, Blog, Info Aplikasi, Kebijakan Privasi, Fungsionaris, Tim Digital
- Pemuatan Warta Jemaat menggunakan web_view ke situs https://www.hkbpperawang.org
- Penanganan Notifikasi agar dapat dikirim dan diterima secara real time
- Penambahan fungsi jadwal kegiatan agar dapat di ubah tanpa pembaharuan
- Penambahan fungsi jadwal ibadah
- Penambahan fitur user
- Penambahan fitur statistik huria untuk memunculkan di halaman info huria

</details>

</details>

---

## 🧪 Rilis Beta

<details>
  <summary><strong>Cek Detail</strong></summary>

### **Versi 2.10.2** ✨ _(Terbaru)_

<details>
  <summary>Lihat Detail Versi</summary>

- Integrasi layanan Sentry pada Aplikasi
- Perubahan UI halaman "Kidung Nyanyian" dan "Isi Nyanyian"
- Menambah fungsi Bagikan Teks dan Bagikan Gambar untuk "Isi Nyanyian"
- Menonaktifkan Keypad "Kidung Nyanyian" jika sumber belum di unduh
- Penyesuaian Ukuran Teks "Isi Nyanyian"
- Menambah fitur gesture untuk zoom in dan zoom out pada halaman "Kidung Nyanyian"
- Memperluas fungsi Capture menjadi Long Capture agar dapat menangkap seluruh isi halaman "Isi nyanyian"
- Menambahkan Fungsi Download pada Fitur "Bagikan Gambar"
- Penyimpanan status selesai unduh per folder nyanyian sehingga aplikasi tahu kapan berkas sudah lengkap meski setelah restart
- Pesan keberhasilan di halaman Kidung Nyanyian yang muncul otomatis ketika semua berkas telah siap dipakai
- Hook Crashlytics yang sudah ada kini ikut meneruskan error ke Sentry

</details>

---

### **Versi 2.10.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Penambahan Halaman Publik "Kidung Nyanyian" yang memuat daftar lagu dari GitHub dengan dukungan unduhan offline
- Penambahan menu sidebar dan fitur keypad pada halaman "Kidung Nyanyian"
- Penambahan Rute "Kidung Nyanyian" pada konfigurasi internal
- Membuat endpoint menjadi raw agar mudah dalam pengunduhan
- Menghapus Interceptor header dan menghormati header khusus agar log tidak membocorkan token github
- Integrasi Judul dan jumlah kidung nyanyian pada firestore
- Integrasi Backend Admin untuk mengelola jenis kidung nyanyian

</details>

---

### **Versi 2.9.2**

<details>
  <summary>Lihat Detail Versi</summary>

- Label overlay lingkungan pada build non-produksi dihapus sehingga tampilan debug kembali bersih tanpa memengaruhi fitur debug, logging, maupun konfigurasi lingkungan yang lain
- Pengiriman notifikasi manual kini mencoba beberapa region Cloud Functions sesuai konfigurasi
- Menghapus file-file Kritis dari sumber proyek untuk keamanan

</details>

---

### **Versi 2.9.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Pembersihan cache memastikan file lokal diregenerasi saat versi server
- Prefetch otomatis Partangiangan dijalankan di latar belakang
- Cloud Function baru untuk mengirim FCM secara aman melalui backend dengan validasi peran admin
- Pemuatan cache Partangiangan segera saat startup sehingga kartu langsung menampilkan data lokal
- Inisialisasi Partangiangan kini memakai satu jalur fallback yang mengutamakan berkas lokal
- Pemuatan snapshot fungsionaris dari cache Hive/DataCache segera setelah provider aktif
- Tombol "Info Partangiangan Weyk" kini selalu aktif tanpa pesan unduhan
- Tampilan penuh Partangiangan menampilkan banner "Harap Hubungkan ke Internet untuk mengambil Info Partangiangan" dan menonaktifkan tombol unduh ketika perangkat sedang offline
- Tombol **Clear Cache** di dasbor menaikkan versi cache di Firestore sehingga semua perangkat memaksa sinkron ulang dan mengosongkan salinan lama
- FCM dan utilitas terkait kini memakai Firebase Cloud Functions sehingga tidak lagi membaca kredensial service account dari bundle aplikasi
- Penyederhanaan penggunaan Firebase API
- Peningkatan keamanan file-file yang dapat diakses publik
- Jadwal Ibadah, Daftar Dokumen, dan Kategori Post kini menyimpan cache dengan metode yang sama
- Rutinitas warmup pasca-frame kini melibatkan `TeamProvider` untuk memicu revalidasi diam-diam ketika perangkat online
- Penambahan kemampuan akses warta dalam mode offline menggunakan pembaca PDF lokal
- Seluruh dialog dan snackbar lintas modul sudah menyimpan navigator/messenger sebelum operasi async
- Penanda lingkungan (`Banner`) dibungkus dengan `Directionality` sehingga overlay label tidak lagi memicu runtime error
- Tombol "Info Partangiangan Weyk" di beranda langsung membuka cache yang tersedia sehingga shimmer hanya muncul ketika aplikasi benar-benar mengambil data terbaru
- Halaman Warta kembali menampilkan daftar arsip ketika perangkat luring karena provider kini selalu mundur ke cache lokal sebelum menghubungi Firestore
- Konfigurasi lint Functions
- Pengubahan Metode CACHE-FIRST untuk semua widget yang mengambil data dari Firebase

</details>

---

### **Versi 2.9.0**

<details>
  <summary>Lihat Detail Versi</summary>

- Skeleton shimmer global untuk halaman di tab utama
- Penyesuaian template shimmer untuk grid, list, dan detail
- Resolusi jalur lokal Partangiangan kini mengenali path Windows dan URI
- Kartu "Info Partangiangan Weyk" selalu aktif menampilkan cache awal
- Fallback shimmer kartu Partangiangan kini ditampilkan maksimal selama validasi ulang jaringan

</details>

---

### **Versi 2.8.6**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan loop saat data offline
- Normalisasi pengambilan URL partangiangan
- Widget smoke test diperbarui agar mengikuti alur bootstrap
- Penambahan fallback agar perangkat tidak berhenti di splash screen
- Halaman Blog dan Warta Acara memaksa pengecekan koneksi pasca-frame
- Pembersihan indikator koneksi di main_page dan dipindahkan ke header
- Koreksi deteksi konektivitas ganda
- Banner offline kini menunggu setidaknya 3 detik setelah masa grace berakhir
- Kartu jadwal Partangiangan di beranda kini tetap aktif menggunakan versi cache
- Inisialisasi kartu Partangiangan memprioritaskan cache sinkron dan menampilkan indikator loading sampai data siap
- Penyesuaian banner indikator offline

</details>

---

### **Versi 2.8.5**

<details>
  <summary>Lihat Detail Versi</summary>

- Update versi dart, kotlin, AGP
- Perbaikan aplikasi berhenti di flash screen
- Perbaikan kotlin
- Migrasi lanjutan build.gradle.kts
- Integrasi arsip native-debug untuk keperluan playconsole

</details>

---

### **Versi 2.8.4**

<details>
  <summary>Lihat Detail Versi</summary>

- Update framework flutter 3.35.4
- Migrasi sinkron data admin dan editor
- Penggantian metode usang
- Integrasi verifikasi 2 langkah untuk admin dan editor

</details>

---

### **Versi 2.7.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan kestabilan unduhan & guard UI
- Crash fatal Null check
- Perbaikan integrasi crashlytics
- Perbaikan metode pengambilan koneksi
- Perbaikan cache file pdf

</details>

---

### **Versi 2.6.5**

<details>
  <summary>Lihat Detail Versi</summary>

- Optimisasi startup offline-first & pengurangan jank
- Revalidasi ringan jadwal hanya bila koneksi tersedia & data masih dari cache
- Revalidasi bertahap WartaAcara
- Hapus logging build berulang
- Warmup post-frame kini menerima context untuk akses provider aman dan menambahkan jadwal revalidation
- Revalidasi multi-provider bertingkat + guard scheduler

</details>

---

### **Versi 2.6.4**

<details>
  <summary>Lihat Detail Versi</summary>

- Sinkronisasi Custom Notes ke HomeScreen
- Tambah render Custom Notes kategori 01 dan 02
- Menjamin konsistensi informasi penting

</details>

---

### **Versi 2.6.3**

<details>
  <summary>Lihat Detail Versi</summary>

- Fokus stabilitas & pembersihan akhir PDF viewer + perbaikan lintas modul
- Perbaikan crash notifikasi firebase
- Perbaikan Build gagal ekstensi Matrix4
- Penyederhanaan controller & callback
- Rewrite terstruktur + scroll aman

</details>

---

### **Versi 2.6.2**

<details>
  <summary>Lihat Detail Versi</summary>

- Refactor & finalisasi arsitektur PDF + telemetry tambahan
- Prefetch hingga 8 PDF Warta
- Penggunaan telemetry untuk pemantau kegagalan inisialisasi aplikasi
- Perbaikan build berlebih saat aplikasi dijalankan

</details>

---

### **Versi 2.6.1**

<details>
  <summary>Lihat Detail Versi</summary>

- Ekstensi caching & observability
- Penerapan SWR secara menyeluruh dalam pengolahan cache
- Analisis kinerja aplikasi dalam Dashboard Admin
- Fallback menggunakan pembaca lokal jika pembaca webview gagal dimuat

</details>

---

### **Versi 2.6.0**

<details>
  <summary>Lihat Detail Versi</summary>

- Fondasi fitur infra kinerja & offline
- Antrian operasi dokumen/kategori + flush otomatis saat online
- Penambahan fitur Prefetch untuk warta acara
- Grace startup
- Penerapan SWR untuk pengelola cache
- Penundaan informasi offline untuk kasus false offline
- Perbaiki banner indikasi offline menyebabkan flicker
- UX offline diawal pembukaan aplikasi

</details>

---

### **Versi 2.5.2**

<details>
  <summary>Lihat Detail Versi</summary>

- Perbaikan beberapa halaman tertutup sistem navigasi perangkat
- Mengatur jarak bawah halaman secara global
- Pembersihan jarak bawah pada halaman-halaman lokal

</details>

</details>

---

## 📬 Info Lainnya

Kami menerima **Kritik, Masukan, dan Saran** terkait fitur dan pengembangan aplikasi.  
Bagi Amang Inang yang memiliki ide atau permintaan terkait aplikasi, dapat mengirimkan pesan melalui sosial media HKBP Perawang:

- **Facebook:** [https://fb.com/HKBPPerawang](https://fb.com/HKBPPerawang)
- **Instagram:** [https://instagram.com/HKBPPerawang](https://instagram.com/HKBPPerawang)

**Hormat Kami,**  
_Devisi Digital Tim Multimedia HKBP Perawang_
