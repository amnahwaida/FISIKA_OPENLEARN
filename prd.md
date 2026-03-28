```markdown
# Product Requirements Document (PRD): Repositori Belajar Fisika SMA

<div align="center">

| Informasi Dokumen | Detail |
| :--- | :--- |
| **Nama Proyek** | FisikaSMA-OpenLearn |
| **Versi** | 1.0.0 |
| **Platform** | GitHub Repository & GitHub Pages |
| **Format Konten** | Markdown (`.md`) |
| **Tanggal** | 24 Mei 2024 |
| **Status** | Final Draft |
| **Pemilik** | AmnaMinaaaa |

</div>

---

## 1. Pendahuluan

### 1.1 Latar Belakang
Banyak siswa SMA kesulitan mengakses rangkuman fisika yang terstruktur, gratis, dan mudah dimodifikasi. GitHub merupakan platform yang tepat untuk hosting materi berbasis teks karena versi kontrolnya yang jelas, aksesibilitas tinggi, dan kemampuan untuk menampilkan materi langsung melalui fitur *GitHub Pages* atau langsung di tampilan repositori.

### 1.2 Tujuan Produk
Membangun repositori GitHub yang berfungsi sebagai perpustakaan digital materi Fisika SMA. Pengguna dapat belajar langsung dengan membaca file Markdown di repositori atau melalui tampilan web yang dihasilkan oleh GitHub Pages.

### 1.3 Target Audiens
- Siswa SMA (Kelas 10-12).
- Kontributor Open Source (Guru/Siswa yang ingin melengkapi materi).
- Pengguna GitHub yang mencari materi belajar teknis.

---

## 2. Arsitektur & Struktur Repositori

Karena navigasi dilakukan sepenuhnya menggunakan Markdown, struktur folder harus rapi dan konsisten agar link relatif berfungsi dengan baik.

### 2.1 Struktur Folder
```text
root/
├── README.md                # Halaman Utama (Home) & Navigasi Global
├── prd.md                   # Dokumen ini
├── CONTRIBUTING.md          # Panduan kontribusi
├── LICENSE                  # Lisensi proyek (CC-BY-SA / MIT)
├── assets/                  # Menyimpan gambar/diagram
│   ├── kelas-10/
│   ├── kelas-11/
│   └── kelas-12/
├── kelas-10/
│   ├── README.md            # Navigasi khusus Kelas 10
│   ├── 01-besaran-satuan.md
│   ├── 02-kinematika.md
│   └── ...
├── kelas-11/
│   ├── README.md            # Navigasi khusus Kelas 11
│   ├── 01-fluida.md
│   └── ...
└── kelas-12/
    ├── README.md            # Navigasi khusus Kelas 12
    ├── 01-listrik-statis.md
    └── ...
```

### 2.2 Strategi Navigasi (Markdown Links)
Semua navigasi menggunakan **Relative Links**. Ini memastikan link tetap bekerja baik saat dilihat di repositori GitHub maupun saat di-deploy ke GitHub Pages.

- **Link ke Folder:** `[Materi Kelas 10](./kelas-10/)`
- **Link ke File:** `[Kinematika](./kelas-10/02-kinematika.md)`
- **Link ke Gambar:** `![Diagram Gerak](../assets/kelas-10/gerak-parabola.png)`
- **Link Kembali ke Home:** `[Kembali ke Beranda](../README.md)`

---

## 3. Ruang Lingkup Materi (Content Scope)

Materi harus dipecah menjadi file `.md` terpisah per Bab/Sub-bab agar mudah dibaca dan dinavigasi.

### 3.1 Kelas 10 (Dasar)
<div align="center">

| File Markdown | Topik Utama |
| :--- | :--- |
| `01-besaran-satuan.md` | Besaran, Satuan, Dimensi, Vektor |
| `02-kinematika.md` | GLB, GLBB, Parabola, Melingkar |
| `03-dinamika.md` | Hukum Newton, Gaya Gesek |
| `04-usaha-energi.md` | Usaha, Energi, Pesawat Sederhana |
| `05-momentum.md` | Impuls, Tumbukan |
| `06-kalor.md` | Suhu, Kalor, Perpindahan Kalor |
| `07-gelombang-bunyi.md` | Gelombang, Bunyi, Efek Doppler |
| `08-optik.md` | Cermin, Lensa, Alat Optik |

</div>

### 3.2 Kelas 11 (Lanjut)
<div align="center">

| File Markdown | Topik Utama |
| :--- | :--- |
| `01-fluida.md` | Fluida Statis & Dinamis |
| `02-termodinamika.md` | Suhu, Kalor Lanjut, Termodinamika |
| `03-gravitasi.md` | Hukum Newton tentang Gravitasi, Kepler |
| `04-getaran.md` | Getaran Harmonis Sederhana |
| `05-gelombang-cahaya.md` | Interferensi, Difraksi, Polarisasi |

</div>

### 3.3 Kelas 12 (Modern & Listrik)
<div align="center">

| File Markdown | Topik Utama |
| :--- | :--- |
| `01-listrik-statis.md` | Coulomb, Medan Listrik, Potensial, Kapasitor |
| `02-listrik-dinamis.md` | Arus, Hambatan, Hukum Kirchhoff |
| `03-magnet.md` | Medan Magnet, Gaya Lorentz, Induksi |
| `04-fisika-inti.md` | Radioaktivitas, Fisika Inti |
| `05-relativitas.md` | Relativitas Khusus, Fisika Kuantum |

</div>

---

## 4. Persyaratan Teknis (Technical Requirements)

### 4.1 Format Penulisan
- **Header:** Gunakan `#` untuk Judul Bab, `##` untuk Sub-bab.
- **Rumus Matematika:**
  - GitHub Markdown sekarang mendukung sintaks LaTeX secara native.
  - **Inline:** `$ F = m \cdot a $`
  - **Block:** `

$$
\Large E = mc^2
$$`
  - Pastikan tidak ada spasi antara tanda `$` dan rumus untuk inline.
- **Gambar:** Simpan semua gambar di folder `assets/`. Jangan gunakan link eksternal yang mungkin mati (hotlinking). Gunakan format `.png` atau `.svg`.

### 4.2 Deployment (GitHub Pages)
- Aktifkan **GitHub Pages** pada repository settings.
- Source: `Deploy from a branch` -> `main` / `root`.
- Theme: Pilih tema yang bersih (misal: `Minima`, `Slate`, atau `Cayman`).
- Pastikan tema mendukung rendering math (kebanyakan tema default Jekyll sudah mendukung jika dikonfigurasi benar, atau gunakan plugin `kramdown-math-ss`).

### 4.3 Template File Materi
Setiap file materi harus memiliki struktur standar berikut:

```markdown
# Judul Bab

[< Kembali ke Daftar Materi Kelas](./README.md) | [Ke Beranda](../README.md)

## Konsep Dasar
Penjelasan teks...

## Rumus Utama

$$
\Large F = m \cdot a
$$

## Contoh Soal
**Soal:** Sebuah benda...
**Jawab:** ...

## Lihat Juga
- [Materi Terkait 1](./file-lain.md)
- [Materi Terkait 2](../kelas-11/file.md)
```

---

## 5. Persyaratan Non-Fungsional

### 5.1 Kinerja
- Ukuran gambar harus dioptimasi (maksimal 200KB per gambar) agar repositori tidak terlalu berat saat di-clone.
- File Markdown harus ringan (teks murni).

### 5.2 Aksesibilitas
- Gunakan teks alternatif (`alt text`) pada semua gambar.
- Kontras warna teks harus terjaga (mengandalkan tema GitHub Pages).

### 5.3 Kemudahan Kontribusi
- Sertakan file `CONTRIBUTING.md` di root untuk panduan orang lain yang ingin menambahkan materi.
- Gunakan penamaan file yang konsisten (huruf kecil, pakai tanda hubung `-`).

---

## 6. Rencana Implementasi (Roadmap)

<div align="center">

| Tahap | Aktivitas | Output |
| :--- | :--- | :--- |
| **1. Setup** | Inisialisasi Repo, Buat Struktur Folder | Struktur folder kosong siap isi |
| **2. Template** | Buat `README.md` utama & Template Materi | Template standar penulisan |
| **3. Konten** | Isi materi Kelas 10 (Prioritas) | 8 File Markdown Kelas 10 |
| **4. Assets** | Upload diagram & gambar pendukung | Folder `assets` terisi |
| **5. Config** | Setup GitHub Pages & MathJax | Web hidup dengan rumus rapi |
| **6. Review** | Cek semua link navigasi | Tidak ada link rusak (404) |
| **7. Launch** | Publikasi link repo ke media sosial | Proyek Live |

</div>

---

## 7. Contoh Implementasi Navigasi (Snippet)

Berikut adalah contoh kode yang harus ada di dalam file `README.md` utama agar navigasi berfungsi:

```markdown
# 📚 FisikaSMA OpenLearn

Selamat datang di repositori rangkuman Fisika SMA lengkap. Pilih kelas untuk mulai belajar:

## 🗂️ Daftar Kelas

<div align="center">

| Kelas | Fokus Materi | Link |
| :---: | :--- | :--- |
| **10** | Dasar Fisika, Gerak, Energi | [Masuk Kelas 10](./kelas-10/) |
| **11** | Fluida, Termodinamika, Gelombang | [Masuk Kelas 11](./kelas-11/) |
| **12** | Listrik, Magnet, Fisika Modern | [Masuk Kelas 12](./kelas-12/) |

</div>

## 🛠️ Fitur
- ✅ Rangkuman Ringkas
- ✅ Rumus LaTeX (Native GitHub Support)
- ✅ Contoh Soal & Pembahasan
- ✅ Gratis & Open Source

---
*Dibuat untuk tujuan pendidikan. Silakan kontribusi melalui Pull Request.*
```

---

## 8. Kriteria Penerimaan (Acceptance Criteria)

1.  [ ] Semua file materi dapat dibuka tanpa error 404.
2.  [ ] Link navigasi antar kelas dan bab berfungsi (klik dari Kelas 10 bisa balik ke Home).
3.  [ ] Rumus matematika terlihat rapi (tidak menampilkan kode LaTeX mentah) saat dibuka via GitHub Pages/Repo.
4.  [ ] Gambar muncul dengan benar pada semua halaman.
5.  [ ] Repositori memiliki lisensi terbuka (misal: MIT atau CC-BY-SA).

---

## 9. Lisensi

Proyek ini direkomendasikan menggunakan lisensi **Creative Commons Attribution-ShareAlike (CC BY-SA)** agar materi dapat disebarluaskan untuk tujuan pendidikan dengan tetap mencantumkan sumber.

---

## 10. Persetujuan

<div align="center">

| Peran | Nama | Tanggal |
| :--- | :--- | :--- |
| **Project Owner** | [Nama Anda] | 24 Mei 2024 |
| **Contributor** | - | - |

</div>
```