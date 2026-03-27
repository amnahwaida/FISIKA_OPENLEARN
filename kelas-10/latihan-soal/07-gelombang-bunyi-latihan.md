# Latihan Soal: Gelombang, Bunyi, Efek Doppler

[< Kembali ke Daftar Latihan](./README.md) | [Materi Terkait](../07-gelombang-bunyi.md)

---

### Soal 1: Rumus Gelombang Dasar
**Pertanyaan:** Sebuh tali diayun membentuk 5 buah bukit dan 5 buah lembah gelombang dalam waktu 2 sekon. Jarak membentang dari pangkal ujung per satu gelombang penuh adalah $40 \text{ cm}$. Berapa frekuensi dan kecepatan rambat gelombangnya?

**Pembahasan:**
- 5 bukit dan 5 lembah = 5 gelombang penuh ($n=5$).
Frekuensi $f = \frac{n}{t} = \frac{5}{2} = \mathbf{2,5 \text{ Hz}}$.
- Panjang 1 buah gelombang ($\lambda$) sudah diketahui ada di jarak $40 \text{ cm} = 0,4 \text{ meter}$.
Kecepatan $v = \lambda \cdot f = 0,4 \times 2,5 = \mathbf{1 \text{ m/s}}$.

---

### Soal 2: Taraf Intensitas Bunyi
**Pertanyaan:** Satu mesin jahit yang menyala memiliki taraf intensitas bunyi sebesar $50 \text{ dB}$. JIka dalam sebuah penjahitan raksasa dinyalakan 100 buah mesin secara serempak/bersamaan. Berapakah nilai Taraf Intensitas totalnya?

**Pembahasan:**
$TI_1 = 50 \text{ dB}$. 
Jumlah sumber bunyi $n = 100$.
$$ TI_{total} = TI_1 + 10 \cdot \log(n) $$
$$ TI_{total} = 50 + 10 \cdot \log(100) $$
$$ TI_{total} = 50 + 10(2) $$
$$ TI_{total} = 50 + 20 = \mathbf{70 \text{ dB}} $$

---

### Soal 3: Efek Doppler
**Pertanyaan:** Kereta api A bergerak dengan kelajuan $72 \text{ km/jam}$ mendekati pengamat. Saat sirine/klakson kereta itu mendengking dengan frekuensi $680 \text{ Hz}$, pengamat sedang ikut berlari kencang mendekati kereta tersebut sejauh $18 \text{ km/jam}$. Hitung frekuensi bunyi detak yang didengar sang pengamat itu bila kecepatan cepat rambat bunyi di udara $v=340 \text{ m/s}$!

**Pembahasan:**
Pertama ubah menjadi Standar Internasional (SI) dulu, lalu pasang rumusnya dengan teliti plus (+) maupun minus (-) pengamat (Pendengar) / Sumber:
- Kec. Sumber: $v_s = 72 \text{ km/jam} = 20 \text{ m/s}$. (Sumber Mendekat ke pendengar -> penyebut **Negatif**)
- Kec. Pendengar: $v_p = 18 \text{ km/jam} = 5 \text{ m/s}$. (Pendengar Mendekat ke sumber -> pembilang **Positif**)
- Kec. Rambat: $v = 340 \text{ m/s}$.
- F. Sumber: $f_s = 680 \text{ Hz}$.

$$ f_p = f_s \cdot \left(\frac{v \pm v_p}{v \pm v_s}\right) $$
$$ f_p = 680 \cdot \left(\frac{340 + 5}{340 - 20}\right) $$
$$ f_p = 680 \cdot \left(\frac{345}{320}\right) $$
$$ f_p = 2,125 \cdot 345 = \mathbf{733,125 \text{ Hz}} $$
Maka nada klakson terdengar jadi lebih kencang / melengking (frekuensinya meninggi)!
