# Bab 3: Dinamika Partikel (Hukum Newton)

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

Dinamika partikel adalah cabang fisika yang mempelajari hubungan antara gerak benda dan penyebabnya (gaya). Jika Kinematika hanya membahas *bagaimana* benda bergerak, Dinamika membahas *mengapa* benda tersebut bergerak.

---

## 1. Hukum Newton tentang Gerak
Sir Isaac Newton merumuskan tiga hukum dasar yang menjadi fondasi mekanika klasik:

### 1.1 Hukum I Newton (Hukum Kelembaman/Inersia)
"Setiap benda akan tetap diam atau bergerak lurus beraturan jika tidak ada gaya luar yang bekerja padanya."
$$ \Sigma F = 0 $$
- **Inersia:** Kecenderungan benda untuk mempertahankan keadaannya.
- **Contoh:** Tubuh terdorong ke depan saat mobil direm mendadak.

### 1.2 Hukum II Newton (Hukum Percepatan)
"Percepatan sebuah benda berbanding lurus dengan resultan gaya yang bekerja dan berbanding terbalik dengan massanya."
$$ \Sigma F = m \cdot a $$
- Satuan Gaya ($F$): Newton (N) atau kg·m/s².

### 1.3 Hukum III Newton (Aksi-Reaksi)
"Setiap ada gaya aksi, akan selalu ada gaya reaksi yang besarnya sama, arahnya berlawanan, dan bekerja pada dua benda yang berbeda."
$$ F_{\text{aksi}} = -F_{\text{reaksi}} $$
- **Syarat:** Besar sama, arah berlawanan, bekerja pada dua benda berbeda, dan jenis gayanya sama.

---

## 2. Mengenal Jenis-Jenis Gaya

### 2.1 Massa vs Berat (Filosofi Penting)

> [!WARNING]
> **Miskonsepsi Fatal: Massa ≠ Berat**
> - **Massa** ($m$): sifat intrinsik benda, **skalar**, tetap di mana saja (satuan: kg).
> - **Berat** ($w$): gaya tarik gravitasi, **vektor**, berubah sesuai nilai $g$ (satuan: Newton).
> - Di bulan ($g_{bulan} \approx 1,6$ m/s²), massa Anda tetap 60 kg, tapi berat Anda hanya $96$ N (bukan $600$ N seperti di bumi).

### 2.2 Daftar Gaya yang Harus Dikenal

1. **Gaya Berat ($w$):** Gaya tarik bumi terhadap benda. Arahnya selalu **tegak lurus ke bawah** menuju pusat bumi.
   $$ w = m \cdot g $$
2. **Gaya Normal ($N$):** Gaya tekan permukaan terhadap benda. Arahnya selalu **tegak lurus bidang sentuh**.

> [!IMPORTANT]
> **Gaya Normal TIDAK SELALU Sama dengan Berat!**
> - Bidang datar tanpa gaya luar: $N = mg$ ✓
> - Bidang miring sudut $\theta$: $N = mg\cos\theta$
> - Di dalam lift naik ($+a$): $N = m(g+a)$
> - Ditarik ke atas dengan gaya $F$: $N = mg - F\sin\alpha$

3. **Gaya Tegangan Tali ($T$):** Gaya pada tali yang tegang. Arahnya menjauhi benda yang ditinjau.
4. **Gaya Gesek ($f$):** Gaya yang menghambat gerak benda. Arahnya berlawanan dengan arah gerak/kecenderungan gerak.
   - **Gaya Gesek Statis ($f_s$):** Bekerja saat benda diam atau tepat akan bergerak.
   - **Gaya Gesek Kinetis ($f_k$):** Bekerja saat benda sudah bergerak. ($f_k = \mu_k \cdot N$).

> [!TIP]
> **Sifat Adaptif Gaya Gesek Statis:**
> Gaya gesek statis bersifat **menyesuaikan** diri dengan gaya dorong. Jika Anda mendorong meja dengan gaya 5 N dan meja diam, maka $f_s = 5$ N. Jika Anda dorong 10 N dan masih diam, $f_s = 10$ N. Rumus $f_{s,max} = \mu_s \cdot N$ hanya berlaku pada **batas maksimum** (tepat hendak bergerak).

5. **Gaya Pegas / Hukum Hooke ($F_p$):**
   $$ F_p = -k \cdot \Delta x $$
   - $k$ = konstanta pegas (N/m)
   - $\Delta x$ = perubahan panjang pegas dari posisi alami
   - Tanda negatif menunjukkan gaya **pemulih** (berlawanan arah simpangan).

---

## 3. Aplikasi Hukum Newton (Problem Solving)

### 3.1 Benda di Bidang Miring
Balok di bidang miring dengan sudut $\theta$:
- Komponen gaya berat searah bidang: $w \sin \theta = m \cdot g \cdot \sin \theta$
- Komponen gaya berat tegak lurus bidang: $w \cos \theta = m \cdot g \cdot \cos \theta$
- **Gaya Normal:** $N = m \cdot g \cdot \cos \theta$ (jika tidak ada gaya luar lain).

### 3.2 Gaya Tarik pada Sudut Miring (Decomposition)
Jika sebuah benda di bidang datar ditarik dengan gaya $F$ yang membentuk sudut $\alpha$ terhadap horizontal:
- Komponen gaya horizontal (penggerak): $F_x = F \cos \alpha$
- Komponen gaya vertikal (mengurangi $N$): $F_y = F \sin \alpha$
- **Gaya Normal menjadi:** $N = mg - F \sin \alpha$
- Percepatan: $a = \frac{F\cos\alpha - \mu_k(mg - F\sin\alpha)}{m}$

### 3.3 Sistem Katrol (Atwood Machine)
Dua massa $m_1$ dan $m_2$ dihubungkan tali melalui katrol ($m_2 > m_1$):

> [!NOTE]
> **Derivasi Rumus Percepatan Katrol:**
> Terapkan Hukum II Newton pada **masing-masing benda**:
> - Benda 1 (naik): $T - m_1 g = m_1 a$ ... (i)
> - Benda 2 (turun): $m_2 g - T = m_2 a$ ... (ii)
> 
> Jumlahkan kedua persamaan (T saling menghilangkan):
> $m_2 g - m_1 g = (m_1 + m_2) a$
> $$ \mathbf{a = \frac{(m_2 - m_1) \cdot g}{m_1 + m_2}} $$
> 
> Substitusi kembali ke persamaan (i) untuk mendapatkan **Tegangan Tali**:
> $$ \mathbf{T = \frac{2 m_1 m_2 g}{m_1 + m_2}} $$

### 3.4 Benda Bertumpuk (Stacked Blocks)
Dua balok ditumpuk: balok A (atas, massa $m_A$) dan balok B (bawah, massa $m_B$). Gaya $F$ diterapkan pada balok A secara horizontal.
- Gaya gesek statis antar permukaan ($f_{AB}$) adalah **satu-satunya gaya** yang menggerakkan balok B.
- Percepatan sistem: $a = \frac{F}{m_A + m_B}$
- Gaya gesek pada B: $f_{AB} = m_B \cdot a$
- **Syarat agar tidak selip:** $f_{AB} \leq \mu_s \cdot m_A \cdot g$

### 3.5 Gaya pada Lift (Elevator)
- Lift Diam/GLB: $N = w = mg$
- Lift Dipercepat ke Atas ($+a$): $N = m(g + a)$ (Terasa lebih berat)
- Lift Dipercepat ke Bawah ($-a$): $N = m(g - a)$ (Terasa lebih ringan)
- **Lift Jatuh Bebas ($a = g$):** $N = m(g - g) = 0$ (Keadaan *Weightless/Melayang*)

---

## 4. Dinamika Gerak Melingkar
Agar benda dapat bergerak melingkar, harus ada gaya yang mengarah ke pusat lingkaran, disebut **Gaya Sentripetal ($F_s$)**.
$$ F_s = m \cdot a_s = m \cdot \frac{v^2}{R} = m \cdot \omega^2 \cdot R $$

**Kasus Populer:**
- **Tikungan Datar (Kasar):** $v_{\text{max}} = \sqrt{\mu_s \cdot g \cdot R}$
- **Tikungan Miring (Licin):** $\tan \theta = \frac{v^2}{g \cdot R}$

### 4.1 Gerak Melingkar Vertikal (Roller Coaster)
Analisis gaya di dua titik krusial:
- **Titik Terendah:** $T - mg = m\frac{v^2}{R} \implies T = m\left(\frac{v^2}{R} + g\right)$
- **Titik Tertinggi:** $T + mg = m\frac{v^2}{R} \implies T = m\left(\frac{v^2}{R} - g\right)$

**Syarat kecepatan minimum di puncak** agar tali tidak kendur ($T \geq 0$):
$$ v_{min} = \sqrt{g \cdot R} $$

---

## 5. Strategi Penyelesaian Soal (FBD)
1. Gambarkan **Diagram Benda Bebas** (FBD) untuk setiap benda.
2. Tentukan arah sumbu koordinat ($X$ dan $Y$). Biasanya sumbu $X$ searah gerak benda.
3. Uraikan gaya-gaya yang tidak terletak pada sumbu koordinat.
4. Terapkan Hukum II Newton pada masing-masing sumbu:
   - $\Sigma F_x = m \cdot a_x$
   - $\Sigma F_y = m \cdot a_y$

---

*(Untuk pembahasan lebih mendalam dan latihan soal, silakan kunjungi [Halaman Latihan Soal Dinamika](./latihan-soal/README.md))*
