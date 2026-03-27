# Latihan Soal: Besaran, Satuan, Dimensi & Vektor

[< Kembali ke Daftar Latihan](./README.md) | [Materi Terkait](../01-besaran-satuan.md)

---

> *Catatan: Seluruh soal di bawah ini telah disesuaikan dan dipastikan **sangat relevan** dengan silabus Bab 1 (Besaran pokok, turunan, konversi satuan, dimensi, alat ukur/angka penting, dan vektor dasar). Ilustrasi murni menggunakan formatting elemen CSS struktural dan Animasi.*

### Soal 1: Analisis Dimensi Energi Kinetik
**Pertanyaan:** Energi kinetik dirumuskan $EK = \frac{1}{2} m v^2$, di mana $m$ adalah massa dan $v$ adalah kecepatan. Tentukan rumus dimensi dari energi kinetik!

**Pembahasan:**
- Massa ($m$) dimensinya = $[M]$
- Kecepatan ($v$) dimensinya = $[L][T]^{-1}$

Oleh karena $v$ dikuadratkan: $([L][T]^{-1})^2 = [L]^2[T]^{-2}$

Maka dimensi EK = $[M] \times [L]^2[T]^{-2} =$ **$[M][L]^2[T]^{-2}$**

---

### Soal 2: Konversi Satuan
**Pertanyaan:** Kecepatan lari seekor cheetah tercatat sebesar $108 \text{ km/jam}$. Jika dikonversi ke satuan Internasional (SI), berapakah kecepatan cheetah tersebut?

**Pembahasan:**
Satuan SI kecepatan adalah m/s.
$108 \text{ km} = 108.000 \text{ m}$
$1 \text{ jam} = 3.600 \text{ s}$

Kecepatan = $\frac{108.000 \text{ m}}{3.600 \text{ s}}$ = **$30 \text{ m/s}$**

---

### Soal 3: Membaca Alat Ukur (Jangka Sorong)
**Pertanyaan:** Dalam sebuah eksperimen, skala jangka sorong menunjukkan posisi sebagai berikut:
- Angka Nol (0) pada rahang geser (skala nonius) berada persis di antara garis $2,4 \text{ cm}$ dan $2,5 \text{ cm}$ pada Skala Utama.
- Garis ke-6 pada skala nonius terlihat menyambung berhimpitan membentuk satu garis lurus dengan garis di Skala Utama atasnya.
Berapakah nilai bacaan objek tersebut? *(Ketelitian alat $0,01 \text{ cm}$)*.

**Pembahasan:**
<div style="background-color: #f8f9fa; border-left: 5px solid #ffc107; padding: 12px; margin: 10px 0; font-family: monospace; font-size: 15px; color: #333;">
  <span style="color: #6c757d;">[Skala Utama]</span> &nbsp;&nbsp;&nbsp; -> Terbaca <strong>2,4 cm</strong> (Garis terakhir sebelum 0 rahang geser)<br/>
  <span style="color: #6c757d;">[Skala Nonius]</span> &nbsp;&nbsp; -> Garis ke-6 &times; 0,01 cm = <strong>0,06 cm</strong><br/>
  <hr style="border: 0; border-top: 1px dashed #ccc; margin: 8px 0;" />
  <span style="color: #28a745;">[Hasil Ukur]</span> &nbsp;&nbsp;&nbsp;&nbsp; -> 2,4 + 0,06 = <strong style="font-size: 18px;">2,46 cm</strong>
</div>

---

### Soal 4: Aturan Angka Penting (Perkalian)
**Pertanyaan:** Sebuah pelat logam diukur panjangnya $12,5 \text{ cm}$ dan lebarnya $3,04 \text{ cm}$. Hitunglah luar pelat logam tersebut mengikuti kaidah **Aturan Angka Penting**!

**Pembahasan:**
<div style="display: flex; flex-direction: column; gap: 8px; background-color: #f1f8ff; padding: 15px; border-radius: 6px; border: 1px solid #c8e1ff;">
  <div style="display: flex; justify-content: space-between;">
    <strong>P = 12,5 cm</strong>
    <em style="color: #0366d6;">(Terdapat 3 Angka Penting)</em>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <strong>L = 3,04 cm</strong>
    <em style="color: #0366d6;">(Terdapat 3 Angka Penting)</em>
  </div>
  <div style="border-top: 2px solid #0366d6; margin-top: 5px; padding-top: 8px; display: flex; justify-content: space-between;">
    <span>Luas = 12,5 &times; 3,04 = <strong>38,000 cm&sup2;</strong></span>
    <em style="color: #d73a49; font-weight: bold;">(Hasil akhir wajib 3 Angka Penting)</em>
  </div>
</div>
Sesuai aturan: hasil kali matematis angka penting **hanya boleh** memiliki jumlah digit sama dengan jumlah angka penting *paling sedikit* dari komponen pengalinya (keduanya punya 3 digit angka penting). 
Jadi, angka `38,000` harus dibulatkan menjadi 3 digit berharga, yaitu: **$38,0 \text{ cm}^2$**.

---

### Soal 5: Penulisan Notasi Ilmiah
**Pertanyaan:** Massa planet Saturnus diperkirakan sebesar $568.300.000.000.000.000.000.000.000 \text{ kg}$. Tuliskan massa tersebut dalam bentuk baku / Notasi Ilmiah!

**Pembahasan:**
Bentuk baku notasi ilmiah adalah $a \times 10^n$, di mana besaran real (a) dibatasi pada parameter $1 \le a < 10$.
<div style="background-color: #212529; color: #f8f9fa; text-align: center; padding: 15px; border-radius: 8px; font-family: monospace; font-size: 18px; letter-spacing: 2px; margin: 15px 0;">
  <span style="color: #ffc107;">5,683</span> &times; 10<sup style="color: #17a2b8;">26</sup> kg
</div>
Kita harus meletakkan koma setelah angka 5 agar nilainya masuk *range* satuan (5,683). Lalu dari koma tersebut, hitung jumlah pergeseran nol ke kanan sampai ujung. Total terdapat 26 loncatan tempat puluhan. Maka orde pangkat eksponensialnya adalah **26**.

---

### Soal 6: Resultan Vektor Metode Jajaran Genjang
**Pertanyaan:** Dua buah perahu motor menarik sebuah tongkang secara bersamaan dari satu posisi ikatan tambang. Perahu A menarik dengan gaya $4.000 \text{ N}$ ke satu sisi, dan perahu B menarik $3.000 \text{ N}$ ke sisi lain. Tali penarik kedua perahu membentuk sudut pelebaran sebesar $60^\circ$ di tengah laut. Hitung resultan tarikannya! *(Gunakan $\cos 60^\circ = 0.5$)*.

**Pembahasan:**
Kapanpun terdapat **dua vektor berpangkal pada satu titik yang sama dan mengapit sudut**, langsung gunakan Aturan Cosinus.

$$
\begin{aligned}
R &= \sqrt{F_A^2 + F_B^2 + 2F_A F_B \cos\theta} \\
R &= \sqrt{(4000)^2 + (3000)^2 + 2(4000)(3000)(0.5)} \\
R &= \sqrt{16.000.000 + 9.000.000 + 12.000.000} \\
R &= \sqrt{37.000.000} \approx 6.082 \text{ N}
\end{aligned}
$$

Maka dari itu resultannya adalah **$6.082 \text{ N}$**.

---

### Soal 7: Pemecahan / Penguraian Komponen Vektor
**Pertanyaan:** Sebuah roket meluncur dengan kecepatan miring sebesar $v = 100 \text{ m/s}$ pada arah elevasi $\theta = 30^\circ$ terhadap aspal mendatar. Berapakah nilai kecepatan roket jika dipecah khusus untuk gaya angkat membelah ke atas saja (Sumbu Vertikal/Y)? *(Diketahui $\sin(30^\circ)=0,5$ dan $\cos(30^\circ)=0,866$)*.

**Pembahasan:**
<div style="padding: 10px 15px; border-left: 4px solid #17a2b8; background-color: #e9ecef; margin-bottom: 10px;">
  <strong>Sumbu Horizontal (X) dihitung pakai <span style="color:#d73a49">Cosinus</span></strong><br>
  <strong>Sumbu Vertikal (Y) dihitung pakai <span style="color:#28a745">Sinus</span></strong>
</div>
Karena yang ditanyakan adalah kecepatan ke atas (Komponen Sumbu Y) yang posisinya persis sejajar dengan sisi *"di depan"* sudut elevasi:

$$
\begin{aligned}
v_y &= v \cdot \sin(\theta) \\
v_y &= 100 \cdot \sin(30^\circ) \\
v_y &= 100 \cdot 0,5 = 50 \text{ m/s}
\end{aligned}
$$

Sehingga kecepatan pada sumbu vertikalnya adalah **$50 \text{ m/s}$**.

---

### Soal 8: Membaca Alat Ukur (Mikrometer Sekrup)
**Pertanyaan:** Seorang siswa mengukur ketebalan koin menggunakan mikrometer sekrup. Pada selongsong Skala Utama terlihat garis `4,5 mm` terbuka. Pada rahang putar (skala nonius), angka yang lurus searah dengan sumbu sentral utama adalah angka `12`. Berapakah ketebalan riil koin tersebut? *(Ketelitian = $0,01 \text{ mm}$)*.

**Pembahasan:**
<div style="background-color: #fdfdfe; border-left: 5px solid #28a745; padding: 12px; margin: 10px 0; font-family: monospace; font-size: 15px; color: #333; box-shadow: 2px 2px 5px rgba(0,0,0,0.05);">
  <span style="color: #6c757d;">[Skala Utama]</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -> <strong>4,50 mm</strong><br/>
  <span style="color: #6c757d;">[Skala Putar Nonius]</span> -> 12 &times; 0,01 mm = <strong>0,12 mm</strong><br/>
  <hr style="border: 0; border-top: 1px dashed #ccc; margin: 8px 0;" />
  <span style="color: #d73a49;">[Tebal Total]</span> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -> 4,50 + 0,12 = <strong style="font-size: 18px;">4,62 mm</strong>
</div>

---

### Soal 9: Aturan Angka Penting (Penjumlahan)
**Pertanyaan:** Tiga buah batu logam presisi massanya $12,4 \text{ kg}$, $3,25 \text{ kg}$, dan $0,051 \text{ kg}$. Ketiganya dimasukkan ke dalam wadah. Menurut format resmi **aturan angka penting**, berapakah massa total ketiga batu tersebut?

**Pembahasan:**
<div style="display: flex; flex-direction: column; gap: 5px; background-color: #fff3cd; padding: 15px; border-radius: 6px; border: 1px solid #ffeeba;">
  <div style="display: flex; justify-content: space-between;"><strong>12,4 </strong> <em style="color: #856404;">(1 angka desimal) -> Paling tidak akurat</em></div>
  <div style="display: flex; justify-content: space-between;"><strong> 3,25</strong> <em style="color: #856404;">(2 angka desimal)</em></div>
  <div style="display: flex; justify-content: space-between; border-bottom: 2px solid #856404; padding-bottom: 5px; margin-bottom: 5px;"><strong> 0,051 +</strong> <em style="color: #856404;">(3 angka desimal)</em></div>
  <div style="display: flex; justify-content: space-between;">Jumlah = <strong>15,701 kg</strong><span></span></div>
  <div style="margin-top: 8px; color: #dc3545; font-weight: bold; font-family: monospace; font-size: 16px; background: #fff; padding: 5px; text-align: center; border-radius: 4px;">=> Dibulatkan menjadi: 15,7 kg</div>
</div>
Untuk operasi **penjumlahan** dan **pengurangan**, hasilnya harus dibulatkan sebanyak bilangan yang *paling sedikit* angka desimalnya (dalam hal ini `12,4`). Maka `15,701` wajib dipotong/dibulatkan matematis sehingga tersisa satu desimal saja menjadi **$15,7 \text{ kg}$**.

---

### Soal 10: Membuktikan Kebenaran Rumus (Analisis Dimensi)
**Pertanyaan:** Dalam kinematika, terdapat rumus untuk mencari jarak: $v_t^2 = v_0^2 + 2as$. Buktikan secara murni menggunakan analisis dimensi bahwa susunan ruas rumus komplit ini bernilai konsisten / valid secara fisika!

**Pembahasan:**
<div style="background-color: #fafbfc; border-radius: 8px; border: 1px solid #e1e4e8; padding: 15px; margin: 10px 0;">
  <strong style="color: #0366d6;">Ruas Kiri ($v_t^2$):</strong><br>
  (Kecepatan)$^2$ = $([L][T]^{-1})^2$ = <strong>$[L]^2[T]^{-2}$</strong>
  <div style="margin: 10px 0; border-top: 1px solid #e1e4e8;"></div>
  <strong style="color: #0366d6;">Ruas Kanan ($v_0^2 + 2as$):</strong><br>
  - $v_0^2$ (kecepatan awal kuadrat) = pastilah <strong>$[L]^2[T]^{-2}$</strong><br>
  - $2as$: Angka $"2"$ tidak punya dimensi. Percepatan $a = [L][T]^{-2}$. Jarak $s = [L]$.<br>
  - Maka dimensi $2as$ = $[L][T]^{-2} \times [L]$ = <strong>$[L]^2[T]^{-2}$</strong>
</div>
Kesimpulan: Karena nilai dimensi semua sukunya absolut sama $\left( [L]^2[T]^{-2} \right)$, maka  rumusnya bernilai **Valid**.

---

### Soal 11: Resultan Sistem Vektor Komplit (Sumbu Silang)
**Pertanyaan:** Tiga buah gaya bekerja ditarik serentak pada titik berat suatu benda sentral. 
- $F_1 = 10 \text{ N}$ horisontal X positif (Kanan).
- $F_2 = 10 \text{ N}$ vertikal Y positif (Atas).
- $F_3 = 5 \text{ N}$ horisontal X negatif (Kiri).
Tentukan nilai akhir dari gabungan besar Resultan sistem tersebut!

**Pembahasan:**
<div style="background-color: #fdfdfe; border-left: 4px solid #6f42c1; padding: 10px 15px; margin-bottom: 12px; box-shadow: 0 2px 4px rgba(0,0,0,0.02);">
  <strong style="color: #6f42c1;">Sumbu X (Mendatar):</strong><br>
  $\Sigma F_x = F_1 (\text{kanan}) - F_3 (\text{kiri}) = 10 - 5$ = <strong>$5 \text{ N ke Kanan}$</strong><br><br>
  <strong style="color: #6f42c1;">Sumbu Y (Vertikal):</strong><br>
  $\Sigma F_y = F_2 (\text{atas})$ = <strong>$10 \text{ N ke Atas}$</strong>
</div>

Gunakan Pythagoras:

$$
\begin{aligned}
R &= \sqrt{(\Sigma F_x)^2 + (\Sigma F_y)^2} \\
R &= \sqrt{5^2 + 10^2} \\
R &= \sqrt{25 + 100} \\
R &= \sqrt{125} = 5\sqrt{5} \text{ N}
\end{aligned}
$$

Nilai akhir resultan gayanya adalah **$5\sqrt{5} \text{ N}$**.

---

### Soal 12: Vektor Kecepatan Relatif (Animasi CSS)
**Pertanyaan:** Pengemudi Mobil Merah (A) melaju ke Timur dengan kecepatan $20 \text{ m/s}$. Pada saat yang sama, Mobil Biru (B) yang berada di jalurnya melaju ke Barat (berlawanan) secepat $15 \text{ m/s}$. Berapakah resultan Kecepatan Relatif Mobil Biru menabrak/melesat melewati Mobil Merah jika dilihat *dari kacamata pengemudi Mobil Merah*?

<style>
  .road-track { position: relative; width: 100%; height: 90px; background: #2c2c2c; border-top: 4px solid #555; border-bottom: 4px solid #555; overflow: hidden; margin: 15px 0; border-radius: 4px; box-shadow: inset 0 0 10px rgba(0,0,0,0.5); }
  .road-dash { position: absolute; top: 50%; width: 200%; height: 4px; border-bottom: 4px dashed #fff; transform: translateY(-50%); opacity: 0.5; }
  .vhcl { position: absolute; top: 10px; width: 60px; height: 30px; border-radius: 6px; color: white; text-align: center; line-height: 30px; font-weight: 800; font-family: sans-serif; font-size: 13px; box-shadow: 0 2px 5px rgba(0,0,0,0.8); }
  .car-A { background: linear-gradient(to right, #dc3545, #c82333); left: -10%; animation: driveA 4s cubic-bezier(0.4, 0, 0.2, 1) infinite; }
  .car-B { background: linear-gradient(to left, #007bff, #0056b3); top: 50px; left: 110%; animation: driveB 4s cubic-bezier(0.4, 0, 0.2, 1) infinite; }
  @keyframes driveA { 0% { left: -20%; } 100% { left: 120%; } }
  @keyframes driveB { 0% { left: 120%; } 100% { left: -20%; } }
</style>
<div class="road-track">
  <div class="road-dash"></div>
  <div class="vhcl car-A">A &rarr;</div>
  <div class="vhcl car-B">&larr; B</div>
</div>

**Pembahasan:**
Konsep Fisikanya: Saat dua benda saling mendekat/berlawanan arah, kecepatan tabrakan/pertemuan mereka bagi mata pengamat saling *menjumlahkan* kekuatan satu sama lain.
Secara vektor matematis: Arah Timur (+), Barat (-).
$V_A = +20 \text{ m/s}$
$V_B = -15 \text{ m/s}$

Kecepatan B Relatif terhadap A dirumuskan $V_{BA} = V_B - V_A$:

$$
\begin{aligned}
V_{BA} &= (-15) - (+20) \\
V_{BA} &= -35 \text{ m/s}
\end{aligned}
$$

Artinya bagi pengemudi A, mobil B melesat ke arahnya dengan sangat cepat di nilai **$35 \text{ m/s}$ ke arah Barat**.

---

### Soal 13: Ketidakpastian Pengukuran Berulang (Animasi Grafik CSS)
**Pertanyaan:** Andi mengukur tebal buku di laboratorium sebanyak 3 kali agar presisi. Ia mendapatkan data: $2,1 \text{ cm}$; $2,2 \text{ cm}$; dan $2,3 \text{ cm}$. Tentukan pelaporan rata-rata tebal buku tersebut ($\bar{x}$) beserta Ketidakpastian Mutlaknya ($\Delta x$) yang ditoleransi!

<style>
  .bar-chart { display: flex; align-items: flex-end; justify-content: space-around; height: 120px; padding: 15px; background: #fafafa; border-left: 3px solid #333; border-bottom: 3px solid #333; margin: 20px 0; border-radius: 0 0 8px 0; }
  .bar { width: 50px; background: #28a745; text-align: center; color: white; border-radius: 4px 4px 0 0; box-shadow: inset -2px -2px 10px rgba(0,0,0,0.2); animation: growBar 1.5s ease-out forwards; transform-origin: bottom; }
  .b1 { animation-delay: 0.2s; height: 70%; transform: scaleY(0); }
  .b2 { animation-delay: 0.5s; height: 80%; transform: scaleY(0); }
  .b3 { animation-delay: 0.8s; height: 90%; transform: scaleY(0); background: #17a2b8; }
  @keyframes growBar { to { transform: scaleY(1); } }
</style>
<div class="bar-chart">
  <div class="bar b1"><span style="display:block; transform:translateY(-20px); color:#333; font-weight:bold;">2,1</span></div>
  <div class="bar b2"><span style="display:block; transform:translateY(-20px); color:#333; font-weight:bold;">2,2</span></div>
  <div class="bar b3"><span style="display:block; transform:translateY(-20px); color:#333; font-weight:bold;">2,3</span></div>
</div>

**Pembahasan:**
a. **Nilai Rata-rata ($\bar{x}$)**: Menjumlahkan lalu dibagi banyaknya data ($n=3$).

$$
\bar{x} = \frac{2,1 + 2,2 + 2,3}{3} = \frac{6,6}{3} = 2,2 \text{ cm}
$$

b. **Ketidakpastian Mutlak ($\Delta x$)**: Dalam fisika SMA, simpangan bisa disederhanakan dengan aturan setengah batas maksimal-minimal.

$$
\begin{aligned}
\Delta x &= \frac{x_{maks} - x_{min}}{2} \\
\Delta x &= \frac{2,3 - 2,1}{2} = \frac{0,2}{2} = 0,1 \text{ cm}
\end{aligned}
$$

**Format Pelaporan Sah:** Laporan lab = **$(2,2 \pm 0,1) \text{ cm}$**.

---

### Soal 14: Perkalian Titik Vektor (Melahirkan Besaran Skalar)
**Pertanyaan:** Usaha ($W$) yang di bab-bab berikutnya akan dibahas merupakan hasil konversi dari perkalian titik ("Dot Product") murni antara vektor Gaya dorong ($\vec{F}$) dan vektor Perpindahan ($\vec{s}$). Jika $\vec{F} = (3\mathbf{i} + 4\mathbf{j}) \text{ N}$ memindahkan benda sejauh rute $\vec{s} = (2\mathbf{i} + 5\mathbf{j}) \text{ m}$, hitunglah besar Energi Usaha yang tersalurkan!

**Pembahasan:**
Berbeda dengan penjumlahan, pada perkalian "Dot" vektor satu dimensi (i dengan i, j dengan j) akan saling melenyapkan sifat vektornya (arahnya hancur) dan melahirkan angka Skalar mutlak (Energi/Usaha).

$$
\begin{aligned}
W &= \vec{F} \cdot \vec{s} \\
W &= (3\mathbf{i} + 4\mathbf{j}) \cdot (2\mathbf{i} + 5\mathbf{j}) \\
W &= (3 \times 2) + (4 \times 5) \\
W &= 6 + 20 = 26 \text{ Joule}
\end{aligned}
$$

Maka diperoleh besar usaha sebesar **$26 \text{ Joule}$**.
