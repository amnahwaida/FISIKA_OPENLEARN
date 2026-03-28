# Bab 1: Listrik Statis (Electrostatics)

[< Kembali ke Daftar Materi Kelas 12](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Hakikat Muatan & Hukum Coulomb](#1-hakikat-muatan--hukum-coulomb)
2. [Medan Listrik & Konsep Garis Gaya](#2-medan-listrik--konsep-garis-gaya)
3. [Hukum Gauss & Fluks Listrik](#3-hukum-gauss--fluks-listrik)
4. [Energi Potensial Listrik Mutlak](#4-energi-potensial-listrik-mutlak)
5. [Potensial Listrik & Bidang Ekipotensial](#5-potensial-listrik--bidang-ekipotensial)
6. [Dinamika Muatan dalam Medan Homogen](#6-dinamika-muatan-dalam-medan-homogen)
7. [Kapasitor & Kapasitansi Geometris](#7-kapasitor--kapasitansi-geometris)
8. [Analisis Dielektrik & Energi Kapasitor](#8-analisis-dielektrik--energi-kapasitor)
9. [Aplikasi Listrik Statis dalam Teknologi](#9-aplikasi-listrik-statis-dalam-teknologi)

---

## 1. Hakikat Muatan & Hukum Coulomb

Muatan listrik adalah properti fisik materi yang menyebabkan interaksi gaya elektromagnetik. Ada dua jenis: Positif (Proton) dan Negatif (Elektron).

**Prinsip Utama:**
- **Kuantisasi Muatan:** Muatan total benda adalah kelipatan bulat dari muatan dasar ($e = 1,6 \times 10^{-19} \text{ C}$).
- **Kekekalan Muatan:** Muatan tidak dapat diciptakan atau dimusnahkan, hanya berpindah.

**Hukum Coulomb:**
Gaya tarik atau tolak antara dua muatan titik sebanding dengan perkalian muatannya dan berbanding terbalik dengan kuadrat jaraknya.
$$ F = k \cdot \frac{q_1 \cdot q_2}{r^2} $$
- $k = \frac{1}{4\pi\epsilon_0} \approx 9 \times 10^9 \text{ Nm}^2\text{/C}^2$.

---

## 2. Medan Listrik & Konsep Garis Gaya

Medan listrik ($\mathbf{E}$) adalah besaran vektor yang menggambarkan pengaruh gaya listrik di sekitar suatu muatan.
$$ \mathbf{E} = \frac{\mathbf{F}}{q_0} = k \cdot \frac{q}{r^2} \quad (\text{N/C}) $$

**Garis Gaya Listrik:**
- Berawal dari muatan **Positif**, berakhir di muatan **Negatif**.
- Kerapatan garis menunjukkan kekuatan medan.
- Garis gaya tidak pernah berpotongan.

---

## 3. Hukum Gauss & Fluks Listrik

**Fluks Listrik ($\Phi$):** Jumlah garis medan yang menembus suatu permukaan.
$$ \Phi = E \cdot A \cdot \cos \theta $$

**Hukum Gauss:**
Fluks listrik total yang menembus permukaan tertutup sebanding dengan total muatan yang dilingkupi permukaan tersebut.
$$ \oint \mathbf{E} \cdot d\mathbf{A} = \frac{Q_{\text{terlingkup}}}{\epsilon_0} $$

> [!IMPORTANT]
> Hukum Gauss sangat sakti untuk menghitung medan pada benda kontinu seperti bola konduktor ($E_{dalam}=0$), kawat panjang, dan pelat sejajar.

---

## 4. Energi Potensial Listrik Mutlak

Usaha ($W$) yang diperlukan untuk memindahkan muatan dari titik tak terhingga ke jarak $r$.
$$ Ep = k \cdot \frac{q_1 \cdot q_2}{r} \quad (\text{Joule}) $$
Berbeda dengan gaya, $Ep$ adalah besaran skalar (tanda muatan $\pm$ wajib dimasukkan dalam hitungan).

---

## 5. Potensial Listrik & Bidang Ekipotensial

Potensial Listrik ($V$) adalah energi potensial per satuan muatan.
$$ V = \frac{Ep}{q} = k \cdot \frac{q}{r} \quad (\text{Volt}) $$

**Hubungan Medan & Potensial:**
Medan listrik adalah gradien negatif dari potensial. Cahaya atau muatan positif akan mengalir "turun" dari potensial tinggi ke rendah.
$$ E = -\frac{\Delta V}{\Delta r} $$

---

## 6. Dinamika Muatan dalam Medan Homogen

Dua keping sejajar dengan muatan berbeda akan menciptakan medan listrik homogen ($E = \text{konstan}$) di antaranya.
- **Kuat Medan:** $E = \frac{V}{d} = \frac{\sigma}{\epsilon_0}$ ($\sigma$ = rapat muatan).
- **Gerak Gerak Muatan:** Mengikuti Hukum II Newton $\mathbf{F} = m\mathbf{a} \implies q\mathbf{E} = m\mathbf{a}$.

---

## 7. Kapasitor & Kapasitansi Geometris

Kapasitor adalah alat untuk menyimpan muatan dan energi listrik. Kemampuannya disebut **Kapasitansi ($C$)**.
$$ C = \frac{Q}{V} \quad (\text{Farad}) $$

**Kapasitansi Keping Sejajar:**
$$ C = \epsilon_0 \cdot \frac{A}{d} $$
- Terlihat bahwa kapasitas hanya bergantung pada geometri (luas $A$ dan jarak $d$), bukan muatan $Q$ atau tegangan $V$.

---

## 8. Analisis Dielektrik & Energi Kapasitor

Jika di sela-sela keping diisi bahan isolator (**Dielektrik** dengan konstanta $\kappa$), maka kapasitasnya akan melonjak:
$$ C_{baru} = \kappa \cdot C_0 $$

**Energi Tersimpan ($W$):**
Kerja yang dilakukan untuk memuati kapasitor disimpan dalam bentuk medan listrik di antara keping.
$$ W = \frac{1}{2} C V^2 = \frac{1}{2} Q V = \frac{1}{2} \frac{Q^2}{C} $$

---

## 9. Aplikasi Listrik Statis dalam Teknologi

1. **Mesin Fotokopi:** Menggunakan toner bermuatan yang menempel pada pola elektrostatik di drum.
2. **Pengendap Elektrostatis (Cottrell):** Membersihkan debu dan asap pada cerobong pabrik agar ramah lingkungan.
3. **Pengecatan Mobil:** Semprotan cat diberi muatan agar menempel rata dan kuat pada bodi mobil yang bermuatan lawan.
4. **Generator Van de Graaff:** Alat penghasil tegangan sangat tinggi untuk eksperimen fisika nuklir.

---

## Lihat Juga
- [Elektronika Dasar](./02-listrik-dinamis.md)
- [Latihan Soal Bab 1 Listrik Statis](latihan-soal/README.md)
