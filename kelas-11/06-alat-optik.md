# Bab 6: Alat-Alat Optik Lanjut

[< Kembali ke Daftar Materi Kelas 11](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Anatomi Mata & Kamera](#1-anatomi-mata--kamera)
2. [Cacat Mata (Miopi & Hipermetropi)](#2-cacat-mata-miopi--hipermetropi)
3. [Kalkulasi Kacamata Koreksi](#3-kalkulasi-kacamata-koreksi)
4. [Lup (Kaca Pembesar)](#4-lup-kaca-pembesar)
5. [Mikroskop Majemuk](#5-mikroskop-majemuk)
6. [Teropong Bintang (Teleskop)](#6-teropong-bintang-teleskop)
7. [Teropong Bumi & Panggung](#7-teropong-bumi--panggung)
8. [Teropong Pantul (Reflektor)](#8-teropong-pantul-reflektor)
9. [Optik Futuristik & Teleskop James Webb](#9-optik-futuristik--teleskop-james-webb)

---

## 1. Anatomi Mata & Kamera

Mata adalah instrumen optik alami paling canggih. Bayangan benda jatuh di **Retina** (layar) setelah melewati **Lensa Mata** (lensa cembung yang bisa berubah kelengkungannya).

**Analogi Mata vs Kamera:**
- **Iris/Pupil:** Diafragma (mengatur jumlah cahaya).
- **Retina:** Sensor/Film (tempat bayangan terbentuk).
- **Lensa Mata:** Lensa Kamera (memfokuskan cahaya).
- **Akomodasi:** Fokus Otomatis (kemampuan otot siliaris mengubah fokus lensa).

---

## 2. Cacat Mata (Miopi & Hipermetropi)

Mata normal memiliki titik dekat ($PP = 25 \text{ cm}$) dan titik jauh ($PR = \sim$).

### 2.1 Miopi (Rabun Jauh)
Lensa terlalu cembung atau bola mata terlalu lonjong, sehingga bayangan jatuh **di depan** retina. Penderita tidak bisa melihat benda jauh.
- **Titik Jauh ($PR$):** Terbatas (kurang dari tak hingga).

### 2.2 Hipermetropi (Rabun Dekat)
Lensa terlalu pipih, bayangan jatuh **di belakang** retina. Penderita tidak bisa melihat benda dekat.
- **Titik Dekat ($PP$):** Menjauh (lebih dari $25 \text{ cm}$).

---

## 3. Kalkulasi Kacamata Koreksi

Kekuatan lensa ($P$) diukur dalam satuan **Dioptri**.

- **Untuk Miopi (Lensa Cekung/Negatif):**
  

$$
\Large P = -\frac{100}{PR} \quad (\text{Jika } PR \text{ dalam cm})
$$
- **Untuk Hipermetropi (Lensa Cembung/Positif):**
  

$$
\Large P = \frac{100}{S_n} - \frac{100}{PP} = 4 - \frac{100}{PP}
$$
- *$S_n = 25 \text{ cm}$ (jarak baca normal).*

---

## 4. Lup (Kaca Pembesar)

Lensa cembung tunggal yang digunakan untuk memperbesar sudut pandang.

**Perbesaran ($M$):**
- **Mata Berakomodasi Maksimum:**
  

$$
\Large M = \frac{S_n}{f} + 1
$$
- **Mata Tak Berakomodasi:**
  

$$
\Large M = \frac{S_n}{f}
$$

---

## 5. Mikroskop Majemuk

Menggunakan dua lensa cembung: **Objektif** (dekat benda) dan **Okuler** (dekat mata).
- **Perbesaran Total:** $M_{tot} = M_{ob} \times M_{ok}$
- **Panjang Mikroskop ($d$):** Jarak antar lensa.
  

$$
\Large d = s'_{ob} + s_{ok}
$$

> [!IMPORTANT]
> Lensa Objektif membentuk bayangan **nyata, terbalik, diperbesar**. Bayangan ini kemudian dianggap sebagai benda oleh lensa Okuler untuk diperbesar lagi secara **maya**.

---

## 6. Teropong Bintang (Teleskop)

Digunakan untuk melihat benda yang sangat jauh (jarak benda $s_{ob} = \sim$).
- **Perbesaran (Tak Berakomodasi):**
  

$$
\Large M = \frac{f_{ob}}{f_{ok}}
$$
- **Panjang Teropong:**
  

$$
\Large d = f_{ob} + f_{ok}
$$

---

## 7. Teropong Bumi & Panggung

Teropong bintang menghasilkan bayangan terbalik (tidak masalah untuk bintang). Namun untuk melihat orang, bayangan harus tegak.
- **Teropong Bumi:** Menambah **Lensa Pembalik** di tengah. Panjang menjadi $d = f_{ob} + 4f_p + f_{ok}$.
- **Teropong Panggung (Galileo):** Menggunakan lensa cekung sebagai okuler agar bayangan langsung tegak.

---

## 8. Teropong Pantul (Reflektor)

Menggunakan **Cermin Cekung** besar sebagai pengganti lensa objektif.
**Keunggulan:**
1. Menghindari Aberasi Kromatik (pelangi di pinggiran lensa).
2. Lebih mudah dibuat dalam ukuran raksasa (meteran).
3. Digunakan oleh hampir semua observatorium profesional dunia.

---

## 9. Optik Futuristik & Teleskop James Webb

Dunia optik kini bergeser dari kaca ke sensor digital dan cermin emas. **JWST** menggunakan cermin segilapan (hexagon) berlapis emas untuk menangkap cahaya inframerah dari galaksi paling awal. Di tingkat medis, lensa kontak dan operasi LASIK secara langsung mengubah kelengkungan kornea mata untuk koreksi permanen.

---

## Lihat Juga
- [Pembiasan Lensa](../kelas-10/08-optik.md)
- [Latihan Soal Bab 6 Alat Optik](latihan-soal/README.md)
