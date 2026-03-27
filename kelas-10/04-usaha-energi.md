# Bab 4: Usaha, Energi, dan Daya

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Pendahuluan](#1-pendahuluan)
2. [Usaha (Work)](#2-usaha-work)
3. [Energi](#3-energi)
4. [Teorema Usaha-Energi](#4-teorema-usaha-energi)
5. [Gaya Konservatif dan Non-Konservatif](#5-gaya-konservatif-dan-non-konservatif)
6. [Hukum Kekekalan Energi Mekanik](#6-hukum-kekekalan-energi-mekanik)
7. [Daya dan Efisiensi](#7-daya-dan-efisiensi)
8. [Aplikasi Elite](#8-aplikasi-elite)

---

## 1. Pendahuluan
Dalam Bab 3 (Dinamika), kita menganalisis gerak menggunakan **gaya** (vektor). Bab ini memperkenalkan pendekatan yang lebih elegan: **Energi** (skalar). Keuntungannya? Kita tidak perlu lagi memecah gaya ke sumbu $x$ dan $y$—cukup menganalisis "neraca energi" di titik awal dan akhir.

> [!NOTE]
> **Filosofi Energi:**
> Energi tidak pernah hilang dan tidak pernah muncul dari ketiadaan. Ia hanya **berpindah** dari satu bentuk ke bentuk lain. Prinsip ini adalah salah satu hukum paling fundamental di seluruh fisika: **Hukum Kekekalan Energi**.

---

## 2. Usaha (Work)

### 2.1 Definisi Formal
Usaha ($W$) adalah transfer energi yang terjadi ketika sebuah **gaya** menyebabkan benda mengalami **perpindahan**. Secara matematis, usaha adalah **perkalian titik (Dot Product)** antara vektor gaya dan vektor perpindahan:

$$ W = \vec{F} \cdot \vec{s} = F \cdot s \cdot \cos\theta $$

Dimana:
- $W$ = Usaha (Joule, J)
- $F$ = Besar gaya (Newton, N)
- $s$ = Besar perpindahan (meter, m)
- $\theta$ = Sudut antara arah gaya dan arah perpindahan

> [!TIP]
> **Asal-Usul Rumus ($\cos\theta$):**
> Mengapa ada $\cos\theta$? Karena hanya **komponen gaya yang searah dengan perpindahan** yang melakukan usaha. Jika Anda menarik koper dengan tali miring $30^\circ$, hanya komponen horizontal gaya ($F \cos 30^\circ$) yang "bekerja" memindahkan koper.

### 2.2 Tanda Usaha (Positif, Negatif, Nol)
| Kondisi | $\theta$ | $\cos\theta$ | Tanda $W$ | Makna Fisis |
| :--- | :---: | :---: | :---: | :--- |
| Gaya searah perpindahan | $0^\circ$ | $+1$ | **Positif** | Gaya **mempercepat** benda |
| Gaya berlawanan perpindahan | $180^\circ$ | $-1$ | **Negatif** | Gaya **memperlambat** benda (misalnya gesekan) |
| Gaya tegak lurus perpindahan | $90^\circ$ | $0$ | **Nol** | Gaya **tidak melakukan usaha** (misalnya gaya normal) |

> [!IMPORTANT]
> **Insight Kritis:**
> Gaya Normal ($N$) dan Gaya Sentripetal **tidak pernah melakukan usaha** karena mereka selalu tegak lurus terhadap perpindahan ($\theta = 90^\circ$). Ini adalah fakta yang sering dilupakan siswa.

### 2.3 Usaha oleh Beberapa Gaya
Jika banyak gaya bekerja pada satu benda, maka usaha total adalah jumlah usaha masing-masing gaya:
$$ W_{total} = W_1 + W_2 + W_3 + \ldots $$

Atau ekuivalen, usaha oleh resultan gaya:
$$ W_{total} = \Sigma F \cdot s \cdot \cos\theta $$

### 2.4 Usaha dari Grafik Gaya vs Perpindahan ($F$-$s$)
Jika gaya tidak konstan (berubah-ubah), maka usaha **tidak bisa** dihitung langsung dengan $W = Fs$. Sebaliknya, usaha adalah **luas daerah di bawah kurva** pada grafik $F$ terhadap $s$.

- **Gaya Konstan:** Grafik berupa garis horizontal $\rightarrow$ Luas persegi panjang.
- **Gaya Linier (Pegas):** Grafik berupa garis miring $\rightarrow$ Luas segitiga.
- **Gaya Arbitrer:** Gabungkan luas geometri (trapesium, segitiga, dll).

> [!TIP]
> **Koneksi ke Kalkulus:**
> Secara teknis, usaha oleh gaya variabel adalah integral: $W = \int_{s_1}^{s_2} F(s) \, ds$. Di level SMA, kita menghitungnya dengan luas geometri biasa.

---

## 3. Energi

Energi adalah kemampuan suatu benda atau sistem untuk melakukan usaha. Dalam mekanika, ada dua bentuk energi utama:

### 3.1 Energi Kinetik ($EK$)
Energi yang dimiliki benda karena **geraknya**.

$$ EK = \frac{1}{2} m v^2 $$

Dimana:
- $m$ = Massa benda (kg)
- $v$ = Kecepatan benda (m/s)

> [!NOTE]
> **Asal-Usul Rumus $EK = \frac{1}{2}mv^2$:**
> Dari Hukum Newton II: $F = ma$. Jika gaya konstan bekerja pada benda dari diam ($v_0 = 0$) sejauh $s$:
> $$ W = F \cdot s = (ma)(s) $$
> Dari kinematika: $v^2 = 2as \implies s = \frac{v^2}{2a}$. Substitusi:
> $$ W = ma \cdot \frac{v^2}{2a} = \frac{1}{2}mv^2 $$
> Maka usaha yang dilakukan gaya tersebut tersimpan sebagai energi kinetik.

### 3.2 Energi Potensial Gravitasi ($EP$)
Energi yang dimiliki benda karena **posisinya** terhadap titik acuan (ketinggian).

$$ EP = mgh $$

Dimana:
- $h$ = Ketinggian benda terhadap titik acuan (m)
- $g$ = Percepatan gravitasi ($\approx 10 \text{ m/s}^2$)

> [!WARNING]
> **Titik Acuan ($h=0$) Itu Bebas!**
> Anda boleh meletakkan titik acuan di mana saja (lantai, meja, dasar lembah). Yang penting adalah **selisih ketinggian** ($\Delta h$) antara dua posisi, bukan ketinggian absolutnya. Pilihlah titik acuan yang paling menyederhanakan perhitungan.

### 3.3 Energi Potensial Pegas ($EP_{\text{pegas}}$)
Energi yang tersimpan dalam pegas yang terkompresi atau teregang.

$$ EP_{\text{pegas}} = \frac{1}{2} k (\Delta x)^2 $$

Dimana:
- $k$ = Konstanta pegas / kekakuan pegas (N/m)
- $\Delta x$ = Perubahan panjang pegas dari posisi alami (m)

> [!NOTE]
> **Asal-Usul Rumus (Dari Grafik Luas):**
> Gaya pegas menurut Hukum Hooke: $F = k \cdot \Delta x$. Grafik $F$ vs $\Delta x$ adalah garis lurus melalui titik asal. Usaha yang dilakukan pegas (= energi yang tersimpan) adalah luas segitiga di bawah garis tersebut:
> $$ W = \text{Luas} = \frac{1}{2} \times \text{alas} \times \text{tinggi} = \frac{1}{2} \times \Delta x \times k\Delta x = \frac{1}{2} k (\Delta x)^2 $$

> [!TIP]
> **Usaha Pegas dari Posisi Non-Nol ($x_1 \to x_2$):**
> Jika pegas sudah teregang dari $x_1$ dan ditarik lebih jauh ke $x_2$, maka usahanya bukan $\frac{1}{2}kx_2^2$ saja, melainkan:
> $$ W_{pegas} = \frac{1}{2}k x_1^2 - \frac{1}{2}k x_2^2 $$
> Ini adalah **selisih luas trapesium** pada grafik $F$-$x$, bukan luas segitiga dari nol.

$$ EM = EK + EP $$

> [!TIP]
> **Preview: Energi Kinetik Rotasi ($EK_{rot}$):**
> Benda yang tidak hanya bergeser tapi juga berputar (seperti roda menggelinding) memiliki energi tambahan:
> $$ EK_{rot} = \frac{1}{2} I \omega^2 $$
> - $I$ = Momen Inersia (ukuran kelembaman rotasi)
> - $\omega$ = Kecepatan sudut (rad/s)
> Inilah alasan mengapa benda yang menggelinding di bidang miring akan tiba di bawah lebih lambat daripada benda yang meluncur licin; sebagian energi potensialnya "dicuri" untuk memutar benda tersebut.

---

## 4. Teorema Usaha-Energi

### 4.1 Pernyataan Teorema (The Bridge)
Ini adalah "jembatan" paling penting yang menghubungkan konsep Usaha dan Energi:

$$ W_{total} = \Delta EK = EK_2 - EK_1 $$
$$ W_{total} = \frac{1}{2}mv_2^2 - \frac{1}{2}mv_1^2 $$

> [!IMPORTANT]
> **Makna Fisis:**
> - Jika usaha total **positif** ($W > 0$): Benda **bertambah cepat** ($v_2 > v_1$).
> - Jika usaha total **negatif** ($W < 0$): Benda **bertambah lambat** ($v_2 < v_1$).
> - Jika usaha total **nol** ($W = 0$): Kecepatan benda **tetap** (GLB).

### 4.2 Kapan Menggunakan Teorema Ini?
Gunakan Teorema Usaha-Energi ketika:
- Diminta mencari **kecepatan akhir** setelah gaya bekerja sejauh $s$.
- Diminta mencari **perpindahan** yang diperlukan untuk menghentikan benda.
- Situasi melibatkan **gaya gesek** (non-konservatif) sehingga HKEM murni tidak berlaku.

---

## 5. Gaya Konservatif dan Non-Konservatif

### 5.1 Gaya Konservatif
Gaya yang usahanya **tidak bergantung pada jalur** yang ditempuh, melainkan hanya pada posisi awal dan akhir. Usaha oleh gaya konservatif dalam satu siklus tertutup selalu nol.

**Contoh:** Gravitasi ($mg$), Gaya Pegas ($kx$).

> [!TIP]
> **Analogi Sederhana:**
> Bayangkan mendaki gunung. Entah Anda naik lewat jalan berliku atau tangga lurus, selisih energi potensial gravitasi Anda tetap sama ($mgh$). Gravitasi tidak peduli *bagaimana* Anda naik, hanya peduli *seberapa tinggi* Anda naik.

### 5.2 Gaya Non-Konservatif
Gaya yang usahanya **bergantung pada jalur** (panjang lintasan). Energi yang "hilang" akibat gaya ini biasanya berubah menjadi **panas** atau **bunyi**.

**Contoh:** Gesekan ($f_k$), Hambatan Udara.

**Usaha oleh gesekan:**
$$ W_{gesek} = -f_k \cdot s $$
*(Selalu negatif karena gesekan selalu berlawanan arah perpindahan).*

---

## 6. Hukum Kekekalan Energi Mekanik (HKEM)

### 6.1 Derivasi HKEM dari Teorema Usaha-Energi (Bukti Formal)
Mengapa HKEM berlaku? Karena ia **lahir** dari Teorema Usaha-Energi.

**Bukti:**
Jika satu-satunya gaya yang bekerja adalah gravitasi, maka:
$$ W_{gravitasi} = \Delta EK $$
Usaha gravitasi juga sama dengan negatif perubahan Energi Potensial:
$$ W_{gravitasi} = -(EP_2 - EP_1) = EP_1 - EP_2 $$
Substitusi:
$$ EP_1 - EP_2 = EK_2 - EK_1 $$
Pindahkan ruas:
$$ \mathbf{EK_1 + EP_1 = EK_2 + EP_2} $$
**Q.E.D.** (Quod Erat Demonstrandum — Terbukti!)

### 6.2 Sistem Konservatif (Tanpa Gesekan)
Jika **hanya gaya konservatif** yang bekerja, maka energi mekanik total di setiap titik selalu sama:

$$ EM_1 = EM_2 $$
$$ EK_1 + EP_1 = EK_2 + EP_2 $$
$$ \frac{1}{2}mv_1^2 + mgh_1 = \frac{1}{2}mv_2^2 + mgh_2 $$

> [!NOTE]
> **Keindahan HKEM:**
> Perhatikan bahwa massa ($m$) bisa **dicoret** dari kedua ruas! Artinya, kecepatan benda di dasar luncuran **tidak bergantung pada massanya**, hanya pada ketinggian. Sebuah kelereng dan bola bowling akan tiba di bawah dengan kecepatan yang sama (tanpa gesekan).

### 6.3 Sistem Non-Konservatif (Dengan Gesekan)
Jika ada gaya gesekan, maka energi mekanik berkurang sebesar usaha gesekan:

$$ EM_1 + W_{gesek} = EM_2 $$
$$ EK_1 + EP_1 - f_k \cdot s = EK_2 + EP_2 $$

*(Energi yang "hilang" berubah menjadi energi panas/kalor, $Q = f_k \cdot s$).*

> [!NOTE]
> **Visualisasi: Metode Diagram Batang Energi (Bar Chart):**
> Untuk mempermudah analisis HKEM, gunakan diagram batang untuk membandingkan $EK$ dan $EP$ di dua posisi berbeda.
> - **Aturan:** Total tinggi batang di posisi 1 harus sama dengan total tinggi batang di posisi 2 (ditambah batang usaha non-konservatif jika ada).
> - **Manfaat:** Sangat membantu memvisualisasikan "aliran" energi tanpa harus langsung masuk ke rumus angka yang rumit.

---

## 7. Daya dan Efisiensi

### 7.1 Daya ($P$)
Daya adalah laju transfer energi atau laju melakukan usaha per satuan waktu:

$$ P = \frac{W}{t} $$

Satuan SI-nya adalah **Watt** ($\text{W} = \text{J/s}$).

**Rumus Alternatif (untuk kecepatan konstan):**
$$ P = F \cdot v $$

> [!NOTE]
> **Asal-Usul $P = Fv$:**
> $$ P = \frac{W}{t} = \frac{F \cdot s}{t} = F \cdot \frac{s}{t} = F \cdot v $$
> Rumus ini sangat berguna untuk menghitung daya mesin kendaraan yang bergerak dengan kecepatan konstan melawan gaya hambat.

**Satuan Praktis:**
- $1 \text{ HP (Horse Power)} = 746 \text{ Watt}$
- $1 \text{ kWh (kilowatt-hour)} = 3,6 \times 10^6 \text{ Joule}$

### 7.2 Efisiensi ($\eta$)
Dalam dunia nyata, tidak ada mesin yang 100% mengubah energi input menjadi usaha berguna. Selalu ada energi yang "bocor" menjadi panas, bunyi, atau getaran.

$$ \eta = \frac{W_{\text{berguna}}}{W_{\text{input}}} \times 100\% = \frac{P_{\text{output}}}{P_{\text{input}}} \times 100\% $$

- Efisiensi selalu bernilai $0\% < \eta \leq 100\%$.
- Mesin ideal ($\eta = 100\%$) tidak ada di alam nyata (Hukum Termodinamika ke-2).

---

## 8. Aplikasi Elite

### 8.1 Dinamika Loop Rollercoaster (Kecepatan Kritis)
Sebuah benda meluncur dari ketinggian $H$ dan memasuki sebuah loop (lingkaran vertikal) berjari-jari $R$. Berapakah ketinggian minimum ($H_{min}$) agar benda tidak jatuh di puncak loop?

**Syarat di Puncak Loop:**
Di titik tertinggi lingkaran, gaya sentripetal disediakan oleh berat benda (gaya normal minimum = 0):
$$ mg = \frac{mv_{top}^2}{R} \implies v_{top}^2 = gR $$

**Gunakan HKEM (dari awal ke puncak loop):**
$$ mgH = mg(2R) + \frac{1}{2}mv_{top}^2 $$
$$ gH = 2gR + \frac{1}{2}(gR) $$
$$ \mathbf{H_{min} = \frac{5}{2}R} $$

> [!IMPORTANT]
> **Hasil Luar Biasa:**
> Ketinggian minimum yang dibutuhkan adalah $H = 2,5R$, terlepas dari massa benda. Ini adalah prinsip yang digunakan oleh insinyur perancang rollercoaster di seluruh dunia.

### 8.2 Kecepatan Lepas (Escape Velocity)
Berapakah kecepatan minimum yang dibutuhkan roket agar bisa lepas dari gravitasi bumi?

**Energi Potensial Gravitasi Universal:**
$$ EP = -\frac{GMm}{r} $$

**Syarat Lepas:** Di titik tak hingga ($r \to \infty$), energi potensial = 0 dan kecepatan minimum = 0.
$$ EK_1 + EP_1 = 0 $$
$$ \frac{1}{2}mv_{esc}^2 - \frac{GMm}{R} = 0 $$
$$ v_{esc} = \sqrt{\frac{2GM}{R}} $$

Substitusi $g = \frac{GM}{R^2} \implies GM = gR^2$:
$$ \mathbf{v_{esc} = \sqrt{2gR}} $$

Dengan $g = 9,8$; $R_{\text{bumi}} = 6,4 \times 10^6$:
$$ v_{esc} \approx 11.200 \text{ m/s} \approx \mathbf{11,2 \text{ km/s}} $$

> [!CAUTION]
> **Fakta Mencengangkan:**
> Kecepatan lepas tidak bergantung pada massa roket! Sebuah bola tenis dan pesawat ulang-alik membutuhkan kecepatan lepas yang sama. Yang berbeda hanyalah **energi (bahan bakar)** yang dibutuhkan untuk mencapai kecepatan tersebut.

---

## 9. Pesawat Sederhana dan Keuntungan Mekanis

Pesawat sederhana adalah alat yang mempermudah pekerjaan manusia. Prinsip dasarnya: **Usaha Input = Usaha Output** (dalam kondisi ideal tanpa gesekan).
$$ F_1 \cdot s_1 = F_2 \cdot s_2 $$

### 9.1 Keuntungan Mekanis (KM)
Keuntungan Mekanis menyatakan berapa kali lipat gaya diperkuat oleh pesawat sederhana:
$$ KM = \frac{F_{beban}}{F_{kuasa}} = \frac{s_{kuasa}}{s_{beban}} $$

### 9.2 Tuas (Pengungkit)
Tuas dibagi menjadi tiga jenis berdasarkan posisi titik tumpu (T), beban (B), dan kuasa (K):
| Jenis | Susunan | Contoh |
| :---: | :--- | :--- |
| **I** | B — T — K | Gunting, Jungkat-jungkit |
| **II** | T — B — K | Pembuka botol, Gerobak |
| **III** | T — K — B | Pinset, Lengan manusia |

Rumus Tuas:
$$ F_1 \cdot l_1 = F_2 \cdot l_2 $$
$$ KM = \frac{l_{kuasa}}{l_{beban}} $$

### 9.3 Bidang Miring
Bidang miring memperkecil gaya yang dibutuhkan untuk menaikkan benda ke ketinggian $h$ dengan menempuh lintasan miring sepanjang $s$:
$$ F \cdot s = W \cdot h \implies F = W \cdot \frac{h}{s} = mg \sin\theta $$
$$ KM = \frac{s}{h} = \frac{1}{\sin\theta} $$

### 9.4 Katrol
| Jenis | KM | Keterangan |
| :--- | :---: | :--- |
| **Katrol Tetap** | $1$ | Hanya mengubah arah gaya |
| **Katrol Bebas** | $2$ | Memperkecil gaya $2\times$ |
| **Katrol Majemuk** ($n$ tali) | $n$ | Memperkecil gaya $n$ kali |

### 9.5 Roda Gigi (Gears)
Gears mengubah torsi dan kecepatan putar. Keuntungan mekanisnya ditentukan oleh perbandingan jumlah gigi:
$$ KM = \frac{\text{Jumlah Gigi Output}}{\text{Jumlah Gigi Input}} $$

### 9.6 Sekrup
Sekrup adalah bidang miring yang dililitkan pada sebuah silinder. Keuntungan mekanisnya sangat tinggi:
$$ KM = \frac{2\pi r}{d} $$
- $r$ = Jari-jari putaran (lengan gaya)
- $d$ = Jarak antar ulir (pitch)

> [!WARNING]
> **"Tidak Ada Makan Siang Gratis":**
> Pesawat sederhana memperkecil gaya, tetapi memperbesar jarak tempuh. Total **Usaha** yang dilakukan tetap sama (bahkan lebih besar jika ada gesekan). Ini adalah konsekuensi langsung dari Hukum Kekekalan Energi.

---

## Lihat Juga
- [Dinamika](./03-dinamika.md)
- [Momentum](./05-momentum.md)
- [Latihan Soal Bab 4](./latihan-soal/04.1-usaha-energi-latihan.md)
