# 📜 Changelog / Catatan Rilis

Lihat riwayat pembaruan dan penambahan fitur pada aplikasi di bawah ini.

---

## 🚀 Rilis Publik

<details open markdown="1">
<summary><strong>Cek Detail</strong></summary>

<br/>

<details markdown="1">
<summary><strong>Versi 2.12.0 ✨ (Terbaru)</strong></summary>

<br/>

**Perbaikan & Peningkatan**
- Migrasi Notifikasi menggunakan Firebase
- Perbaikan mengikuti Kebijakan Google Play
- Mencabut ijin pembacaan Gambar/Video pada perangkat pengguna
- Perbaikan waktu sinkronasi interval aplikasi
- Update depedensi dan versi framework
- Perbaikan beberapa Bug
- Menyimpan riwayat notifikasi langsung ke koleksi di Cloud Firestore dari sisi client
- Menghapus ketergantungan pada Cloudflare Workers dan Cloud Functions.

</details>

<details markdown="1">
<summary><strong>Versi 2.11.4</strong></summary>

<br/>

**Fitur Baru**
- **Modul Kidung Nyanyian:** Fitur lengkap untuk akses kidung digital, unduhan offline, navigasi keypad, pencarian lirik, zoom gesture, dan bagikan gambar lirik
- **Sistem Notifikasi:** Penjadwalan otomatis, in-app messaging, histori lengkap (akses admin)
- **Stiker & Pengumuman:** Teks berjalan multi-item dengan pengaturan warna dan kecepatan
- **Mode Offline-First:** Cache pintar dengan sinkronisasi otomatis di latar belakang
- **Postingan:** Penambahan beberapa kategori Postingan
- **Sentry:** Integrasi layanan sentry untuk memantau kerusakan pada user

**Perbaikan & Peningkatan**
- Perbaikan carousel artikel unggulan, filter kategori, dan sistem cache offline
- Optimisasi performa dan startup aplikasi
- Perbaikan stabilitas (crash PDF, koneksi internet, splash screen)
- Peningkatan antarmuka pengguna dengan desain modern
- Perbaikan warta & PDF dengan prefetch otomatis
- Peningkatan sistem tim dan notifikasi

**Keamanan & Kompatibilitas**
- Firebase App Check untuk proteksi API
- Kompatibilitas penuh Android 15 (API Level 35)
- Migrasi ke Play Integrity API

**Bug Yang Diketahui**
- Notifikasi tidak berkerja (sedang dalam pengerjaan)

</details>

<details markdown="1">
<summary><strong>Versi 2.10.10</strong></summary>

<br/>

**Fitur Baru**
- **Modul Kidung Nyanyian:** Fitur lengkap untuk akses kidung digital, unduhan offline, navigasi keypad, pencarian lirik, zoom gesture, dan bagikan gambar lirik
- **Sistem Notifikasi:** Penjadwalan otomatis, in-app messaging, histori lengkap (akses admin)
- **Stiker & Pengumuman:** Teks berjalan multi-item dengan pengaturan warna dan kecepatan
- **Mode Offline-First:** Cache pintar dengan sinkronisasi otomatis di latar belakang
- **Postingan:** Penambahan beberapa kategori Postingan
- **Sentry:** Integrasi layanan sentry untuk memantau kerusakan pada user

**Perbaikan & Peningkatan**
- Perbaikan carousel artikel unggulan, filter kategori, dan sistem cache offline
- Optimisasi performa dan startup aplikasi
- Perbaikan stabilitas (crash PDF, koneksi internet, splash screen)
- Peningkatan antarmuka pengguna dengan desain modern
- Perbaikan warta & PDF dengan prefetch otomatis
- Peningkatan sistem tim dan notifikasi

**Keamanan & Kompatibilitas**
- Firebase App Check untuk proteksi API
- Kompatibilitas penuh Android 15 (API Level 35)
- Migrasi ke Play Integrity API

**Bug Yang Diketahui**
- Notifikasi tidak berkerja (sedang dalam pengerjaan)

</details>

<details markdown="1">
<summary><strong>Versi 2.7.0</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.5.1</strong></summary>

<br/>

- Perbaikan lag pada saat kali pertama install aplikasi
- Perbaikan postingan blog yang menampilkan simbol-simbol
- Blokir kode iklan web pada tampilan postingan android
- Perbaikan fitur stiker teks berjalan
- Perubahan indikator offline
- Perubahan struktur penampil stiker teks berjalan

</details>

<details markdown="1">
<summary><strong>Versi 2.4.17</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.4.11</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.4.10</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.4.9</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.4.0</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.2.1</strong></summary>

<br/>

- Integrasi crashlytic untuk non-fatal crash

</details>

<details markdown="1">
<summary><strong>Versi 2.2.0</strong></summary>

<br/>

- Perubahan struktur metode implementasi Admin
- Sleksi User (untuk Admin)
- Penambahan role contributor untuk admin
- Redesign Profil Admin
- Peningkatan keamanan admin
- Integrasi keamanan google admin

</details>

<details markdown="1">
<summary><strong>Versi 2.1.0</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 1.0.58</strong></summary>

<br/>

- Perbaikan force close pada versi 1.0.57
- Perbaikan fitur pencarian pada halaman blog
- Optimasi Edge-to-edge
- Penghapusan metode usang
- Perbaikan bug

</details>

<details markdown="1">
<summary><strong>Versi 1.0.57</strong></summary>

<br/>

- Perbaikan tombol "kembali ke atas"
- Perubahan halaman Tentang aplikasi
- Desain ulang header Aplikasi
- Perbaikan beberapa bug
- Pengoptimalan kode aplikasi
- Penanganan Admin dashboard
- Penambahan fitur ubah password untuk Admin
- Penambahan fitur sinkronisasi Google untuk Admin

</details>

<details markdown="1">
<summary><strong>Versi 1.0.56</strong></summary>

<br/>

- Perbaikan bug dan peningkatan performa
- Penambahan metode scrap PDF dari web dan GDrive
- Perubahan UI Blog
- Penambahan Fitur Postingan Unggulan
- Optimasi pembuka PDF
- Optimasi metode unduh PDF
- Perbaikan Cache Info Partangiangan
- Perbaikan beberapa bug

</details>

<details markdown="1">
<summary><strong>Versi 1.0.55</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 1.0.50</strong></summary>

<br/>

- Perbaikan bug dan peningkatan performa
- Perbaikan edge-to-edge
- Integrasi Play Integrity
- Dan banyak lagi

</details>

<details markdown="1">
<summary><strong>Versi 1.0.43</strong></summary>

<br/>

- Fetch Warta Acara dengan Metode Baru mengikuti struktur web
- Penambahan Sistem notifikasi dengan fitur Tombol
- Perbaikan direct sistem notifikasi
- Perbaikan Bug
- Penyimpanan Dokumen tersendiri
- Pengoptimalan Pembuka Pdf

</details>

<details markdown="1">
<summary><strong>Versi 1.0.38</strong></summary>

<br/>

- Perbaikan Bug
- Perbaikan cache lokal
- Perbaikan sinkronasi Jadwal
- Penambahan metode refresh di halaman warta
- Fitur Pengurutan kategori team
- Perbaikan logika halaman info huria
- Fitur Perbaikan sinkronasi Jadwal dan Team dengan firebase

</details>

<details markdown="1">
<summary><strong>Versi 1.0.37</strong></summary>

<br/>

- Perbaikan Bug
- Memperbaiki fitur cache
- Menutup akses pendaftaran user
- Sinkronasi data team dengan firebase

</details>

<details markdown="1">
<summary><strong>Versi 1.0.36</strong></summary>

<br/>

- Perbaikan bug
- Migrasi penyimpanan dari hive ke hive_ce
- Perbaikan Halaman Dokumen
- Integrasi Dokumen di Halaman Dokumen Dengan ImageKit
- Menetapkan sidebar hanya untuk warta-acara
- Memperbaiki gambar terbalik pada sidebar

</details>

<details markdown="1">
<summary><strong>Versi 1.0.35</strong></summary>

<br/>

- Perbaikan bug
- Integrasi ImageKit sebagai media utama penyimpanan file
- Perbaikan fitur Analystik
- Perbaikan integrasi firebase

</details>

<details markdown="1">
<summary><strong>Versi 1.0.34</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 1.0.30</strong></summary>

<br/>

- Penambahan fitur popup pada foto info huria, fungsionaris, dan tim digital
- Penambahan menu Dokumen pada Sidebar
- Menghapus metode Signup
- Menambah fitur penambahan user hanya oleh Admin
- Perbaikan splash screen terpotong pada Android 14
- Perbaikan bug

</details>

<details markdown="1">
<summary><strong>Versi 1.0.25</strong></summary>

<br/>

- Perbaikan bug
- Pengelompokan halaman warta-acara berdasarkan kegiatan acara
- Metode fetch warta agar dapat mendeteksi postingan terbaru di website

</details>

<details markdown="1">
<summary><strong>Versi 1.0.1</strong></summary>

<br/>

- Penambahan fitur analistik
- Perbaikan beberapa bug
- Optimisasi halaman warta acara setiap kali dibuka
- Penambahan tabel "hari" dalam jadwal kegiatan
- Peningkatan keamanan
- Penambahan sosial media facebook, youtube, dan instagram di halaman kontak

</details>

<details markdown="1">
<summary><strong>Versi 1.0.0</strong> <em>(Rilis Awal)</em></summary>

<br/>

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

<details markdown="1">
<summary><strong>Cek Detail</strong></summary>

<br/>

<details markdown="1">
<summary><strong>Versi 2.12.0 ✨ (Terbaru)</strong></summary>

<br/>

### Diperbaiki

- **Migrasi Notifikasi FCM ke Client-Side HTTP v1 (Firebase Free/Spark Plan)**: Memindahkan seluruh pengiriman notifikasi push manual dari Firebase Cloud Functions & Cloudflare Worker ke pemanggilan langsung dari sisi client menggunakan FCM HTTP v1 REST API.
- Mengintegrasikan pustaka `googleapis_auth` untuk menghasilkan token OAuth2 secara lokal dari aplikasi menggunakan kredensial Service Account.
- Menyimpan riwayat notifikasi langsung ke koleksi di Cloud Firestore dari sisi client.
- Menghapus ketergantungan pada Cloudflare Workers dan Cloud Functions.
- Integrasi Firevase FCM

</details>

<details markdown="1">
<summary><strong>Versi 2.11.6</strong></summary>

<br/>

### Diperbaiki

- **Error `onReorder` deprecated**: Memperbaiki peringatan deprecation serta menghapus penyesuaian indeks manual sesuai dengan pembaruan Flutter v3.41.0.
- **Error `cacheExtent` deprecated**: Mengganti `cacheExtent` menjadi `scrollCacheExtent` pada `pdf_sidebar.dart` sesuai dengan pembaruan Flutter v3.41.0.
- **Peringatan `use_null_aware_elements`**: Mengganti *null check* manual menjadi *null-aware map elements* (`?`) pada `nyanyian_config_service.dart` dan `nyanyian_song.dart` sesuai dengan *lint rules* Dart terbaru.
- **Google Play Console Policy Violation**: Menghapus `READ_MEDIA_IMAGES` dan `READ_MEDIA_VIDEO` dari `AndroidManifest.xml` untuk mematuhi kebijakan Google Play Console terkait akses file media, karena aplikasi hanya melakukan operasi simpan (download) yang tidak memerlukan izin tersebut pada sistem Android modern.
- **Error `TickerMode.of` deprecated**: Memperbaiki peringatan deprecation sesuai dengan pembaruan Flutter v3.35.0.
- **Error `admin-restricted-operation` saat inisialisasi aplikasi**: Memperbaiki error FirebaseAuthException yang terjadi saat aplikasi dimulai.

</details>

<details markdown="1">
<summary><strong>Versi 2.11.4</strong></summary>

<br/>

**Perbaikan**
- **Error `Firebase App Check token is invalid` saat inisialisasi aplikasi**: Memperbaiki race condition kritis antara inisialisasi App Check dan query Firestore yang menyebabkan error saat aplikasi dimulai, terutama pada perangkat dengan koneksi lambat (Android 13-16). Perbaikan meliputi:
	- Menambahkan method `AppCheckService.waitForValidToken()` untuk memastikan token App Check valid sudah tersedia sebelum melanjutkan operasi Firestore
	- Update `AppInitializer._configureFirebaseServices()` untuk menunggu token App Check siap dengan retry logic (max 8 percobaan, exponential backoff dengan jitter)
	- Menambahkan delay tambahan 200ms di `_handlePostFrameBootstrap()` sebelum memanggil `teamCategoryProvider.initialize()` untuk memberikan waktu ekstra bagi App Check pada perangkat lambat
	- Logging yang lebih informatif untuk tracking status App Check token selama proses inisialisasi

</details>


<details markdown="1">
<summary><strong>Versi 2.11.3</strong></summary>

<br/>

**Perbaikan**
- **Error sintaks kritis** yang menyebabkan aplikasi crash: State class dan method yang hilang telah dipulihkan.
- **Peringatan kompilasi** di `Home Screen`: removed unused variables dan memperbaiki const correctness di widget `_PartangianganLoadingCard`.
- **Flash banner default** saat aplikasi dibuka: Banner Partangiangan kini langsung menampilkan data yang dikonfigurasi (title, deskripsi, icon) tanpa menampilkan "Info Partangiangan Weyk" terlebih dahulu dengan menambahkan method `getCachedPartangianganInfo()` untuk pembacaan cache sinkron.
- **Error `UNAUTHENTICATED` saat mengirim notifikasi**: Memperbaiki race condition di `FCMService` yang menyebabkan Cloud Function `adminSendNotification` gagal dengan error `UNAUTHENTICATED` ketika sesi Firebase Auth user berakhir atau menjadi invalid di antara proses validasi token dan pemanggilan Cloud Function. Perbaikan meliputi:
- Validasi ulang user setelah `user.reload()` di `_ensureAuthenticated()` dan `_refreshUserToken()` untuk memastikan sesi masih valid
- Penambahan pemeriksaan autentikasi final tepat sebelum `callable.call()` untuk meminimalkan jeda waktu antara validasi auth dan pemanggilan Cloud Function
- Peningkatan error handling untuk mendeteksi dan melaporkan masalah auth state dengan lebih baik, termasuk menghentikan retry jika user sudah logout
- Pesan error yang lebih jelas dan actionable untuk memandu pengguna melakukan login ulang ketika sesi berakhir

**Perubahan**
- Opsi pengiriman notifikasi kini memakai radio Pop Up/Notifikasi, sekaligus menghapus pengaturan Penjadwalan dan Kadaluarsa dari form kirim notifikasi.
- Mode Pop Up dikirim sebagai pesan data-only dan hanya muncul di dalam aplikasi; pesan ini tidak disimpan ke Firestore maupun status bar karena Cloud Function dan `NotificationHandler` melewati penulisan riwayat ketika `isPopup` aktif.
- Pengiriman notifikasi kini memaksa refresh token Firebase saat kena error `UNAUTHENTICATED` serta menolak pengiriman jika sesi login sudah habis, menghindari kegagalan callable `adminSendNotification`.
- Tambahan refresh token dan App Check sebelum setiap percobaan callable memastikan sesi terbaru selalu dipakai saat memanggil `adminSendNotification`.
- Fungsi callable kembali memakai instance default (us-central1) dengan fallback not-found, menyesuaikan lokasi deploy aktual.
- Optimisasi tombol refresh di *Tambah Postingan* kini mendeteksi perubahan konten (HTML/teks) menggunakan hashing SHA-256, mengatasi masalah di mana perubahan isi postingan tidak terdeteksi sebelumnya.
- Indikator "Diubah" pada daftar postingan kini langsung hilang segera setelah postingan berhasil disimpan, memberikan umpan balik instan tanpa perlu refresh manual.
- Daftar icon banner Partangiangan dikurasi dan dibersihkan: dihapus icon yang tidak relevan (love, music, people, transport, maps, weather, communication seperti guitar, mic, bubble chat) dan ditambahkan icon khusus perayaan.
- `HomeScreen` kini menggunakan data cache sebagai nilai awal di `StreamBuilder` sebelum stream data tersedia, memberikan pengalaman loading yang lebih mulus.
- Reference ke icon map sekarang menggunakan `PartangianganIcons`.

**Penambahan**
- Fitur **Manajemen Banner Partangiangan** yang dinamis: Admin kini dapat mengubah judul, deskripsi, dan visibilitas banner langsung dari aplikasi tanpa perlu update kodingan.
- Dukungan **Realtime Updates**: Perubahan pada konfigurasi banner langsung terefleksi di Home Screen semua pengguna yang sedang membuka aplikasi.
- Validasi URL gambar yang lebih fleksibel (mendukung ekstensi .JPG, .PNG, dll secara case-insensitive) dan tombol hapus cepat pada field input URL.
- Opsi URL gambar opsional: Banner tetap dapat ditampilkan dengan judul dan deskripsi saja meskipun tanpa gambar (menampilkan pesan "Gambar tidak tersedia" saat diketuk).
- Fitur **Pilih Semua** / **Batal Pilih Semua** di layar *Tambah Postingan* untuk memudahkan seleksi massal, lengkap dengan dukungan filter "Tampilkan yang diubah".
- Mekanisme invalidasi cache otomatis pada detail postingan: aplikasi kini mendeteksi perubahan konten (hash SHA-256) dan otomatis mengunduh ulang data terbaru tanpa interaksi pengguna.
- **Library icon terpusat** dengan ~50 icon yang relevan dari FontAwesome dan Material Icons untuk pemilihan icon banner Partangiangan.
- **Icon Material Design untuk perayaan**: Ditambahkan `Icons.celebration` (kembang api tahun baru), `Icons.auto_awesome` (kilauan), dan `Icons.flare` sebagai alternatif icon perayaan tanpa menambah dependensi.
- Method PartangianganService untuk membaca data cache Partangiangan secara sinkron, mencegah flash konten default.

**Penghapusan**
- Seluruh modul penjadwalan notifikasi (layanan Flutter, layar/admin widget, aturan Firestore, fallback koleksi `scheduled_notifications`, fungsi terjadwal, serta template/infra penjadwal) dihapus sejalan dengan penghentian fitur kadaluarsa pengiriman.

</details>

<details markdown="1">
<summary><strong>Versi 2.10.15</strong></summary>

<br/>

**Perbaikan**
- Menyeragamkan line ending dan membungkus baris panjang pada skrip Firebase Functions sehingga lint berbasis Unix line ending kembali lulus tanpa mengubah versi dependensi Node 22 / Firebase Functions.
- Inisialisasi Sentry kini memprioritaskan `--dart-define=SENTRY_DSN` dengan fallback ke `.env`, serta menampilkan peringatan saat DSN absen agar build rilis tidak diam-diam berjalan tanpa pelaporan.
- Menambahkan aturan ProGuard khusus Sentry agar auto-instrumentation, transport, dan AndroidX Startup tidak dipangkas saat rilis, sehingga pelaporan crash & performa tetap lengkap.
- Migrasi parameter `androidProvider` dan `appleProvider` yang usang pada `AppCheckService` menjadi `providerAndroid` dan `providerApple` sesuai rekomendasi Firebase App Check terbaru.
- Mengunci App Check debug token supaya nilai token konsisten saat run/debug (F5) dan tidak lagi berubah sehingga App Check tidak gagal dengan `App attestation failed`.
- Memanggil `_loadData` di Halaman jadwal setelah frame pertama selesai dibangun supaya Jadwal tidak memicu `notifyListeners` saat fase build, menghilangkan error Crashlytics "setState() or markNeedsBuild() called during build."
- Timeout prefetch PDF Google Drive kini dicatat sebagai log debug (tanpa warning Crashlytics) sehingga retry background tidak lagi memunculkan error non-fatal saat jaringan lambat atau link membutuhkan waktu lebih lama untuk merespons.
- Indikator carousel posting unggulan di `BlogScreen` kini memeriksa jumlah attach PageView sebelum membaca `PageController.page`, mencegah assertion "page property cannot be read when multiple PageViews are attached" saat navigasi antar tab.
- Tombol "Muat Lebih Banyak" di Warta Acara kini menampilkan shimmer list selama penambahan data dan tidak lagi langsung menunjukkan pesan "Semua file sudah dimuat" sebelum snapshot baru datang, menyelaraskan perilaku dengan halaman blog.

**Perubahan**
- Refaktor animasi load more pada WartaAcaraScreen agar menampilkan skeleton loader sebagai item daftar individual, menyamakan perilaku dengan BlogScreen untuk pengalaman pengguna yang lebih mulus.
- Tombol "Kirim error uji coba ke Sentry" pada halaman Tentang Aplikasi kini hanya muncul saat aplikasi berjalan dalam mode debug, mencegah pengguna produksi memicu laporan kesalahan palsu.

</details>

<details markdown="1">
<summary><strong>Versi 2.10.2</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.10.1</strong></summary>

<br/>

- Penambahan Halaman Publik "Kidung Nyanyian" yang memuat daftar lagu dari GitHub dengan dukungan unduhan offline
- Penambahan menu sidebar dan fitur keypad pada halaman "Kidung Nyanyian"
- Penambahan Rute "Kidung Nyanyian" pada konfigurasi internal
- Membuat endpoint menjadi raw agar mudah dalam pengunduhan
- Menghapus Interceptor header dan menghormati header khusus agar log tidak membocorkan token github
- Integrasi Judul dan jumlah kidung nyanyian pada firestore
- Integrasi Backend Admin untuk mengelola jenis kidung nyanyian

</details>

<details markdown="1">
<summary><strong>Versi 2.9.2</strong></summary>

<br/>

- Label overlay lingkungan pada build non-produksi dihapus sehingga tampilan debug kembali bersih tanpa memengaruhi fitur debug, logging, maupun konfigurasi lingkungan yang lain
- Pengiriman notifikasi manual kini mencoba beberapa region Cloud Functions sesuai konfigurasi
- Menghapus file-file Kritis dari sumber proyek untuk keamanan

</details>

<details markdown="1">
<summary><strong>Versi 2.9.1</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.9.0</strong></summary>

<br/>

- Skeleton shimmer global untuk halaman di tab utama
- Penyesuaian template shimmer untuk grid, list, dan detail
- Resolusi jalur lokal Partangiangan kini mengenali path Windows dan URI
- Kartu "Info Partangiangan Weyk" selalu aktif menampilkan cache awal
- Fallback shimmer kartu Partangiangan kini ditampilkan maksimal selama validasi ulang jaringan

</details>

<details markdown="1">
<summary><strong>Versi 2.8.6</strong></summary>

<br/>

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

<details markdown="1">
<summary><strong>Versi 2.8.5</strong></summary>

<br/>

- Update versi dart, kotlin, AGP
- Perbaikan aplikasi berhenti di flash screen
- Perbaikan kotlin
- Migrasi lanjutan build.gradle.kts
- Integrasi arsip native-debug untuk keperluan playconsole

</details>

<details markdown="1">
<summary><strong>Versi 2.8.4</strong></summary>

<br/>

- Update framework flutter 3.35.4
- Migrasi sinkron data admin dan editor
- Penggantian metode usang
- Integrasi verifikasi 2 langkah untuk admin dan editor

</details>

<details markdown="1">
<summary><strong>Versi 2.7.1</strong></summary>

<br/>

- Perbaikan kestabilan unduhan & guard UI
- Crash fatal Null check
- Perbaikan integrasi crashlytics
- Perbaikan metode pengambilan koneksi
- Perbaikan cache file pdf

</details>

<details markdown="1">
<summary><strong>Versi 2.6.5</strong></summary>

<br/>

- Optimisasi startup offline-first & pengurangan jank
- Revalidasi ringan jadwal hanya bila koneksi tersedia & data masih dari cache
- Revalidasi bertahap WartaAcara
- Hapus logging build berulang
- Warmup post-frame kini menerima context untuk akses provider aman dan menambahkan jadwal revalidation
- Revalidasi multi-provider bertingkat + guard scheduler

</details>

<details markdown="1">
<summary><strong>Versi 2.6.4</strong></summary>

<br/>

- Sinkronisasi Custom Notes ke HomeScreen
- Tambah render Custom Notes kategori 01 dan 02
- Menjamin konsistensi informasi penting

</details>

<details markdown="1">
<summary><strong>Versi 2.6.3</strong></summary>

<br/>

- Fokus stabilitas & pembersihan akhir PDF viewer + perbaikan lintas modul
- Perbaikan crash notifikasi firebase
- Perbaikan Build gagal ekstensi Matrix4
- Penyederhanaan controller & callback
- Rewrite terstruktur + scroll aman

</details>

<details markdown="1">
<summary><strong>Versi 2.6.2</strong></summary>

<br/>

- Refactor & finalisasi arsitektur PDF + telemetry tambahan
- Prefetch hingga 8 PDF Warta
- Penggunaan telemetry untuk pemantau kegagalan inisialisasi aplikasi
- Perbaikan build berlebih saat aplikasi dijalankan

</details>

<details markdown="1">
<summary><strong>Versi 2.6.1</strong></summary>

<br/>

- Ekstensi caching & observability
- Penerapan SWR secara menyeluruh dalam pengolahan cache
- Analisis kinerja aplikasi dalam Dashboard Admin
- Fallback menggunakan pembaca lokal jika pembaca webview gagal dimuat

</details>

<details markdown="1">
<summary><strong>Versi 2.6.0</strong></summary>

<br/>

- Fondasi fitur infra kinerja & offline
- Antrian operasi dokumen/kategori + flush otomatis saat online
- Penambahan fitur Prefetch untuk warta acara
- Grace startup
- Penerapan SWR untuk pengelola cache
- Penundaan informasi offline untuk kasus false offline
- Perbaiki banner indikasi offline menyebabkan flicker
- UX offline diawal pembukaan aplikasi

</details>

<details markdown="1">
<summary><strong>Versi 2.5.2</strong></summary>

<br/>

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
