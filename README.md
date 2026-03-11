[markmap.html](https://github.com/user-attachments/files/25892231/markmap.html)# LR-SLR
Repositori ini akan membahas bagaimana promt yang baik untuk melakukan LR/SLR dengan bantuan AI seperti chatgpt

<details>
<summary> Promt Chat GPT</summary>

## Tahap 1
"Dari file PDF artikel jurnal yang diberikan, bacalah dengan teliti dan pahami seluruh isinya. Setelah itu, konfirmasikan bahwa Anda telah membaca dan memahaminya sepenuhnya."

## Tahap 2
Dari file PDF artikel jurnal yang sama, susunlah sebuah review artikel yang mencakup: judul penelitian, lokasi penelitian, nama penulis, tahun terbit, insight utama, Fault yang disoroti, General concern, spesific concern, Solusi yang diusulkan, Kenapa topik ini penting, GAP yang disampaikan, steps, Set up Eksperimen yang dilakukan, teori yang digunakan, metode penelitian, hasil penelitian, keterbatasan penelitian, serta korelasi dengan penelitian yang akan dilakukan. 

Susun hasil review dari keseluruhan file dalam bentuk tabel yang tersusun ke samping yang bisa di copy ke excel. 

Sebagai informasi, Topik Penelitian saya yaitu: Fault Detection, Classification, and Fault-Tolerant Control Strategy for Dual Active Bridge Converter in Renewable Energy Microgrids.

## Tahap 3
Berdasarkan seluruh tinjauan penelitian terdahulu yang telah diberikan, susunlah uraian tinjauan pustaka dari masing-masing penelitian dengan ketentuan:

- Ditulis dalam Bahasa Indonesia
- Panjang minimal 300 kata
- Disusun dalam bentuk paragraf
- Terdiri dari minimal 8 kalimat per paragraf
- Menggunakan seluruh sitasi dan referensi yang telah saya berikan
- Tidak menambahkan sitasi atau referensi baru

## Tahap 4

Selanjutnya, dari keseluruhan tinjauan penelitian terdahulu tersebut, lakukan sintesis dan berikan pernyataan yang menegaskan state of the art, research gap, novelty, tingkat orisinalitas, serta korelasinya dengan penelitian yang akan dilakukan, dengan ketentuan:

- Ditulis dalam Bahasa Indonesia
- Panjang minimal 300 kata
- Disusun dalam bentuk paragraf
- Terdiri dari minimal 8 kalimat per paragraf
- Menggunakan seluruh sitasi dan referensi yang telah saya berikan
- Tidak menambahkan sitasi atau referensi baru

## Tahap 5: Gabungkan antara narasi dengan tabel review

Berdasarkan seluruh tinjauan terhadap penelitian-penelitian terdahulu yang telah disajikan, lakukan sintesis untuk merumuskan dan menjelaskan state of the art, research gap, novelty, serta orisinalitas penelitian, sekaligus menunjukkan keterkaitannya dengan penelitian yang sedang saya lakukan. Uraian tersebut harus disusun dalam bahasa Indonesia dengan panjang minimal 3000 kata. Penulisan harus berbentuk paragraf, di mana setiap paragraf terdiri atas minimal delapan kalimat. Dalam penyusunannya, gunakan seluruh sitasi dan referensi yang telah saya berikan sebelumnya, tanpa menambahkan sitasi maupun referensi baru di luar yang sudah tersedia.

## Tahap 6 Mapping dengan Markdown
Ubah uraian tersebut menjadi bagan poin-poin kerangka berpikir yang mencakup state of the art, research gap, novelty, orisinalitas, serta keterkaitannya dengan penelitian yang saya lakukan. Penyajian harus ditulis dalam format kode Markdown yang ringkas, jelas, dan sederhana, sehingga mudah dipahami dan dapat menggambarkan alur pemikiran penelitian secara sistematis.

[Link mapping](https://markmap.js.org/)
[Alternatif](https://www.napkin.ai/)

## Tahap 7: Buat Pertanyaan Penelitian (Research Quetion

Susunlah tiga pertanyaan penelitian (research question) yang relevan berdasarkan tinjauan literatur yang telah Anda buat sebelumnya. Pertanyaan penelitian tersebut harus memenuhi kaidah penyusunan research question dalam Systematic Literature Review (SLR). Dalam penyusunannya, hilangkan konteks lokus atau lokasi penelitian, dan arahkan fokus sepenuhnya pada analisis terhadap literatur yang ditinjau.

## Tahap 8: Menyusun Jawaban Pertanyaan

Berdasarkan research question yang telah ditetapkan, susunlah jawabannya dengan merujuk pada seluruh referensi yang telah diberikan. Uraian tersebut harus ditulis dalam bahasa Indonesia dengan panjang minimal 3000 kata. Penulisan disusun dalam bentuk paragraf, di mana setiap paragraf terdiri atas sekurang-kurangnya delapan kalimat. Dalam proses penulisan, gunakan seluruh sitasi dan referensi yang telah disediakan, serta tidak diperkenankan menambahkan sitasi atau referensi lain di luar yang telah diberikan.

</details>

<details>
<summary>
Tinjauan Penelitian Terdahulu
  
</summary>

# Tinjauan Penelitian Terdahulu

## 1. State of the Art (Posisi Ilmiah Terkini)
Perkembangan riset konverter Dual Active Bridge (DAB) saat ini berfokus pada peningkatan:
- **Keandalan sistem konversi daya DC**
- **Ketahanan operasi saat gangguan (fault-resilient operation)**
- **Kontinuitas suplai daya pada sistem energi modern**

### Pilar utama perkembangan riset:
1. **Fault Detection & Diagnosis**
   - Deteksi gangguan sangat cepat (mikrodetik–sub-siklus switching)
   - Ekstraksi fault signature berbasis:
     - Tegangan titik tengah jembatan
     - Arus fasa & komponen DC
     - Spektrum harmonik
   - Pendekatan:
     - Sensorless
     - Low-cost hardware
     - Finite State Machine (FSM)
     - Analisis domain waktu & frekuensi

2. **Fault-Tolerant Strategy**
   - Rekonfigurasi topologi tanpa redundansi mahal
   - Isolasi fasa/sakelar rusak
   - Transfer daya tetap berjalan saat fault
   - Multiple-fault tolerance
   - Fault ride-through (FRT)

3. **Stabilisasi Operasi Pascagangguan**
   - Eliminasi DC-bias arus transformator
   - Pencegahan saturasi inti magnetik
   - Kontrol transien cepat
   - Mitigasi osilasi frekuensi tinggi
   - Ekspansi rentang soft switching (ZVS)

4. **Proteksi Sistem Level Jaringan DC**
   - Integrasi proteksi konverter dan proteksi jaringan
   - Fault current limiter (FCL)
   - Protection zones
   - Deteksi gangguan berbasis fitur arus lokal

➡ **Kesimpulan State of the Art**  
Riset mutakhir telah maju dalam:
- Deteksi gangguan cepat  
- Toleransi gangguan berbasis topologi & kontrol  
- Stabilisasi operasi pascagangguan  
Namun masih berkembang secara parsial dan terpisah.

---

## 2. Research Gap (Kesenjangan Penelitian)

### Gap Konseptual
- Fault Detection, Classification, dan Fault-Tolerant Control
  ➜ Masih diteliti sebagai domain terpisah
  ➜ Belum terintegrasi dalam satu arsitektur kendali terpadu

### Gap Teknis
- Mayoritas studi fokus pada:
  - Single fault (terutama open-circuit)
  - Skala laboratorium kecil
- Minim kajian:
  - Integrasi real-time detection → classification → control
  - Multi-fault scenario
  - Respons otomatis berbasis jenis gangguan

### Gap Aplikasi
- Kurang spesifik pada:
  - Renewable energy microgrids
  - Sistem terisolasi
  - Variabilitas sumber energi terbarukan
  - Kontinuitas suplai daya kritis

### Gap Metodologis
- Klasifikasi gangguan berbasis multi-fitur sinyal masih terbatas
- Minim sistem fault management berbasis kecerdasan kendali terpadu

➡ **Inti Kesenjangan:**  
Belum ada kerangka sistem terpadu yang menyatukan:
> Fault Detection → Fault Classification → Fault-Tolerant Control  
secara real-time dalam konteks microgrid energi terbarukan.

---

## 3. Novelty (Kebaruan Penelitian)

Penelitian ini menawarkan pendekatan baru berupa:

### Integrasi Komprehensif
- Menggabungkan secara terpadu:
  1. Fault Detection cepat
  2. Fault Classification cerdas
  3. Fault-Tolerant Control adaptif

### Transisi Otomatis Berbasis Kendali
- Fault terdeteksi
  → Diklasifikasikan jenisnya
  → Sistem otomatis rekonfigurasi kontrol

### Pendekatan Real-Time System Intelligence
- Respons gangguan berbasis logika kendali terintegrasi
- Minim intervensi manual
- Minim waktu henti sistem

### Konteks Aplikasi Spesifik
- Difokuskan pada:
  - Renewable energy microgrids
  - Sistem distribusi DC terisolasi
  - Ketahanan energi berbasis konverter daya

➡ **Esensi Novelty:**  
Bukan hanya solusi parsial, tetapi arsitektur fault management terpadu.

---

## 4. Orisinalitas Penelitian

### Orisinal secara Konseptual
- Memposisikan DAB sebagai:
  > Intelligent fault-resilient power conversion unit  
  bukan sekadar konverter daya.

### Orisinal secara Sistemik
- Menghubungkan tiga domain:
  - Proteksi konverter daya
  - Klasifikasi gangguan cerdas
  - Kendali toleran gangguan

### Orisinal secara Konteks Energi
- Difokuskan pada:
  - Ketahanan energi wilayah terisolasi
  - Transisi energi terbarukan
  - Keandalan microgrid modern

### Orisinal secara Arsitektur Kendali
- Desain strategi:
  - Fault-aware control system
  - Self-reconfigurable converter operation

➡ **Inti Orisinalitas:**  
Kontribusi baru pada desain sistem konversi daya yang resilien dan adaptif.

---

## 5. Keterkaitan dengan Penelitian yang Dilakukan

### Judul Penelitian:
**Fault Detection, Classification, and Fault-Tolerant Control Strategy  
for Dual Active Bridge Converter in Renewable Energy Microgrids**

### Kesesuaian dengan State of the Art
✓ Sejalan dengan kebutuhan peningkatan keandalan DAB  
✓ Mendukung ketahanan sistem energi berbasis DC  
✓ Relevan dengan evolusi proteksi konverter modern

### Menjawab Research Gap
✓ Mengintegrasikan detection–classification–control  
✓ Mengembangkan sistem fault management terpadu  
✓ Fokus pada lingkungan microgrid energi terbarukan

### Memenuhi Novelty
✓ Arsitektur kendali terintegrasi real-time  
✓ Transisi otomatis berbasis jenis gangguan  
✓ Pendekatan sistem cerdas dan adaptif

### Menunjukkan Orisinalitas
✓ Kontribusi lintas-domain (power electronics + protection + control)  
✓ Relevansi tinggi untuk ketahanan energi masa depan  
✓ Pendekatan sistemik, bukan parsial

---

## 6. Alur Logis Kerangka Berpikir

State of the Art  
↓  
Masih parsial & terpisah  
↓  
Research Gap: belum ada sistem terpadu  
↓  
Penelitian ini mengintegrasikan detection–classification–control  
↓  
Novelty: arsitektur fault management komprehensif  
↓  
Orisinalitas: sistem konverter daya resilien & adaptif  
↓  
Kontribusi nyata untuk renewable energy microgrids

  
</details>
