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
- **Contoh-contoh kehidupan nyata:**
  - Tubuh terdorong ke depan saat mobil direm mendadak.
  - Koin di atas kertas tetap diam saat kertas ditarik dengan cepat.
  - Benda di dashboard mobil terlempar ke samping saat belok tajam (benda mempertahankan arah lurus).

### 1.2 Hukum II Newton (Hukum Percepatan)
"Percepatan sebuah benda berbanding lurus dengan resultan gaya yang bekerja dan berbanding terbalik dengan massanya."
$$ \Sigma F = m \cdot a $$
- Satuan Gaya ($F$): Newton (N) atau kg·m/s².

> [!NOTE]
> **Hubungan Hukum I dan II:**
> Hukum I Newton sebenarnya adalah **kasus khusus** dari Hukum II ketika $a = 0$. Jika $a = 0$, maka $\Sigma F = m \cdot 0 = 0$. Inilah mengapa Hukum I menyatakan "$\Sigma F = 0$" untuk benda diam atau GLB. Ketiga hukum Newton bukan tiga hal terpisah — mereka adalah **satu kesatuan logika**.

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
> - **Didorong ke bawah** dengan gaya $F$: $N = mg + F\sin\alpha$

3. **Gaya Tegangan Tali ($T$):** Gaya pada tali yang tegang. Arahnya menjauhi benda yang ditinjau.
4. **Gaya Gesek ($f$):** Gaya yang menghambat gerak benda. Arahnya berlawanan dengan arah gerak/kecenderungan gerak.
   - **Gaya Gesek Statis ($f_s$):** Bekerja saat benda diam atau tepat akan bergerak.
   - **Gaya Gesek Kinetis ($f_k$):** Bekerja saat benda sudah bergerak. ($f_k = \mu_k \cdot N$).

> [!TIP]
> **Sifat Adaptif Gaya Gesek Statis:**
> Gaya gesek statis bersifat **menyesuaikan** diri dengan gaya dorong. Jika Anda mendorong meja dengan gaya 5 N dan meja diam, maka $f_s = 5$ N. Jika Anda dorong 10 N dan masih diam, $f_s = 10$ N. Rumus $f_{s,max} = \mu_s \cdot N$ hanya berlaku pada **batas maksimum** (tepat hendak bergerak).

> [!NOTE]
> **Gaya Gesek Udara & Kecepatan Terminal:**
> Dalam dunia nyata, benda jatuh mengalami hambatan udara ($F_{drag} = -kv$). Saat gaya hambat membesar hingga sama dengan gaya berat ($F_{drag} = w$), resultan gaya pembentuk percepatan menjadi nol ($\Sigma F = 0$). Pada titik ini, benda berhenti mengalami percepatan dan akan terus melaju ke bawah dengan kecepatan maksimal yang konstan (disebut **Kecepatan Terminal**). Inilah alasan penerjun payung bisa mendarat dengan aman.

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

> [!NOTE]
> **Sudut Kritis (Sudut Repos):**
> Merupakan sudut kemiringan ($\theta_c$) di mana benda **tepat akan meluncur** ke bawah. Pada kondisi ini, gaya penggerak sama dengan gaya gesek statis maksimum.
> $mg\sin\theta_c = \mu_s \cdot mg\cos\theta_c \implies \mathbf{\tan\theta_c = \mu_s}$.

### 3.2 Gaya Tarik pada Sudut Miring (Decomposition)
Jika sebuah benda di bidang datar ditarik dengan gaya $F$ yang membentuk sudut $\alpha$ terhadap horizontal:
- Komponen gaya horizontal (penggerak): $F_x = F \cos \alpha$
- Komponen gaya vertikal (mengurangi $N$): $F_y = F \sin \alpha$
- **Gaya Normal menjadi:** $N = mg - F \sin \alpha$
- Percepatan: $a = \frac{F\cos\alpha - \mu_k(mg - F\sin\alpha)}{m}$

### 3.3 Gaya Dorong pada Sudut ke Bawah (Push Force)
Kebalikan dari gaya tarik: jika benda **didorong** dengan sudut $\alpha$ ke bawah:
- Komponen horizontal tetap: $F_x = F \cos \alpha$
- Komponen vertikal kini **menambah** Normal: $N = mg + F \sin \alpha$
- Gesek jadi lebih besar: $f_k = \mu_k \cdot (mg + F\sin\alpha)$

> [!TIP]
> **Menarik vs Mendorong: Mana Lebih Efisien?**
> **Menarik** selalu lebih efisien daripada mendorong pada sudut yang sama, karena menarik mengurangi gaya Normal (dan gesek), sedangkan mendorong menambah gaya Normal (dan gesek).

### 3.4 Sistem Katrol (Atwood Machine)
Dua massa $m_1$ dan $m_2$ dihubungkan tali melalui katrol ($m_2 > m_1$):

> [!WARNING]
> **Asumsi Fisika Kelas 10:**
> 1. Katrol dianggap **licin ideal & tak bermassa** ($m_{katrol} = 0$).
> 2. Akibatnya, tegangan tali di kiri dan kanan katrol dijamin **SAMA** besar ($T_1 = T_2 = T$).
> *(Fakta Logis: Jika katrol memiliki massa, $T_1$ HARUS berbeda dengan $T_2$ untuk bisa memutar katrol yang masif tersebut — materi ini akan dipelajari di Eksplorasi Tingkat Lanjut Kelas 11: Dinamika Rotasi).*

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

### 3.5 Sistem Benda Terhubung Tali (Sistem Kereta & Katrol Meja)
Dua balok atau lebih dihubungkan dengan tali dan ditarik bersamaan bergerbong-gerbong.
- **Percepatan Sistem:** $a = \frac{\Sigma F_{\text{penggerak}} - \Sigma f_k}{m_{\text{total}}}$
- **Tegangan Tali ($T$):** Selalu tinjau benda yang "diseret" oleh tali tersebut. Tali menanggung beban benda di belakangnya.
  > Terapkan Hukum II Newton hanya pada benda di belakang tali: $\Sigma F_{\text{belakang}} = m_{\text{belakang}} \cdot a$.

### 3.6 Percepatan Maksimum Alas (Benda di Bak Truk)
Sebuah balok diletakkan secara bebas di atas bak truk yang melaju dengan percepatan $a$. Agar balok **tidak merosot ke belakang**, gaya gesek statis ($f_s$) antarmuka-lah yang menarik balok ke depan untuk "ikut melaju" bersama truk.
- Syarat balok ikut melaju tanpa selip: $\Sigma F_{\text{balok}} = m_{\text{balok}} \cdot a \implies f_s = m \cdot a$
- Batas percepatan truk maksimum sebelum selip ke belakang: 
  $f_{s,max} = m \cdot a_{max} \implies \mu_s \cdot mg = m \cdot a_{max} \implies \mathbf{a_{max} = \mu_s \cdot g}$

### 3.7 Benda Bertumpuk (Stacked Blocks)
Dua balok ditumpuk: balok A (atas, massa $m_A$) dan balok B (bawah, massa $m_B$). Gaya $F$ diterapkan pada balok A secara horizontal.
- Gaya gesek statis antar permukaan ($f_{AB}$) adalah **satu-satunya gaya** yang menggerakkan balok B.
- Percepatan sistem: $a = \frac{F}{m_A + m_B}$
- Gaya gesek pada B: $f_{AB} = m_B \cdot a$
- **Syarat agar tidak selip:** $f_{AB} \leq \mu_s \cdot m_A \cdot g$

### 3.8 Gaya pada Lift (Elevator)
- Lift Diam/GLB: $N = w = mg$
- Lift Dipercepat ke Atas ($+a$): $N = m(g + a)$ (Terasa lebih berat)
- Lift Dipercepat ke Bawah ($-a$): $N = m(g - a)$ (Terasa lebih ringan)
- **Lift Jatuh Bebas ($a = g$):** $N = m(g - g) = 0$ (Keadaan *Weightless/Melayang/Tanpa Bobot*)

### 3.9 Kesetimbangan Statis (Benda Digantung 2 Tali)
Jika benda bermassa $m$ digantung oleh dua tali yang membentuk sudut $\alpha$ dan $\beta$ terhadap horizontal:
- $\Sigma F_x = 0$: $T_1 \cos \alpha = T_2 \cos \beta$
- $\Sigma F_y = 0$: $T_1 \sin \alpha + T_2 \sin \beta = mg$

---

## 4. Dinamika Gerak Melingkar
Agar benda dapat bergerak melingkar, harus ada gaya yang mengarah ke pusat lingkaran, disebut **Gaya Sentripetal ($F_s$)**.
$$ F_s = m \cdot a_s = m \cdot \frac{v^2}{R} = m \cdot \omega^2 \cdot R $$

> [!WARNING]
> **Gaya Sentripetal BUKAN Gaya Baru!**
> $F_s$ adalah **peran** yang dimainkan oleh gaya yang sudah ada. Jangan pernah menggambar "$F_s$" sebagai gaya tambahan di Diagram Benda Bebas (FBD). Identifikasi gaya aslinya:
> - Pada tali: $F_s$ = Tegangan Tali ($T$).
> - Pada tikungan: $F_s$ = Gaya Gesek ($f_s$) atau komponen Normal ($N\sin\theta$).
> - Pada orbit planet: $F_s$ = Gaya Gravitasi.

> [!NOTE]
> **Gaya Sentrifugal (Klarifikasi):**
> Gaya sentrifugal adalah **gaya semu (fictitious force)** yang hanya muncul di kerangka acuan yang berputar (non-inersial). Dalam kerangka inersial (pengamat diam), gaya ini **tidak ada**. Jadi, dalam analisis soal SMA yang menggunakan kerangka inersial, **jangan gunakan gaya sentrifugal**.

**Kasus Populer:**

**Tikungan Datar (Kasar):**

> [!NOTE]
> **Derivasi:** Gaya gesek statis berperan sebagai $F_s$:
> $f_s = F_s \implies \mu_s \cdot mg = m\frac{v^2}{R}$
> Massa saling menghilangkan:
> $$ v_{max} = \sqrt{\mu_s \cdot g \cdot R} $$

**Tikungan Miring (Licin):**

> [!NOTE]
> **Derivasi:** Komponen Normal menyediakan $F_s$:
> - Vertikal: $N\cos\theta = mg$ ... (i)
> - Horizontal: $N\sin\theta = m\frac{v^2}{R}$ ... (ii)
> Bagi (ii) dengan (i): $\frac{\sin\theta}{\cos\theta} = \frac{v^2}{gR}$
> $$ \tan \theta = \frac{v^2}{g \cdot R} $$

**Ayunan Konis (Bandul Gerak Melingkar Horizontal):**

> [!NOTE]
> **Derivasi:** Secara matematis sangat identik dengan tikungan miring, di mana pembentuk sudut adalah **Tegangan Tali ($T$)** (menggantikan peran gaya Normal).
> - Vertikal: $T\cos\theta = mg$ ... (i)
> - Horizontal: $T\sin\theta = m\frac{v^2}{R}$ ... (ii)
> Jika dibagi (ii) terhadap (i), masa konis memiliki hubungan yang sama dengan tikungan miring:
> $$ \mathbf{\tan \theta = \frac{v^2}{g \cdot R}} $$

### 4.1 Gerak Melingkar Vertikal (Roller Coaster & Jembatan)
Analisis gaya sangat bergantung pada arah kelengkungan dan posisi benda:

**Pada Roller Coaster / Lilitan Tali:**
- **Titik Terendah:** $T - mg = m\frac{v^2}{R} \implies T = m\left(\frac{v^2}{R} + g\right)$
- **Titik Tertinggi:** $T + mg = m\frac{v^2}{R} \implies T = m\left(\frac{v^2}{R} - g\right)$

> [!NOTE]
> **Derivasi Kecepatan Minimum di Puncak:**
> Agar tali / lintasan tidak kendur, syarat batasnya $T \geq 0$. Pada batas kritis ($T = 0$):
> $mg = m\frac{v_{min}^2}{R} \implies \mathbf{v_{min} = \sqrt{g \cdot R}}$

**Gaya Normal Kendaraan pada Jembatan/Lembah:**
- **Puncak Bukit Cembung:** Analog dengan titik tertinggi. Gaya berat mengarah ke pusat. 
  $mg - N = m\frac{v^2}{R}$.
  *(Jika $v$ melebihi $\sqrt{gR}$, maka kecepatan sentripetal yang dibutuhkan terlalu besar, Normal menjadi nol, dan mobil terbang lepas dari jalan).*
- **Dasar Lembah Cekung:** Analog dengan titik terendah. Gaya normal mengarah ke pusat.
  $N - mg = m\frac{v^2}{R}$.

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
