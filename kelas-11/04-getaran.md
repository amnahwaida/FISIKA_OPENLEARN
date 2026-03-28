# Bab 4: Getaran Harmonis & Mekanika Pegas

[< Kembali ke Daftar Materi Kelas 11](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Hakikat GHS & Gaya Pemulih](#1-hakikat-ghs--gaya-pemulih)
2. [Kinematika GHS (Persamaan Simpangan)](#2-kinematika-ghs-persamaan-simpangan)
3. [Kecepatan & Percepatan GHS](#3-kecepatan--percepatan-ghs)
4. [Osilator Pegas Tunggal](#4-osilator-pegas-tunggal)
5. [Ayunan Bandul Sederhana (Pendulum)](#5-ayunan-bandul-sederhana-pendulum)
6. [Susunan Pegas Seri & Paralel](#6-susunan-pegas-seri--paralel)
7. [Kekekalan Energi Mekanik GHS](#7-kekekalan-energi-mekanik-ghs)
8. [Asal Usul Rumus via Proyeksi GMB](#8-asal-usul-rumus-via-proyeksi-gmb)
9. [Getaran Terpaksa & Resonansi](#9-getaran-terpaksa--resonansi)

---

## 1. Hakikat GHS & Gaya Pemulih

**Getaran Harmonis Sederhana (GHS)** adalah gerak bolak-balik berkala di sekitar titik keseimbangan dengan ciri khas: gaya yang bekerja pada benda selalu mengarah ke titik keseimbangan dan besarnya sebanding dengan simpangannya.

Gaya pendorong ini disebut **Gaya Pemulih (*Restoring Force*)**. Berdasarkan **Hukum Hooke**:

$$
\Large F_p = -k \cdot x
$$
- **$k$:** Konstanta pegas (N/m).
- **$x$:** Simpangan (jarak dari titik setimbang).
- **Tanda $(-)$:** Menunjukkan arah gaya selalu berlawanan dengan arah simpangan (menarik benda kembali ke tengah).

---

## 2. Kinematika GHS (Persamaan Simpangan)

Karena GHS adalah proyeksi dari gerak melingkar, posisinya berubah secara sinusoidal terhadap waktu.

**Persamaan Umum Simpangan ($y$):**

$$
\Large y = A \sin(\omega t + \theta_0)
$$
- **$A$:** Amplitudo (Simpangan maksimum).
- **$\omega$:** Frekuensi sudut ($\text{rad/s}$), di mana $\omega = 2\pi f = \frac{2\pi}{T}$.
- **$\theta_0$:** Fase awal (posisi saat $t=0$).

---

## 3. Kecepatan & Percepatan GHS

Kecepatan dan percepatan diperoleh dari turunan matematis persamaan simpangan.

### 3.1 Kecepatan ($v$)
Laju gerak benda saat melintasi titik tertentu.

$$
\Large v = \frac{dy}{dt} = \omega A \cos(\omega t + \theta_0)
$$
- **$v_{max}$:** Terjadi di **Titik Setimbang** ($v_{max} = \omega A$).

### 3.2 Percepatan ($a$)
Perubahan kecepatan yang selalu mengincar titik tengah.

$$
\Large a = \frac{dv}{dt} = -\omega^2 A \sin(\omega t + \theta_0) = -\omega^2 y
$$
- **$a_{max}$:** Terjadi di **Titik Terjauh/Amplitudo** ($a_{max} = \omega^2 A$).

---

## 4. Osilator Pegas Tunggal

Untuk sebuah massa $m$ yang digantungkan pada pegas dengan konstanta $k$:

$$
\Large T = 2\pi \sqrt{\frac{m}{k}} \quad \text{dan} \quad f = \frac{1}{2\pi} \sqrt{\frac{k}{m}}
$$

> [!TIP]
> **Hukum "Massa Berat, Gerak Lambat":**
> Semakin berat beban ($m$), getarannya akan semakin lamban (Periode $T$ besar). Sebaliknya, semakin kaku pegasnya ($k$ besar), getarannya akan semakin cepat.

---

## 5. Ayunan Bandul Sederhana (Pendulum)

Untuk beban yang diayunkan pada tali sepanjang $L$ dengan sudut simpangan kecil ($\theta < 10^\circ$):

$$
\Large T = 2\pi \sqrt{\frac{L}{g}} \quad \text{dan} \quad f = \frac{1}{2\pi} \sqrt{\frac{g}{L}}
$$

> [!NOTE]
> Pada bandul sederhana, massa beban **TIDAK** mempengaruhi periode getaran. Hanya panjang tali dan gravitasi yang menentukan ritme ayunannya.

---

## 6. Susunan Pegas Seri & Paralel

Seringkali kita menggunakan lebih dari satu pegas untuk menopang beban (misal: shockbreaker motor).

### 6.1 Susunan Paralel (Samping-sampangan)
Pegas terlihat lebih kaku.

$$
\Large k_p = k_1 + k_2 + k_3 + \dots
$$

### 6.2 Susunan Seri (Deret memanjang)
Pegas terasa lebih lentur.

$$
\Large \frac{1}{k_s} = \frac{1}{k_1} + \frac{1}{k_2} + \frac{1}{k_3} + \dots
$$

---

## 7. Kekekalan Energi Mekanik GHS

Pada GHS terjadi pertukaran energi yang kontinu antara potensial dan kinetik.

- **Energi Potensial ($Ep$):** Maksimum di Amplitudo ($Ep = \frac{1}{2} k y^2$).
- **Energi Kinetik ($Ek$):** Maksimum di Titik Setimbang ($Ek = \frac{1}{2} m v^2$).
- **Energi Mekanik ($Em$):** Konstan di semua titik ($Em = \frac{1}{2} k A^2$).

---

## 8. Asal Usul Rumus via Proyeksi GMB

Jika sebuah titik bergerak melingkar beraturan (GMB) dan kita senter dari samping, bayangannya di layar akan bergerak bolak-balik persis seperti getaran pegas. 
- Sudut tempuh $\theta = \omega t$.
- Proyeksi vertikalnya adalah $R \sin \theta$, yang identik dengan $A \sin(\omega t)$. 
Inilah alasan mengapa fungsi sinus digunakan dalam GHS.

---

## 9. Getaran Terpaksa & Resonansi

Setiap benda punya "Frekuensi Alami". Jika kita memberi getaran luar yang frekuensinya tepat sama dengan frekuensi alami benda tersebut, amplitudonya akan melonjak drastis. Fenomena ini disebut **Resonansi**.

**Contoh Klasik:**
- Jembatan Tacoma Narrows yang runtuh akibat tiupan angin yang memicu resonansi.
- Penyanyi opera yang bisa memecahkan gelas karena frekuensi suaranya selaras dengan frekuensi kristal gelas.

---

## Lihat Juga
- [Hukum Newton](../kelas-10/03-dinamika.md)
- [Gelombang Mekanik](./05-gelombang-cahaya.md)
- [Latihan Soal Bab 4 Getaran](latihan-soal/README.md)
