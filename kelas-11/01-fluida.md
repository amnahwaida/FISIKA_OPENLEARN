# Bab 1: Fluida Statis & Dinamis

[< Kembali ke Daftar Materi Kelas 11](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
**Kajian Fluida Statis (Cairan Diam):**
1. [Tekanan Mutlak & Paradoks Hidrostatis](#1-tekanan-mutlak--paradoks-hidrostatis)
2. [Hukum Pascal dan Mekanika Hidrolik](#2-hukum-pascal-dan-mekanika-hidrolik)
3. [Hukum Archimedes dan Berat Semu](#3-hukum-archimedes-dan-berat-semu)
4. [Tegangan Permukaan & Batas Kapilaritas](#4-tegangan-permukaan--batas-kapilaritas)

**Kajian Fluida Dinamis (Aliran Cairan & Gas):**
5. [Debit Aliran & Persamaan Kontinuitas](#5-debit-aliran--pengaruh-viskositas)
6. [Asas Fundamental Bernoulli](#6-asas-fundamental-bernoulli)
7. [Aplikasi Bernoulli I (Tangki Bocor & Venturimeter)](#7-aplikasi-bernoulli-i-tangki-bocor--venturimeter)
8. [Aplikasi Bernoulli II (Tabung Pitot & Aerodinamika Sayap)](#8-aplikasi-bernoulli-ii-tabung-pitot--aerodinamika-sayap)
9. [Fluida Kental Realitas (Viskositas & Hukum Stokes)](#9-fluida-kental-realitas-viskositas--hukum-stokes)

---

## 1. Tekanan Mutlak & Paradoks Hidrostatis

**Fluida** adalah segala zat yang tak bisa mempertahankan bentuk kaku. Parameter sakral fluida adalah **Massa Jenis ($\rho$) / Kerapatan:**

$$
\Large \rho = \frac{m}{V}
$$

### 1.1 Tekanan Hidrostatis ($P_h$)

$$
\Large P_h = \rho \cdot g \cdot h
$$

- $h$ adalah kedalaman diukur dari permukaan air.

### 1.2 Tekanan Total Absolut ($P_{total}$)

$$
\Large P_{total} = P_0 + \rho g h
$$

---

## 2. Hukum Pascal dan Mekanika Hidrolik

Tekanan pada ruang tertutup diteruskan ke segala arah sama besar:

$$
\Large \frac{F_1}{A_1} = \frac{F_2}{A_2}
$$

> [!TIP]
> **Dongkrak Hidrolik:**
> 
>

$$
> \Large F_2 = F_1 \times \frac{A_2}{A_1}
>
$$

---

## 3. Hukum Archimedes

Setiap benda yang dicelupkan akan menerima gaya angkat ($F_a$):

$$
\Large F_a = \rho_f \cdot V_c \cdot g
$$

### 3.1 Berat Semu ($W'$)

$$
\Large W' = W - F_a
$$

---

## 4. Tegangan Permukaan & Kapilaritas

### 4.1 Tegangan Permukaan ($\gamma$)

$$
\Large \gamma = \frac{F}{d}
$$

### 4.2 Kapilaritas ($h$)

$$
\Large h = \frac{2 \gamma \cos \theta}{\rho g r}
$$

---

## 5. Debit & Kontinuitas

$$
\Large Q = A \cdot v
$$

$$
\Large A_1 v_1 = A_2 v_2
$$

---

## 6. Asas Bernoulli

$$
\Large P + \rho g h + \frac{1}{2}\rho v^2 = \text{Konstan}
$$

---

## 7. Tangki Bocor & Venturimeter

### 7.1 Tangki Bocor ($v$)

$$
\Large v = \sqrt{2gh}
$$

### 7.2 Venturimeter

$$
\Large v_1 = \sqrt{\frac{2gh}{(A_1/A_2)^2 - 1}}
$$

---

## 8. Tabung Pitot & Gaya Angkat Sayap

### 8.1 Tabung Pitot

$$
\Large v = \sqrt{\frac{2 \rho' g h}{\rho}}
$$

### 8.2 Gaya Angkat Sayap

$$
\Large F_1 - F_2 = \frac{1}{2} \rho A (v_a^2 - v_b^2)
$$

---

## 9. Viskositas & Hukum Stokes

### 9.1 Hukum Stokes

$$
\Large F_s = 6 \pi \eta r v
$$

### 9.2 Kecepatan Terminal

$$
\Large v_t = \frac{2r^2 g}{9\eta} (\rho_b - \rho_f)
$$

---

## Lihat Juga
- [Materi Kelas 10 & 11](../README.md)
- [Latihan Soal Bab 1 Fluida](latihan-soal/README.md)
