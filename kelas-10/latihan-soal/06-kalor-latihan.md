# Latihan Soal: Suhu, Kalor, & Perpindahannya

[< Kembali ke Daftar Latihan](./README.md) | [Materi Terkait](../06-kalor.md)

---

### Soal 1: Pemanasan Es
**Pertanyaan:** Hitunglah kalor yang dbutuhkan untuk mengubah $200 \text{ gram}$ balok es dari yang suhunya $-5^\circ \text{C}$ menjadi air seluruhnya bersuhu $10^\circ \text{C}$.
*(Kalor jenis es = $2.100 \text{ J/kg}^\circ\text{C}$; kalor lebur es = $336.000 \text{ J/kg}$; kalor jenis air = $4.200 \text{ J/kg}^\circ\text{C}$)*.

**Pembahasan:**
$m = 200 \text{ gr} = 0,2 \text{ kg}$.
Proses terbagi menjadi 3 tahap energi:
$Q_1$ (Memanaskan es dari $-5$ ke $0$):
$Q_1 = m \cdot c_{es} \cdot \Delta T = 0,2 \cdot 2100 \cdot (0 - (-5)) = 420 \cdot 5 = 2.100 \text{ J}$.

$Q_2$ (Meleburkan seluruh es di suhu $0$ menjadi air bersuhu $0$):
$Q_2 = m \cdot L_{es} = 0,2 \cdot 336.000 = 67.200 \text{ J}$.

$Q_3$ (Menaikkan suhu air $0$ hingga air $10$):
$Q_3 = m \cdot c_{air} \cdot \Delta T = 0,2 \cdot 4200 \cdot 10 = 8.400 \text{ J}$.

Total $Q = 2.100 + 67.200 + 8.400 = \mathbf{77.700 \text{ Joule}}$.

---

### Soal 2: Asas Black (Campuran Suhu Berbeda)
**Pertanyaan:** Sebanyak $50 \text{ gram}$ air panas bersuhu $90^\circ \text{C}$ dicampurkan dengan $100 \text{ gram}$ air dingin bersuhu $30^\circ \text{C}$ di gelas tahan panas. Jika gelas tidak menyerap kalor, berapa suhu akhir campurannya ($T_{camp}$)?

**Pembahasan:**
Kalor yang dilepas oleh benda panas sama seratus persen dengan kalor yang diterima oleh benda dingin.
$Q_{lepas} = Q_{terima}$
$m_p \cdot c \cdot \Delta T_p = m_d \cdot c \cdot \Delta T_d$
(Karena substansi sama-sama air, maka nilai $c$ bisa dicoret di kedua ruas rumus).
$50 \cdot (90 - T_c) = 100 \cdot (T_c - 30)$
$4.500 - 50 T_c = 100 T_c - 3.000$
$4.500 + 3.000 = 100 T_c + 50 T_c$
$7.500 = 150 T_c$
$T_c = \frac{7500}{150} = \mathbf{50^\circ\text{C}}$

---

### Soal 3: Rambatan Konduksi Kalor
**Pertanyaan:** Ujung batang besi memiliki suhu $100^\circ\text{C}$ sementara ujung sebelahnya berada di balok es $0^\circ\text{C}$. Panjang batang 2 meter dengan luas penampang $5 \text{ cm}^2$. Berapa nilai laju aliran kalornya ($H$ / daya masuk panas)?
*(Konduktivitas termal besi $k = 80 \text{ W/mC}$)*.

**Pembahasan:**
Rumus laju kalor Konduksi ($\frac{Q}{t} = H$):
$H = \frac{k\cdot A \cdot \Delta T}{l}$

Cari nilai standar semua angka (SI):
$l = 2 \text{ m}$
$A = 5 \text{ cm}^2 = 5 \times 10^{-4} \text{ m}^2$
$\Delta T = 100 - 0 = 100^\circ\text{C}$

$H = \frac{80 \times 5 \times 10^{-4} \times 100}{2} = \frac{40.000 \times 10^{-4}}{2} = \frac{4}{2} = \mathbf{2 \text{ J/s (Watt)}}$.
