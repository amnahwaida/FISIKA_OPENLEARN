# Bab 5: Arus Bolak-Balik (AC)

[< Kembali ke Daftar Materi Kelas 12](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Nilai Efektif & Maksimum](#1-nilai-efektif--maksimum)
2. [Resistor Murni dalam Arus AC](#2-resistor-murni-dalam-arus-ac)
3. [Induktor Murni (Reaktansi Induktif)](#3-induktor-murni-reaktansi-induktif)
4. [Kapasitor Murni (Reaktansi Kapasitif)](#4-kapasitor-murni-reaktansi-kapasitif)
5. [Rangkaian Seri RLC & Impedansi](#5-rangkaian-seri-rlc--impedansi)
6. [Diagram Fasor & Sudut Fase](#6-diagram-fasor--sudut-fase)
7. [Daya & Faktor Daya (Cos Phi)](#7-daya--faktor-daya-cos-phi)
8. [Resonansi Rangkaian RLC](#8-resonansi-rangkaian-rlc)
9. [Teknologi Inverter & Rectifier](#9-teknologi-inverter--rectifier)

---

## 1. Nilai Efektif & Maksimum

Berbeda dengan arus searah (DC) yang nilainya stabil, arus bolak-balik (AC) memiliki nilai yang berubah secara sinusoidal terhadap waktu.

**Nilai Maksimum ($V_{max}$):** Tegangan puncak tertinggi pada gelombang.
**Nilai Efektif ($V_{rms}$):** Nilai tegangan AC yang menghasilkan efek panas (disipasi daya) yang sama dengan tegangan DC. Inilah nilai yang dibaca oleh Voltmeter/Ammeter AC.
$$
\Large V_{ef} = \frac{V_{max}}{\sqrt{2}} \approx 0,707 \cdot V_{max}
$$
$$
\Large I_{ef} = \frac{I_{max}}{\sqrt{2}}
$$

---

## 2. Resistor Murni dalam Arus AC

Pada hambatan murni ($R$), tegangan dan arus berubah secara bersamaan.
- **Karakteristik:** Arus dan Tegangan **Sefase** ($\phi = 0$).
- **Hukum Ohm:** $V_R = I \cdot R$ (Berlaku untuk nilai maksimum maupun efektif).

---

## 3. Induktor Murni (Reaktansi Induktif)

Induktor ($L$) menghambat arus AC tidak hanya lewat hambatan kawat, tapi lewat Ggl induksi diri.
- **Reaktansi Induktif ($X_L$):** 
  $$
  \Large X_L = \omega \cdot L = 2\pi f \cdot L \quad (\text{Ohm})
  $$
- **Karakteristik Fase:** Tegangan **Mendahului** Arus sebesar $90^\circ$ (CIVIL: $V$ before $I$ in $L$).

---

## 4. Kapasitor Murni (Reaktansi Kapasitif)

Kapasitor ($C$) menghambat arus AC melalui proses pengosongan dan pengisian muatan.
- **Reaktansi Kapasitif ($X_C$):**
  $$
  \Large X_C = \frac{1}{\omega \cdot C} = \frac{1}{2\pi f \cdot C} \quad (\text{Ohm})
  $$
- **Karakteristik Fase:** Arus **Mendahului** Tegangan sebesar $90^\circ$ (CIVIL: $I$ before $V$ in $C$).

---

## 5. Rangkaian Seri RLC & Impedansi

Saat $R, L,$ dan $C$ disusun seri, hambatan totalnya tidak bisa dijumlahkan secara aljabar biasa karena perbedaan fase. Kita menggunakan penjumlahan vektor (**Impedansi, $Z$**).
$$
\Large Z = \sqrt{R^2 + (X_L - X_C)^2} \quad (\text{Ohm})
$$
**Tegangan Total ($V$):**
$$
\Large V_{total} = \sqrt{V_R^2 + (V_L - V_C)^2}
$$

---

## 6. Diagram Fasor & Sudut Fase

Fasor (*Phase Vector*) adalah cara memvisualisasikan tegangan sebagai vektor yang berputar.
- **Sudut Fase ($\phi$):** Pergeseran antara tegangan total dan arus total.
  $$
  \Large \tan \phi = \frac{X_L - X_C}{R}
  $$

---

## 7. Daya & Faktor Daya (Cos Phi)

Daya pada AC hanya benar-benar terpakai (diserap) pada komponen Resistor ($R$).
**Daya Nyata ($P$):**
$$
\Large P = V_{ef} \cdot I_{ef} \cdot \cos \phi \quad (\text{Watt})
$$
- **Faktor Daya ($\cos \phi$):** Nilai efisiensi penggunaan daya. Idealnya bernilai $1$. Jika terlalu rendah, tagihan listrik membengkak akibat "Daya Buta" ($Q$) yang tidak terpakai tapi tetap mengalir.

---

## 8. Resonansi Rangkaian RLC

Resonansi terjadi saat hambatan induktif saling meniadakan hambatan kapasitif ($X_L = X_C$).
- **Akibat:** Impedansi minimum ($Z = R$), Arus maksimum.
- **Frekuensi Resonansi ($f_r$):**
  $$
  \Large f_r = \frac{1}{2\pi \sqrt{L \cdot C}}
  $$
Prinsip ini digunakan pada **Tuning Radio**; kita mengubah nilai $C$ pada kapasitor variabel agar frekuensi resonansi rangkaian sama dengan frekuensi stasiun radio.

---

## 9. Teknologi Inverter & Rectifier

1. **Rectifier (Penyearah):** Mengubah AC menjadi DC (digunakan pada semua charger ponsel dan adaptor laptop).
2. **Inverter:** Mengubah DC menjadi AC (digunakan pada sistem Panel Surya dan sistem UPS kantor).
3. **Trafo Distribusi:** Menurunkan tegangan tinggi transmisi menjadi $220 \text{ V}$ yang siap digunakan di rumah.

---

## Lihat Juga
- [Radioaktivitas & Fisika Inti](./06-fisika-inti.md)
- [Latihan Soal Bab 5 Arus AC](latihan-soal/README.md)
