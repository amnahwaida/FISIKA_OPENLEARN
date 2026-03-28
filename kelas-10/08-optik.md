# Bab 8: Cermin, Lensa, dan Alat Optik

[< Kembali ke Daftar Materi Kelas 10](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
1. [Sifat Cahaya & Pemantulan Cermin Datar](#1-sifat-cahaya--pemantulan-cermin-datar)
2. [Cermin Lengkung (Sferis) dan Aturan Tanda](#2-cermin-lengkung-sferis-dan-aturan-tanda)
3. [Pembiasan dan Hukum Snellius](#3-pembiasan-dan-hukum-snellius)
4. [Lensa Tipis dan Kekuatan Dioptri](#4-lensa-tipis-dan-kekuatan-dioptri)
5. [Rumus Pembuat Lensa (Lens Maker's Equation)](#5-rumus-pembuat-lensa-lens-makers-equation)
6. [Mata Manusia dan Reparasi Kacamata](#6-mata-manusia-dan-reparasi-kacamata)
7. [Kaca Pembesar (Lup)](#7-kaca-pembesar-lup)
8. [Alat Optik Instrumen Majemuk](#8-alat-optik-instrumen-majemuk)
9. [Aplikasi Elite & Filosofi Ruang (Aberasi)](#9-aplikasi-elite--filosofi-ruang-aberasi)

---

## 1. Sifat Cahaya & Pemantulan Cermin Datar

Cahaya di dalam optik geometri dimodelkan sebagai sekumpulan sinar lurus sejajar (Ray Optics). Karena bersifat partikel lurus, merambatkannya mematuhi Hukum Pemantulan Mutlak:
**"Sinar Datang = Sinar Pantul ($i = r$)"** terhadap garis normal tegak lurus cermin.

**1. Sifat Bayangan Cermin Datar Murni:**
- Maya (di dalam/di belakang kaca).
- Tegak (tidak terbalik atas-bawah).
- Berlaku efek perputaran membalik lateral (Kiri menjadi Kanan).
- Jarak Benda ke cermin ($s$) = Jarak Bayangan ke cermin ($s'$).

**2. Efek Dua Cermin Bersudut:**
Jika Anda berdiri di tengah apitan dua cermin datar dengan sudut $\alpha$, kemunculan ilusi bayangan ($n$) yang memantul satu sama lain adalah:

$$
\Large n = \frac{360^\circ}{\alpha} - 1
$$

*(Bila hasilnya desimal genap, bulatkan ke bawah rasional).*

> [!TIP]
> Berapa sentimeter Anda harus membeli cermin minimum garasi rias agar seluruh jempol kaki hingga puncak rambut Anda ($h$) masuk *full body*? Anda secara fisika pasti HANYA butuh cermin datar setinggi separuh absolut postur diri Anda ($\frac{1}{2}h$) murni dan letakkan ia menggantung tepat di posisi mata Anda ke tengah tubuh! Membeli setinggi badan penuh adalah pembaziran uang belaka.

---

## 2. Cermin Lengkung (Sferis) dan Aturan Tanda

Cermin berlekuk merupakan irisan bola memusat raksasa. Terdapat dua jenis ekstrim:
1. **Cermin Cekung** (Positif / Konvergen): Mengumpulkan pendaran cahaya seakan fokus menajam di satu titik pusat ($f$ bernilai POSITIF).
2. **Cermin Cembung** (Negatif / Divergen): Menghambur-pecahkan sinar yang jatuh menjauh dari kaca ($f$ bernilai NEGATIF). Kaca spion mobil/tikungan gila!

**Rumus Fundamental Mutlak Optik (Mirror Equation):**

$$
\Large \frac{1}{f} = \frac{1}{s} + \frac{1}{s'}
$$

**Perbesaran Lateral Bayangan ($M$):**

$$
\Large M = \left| \frac{s'}{s} \right| = \left| \frac{h'}{h} \right|
$$

> [!WARNING]
> **ATURAN TANDA HARGA MATI (Rule of Optics)**
> Mayoritas siswa gagal dalam optik karena salah menyelisik tebakan tanda variabel. Hafalkan sumpah ini:
> - Fokus $f$ $\to$ (+) untuk Cermin Cekung, (-) untuk Cermin Cembung.
> - Benda Asli $s$ $\to$ selalu (+) (di alam nyata depan kaca rias).
> - **Bayangan $s'$ $\to$ (+):** Sifat **NYATA**, letak terjerembab jatuhnya DI DEPAN KERANJANG CERMIN (harus ditangkap layar boks putih proyektor bioskop, dan posisinya dipastikan **TERBALIK ATAS BAWAH**).
> - **Bayangan $s'$ $\to$ (-):** Sifat **MAYA**, berada nampak tembus bayang ilusi DI DALAM CERMIN/belakang. Dan pastinya **TEGAK**.

---

## 3. Pembiasan dan Hukum Snellius

Terjadi ketika foton cahaya melintasi masuk perbatasan dua kepadatan atmosfer material (Misal: Udara menabrak masuk Kolam Air bening). Cahaya dipaksa mengerem lambat, arah merambat terpelanting menikung serong patah ke dasar.

Setiap padatan/cairan di jagat raya memiliki angka "kekakuan menghambat laju absolut" alias **Indeks Bias Benda ($n$)** berbanding lari cepat di hampa udara Kosmos ($v_{hampa} = c$).

$$
\Large n = \frac{c}{v_{benda}}
$$

**Hukum Belokan Maut Snellius:**

$$
\Large n_1 \cdot \sin \theta_1 = n_2 \cdot \sin \theta_2
$$

Dimana $\theta$ murni harus bertolak peluru diukur dari tongkat penancap palang Garis Normal tegak air (Bukan dari garis mendatar pinggir permukaan/horison!).

### 3.1 Pemantulan Internal Sempurna (Total Internal Reflection / TIR)
Bila Anda menyelam di kolam, dan menyorot senter melesat menanjak menyasar tajam pinggiran mendatar pembatas air ke arah atmosfer udara yang merenggang ($n_{air} > n_{udara}$), cahaya bukannya menembus melepaskan diri menjadi terang luar riak, melainkan mendadak disiksa HANCUR dan DIPANTULKAN MURNI SEPENUHNYA kembali memutar ke jurang dasar kolam murni layaknya menabrak cermin ajaib mutlak.

Syarat ini mensyaratkan tabrakan menabrak harus menyentuh Sudut Kritis ($\theta_k$) murni kematian batas pantul sempurna ke udara luar:

$$
\Large \sin \theta_k = \frac{n_{\text{renggang}}}{n_{\text{rapat}}} = \frac{n_2}{n_1}
$$

Sistem fiber optik kabel data merantai kebal bocoran internet antar samudera seratus persen bergantung di prinsip pelipatan tertekan hancur cahaya TIR ini di dalam sumsum serat kaca silika.

---

## 4. Lensa Tipis dan Kekuatan Dioptri

Lensa bekerja kebalikan ekstrem dari cermin. Di lensa bias kaca bening menembus layar.
1. **Lensa Cembung (Bikonveks):** Sang pengumpul titik laser surya di tengah membara. (Fokus $f \to \text{Positif}(+)$).
2. **Lensa Cekung (Bikonkaf):** Sang penebal pinggiran melarang menyatu sinar. (Fokus $f \to \text{Negatif}(-)$).

Persamaan dan perbesaran persis absolut identik diwarisi dari Cermin sferik murni: $\frac{1}{f} = \frac{1}{s} + \frac{1}{s'}$.
Namun Aturan Bayangannya berkebalikan letaknya di Alam Lensa!
*(Nyata = menembus laju keluar di sisi Sebelah Belakang Kaca bening; Maya = malahan tersangkut pendaran bayang bersisian bersama tepat di mana letak Sang Benda berada di ranah asalnya Depan Lensa).*

**Kekuatan Lensa Optik Muka ($P$):**
Aplikasi praktis resep dioptri kacamata dokter, bukan lagi milimeter fokus tapi satuan **Dioptri (D)** murni dengan variabel fokus paksaan seratus ditekuk:

$$
\Large P = \frac{1}{f \text{ (dalam meter)}} \quad \text{atau} \quad P = \frac{100}{f \text{ (dalam cm)}}
$$

---

## 5. Rumus Pembuat Lensa (Lens Maker's Equation)

Bagi industri pabrikan mikroskop elit atau pemotong balok kaca bening kacamata, mereka tak repot memikirkan bayangan. Mereka hanya menilik kepadatan jenis batu murni indeksnya ($n_L$) dan mengeruk menderajatkan potong radius permukaan kiri ($R_1$) dan kanan irisan lensa lengkung bening tersebut ($R_2$).

$$
\Large \frac{1}{f} = \left(\frac{n_{\text{lensa}}}{n_{\text{medium}}} - 1 \right) \left( \frac{1}{R_1} + \frac{1}{R_2} \right)
$$

> [!WARNING]
> Aturan lengkung potong Pabrik ($R_1$ dan $R_2$):
> - **Permukaan Cembung:** Menjorok melengkung menggunung ke luar $\implies$ Radius Potong (+) Plus.
> - **Permukaan Cekung:** Terlubang menukik dikupas ke dalam $\implies$ Radius (+) Minus.
> - **Permukaan Datar Murni:** Rata setara papan meja $\implies R = \infty$ tak hingga batas ($1/R = 0$).

---

## 6. Mata Manusia dan Reparasi Kacamata

Mata normal (Emetropi) memaku lensa mencembung/menyabit rileks fleksibel dari Titik Jauh melesat di raksasa ($PR = \infty$) ditarik keras setidaknya titik Dekat baca koran wajar $25 \text{ cm}$ ($PP = 25 \text{ cm}$).

### 6.1 Miopi (Rabun Jauh)
- Bayangan tak henti kelewatan jatuh tembus murni di ranah DEPAN makula Retina saraf.
- Penyebab: Bola mata hiper panjang membujur atau lensa tebal cacat hiper.
- Titik lelah pandang jauh $PR < \infty$ meter tak hingga (hanya sanggup jelas di letak $PR$ ini).
- **Reparasi Lensa Kacamata (-) Minus Tipe Cekung Pembuka Sudut:**

$$
\Large P_{\text{Miopi}} = -\frac{100}{PR (\text{dalam cm})}
$$

### 6.2 Hipermetropi (Rabun Dekat Tua)
- Kertas koran berjarak normal dekat 25 cm membias tertahan malah melesat JATUH terhempas tembus di BAWAH BELAKANG Retinanya sana (Kabur Blur tak meyakinkan terbaca).
- Titik paling batas nampak dekatnya sangat parah memanjang jauh diletakkan $PP > 25 \text{ cm}$ mutlak tertarik.
- **Reparasi Kacamata Bikonveks (+) Positif Kuat:**

$$
\Large P_{\text{Hiper}} = 4 - \frac{100}{PP (\text{dalam cm})} \quad \text{*(Asumsi murni Sn = 25 cm)*}
$$

---

## 7. Kaca Pembesar (Lup)

Kacamata gila primitif lensa Cembung Positif pembuat besar ($+$). Digenggam tegang menatap serangga super kecil di jarum titik sempit mendekati sebelum area Fokus lensa agar ilusi terompet bayangan tegak maya membesar raksasa muncul serempak di belakang.

**Kalkulasi Ganda Perbesaran Murni Serangga ($M$):**
1. **Mata Paring Ekstrem Lelah Berakomodasi Seterangnya:** (Si bayangan diarahkan murni membentur masuk sejajar titik $s' = -25 \text{ cm}$ terkuat lelah lensa mata).

$$
\Large M = \frac{25}{f} + 1
$$

2. **Mata Rehat Melamun Santai Penuh Rileks (Tanpa Akomodasi):** Bayangan ditembak buang terlempar maya menjauh ke titik maya Infinity semesta $s' = \infty$.

$$
\Large M = \frac{25}{f}
$$

---

## 8. Alat Optik Instrumen Majemuk

### 8.1 Mikroskop Kuman Biologi (Dua Tingkat Cembung Ganda)
Terlaksana absolut mutlak melalui paduan 2 lensa membedah rentang serangga.
- **Lensa Objektif (Bawah menyentuh darah spesimen):** Melontarkan realita pembesaran ekstrim Pertama jatuh Terbalik Nyata rahasia raksasa di lorong tabung tengah. (Syarat $f_{\text{ob}}$ amat pendek curam, $s_{\text{ob}}$ benda wajib sekilas lewat batas $f_{\text{ob}}$ pinggir).
- **Lensa Okuler (Menempel Kornea Peneliti):** Bereaksi memungut tembakan raksasa objektif dan menggandakannya lagi melalui trik Kaca Pembesar Lupa mutlak yang menyiksa maya ekstrim bayang mutlak akhir di saraf Retina menjadi ilusi.

**Total Magnifikasi Pembedahan Serangga Mutlak:**

$$
\Large M_{\text{total}} = M_{\text{objektif}} \times M_{\text{okuler}}
$$

Panjang Tembaga Koridor Alat (Jarak antar $2$ sekian milimeter lensa $d$):

$$
\Large d = s'_{\text{ob}} + s_{\text{ok}}
$$

### 8.2 Teropong (Teleskop Bintang) Lensa Bikonveks Raksasa
Terbalik total dari mikroskop, $f_{\text{objektif}}$ di astronomi harus raksasa menyerap tembusan jutaan serpihan sinar rembulan, sementara the $f_{\text{okuler}}$ sekadar tipisan pemfokus intai kecil di mata peramal. Pembesaran astronomi santai mata tak lelah (Tanpa Akomodasi Bintang):

$$
\Large M = \frac{f_{\text{ob}}}{f_{\text{ok}}} \qquad \text{Dan tabung terpotong panjang} \ d = f_{\text{ob}} + f_{\text{ok}}
$$

---

## 9. Aplikasi Elite & Filosofi Ruang (Aberasi)

Ilusi rumusan Fisika klasik selalu hancur ketika dihadapkan pada kurva nyata irisan bola tebal cacat mikroskop murni.

1. **Aberasi Kromatik (Banjir Warna Pucat Pelangi Lensa Cahaya Pinggiran)**
   Mengapa teleskop kaca murahan menampilkan tepian bias warna-warni pelangi tipis mengitar mengganggu tepi bulat objek bulannya? Tersebabkan **Gelombang Biru dan Merah memiliki kecepatan serapan indeks bias murni tak setara persis** ($n_{\text{biru}} \neq n_{\text{merah}}$)! Sudut patahan biru lebih keras mencekik dalam mendarat fokus mendahului si lambat fokus pinggir cahaya pelangi Merah di garis utama retinam! (Obat perbaikan ini hanyalah menggandeng tumpuk menyatukan mutlak silangan gabungan **Lensa Akromatik** positif dan cermin negatif tawar serempak).

2. **Aberasi Sferis (Kabin Kabur Garis Lengkung Luar Sinar Bintang)**
   Sinar sejati semesta murni yang masuk mepet menghantam area batas terluar jauh pinggiran lengkung cermin murni justru menggunting titik potong jatuh mendarat liar mendahului sebelum di fokus nyata aslinya. Membikin cermin sferikal gembung gila memproduksi bauran kabur putih bayangan di dinding teater. (Solusi final elit Newton di jagat murni astronomi teleskop satelit observatorium masa depan dunia hanyalah menebang mengganti sang lengkung bolanya bertransformasi melesat memahat parabola murni Parabola cermin sempurna satu penampang murni).

---

## Lihat Juga
- [Gelombang dan Bunyi](./07-gelombang-bunyi.md)
- [Latihan Soal Bab 8](latihan-soal/README.md)
