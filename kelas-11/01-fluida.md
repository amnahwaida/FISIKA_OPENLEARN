# Bab 1: Fluida Statis & Dinamis

[< Kembali ke Daftar Materi Kelas 11](./README.md) | [Ke Beranda](../README.md)

---

## Daftar Isi
**Kajian Fluida Statis (Cairan Diam):**
1. [Tekanan Mutlak & Paradoks Hidrostatis](#1-tekanan-mutlak--paradoks-hidrostatis)
2. [Hukum Pascal dan Mekanika Hidrolik](#2-hukum-pascal-dan-mekanika-hidrolik)
3. [Hukum Archimedes dan Berat Semu](#3-hukum-archimedes-dan-berat-semu)
4. [Tegangan Permukaan & Batas Kapilaritas](#4-tegangan-permukaan--batas-kapilaritas)

**Kajian Fluida Dinamis (Aliran Cairan & Gas):**
5. [Debit Aliran & Persamaan Kontinuitas](#5-debit-aliran--persamaan-kontinuitas)
6. [Asas Fundamental Bernoulli](#6-asas-fundamental-bernoulli)
7. [Aplikasi Bernoulli I (Tangki Bocor & Venturimeter)](#7-aplikasi-bernoulli-i-tangki-bocor--venturimeter)
8. [Aplikasi Bernoulli II (Tabung Pitot & Aerodinamika Sayap)](#8-aplikasi-bernoulli-ii-tabung-pitot--aerodinamika-sayap)
9. [Fluida Kental Realitas (Viskositas & Hukum Stokes)](#9-fluida-kental-realitas-viskositas--hukum-stokes)

---

## 1. Tekanan Mutlak & Paradoks Hidrostatis

**Fluida** adalah segala zat yang tak bisa mempertahankan bentuk kaku (tidak mampu menahan tegangan geser), sehingga ia akan mengalir mengikut wadah. Fluida mencakup **Zat Cair** (Volume tetap) dan **Gas** (Otomatis berekspansi memenuhi ruang).

Parameter sakral fluida adalah **Massa Jenis ($\rho$) / Kerapatan:**
$$ \rho = \frac{m}{V} \quad (\text{kg/m}^3) $$
*(Catatan OSN: $\rho_{\text{air murni}} = 1000 \text{ kg/m}^3$; $\rho_{\text{air laut}} \approx 1030 \text{ kg/m}^3$; $\rho_{\text{raksa}} = 13600 \text{ kg/m}^3$).*

### 1.1 Tekanan Hidrostatis ($P_h$)
Tekanan akibat timpaan beban berat air yang menindas dari atas tubuh Anda ke kedalaman menukik.
$$ P_h = \rho \cdot g \cdot h $$
- $h$ $\to$ SANGAT KRUSIAL: Ini adalah **Kedalaman** (diukur terjun menukik **DARI PERMUKAAN AIR KE BAWAH**, BUKAN dari dasar tangki menaik ke atas!).

### 1.2 Tekanan Total Absolut ($P_{abs}$)
Di Bumi terbuka, dasar palung mariana tidak hanya menanggung himpitan kolong air laut, namun juga wajib memikul tekanan tumpukan gumpalan langit lapisan atmosfer murni di atas laut tersebut ($P_0 \approx 1 \text{ atm} = 1,01 \times 10^5 \text{ Pascal}$).
$$ P_{total} = P_0 + P_h = P_0 + (\rho \cdot g \cdot h) $$

> [!WARNING]
> **Paradoks Hidrostatis:**
> Jika Anda memiliki botol air tabung lurus, botol cembung bengkak, tabung pipih zig-zag berliku tajam yang semua basenya terhubung. Tekanan menancap di dasar mutlak SAMA BESAR selama mereka disiram cairan sedalam eleveasi sejajar rata $h$. Tekanan air tidak peduli betapa banyak liukan desain arsitektur pipa penampung, murni hanya patuh sujud pada ketinggian vertikal $h$ atapnya! Inilah yang mendasari prinsip selang perata cor bangunan (Waterpass tukang batu).

---

## 2. Hukum Pascal dan Mekanika Hidrolik

Blaise Pascal menghancurleburkan batasan gaya manusia lewat hukum magis: 
**"Tekanan diam yang dikenakan fluida di dalam ruang kubik tertutup, akan dihamburkan menembak ke SEGALA ARAH dengan kekuatan utuh tidak berkurang sepersenpun!"**

Artinya, Tekanan pomp kecil ($P_1$) mutlak sama gedorannya dengan Tekanan pipa raksasa ($P_2$):
$$ P_1 = P_2 \implies \frac{F_1}{A_1} = \frac{F_2}{A_2} $$

> [!TIP]
> **Sulap Dongkrak Hidrolik Bengkel Mobil:** Bagaimana jari mungil anak kecil ($F_1 = 50 \text{ N}$ tekan di sedotan kecil luas murni $A_1 = 1 \text{ cm}^2$) bisa melanting menaikkan truk tonase raksasa ($F_2 \impliedby ?$) di pipa pijak bantal besar ($A_2 = 1.000 \text{ cm}^2$)?
> $$ F_2 = F_1 \times \left(\frac{A_2}{A_1}\right) = 50 \times 1000 = \mathbf{50.000 \text{ Newton (Truk 5 Ton Terangkat Jari!)}} $$
> Mekanisme inilah alasan injakan rem depan pedal kecil jari kaki pengemudi mobil diubah menjadi sergapan cengkram balok besi kaliper merobek roda lari truk baja tronton pemicu rem hidrolik!

---

## 3. Hukum Archimedes dan Berat Semu

Eureka! Benda yang dicelupkan melesak ke kubangan cairan akan sekujurnya diamuk tembakan penolakan gaya dorong vertikal merongrong melontar membumbung **(Gaya Apung / Bouyancy $F_a$)** seberat absolut bobot volume tumpahan cairan malang yang diongkek tumpah tergusur dari tanah pijaknya oleh oknum ruang benda si pencemplung itu!

$$ F_{a} = \rho_{\text{FLUIDA}} \cdot V_{\text{Benda yang TERCELUP}} \cdot g $$

### 3.1 Status Sosial Tumbukan Tiga Batas ($W$ vs $F_a$)
1. **TERAPUNG:** Objek lebih enteng murni ($\rho_{\text{benda}} < \rho_{\text{fluida}}$). Kapal laut baja bisa mengapung bukan karena baja enteng laut, melainkan lambung perut kapal berisi rongga gempuran jutaan gumpal udara kosong $\to$ merusak Rata-rata $\rho$ hancur ke level kayu enteng! $V_{\text{celup}}$ hanya separuh belah.
2. **MELAYANG:** Melayang zombie hantu mengutuk tak ke atas tak ke dasar ($\rho_{\text{benda}} = \rho_{\text{fluida}}$). Inilah rahasia teknik hidup Kapal Selam dengan mengatur tangki Ballast isi rongga udara ditarik tarik. Volume $100\%$ terendam murni $V_c = V_b$.
3. **TENGGELAM:** Objek tumpat tak terbantah berat mutlak membentur pecah ke dasar keramik ($\rho_{\text{benda}} > \rho_{\text{fluida}}$). Volume seluruh utuh tancap terendam mutlak penuh $V_c = V_b$.

### 3.2 Misteri Keringanan Misterius (Berat Semu, $W'$ atau $W_{semu}$)
Mengapa Anda kuat membopong gerbong manusia hidup gempal saat berenang tumpu di kolam, namun lengan akan memelintir patah tulang letih gontai lumpuh bila membopong ia keluar lari dari air tangga ombak? Kerena campur tangan Bantuan Dewa Apung ($F_a$) menopang mengurangi!
$$ W_{\text{semu}} = W_{\text{asli udara}} - F_a $$
*(Cek neraca timbang lengan batu dalam keranjang dicelup kolam, jarum beratnya merosot anjlok patah menipu ke angka kecil seolah ia gabus!).*

---

## 4. Tegangan Permukaan & Batas Kapilaritas

Tegangan gesekan selabut memaku permukaan cairan rahim disebabkan tarikan rantai gila molekul air sesamanya (Gaya ikat **Kohesi** memburu diri absolut saling kepal ke tengah). Hal inilah yang menitah bentuk air mendarat lali membola di talas (mengincar volume rahim terhemat sfera) dan mengawinkan jarum serangga ngengat rawa Nyamuk Berjalan terbang di air dan patahan koin klip besi tak jebol mengapung pelan di piring air!
$$ \gamma = \frac{F}{d} \ \quad (\text{Newton/meter}) $$

### 4.1 Meniskus Permukaan Tabung Kaca Ujung
- **Meniskus CEKUNG ($\cup$):** Cairan (Misal Air). Molekul pinggir air lebih tergila-gila murni cium bermanja merambati memeluk memanjat dinginnya kaca pingngiran dinding daripada memeluk murni temannya sendiri (**Adhesi** Air-Kaca > **Kohesi** Air).
- **Meniskus CEMBUNG ($\cap$):** Logam Cair (Misal Raksa maut perak). Raksa angkuh murni jijik benci merapatkan diri ke belingan silika kaca. Mereka menarik melingkar ke tengah rahim membentuk gundukan embun melingkar bulat pongah nangkring (**Kohesi** mutlak menang telak > **Adhesi** buang buang waktu ke kaca).

### 4.2 Kapilaritas Menarik Ke Puncak Pohon (Hukum Jurin)
Inilah trik mukjizat pohon Redwood menjulang merangkak menyekah meresap tetesan air menyedot tanah ke akar setinggi awan gumpal langit. Air sanggup **MENDANGAK MEMANJAT PIPA LUBANG SEMPIT** celah urat tanpa mesin hisap motor sama sekali belaka mendatangi daun melipati gravitasi! 
$$ y = \frac{2 \gamma \cos \theta}{\rho \cdot g \cdot R} $$
Ketinggian memanjat naik ($y$) menembus mendesak semakin jauh mutlak memuncak bila celah retak pipa rambut urat ($R$ Jari tabung kapiler) semakin dikerdil menyempit kurus (Berbanding Terbalik)! 

---

## 5. Debit Aliran & Persamaan Kontinuitas

Kita tinggalkan air statis dan terjun ke putaran pusaran deras keran memancar!
**Debit ($Q$)** adalah volume galon kubik raksasa air yang dipompa dimuntahkan disembur paksa lari per detiknya waktu mutlak.
$$ Q = \frac{V}{t} \quad (\text{m}^3\text{/s}) $$
Karena volume murni ($V$) balok adalah Luas alas terali pipa potong penampang melintang mutlak ($A$) dikali pergeseran pancaran melesat jauh ruang gerak lari ($x = v \cdot t$), debit menjelma wujud rahasia kedua:
$$ Q = A \cdot v $$

### 5.1 Persamaan Talian Darah Kontinuitas Pipa
Setiap tetes aliran mutlak hampa kompresi tumpat murni (Hukum Kekekalan Massa)! Jika pipa mendadak menciut menyempit leher botol mencekik, air TIDAK mengendap parkir macet di pinggir persis laksana mobil jalan tol tumpukan antrean! Air murka nekat memelanting lari seratus kali lipat melesat mengerikan memecah mendongkrak **KECEPATAN MURNINYA**!
$$ Q_1 = Q_2 \implies A_1 \cdot v_1 = A_2 \cdot v_2 $$
> Aplikasi Murni: Mengapa kala mencuci mobil kotor bodi dekil parah, jempol Anda harus meremas menyumbat mati ujung selang air memencet mulutnya kerdil? Agar selang ciutan area ($A_{sempit}$ terjun tipis drastis) membanting kecepatan tembak rudal roket ($v$ menembus hiper-laju jet!) memecah murni lumpur kerak kotor ban membandel!

---

## 6. Asas Fundamental Bernoulli

Daniel Bernoulli ($1738$) menurunkan kengerian mukjizat fisika maut dari Kekekalan Mekanik Energi Mutlak (Kerja $P$, Kinetik $\frac{1}{2}mv^2$, dan Potensial $mgh$):
$$ P_1 + \frac{1}{2} \rho v_1^2 + \rho g h_1 = P_2 + \frac{1}{2} \rho v_2^2 + \rho g h_2 $$

Hukum Tatanan Mutlaknya murni ganjil dan sering "Melawan Nalar Awam":
***"Disaat gerak pacu fluida melesat lari kecepatan ekstrem tak wajar mendidih putar ($v$ besar), TEKANAN STATIS NGOTOT MENINDAS ALAM DIAM dinding tangki fluida tersebut malahan akan KOSONG AMBLAS MERUSUT MENJUNAM HANCUR TURUN drastis ($P$ Mengecil drastis)!"***
- Itulah alasan angin topan di atas genteng (Angin lari hyper $v$ gede) meruntuhkan tekanan aspal hisap hampa udara murni menyedot teriak pelanting Atap Rumah Genteng mendarat mental copot menjulang tersedut loncat terseret melayang ke langit hisap membuang tekanan hampa belaka.

---

## 7. Aplikasi Bernoulli I (Tangki Bocor & Venturimeter)

### 7.1 Tangki Bocor Memanah (Teorema Torricelli)
Tangki air dilubangi mendadak tertebas setajam silet dari kejauhan kedalaman melengkung bocor menyemprot dari atap lurus permukaannya (sejauh elevasi lubang dari plafon $h$). Letusan muncratan pacuannya persis serupa benda gerak batu dilempar terhempas jatuh kendor bebas absolut Gerak Parabola Murni Kinematika!
- **Laju Pancaran Bocor Tembak ($v$):** $v = \sqrt{2 \cdot g \cdot h}$
- **Jangkauan Lontaran Dataran Jatuh Tembak Terjauh Murni ($X_{\text{mendatar}}$):** 
  $X = 2 \sqrt{h \cdot h_{\text{lubang\_ke\_tanah}} }$

### 7.2 Tabung Venturimeter (Pengukur Debit Laju PIPA Utama Pabrik)
Pipa leher gembung disambung sengaja corong ciut sempit menyiksa ($A_2$). Pipa ini ditusuk sengaja dicolok jarum manometer raksa pemantau ganda (atau celah bening tekanan U) untuk mengintip perselisihan hancur anjloknya tekanan akibat air dijerat lari memecut maut lewat masuk pipa picing.
Rumus Dasar Laju Air Memasuki Perangkap Venturi (Tanpa Cairan Rawa Tambahan):
$$ v_1 = \sqrt{\frac{2 \cdot g \cdot h}{\left(\frac{A_1}{A_2}\right)^2 - 1}} $$
*(Di mana $h$ adalah belahan beda elevasi selisih meniskus tinggi dua air di menara kaca pembantu lurus tembak)*.

---

## 8. Aplikasi Bernoulli II (Tabung Pitot & Aerodinamika Sayap)

### 8.1 Tabung Pitot Jarum Pengukur Jet Supersonik
Ditempel di bibir moncong jet tempur, jarum bolong berujung buntung huruf L mencegat tabrakan hantam sengit aliran udara keras murni dari angkasa luar, menyumbat rem mendadak mematikan laju udara mati seketika diam menabrak ($v = 0$ di ujung lubang stagnasi titik hisap). Tekanan hancur membanting beda mencelik ke layar meteran pilot membongkar kecepatan murni lari siluman jet menembus langit:
$$ v_{\text{pesawat}} = \sqrt{\frac{2 \cdot \rho_{\text{Cairan\_Manometer Timbangan}} \cdot g \cdot h}{\rho_{\text{udara luar terbang}}}} $$

### 8.2 Sayap Mengapung Raksasa Pesawat Aviasi Udara Terbang (Lift Force Aerodinamis)
Pesawat rongsok Boeing bertonase ribuan MegaTon mampu ngangkang murni terangkat melayang leluasa memelangi angkasa murni BUKAN karena dorongan pantatan roket ke bawah, namun karena pisau tebasan Sayap bengkoknya murni diukir cacat menggunung cembung di punggung atap (Airfoil) namun murni memapas merata rata lurus setara telapak sepatu di landasan lantai alas jantungan bawah balok sayap!
- Jarak udara membanting membelah lewat lari punggung ATAS sayap wajib menyusuri melengkung gundukan jauh lebih berputar panjeng panjang. Terpaksa, lari melesat Udara atas **Lebar Cepat Lebih Gila** ($v_{\text{atas}} > v_{\text{bawah}}$).
- Hukum Bernoulli meneriak: Jika gerak meriam $v_{\text{atas}}$ cepat lari, maka Tekanan atap Langit Sayap $P_{\text{atas}}$ Anjlok Hancur Hampa Kempos Kosong ($P_{\text{atas}} < P_{\text{bawah}}$) menyurut drastis.
- Perbedaan Tekanan bawah padat vs atas bolong mendongkrak **Angkat Menyedor Mutlak (Lift Force $F_{\text{angkat}}$):**
$$ F_{\text{angkat}} = (P_{\text{bawah}} - P_{\text{atas}}) \cdot A \implies F_{\text{angkat}} = \frac{1}{2} \rho_{\text{udara}} \cdot (v_{\text{atas}}^2 - v_{\text{bawah}}^2) \cdot A_{\text{sayap}} $$
Syarat lepas landas roda lari selamat (*Take Off*): Dorongan mutlak angkat maut menyedot ini wajib menang lebih gigih galak membanjir hancurkan tarikan mati total Massa beratan Pesawat baja ($F_{\text{angkat}} > W_{\text{pesawat}}$). 

---

## 9. Fluida Kental Realitas (Viskositas & Hukum Stokes)

Semesta fluida Bernoulli di atas hanya murni mengkaji Air Siluman "Malaikat Ideal" (tanpa ampas pergesekan, Encer sempurna mutlak nir lendir). 
Kenyataan asli realitas minyak Bumi, lumpur, oli rem kental lengket gila parah. Fluida menempel enggan berotasi punya gesekan rem (*Viskositas Kental / $\eta$*) mutlak.

**Hukum Sir George Stokes Gesek Tenggelam Berlumpur:**
Kelereng baja dijatuhkan lurus meluncur dalam drum raksasa tabung oli kental hitam lengket tidak akan pernah melaju akselerasi meledak ke bawah sejadi gravitasi lliar awam membelah. Ia akan dijegal serbuk mengerem hisap hampa seret tarung dari segala dinding kulitnya (*Drag Fluid Force / $F_s$*):
$$ F_s = 6 \cdot \pi \cdot \eta \cdot r \cdot v $$
- $\eta$ : Kekentalan absolut cairan si monster ($Pa\cdot s$).
- $r$ : Jari-jari gahar bola padat tenggelam (m). 
- $v$ : Kecepatan tancap hancur terjunnya maut tersebut kelak.

**Velositas Tertinggi Final Maut Konstan Absolut (Terminal Velocity mutlak / $v_t$):**
Benda mati tersebut di suatu milidetik melaju di lumpur lambat laut, Gaya hantu gesek Stokes akan mengungguli membela hancur seri gaya gravitasi bongkah, menjadikannya jatuh bukan memecut gila pelesakan, namun jatuh luruh terayun malas pelan diam Kecepatan Konstan Absolut seratus persen stabil merapat selamanya hingga rebah menyentuh memukul maut lantai tanki bumi. 
$$ v_t = \frac{2 \cdot r^2 \cdot g (\rho_{\text{bola baja benda}} - \rho_{\text{oli fluida}})}{9 \cdot \eta} $$

---

## Lihat Juga
- [Dinamika Partikel](../kelas-10/03-dinamika.md)
- [Latihan Soal Bab 1 Fluida](latihan-soal/README.md)
