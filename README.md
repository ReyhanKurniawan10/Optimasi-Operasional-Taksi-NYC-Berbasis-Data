# Capstone-2
# Optimasi Operasional Taksi NYC Berbasis Data

## Ringkasan Proyek

**Judul:**  
**Optimasi Operasional Taksi NYC Berbasis Data**

**Tujuan:**  
Proyek ini bertujuan untuk mengeksplorasi bagaimana efisiensi dan pendapatan operasional dapat ditingkatkan pada sistem taksi di bawah New York City Taxi and Limousine Commission (NYC TLC), tanpa menambah jumlah armada. Analisis dilakukan dengan menggunakan data perjalanan aktual guna mengidentifikasi waktu, lokasi, dan jenis trip yang paling menguntungkan, serta tren musiman yang dapat dimanfaatkan.

**Lingkup Pekerjaan:**
- Menganalisis data Green Taxi NYC untuk periode Januari 2023
- Menentukan waktu dan lokasi dengan pendapatan tertinggi dan terendah
- Mengevaluasi efisiensi trip sangat pendek (< 1 mil)
- Mengidentifikasi lokasi dengan biaya tambahan tertinggi
- Menganalisis pola musiman terhadap volume perjalanan dan pendapatan

**Teknologi & Alat yang Digunakan:**
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- Microsoft Excel & PowerPoint (untuk pelaporan dan presentasi)
- GitHub (untuk kontrol versi dan publikasi proyek)

---

## Ringkasan Temuan

### Waktu & Lokasi dengan Pendapatan Tertinggi
- Jam dengan pendapatan tertinggi adalah **pukul 16.00 (4 sore)**, sesuai dengan jam sibuk pulang kerja.
- **PULocationID 74** tercatat sebagai lokasi dengan total pendapatan tertinggi.
- Hari kerja (terutama Selasa–Jumat) memiliki volume trip dan pendapatan jauh lebih tinggi dibanding akhir pekan.

### Efisiensi Trip Sangat Pendek
- **17% dari total trip** adalah perjalanan dengan jarak < 1 mil.
- Namun, trip pendek menunjukkan **pendapatan per mil ($14,31)** dan **pendapatan per menit ($2,08)** yang lebih tinggi daripada trip normal.
- Menunjukkan potensi strategi layanan ekspres atau tarif khusus untuk trip jarak pendek.

### Lokasi dengan Biaya Tambahan Tinggi
- **PULocationID 23** memiliki rata-rata surcharge tertinggi yaitu **$17,10 per trip**, umumnya disebabkan oleh tol dan kemacetan.
- Lokasi ini perlu dievaluasi untuk efisiensi biaya atau disesuaikan kebijakan tarifnya.

### Tren Musiman dan Harian
- Trip dan pendapatan harian **meningkat tajam pada hari kerja**, dan menurun saat akhir pekan.
- Tren ini mendukung strategi penjadwalan armada, shift pengemudi, dan promosi musiman berbasis waktu.

---

## Struktur Repositori

├── data
│   ├── clean
│   │   └── NYCTLCTripRecordClean.csv
│   └── raw
│       └── NYC TLC Trip Record.csv
├── notebooks
│   └── Capstone 2.ipynb
├── slide
│   └── Capstone 2 - Reyhan Kurniawan [NYC TLC].pdf
└── README.md
