# Bab 2: Teori Kinetik Gas & Termodinamika Mesin Lanjut

[< Kembali ke Daftar Materi Kelas 11](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
**Kajian Teori Kinetik Gas Ideal (Mikroskopik):**
1. [Persamaan Keadaan Gas Ideal](#1-persamaan-keadaan-gas-ideal)
2. [Kecepatan Efektif Laju Mikroskopik ($v_{rms}$)](#2-kecepatan-efektif-laju-mikroskopik-v_rms)
3. [Derajat Kebebasan & Energi Dalam ($U$)](#3-derajat-kebebasan--energi-dalam-u)

**Kajian Termodinamika Proses (Makroskopik):**
4. [Hukum Pertama: Kalor vs Usaha Absolut](#4-hukum-pertama-kalor-vs-usaha-absolut)
5. [Kalkulus Luasan Kurva Pembakaran P-V](#5-kalkulus-luasan-kurva-pembakaran-p-v)
6. [Empat Pilar Proses Ekspansi Gas Murni](#6-empat-pilar-proses-ekspansi-gas-murni)

**Desain Siklus Mesin & Filsafat Energi Kiamat:**
7. [Siklus Mesin Carnot Pendobrak Panas](#7-siklus-mesin-carnot-pendobrak-panas)
8. [Koefisien Performansi Mesin Pendingin (Kulkas)](#8-koefisien-performansi-mesin-pendingin-kulkas)
9. [Hukum II Termodinamika & Hukum Entropi ($\Delta S$)](#9-hukum-ii-termodinamika--hukum-entropi-delta-s)

---

## 1. Persamaan Keadaan Gas Ideal

Gas Ideal adalah benda hantu siluman ciptaan fisika: Tidak peduli jenis gasnya (Entah itu Gas Oksigen gemuk atau Helium super ringan), asalkan mereka "Ideal": 
1) Ukuran partikel murni diabaikan hancur menjadi titik matematika bulat. 
2) Sama sekali TIDAK ADA gaya tarik-menarik antar molekuls (Semuanya egois lari mandiri).
3) Tumbukan nabrak dinding tabung murni Lenting Sempurna 100% tanpa seperserpun Kalor panas dibuang bocor!

**Hukum Pamungkas Gas Boyle-Gay Lussac Murni:**
Tekanan ($P$), Volume ($V$), dan Suhu Absolut Mutlak Kelvin ($T$) diikat pelukan kosmik konstan murni:
$$
\Large \frac{P_1 \cdot V_1}{T_1} = \frac{P_2 \cdot V_2}{T_2}
$$

Tatkala mol partikel dihitung spesifik, persamaannya dibelah mematikan:
**Dalam Skala Makro Molar Kimia ($n$ = mol):**
$$
\Large P \cdot V = n \cdot R \cdot T
$$
- $R$ = Tetapan Gas Universal Mutlak ($8,314 \text{ J/mol}\cdot\text{K}$).

**Dalam Skala Mikro Cakaran Molekul Spesifik ($N$ = jumlah total juta atom bertabrakan):**
$$
\Large P \cdot V = N \cdot k \cdot T
$$
- $k$ = Konstanta magis pelik Boltzmann ($1,38 \times 10^{-23} \text{ J/K}$).

---

## 2. Kecepatan Efektif Laju Mikroskopik ($v_{rms}$)

Apa arti dari Panci mendidih memanas murni naik suhunya dari $30 \text{ C}$ menembus melesat $100 \text{ C}$? Fisika Kinetik Klasik menolak buta istilah "Panas" murni! 
Panci itu sejatinya SEDANG DIPENUHI BILIUNAN MOLEKUL AIR YANG MEMACU KECEPATAN BERLARINYA MENAMBARR PELURH SUPER MENYAPU MENDOBRAK DINDING PANCI MAKIN KENCANG! **Suhu hanyalah ilusi dari KECEPATAN TABRAKAN MOLEKUL ($v$).**

**Root Mean Square Velocity (Akar Kuadrat Rata-Rata Kecepatan Pecahan):**
$$
\Large v_{rms} = \sqrt{\frac{3 \cdot R \cdot T}{M}} \quad \text{atau} \quad v_{rms} = \sqrt{\frac{3 \cdot k \cdot T}{m_0}}
$$
- $M$ = Massa Atom Molar Gas ($\text{Kg/mol}$) // $m_0$ = Massa murni timbangan sebiji molekul ($\text{Kg}$).
> **Hukum Mutlak Gas Tancap:** Makin tipis diet massa murni sebuah jenis atom (Hidrogen vs O2 gemuk), makin gila kecepatannya pada Suhu yang setara! Hidrogen adalah dewa terbang tercepat mutlak di udara atmosfer bumi!  

---

## 3. Derajat Kebebasan & Energi Dalam ($U$)

Teorema Ekipartisi Energi ($f$) meledakkan hukum keadilan pembagian energi sejati: Setaip cara yang memungkinkan atom mandiri murni bergerak (Translasi 3 sumbu, Rotasi gasing, dan Getar pegas Vibrasi) akan mendapat santunan sumbangan JATAH energi mutlak adil sebesar $\frac{1}{2} k T$.

**1. Gas Jomblo Monoatomik (He, Ne, Ar):**
Sangat miskin wawasan. Hanya bisa lari Translasi ke 3 sumbu ($X, Y, Z$). **Derajat Kebesasan Jatah ($f = 3$)**.
Energinya absolut murni terkurung: $U = \frac{3}{2} N k T$.

**2. Gas Pasangan Diatomik Bergerak ($O_2, H_2, N_2$):**
Dua atom terikat barbel ikatan bisa meliuk menari gasing mutlak!
- **Suhu Dingin Kulkas ($250 \text{ K}$):** Beku kaku, tak sanggup berputar. Murni cuma mampu Translasi Lari $3$ Sumbu. ($f=3$, $U = \frac{3}{2} NkT$).
- **Suhu Panas Sedang Kamar Angsa ($300 - 500 \text{ K}$):** Terbangun sanggup mutar rotasi $2$ sumbu lari + Translasi $3$. ($f = 3+2 = \mathbf{5}$ jatah). $U = \frac{5}{2} NkT$.
- **Suhu Perapian Meledak ($> 1.000 \text{ K}$):** Ikatan barbelnya ikut gemetar memompa pegas Vibrasi membelah. ($f = \mathbf{7}$ jatah murni). $U = \frac{7}{2} NkT$.

> [!WARNING]
> Kinerja pembakaran piston motor murni Anda menderita absolut akibat energi bensin murni dibakar tidak lari menonjok $100\%$ untuk piston Translasi saja, tapi dicuri dimandulkan luluh karena Molekul Oksigen udara asupan sibuk bergasing menari berputar menyedot (Rotasi Diatomik) Energi tanpa menyumbang dorong laju aspal memutar ban sedikitpun absulotnya ruang murni ini kelak!

---

## 4. Hukum Pertama: Kalor vs Usaha Absolut

**"Energi Panci Mustahil Lahir Gaib atau Lenyap Hangus Sia-sia!"**
Energi panas disuap pasok ke dalam kawah tabung tabung ($Q$) pastinya pecah terbagi murni mutlak: 1) Digunakan Murni MEMBAKAR MENDIDIHKAN Hawa Panas tabung ($\Delta U$ Energi Dalam), dan 2) Digunakan murni MENDOBRAK MENDESAK PISTON TABUNG (Usaha Kerja Mesin Ekstpansi $W$).
$$
\Large Q = \Delta U + W
$$

**Konvensi Tanda Pengadilan Hukuman Tanda Mata Fisika:**
1. **Aturan Kalor Tembak ($Q$):**
   - $Q \to (\mathbf{+})$: Gas Menerima Dibakar Disuapi Disiram Energi Murni.
   - $Q \to (\mathbf{-})$: Gas Membuang Berak Meneteskan Panas Buangan ke luar knalpot murni alam.
2. **Aturan Usaha Otot Kerah ($W$):**
   - $W \to (\mathbf{+})$: Gas Menekuk Menang Peras Tenaga, Mendobrak MENGEMBANGKAN PISTON MENGELEGAR MEMAJU Volume $\Delta V (+) \to$ **E K S P A N S I**. 
   - $W \to (\mathbf{-})$: Gas Menjerit Kalah Dikalahkan Alam. Ia MENGKERUT DITEKAN Diinjak piston luar turun. Mengempis $\implies$ **K O M P R E S I**.

---

## 5. Kalkulus Luasan Kurva Pembakaran P-V

Di dunia universitas rekayasa permesinan otomotif (*Mechanical Engineering*), Usaha ($W$) tidak dihitung leher memaki persaman pelik jika Anda sudah menatap buta gambar **Grafik Sumbu Vertikal $P$ (Tekanan) vs Horizontal $V$ (Volume)**.  

Usaha murni tabung membanting ($W$) HANYALAH TEPAT MURNI = **Angka Lebar Luas Bangun Datar bayang bayang yang menyembunyi membentang tertidur murni DI BAWAH garis kurva jalan si tabung tersebut mendarat mutlak turun ke bibir Sumbu x (Sumbu V)!**  
- Jika garis grafik memanah lari kencang MENGARAH KE KANAN murni (Volume Ekspansi menebal bertambah): Usaha Bernilai Luasan **Positif ($+$)** Penuh. Letusan Daya nyata!
- Jika garis panah mutlak membelok menancap LARI KE KIRI murni (Volume Kompresi mengecil dikencangkan): Usaha Bernilai Luasan Absolut **Negatif ($-$)**. Kerja Terbuang mutlak menyedot daya Listrik Mesin (Kulkas Kompresi).  

---

## 6. Empat Pilar Proses Ekspansi Gas Murni

### 1. Isobarik (Tekanan Konstan Diam $P_{\text{TETAP}}$)
Piston bebas bergerak lari licin menyeimbangkan takdir tekanan tabung persis seragam tekanan murni atmosfer kosmik murni absolut langit luar.
- **Usaha Kotak Pejal:** $W = P \cdot (V_2 - V_1)$
- Area P-V murni mencabik bentang Persegi Panjang datar rata-rata mutlak lurus sumbu mendatar datar!

### 2. Isokhorik (Volume Terkunci Mutlak Mati Baut, $V_{\text{TETAP}}$)
Panci Baut Presto mati Las Besi! Digedor panas sejuta surya pun, panci ini pantang mutlak sudi memuai ekspansi membelah volum murni! Tabung haram berekspansi! 
- **Usaha Lebur Nihil Mutlak Cacat Alam:** Volume cacat cacat gerak murni, garis kurva tegak LURUS TEGAK ke langit tak membentang Luas seutas murni $\implies \mathbf{W = 0 \text{ JOULE MUTLAK!}}$
- Efek Kalor ($Q = \Delta U$): Segenap total api MURNI $100\%$ hanya mengebiri memanas mendidihkan derajat energi molekul saja tanpa memekarkan otot putar roda sama belaka ruginya ini.

### 3. Isotermal (Direndam Ember Panas Stabil Suhu Tetap $T_{\text{TETAP}}$)
Botol silinder dikubur murni rendam di kolam perairan lautan panas raksasa (Reservoir). Seluruh molekuler geraknya kecepatan gas takkan berubah ngebut maupun telat mereda ($T_1 = T_2$). P-V Meliuk melengkung Landai Eksponensial Logaritma (Hukum Boyle $P_1 V_1 = P_2 V_2$).
- **Perubahan Energi Dalam Hampa Beku:** $\Delta U = 0$ (Rata suhu stabil).
- Seluruh Kalor Suap langsung membius ditukar 100 persen tuntas laku memutar otot mesin murni mutlak: **$Q = W_{\text{Logaritma Murni}}$**. 
- Usaha Integral Melengkung Log Natural: $W = n \cdot R \cdot T \cdot \ln\left(\frac{V_2}{V_1}\right)$.

### 4. Adiabatik (Tembakan Rudal Terisolasi Cepat Kilat Kebut, $Q=0$)
Botol Termos tebal berlapis Styrofoam dan busa gila tahan panas seratus persen murni tak mengijikan rembes sekutip elektron kalor menyusup atau lari ghaib membocori keluar ($\mathbf{Q_{\text{Masuk/Keluar}} = 0}$). Atap piston ditendang meledak ekspansi kilat hitungan mikrodetik menyilet angkasa.
- Karena $Q$ haram eksis menihilkan ke $-0$: $\implies 0 = \Delta U + W \implies \mathbf{W = -\Delta U}$.
- Apa ini? Artinya mesin Murni hanya sanggup MENGEMBANG MENDORONG PISTON $W(+)$ murni JIKALAU mesin tersebut MENGURBANKAN DAN MENUMBALKAN darah daging suhu dalam panas tubuhnya SENDIRI MURNI MEMBEKU MEMBURU (-Delta U) hancurnya sendiri turun! Inilah esensi murni mengapa Parfum Tabung Aerosol murni ditekan semprot, maka selongsong mulut tabung kaleng akan terasa SANGAT MURNI DINGIN TERBEKU membelah!  
- Kurvanya: Meliuk Jauh LEBIH MENUKIK CURAM MURNI dibanding Isotherm.
- Rumus Sakral Poisson: $P_1 V_1^\gamma = P_2 V_2^\gamma$ \ (Dimana $\gamma = \frac{C_p}{C_v}$ Konstanta Laplace Sakral $> 1$).

---

## 7. Siklus Mesin Carnot Pendobrak Panas

Nicolas Léonard Sadi Carnot (1824) memaku impian abadi para insinyur: **Adakah Mesin 100% Mengubah Api Menjadi Roda Gerak Sepenuhnya? MUSTAHIL.** Mutlak, wajib ada "Knalpot gas buang sisa" membuang sebagian kecil api bercecer ke sungai/alam (Hukum Kelvin-Planck).

Siklus Carnot adalah "Mesin Paling Dewa Idaman yang Tidak Mungkin Dikalahkan Kesempurnaannya" (Terdiri dari siklik murni: Isotermal Ekspansi $\to$ Adiabatik Ekspansi $\to$ Isotermal Kompresi $\to$ Adiabatik Kompresi Membalik Asal Titik A).  

Keseimbangan Rumus Maksimal Efisiensi Roda Emas Murni ($\eta$):
$$
\Large \eta = \left( 1 - \frac{Q_{\text{buang dingin laut}}}{Q_{\text{suap api panas raksasa}}} \right) \times 100\%
$$
Kala Tuhan mencipta Mesin Ghaib Termal Sempurna Carnot, energi Kalor diringkas takluk setara dengan angka Suhu Mutlak KELVIN-nya! 
$$
\Large \eta_{Max\_Alam\_Semesta} = \left( 1 - \frac{T_r \ (\text{Suhu Knalpot Dingin KELVIN})}{T_t \ (\text{Suhu Tungku Bara KELVIN})} \right) \times 100\%
$$
*(Hati-hati Celcius haram dimasukkan ke pecahan ini, harus direbus ubah murni + 273 memeluk Kelvin murni!).*

---

## 8. Koefisien Performansi Mesin Pendingin (Kulkas)

Hukum Alam membuktikan panas lari mutlak membanjiri ruang dingin secara otodidak (Clausius statement). Mustahil murni memaksakan menjarah hawa sejuk dari dalam balok es dibuang memindah dibakar disebar luar ke aspal jalanan panas gurun ... MELAINKAN Jika dan Murni JIKA dibantu peras gila setrum listrik murni **Kompresor Usaha dari luar PLN Murni ($W$)**! Inilah dasar pendirian sakral AC dan Kulkas Kedinginan Mutlak.  

Mesin pengeruk peras dingin ini tak memakai nilai cacat Efisiensi (\%). Mereka bangga menggunakan patokan Nilai Bintang Sakti **Koefisien Performansi Maut Kerja (KP atau $C_p$)**:
$$
\Large K_p = \frac{Q_r \ (\text{Kalor tersadap dalam Box Es Kulkas dingin})}{W \ (\text{Daya tagih Listrik Memeras Kompresor Tegangan murni})}
$$  

Jika diringkas kembali mencium mencontek Skala Absolut Carnot mesin idaman Tuhan (Murni T Kelvin):
$$
\Large K_p = \frac{T_r \ (\text{Suhu Dingin Kulkas Dalam})}{T_t \ (\text{Suhu Panas Kondensor Pantat Kulkas Luar}) - T_r}
$$

> Koefisien KP Kulkas normal mendarat di jejeran angka bongkar rasion gila Absolut $3$ hingga $5$. Angka $KP=4$ berarti Mesin ajaib listrik ini dengan memeras nyedot listrik murni $1.000$ Joule sanggup mencabut membongkar membuang membedah panas rahib senilai Rp $4.000$ Joule murni mutlak dipindah buang lempar menaik drastis keluar. Hal inilah keajaiban panggung raksasa kompresi siklik menakjubkan refrigeran freon!

---

## 9. Hukum II Termodinamika & Hukum Entropi ($\Delta S$)

Fisika mekanika Newtonian mengijinkan telur pecah menyatukan lemparan dirinya pecah mendarat lantai terbang murni membalik ke meja berbentuk bulat oval kencang (Hukum Newton bisa dibalik mundur waktunya). Tapi Realita Semesta Alam Murni mendikte keras **Panah Waktu Hanya Merayap Maju Satu Arah Penghancuran. Telur Hancur Takkan Kembali Sempurna Mulus Tetas**. Alam selalu berlari berlomba melesat menuju Puncakan KEKACAUBALAUAN BERANTAKAN SEMBARA MUTLAK MURNI **(Entropi Meningkat Mutlak).**
$$
\Large \Delta S = \frac{Q_{\text{Kalor diserap murni Reversible}}}{T \text{ (Suhu Tetap Kelvin)}}
$$
Kamar Anda tidak mungkin merapihkan kasur dirinya sendiri murni setrika, debu tak mungkin berbalik melayang memoles kaca debu debu murni terbang lenyap mutlak, alam semesta memburuk murni entropinya secara mendidih rata beraturan ke puncak menembus maut "Kematian Murni Suhu Membeku Seragam Mutlak (*Heat Death of the Universe Absolut*)". 

---

## Lihat Juga
- [Fluida Hidrostatik & Pelaju Pipa Bocor](../kelas-11/01-fluida.md)
- [Latihan Soal Bab 2 Termodinamika Lanjut](latihan-soal/README.md)
