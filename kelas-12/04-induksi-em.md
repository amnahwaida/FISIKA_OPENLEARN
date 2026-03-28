# Bab 4: Induksi Elektromagnetik

[< Kembali ke Daftar Materi Kelas 12](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Fluks Magnetik & Hukum Faraday](#1-fluks-magnetik--hukum-faraday)
2. [Hukum Lenz (Arah Arus Induksi)](#2-hukum-lenz-arah-arus-induksi)
3. [Ggl Induksi Kawat Melintasi Medan](#3-ggl-induksi-kawat-melintasi-medan)
4. [Induktansi Diri (Solenoida)](#4-induktansi-diri-solenoida)
5. [Energi dalam Medan Magnet Induktor](#5-energi-dalam-medan-magnet-induktor)
6. [Generator Arus Bolak-Balik (AC)](#6-generator-arus-bolak-balik-ac)
7. [Transformator (Trafo) Ideal](#7-transformator-trafo-ideal)
8. [Efisiensi Trafo & Arus Eddy](#8-efisiensi-trafo--arus-eddy)
9. [Teknologi Wireless Charging & Induksi Modern](#9-teknologi-wireless-charging--induksi-modern)

---

## 1. Fluks Magnetik & Hukum Faraday

Jika magnetisme diciptakan oleh arus listrik (Bab 3), maka sebaliknya, **Arus Listrik bisa diciptakan oleh Magnet**. Namun, magnetnya harus "Bergerak" atau Berubah.

**Fluks Magnetik ($\Phi$):** Jumlah garis medan magnet yang menembus luasan tertentu.
$$
\Large \Phi = B \cdot A \cdot \cos \theta \quad (\text{Weber})
$$

**Hukum Faraday:**
Gaya Gerak Listrik (Ggl) induksi timbul sebanding dengan laju perubahan fluks magnetik.
$$
\Large \varepsilon = -N \frac{d\Phi}{dt} \approx -N \frac{\Delta \Phi}{\Delta t}
$$

---

## 2. Hukum Lenz (Arah Arus Induksi)

Tanda negatif ($-$) pada hukum Faraday dijelaskan oleh **Hukum Lenz**.
> "Arus induksi akan muncul dengan arah sedemikian rupa sehingga menciptakan medan magnet tandingan yang **melawan** penyebab perubahan fluksnya."

Ini adalah mekanisme alam untuk menjaga **Kekekalan Energi**. Kita tidak bisa mendapatkan energi listrik secara gratis; kita harus melakukan usaha mekanik untuk melawan gaya tolak induksi tersebut.

---

## 3. Ggl Induksi Kawat Melintasi Medan

Sebuah kawat penghantar sepanjang $L$ yang digerakkan memotong medan magnet $B$ dengan kecepatan $v$.
$$
\Large \varepsilon = B \cdot L \cdot v \cdot \sin \theta
$$
- **Aturan Tangan Kanan:** Ibu jari ($v$), Telunjuk ($B$), Tengah ($I$ induksi).

---

## 4. Induktansi Diri (Solenoida)

Kumparan memiliki sifat melawan perubahan arus yang melewatinya sendiri. Sifat ini disebut **Induktansi ($L$)**.
$$
\Large \varepsilon = -L \frac{dI}{dt}
$$
**Induktansi Solenoida:**
$$
\Large L = \frac{\mu_0 \cdot N^2 \cdot A}{\ell} \quad (\text{Henry})
$$

---

## 5. Energi dalam Medan Magnet Induktor

Induktor menyimpan energi dalam bentuk **Medan Magnet**.
$$
\Large W = \frac{1}{2} L I^2 \quad (\text{Joule})
$$

---

## 6. Generator Arus Bolak-Balik (AC)

Mengubah energi mekanik (putar) menjadi listrik. Sebuah loop kumparan diputar dalam medan magnet tetap.
$$
\Large \Phi = B \cdot A \cdot \cos(\omega t)
$$
$$
\Large \varepsilon = N \cdot B \cdot A \cdot \omega \cdot \sin(\omega t)
$$
$$
\Large \varepsilon = \varepsilon_{max} \sin(\omega t)
$$
Inilah asal mula tegangan listrik yang berubah-ubah naik turun (AC).

---

## 7. Transformator (Trafo) Ideal

Alat untuk menaikkan (**Step-up**) atau menurunkan (**Step-down**) tegangan AC tanpa bagian yang bergerak.
- **Prinsip:** Induksi silang antar kumparan primer dan sekunder.
  $$
  \Large \frac{V_p}{V_s} = \frac{N_p}{N_s} = \frac{I_s}{I_p}
  $$

---

## 8. Efisiensi Trafo & Arus Eddy

Trafo nyata tidak pernah $100\%$ efisien.
- **Penyebab Rugi:** Panas Joule di kabel, **Arus Eddy** (arus pusar di inti besi), Kebocoran Fluks, dan Histeresis.
**Efisiensi ($\eta$):**
$$
\Large \eta = \frac{P_{out}}{P_{in}} \times 100\% = \frac{V_s I_s}{V_p I_p} \times 100\%
$$

---

## 9. Teknologi Wireless Charging & Induksi Modern

1. **Wireless Charging:** Ponsel dan charger memiliki kumparan induksi yang saling mentransfer energi lewat medan magnet udara (Resonansi Magnetik).
2. **Induksi Cooker:** Kompor listrik tanpa api. Medan magnet frekuensi tinggi menginduksi arus Eddy pada dasar panci besi, sehingga panci memanas seketika sementara kaca kompor tetap dingin.
3. **Penyimpanan Energi:** Induktor raksasa digunakan dalam sistem penstabil tegangan pada jaringan listrik cerdas (Smart Grid).

---

## Lihat Juga
- [Arus Bolak-Balik (AC)](./05-arus-ac.md)
- [Latihan Soal Bab 4 Induksi EM](latihan-soal/README.md)
