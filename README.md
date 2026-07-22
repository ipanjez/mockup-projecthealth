# 📊 Project Risk & Health Dashboard v3

![Version](https://img.shields.io/badge/version-3.0.0-blue)
![Platform](https://img.shields.io/badge/platform-Web-green)
![Status](https://img.shields.io/badge/status-Dynamic_v3_Ready-success)
![License](https://img.shields.io/badge/license-MIT-purple)

Aplikasi *dashboard* berbasis web interaktif dan terintegrasi untuk pemantauan profil risiko dan kesehatan proyek (*Project Risk & Health Dashboard*). Dilengkapi dengan mesin impor Excel dinamis, *Dark Mode*, *Multi-Risk Heat Map*, *Early Warning System (EWS)*, serta *Glassmorphism UI* siap presentasi.

---

## 🌐 Live Demo & Akses Aplikasi

Aplikasi web dapat diakses secara publik dan langsung digunakan tanpa instalasi server:

👉 **[https://ipanjez.github.io/mockup-projecthealth/](https://ipanjez.github.io/mockup-projecthealth/)**

---

## ✨ Fitur-Fitur Utama (Versi 3.0)

- **📈 5 Pilar Project Health Score (PHS):**
  - **Financial Health:** CPI (Cost Performance Index), CV (Cost Variance), & NPV (Net Present Value).
  - **Schedule Health:** SPI (Schedule Performance Index) & SV (Schedule Variance).
  - **Supply Readiness Index (SRI):** Indeks kesiapan pasokan bahan baku (6 parameter termasuk Salt Readiness).
  - **Project Execution Index (PEI):** Indeks progres fisik proyek (5 parameter termasuk Performance Test).
  - **Commercial Readiness Index (CRI):** Indeks kesiapan komersial & legal (6 parameter termasuk Regulatory Readiness).
  
- **🗺️ Dynamic Risk Profile Heat Map (5x5):**
  - Pemetaan matriks *Likelihood (Y)* x *Consequence (X)* sesuai standar manajemen risiko Pertamina.
  - **Multi-Risk per Cell:** Mendukung penampilan beberapa kode risiko sekaligus dalam satu koordinat sel.

- **⚡ Marker-Based & Dynamic Row Excel Importer:**
  - Impor data instan dari `Template_Dashboard_v3.xlsx` tanpa ketergantungan pada alamat sel kaku.
  - Memungkinkan penambahan baris baru secara tak terbatas untuk EWS, Top Risk, dan Executive Actions.
  - Mendukung kustomisasi bobot, nama perusahaan, proyek, hingga warna secara otomatis melalui sheet `Config`.

- **🌙 Modern UI/UX & Dark Mode:**
  - Desain *Glassmorphism* dengan rasio presentasi 16:9 yang responsif.
  - Toggle *Dark Mode* untuk kenyamanan presentasi di ruang gelap.
  - Gauge SVG dinamis dengan animasi transisi yang halus.

- **🖨️ Multi-Format Export:**
  - Ekspor tampilan slide ke **PNG**, **JPG**, atau **PDF (A4 Landscape)** resolusi tinggi dengan satu klik.

---

## 📂 Struktur File Template Excel (`Template_Dashboard_v3.xlsx`)

File template Excel terdiri dari 6 sheet terintegrasi:

| Sheet | Fungsi | Pengisi Data |
| :--- | :--- | :--- |
| **`Config`** | Pusat pengaturan global: nama proyek, bobot 5 pilar PHS, bobot risk index, warna, dan limitasi tampilan. | PM / PMO |
| **`Panduan`** | Panduan lengkap cara mengisi data, format warna sel, dan penambahan baris baru. | Hanya dibaca |
| **`Referensi_Threshold`** | Matriks skala risiko 5x5 non-linear dan daftar referensi bobot pilar. | Risk Manager |
| **`Input_Bulanan`** | Sheet input data utama berkala (EVM, SRI, PEI, CRI, EWS, Top Risk). | Project Control |
| **`Risk_Action_Tracker`** | Tracker aksi mitigasi bulanan, dinamika pergerakan risiko, dan prioritas keputusan eksekutif. | Risk Manager / Project Control |
| **`Dashboard`** | Ringkasan visual otomatis dalam Excel. | Otomatis |

---

## 🚀 Panduan Penggunaan Instant

1. **Buka Aplikasi:** Akses web dashboard melalui link [Live Demo](https://ipanjez.github.io/mockup-projecthealth/).
2. **Unduh Template:** Klik tombol **`⭳ Unduh Template`** di toolbar untuk mengunduh `Template_Dashboard_v3.xlsx`.
3. **Isi Data Bulanan:** Isi sel berlatar belakang **KUNING (font biru)** di sheet `Input_Bulanan` dan `Risk_Action_Tracker`.
4. **Muat ke Web:** Klik tombol **`⭱ Muat Data Excel`**, pilih file Excel Anda, dan lihat visualisasi dashboard instan!
5. **Ekspor Report:** Klik tombol **`PDF`**, **`PNG`**, atau **`JPG`** untuk mengunduh laporan siap pakai.

---

## 🛠️ Teknologi yang Digunakan

- **Frontend:** HTML5, Vanilla CSS3 (Custom Variables, Glassmorphism, Flexbox/Grid), JavaScript ES6+.
- **Typography:** Google Fonts (*Inter*, *Space Grotesk*, *IBM Plex Mono*).
- **Excel Parser:** [SheetJS (xlsx.full.min.js)](https://sheetjs.com/).
- **Export Engines:** [html2canvas](https://html2canvas.hertzen.com/) & [jsPDF](https://github.com/parallax/jsPDF).

---

## 👨‍💻 Credits & Author

Aplikasi *Project Risk & Health Dashboard* ini dirancang dan dikembangkan secara independen oleh **Ipanjez**.

### Connect with Me:

[![GitHub](https://img.shields.io/badge/GitHub-ipanjez-181717?style=for-the-badge&logo=github)](https://github.com/ipanjez)
[![Instagram](https://img.shields.io/badge/Instagram-ipanjez-E4405F?style=for-the-badge&logo=instagram)](https://instagram.com/ipanjez)
[![Facebook](https://img.shields.io/badge/Facebook-ipanjez-1877F2?style=for-the-badge&logo=facebook)](https://facebook.com/ipanjez)
[![Gravatar](https://img.shields.io/badge/Gravatar-ipanjez-1E8CBE?style=for-the-badge&logo=gravatar)](https://gravatar.com/ipanjez)

---
*Copyright © 2026 Ipanjez. All rights reserved.*
