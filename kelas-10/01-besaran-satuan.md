# Besaran, Satuan, dan Pengukuran dalam Fisika

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

Fisika adalah ilmu yang mempelajari gejala alam melalui pengamatan dan pengukuran. Materi ini adalah pintu gerbang untuk memahami bagaimana ilmuwan mendefinisikan, mengukur, dan melaporkan sifat-sifat fisik alam semesta secara akurat.

---

## 1. Besaran dan Satuan: Bahasa Dasar Fisika

Fisika dimulai dengan mendefinisikan apa yang akan diukur. Sifat fisik yang dapat diukur dan dinyatakan dengan angka disebut sebagai **Besaran**. Untuk menyatakan besaran tersebut secara seragam di seluruh dunia, kita membutuhkan **Satuan**.

### 1.1 Besaran Pokok (SI)
Terdapat tujuh besaran dasar yang disepakati secara internasional (Sistem Internasional/SI) sebagai penyusun utama segala besaran lainnya.

| Besaran Pokok | Satuan (SI) | Simbol | Dimensi |
| :--- | :--- | :---: | :---: |
| Panjang | meter | m | [L] |
| Massa | kilogram | kg | [M] |
| Waktu | sekon | s | [T] |
| Suhu | kelvin | K | [θ] |
| Kuat Arus | ampere | A | [I] |
| Intensitas Cahaya | candela | cd | [J] |
| Jumlah Zat | mol | mol | [N] |

### 1.2 Besaran Turunan dan Dimensi
Besaran yang diturunkan dari kombinasi besaran pokok disebut **Besaran Turunan**. **Dimensi** digunakan untuk menggambarkan bagaimana suatu besaran turunan tersusun dari besaran pokok. Analisis dimensi sangat berguna untuk membuktikan kebenaran sebuah persamaan fisika.

Berikut adalah 7 contoh cara menurunkan dimensi dari yang paling sederhana hingga lebih kompleks:

| No | Besaran Turunan | Rumus Dasar | Penurunan Dimensi | Dimensi Akhir |
| :-- | :--- | :--- | :--- | :---: |
| 1 | **Luas** | $p \times l$ | $[L] \times [L]$ | $[L]^2$ |
| 2 | **Volume** | $p \times l \times t$ | $[L] \times [L] \times [L]$ | $[L]^3$ |
| 3 | **Massa Jenis** | $m / V$ | $[M] / [L]^3$ | $[M][L]^{-3}$ |
| 4 | **Kecepatan** | $s / t$ | $[L] / [T]$ | $[L][T]^{-1}$ |
| 5 | **Percepatan** | $v / t$ | $[L][T]^{-1} / [T]$ | $[L][T]^{-2}$ |
| 6 | **Gaya** | $m \times a$ | $[M] \times [L][T]^{-2}$ | $[M][L][T]^{-2}$ |
| 7 | **Usaha** | $F \times s$ | $[M][L][T]^{-2} \times [L]$ | $[M][L]^2[T]^{-2}$ |
### 1.3 Konversi Satuan dan Sistem Awalan
Dalam Fisika, kita sering berhadapan dengan angka yang sangat besar atau sangat kecil. Untuk itu, kita menggunakan **Awalan Satuan** (seperti kilo, centi, mili) dan teknik **Konversi Satuan**.

#### A. Konversi Satuan Panjang dan Massa
Konversi ini menggunakan aturan dasar "Tangga Satuan". Setiap perpindahan satu langkah (anak tangga) akan mengubah nilai sebesar faktor 10.

| Awalan | Simbol | Panjang | Massa | Aturan Main |
| :--- | :---: | :--- | :--- | :--- |
| **kilo** | k | km (kilometer) | kg (kilogram) | ⬇️ **Turun:** Kali 10 |
| **hekto** | h | hm (hektometer) | hg (**ons**) | ⬆️ **Naik:** Bagi 10 |
| **deka** | da | dam (dekameter) | dag (dekagram) | |
| **(Dasar)** | - | **m (meter)** | **g (gram)** | |
| **desi** | d | dm (desimeter) | dg (desigram) | |
| **centi** | c | cm (centimeter) | cg (centigram) | |
| **mili** | m | mm (milimeter) | mg (miligram) | |

#### B. Konversi Satuan Luas ($L^2$) dan Volume ($L^3$)
Konversi satuan berpangkat mengikuti aturan eksponensial. Jika tangga satuan panjang memiliki faktor 10, maka satuan berpangkat memiliki faktor pengali **$10^n$**, di mana **$n$** adalah pangkat dari satuan tersebut.

**Logika Perhitungan:**
$$ \text{Faktor Konversi} = (10^{\text{jumlah tangga}})^n $$

1. **Satuan Luas ($n=2$):**
   Setiap turun satu tangga, nilai dikali $10^2 = \mathbf{100}$. Sebaliknya, setiap naik satu tangga dibagi $100$.
   - **Contoh:** Ubah $5 \text{ m}^2$ menjadi $\text{cm}^2$.
     - Langkah 1: Dari `m` ke `cm` turun **2 tangga**.
     - Langkah 2: Faktor pengali = $(10^2)^2 = 10^4 = 10.000$.
     - Langkah 3: $5 \times 10.000 = \mathbf{50.000 \text{ cm}^2}$.

2. **Satuan Volume ($n=3$):**
   Setiap turun satu tangga, nilai dikali $10^3 = \mathbf{1.000}$. Sebaliknya, setiap naik satu tangga dibagi $1.000$.
   - **Contoh:** Ubah $2.000.000 \text{ mm}^3$ menjadi $\text{dm}^3$.
     - Langkah 1: Dari `mm` ke `dm` naik **2 tangga**.
     - Langkah 2: Faktor pembagi = $(10^2)^3 = 10^6 = 1.000.000$.
     - Langkah 3: $2.000.000 / 1.000.000 = \mathbf{2 \text{ dm}^3}$ atau **2 Liter**.

> [!TIP]
> **Ingat:** $1 \text{ dm}^3 = 1 \text{ liter}$ dan $1 \text{ cm}^3 = 1 \text{ mL} = 1 \text{ cc}$. Hubungan ini sangat sering muncul dalam soal-soal fisika fluida dan kimia.

| Satuan Asal | Satuan Tujuan | Faktor Kali | Contoh Aplikasi |
| :--- | :---: | :---: | :--- |
| **Pangkat 2 (Luas)** | | | |
| $1 \text{ cm}^2$ | $\text{mm}^2$ | $100$ | Luas penampang kabel |
| $1 \text{ m}^2$ | $\text{cm}^2$ | $10.000$ | Luas ubin, meja |
| **Pangkat 3 (Volume)** | | | |
| $1 \text{ cm}^3$ | $\text{mm}^3$ | $1.000$ | Volume tetesan air |
| $1 \text{ m}^3$ | $\text{dm}^3$ (L) | $1.000$ | Volume bak mandi |
| $1 \text{ m}^3$ | $\text{cm}^3$ | $1.000.000$ | Massa jenis air |


#### C. Konversi Satuan Lain (Waktu)
Berbeda dengan sistem desimal di atas, waktu menggunakan sistem berbasis 60 (Seksagesimal):
- $1 \text{ jam} = 60 \text{ menit} = 3.600 \text{ sekon}$
- $1 \text{ hari} = 24 \text{ jam} = 86.400 \text{ sekon}$


---


## 2. Alat Ukur dan Teknik Pengukuran

Mengukur adalah kegiatan membandingkan suatu besaran dengan besaran sejenis yang ditetapkan sebagai satuan. Berikut adalah instrumen pengukuran yang sering digunakan dalam laboratorium Fisika.

### 2.1 Mistar (Ruler)
Alat ukur panjang dengan ketelitian hingga 1 mm atau 0,1 cm.
- **Nilai Skala Terkecil (NST):** 1 mm (0,1 cm)
- **Ketidakpastian ($\Delta x$):** $\frac{1}{2} \times 0,1 \text{ cm} = 0,05 \text{ cm}$

### 2.2 Jangka Sorong (Vernier Caliper)
Digunakan untuk mengukur diameter luar, diameter dalam, dan kedalaman benda dengan tingkat ketelitian hingga **0,1 mm** atau **0,01 cm**.
- **Nilai Skala Terkecil (NST):** 0,1 mm (0,01 cm)
- **Ketidakpastian ($\Delta x$):** $\frac{1}{2} \times 0,01 \text{ cm} = 0,005 \text{ cm}$

<div style="background-color: #f0f0f0; padding: 20px; border-radius: 10px; border: 1px solid #ccc; margin: 20px 0;">
  <div style="position: relative; width: 320px; height: 80px; background: #ddd; border: 2px solid #888; margin: 0 auto; overflow: hidden; border-radius: 5px;">
    <!-- Skala Utama -->
    <div style="position: absolute; width: 100%; height: 40px; border-bottom: 2px solid #444; color: #444; font-size: 12px; font-family: monospace; display: flex; align-items: flex-end; padding-bottom: 2px;">
      <div style="border-left: 1px solid #444; height: 15px; margin-left: 20px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 15px;">1 cm</div>
      <div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 8px;"></div><div style="margin-left: 15px; border-left: 1px solid #444; height: 15px;">2 cm</div>
    </div>
    <!-- Skala Nonius Bergerak -->
    <div style="position: absolute; bottom: 0; width: 120px; height: 40px; background: #ffeb3b; border-top: 2px solid #f9a825; animation: slidingRuler 5s infinite alternate ease-in-out; display: flex; align-items: flex-start;">
      <div style="border-left: 1px solid #f9a825; height: 12px; margin-left: 10px;"></div><div style="margin-left: 9px; border-left: 1px solid #f9a825; height: 6px;"></div><div style="margin-left: 9px; border-left: 1px solid #f9a825; height: 6px;"></div><div style="margin-left: 9px; border-left: 1px solid #f9a825; height: 6px;"></div><div style="margin-left: 9px; border-left: 1px solid #f9a825; height: 6px;"></div><div style="margin-left: 9px; border-left: 1px solid #f9a825; height: 10px;"></div>
    </div>
    <style>
      @keyframes slidingRuler {
        0% { left: 10px; }
        100% { left: 180px; }
      }
    </style>
  </div>
  <p style="text-align: center; font-size: 14px; color: #666; font-style: italic; margin-top: 10px;">Simulasi: Rahang geser jangka sorong bergerak menyesuaikan dimensi benda.</p>
</div>

### 2.3 Mikrometer Sekrup (Micrometer Screw Gauge)
Alat ukur panjang paling presisi dengan ketelitian hingga 0,01 mm. Sangat cocok untuk mengukur ketebalan benda yang sangat tipis (seperti kertas atau kawat).
- **Nilai Skala Terkecil (NST):** 0,01 mm
- **Ketidakpastian ($\Delta x$):** $\frac{1}{2} \times 0,01 \text{ mm} = 0,005 \text{ mm}$

<div style="background-color: #f5f5f5; padding: 25px; border-radius: 12px; border: 1px solid #ddd; margin: 20px 0; display: flex; flex-direction: column; align-items: center;">
  <div style="display: flex; align-items: center; justify-content: center;">
    <!-- Bagian Utama Mikrometer -->
    <div style="width: 140px; height: 60px; background: #9e9e9e; border: 2px solid #616161; border-radius: 5px 0 0 5px; color: white; display: flex; align-items: center; justify-content: center; font-weight: bold; font-family: sans-serif;">SKALA UTAMA</div>
    <!-- Bidal (Thimble) yang berputar -->
    <div style="width: 60px; height: 90px; background: #2196f3; border: 2px solid #0d47a1; border-radius: 5px; color: white; display: flex; flex-direction: column; align-items: center; justify-content: center; animation: rotatingThimble 4s infinite linear; box-shadow: inset 5px 0 15px rgba(0,0,0,0.3);">
      <div style="font-size: 10px; border-bottom: 2px solid rgba(255,255,255,0.5); width: 80%; text-align: right; margin: 4px 0;">25</div>
      <div style="font-size: 10px; border-bottom: 2px solid white; width: 100%; text-align: right; margin: 4px 0;">20</div>
      <div style="font-size: 10px; border-bottom: 2px solid rgba(255,255,255,0.5); width: 80%; text-align: right; margin: 4px 0;">15</div>
    </div>
    <style>
      @keyframes rotatingThimble {
        0% { transform: translateY(0); }
        50% { transform: translateY(-15px); }
        100% { transform: translateY(0); }
      }
    </style>
  </div>
  <p style="font-size: 14px; color: #666; font-style: italic; margin-top: 15px;">Simulasi: Putaran bidal mikrometer untuk menyesuaikan jepitan benda.</p>
</div>

### 2.4 Neraca Ohaus
Alat ukur massa benda di laboratorium dengan ketelitian hingga 0,1 gram. Bekerja dengan cara menggeser beban (anting) pada lengan neraca hingga mencapai kesetimbangan.
- **Nilai Skala Terkecil (NST):** 0,1 g
- **Ketidakpastian ($\Delta x$):** $\frac{1}{2} \times 0,1 \text{ g} = 0,05 \text{ g}$

### 2.5 Termometer (Alat Ukur Suhu)
Suhu adalah derajat panas atau dinginnya suatu benda. Kita mengukurnya dengan termometer. Meskipun kita sering menggunakan Celsius, **Satuan Internasional (SI) untuk suhu adalah Kelvin (K)**.

Berikut adalah 4 skala pengukuran suhu beserta titik beku air (bawah) dan titik didih air (atas) pada tekanan 1 atm:
- **Celsius ($^\circ\text{C}$):** Titik bawah $0^\circ$, titik atas $100^\circ$. (Skala $100$).
- **Reamur ($^\circ\text{R}$):** Titik bawah $0^\circ$, titik atas $80^\circ$. (Skala $80$).
- **Fahrenheit ($^\circ\text{F}$):** Titik bawah $32^\circ$, titik atas $212^\circ$. (Skala $180$).
- **Kelvin ($\text{K}$):** Titik bawah $273$, titik atas $373$. (Skala $100$). 
*(Catatan: Kelvin merupakan skala mutlak sehingga penulisannya tidak menggunakan simbol derajat $\circ$)*.

Dari rentang skalanya ($100 : 80 : 180 : 100$), kita dapat menyederhanakan rasio perbandingan matematika antar termometer menjadi **$5 : 4 : 9 : 5$**.

**Rumus Praktis Konversi Skala Suhu:**
Mengacu pada rasio tersebut, berikut cara konversinya secara cepat:
- **C ke R:** $\text{R} = \frac{4}{5} \times \text{C}$
- **R ke C:** $\text{C} = \frac{5}{4} \times \text{R}$
- **C ke F:** $\text{F} = (\frac{9}{5} \times \text{C}) + 32$
- **F ke C:** $\text{C} = \frac{5}{9} \times (\text{F} - 32)$
- **C ke K:** $\text{K} = \text{C} + 273$

> [!TIP]
> **Logika Menghafal:** Semua konversi berbentuk *($\frac{\text{Rasio Tujuan}}{\text{Rasio Asal}} \times \text{Suhu Asal}$)*. Khusus untuk Fahrenheit, ingat bahwa dia "start" dari angka 32, sehingga harus ada proses penambahan atau pengurangan 32.

---

## 3. Ketidakpastian dalam Pengukuran

Tidak ada pengukuran yang benar-benar sempurna. Selalu ada selisih antara nilai terukur dengan nilai sebenarnya. Hal ini dipelajari dalam **Ketidakpastian Pengukuran**.

### 3.1 Jenis-jenis Kesalahan Pengukuran
Kesalahan (Error) dalam pengukuran menyebabkan hasil ukur menjadi tidak pasti. Ada tiga jenis kesalahan utama:
1. **Kesalahan Umum (Kecerobohan):** Disebabkan oleh keterbatasan pengamat, seperti salah membaca skala atau salah mengatur posisi alat ukur.
2. **Kesalahan Sistematis:** Bersumber dari alat ukurnya itu sendiri.
   - **Kesalahan Kalibrasi:** Nilai skala pada alat ukur tidak tepat sejak diproduksi.
   - **Kesalahan Titik Nol (Zero Error):** Jarum penunjuk tidak berada tepat di angka nol saat sebelum digunakan.
   - **Kesalahan Paralaks:** Sudut pandang mata pengamat tidak tegak lurus dengan jarum/skala ukur, sehingga nilai terbaca meleset.
3. **Kesalahan Acak:** Disebabkan oleh fluktuasi halus yang tidak dapat dihindari, seperti perubahan tegangan listrik mendadak, getaran bumi, atau perubahan suhu ruangan secara tak terduga.

### 3.2 Pengukuran Tunggal
Dilakukan hanya satu kali. Ketidakpastiannya ($\Delta x$) biasanya diambil dari setengah nilai skala terkecil (NST) alat ukur:
$$ \Delta x = \frac{1}{2} \times \text{NST} $$

### 3.3 Pengukuran Berulang
Dilakukan beberapa kali untuk meminimalkan ralat acak. Data hasil pengukuran dilaporkan dalam bentuk rata-rata ($\bar{x}$) dan ketidakpastian ($\Delta x$) yang dihitung menggunakan statistik:

1. **Nilai Rata-rata ($\bar{x}$):**
   $$ \bar{x} = \frac{\sum x_i}{n} = \frac{x_1 + x_2 + \dots + x_n}{n} $$
   *Keterangan: $\sum x_i$ adalah jumlah seluruh data, dan $n$ adalah jumlah pengulangan.*

2. **Ketidakpastian Pengukuran Berulang ($\Delta x$):**
   Menggunakan simpangan baku rata-rata untuk memberikan estimasi ralat:
   $$ \Delta x = \frac{1}{n} \sqrt{\frac{n \sum x_i^2 - (\sum x_i)^2}{n-1}} $$
   *Keterangan:*
   - $n$: Jumlah pengulangan (data).
   - $\sum x_i$: Jumlah seluruh nilai data.
   - $\sum x_i^2$: Jumlah dari setiap kuadrat nilai data.

Hasil akhir dilaporkan sebagai:
$$ x = \bar{x} \pm \Delta x $$
Maka laporan ditulis dalam format: **$(\bar{x} \pm \Delta x) \text{ Satuan}$**.

3. **Ketidakpastian Relatif (KSR):**
   Untuk mengetahui persentase ketelitian alat atau percobaan, digunakan rasio persentase ralat terhadap rata-rata:
   $$ \text{KSR} = \left(\frac{\Delta x}{\bar{x}}\right) \times 100\% $$
   *Aturan Penulisan Angka Penting dari KSR:*
   - Jika KSR sekitar $10\%$, berhak atas **2 Angka Penting**.
   - Jika KSR sekitar $1\%$, berhak atas **3 Angka Penting**.
   - Jika KSR sekitar $0,1\%$, berhak atas **4 Angka Penting**.

---

## 4. Angka Penting dan Notasi Ilmiah

Hasil pengukuran harus ditulis sesuai dengan ketelitian alat ukur melalui aturan **Angka Penting**. Secara umum, angka penting terdiri dari angka pasti dan satu angka terakhir yang ditaksir (angka ragu-ragu).

### 4.1 Aturan Penulisan Angka Penting
1. **Semua angka bukan nol** adalah Angka Penting (AP). (Contoh: 123,4 memiliki 4 AP).
2. **Angka nol di antara angka bukan nol** adalah AP. (Contoh: 2005 memiliki 4 AP).
3. **Angka nol di sebelah kanan angka bukan nol** dalam bilangan desimal adalah AP. (Contoh: 0,500 memiliki 3 AP).
4. **Angka nol di sebelah kiri angka bukan nol** (angka desimal < 1) **bukan** AP. (Contoh: 0,0025 memiliki 2 AP).
5. **Angka nol di sebelah kanan angka tanpa tanda desimal** biasanya bukan AP, kecuali jika diberi tanda khusus (garis bawah). (Contoh: 1200 memiliki 2 AP).

### 4.2 Aturan Operasi Angka Penting
- **Penjumlahan & Pengurangan:** Hasilnya hanya boleh mengandung **satu angka taksiran**. (Aturan praktis: Ikuti jumlah angka di belakang koma yang paling sedikit).
- **Perkalian & Pembagian:** Hasilnya harus mengikuti **jumlah Angka Penting yang paling sedikit** dari komponen yang dioperasikan.
- **Pemangkatan & Pengakaran:** Hasilnya mengikuti jumlah Angka Penting pada angka yang dipangkatkan atau diakarkan.

### 4.3 Notasi Ilmiah
Penulisan angka dalam bentuk $a \times 10^n$ (dengan $1 \le a < 10$) untuk memudahkan penulisan angka sangat besar atau sangat kecil.
- Contoh: $300.000.000 \text{ m/s} \rightarrow 3,0 \times 10^8 \text{ m/s}$ (memiliki 2 AP).

---

## 5. Besaran Skalar dan Vektor

Banyak besaran fisika yang tidak cukup dinyatakan hanya dengan angka dan satuan. Kita membaginya menjadi dua kelompok berdasarkan ada atau tidaknya arah:

### 5.1 Besaran Skalar
Hanya memiliki **nilai (magnitude)** dan satuan saja. Besaran ini tidak dipengaruhi oleh arah gerak atau posisi.
- **Contoh:** Jarak, Kelajuan, Massa, Waktu, Suhu, Energi, Usaha, Daya, Tekanan, Massa Jenis, Potensial Listrik, dan Hambatan Listrik.

### 5.2 Besaran Vektor
Memiliki **nilai (magnitude)** dan **arah**. Arah sangat menentukan hasil akhir dalam operasi matematis (perhitungan) vektor.
- **Contoh:** Perpindahan, Kecepatan, Percepatan, Gaya, Berat, Momentum, Impuls, Medan Listrik, Medan Magnet, Torsi (Momen Gaya), dan Induksi Magnetik.

> **Penting:** Dalam penulisan, simbol besaran vektor biasanya ditebalkan (Contoh: **F**) atau diberi tanda anak panah di atasnya ($\vec{F}$). Secara visual, vektor digambarkan dengan anak panah, di mana panjang panah menyatakan besarnya nilai dan ujung panah menyatakan arahnya.

### 5.3 Operasi Besaran Skalar
Operasi penjumlahan, pengurangan, perkalian, atau pembagian pada besaran skalar dapat dilakukan menggunakan operasi aljabar biasa. Syarat utama untuk menjumlahkan atom mengurangkan besaran skalar adalah **satuannya harus sama**.
- **Contoh:** Massa $3 \text{ kg} + 2 \text{ kg} = 5 \text{ kg}$. (Jika berbeda satuan: $1 \text{ jam} + 30 \text{ menit}$, harus disamakan terlebih dahulu menjadi $90 \text{ menit}$ atau $1,5 \text{ jam}$).

### 5.4 Operasi Besaran Vektor
Berbeda dengan skalar, besaran vektor **tidak bisa** langsung dijumlahkan secara numerik karena terikat oleh arah. Penjumlahan beberapa vektor akan menghasilkan panah baru yang disebut **Resultan ($R$)**.

#### A. Penjumlahan Vektor (Metode Analitis Sudut Apit)
Metode ini digunakan untuk menjumlahkan dua vektor yang pangkalnya bertemu dan membentuk sudut apit lurus $\alpha$. Rumus matematis menghitung kuat resultan ($R$) antara dua vektor ($F_1$ dan $F_2$) adalah menggunakan Rumus Cosinus:
$$ R = \sqrt{F_1^2 + F_2^2 + 2 \cdot F_1 \cdot F_2 \cdot \cos(\alpha)} $$

- _Kondisi khusus:_ 
  - Jika searah ($\alpha = 0^\circ$): $R = F_1 + F_2$ (Maksimum).
  - Jika berlawanan arah ($\alpha = 180^\circ$): $R = |F_1 - F_2|$ (Minimum).
  - Jika tegak lurus ($\alpha = 90^\circ$): $R = \sqrt{F_1^2 + F_2^2}$ (Phytagoras).

#### B. Penguraian Vektor ke Sumbu Koordinat (Metode Komponen XY)
Jika terdapat lebih dari dua vektor menyebar merata, cara penyelesaian paling aman adalah menguraikan setiap kemiringan menjadi komponen horizontal (Sumbu $X$) dan komponen vertikal (Sumbu $Y$) menggunakan prinsip trigonometri sudut $\theta$ (sudut kemiringan terhadap sumbu mendatar).
- **Proyeksi Sumbu X:** $F_x = F \cdot \cos(\theta)$
- **Proyeksi Sumbu Y:** $F_y = F \cdot \sin(\theta)$

Setelah semua gaya dipecah, jumlahkan per masing-masing sumbu ($\sum F_x$ dan $\sum F_y$). Resultan totalnya ditegakkan kembali dengan Phytagoras:
$$ R_{\text{total}} = \sqrt{(\sum F_x)^2 + (\sum F_y)^2} $$

#### C. Perkalian Vektor (Dot Product & Cross Product)
Vektor dapat dikalikan satu sama lain dengan dua metode matematis utama yang memiliki signifikansi fisis berbeda:

1. **Perkalian Titik (Dot Product) $\rightarrow$ Menghasilkan Skalar**
   Digunakan ketika dua vektor dikalikan untuk mendapatkan nilai energi/besaran yang tidak punya arah. (Contoh fisis: Usaha matematis $W = \vec{F} \cdot \vec{s}$).
   $$ \vec{A} \cdot \vec{B} = |\vec{A}| \cdot |\vec{B}| \cdot \cos(\theta) $$
   *(Catatan: Karena berupa skalar, hasilnya cukup berupa nilai numerik tunggal tanpa arah).*

2. **Perkalian Silang (Cross Product) $\rightarrow$ Menghasilkan Vektor Baru**
   Digunakan ketika hasil kali kedua vektor menciptakan efek putaran (torsi) atau gaya pada sumbu ketiga (ruang 3D) yang tegak lurus dari kedua vektor asalnya. (Contoh fisis: Momen Gaya / Torsi $\vec{\tau} = \vec{r} \times \vec{F}$).
   $$ |\vec{A} \times \vec{B}| = |\vec{A}| \cdot |\vec{B}| \cdot \sin(\theta) $$
   *(Catatan: Penentuan arah vektor yang baru ditelusuri menggunakan insting Aturan Tangan Kanan dari $\vec{A}$ menuju $\vec{B}$).*

---

*(Seluruh pembahasan contoh soal dan aplikasi perhitungan vektor di atas telah tersedia di halaman [Latihan Soal Kelas 10](./latihan-soal/README.md))*
