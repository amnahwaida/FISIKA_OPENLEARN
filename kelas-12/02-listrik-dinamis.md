# Bab 2: Listrik Dinamis (DC Circuits)

[< Kembali ke Daftar Materi Kelas 12](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Hakikat Arus & Mekanika Drif Elektron](#1-hakikat-arus--mekanika-drif-elektron)
2. [Hambatan Jenis & Efek Suhu](#2-hambatan-jenis--efek-suhu)
3. [Hukum Ohm & Material Non-Ohmik](#3-hukum-ohm--material-non-ohmik)
4. [Hukum Kirchhoff I (Node Rule)](#4-hukum-kirchhoff-i-node-rule)
5. [Hukum Kirchhoff II (Loop Rule)](#5-hukum-kirchhoff-ii-loop-rule)
6. [Jembatan Wheatstone & Transformasi Delta-Y](#6-jembatan-wheatstone--transformasi-delta-y)
7. [Disipasi Daya & Energi Joule](#7-disipasi-daya--energi-joule)
8. [Rekayasa Alat Ukur (Shunt & Multiplier)](#8-rekayasa-alat-ukur-shunt--multiplier)
9. [Potensiometer & Jembatan Kawat](#9-potensiometer--jembatan-kawat)

---

## 1. Hakikat Arus & Mekanika Drif Elektron

Arus listrik ($I$) adalah laju aliran muatan menembus suatu penampang per satuan waktu.

$$

\Large I = \frac{dQ}{dt} \approx \frac{\Delta Q}{\Delta t} \quad (\text{Ampere})

$$

**Kecepatan Drif ($v_d$):**
Meskipun sinyal listrik merambat mendekati kecepatan cahaya, elektron fisik sebenarnya bergerak sangat lambat (hanyut) akibat tumbukan konstan dengan ion logam.

$$

\Large I = n \cdot q \cdot A \cdot v_d

$$

- $n$: densitas elektron bebas.
- $v_d$: kecepatan drif ($ \sim 10^{-4} \text{ m/s}$).

---

## 2. Hambatan Jenis & Efek Suhu

Hambatan ($R$) kawat penghantar dipengaruhi oleh geometri dan jenis material.

$$

\Large R = \rho \cdot \frac{L}{A}

$$

**Ketergantungan Suhu:**
Getaran atom logam meningkat seiring suhu, menghambat laju elektron.

$$

\Large R = R_0 (1 + \alpha \cdot \Delta T)

$$

- $\alpha$: koefisien suhu hambatan ($/^\circ\text{C}$).

---

## 3. Hukum Ohm & Material Non-Ohmik

**Hukum Ohm:** Untuk banyak material (terutama logam pada suhu konstan), arus sebanding dengan tegangan.

$$

\Large V = I \cdot R

$$

**Non-Ohmik:** Beberapa komponen seperti Dioda, LED, dan Termistor tidak memiliki grafik V-I linear. Hambatannya berubah-ubah tergantung tegangan yang diberikan (Hambatan Dinamis).

---

## 4. Hukum Kirchhoff I (Node Rule)

Berdasarkan hukum **Kekekalan Muatan**, total arus yang masuk ke titik percabangan harus sama dengan total arus yang keluar.

$$

\Large \sum I_{\text{masuk}} = \sum I_{\text{keluar}}

$$

---

## 5. Hukum Kirchhoff II (Loop Rule)

Berdasarkan hukum **Kekekalan Energi**, jumlah perubahan potensial (Ggl dan penurunan tegangan) dalam suatu lintasan tertutup (loop) adalah NOL.

$$

\Large \sum \varepsilon + \sum (I \cdot R) = 0

$$

**Sumber Tegangan Riil:**
Baterai memiliki **Hambatan Dalam ($r$)**. Tegangan jepit ($V_{jepit}$) selalu lebih kecil dari Ggl ($\varepsilon$) saat arus mengalir.

$$

\Large V_{jepit} = \varepsilon - I \cdot r

$$

---

## 6. Jembatan Wheatstone & Transformasi Delta-Y

**Jembatan Wheatstone:** Rangkaian khusus untuk mengukur hambatan yang tidak diketahui dengan presisi tinggi.
- **Kondisi Seimbang:** Jika $R_1 \cdot R_3 = R_2 \cdot R_4$, maka tidak ada arus di galvano ($R_g$).

**Transformasi $\Delta - Y$:** Teknik menyederhanakan rangkaian "jembatan" yang tidak seimbang menjadi rangkaian seri-paralel biasa.

---

## 7. Disipasi Daya & Energi Joule

Energi listrik yang hilang menjadi panas (Efek Joule) saat melewati hambatan.

$$

\Large W = V \cdot I \cdot t = I^2 \cdot R \cdot t

$$

**Daya Listrik ($P$):**

$$

\Large P = \frac{W}{t} = V \cdot I = I^2 \cdot R = \frac{V^2}{R}

$$

> [!TIP]
> Untuk transmisi jarak jauh, tegangan dinaikkan (High Voltage) agar arus ($I$) mengecil, sehingga rugi-rugi daya ($I^2 R$) di kabel transmisi menjadi minimal.

---

## 8. Rekayasa Alat Ukur (Shunt & Multiplier)

Galvanometer dasar memiliki batas ukur sangat kecil.
- **Ammeter (Paralel):** Memasang **Hambatan Shunt ($R_s$)** secara paralel untuk memperbesar batas ukur arus.
- **Voltmeter (Seri):** Memasang **Hambatan Depan ($R_d$)** secara seri untuk memperbesar batas ukur tegangan.

---

## 9. Potensiometer & Jembatan Kawat

**Potensiometer:** Alat ukur tegangan yang tidak mengambil arus dari rangkaian yang diukur (**Null Method**).
Prinsipnya membandingkan Ggl yang tidak diketahui dengan Ggl standar menggunakan perbandingan panjang kawat hambatan yang seragam.

$$

\Large \frac{\varepsilon_1}{\varepsilon_2} = \frac{L_1}{L_2}

$$

---

## Lihat Juga
- [Kelistrikan Statis](./01-listrik-statis.md)
- [Medan Magnet & Induksi](./03-magnet.md)
- [Latihan Soal Bab 2 Listrik Dinamis](latihan-soal/README.md)
