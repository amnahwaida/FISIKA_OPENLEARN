# Bab 6: Suhu, Kalor, dan Perpindahan Kalor

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Pendahuluan: Suhu vs Kalor](#1-pendahuluan-suhu-vs-kalor)
2. [Suhu dan Skala Termometer](#2-suhu-dan-skala-termometer)
3. [Pemuaian Zat](#3-pemuaian-zat)
4. [Kalor Pemanasan dan Kapasitas Kalor](#4-kalor-pemanasan-dan-kapasitas-kalor)
5. [Perubahan Wujud dan Kalor Laten](#5-perubahan-wujud-dan-kalor-laten)
6. [Grafik Pemanasan (Kurva Suhu-Waktu)](#6-grafik-pemanasan-kurva-suhu-waktu)
7. [Asas Black](#7-asas-black)
8. [Perpindahan Kalor](#8-perpindahan-kalor)
9. [Aplikasi Elite & Filosofi](#9-aplikasi-elite--filosofi)

---

## 1. Pendahuluan: Suhu vs Kalor

Banyak orang menganggap suhu dan kalor adalah hal yang sama. Dalam fisika, keduanya sangat berbeda:
- **Suhu (Temperatur):** Ukuran *rata-rata* energi kinetik mikroskopis partikel dalam suatu benda. Suhu menentukan seberapa "panas" atau "dingin" benda tersebut. (Sifat keadaan / *state variable*).
- **Kalor (Panas):** Energi yang **berpindah** dari benda bersuhu tinggi ke benda bersuhu rendah. Benda tidak "memiliki" kalor, benda memiliki *energi dalam*. Kalor hanyalah energi yang sedang transit. (Energi transfer).

> [!NOTE]
> **Hukum ke-0 Termodinamika:**
> Jika benda A setimbang termal (suhunya sama) dengan benda B, dan B setimbang dengan C, maka A pasti setimbang dengan C. Fakta sederhana inilah yang memungkinkan kita menggunakan **Termometer** (Benda B) untuk mengukur suhu tubuh manusia (A) dan suhu ruangan (C).

---

## 2. Suhu dan Skala Termometer

Untuk mengukur derajat panas, kita membutuhkan skala. Semua termometer bekerja berdasarkan sifat fisik benda yang berubah linear terhadap suhu (termometrik), seperti pemuaian raksa atau hambatan listrik.

### 2.1 Kalibrasi dan Konversi Skala
Setiap skala memiliki titik tetap bawah (es mencair) dan titik tetap atas (air mendidih) pada tekanan 1 atm.

<div align="center">

| Skala | Titik Bawah | Titik Atas | Rentang |
| :--- | :---: | :---: | :---: |
| **Celsius (C)** | 0° | 100° | 100 |
| **Reamur (R)** | 0° | 80° | 80 |
| **Fahrenheit (F)** | 32° | 212° | 180 |
| **Kelvin (K)** | 273 | 373 | 100 |

</div>

**Rumus Umum Konversi:**
$$ \frac{T_X - TitikBawah_X}{TitikAtas_X - TitikBawah_X} = \frac{T_Y - TitikBawah_Y}{TitikAtas_Y - TitikBawah_Y} $$

**Perbandingan Skala (C : R : F : K):**
$$ 5 : 4 : 9 : 5 $$

> [!IMPORTANT]
> **Mengapa Kelvin Tidak Menggunakan Derajat (°)?**
> Skala C, R, dan F adalah skala *arbitrary* (buatan manusia). $0^\circ\text{C}$ bukanlah titik di mana energi panas habis. Sebaliknya, **Kelvin adalah skala absolut**. Pada $0 \text{ K}$ (Nol Mutlak), seluruh gerakan termal partikel benar-benar berhenti. Karena ini adalah batas alam semesta terendah, ia adalah satuan ukur mutlak, bukan sekadar "derajat".

---

## 3. Pemuaian Zat

Ketika dipanaskan, partikel zat bergetar lebih kuat, sehingga jarak antar partikel merenggang. Inilah yang menyebabkan pemuaian.

### 3.1 Pemuaian Zat Padat
1. **Pemuaian Panjang ($\Delta L$):** Berlaku untuk benda berbentuk kawat/batang.
   $$ \Delta L = L_0 \cdot \alpha \cdot \Delta T $$
   $$ L_t = L_0 (1 + \alpha \Delta T) $$
   ($\alpha$ = koefisien muai panjang)

2. **Pemuaian Luas ($\Delta A$):** Benda berupa lempengan.
   $$ \Delta A = A_0 \cdot \beta \cdot \Delta T \quad (\beta = 2\alpha) $$

3. **Pemuaian Volume ($\Delta V$):** Benda pejal/3D.
   $$ \Delta V = V_0 \cdot \gamma \cdot \Delta T \quad (\gamma = 3\alpha) $$

> [!WARNING]
> **Aplikasi Teknis: Kaca Tahan Panas**
> Gelas kaca tebal yang disiram air panas akan pecah karena bagian dalam memuai tiba-tiba sementara bagian luar belum (kaca adalah konduktor buruk). Untuk gelas laboratorium (Pyrex), ilmuwan menambahkan *Boron* untuk membuat kaca borosilikat yang memiliki nilai $\alpha$ sangat kecil, sehingga hampir tidak memuai dan aman dipanaskan ekstrem.

### 3.2 Pemuaian Zat Cair dan Anomali Air
Zat cair umumnya hanya mengalami **pemuaian volume**. Namun, ada satu pengecualian mikroskopis yang menyelamatkan kehidupan di bumi: **Anomali Air**.

- Dari $0^\circ\text{C}$ ke $4^\circ\text{C}$, air bukannya memuai, tetapi malah **menyusut** (volume mengecil, massa jenis naik).
- Di atas $4^\circ\text{C}$, air memuai normal seperti cairan lain.

> [!IMPORTANT]
> **Divine Insight: Mengapa Danau Membeku dari Atas?**
> Saat suhu udara turun mendekati $0^\circ\text{C}$, air di permukaan menjadi dingin hingga $4^\circ\text{C}$. Karena massa jenisnya maksimum, air ini tenggelam ke dasar. Proses ini terus berlanjut hingga *seluruh* danau bersuhu $4^\circ\text{C}$. Saat suhu permukaan turun menjadi $0^\circ\text{C}$, es terbentuk. Es ini memiliki massa jenis lebih ringan dari air $4^\circ\text{C}$ di bawahnya, sehingga ia mengapung. Lapisan es ini kemudian bertindak sebagai selimut pelindung, menjaga air di bawahnya tetap cair agar ikan bertahan hidup selama musim dingin!

### 3.3 "Grandmaster Apex": Tegangan Termal (Thermal Stress)
Apa yang terjadi jika sebatang logam dipanaskan ($\Delta T$) tetapi ujung-ujungnya **ditahan kaku** sehingga tidak bisa memuai? Benda tersebut akan membangkitkan **Gaya Internal** yang sangat merusak untuk memaksa memuai.
Berdasarkan modulus elastisitas Young ($Y$):
$$ F = Y \cdot A \cdot \alpha \cdot \Delta T $$
> Inilah alasan jembatan tanpa celah memuai akan hancur melengkung. Gaya termal ini bisa mencapai jutaan Newton!

---

## 4. Kalor Pemanasan dan Kapasitas Kalor

Ketika kalor menyumbang pada perubahan suhu benda tanpa mengubah wujudnya:

$$ Q = m \cdot c \cdot \Delta T $$

Dimana:
- $Q$ = Kalor (Joule)
- $m$ = Massa benda (kg)
- $c$ = **Kalor Jenis / Specific Heat** ($\text{J/kg}\cdot^\circ\text{C}$)
- $\Delta T$ = Perubahan Suhu ($T_{\text{akhir}} - T_{\text{awal}}$)

> [!TIP]
> **Makna Fisis Kalor Jenis ($c$):**
> $c_{\text{air}}$ adalah $4200$, sedangkan $c_{\text{besi}}$ hanya $450$. Artinya, butuh jumlah energi yang *jauh lebih besar* untuk memanaskan air dibanding besi. Itulah sebabnya pada siang hari di pantai, pasir ($c$ rendah) terasa sangat panas, sementara lautan ($c$ tinggi) tetap sejuk, yang memicu terjadinya **Angin Laut**.

**Kapasitas Kalor ($C$):**
Besaran untuk satu benda utuh (bukan per kg massa).
$$ C = m \cdot c \implies Q = C \cdot \Delta T $$

---

## 5. Perubahan Wujud dan Kalor Laten

Saat zat mencapai titik lebur atau titik didihnya, energi kalor yang masuk **TIDAK** digunakan untuk menaikkan kecepatan partikel (suhu diam), melainkan digunakan untuk **memutuskan ikatan antar molekul** (mengubah wujud).

Kalor ini disebut Kalor "Tersembunyi" (Laten):

$$ Q = m \cdot L $$

- **Melebur / Membeku:** Gunakan Kalor Lebur ($L_f$).
- **Menguap / Mengembun:** Gunakan Kalor Uap ($L_v$).

### 5.1 Kalor Sublimasi (Padat $\leftrightarrow$ Gas)
Zat tertentu seperti Es Kering ($CO_2$ padat) atau kapur barus dapat menyublim menyerap kalor lompat wujud tanpa melewati fase cair. Laten Kalor Sublimasi ($L_s$) didefinisikan secara konseptual setara dengan totalitas kalor lebur ditambah kalor uap:
$$ L_s \approx L_f + L_v $$

---

## 6. Grafik Pemanasan (Kurva Suhu-Waktu)

Untuk merubah Es $-10^\circ\text{C}$ menjadi Uap $120^\circ\text{C}$, kalor harus dihitung **tahap demi tahap**:

1. **Memanaskan Es:** $Q_1 = m \cdot c_{es} \cdot \Delta T_1$ (Dari $-10^\circ$ ke $0^\circ$)
2. **Meleburkan Es:** $Q_2 = m \cdot L_f$ (Suhu tetap di $0^\circ$)
3. **Memanaskan Air:** $Q_3 = m \cdot c_{air} \cdot \Delta T_2$ (Dari $0^\circ$ ke $100^\circ$)
4. **Mendidihkan Air:** $Q_4 = m \cdot L_v$ (Suhu tetap di $100^\circ$)
5. **Memanaskan Uap:** $Q_5 = m \cdot c_{uap} \cdot \Delta T_3$ (Dari $100^\circ$ ke $120^\circ$)

**Total Kalor:** $Q_{total} = Q_1 + Q_2 + Q_3 + Q_4 + Q_5$

> [!WARNING]
> Anda sama sekali **TIDAK Boleh** menghitung dari $-10^\circ$ langsung melompat ke $120^\circ$ dengan rumus $mc\Delta T$ tunggal! Nilai $c$ untuk es, air, dan uap itu berbeda-beda.

---

## 7. Asas Black

Berdasarkan Hukum Kekekalan Energi, jika dua benda beda suhu dicampur dalam wadah tertutup yang terisolasi sempurna (kalorimeter):

$$ Q_{\text{lepas}} = Q_{\text{terima}} $$

- **Melepas Kalor:** Benda dengan suhu memula yang LEBIH TINGGI.
- **Menerima Kalor:** Benda dengan suhu memula yang LEBIH RENDAH (termasuk kalor untuk perubahan wujud, jika ada es yang melebur).

> [!TIP]
> **Strategi Soal Es & Air:**
> Jika mencampur es dan air bersuhu panas, jangan langsung berasumsi suhu akhirnya ($T_a$) berada di atas $0^\circ\text{C}$. Bisa jadi air panas tidak cukup energinya untuk meleburkan seluruh es! Suhu akhirnya mungkin akan mengendap konstan di $0^\circ\text{C}$ dengan sebagian es masih tersisa!

### 7.1 Kalorimeter Non-Ideal (Wadah Aktif)
Di soal tingkat dasar, wadah pencampur (Kalorimeter) diabaikan massa dan kapasitas kalornya. Di dunia nyata (dan OSN), **wadah logam juga ikut menyerap kalor**.
Maka rumus kesetimbangan meluas menjadi:
$$ Q_{lepas} = Q_{terima(\text{Zat Cair})} + Q_{terima(\text{Kalorimeter})} $$

> **Nilai Air (Water Equivalent - $W_k$):** Untuk mempermudah, kapasitas kalor wadah sering disetarakan seperti sekian gram "massa air" fiktif ($W_k = \frac{C_{\text{wadah}}}{c_{\text{air}}}$). Siswa cukup menambahkan gram ini ke total massa air dingin seolah-olah volume air bertambah.

---

## 8. Perpindahan Kalor

Terdapat tiga mode dasar bagaimana energi panas berpindah ruang:

### 8.1 Konduksi (Rambatan)
Perpindahan kalor melalui benda padat tanpa materi yang ikut berpindah (disebabkan getaran elektron & kisi atom).
**Laju Kalor ($H = Q/t$):**
$$ H = \frac{k \cdot A \cdot \Delta T}{L} $$
- $k$ = Konduktivitas Termal (Makin besar = penghantar baik / konduktor).
- Sifat ini dimanfaatkan dalam pembuatan panci (alas logam $k$-tinggi, gagang kayu/plastik $k$-rendah).

### 8.2 Konveksi (Aliran)
Perpindahan kalor yang disertai perpindahan massanya (terjadi pada fluida: cairan/gas).
$$ H = h \cdot A \cdot \Delta T $$
- $h$ = Koefisien konveksi.
- **Contoh Real:** Aliran air mendidih dari bawah ke atas panci, sistem pendingin radiator mobil, dan arus angin lokal/global.

### 8.3 Radiasi (Pancaran)
Perpindahan kalor dalam bentuk gelombang elektromagnetik (inframerah) **tanpa memerlukan medium**. Inilah cara energi matahari menembus ruang hampa mencapai bumi.
**Hukum Stefan-Boltzmann (Daya Radiasi, $P$):**
$$ P = e \cdot \sigma \cdot A \cdot T^4 $$
- $e$ = Emisivitas benda ($0 \leq e \leq 1$, Hitam ideal $e=1$).
- $\sigma$ = Tetapan Stefan-Boltzmann ($5,67 \times 10^{-8} \text{ W/m}^2\text{K}^4$).
- $T$ = Suhu mutlak dalam **Kelvin**.

---

## 9. Aplikasi Elite & Filosofi

### 9.1 Kesetaraan Mekanik-Kalor (Joule's Experiment)
James Prescott Joule membuktikan bahwa "Kalor" dan "Usaha Mekanik" adalah hal yang sama (keduanya energi).
**Konversi Dewa:**
$$ 1 \text{ kalori} = 4,184 \text{ Joule} $$
$$ 1 \text{ Joule} = 0,24 \text{ kalori} $$

> Aplikasi ekstrem: Suhu peluru yang jatuh perlahan meningkat murni karena usaha gesekan udara $\to$ energi kinetik musnah diubah $\to$ energi dalam (suhu peluru meroket).

### 9.2 Efek Rumah Kaca (Greenhouse Effect)
Berdasarkan hukum Radiasi, bumi menyerap radiasi tampak bermuka gelombang pendek dari matahari, namun memancarkannya kembali ke luar angkasa dalam bentuk *radiasi inframerah* bersuhu gelombang panjang (karena $T$ bumi rendah). Gas CO2 di udara transparan terhadap cahaya tampak, tetapi **memblokir / re-Radiasi** sebagian gelombang inframerah kembali ke bawah. Tanpa efek rumah kaca berderajat wajar—rata-rata suhu bumi adalah $-18^\circ\text{C}$!

---

## Lihat Juga
- [Usaha dan Energi](./04-usaha-energi.md)
- [Latihan Soal Bab 6](latihan-soal/README.md)
