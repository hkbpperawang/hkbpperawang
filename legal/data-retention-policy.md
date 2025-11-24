# KEBIJAKAN RETENSI DATA
## APLIKASI HKBP PERAWANG

**Terakhir diperbarui: 25 November 2025**

---

## 1. PENGANTAR

Kebijakan Retensi Data ini menjelaskan berapa lama kami menyimpan data Anda, bagaimana kami melakukan backup, dan kapan data akan dihapus. Kebijakan ini adalah bagian dari komitmen kami terhadap transparansi dan perlindungan privasi pengguna.

---

## 2. JENIS DATA DAN PERIODE RETENSI

### 2.1. Data Pengguna Admin/Editor

#### a) **Data Akun**
- **Jenis**: Nama, email, nomor telepon, foto profil
- **Retensi**: Selama akun aktif + **4 bulan** setelah akun tidak aktif
- **Automatic Deletion**: Akun yang tidak digunakan selama **4 bulan berturut-turut** akan otomatis dinonaktifkan dan data akan dihapus
- **Pemberitahuan**: Admin/Editor akan diberi tahu via email 30 hari sebelum penghapusan

#### b) **Data Aktivitas**
- **Jenis**: Log aktivitas dashboard, konten yang dibuat/diedit, waktu login
- **Retensi**: **90 hari** (3 bulan)
- **Tujuan**: Audit trail dan keamanan
- **Penghapusan**: Otomatis setelah 90 hari

#### c) **Data Autentikasi**
- **Jenis**: Session tokens, refresh tokens
- **Retensi**: **7 hari** untuk session token, **30 hari** untuk refresh token
- **Penghapusan**: Otomatis saat expired atau saat logout

---

### 2.2. Data Konten Aplikasi

#### a) **Warta dan Dokumen PDF**
- **Retensi**: **Permanen** (disimpan sebagai arsip gereja)
- **Backup**: Included in regular backups
- **Penghapusan**: Hanya jika ada permintaan resmi dari pimpinan gereja

#### b) **Artikel Blog dan Renungan**
- **Retensi**: **Permanen** (kecuali dihapus oleh Admin atau penulis)
- **Backup**: Included in regular backups
- **Penghapusan**: Dapat dihapus atas permintaan penulis atau Admin

#### c) **Jadwal Ibadah**
- **Retensi**: **1 tahun** setelah tanggal acara
- **Backup**: 3 bulan
- **Penghapusan**: Otomatis setelah 1 tahun

#### d) **Foto dan Video Kegiatan**
- **Retensi**: **Permanen** (arsip dokumentasi gereja)
- **Backup**: Included in regular backups
- **Penghapusan**: Hanya atas permintaan pimpinan gereja atau jika melanggar privasi seseorang

---

### 2.3. Data Analytics dan Log

#### a) **Log Error dan Crash Reports**
- **Jenis**: Stack traces, error messages, device info
- **Retensi**: **1 bulan** (30 hari)
- **Layanan**: Sentry, Firebase Crashlytics
- **Penghapusan**: Otomatis setelah 30 hari
- **Tujuan**: Debugging dan perbaikan bug

#### b) **Analytics Data**
- **Jenis**: Page views, user behavior, session duration
- **Retensi**: **14 bulan** (sesuai default Google Analytics)
- **Layanan**: Google Analytics, Firebase Analytics
- **Anonimisasi**: IP address di-anonimkan setelah 24 jam

#### c) **Performance Monitoring**
- **Jenis**: App performance metrics, network latency, screen load times
- **Retensi**: **90 hari** (3 bulan)
- **Layanan**: Firebase Performance Monitoring
- **Penghapusan**: Otomatis setelah 90 hari

---

### 2.4. Data Cache Lokal

#### a) **Data Aplikasi Mobile**
- **Cache Umum**: **6 jam** (default)
- **Cache Kritis**: **7 hari**
- **Cache Gambar**: **3 hari**
- **Cache PDF/Dokumen**: **14 hari**
- **Penghapusan**: Otomatis berdasarkan expiry, atau manual melalui Settings → Hapus Cache

#### b) **Data Browser (Web Version)**
- **Session Storage**: **Sampai tab/browser ditutup**
- **Local Storage**: **30 hari**
- **Cookies**: Lihat Kebijakan Cookie untuk detail lengkap
- **Penghapusan**: Manual via browser settings atau automatic expiry

---

## 3. KEBIJAKAN BACKUP

### 3.1. Frekuensi Backup
- **Database Utama (Firestore)**: **Harian** (automatic)
- **File Storage (PDF, gambar)**: **Mingguan**
- **Konfigurasi Aplikasi**: **Bulanan**
- **Full System Backup**: **Bulanan**

### 3.2. Retensi Backup
- **Backup Harian**: Disimpan selama **30 hari**
- **Backup Mingguan**: Disimpan selama **90 hari** (3 bulan)
- **Backup Bulanan**: Disimpan selama **1 tahun**
- **Archive Backup**: Backup tahunan disimpan **permanen** (untuk arsip gereja)

### 3.3. Lokasi Backup
- **Primary**: Firebase Storage (region: us-central1 dan asia-southeast1)
- **Secondary**: Google Drive (encrypted)
- **Tertiary**: External hard drive (offline backup untuk disaster recovery)

### 3.4. Keamanan Backup
- Semua backup **dienkripsi** menggunakan AES-256
- Access control: Hanya Tim Multimedia yang memiliki akses
- Backup offline disimpan di lokasi fisik yang aman

---

## 4. PENGHAPUSAN DATA

### 4.1. Penghapusan Otomatis
Data berikut akan **otomatis dihapus** berdasarkan periode retensi:

| Jenis Data | Periode Retensi | Automatic Deletion |
|------------|----------------|-------------------|
| Session tokens | 7 hari | ✅ Ya |
| Error logs | 30 hari | ✅ Ya |
| Performance metrics | 90 hari | ✅ Ya |
| Jadwal lama | 1 tahun | ✅ Ya |
| Akun tidak aktif | 4 bulan | ✅ Ya (dengan pemberitahuan) |
| Cache aplikasi | Varies (6 jam - 14 hari) | ✅ Ya |

### 4.2. Penghapusan Manual atas Permintaan
Anda dapat meminta penghapusan data melalui:
- **Email**: kontak@hkbpperawang.org
- **Subject**: "Data Deletion Request - [Nama Anda]"

**Informasi yang Diperlukan**:
- Nama lengkap
- Email yang terdaftar
- Jenis data yang ingin dihapus
- Alasan penghapusan (opsional)

**Timeline**:
- **Konfirmasi**: Dalam 2 hari kerja
- **Penghapusan**: Dalam 7 hari kerja setelah konfirmasi
- **Pemberitahuan**: Email konfirmasi setelah data dihapus

### 4.3. Data yang Tidak Dapat Dihapus
Beberapa data **tidak dapat dihapus** karena alasan legal, arsip, atau operasional:

❌ **Warta dan dokumen resmi gereja** (arsip permanen)  
❌ **Data transaksi atau log audit** (required by law)  
❌ **Data yang sudah di-anonimkan** (tidak lagi identifiable)  
❌ **Backup arsip tahunan** (sampai periode retensi backup selesai)

Namun, kami dapat **meng-anonimkan** data Anda sehingga tidak lagi dapat diidentifikasi.

---

## 5. ANONIMISASI DAN PSEUDONIMISASI

### 5.1. Anonimisasi
Untuk data analytics dan statistik, kami **meng-anonimkan** data agar tidak dapat dilacak kembali ke individu:

- **IP Address**: Di-hash atau di-anonimkan setelah 24 jam
- **Device ID**: Di-hash untuk analytics
- **User behavior**: Aggregated dan tidak terkait dengan identitas personal

### 5.2. Pseudonimisasi
Untuk data yang perlu dilacak tapi tetap privat, kami menggunakan **pseudonimisasi**:
- Menggunakan ID unik (UUID) alih-alih nama
- Data identitas disimpan terpisah dari data aktivitas
- Mapping antara pseudonym dan identitas asli hanya dapat diakses oleh authorized personnel

---

## 6. TRANSFER DAN PENYIMPANAN DATA

### 6.1. Lokasi Penyimpanan Data
Data disimpan di **server Firebase** yang berlokasi di:
- **us-central1** (Iowa, Amerika Serikat)
- **asia-southeast1** (Singapura)

**Compliance**: Firebase memenuhi standar keamanan internasional (ISO 27001, SOC 2, dll)

### 6.2. Transfer Data Internasional
Dengan menggunakan aplikasi, Anda menyetujui transfer data Anda ke server di luar Indonesia. Kami memastikan bahwa transfer data dilakukan dengan:
- **Enkripsi in-transit** (TLS 1.3)
- **Enkripsi at-rest** (AES-256)
- **Compliance** dengan GDPR dan standar privasi internasional

---

## 7. AKSES DAN PORTABILITAS DATA

### 7.1. Hak Akses Data
Anda memiliki hak untuk:
- ✅ Mengakses data pribadi yang kami simpan tentang Anda
- ✅ Mendapatkan salinan data Anda
- ✅ Meminta koreksi data yang tidak akurat
- ✅ Meminta penghapusan data (dengan batasan tertentu)
- ✅ Meminta portabilitas data ke layanan lain

### 7.2. Cara Mengajukan Permintaan
Kirim email ke: kontak@hkbpperawang.org  
**Subject**: "Data Access Request - [Nama Anda]"

Kami akan merespons dalam **maksimal 7 hari kerja** dan menyediakan data dalam format **JSON atau CSV**.

---

## 8. KEAMANAN PENYIMPANAN DATA

### 8.1. Langkah Keamanan
- **Enkripsi**: AES-256 untuk data at-rest, TLS 1.3 untuk data in-transit
- **Access Control**: Role-based access (hanya Admin/Tim Multimedia yang memiliki akses)
- **Firewall**: Firebase Security Rules untuk database
- **Monitoring**: Real-time monitoring untuk akses tidak sah
- **Audit Logs**: Logging semua akses ke data sensitif

### 8.2. Tanggung Jawab Tim Multimedia
Tim Multimedia HKBP Perawang bertanggung jawab untuk:
- ✅ Melakukan backup rutin sesuai jadwal
- ✅ Memverifikasi integritas backup secara berkala
- ✅ Menjaga keamanan credentials dan encryption keys
- ✅ Merespons incident keamanan dalam 24 jam
- ✅ Melakukan disaster recovery testing minimal 2x setahun

---

## 9. KEBIJAKAN KHUSUS

### 9.1. Data Anak-Anak
Meskipun aplikasi ramah untuk anak-anak, kami **tidak secara khusus mengumpulkan data dari anak di bawah 13 tahun**. Jika kami menemukan bahwa data anak di bawah 13 tahun telah dikumpulkan tanpa persetujuan orang tua, data akan segera dihapus.

### 9.2. Data Sensitif
Kami **TIDAK mengumpulkan dan menyimpan** data sensitif seperti:
- Informasi kesehatan
- Data keuangan atau kartu kredit
- Informasi politik atau afiliasi partai
- Data biometrik

### 9.3. Data Jemaat untuk Pelayanan
Jika jemaat memberikan data untuk pelayanan pastoral (konseling, kunjungan, dll), data tersebut:
- Disimpan secara **terpisah** dari database aplikasi
- Hanya diakses oleh **pendeta dan pima gereja**
- Retensi sesuai dengan **kebijakan gereja** (tidak terkait dengan aplikasi)

---

## 10. PERUBAHAN KEBIJAKAN

Kami dapat mengubah Kebijakan Retensi Data ini untuk:
- Mematuhi perubahan hukum dan regulasi
- Meningkatkan praktik keamanan data
- Menyesuaikan dengan perubahan teknologi

Perubahan akan diberitahukan melalui:
- Notifikasi dalam aplikasi
- Email kepada Admin/Editor terdaftar
- Pengumuman di website

---

## 11. KONTAK

Untuk pertanyaan tentang retensi data atau untuk mengajukan permintaan terkait data, hubungi:

- **Email**: kontak@hkbpperawang.org
- **WhatsApp**: +1 (220) 222-4575
- **Alamat**: Jl. Gajah Tunggal, Tualang, Kec. Tualang, Kabupaten Siak, Riau 28772
- **Website**: https://www.hkbpperawang.org

**Data Protection Officer**: Tim Multimedia HKBP Perawang

---

## PENUTUP

Kebijakan Retensi Data ini dirancang untuk menyeimbangkan kebutuhan operasional gereja dengan perlindungan privasi Anda. Kami berkomitmen untuk mengelola data Anda dengan bertanggung jawab dan transparan.

---

**© 2025 Gereja HKBP Perawang. All Rights Reserved.**
