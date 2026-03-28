# Bab 3: Magnetisme & Gaya Lorentz

[< Kembali ke Daftar Materi Kelas 12](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Hakikat Magnetisme & Eksperimen Oersted](#1-hakikat-magnetisme--eksperimen-oersted)
2. [Hukum Biot-Savart (Kawat Lurus)](#2-hukum-biot-savart-kawat-lurus)
3. [Kawat Melingkar & Solenoida](#3-kawat-melingkar--solenoida)
4. [Hukum Ampere & Toroida](#4-hukum-ampere--toroida)
5. [Gaya Lorentz (Muatan Titik)](#5-gaya-lorentz-muatan-titik)
6. [Gaya Lorentz (Kawat Berarus)](#6-gaya-lorentz-kawat-berarus)
7. [Torsi pada Loop & Motor DC](#7-torsi-pada-loop--motor-dc)
8. [Sifat Magnetik Bahan (Dia, Para, Ferro)](#8-sifat-magnetik-bahan-dia-para-ferro)
9. [Teknologi Akselerator & Spektrometer](#9-teknologi-akselerator--spektrometer)

---

## 1. Hakikat Magnetisme & Eksperimen Oersted

Magnetisme bukan lagi sekadar "batu ajaib", melainkan fenomena yang muncul akibat **Muatan Listrik yang Bergerak**.

**Eksperimen Oersted (1820):**
Hans Christian Oersted menemukan bahwa jarum kompas menyimpang saat diletakkan di dekat kawat berarus. Ini membuktikan bahwa arus listrik menciptakan medan magnet ($\mathbf{B}$) di sekitarnya.
- **Aturan Tangan Kanan:** Ibu jari menunjukkan arah arus ($I$), empat jari melingkar menunjukkan arah medan magnet ($B$).

---

## 2. Hukum Biot-Savart (Kawat Lurus)

Hukum Biot-Savart secara matematis mendefinisikan kontribusi kecil medan magnet ($dB$) dari elemen arus kecil ($dl$).

**Kawat Lurus Sangat Panjang:**
Pada jarak $a$ dari kawat lurus tak hingga:
$$
\Large B = \frac{\mu_0 \cdot I}{2\pi \cdot a}
$$
- $\mu_0 = 4\pi \times 10^{-7} \text{ Wb/Am}$ (Permeabilitas vakum).

---

## 3. Kawat Melingkar & Solenoida

### 3.1 Kawat Melingkar
Kuat medan magnet di pusat lingkaran dengan jari-jari $a$ dan $N$ lilitan:
$$
\Large B = \frac{\mu_0 \cdot I \cdot N}{2a}
$$

### 3.2 Solenoida (Kumparan Lurus)
Kawat yang dililitkan rapat pada silinder panjang. Di dalam solenoida, medan magnet sangat homogen.
- **Di Pusat:** $B = \mu_0 \cdot n \cdot I$  ($n = N/L$ lilitan per meter).
- **Di Ujung:** $B = \frac{1}{2} \mu_0 \cdot n \cdot I$.

---

## 4. Hukum Ampere & Toroida

**Hukum Ampere:** Analog dengan hukum Gauss pada listrik, hukum ini mempermudah perhitungan medan pada sistem simetri tinggi.
$$
\Large \oint \mathbf{B} \cdot d\mathbf{l} = \mu_0 \cdot I_{enc}
$$

**Toroida:** Solenoida yang ditekuk menjadi lingkaran (seperti donat).
$$
\Large B = \frac{\mu_0 \cdot I \cdot N}{2\pi \cdot r}
$$

---

## 5. Gaya Lorentz (Muatan Titik)

Muatan $q$ yang bergerak dengan kecepatan $\mathbf{v}$ di dalam medan magnet $\mathbf{B}$ akan mengalami gaya magnet.
$$
\Large \mathbf{F} = q (\mathbf{v} \times \mathbf{B}) \implies F = q \cdot v \cdot B \sin \theta
$$

**Lintasan Partikel:**
Jika $\mathbf{v} \perp \mathbf{B}$, partikel akan bergerak **Melingkar** dengan jari-jari siklotron:
$$
\Large R = \frac{m \cdot v}{q \cdot B}
$$

---

## 6. Gaya Lorentz (Kawat Berarus)

Kawat sepanjang $L$ yang dialiri arus $I$ dalam medan $B$ akan merasakan gaya mekanik (prinsip pengeras suara/speaker).
$$
\Large F = B \cdot I \cdot L \sin \theta
$$

**Interaksi Dua Kawat Sejajar:**
Dua kawat sejajar akan berinteraksi:
- **Tarik-menarik:** Jika arus searah.
- **Tolak-menolak:** Jika arus berlawanan arah.
  $$
  \Large F/L = \frac{\mu_0 \cdot I_1 \cdot I_2}{2\pi \cdot a}
  $$

---

## 7. Torsi pada Loop & Motor DC

Loop kawat berarus dalam medan magnet homogen tidak hanya menerima gaya, tetapi juga **Momen Gaya (Torsi)** yang membuatnya berputar.
$$
\Large \tau = N \cdot I \cdot A \cdot B \sin \theta
$$
- $A$: Luas Loop, $\mu = N I A$ (Momen Dipol Magnetik).
Inilah jantung dari setiap **Motor Listrik** di dunia.

---

## 8. Sifat Magnetik Bahan (Dia, Para, Ferro)

Atom memiliki momen magnetik akibat spin elektron.
1. **Diamagnetik:** Ditolak lemah oleh magnet (Contoh: Air, Emas).
2. **Paramagnetik:** ditarik lemah, momen atom acak (Contoh: Aluminium, Magnesium).
3. **Ferromagnetik:** Ditarik sangat kuat, memiliki *Domain Magnetik* (Contoh: Besi, Nikel, Kobalt).

---

## 9. Teknologi Akselerator & Spektrometer

1. **Spektrometer Massa:** Memisahkan isotop berdasarkan jari-jari lintasan magnetiknya untuk menentukan massa atom.
2. **Cyclotron:** Mempercepat partikel bermuatan dalam lintasan spiral untuk terapi kanker atau fisika nuklir.
3. **Maglev:** Kereta api yang melayang menggunakan gaya tolak magnetik untuk meminimalkan gesekan udara.

---

## Lihat Juga
- [Induksi Faraday](./04-fisika-inti.md) *(Catatan: Perlu cek apakah Ch 4 adalah Induksi EM)*
- [Latihan Soal Bab 3 Magnetisme](latihan-soal/README.md)
