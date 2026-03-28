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

$$

\Large \vec{p} = \gamma m_0 \vec{v} = \frac{m_0 \vec{v}}{\sqrt{1 - \frac{v^2}{c^2}}}

$$

> Tanpa faktor Lorentz ($\gamma$), perhitungan momentum roket antar bintang atau partikel atom akan salah total.

Dimana:
- $\vec{p}$ = Momentum (kg·m/s)
- $m$ = Massa benda (kg)
- $\vec{v}$ = Kecepatan benda (m/s)

> [!WARNING]
> **Momentum adalah VEKTOR!**
> Tanda positif/negatif pada momentum menunjukkan **arah**. Dalam soal tumbukan, tentukan arah positif terlebih dahulu (biasanya ke kanan), lalu benda yang bergerak ke kiri memiliki momentum negatif.

### 2.2 Asal-Usul: Momentum dari Hukum Newton II
Hukum Newton II dalam bentuk aslinya (yang ditulis Newton sendiri) bukan $F = ma$, melainkan:

$$

\Large \vec{F} = \frac{d\vec{p}}{dt} = \frac{\Delta \vec{p}}{\Delta t}

$$

Artinya: **Gaya adalah laju perubahan momentum**. Bentuk $F = ma$ hanyalah kasus khusus saat massa konstan ($F = \frac{d(mv)}{dt} = m\frac{dv}{dt} = ma$).

> [!TIP]
> **Mengapa Bentuk Momentum Lebih Fundamental?**
> Karena bentuk $F = ma$ tidak berlaku untuk benda yang massanya berubah (seperti roket yang membakar bahan bakar). Bentuk $F = \frac{dp}{dt}$ selalu berlaku untuk semua situasi.

### 2.3 Satuan dan Dimensi
- Satuan SI: $\text{kg} \cdot \text{m/s}$ (tidak punya nama khusus)
- Dimensi: $[M][L][T]^{-1}$
- Satuan alternatif: $\text{N} \cdot \text{s}$ (Newton-sekon), yang identik secara dimensional

---

## 3. Impuls

### 3.1 Definisi dan Teorema Impuls-Momentum
Impuls ($\vec{J}$) adalah efek kumulatif gaya yang bekerja selama selang waktu tertentu:

$$

\Large \vec{J} = \vec{F} \cdot \Delta t = \Delta \vec{p} = m\vec{v}_2 - m\vec{v}_1

$$

Ini adalah **Teorema Impuls-Momentum**: Impuls yang diberikan pada benda sama dengan perubahan momentumnya.

> [!NOTE]
> **Asal-Usul Teorema:**
> Dari $F = \frac{\Delta p}{\Delta t}$, kalikan kedua ruas dengan $\Delta t$:
> 

$$

\Large F \cdot \Delta t = \Delta p

$$

> Ruas kiri = Impuls. Ruas kanan = Perubahan momentum. Q.E.D.

### 3.2 Impuls dari Grafik $F$-$t$
Jika gaya berubah terhadap waktu, maka impuls adalah **luas daerah di bawah kurva** pada grafik $F$ terhadap $t$:
- **Gaya Konstan:** Luas persegi panjang = $F \cdot \Delta t$
- **Gaya Linier:** Luas segitiga = $\frac{1}{2} F_{max} \cdot \Delta t$
- **Gaya Arbitrer:** Gabungkan luas geometri atau gunakan integral ($J = \int F \, dt$)

### 3.3 Aplikasi Keselamatan: Memperbesar $\Delta t$
Dari $F = \frac{\Delta p}{\Delta t}$, jika $\Delta p$ sama, maka:
- **$\Delta t$ kecil** → Gaya besar (bahaya!)
- **$\Delta t$ besar** → Gaya kecil (aman!)

<div align="center">

| Perangkat | Mekanisme | Efek |
| :--- | :--- | :--- |
| **Airbag** | Memperpanjang waktu tumbukan kepala | Gaya tumbukan berkurang drastis |
| **Helm** | Busa menyerap deformasi | Waktu tumbukan otak diperpanjang |
| **Matras Lompat Tinggi** | Badan "tenggelam" perlahan | Waktu penghentian menjadi lama |
| **Teknik Guling (Parkour)** | Mengubah tumbukan menjadi putaran | Menyebar gaya ke seluruh tubuh |

</div>

> [!IMPORTANT]
> **Divine Insight:**
> Semua perangkat keselamatan di dunia bekerja dengan prinsip yang sama: **memperbesar $\Delta t$** untuk memperkecil gaya puncak ($F$). Ini adalah salah satu aplikasi fisika paling penting dalam kehidupan nyata.

---

## 4. Hukum Kekekalan Momentum Linear (HKML)

### 4.1 Derivasi dari Hukum Newton III
**Bukti Formal:**
Perhatikan dua benda ($m_1, m_2$) yang saling berinteraksi (tumbukan):
- Menurut Newton III: $\vec{F}_{12} = -\vec{F}_{21}$ (aksi-reaksi)
- Maka:

$$

\Large \frac{\Delta \vec{p}_1}{\Delta t} = -\frac{\Delta \vec{p}_2}{\Delta t}

$$

- Kalikan $\Delta t$: $\Delta \vec{p}_1 = -\Delta \vec{p}_2$
- Artinya:

$$

\Large \Delta \vec{p}_1 + \Delta \vec{p}_2 = 0

$$

$$
\Large \mathbf{\vec{p}_{total,\text{awal}} = \vec{p}_{total,\text{akhir}}}

$$

$$
\Large m_1 v_1 + m_2 v_2 = m_1 v_1' + m_2 v_2'

$$

**Q.E.D.** — Momentum total sistem selalu konstan.

### 4.3 "The Apex": Teorema Noether (Simetri Translasi Ruang)
Mengapa momentum harus kekal? 
Fisikawan Emmy Noether membuktikan bahwa momentum kekal karena alam semesta memiliki **Simetri Translasi Ruang** (Homogenitas Ruang). Artinya, hukum fisika di Jakarta sama dengan hukum fisika di bulan Mars. Karena hukum alam tidak bergantung pada *lokasi* spesifik di ruang hampa, maka momentum sistem tertutup harus bernilai tetap. Inilah landasan filosofis terdalam dari mekanika.

### 4.4 Syarat Berlakunya HKML
HKML hanya berlaku jika:
1. **Sistem tertutup** (tidak ada gaya luar netto yang bekerja, atau gaya luar jauh lebih kecil dari gaya internal tumbukan).
2. **Resultan gaya luar = 0** ($\Sigma \vec{F}_{ext} = 0$).

> [!WARNING]
> **Kesalahan Fatal yang Sering Terjadi:**
> - Gesekan lantai adalah gaya luar → HKML masih bisa digunakan jika waktu tumbukan sangat singkat (gaya gesek $\ll$ gaya tumbukan).
> - Gravitasi adalah gaya luar → HKML berlaku pada sumbu horizontal, tetapi **tidak** pada sumbu vertikal (kecuali benda jatuh bebas dalam sistem tertutup).

---

## 5. Tumbukan

### 5.1 Koefisien Restitusi ($e$)
Koefisien restitusi mengukur "keelastisan" tumbukan:

$$

\Large e = -\frac{v_1' - v_2'}{v_1 - v_2} = \frac{\text{kecepatan relatif setelah}}{\text{kecepatan relatif sebelum}}

$$

<div align="center">

| Nilai $e$ | Jenis Tumbukan | Sifat |
| :---: | :--- | :--- |
| $e = 1$ | **Lenting Sempurna** | $EK$ kekal sempurna |
| $0 < e < 1$ | **Lenting Sebagian** | Sebagian $EK$ hilang |
| $e = 0$ | **Tidak Lenting Sempurna** | Benda menyatu, $EK$ hilang maksimum |

</div>

### 5.2 Tumbukan Lenting Sempurna ($e = 1$)
Dua hukum berlaku sekaligus:
1. **HKML:** $m_1 v_1 + m_2 v_2 = m_1 v_1' + m_2 v_2'$
2. **Kekekalan EK:** $\frac{1}{2}m_1 v_1^2 + \frac{1}{2}m_2 v_2^2 = \frac{1}{2}m_1 v_1'^2 + \frac{1}{2}m_2 v_2'^2$

**Rumus Cepat (target awalnya diam, $v_2 = 0$):**

$$

\Large v_1' = \frac{m_1 - m_2}{m_1 + m_2} v_1

$$

$$
\Large v_2' = \frac{2m_1}{m_1 + m_2} v_1

$$

> [!TIP]
> **Kasus Spesial Lenting Sempurna:**
> - **$m_1 = m_2$:** Benda pertama berhenti ($v_1' = 0$), benda kedua bergerak dengan kecepatan awal benda pertama ($v_2' = v_1$). Contoh: Bola biliar.
> - **$m_1 \gg m_2$:** Benda besar hampir tidak terpengaruh ($v_1' \approx v_1$), benda kecil terpental dengan $v_2' \approx 2v_1$.
> - **$m_1 \ll m_2$:** Benda kecil terpental balik ($v_1' \approx -v_1$), benda besar diam ($v_2' \approx 0$). Contoh: Bola memantul di dinding.

### 5.3 Tumbukan Tidak Lenting Sempurna ($e = 0$)
Kedua benda **menyatu** setelah tumbukan dan bergerak dengan kecepatan yang sama:

$$

\Large m_1 v_1 + m_2 v_2 = (m_1 + m_2) v'

$$

$$
\Large v' = \frac{m_1 v_1 + m_2 v_2}{m_1 + m_2}

$$

> [!CAUTION]
> **Energi "Hilang":**
> Pada tumbukan tidak lenting sempurna, energi kinetik yang hilang berubah menjadi panas, bunyi, dan deformasi. Jumlah energi yang hilang:
> 

$$

\Large \Delta EK = \frac{1}{2} \frac{m_1 m_2}{m_1 + m_2} (v_1 - v_2)^2

$$

### 5.4 Tumbukan Lenting Sebagian ($0 < e < 1$)
Gunakan dua persamaan:
1. **HKML:** $m_1 v_1 + m_2 v_2 = m_1 v_1' + m_2 v_2'$
2. **Restitusi:** $e = -\frac{v_1' - v_2'}{v_1 - v_2}$

Selesaikan secara simultan untuk mendapatkan $v_1'$ dan $v_2'$.

---

## 6. Tumbukan dalam 2 Dimensi

### 6.1 Prinsip Dasar
Dalam tumbukan miring (seperti bola biliar), HKML berlaku **secara terpisah** pada setiap sumbu:
- **Sumbu $x$:** $m_1 v_{1x} + m_2 v_{2x} = m_1 v_{1x}' + m_2 v_{2x}'$
- **Sumbu $y$:** $m_1 v_{1y} + m_2 v_{2y} = m_1 v_{1y}' + m_2 v_{2y}'$

### 6.2 Teknik Pemecahan
1. Tentukan sumbu $x$ (biasanya searah gerak awal benda pertama).
2. Uraikan semua kecepatan ke komponen $x$ dan $y$ menggunakan trigonometri.
3. Terapkan HKML pada masing-masing sumbu secara independen.
4. Gabungkan hasil untuk mendapatkan besar dan arah kecepatan akhir.

> [!IMPORTANT]
> **Apex Detail: Tumbukan Miring & Restitusi ($e$):**
> Pada tumbukan 2D, koefisien restitusi ($e$) **HANYA** berlaku pada komponen kecepatan yang tegak lurus bidang sentuh (sumbu normal). Komponen kecepatan yang sejajar bidang sentuh (sumbu tangensial) tidak berubah jika bidang tersebut licin sempurna.

> [!TIP]
> **Fakta Biliar:**
> Pada tumbukan lenting sempurna antara dua bola bermassa sama (salah satu diam), sudut antara kedua bola setelah tumbukan selalu **$90°$**. Ini adalah konsekuensi matematis murni dari HKML + Kekekalan EK.

---

## 7. Pusat Massa (Center of Mass)

### 7.1 Definisi
Pusat massa adalah titik rata-rata posisi massa dalam suatu sistem:

$$

\Large x_{cm} = \frac{\sum m_i x_i}{\sum m_i} = \frac{m_1 x_1 + m_2 x_2 + \ldots}{m_1 + m_2 + \ldots}

$$

### 7.2 Kecepatan Pusat Massa

$$

\Large v_{cm} = \frac{p_{total}}{m_{total}} = \frac{m_1 v_1 + m_2 v_2}{m_1 + m_2}

$$

### 7.3 Massa Tereduksi (Reduced Mass - $\mu$)
Untuk sistem dua benda yang saling berinteraksi (seperti planet dan satelit, atau dua atom), kita bisa menyederhanakan masalah dengan menganggap salah satu benda diam dan benda lainnya memiliki massa "terreduksi":

$$

\Large \mu = \frac{m_1 \cdot m_2}{m_1 + m_2}

$$

Ini adalah teknik "Sakti" untuk menghitung energi kinetik relatif sistem tanpa harus menganalisis dua benda secara terpisah: $EK_{\text{rel}} = \frac{1}{2}\mu v_{\text{rel}}^2$.

> [!IMPORTANT]
> **Properti Ajaib Pusat Massa:**
> Pada sistem tertutup (tanpa gaya luar), pusat massa bergerak dengan **kecepatan konstan** (atau tetap diam jika awalnya diam) — bahkan saat terjadi tumbukan atau ledakan di dalam sistem. Ini adalah cara lain menyatakan HKML.

---

## 8. Hubungan Momentum dan Energi

### 8.1 Rumus Penghubung
Energi Kinetik dapat dinyatakan dalam momentum:

$$

\Large EK = \frac{p^2}{2m}

$$

> [!NOTE]
> **Asal-Usul:**
> Dari $p = mv \implies v = \frac{p}{m}$. Substitusi ke $EK = \frac{1}{2}mv^2$:
> 

$$

\Large EK = \frac{1}{2}m\left(\frac{p}{m}\right)^2 = \frac{p^2}{2m}

$$

> Rumus ini sangat berguna dalam soal olimpiade yang melibatkan momentum dan energi sekaligus.

### 8.2 Analisis Kehilangan Energi pada Tumbukan
Pada tumbukan:
- **Momentum selalu kekal** (HKML berlaku).
- **Energi kinetik tidak selalu kekal** (hanya pada tumbukan lenting sempurna).
- Energi yang "hilang" berubah menjadi panas, bunyi, dan deformasi benda.

---

## 9. Aplikasi Elite

### 9.1 Pendulum Balistik
Sebuah peluru bermassa $m$ menghantam balok bermassa $M$ yang tergantung (pendulum) dan tertanam di dalamnya. Sistem ini menggabungkan:
1. **HKML** (saat tumbukan tidak lenting sempurna): $mv = (m + M)v'$
2. **HKEM** (setelah tumbukan, balok+peluru berayun naik): $\frac{1}{2}(m+M)v'^2 = (m+M)gh$

**Rumus Cepat Kecepatan Peluru:**

$$

\Large v_{peluru} = \frac{m + M}{m} \sqrt{2gh}

$$

> [!IMPORTANT]
> **Mengapa Ini Istimewa:**
> Pendulum balistik adalah contoh sempurna di mana **dua prinsip kekekalan digunakan berurutan**: HKML selama tumbukan (karena EK tidak kekal), lalu HKEM setelah tumbukan (karena tidak ada gaya non-konservatif). Ini adalah soal "pembunuh" di ujian masuk universitas.

### 9.2 Prinsip Roket (Sistem Massa Berubah)
Roket bekerja berdasarkan HKML: gas dikeluarkan ke belakang, roket terdorong ke depan.

**Persamaan Gaya Dorong Roket:**

$$

\Large F_{thrust} = v_{rel} \cdot \frac{dm}{dt}

$$

- $v_{rel}$ = Kecepatan gas relatif terhadap roket (m/s)
- $\frac{dm}{dt}$ = Laju pembakaran bahan bakar (kg/s)

> [!CAUTION]
> **Fakta Mencengangkan:**
> Roket bisa bekerja di luar angkasa (vakum) karena prinsip kekekalan momentum tidak memerlukan medium. Momentum gas ke belakang = momentum roket ke depan. Ini membantah miskonsepsi bahwa roket "mendorong udara".

### 9.3 Ledakan (Kebalikan Tumbukan)
Pada ledakan, benda yang awalnya diam terpecah menjadi beberapa bagian. HKML tetap berlaku:

$$

\Large 0 = m_1 v_1' + m_2 v_2' + \ldots

$$

Artinya, jumlah vektor momentum semua pecahan setelah ledakan = **nol**.

---

## Lihat Juga
- [Usaha dan Energi](./04-usaha-energi.md)
- [Latihan Soal Bab 5](latihan-soal/README.md)
