# Bab 5: Momentum, Impuls, dan Tumbukan

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Pendahuluan](#1-pendahuluan)
2. [Momentum](#2-momentum)
3. [Impuls](#3-impuls)
4. [Hukum Kekekalan Momentum Linear (HKML)](#4-hukum-kekekalan-momentum-linear-hkml)
5. [Tumbukan](#5-tumbukan)
6. [Tumbukan dalam 2 Dimensi](#6-tumbukan-dalam-2-dimensi)
7. [Pusat Massa (Center of Mass)](#7-pusat-massa-center-of-mass)
8. [Hubungan Momentum dan Energi](#8-hubungan-momentum-dan-energi)
9. [Aplikasi Elite](#9-aplikasi-elite)

---

## 1. Pendahuluan
Di Bab 4, kita menganalisis gerak menggunakan **Energi** (skalar). Bab ini memperkenalkan besaran baru: **Momentum** (vektor). Jika energi menjawab pertanyaan "berapa besar usaha yang dibutuhkan?", maka momentum menjawab "seberapa sulit menghentikan benda ini?".

> [!NOTE]
> **Filosofi Momentum:**
> Seekor nyamuk dan sebuah truk bisa memiliki energi kinetik yang sama jika nyamuk bergerak sangat cepat. Namun, momentum truk jauh lebih besar karena **massanya**, menjadikannya jauh lebih sulit dihentikan. Momentum menangkap "kegigihan gerak" yang tidak bisa ditangkap oleh energi saja.

---

## 2. Momentum

### 2.1 Definisi Formal
Momentum linear ($\vec{p}$) adalah besaran **vektor** yang menggambarkan kuantitas gerak suatu benda:

$$
\Large \vec{p} = m \cdot \vec{v}
$$

> [!IMPORTANT]
> **Eternal Bridge: Momentum Relativistik:**
> Pada kecepatan mendekati cahaya, massa benda tampak bertambah ($m_{\text{rel}} = \gamma m_0$). Oleh karena itu, rumus momentum menjadi:
> 
>

$$
> \Large \vec{p} = \gamma m_0 \vec{v} = \frac{m_0 \vec{v}}{\sqrt{1 - \frac{v^2}{c^2}}}
>
$$

> 
> Tanpa faktor Lorentz ($\gamma$), perhitungan momentum roket antar bintang atau partikel atom akan salah total.

Dimana:
- $\vec{p}$ = Momentum (kg·m/s)
- $m$ = Massa benda (kg)
- $\vec{v}$ = Kecepatan benda (m/s)

---

## 3. Impuls

### 3.1 Definisi dan Teorema Impuls-Momentum

$$
\Large \vec{J} = \vec{F} \cdot \Delta t = \Delta \vec{p} = m\vec{v}_2 - m\vec{v}_1
$$

### 3.2 Aplikasi Keselamatan: Memperbesar $\Delta t$
Dari $F = \frac{\Delta p}{\Delta t}$, jika $\Delta p$ sama, maka:
- **$\Delta t$ kecil** → Gaya besar (bahaya!)
- **$\Delta t$ besar** → Gaya kecil (aman!)

---

## 4. Hukum Kekekalan Momentum Linear (HKML)

### 4.1 Derivasi dari Hukum Newton III
**Bukti Formal:**
Perhatikan dua benda ($m_1, m_2$) yang saling berinteraksi (tumbukan):

**A. Berdasarkan Hukum Newton III (Aksi-Reaksi):**

$$
\Large \vec{F}_{12} = -\vec{F}_{21}
$$

**B. Gaya adalah Laju Perubahan Momentum:**

$$
\Large \frac{\Delta \vec{p}_1}{\Delta t} = -\frac{\Delta \vec{p}_2}{\Delta t}
$$

**C. Kalikan dengan $\Delta t$ (Internal Interaction):**

$$
\Large \Delta \vec{p}_1 = -\Delta \vec{p}_2
$$

**D. Jumlahkan Seluruh Perubahan Momentum:**

$$
\Large \Delta \vec{p}_1 + \Delta \vec{p}_2 = 0
$$

**E. Maka Momentum Total Selalu Kekal:**

$$
\Large \mathbf{\vec{p}_{total,\text{awal}} = \vec{p}_{total,\text{akhir}}}
$$

$$
\Large m_1 v_1 + m_2 v_2 = m_1 v_1' + m_2 v_2'
$$

**Q.E.D.** — Momentum total sistem selalu konstan.

---

## 5. Tumbukan

### 5.1 Koefisien Restitusi ($e$)

$$
\Large e = -\frac{v_1' - v_2'}{v_1 - v_2}
$$

### 5.2 Tumbukan Lenting Sempurna ($e = 1$)

**Rumus Cepat (target awalnya diam, $v_2 = 0$):**

$$
\Large v_1' = \frac{m_1 - m_2}{m_1 + m_2} v_1
$$

$$
\Large v_2' = \frac{2m_1}{m_1 + m_2} v_1
$$

---

## 9. Aplikasi Elite

### 9.1 Pendulum Balistik
**Rumus Cepat Kecepatan Peluru:**

$$
\Large v_{peluru} = \frac{m + M}{m} \sqrt{2gh}
$$

### 9.2 Prinsip Roket (Sistem Massa Berubah)
**Persamaan Gaya Dorong Roket:**

$$
\Large F_{thrust} = v_{rel} \cdot \frac{dm}{dt}
$$

### 9.3 Ledakan (Kebalikan Tumbukan)

$$
\Large 0 = m_1 v_1' + m_2 v_2' + \ldots
$$

Artinya, jumlah vektor momentum semua pecahan setelah ledakan = **nol**.

---

## Lihat Juga
- [Usaha dan Energi](./04-usaha-energi.md)
- [Latihan Soal Bab 5](latihan-soal/README.md)
