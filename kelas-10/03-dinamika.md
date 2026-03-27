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
Dalam analisis dinamika, kita harus mampu mengidentifikasi gaya-gaya yang bekerja pada benda:

1. **Gaya Berat ($w$):** Gaya tarik bumi terhadap benda. Arahnya selalu **tegak lurus ke bawah** menuju pusat bumi.
   $$ w = m \cdot g $$
2. **Gaya Normal ($N$):** Gaya tekan permukaan terhadap benda. Arahnya selalu **tegak lurus bidang sentuh**.
3. **Gaya Tegangan Tali ($T$):** Gaya pada tali yang tegang. Arahnya menjauhi benda yang ditinjau.
4. **Gaya Gesek ($f$):** Gaya yang menghambat gerak benda. Arahnya berlawanan dengan arah gerak/kecenderungan gerak.
   - **Gaya Gesek Statis ($f_s$):** Bekerja saat benda diam atau tepat akan bergerak. ($f_s = \mu_s \cdot N$).
   - **Gaya Gesek Kinetis ($f_k$):** Bekerja saat benda sudah bergerak. ($f_k = \mu_k \cdot N$).

---

## 3. Aplikasi Hukum Newton (Problem Solving)

### 3.1 Benda di Bidang Miring
Balok di bidang miring dengan sudut $\theta$:
- Komponen gaya berat searah bidang: $w \sin \theta = m \cdot g \cdot \sin \theta$
- Komponen gaya berat tegak lurus bidang: $w \cos \theta = m \cdot g \cdot \cos \theta$
- **Gaya Normal:** $N = m \cdot g \cdot \cos \theta$ (jika tidak ada gaya luar lain).

### 3.2 Sistem Katrol (Atwood Machine)
Dua massa $m_1$ dan $m_2$ dihubungkan tali melalui katrol ($m_2 > m_1$):
- Percepatan sistem ($a$):
  $$ a = \frac{(m_2 - m_1) \cdot g}{m_1 + m_2} $$

### 3.3 Gaya pada Lift (Elevator)
- Lift Diam/GLB: $N = w$
- Lift Dipercepat ke Atas ($+a$): $N = m(g + a)$ (Terasa lebih berat)
- Lift Dipercepat ke Bawah ($-a$): $N = m(g - a)$ (Terasa lebih ringan)

---

## 4. Dinamika Gerak Melingkar
Agar benda dapat bergerak melingkar, harus ada gaya yang mengarah ke pusat lingkaran, disebut **Gaya Sentripetal ($F_s$)**.
$$ F_s = m \cdot a_s = m \cdot \frac{v^2}{R} = m \cdot \omega^2 \cdot R $$

**Kasus Populer:**
- **Tikungan Datar (Kasar):** $v_{\text{max}} = \sqrt{\mu_s \cdot g \cdot R}$
- **Tikungan Miring (Licin):** $\tan \theta = \frac{v^2}{g \cdot R}$

---

## 5. Strategi Penyelesaian Soal (FBD)
1. Gambarkan **Diagram Benda Bebas** (FBD) untuk setiap benda.
2. Tentukan arah sumbu korodinat ($X$ dan $Y$). Biasanya sumbu $X$ searah gerak benda.
3. Uraikan gaya-gaya yang tidak terletak pada sumbu koordinat.
4. Terapkan Hukum II Newton pada masing-masing sumbu:
   - $\Sigma F_x = m \cdot a_x$
   - $\Sigma F_y = m \cdot a_y$

---

*(Untuk pembahasan lebih mendalam dan latihan soal, silakan kunjungi [Halaman Latihan Soal Dinamika](./latihan-soal/README.md))*
