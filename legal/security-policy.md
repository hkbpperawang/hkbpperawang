# KEBIJAKAN KEAMANAN
## APLIKASI HKBP PERAWANG

**Terakhir diperbarui: 25 November 2025**

---

## 1. KOMITMEN KEAMANAN

Gereja HKBP Perawang berkomitmen untuk melindungi keamanan data dan privasi pengguna. Kami menerapkan langkah-langkah keamanan teknis, administratif, dan fisik untuk melindungi aplikasi dari ancaman cyber dan akses tidak sah.

---

## 2. LANGKAH-LANGKAH KEAMANAN

### 2.1. Keamanan Infrastruktur
- **Cloud Platform**: Firebase (Google Cloud Platform) dengan compliance ISO 27001, SOC 2, GDPR
- **Enkripsi Data**:
  - **In-Transit**: TLS 1.3 untuk semua komunikasi aplikasi-server
  - **At-Rest**: AES-256 encryption untuk data di database
- **Firewall**: Firebase Security Rules untuk kontrol akses database
- **DDoS Protection**: Cloud Armor dan Firebase built-in protection

### 2.2. Keamanan Autentikasi
- **Password Hashing**: bcrypt atau Firebase Auth (SHA-256 + salt)
- **Multi-Factor Authentication (MFA)**: Tersedia untuk Admin/Editor
- **Session Management**: Secure session tokens dengan HttpOnly dan Secure flags
- **Token Expiry**: Session tokens expired dalam 7 hari, refresh tokens dalam 30 hari

### 2.3. Keamanan Aplikasi
- **Input Validation**: Semua input user divalidasi dan di-sanitize
- **XSS Protection**: Content Security Policy (CSP) headers
- **SQL Injection Prevention**: Menggunakan parameterized queries (Firestore tidak rentan terhadap SQL injection)
- **CSRF Protection**: SameSite cookies dan CSRF tokens untuk form submission
- **Code Obfuscation**: Release builds menggunakan obfuscation untuk protect source code

### 2.4. Keamanan API
- **API Key Security**: API keys tidak di-hardcode di client-side code
- **Rate Limiting**: Batasan request untuk prevent abuse
- **Request Signing**: Semua API request di-sign untuk validasi
- **App Check**: Firebase App Check untuk verify legitimate app traffic

---

## 3. MONITORING DAN DETEKSI

### 3.1. Real-Time Monitoring
- **Firebase Security Monitoring**: Automatic detection of suspicious activities
- **Sentry Error Tracking**: Real-time crash and error reporting
- **Analytics Anomaly Detection**: Unusual traffic patterns atau behavior
- **Login Anomaly Detection**: Failed login attempts tracking

### 3.2. Logging dan Audit
- **Access Logs**: Semua akses ke data sensitif di-log
- **Activity Logs**: Admin/Editor activity tracked untuk audit
- **Security Events**: Failed logins, permission denials, API errors
- **Retention**: Logs disimpan selama **30 hari**

---

## 4. PELAPORAN KERENTANAN (RESPONSIBLE DISCLOSURE)

### 4.1. Kebijakan Pelaporan
Kami sangat menghargai kontribusi security researchers dan pengguna yang melaporkan kerentanan keamanan secara bertanggung jawab.

**Jika Anda menemukan kerentanan keamanan**, harap laporkan ke:
- **Email**: kontak@hkbpperawang.org
- **Subject**: "Security Vulnerability Report - CONFIDENTIAL"
- **Enkripsi**: Gunakan PGP jika mungkin (public key tersedia atas permintaan)

### 4.2. Informasi yang Diperlukan
Harap sertakan informasi berikut dalam laporan:
1. **Deskripsi kerentanan**: Jenis kerentanan (XSS, injection, dll)
2. **Steps to Reproduce**: Langkah-langkah detail untuk mereproduksi kerentanan
3. **Impact Assessment**: Tingkat keparahan dan dampak potensial
4. **Proof of Concept**: Screenshot, video, atau kode demonstrasi (jika aman)
5. **Affected Versions**: Versi aplikasi yang terpengaruh
6. **Suggested Fix**: Saran perbaikan (opsional)

### 4.3. Apa yang TIDAK Boleh Dilakukan
Saat melaporkan kerentanan, harap **JANGAN**:
- ❌ Mengakses data pengguna lain atau mencoba mencuri data
- ❌ Melakukan Denial of Service (DoS) attacks
- ❌ Mengumumkan kerentanan ke publik sebelum diperbaiki
- ❌ Menggunakan kerentanan untuk keuntungan pribadi
- ❌ Melakukan social engineering terhadap Admin/Editor atau jemaat

### 4.4. Timeline Respon
- **Acknowledgment**: Maksimal **24 jam** setelah laporan diterima
- **Initial Assessment**: 2-3 hari kerja untuk menilai severity
- **Update Berkala**: Setiap 7 hari sampai kerentanan diperbaiki
- **Fix Deployment**: Varies berdasarkan severity:
  - **Critical**: 1-3 hari
  - **High**: 7-14 hari
  - **Medium**: 30 hari
  - **Low**: 60 hari atau dengan next release
- **Disclosure**: Setelah fix deployed + 90 hari (untuk public disclosure)

### 4.5. Penghargaan untuk Pelapor
Meskipun kami **tidak memiliki bug bounty program** berbayar, kami akan:
- ✅ Mengakui kontribusi Anda dalam **Hall of Fame** (jika Anda setuju)
- ✅ Menambahkan nama Anda di halaman **"Pendukung"** dalam aplikasi (Menu Tentang Aplikasi)
- ✅ Memberikan sertifikat **"Security Contributor"** dari Gereja HKBP Perawang
- ✅ Menyebut Anda dalam **security advisory** (jika Anda setuju)

**Catatan**: Ini adalah program sukarela. Kami sangat menghargai kontribusi Anda untuk kebaikan bersama.

---

## 5. TINGKAT KEPARAHAN (SEVERITY LEVELS)

Kami mengklasifikasikan kerentanan berdasarkan CVSS v3.1:

### **Critical** (CVSS 9.0-10.0)
- Remote Code Execution (RCE)
- Authentication bypass yang memungkinkan takeover akun Admin
- Akses tidak sah ke database penuh
- Massive data breach

### **High** (CVSS 7.0-8.9)
- SQL Injection atau NoSQL Injection
- Cross-Site Scripting (XSS) yang persistent atau dapat steal credentials
- Server-Side Request Forgery (SSRF) dengan impact tinggi
- Access control bypass untuk data sensitif

### **Medium** (CVSS 4.0-6.9)
- Reflected XSS
- CSRF yang berdampak pada data integrity
- Information disclosure minor
- Broken authentication mechanisms

### **Low** (CVSS 0.1-3.9)
- Self-XSS
- Minor information disclosure
- Low-impact CSRF
- Security misconfiguration dengan dampak terbatas

---

## 6. LANGKAH KEAMANAN UNTUK PENGGUNA

### 6.1. Admin/Editor
Jika Anda adalah Admin/Editor, harap ikuti best practices berikut:
- ✅ Gunakan **password yang kuat** (min. 12 karakter, kombinasi huruf, angka, simbol)
- ✅ Aktifkan **Multi-Factor Authentication (MFA)** jika tersedia
- ✅ **Jangan share** credentials dengan siapapun
- ✅ **Logout** setelah selesai menggunakan dashboard
- ✅ Gunakan **perangkat dan jaringan yang aman** saat login
- ✅ **Update aplikasi** ke versi terbaru untuk mendapatkan security patches
- ✅ Laporkan aktivitas mencurigakan segera ke Tim Multimedia

### 6.2. Pengguna Umum
- ✅ **Update aplikasi** secara berkala
- ✅ Jangan install aplikasi dari sumber tidak resmi (sideload APK)
- ✅ Periksa permissions yang diminta aplikasi
- ✅ Gunakan **koneksi internet yang aman** (hindari WiFi publik tanpa VPN)
- ✅ Laporkan konten atau aktivitas mencurigakan

---

## 7. INCIDENT RESPONSE

### 7.1. Security Incident Handling
Jika terjadi security incident:
1. **Detection**: Monitoring systems detect anomaly
2. **Triage**: Tim Multimedia assess severity dan impact
3. **Containment**: Immediate actions untuk limit damage (block IPs, disable features, dll)
4. **Eradication**: Patch vulnerabilities dan remove malicious code
5. **Recovery**: Restore services dan verify integrity
6. **Lessons Learned**: Post-incident review dan update security measures

### 7.2. Komunikasi dengan Pengguna
Jika terjadi data breach yang mempengaruhi pengguna:
- **Pemberitahuan**: Maksimal **72 jam** setelah incident detected
- **Channels**: Email, notifikasi aplikasi, website announcement
- **Informasi**: Jenis data yang terpengaruh, langkah mitigasi, actions yang perlu user lakukan

---

## 8. COMPLIANCE DAN STANDAR

### 8.1. Compliance
Aplikasi HKBP Perawang berusaha mematuhi:
- **Indonesia Data Protection Law**: UU ITE dan peraturan terkait
- **GDPR Principles**: Meskipun bukan EU-based, kami menerapkan best practices GDPR
- **Firebase Security Best Practices**: Mengikuti panduan Google Cloud

### 8.2. Regular Security Audits
- **Code Reviews**: Peer review untuk semua code changes
- **Vulnerability Scanning**: Monthly automatic scans menggunakan tools
- **Penetration Testing**: Annual penetration testing (jika budget tersedia)
- **Dependency Checks**: Automatic checks untuk vulnerable dependencies

---

## 9. UPDATE KEAMANAN

### 9.1. Security Patches
- **Critical Updates**: Dirilis sesegera mungkin (1-3 hari)
- **Regular Updates**: Bundled dengan app updates (bulanan atau quarterly)
- **Pemberitahuan**: Via in-app notifications dan release notes

### 9.2. End of Life (EOL) Policy
- **Old Versions**: Force upgrade untuk versions yang sudah **6 bulan** outdated
- **Security Support**: Hanya **2 latest major versions** yang menerima security patches

---

## 10. SECURITY HALL OF FAME

Kami menghargai kontribusi dari security researchers berikut (dengan persetujuan mereka):

*[Akan diupdate saat ada pelapor kerentanan yang setuju untuk dicantumkan]*

Jika Anda melaporkan kerentanan dan ingin dicantumkan, beri tahu kami!

---

## 11. KONTAK

Untuk semua pertanyaan terkait keamanan:

**Security Team**: Tim Multimedia HKBP Perawang  
**Email**: kontak@hkbpperawang.org  
**Subject**: "Security Issue - [Brief Description]"  
**WhatsApp**: +1 (220) 222-4575 (untuk issues non-

urgent)

**Alamat**: Jl. Gajah Tunggal, Tualang, Kec. Tualang, Kabupaten Siak, Riau 28772  
**Website**: https://www.hkbpperawang.org

---

## 12. PERUBAHAN KEBIJAKAN

Kebijakan Keamanan ini dapat diperbarui untuk mencerminkan perubahan dalam praktik keamanan, teknologi, atau regulasi. Perubahan akan diberitahukan melalui aplikasi dan website.

---

## PENUTUP

Keamanan adalah tanggung jawab bersama. Dengan bekerja sama, kita dapat menjaga aplikasi HKBP Perawang tetap aman untuk semua pengguna.

**Terima kasih atas dukungan Anda dalam menjaga keamanan komunitas digital kami!**

---

**© 2025 Gereja HKBP Perawang. All Rights Reserved.**
