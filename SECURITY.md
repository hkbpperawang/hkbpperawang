# Kebijakan Keamanan (Security Policy) — HKBP Perawang

Keamanan data, privasi jemaat, dan integritas sistem informasi HKBP Perawang adalah prioritas utama kami. Dokumen ini menjelaskan kebijakan pelaporan kerentanan (*responsible disclosure*), cakupan versi yang didukung, serta prosedur penanganan insiden keamanan.

Kebijakan lengkap dapat dibaca pada dokumen resmi [**security policy**](https://aplikasi.hkbpperawang.org/legal/security-policy).

---

## 1. Versi yang Didukung (Supported Versions)

Pembaruan keamanan dan perbaikan kerentanan aktif disediakan untuk versi rilis stabil terkini:

| Platform | Versi Didukung | Status Dukungan |
| :--- | :--- | :--- |
| **Android** | Versi rilis stabil terbaru (Play Store / APK resmi) | :white_check_mark: Didukung penuh |
| **Web Portal** (`aplikasi.hkbpperawang.org` / `parhalado.hkbpperawang.org`) | Versi produksi aktif di server | :white_check_mark: Didukung penuh |
| **Desktop / Lainnya** | Versi rilis terkini | :white_check_mark: Didukung penuh |
| **Versi Legacy (< 6 bulan ke belakang)** | Versi lama | :x: Tidak didukung (disarankan segera memperbarui aplikasi) |

---

## 2. Pelaporan Kerentanan (Reporting a Vulnerability)

Kami sangat menghargai peneliti keamanan (*security researchers*), pengembang, dan jemaat yang melaporkan potensi celah keamanan secara bertanggung jawab (*responsible disclosure*).

### Saluran Pelaporan Resmi:
Kirimkan rincian kerentanan melalui email terenkripsi atau langsung ke:
- **Developer / Tim Multimedia Devisi Digital**: `dev@hkbpperawang.org`
- **Support / Layanan Pengaduan**: `support@hkbpperawang.org`
- **Kontak Alternatif Kantor**: `kontak@hkbpperawang.org`
- **Informasi Resmi**: `informasi@hkbpperawang.org`
- **Subjek Email**: `Security Vulnerability Report - CONFIDENTIAL`

### Informasi yang Wajib Disertakan:
1. **Jenis Kerentanan**: (misalnya XSS, Broken Access Control, SQL/NoSQL Injection, API Authentication Bypass, Information Disclosure, dll.).
2. **Langkah-langkah Reproduksi (*Steps to Reproduce*)**: Urutan langkah yang jelas dan terperinci agar tim dapat memvalidasi temuan.
3. **Analisis Dampak (*Impact Assessment*)**: Penjelasan potensi risiko terhadap data jemaat atau integritas sistem (estimasi skor CVSS jika ada).
4. **Bukti Konsep (*Proof of Concept / PoC*)**: Tangkapan layar, cuplikan permintaan HTTP (*cURL*), skrip aman, atau video demonstrasi.
5. **Komponen/Versi Terdampak**: URL endpoint, file, layar, atau versi aplikasi terkait.
6. **Saran Mitigasi**: Rekomendasi teknis untuk perbaikan (opsional).

---

## 3. Ketentuan Pengujian yang Bertanggung Jawab

Saat mencari atau memverifikasi kerentanan, Anda **DILARANG**:
- Melakukan serangan yang merusak layanan (*Denial of Service* / DoS / DDoS).
- Mengakses, mengubah, menghapus, atau menyebarluaskan data pribadi jemaat atau pengurus.
- Melakukan rekayasa sosial (*social engineering*), phishing, atau serangan fisik terhadap kantor gereja/pengurus/jemaat.
- Membocorkan atau mempublikasikan kerentanan kepada publik sebelum perbaikan dirilis dan disetujui (*coordinated disclosure*).

---

## 4. Alur & Waktu Respon (Response Timeline)

Tim Pengembang akan menangani laporan sesuai tingkatan keparahan:

- **Konfirmasi Penerimaan (*Acknowledgment*)**: Maksimal **24 jam** sejak laporan masuk.
- **Penilaian Awal (*Initial Assessment*)**: Dalam **2–3 hari kerja** untuk memvalidasi keparahan celah (Critical, High, Medium, Low).
- **Pembaruan Berkala**: Informasi status perbaikan diberikan setiap 7 hari kerja.
- **Penyelesaian (*Fix Deployment*)**:
  - **Kritis (Critical - CVSS 9.0–10.0)**: 1–3 hari.
  - **Tinggi (High - CVSS 7.0–8.9)**: 7–14 hari.
  - **Sedang (Medium - CVSS 4.0–6.9)**: Hingga 30 hari.
  - **Rendah (Low - CVSS 0.1–3.9)**: Dirilis pada siklus rilis berikutnya.

---

## 5. Penghargaan & Pengakuan

HKBP Perawang tidak menyediakan program bug bounty berupa imbalan finansial, namun kami sangat mengapresiasi kontribusi sukarela Anda:
- Pencantuman nama pada **Security Hall of Fame** / Catatan Rilis resmi (dengan persetujuan pelapor).
- Sertifikat penghargaan digital **"Security Contributor"** dari Tim Multimedia HKBP Perawang.

---

Untuk informasi arsitektur keamanan, kepatuhan data, dan perlindungan privasi lebih mendalam, silakan baca [**Kebijakan Keamanan Lengkap (legal/security-policy.md)**](legal/security-policy.md).

© 2024–2026 Gereja HKBP Perawang & Tim Multimedia HKBP Perawang (Devisi Digital). All Rights Reserved.
