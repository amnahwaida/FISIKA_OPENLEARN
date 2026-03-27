# Kinematika: Analisis Gerak Benda

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

**Kinematika** adalah cabang ilmu Fisika yang mempelajari gerak suatu benda tanpa meninjau penyebab atau gaya yang mendasarinya. Di sini kita fokus pada deskripsi gerak: seberapa jauh, seberapa cepat, dan seberapa lama sebuah benda berpindah.

---

## 1. Konsep Dasar Gerak

Sebelum kita masuk ke jenis-jenis gerak, sangat penting untuk memahami perbedaan antara besaran skalar dan besaran vektor dalam kinematika.

### 1.1 Posisi, Jarak, dan Perpindahan
- **Posisi:** Letak suatu benda pada suatu waktu tertentu terhadap titik acuan.
- **Jarak (Skalar):** Total panjang lintasan yang ditempuh benda. Nilainya selalu positif.
- **Perpindahan (Vektor):** Perubahan posisi benda (selisih posisi akhir dan awal). Disimbolkan sebagai $\Delta \vec{x} = \vec{x}_t - \vec{x}_0$.

### 1.2 Kelajuan dan Kecepatan
- **Kelajuan (Skalar):** Jarak per satuan waktu.
  $$ v = \frac{s}{t} $$
- **Kecepatan (Vektor):** Perpindahan per satuan waktu.
  $$ \vec{v} = \frac{\Delta \vec{x}}{\Delta t} = \frac{\vec{x}_t - \vec{x}_0}{t_t - t_0} $$

> [!TIP]
> **Kecepatan Rata-rata Lintasan Bertahap:**
> Jika benda menempuh paruh jarak pertama dengan $v_1$ dan paruh jarak kedua dengan $v_2$, kecepatan rata-ratanya adalah **rata-rata harmonik**:
> $$ v_{avg} = \frac{2 \cdot v_1 \cdot v_2}{v_1 + v_2} $$

**Kecepatan Relatif 2 Dimensi (Kasus Vektor):**
Jika sebuah benda (misal perahu) bergerak dengan kecepatan $\vec{v}_p$ di atas medium (misal sungai) yang juga bergerak dengan kecepatan $\vec{v}_s$, maka kecepatan total perahu terhadap pengamat diam di pinggir adalah:
$$ \vec{v}_{\text{total}} = \vec{v}_p + \vec{v}_s $$
Jika perahu menyeberang tegak lurus arus, besar kecepatan resultannya adalah:
$$ v_{\text{res}} = \sqrt{v_p^2 + v_s^2} $$

### 1.3 Percepatan (Acceleration)
Perubahan kecepatan tiap satuan waktu. Percepatan bernilai positif ($+$) berarti benda dipercepat, sedangkan negatif ($-$) berarti benda diperlambat.
$$ a = \frac{\Delta v}{\Delta t} = \frac{v_t - v_0}{t} $$

### 1.4 Kinematika dengan Analisis Vektor (Kalkulus Dasar)
Pada tingkat lanjut, besaran kinematika didefinisikan menggunakan operasi turunan (derivatif):
- **Kecepatan Sesaat ($v$):** Turunan pertama fungsi posisi ($r$) terhadap waktu.
  $$ v(t) = \frac{dr}{dt} $$
- **Percepatan Sesaat ($a$):** Turunan pertama fungsi kecepatan ($v$) terhadap waktu.
  $$ a(t) = \frac{dv}{dt} $$
*(Contoh: Jika $r(t) = 2t^3$, maka $v(t) = 6t^2$ dan $a(t) = 12t$).*

---

## 2. Gerak Lurus Beraturan (GLB)

GLB adalah gerak benda pada lintasan lurus dengan **kecepatan konstan ($v$ tetap)**. Artinya, percepatannya adalah nol ($a = 0$).

- **Ciri Utama:** Dalam selang waktu yang sama, benda menempuh jarak yang sama.
- **Rumus:**
  $$ s = v \cdot t $$
- **Grafik GLB:**
  - Grafik $s-t$ (Jarak-Waktu) berupa garis lurus miring ke atas (linear).
  - Grafik $v-t$ (Kecepatan-Waktu) berupa garis lurus mendatar (horizontal).

### 2.1 Logika Gerak Menyusul
Kasus di mana benda B mengejar benda A yang berada di depannya. Syarat benda B menyusul benda A adalah **Posisi Akhir Sama ($x_A = x_B$)** pada waktu yang sama ($t$).

- **Jika Keduanya GLB:**
  $$ x_{0A} + v_A \cdot t = x_{0B} + v_B \cdot t $$
- **Jika Salah Satu atau Keduanya GLBB:**
  Gunakan persamaan posisi GLBB ($s = v_0 t + \frac{1}{2}at^2$) dan selesaikan persamaan kuadrat untuk mencari $t$.

---

## 3. Gerak Lurus Berubah Beraturan (GLBB)

GLBB adalah gerak benda pada lintasan lurus dengan **percepatan konstan ($a$ tetap)**. Artinya, kecepatannya berubah secara teratur.

- **Rumus Utama GLBB:**
  1. $v_t = v_0 + a \cdot t$ (Mencari kecepatan akhir)
  2. $s = v_0 \cdot t + \frac{1}{2} a \cdot t^2$ (Mencari perpindahan)
  3. $v_t^2 = v_0^2 + 2 \cdot a \cdot s$ (Mencari hubungan kecepatan dan jarak tanpa waktu)

- **Grafik GLBB:**
  - Grafik $a-t$ (Percepatan-Waktu) berupa garis lurus mendatar (asumsikan $a \neq 0$).
  - Grafik $v-t$ (Kecepatan-Waktu) berupa garis lurus miring ($a > 0$ miring ke atas, $a < 0$ miring ke bawah).
  - Grafik $s-t$ (Jarak-Waktu) berupa lintasan melengkung (parabola).

> [!IMPORTANT]
> **Metode Luas Area:** Jarak tempuh benda dapat dihitung dengan mencari **Luas di bawah kurva** pada grafik kecepatan terhadap waktu ($v-t$).

---

## 4. Gerak Vertikal (Gerak Satu Dimensi dengan Gravitasi)

Gerak vertikal adalah aplikasi nyata GLBB di mana percepatan yang dialami benda adalah percepatan gravitasi bumi ($g \approx 9,8 \text{ m/s}^2$ atau sering dibulatkan menjadi $10 \text{ m/s}^2$).

### 4.1 Gerak Jatuh Bebas (GJB)
Benda dijatuhkan tanpa kecepatan awal ($v_0 = 0$).
- $v_t = g \cdot t$
- $h = \frac{1}{2} \cdot g \cdot t^2$
- $v_t = \sqrt{2 \cdot g \cdot h}$

### 4.2 Gerak Vertikal ke Atas (GVA)
Benda dilempar ke atas dengan $v_0$ tertentu. Benda akan melambat karena gravitasi bersifat menghambat ($-g$).
- **Di titik tertinggi:** Kecepatan sesaat benda adalah nol ($v_t = 0$).
- $h_{\text{max}} = \frac{v_0^2}{2g}$
- $t_{\text{naik}} = \frac{v_0}{g}$

### 4.3 Gerak Vertikal ke Bawah (GVB)
Benda dilempar ke bawah dengan kecepatan awal ($v_0 \neq 0$). Gunakan rumus GLBB dengan mengganti $a = +g$.

### 4.4 Pertemuan Dua Benda di Udara
Jika benda A dilempar ke atas dari tanah dan benda B dijatuhkan dari ketinggian $H$ di atasnya, mereka akan bertemu jika:
$$ y_A + y_B = H $$
(dengan $y_A$ adalah posisi bola A dan $y_B$ adalah jarak jatuh bola B).

---

## 5. Gerak Parabola (Projectile Motion)

Gerak parabola adalah perpaduan dua gerak pada dua sumbu koordinat yang saling tegak lurus:
1. **Sumbu X (Horizontal):** Bergerak secara **GLB** (kecepatan tetap $v_x = v_0 \cos \alpha$).
2. **Sumbu Y (Vertikal):** Bergerak secara **GLBB** (dipengaruhi gravitasi $v_y = v_0 \sin \alpha - gt$).

- **Kecepatan Awal di Sumbu X:** $v_{0x} = v_0 \cos \alpha$
- **Kecepatan Awal di Sumbu Y:** $v_{0y} = v_0 \sin \alpha$
- **Tinggi Maksimum ($h_{\text{max}}$):**
  $$ h_{\text{max}} = \frac{v_0^2 \sin^2 \alpha}{2g} $$
- **Jarak Terjauh ($x_{\text{max}}$):**
  $$ x_{\text{max}} = \frac{v_0^2 \sin 2\alpha}{g} $$

**Persamaan Posisi Setiap Saat ($t$):**
Koordinat peluru pada sembarang waktu $t$ selama di udara:
- **Posisi Mendatar ($x$):** $x(t) = v_0 \cos \alpha \cdot t$
- **Posisi Vertikal ($y$):** $y(t) = v_0 \sin \alpha \cdot t - \frac{1}{2}gt^2$

$$ v_t = \sqrt{v_x^2 + v_{ty}^2} \quad \text{di mana } v_{ty} = v_0 \sin \alpha - gt $$

**Vektor Kecepatan dalam Notasi $\hat{i}, \hat{j}$:**
$$ \vec{v}(t) = (v_0 \cos \alpha) \hat{i} + (v_0 \sin \alpha - gt) \hat{j} $$

**Analisis Sudut Elevasi Maksimum:**
Jangkauan terjauh ($x_{\text{max}}$) akan dicapai jika $\sin 2\alpha$ bernilai maksimum (yaitu 1). Hal ini terjadi saat $2\alpha = 90^\circ$, atau **$\alpha = 45^\circ$**.

**Persamaan Lintasan ($y$ sebagai fungsi $x$):**
Jika kita mengeliminasi variabel waktu ($t$), kita mendapatkan persamaan parabola murni:
$$ y = x \tan \alpha - \frac{gx^2}{2v_0^2 \cos^2 \alpha} $$

**Penembakan dari Ketinggian ($H$):**
Jika benda ditembakkan dari puncak gedung setinggi $H$, maka posisi vertikalnya terhadap tanah adalah:
$$ y(t) = H + v_0 \sin \alpha \cdot t - \frac{1}{2}gt^2 $$
*(Benda mencapai tanah saat $y = 0$).*

**Sifat Sudut Komplementer:**
Jangkauan mendatar ($x_{\text{max}}$) akan bernilai sama untuk dua sudut elevasi $\theta_1$ dan $\theta_2$ yang berjumlah $90^\circ$ (misal $30^\circ$ dan $60^\circ$).

---

## 6. Gerak Melingkar Beraturan (GMB)

GMB adalah gerak benda dalam lintasan lingkaran dengan laju tetap, namun arah kecepatannya selalu berubah (kecepatan linearnya tidak konstan).

### 6.1 Besaran-Besaran GMB
- **Frekuensi ($f$):** Jumlah putaran tiap detik. ($f = n / t$, satuan Hertz).
- **Periode ($T$):** Waktu untuk satu kali putaran penuh. ($T = t / n$, satuan sekon). ($T = 1/f$).
- **Kecepatan Sudut ($\omega$):** Sudut yang ditempuh per satuan waktu.
  $$ \omega = 2\pi f = \frac{2\pi}{T} \text{ (rad/s)} $$
- **Kecepatan Linear ($v$):** Laju pada pinggir lingkaran.
  $$ v = \omega \cdot R $$

### 6.2 Percepatan Sentripetal ($a_s$)
Meskipun lajunya tetap, ada percepatan yang arahnya selalu menuju pusat lingkaran untuk membelokkan arah benda.
$$ a_s = \frac{v^2}{R} = \omega^2 \cdot R $$

### 6.3 Hubungan Roda-Roda
1. **Dua Roda Seporos (Satu As):**
   Arah putar sama dan **Kecepatan Sudut sama ($\omega_A = \omega_B$)**.
2. **Dua Roda Bersinggungan / Dihubungkan Sabuk:**
   Arah putar bisa sama (sabuk lurus) atau beda (bersinggungan), namun **Kecepatan Linear sama ($v_A = v_B$)**.

### 6.4 Gerak Melingkar Berubah Beraturan (GMBB)
GMBB adalah gerak melingkar dengan **Percepatan Sudut ($\alpha$)** konstan.
- **Kecepatan Sudut Akhir:** $\omega_t = \omega_0 + \alpha \cdot t$
- **Posisi Sudut (Sudut Tempuh):** $\theta = \omega_0 \cdot t + \frac{1}{2} \alpha \cdot t^2$
- **Percepatan Tangensial ($a_t$):** Percepatan yang sejajar lintasan (mengubah laju linear).
  $$ a_t = \alpha \cdot R $$

### 6.5 Percepatan Total ($a_{\text{tot}}$)
Pada GMBB, benda memiliki dua percepatan yang saling tegak lurus ($a_s$ dan $a_t$):
$$ a_{\text{tot}} = \sqrt{a_s^2 + a_t^2} $$

---

*(Untuk pembahasan lebih mendalam dan latihan soal, silakan kunjungi [Halaman Latihan Soal Kinematika](./latihan-soal/README.md))*
