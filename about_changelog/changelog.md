# 📜 **Changelog / Catatan Rilis**

Lihat riwayat pembaruan dan penambahan fitur pada aplikasi di bawah ini.

## Rilis Publik

<details>
  <summary><h2>Cek Detail</h2></summary>
<br/>

  <details>
    <summary><h3><strong>Versi 2.10.10 (Terbaru)</strong></h3></summary>
    <h3>Fitur Baru</h3>
    <ul>
      <li>Modul Kidung Nyanyian: Fitur lengkap untuk akses kidung digital, unduhan offline, navigasi keypad, pencarian lirik, zoom gesture, dan bagikan gambar lirik</li>
      <li>Sistem Notifikasi: Penjadwalan otomatis, in-app messaging, histori lengkap (akses admin)</li>
      <li>Stiker & Pengumuman: Teks berjalan multi-item dengan pengaturan warna dan kecepatan</li>
      <li>Mode Offline-First: Cache pintar dengan sinkronisasi otomatis di latar belakang</li>
      <li>Postingan: Penambahan beberapa kategori Postingan</li>
    </ul>
    <h3>Perbaikan & Peningkatan</h3>
    <ul>
      <li>Perbaikan carousel artikel unggulan, filter kategori, dan sistem cache offline</li>
      <li>Optimisasi performa dan startup aplikasi</li>
      <li>Perbaikan stabilitas (crash PDF, koneksi internet, splash screen)</li>
      <li>Peningkatan antarmuka pengguna dengan desain modern</li>
      <li>Perbaikan warta & PDF dengan prefetch otomatis</li>
      <li>Peningkatan sistem tim dan notifikasi</li>
    </ul>
    <h3>Keamanan & Kompatibilitas</h3>
    <ul>
      <li>Firebase App Check untuk proteksi API</li>
      <li>Kompatibilitas penuh Android 15 (API Level 35)</li>
      <li>Migrasi ke Play Integrity API</li>
    </ul>
    <h4>Bug Yang Diketahui</h4>
    <ul>
      <li>Notifikasi tidak berkerja (sedang dalam pengerjaan)</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.7.0</summary>
    <ul>
      <li>Ekstensi offline-first ke semua tabel jadwal & Partangiangan.</li>
      <li>Konsistensi jadwal & cache offline untuk tabel.</li>
      <li>Jadwal Mingguan & Sermon Parhalado: Dukungan cache instan dan update latar belakang</li>
      <li>Info Banner Partangiangan render cache sinkron lebih awal</li>
      <li>Jadwal Ibadah & Jadwal PA/PHD: Caching offline (ambil instan dari Manajemen lalu update di latar belakang)</li>
      <li>fallback offline pakai cache</li>
      <li>Konversi widget jadwal untuk manajemen cache & pembaharuan instan</li>
      <li>Halaman Home & Jadwal: Pemanggilan diperbarui</li>
      <li>Perubahan konstruktor Jadwal Ibadah bersifat breaking minor</li>
      <li>Masa kedaluwarsa cache jadwal: 7 hari</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.5.1</summary>
    <ul>
      <li>Perbaikan lag pada saat kali pertama install aplikasi</li>
      <li>Perbaikan postingan blog yang menampilkan simbol-simbol</li>
      <li>blokir kode iklan web pada tampilan postingan android</li>
      <li>perbaikan fitur stiker teks berjalan</li>
      <li>perubahan indikator offline</li>
      <li>Perubahan struktur penampil stiker teks berjalan</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.4.17</summary>
    <ul>
      <li>Perbaikan pengolahan cache yang menyebabkan aplikasi terhenti tiba-tiba</li>
      <li>Peningkatan peforma</li>
      <li>Penyegaran banner informasi</li>
      <li>Penambahan banner untuk keterangan halaman</li>
      <li>Penambahan Stiker informasi teks berjalan dibawah header</li>
      <li>Optimasi pengolahan cache</li>
      <li>Perbaikan beberapa bug</li>
      <li>Pengolahan Stiker dan Banner informasi untuk Admin</li>
      <li>Monitor crash pada user</li>
      <li>Optimasi pengolahan tim untuk jenis devisi</li>
      <li>Optimasi pengolahan pembaca PDF bawaan dan webview</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.4.11</summary>
    <ul>
      <li>Peningkatan keamanan dan logging</li>
      <li>Optimasi kinerja aplikasi</li>
      <li>Penambahan fitur layar tetap menyala saat membaca warta di pengaturan</li>
      <li>Penambahan penampil PDF webview di pengaturan aplikasi</li>
      <li>Penyederhanaan tampilan</li>
      <li>Penjadwalan notifikasi (untuk Admin)</li>
      <li>Optimasi pengelolaan tim dan kategori tim</li>
      <li>Peningkatan stabilitas</li>
      <li>Perubahan UI halaman warta-acara</li>
      <li>Perbaikan widget team yang tiba-tiba berpindah acak</li>
      <li>Cache hanya pada alur internal untuk keamanan</li>
    </ul>
  </details>
  <details>
    <summary>versi 2.4.10</summary>
    <ul>
      <li>Tambah guard ekstra agar tidak ada akses ke controller sebelum siap saat frame awal</li>
      <li>Optimasi pembaca pdf lokal</li>
      <li>Penambahan fitur membuka pdf secara eksternal</li>
      <li>Redesain halaman warta acara</li>
      <li>Otomasi ikon warta acara sesuai jenis file</li>
      <li>Validasi url pdf untuk webview</li>
      <li>Memisahkan cache domain ke box khusus</li>
      <li>Menambah migrasi ringan</li>
      <li>Perbaikan beberapa bug</li>
    </ul>
  </details>
  <details>
    <summary>versi 2.4.1 - 2.4.9</summary>
    <ul>
      <li>Redesign UI Pengaturan</li>
      <li>Otomasi Penghapus cache lebih dari 2 minggu</li>
      <li>Perbaikan beberapa bug dan crash</li>
      <li>Konfigurasi Ulang Team agar konsisten</li>
      <li>Hindari rebuild team jika sudah di kunci oleh Admin</li>
      <li>Perbaikan kategori team yang tiba-tiba hilang</li>
      <li>Penambahan opsi check box untuk tim (admin)</li>
      <li>Redesain pengaturan tim di admin dashboard</li>
      <li>Ganti pemanggilan API usang</li>
      <li>Penghapusan pencatatan log yang tidak diperlukan</li>
      <li>Konsistensi cache untuk semua halaman</li>
      <li>Optimasi pengkompres data untuk sinkronisasi latar belakang</li>
      <li>Redesign indikator offline</li>
      <li>Otomatisasi pengiriman informassi crash pada user</li>
      <li>Perbaikan strukrur penyimpanan tim</li>
    </ul>
  </details>
  <details>
    <summary>versi 2.2.2 - versi 2.4.0</summary>
    <ul>
      <li>Integrasi dropbox dan google drive untuk penyimpanan online</li>
      <li>Perubahan metode pengambilan postingan</li>
      <li>Fitur edit post khusus mobile</li>
      <li>Fitur pendeteksi perubahan postingan</li>
      <li>Redesign Sidebar Global dan Admin dashboard</li>
      <li>Pemecahan beberapa file menjadi bagian-bagian kecil</li>
      <li>Penguraian kinerja berat menjadi beberapa tahap</li>
      <li>Mengurangi definisi animasi untuk mengurangi beban GPU/CPU</li>
      <li>optimasi cache, pembersihan PDF, Remote Config fetch, dan priming data awal</li>
    </ul>
  </details>
  <details>
    <summary>versi 2.2.1</summary>
    <ul>
      <li>Integrasi crashlytic untuk non-fatal crash</li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </details>
  <details>
    <summary>versi 2.2.0</summary>
    <ul>
      <li>Perubahan struktur metode implementasi Admin</li>
      <li>Sleksi User (untuk Admin)</li>
      <li>Penambahan role contributor untuk admin</li>
      <li>Redesign Profil Admin</li>
      <li>Peningkatan keamanan admin</li>
      <li>integrasi keamanan google admin</li>
    </ul>
  </details>
  <details>
    <summary>Versi 2.1.0 - 19 Agustus 2025</summary>
    <ul>
      <li>Perubahan arsitektur pengiriman notifikasi</li>
      <li>Penjadwalan notifikasi</li>
      <li>Optimasi dan konsistensi cache setiap halaman</li>
      <li>Menambahkan kompibilitas edge-to-edge</li>
      <li>mengganti depedensi usang</li>
      <li>perbaikan bug</li>
      <li>Perubahan struktur header</li>
      <li>Menghapus entri cache korup saat gagal dekompresi</li>
      <li>Redesign layar login</li>
      <li>Perbaikan izin FCM</li>
      <li>Integrasi dengan Github action</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.58 - 17 Agustus 2025</summary>
    <ul>
      <li>Perbaikan force close pada versi 1.0.57</li>
      <li>Perbaikan fitur pencarian pada halaman blog</li>
      <li>Optimasi Edge-to-edge</li>
      <li>Penghapusan metode usang</li>
      <li>Perbaikan bug</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.57 - 15 Agustus 2025</summary>
    <ul>
      <li>Perbaikan tombol "kembali ke atas"</li>
      <li>Perubahan halaman Tentang aplikasi</li>
      <li>Desain ulang header Aplikasi</li>
      <li>Perbaikan beberapa bug</li>
      <li>Pengoptimalan kode aplikasi</li>
      <li>Penanganan Admin dashboard</li>
      <li>Penambahan fitur ubah password untuk Admin</li>
      <li>Penambahan fitur sinkronisasi Google untuk Admin</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.56 - 07 Agustus 2025</summary>
    <ul>
      <li>Perbaikan bug dan peningkatan performa</li>
      <li>Penambahan metode scrap PDF dari web dan GDrive</li>
      <li>Perubahan UI Blog</li>
      <li>Penambahan Fitur Postingan Unggulan</li>
      <li>Optimasi pembuka PDF</li>
      <li>Optimasi metode unduh PDF</li>
      <li>Perbaikan Cache Info Partangiangan</li>
      <li>Perbaikan beberapa bug</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.55 - 02 Agustus 2025</summary>
    <ul>
      <li>Perbaikan bug dan peningkatan performa</li>
      <li>Penambahan kemampuan memuat gambar pada notifikasi</li>
      <li>Pengoptimalan metode cache</li>
      <li>Penambahan Jadwal Partangiangan Weyk</li>
      <li>Penghapusan sisi samping Penampil PDF</li>
      <li>Pengoptimalan Pembacaan PDF</li>
      <li>Meringankan halaman utama aplikasi</li>
      <li>Penambahan keamanan AppCheck</li>
      <li>Perbaikan Bug</li>
      <li>Perbaikan tombol aksi notifikasi</li>
      <li>Pembaharuan bahasa pendukung</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.50 - 20 Juni 2025</summary>
    <ul>
      <li>Perbaikan bug dan peningkatan performa</li>
      <li>Perbaikan edge-to-edge</li>
      <li>Integrasi Play Integrity</li>
      <li>dan banyak lagi</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.43 - 28 April 2025</summary>
    <ul>
      <li>Fetch Warta Acara dengan Metode Baru mengikuti struktur web</li>
      <li>Penambahan Sistem notifikasi dengan fitur Tombol</li>
      <li>Perbaikan direct sistem notifikasi</li>
      <li>Perbagian Bug</li>
      <li>Penyimpanan Dokumen tersendiri</li>
      <li>Pengoptimalan Pembuka Pdf</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.37 - 1.0.38</summary>
    <ul>
      <li>Perbaikan Fug</li>
      <li>Perbaikan cache lokal</li>
      <li>Perbaikan snkronasi Jadwal</li>
      <li>Penambahan metode refresh di halaman warta</li>
      <li>Fitur Pengurutan kategori team</li>
      <li>Perbaikan logika halaman info huria</li>
      <li>Fitur Perbaikan sinkronasi Jadwal dan Team dengan firebase</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.36 - 1.0.37</summary>
    <ul>
      <li>Perbaikan Bug</li>
      <li>Memperbaiki fitur cache</li>
      <li>Menutup akses pendaftaran user</li>
      <li>Sinkronasi data team dengan firebase</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.35 - 1.0.36</summary>
    <ul>
      <li>Perbaikan bug</li>
      <li>Migrasi penyimpanan dari hive ke hive_ce</li>
      <li>Perbaikan Halaman Dokumen</li>
      <li>Integrasi Dokumen di Halaman Dokumen Dengan ImageKit</li>
      <li>Menetapkan sidebar hanya untuk warta-acara</li>
      <li>Memperbaiki gambar terbalik pada sidebar</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.34 - 1.0.35</summary>
    <ul>
      <li>Perbaikan bug</li>
      <li>Integrasi ImageKit sebagai media utama penyimpanan file</li>
      <li>Perbaikan fitur Analystik</li>
      <li>Perbaikan integrasi firebase</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.30 - 1.0.34</summary>
    <ul>
      <li>Meningkatkan stabilitas</li>
      <li>Mengubah metode fetch dokumen dan warta hanya oleh admin</li>
      <li>Pembaharuan otomatis dokumen</li>
      <li>Perbaikan bug</li>
      <li>Penambahan fitur agara dapat di akses dalam mode offline</li>
      <li>Sinkronasi otomatis jika koneksi terdeteksi</li>
      <li>Menambah perijinan perangkat agar dapat mengunduh warta atau dokumen.</li>
      <li>Perbaikan halaman blog untuk mengambil dari web.</li>
      <li>Merapikan detail isi post pada blog.</li>
      <li>Menambahkan Imagekit sebagai penyimpanan online.</li>
      <li>Penambahan database warta untuk menangkap dari web</li>
      <li>Memperbaiki metode dokumen</li>
      <li>Filter postingan yang di tangkap dari web pada data dokumen.</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.30 - 1.0.35</summary>
    <ul>
      <li>Perbaikan Bug</li>
      <li>Integrasi ImageKit sebagai Media Library</li>
      <li>Perbaikan fitur Analistik</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.25 - 1.0.30</summary>
    <ul>
      <li>Penambahan fitur popup pada foto info huria, fungsionaris, dan tim digital</li>
      <li>Penambahan menu Dokumen pada Sidebar</li>
      <li>Menghapus metode Signup</li>
      <li>Menambah fitur penambahan user hanya oleh Admin</li>
      <li>Perbaikan splash screen terpotong pada Android 14</li>
    <li>Perbaikan bug</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.1 - 1.0.25</summary>
    <ul>
      <li>Perbaikan bug</li>
      <li>Pengelompokan halaman warta-acara berdasarkan kegiatan acara</li>
      <li>Metode fetch warta agar dapat mendeteksi postingan terbaru di website.</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.1</summary>
    <ul>
      <li>Penambahan fitur analistik.</li>
      <li>Perbaikan beberapa bug.</li>
      <li>Optimisasi halaman warta acara setiap kali dibuka</li>
      <li>penambahan tabel “hari” dalam jadwal kegiatan.</li>
      <li>peningkatan keamanan.</li>
      <li>penambahan sosial media facebook, youtube, dan instagram di halaman kontak</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.0</summary>
    <ul>
      <li>Perbaikan beberapa bug.</li>
      <li>penambahan pop up jika versi baru tersedia.</li>
      <li>melenngkapi data sintua dan halaman fungsionaris</li>
      <li>perbaikan info team agar dapat memunculkan pop up foto.</li>
    </ul>
  </details>

  <details>
  <summary>Versi 1.0.0</summary>
    <ul>
      <li>Penambahan Halaman: Info Huria, Warta Jemaat, Jadwal Kegiatan, Blog, Info Aplikasi, Kebijakan Privasi, Fungsionaris, Tim Digital.</li>
      <li>Pemuatan Warta Jemaat menggunakan web_view ke situs https://www.hkbpperawang.org.</li>
      <li>Penanganan Notifikasi agar dapat dikirim dan diterima secara real time.</li>
      <li>Penambahan fungsi jadwal kegiatan agar dapat di ubah tanpa pembaharuan</li>
      <li>Penambahan fungsi jadwal ibadah</li>
      <li>penambahan fitur user</li>
      <li>penambahan fitur statistik huria untuk memunculkan di halaman info huria.</li>
    </ul>
  </details>
</details>

---

## Rilis Beta
<details>
  <summary>Cek Detail</summary>
  <br/>

  <details>
    <summary>Versi 2.10.2 <strong>(Terbaru)</strong></summary>
    <ul>
      <li>Integrasi layanan Sentry pada Aplikasi</li>
      <li>Perubahan UI halaman "Kidung Nyanyian" dan "Isi Nyanyian"</li>
      <li>Menambah fungsi Bagikan Teks dan Bagikan Gambar untuk "Isi Nyanyian"</li>
      <li>Menonaktifkan Keypada "Kidung Nyanyian" jika sumber belum di unduh</li>
      <li>Penyesuaian Ukuran Teks "Isi Nyanyian"</li>
      <li>Menambah fitur gesture untuk zoom in dan zoom out pada halaman "Kidung Nyanyian</li>
      <li>Memperluas fungsi Capture menjadi Long Capture agar dapat menangkap seluruh isi halaman "Isi nyanyian"</li>
      <li>Menambahkan Fungsi Download pada Fitur "Bagikan Gambar"</li>
      <li>Penyimpanan status selesai unduh per folder nyanyian sehingga aplikasi tahu kapan berkas sudah lengkap meski setelah restart</li>
      <li>Pesan keberhasilan di halaman Kidung Nyanyian yang muncul otomatis ketika semua berkas telah siap dipakai.</li>
      <li>Hook Crashlytics yang sudah ada kini ikut meneruskan error ke Sentry</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.10.1</summary>
    <ul>
      <li>Penambahan Halaman Publik "Kidung Nyanyian" yang memuat daftar lagu dari GitHub dengan dukungan unduhan offline</li>
      <li>Penambahan menu sidebar dan fitur keypad pada halaman "Kidunng Nyanyian"</li>
      <li>Penambahan Rute "Kidung Nyanyian" pada konfigurasi internal</li>
      <li>Membuat endpoint menjadi raw agar mudah dalam pengunduhan</li>
      <li>Menghapus Interceptor header dan menghormati header khusus agar log tidak membocorkan token github</li>
      <li>Integrasi Judul dan jumlah kidung nyanyian pada firestore</li>
      <li>Integrasi Backend Admin untuk mengelola jenis kidung nyanyian</li>
    </ul>
  </details>
  
  <details>
    <summary>Versi 2.9.2</summary>
    <ul>
      <li>Label overlay lingkungan pada build non-produksi dihapus sehingga tampilan debug kembali bersih tanpa memengaruhi fitur debug, logging, maupun konfigurasi lingkungan yang lain.</li>
      <li>Pengiriman notifikasi manual kini mencoba beberapa region Cloud Functions sesuai konfigurasi</li>
      <li>Menghapus file-file Kritis dari sumber proyek untuk keamanan.</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.9.1 <strong></strong></summary>
    <ul>
      <li>Pembersihan cache memastikan file lokal diregenerasi saat versi server</li>
      <li>Prefetch otomatis Partangiangan dijalankan di latar belakang</li>
      <li>Cloud Function baru untuk mengirim FCM secara aman melalui backend dengan validasi peran admin</li>
      <li>Pemuatan cache Partangiangan segera saat startup sehingga kartu langsung menampilkan data lokal</li>
      <li>Inisialisasi Partangiangan kini memakai satu jalur fallback yang mengutamakan berkas lokal</li>
      <li>Pemuatan snapshot fungsionaris dari cache Hive/DataCache segera setelah provider aktif</li>
      <li>Tombol "Info Partangiangan Weyk" kini selalu aktif tanpa pesan unduhan</li>
      <li>Tampilan penuh Partangiangan menampilkan banner "Harap Hubungkan ke Internet untuk mengambil Info Partangiangan" dan menonaktifkan tombol unduh ketika perangkat sedang offline.</li>
      <li>Tombol **Clear Cache** di dasbor menaikkan versi cache di Firestore sehingga semua perangkat memaksa sinkron ulang dan mengosongkan salinan lama.</li>
      <li>FCM dan utilitas terkait kini memakai Firebase Cloud Functions sehingga tidak lagi membaca kredensial service account dari bundle aplikasi</li>
      <li>Penyederhanaan penggunaan Firebase API</li>
      <li>Peningkatan keamanan file-file yang dapat diakses publik</li>
      <li>Jadwal Ibadah, Daftar Dokumen, dan Kategori Post kini menyimpan cache dengan metode yang sama</li>
      <li>Rutinitas warmup pasca-frame kini melibatkan `TeamProvider` untuk memicu revalidasi diam-diam ketika perangkat online</li>
      <li>Penambahan kemampuan akses warta dalam mode offline menggunakan pembaca PDF lokal</li>
      <li>Seluruh dialog dan snackbar lintas modul sudah menyimpan navigator/messenger sebelum operasi async</li>
      <li>Penanda lingkungan (`Banner`) dibungkus dengan `Directionality` sehingga overlay label tidak lagi memicu runtime error</li>
      <li>Tombol "Info Partangiangan Weyk" di beranda langsung membuka cache yang tersedia sehingga shimmer hanya muncul ketika aplikasi benar-benar mengambil data terbaru</li>
      <li>Halaman Warta kembali menampilkan daftar arsip ketika perangkat luring karena provider kini selalu mundur ke cache lokal sebelum menghubungi Firestore</li>
      <li>Konfigurasi lint Functions</li>
      <li>Pengubahan Metode CACHE-FIRST untuk semua widget yanng mengambil data dari Firebase.</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.9.0</summary>
    <ul>
      <li>Skeleton shimmer global untuk halaman di tab utama</li>
      <li>Penyesuaian template shimmer untuk grid, list, , detail</li>
      <li>Resolusi jalur lokal Partangiangan kini mengenali path Windows dan URI</li>
      <li>Kartu "Info Partangiangan Weyk" selalu aktif menampilkan cache awal</li>
      <li>Fallback shimmer kartu Partangiangan kini ditampilkan maksimal selama validasi ulang jaringan</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.8.6</summary>
    <ul>
      <li>Perbaikan loop saat data offline</li>
      <li>Normalisasi pengambilan URL partangiangan</li>
      <li>Widget smoke test diperbarui agar mengikuti alur bootstrap</li>
      <li>Penambahan fallback agar perangkat tidak berhenti di splash screen</li>
      <li>Halaman Blog dan Warta Acara memaksa pengecekan koneksi pasca-frame</li>
      <li>Pembersihan indikator koneksi di main_page dan dipindahkan ke header</li>
      <li>Koreksi deteksi konektivitas ganda</li>
      <li>Banner offline kini menunggu setidaknya 3 detik setelah masa grace berakhir</li>
      <li>Kartu jadwal Partangiangan di beranda kini tetap aktif menggunakan versi cache</li>
      <li>Inisialisasi kartu Partangiangan memprioritaskan cache sinkron dan menampilkan indikator loading sampai data siap</li>
      <li>Penyesuaian banner indikator offline</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.8.5</summary>
    <ul>
      <li>Update versi dart, kotlin, AGP</li>
      <li>Perbaikan aplikasi berhenti di flash screen</li>
      <li>Perbaikan kotlin</li>
      <li>Migrasi lanjutan build.gradle.kts</li>
      <li>Integrasi arsip native-debug untuk keperluan playconsole</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.8.4</summary>
    <ul>
      <li>Update framework flutter 3.35.4</li>
      <li>Migrasi sinkron data admin dan editor</li>
      <li>Penggantian metode usang</li>
      <li>Integrasi verifikasi 2 langkah untuk admin dan editor</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.7.1</summary>
    <ul>
      <li>Perbaikan kestabilan unduhan & guard UI</li>
      <li>Crash fatal Null check</li>
      <li>Perbaikan integrasi crashlytics</li>
      <li>Perbaikan metode pengambilan koneksi</li>
      <li>Perbaikan cache file pdf</li>
    </ul>
  </details>
  
  <details>
  <summary>Versi 2.6.5</summary>
  <ul>
    <li>Optimisasi startup offline-first & pengurangan jank.</li>
    <li>Revalidasi ringan jadwal hanya bila koneksi tersedia & data masih dari cache.</li>
    <li>Revalidasi bertahap WartaAcara</li>
    <li>Hapus logging build berulang</li>
    <li> Warmup post-frame kini menerima context untuk akses provider aman dan menambahkan jadwal revalidation</li>
    <li>Revalidasi multi-provider bertingkat + guard scheduler</li>
  </ul>
  </details>

  <details>
    <summary>Versi 2.6.4</summary>
    <ul>
      <li>Sinkronisasi Custom Notes ke HomeScreen.</li>
      <li>Tambah render Custom Notes kategori 01 dan 02</li>
      <li>Menjamin konsistensi informasi penting</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.6.3</summary>
    <ul>
      <li>Fokus stabilitas & pembersihan akhir PDF viewer + perbaikan lintas modul.</li>
      <li>Perbaikan crash notifikasi firebase</li>
      <li>Perbaikan Build gagal ekstensi Matrix4</li>
      <li>Penyederhanaan controller & callback</li>
      <li>Rewrite terstruktur + scroll aman</li>
      <li></li>
      <li></li>
      <li></li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.6.2</summary>
    <ul>
      <li>Refactor & finalisasi arsitektur PDF + telemetry tambahan.</li>
      <li>Prefetch hingga 8 PDF Warta</li>
      <li>Penggunaan telemetry untuk pemantau kegagalan inisialisasi aplikasi</li>
      <li>Perbaikan build berlebih saat aplikasi dijalankan</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.6.1</summary>
    <ul>
      <li>Ekstensi caching & observability</li>
      <li>Penerapan SWR secara menyeluruh dalam pengolahan cache</li>
      <li>Analisis kinerja aplikasi dalam Dashboard Admin</li>
      <li>Fallback menggunakan pembaca lokal jika pembaca webview gagal dimuat</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.6.0</summary>
    <ul>
      <li>Fondasi fitur infra kinerja & offline.</li>
      <li>antrian operasi dokumen/kategori + flush otomatis saat online</li>
      <li>Penambahan fitur Prefetch untuk warta acara</li>
      <li>Grace startup</li>
      <li>Penerapan SWR untuk pengeola cache</li>
      <li>Penundaan informasi offline untuk kasus false offline</li>
      <li>Perbaiki banner indikasi offline menyebabkan flicker</li>
      <li>UX offline diawal pembukaan aplikasi</li>
    </ul>
  </details>

  <details>
    <summary>Versi 2.5.2</summary>
    <ul>
      <li>Perbaikan beberapa halaman tertutup sistem navigasi perangkat</li>
      <li>Mengatur jarak bawah halaman secara global</li>
      <li>Pembersihan jarak bawah pada halaman-halaman lokal</li>
    </ul>
  </details>

</details>

## Info Lainnya
Kami menerima Kritik, Masukan, dan Saran Terkait Fitur dan Pengembangan Aplikasi. Bagi Amang Inang yang memiliki Ide, Permintaan terkait aplikasi dapat mengirimkan pesan pada sosial media HKBP Perawang.
<ul>
  <li><strong>Facebook:</strong> https://fb.com/HKBPPerawang</li>
  <li><strong>Instagram:</strong> https://instagram.com/HKBPPerawang</li>
</ul>

Hormat Kami,
- Devisi Digital Tim Multimedia HKBP Perawang
