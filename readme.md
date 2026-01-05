# REDO FINAL PROJECT SEMESTER GASAL 2025/2026
**DEPARTEMEN STATISTIKA** | **FAKULTAS SAINS DAN ANALITIKA DATA** | **INSTITUT TEKNOLOGI SEPULUH NOPEMBER**

**Program Studi**: S1-Sains Data

**Mata Kuliah**: Teknik Sampling dan Data Wrangling A (SD234304)

**Dosen Pengampu**:
1. Dr. Dra. Agnes Tuti Rumiati, M.Sc.
2. Neni Alya Firdausanti, S.Si., M. Stat., Ph.D.
3. Husna Mir'atin Nuroini, S.Stat., M.Stat.

**Penganalisis**: Dewa Putra Yuda (5052241012)

= : >< : = : >< : =

## Analisis Dataset Airbnb Singapura (2025-2026)

### Temuan Utama:

#### 1. Geografi Nilai (Geography of Value)
Analisis spasial menyatakan bahwa lokasi premium di pusat kota (CBD) tidak selalu memberikan nilai terbaik bagi tamu. Munculnya klaster "Hidden Values" di wilayah seperti Geylang dan Kallang menunjukkan harga tetap di bawah rata-rata, namun tingkat hunian dan popularitas (ulasan) mencapai titik tertinggi secara nasional.

#### 2. Event Dunia Sebagai Penggerak
Pasar akomodasi Singapura sangat sensitif terhadap agenda global. Hasil analisis Scarcity menunjukkan bahwa periode F1 Singapore GP 2025 dan Imlek 2026 memicu lonjakan harga non-linear. Hal ini disebabkan oleh penipisan suplai unit tersedia secara drastis, memaksa harga pasar meroket karena hanya unit kategori premium yang tersisa.

#### 3. Faktor Lingkungan mendominasi Faktor Sosial
Data menggagalkan asumsi bahwa "murah pasti laku". Visualisasi Strategic Map kami menunjukkan penumpukan listing di kuadran "Rebuilding/New" (Harga Rendah & Sepi Ulasan) yang terjebak dalam kompetisi harga tanpa jejak. Kesuksesan di Singapura terkonsentrasi pada dua kutub yaitu efisiensi ekstrem (Hidden Values) atau reputasi elit (Premium Gems).

### Library dan Bahasa:
*Final Project* ini dikerjakan menggunakan **Python** dengan library & package berikut:
- Pandas (untuk manipulasi, data wrangling, & agregasi),
- NumPy (untuk komputasi numerik & kalkulasi indeks),
- GeoPandas (untuk pemrosesan data spasial/peta Singapura),
- Matplotlib & Seaborn (untuk visualisasi tren temporal & peta distribusi), dan
- Scikit-Learn (untuk normalisasi fitur/MinMax Scaling).

## Cara Menjalankan/*Run* *Project*
1. **Clone repository ini:**
```bash
git clone https://github.com/gacoanphilia/redo-fp.git
```
2. **Install dependencies**  
Pastikan **Python** sudah terinstall! Kemudian jalankan kode di bawah ini:
```bash
pip install -r requirements.txt
```
3. **Buka Notebook**  
Jalankan/*run* file `.ipynb` untuk melihat proses analisis:
```bash
jupyter notebook final-project.ipynb
```

## Struktur Direktori
```
final-project/  
│  
├── data/  
|   ├── raw/
|   └── processed/
├── notebooks/  
|   └── final-project.ipynb  # Notebook analisis utama  
├── requirements.txt     # Daftar package Python yang digunakan  
└── README.md            # File yang menjelaskan final project
```
  
*Laporan ini disusun sebagai pemenuhan remedial mata kuliah Teknik Sampling dan Data Wrangling (A).*