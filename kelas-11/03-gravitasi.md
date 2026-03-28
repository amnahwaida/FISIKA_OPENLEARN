# Bab 3: Medan Gravitasi & Mekanika Langit

[< Kembali ke Daftar Materi Kelas 11](./README.md)| [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Hukum Gravitasi Umum Newton](#1-hukum-gravitasi-umum-newton)
2. [Medan Gravitasi & Variasi Percepatan (g)](#2-medan-gravitasi--variasi-percepatan-g)
3. [Energi Potensial Gravitasi Mutlak](#3-energi-potensial-gravitasi-mutlak)
4. [Potensial Gravitasi (V)](#4-potensial-gravitasi-v)
5. [Kecepatan Lepas (Escape Velocity)](#5-kecepatan-lepas-escape-velocity)
6. [Gerak Orbit Satelit & Kecepatan Orbit](#6-gerak-orbit-satelit--kecepatan-orbit)
7. [Hukum-Hukum Kepler (I, II, III)](#7-hukum-hukum-kepler-i-ii-iii)
8. [Titik Lagrange & Medan Gravitasi Nol](#8-titik-lagrange--medan-gravitasi-nol)
9. [Filosofi Ruang Waktu Einstein](#9-filosofi-ruang-waktu-einstein)

---

## 1. Hukum Gravitasi Umum Newton

Sir Isaac Newton menyadari bahwa apel yang jatuh ke tanah dan Bulan yang mengorbit Bumi digerakkan oleh satu hukum tunggal: **Gravitasi**. 

**Prinsip Utama:**
Setiap benda bermassa di alam semesta ini saling tarik-menarik dengan gaya yang berbanding lurus dengan hasil kali kedua massa dan berbanding terbalik dengan kuadrat jarak antara pusat massa keduanya.

$$
\Large F = G \cdot \frac{M \cdot m}{r^2}
$$
- **$G$:** Konstanta Gravitasi Umum ($6,67 \times 10^{-11} \text{ Nm}^2\text{/kg}^2$).
- **$r$:** Jarak antara **Pusat** benda (bukan permukaan!).

> [!NOTE]
> Konstanta $G$ sangatlah kecil. Inilah alasan mengapa Anda tidak merasa ditarik secara fisik oleh teman di sebelah Anda, namun Anda merasa "ditarik" oleh Bumi yang masif ($6 \times 10^{24} \text{ kg}$).

---

## 2. Medan Gravitasi & Variasi Percepatan ($g$)

**Medan Gravitasi** adalah ruang di sekitar benda bermassa di mana benda lain akan merasakan gaya gravitasi. Besarnya kuat medan gravitasi di suatu titik setara dengan percepatan gravitasi ($g$).

$$
\Large g = G \cdot \frac{M}{r^2}
$$

### 2.1 Variasi Ketinggian ($h$)
Semakin jauh Anda menjauh dari pusat planet ($r = R + h$), tarikan gravitasi akan melemah sesuai kuadrat jaraknya.

$$
\Large g_h = g_{permukaan} \cdot \left( \frac{R}{R+h} \right)^2
$$

### 2.2 Berat Astronot di Luar Angkasa
Mengapa astronot melayang di Stasiun Luar Angkasa (ISS)? Bukan karena tidak ada gravitasi (di ISS, gravitasi masih sekitar $90\%$ Bumi), melainkan karena mereka sedang dalam kondisi **Jatuh Bebas Kontinu** (Kecepatan orbit menyeimbangkan tarikan jatuh).

---

## 3. Energi Potensial Gravitasi Mutlak

Energi Potensial ($Ep$) yang kita pelajari di kelas 10 ($mgh$) hanyalah penyederhanaan untuk jarak dekat. Untuk mekanika langit, kita menggunakan definisi mutlak:

$$
\Large Ep = -G \cdot \frac{M \cdot m}{r}
$$

> [!IMPORTANT]
> **Mengapa Negatif?**
> Tanda negatif menunjukkan bahwa benda sedang "terperangkap" dalam sumur gravitasi planet. Anda butuh energi POSITIF (bahan bakar roket) untuk menaikkan energi tersebut menuju NOL (titik tak terhingga di mana tarikan planet sudah tidak terasa).

---

## 4. Potensial Gravitasi ($V$)

Potensial Gravitasi adalah energi potensial per satuan massa di suatu titik medan. Ini adalah besaran skalar yang menggambarkan "kedalaman" sumur gravitasi.

$$
\Large V = \frac{Ep}{m} = -G \cdot \frac{M}{r} \quad (\text{J/kg})
$$

---

## 5. Kecepatan Lepas (Escape Velocity)

Ingin pergi dari Bumi dan tidak pernah kembali? Roket Anda harus memiliki kecepatan awal yang cukup besar agar Energi Totalnya $\geq 0$. Kecepatan minimum ini disebut **Kecepatan Lepas**.

$$
\Large v_e = \sqrt{\frac{2 \cdot G \cdot M}{R}} = \sqrt{2 \cdot g \cdot R}
$$
- Untuk Bumi, $v_e \approx \mathbf{11,2 \text{ km/s}}$ ($40.320 \text{ km/jam}$). Tanpa kecepatan ini, roket Anda akan selalu jatuh kembali ke pelukan Bumi.

---

## 6. Gerak Orbit Satelit & Kecepatan Orbit

Agar satelit tetap berkeliling melingkar tanpa jatuh, Gaya Gravitasi harus bertindak sebagai Gaya Sentripetal ($F_g = F_s$).

$$
\Large G \cdot \frac{Mm}{r^2} = \frac{m v^2}{r} \implies v_o = \sqrt{\frac{G \cdot M}{r}}
$$

### 6.1 Satelit Geostasioner
Satelit yang memiliki periode orbit tepat $24$ jam. Ia akan terlihat "diam" nangkring di langit di atas titik yang sama di Bumi. Sangat penting untuk komunikasi dan siaran TV. Orbitnya berada pada ketinggian sekitar $36.000$ km.

---

## 7. Hukum-Hukum Kepler (I, II, III)

Johannes Kepler memberikan hukum empiris mengenai tarian planet:
1. **Hukum I (Lintasan):** Semua planet mengorbit Matahari dalam lintasan **Elips**, dengan Matahari berada di salah satu titik fokusnya.
2. **Hukum II (Luas):** Garis hubung planet-matahari menyapu **Luas yang sama dalam selang waktu yang sama**. (Planet bergerak lebih cepat saat dekat matahari/perihelion).
3. **Hukum III (Harmonik):** Kuadrat periode orbit ($T$) berbanding lurus dengan pangkat tiga jari-jari rata-rata lintasan ($R$).
   

$$
\Large \frac{T^2}{R^3} = \text{Konstan} \implies \frac{T_1^2}{R_1^3} = \frac{T_2^2}{R_2^3}
$$

---

## 8. Titik Lagrange & Medan Gravitasi Nol

Di antara dua benda langit (misal Bumi dan Bulan), terdapat titik-titik di mana tarikan gravitasi keduanya saling meniadakan atau bekerja sama sedemikian rupa sehingga objek kecil bisa tetap diam relatif terhadap keduanya. 
- **Titik Lagrange L1:** Di antara Bumi-Bulan, tempat ideal untuk menaruh teleskop pengamat matahari.
- **Titik Medan Nol:** Titik di mana $F_{\text{bumi}} = F_{\text{bulan}}$. Objek di sini tidak merasakan berat ke arah manapun.

---

## 9. Filosofi Ruang Waktu Einstein

Newton menganggap gravitasi sebagai "gaya tarik gaib" instan. Pada 1915, Albert Einstein lewat **Relativitas Umum** mengoreksinya:
Gravitasi bukanlah gaya, melainkan **Kelengkungan ruang dan waktu** akibat adanya massa. 
> *"Massa memberitahu ruang bagaimana cara melengkung; Ruang melengkung memberitahu massa bagaimana cara bergerak."*

Sinar cahaya pun yang tidak bermassa akan terlihat belok saat melewati bintang besar karena mengikuti lintasan ruang yang melengkung tersebut (Lensa Gravitasi).

---

## Lihat Juga
- [Dinamika Partikel](../kelas-10/03-dinamika.md)
- [Latihan Soal Bab 3 Gravitasi](latihan-soal/README.md)
