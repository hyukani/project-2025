# 🧠 Uncovering Hidden Patterns in Health Insurance Claims

This project explores how health insurance claim data can reveal potential fraud and inefficiencies by uncovering hidden patterns using data science techniques. By applying **Clustering** and **Association Rule Mining (Apriori)**, we identified distinct patient groups and frequent clinical relationships that help support fairer and more efficient decision-making in claims management.

### 🎯 Objectives

- Detect anomalies in insurance claim patterns using a data-driven approach  
- Improve efficiency in claim processing  
- Support fair and informed decision-making using analytical insights

### 🧪 Methodology

1. **Data Collection** – Health claim data from CMS.gov  
2. **Preprocessing** – Data cleaning and transformation  
3. **EDA (Exploratory Data Analysis)** – Identifying trends and distributions  
4. **Clustering** – Segmenting patients based on diagnosis and cost  
5. **ARM (Apriori Algorithm)** – Finding clinical association patterns  
6. **Interpretation** – Extracting key insights from results  

### 📊 Clustering Results

| Cluster | Age Range | Avg. Cost | Common Diagnoses |
|--------:|------------|----------:|------------------|
| 0 | 30–39 years | 72 USD | Heart failure, diabetes, arthritis, osteoporosis |
| 1 | 6–58 years | 86 USD | Alzheimer’s, diabetes, depression, heart disease |
| 2 | 48 years | 116 USD | Multiple chronic illnesses: heart, kidney, lung, Alzheimer’s, etc. |

### 🔍 Top 3 Clinical Association Patterns (ARM)

1. **Diabetes → Heart Failure**  
   Patients with diabetes are **2x more likely** to experience heart failure.  
   *(Confidence: 68%, Lift: 2.15)*

2. **Arthritis → Osteoporosis**  
   Younger patients with arthritis tend to also have osteoporosis.  
   *(Confidence: 61%, Lift: 1.75)*

3. **Alzheimer’s + Depression → Heart Disease**  
   Alzheimer’s combined with depression often correlates with heart disease.  
   *(Confidence: 70%, Lift: 2.32)*

### 🧾 Top Medical Service Codes

The five most frequent procedure codes in claim data were:

- **99213** – Medium-level outpatient visit (256 claims)  
- **99214** – Complex outpatient visit  
- **36415** – Venipuncture (blood draw)  
- **85025** – Complete blood count (CBC)  
- **99232** – Subsequent hospital inpatient visit  

These indicate frequent follow-ups, lab diagnostics, and chronic care routines in claim records.

### 🧠 Conclusion

This project uncovered three major patient clusters with distinct diagnostic and cost patterns. It revealed strong associations between chronic diseases such as diabetes, Alzheimer’s, and heart conditions. The results provide valuable insights for insurers to detect potential fraud, improve claim efficiency, and make better data-driven decisions.

# ==========================================================================================================================#

# 🧠 Menyingkap Pola Tersembunyi dalam Klaim Asuransi Kesehatan

Proyek ini bertujuan mengungkap pola tersembunyi dalam data klaim asuransi kesehatan untuk mengidentifikasi potensi kecurangan dan meningkatkan efisiensi. Dengan menggunakan teknik **Clustering** dan **Association Rule Mining (Apriori)**, kami mengelompokkan pasien berdasarkan kemiripan karakteristik dan menemukan hubungan klinis yang sering muncul dalam data.

### 🎯 Tujuan

- Mendeteksi anomali pada pola klaim asuransi secara data-driven  
- Meningkatkan efisiensi pengelolaan klaim  
- Mendukung pengambilan keputusan yang adil dan berbasis data

### 🧪 Metodologi

1. **Pengumpulan Data** – Menggunakan data klaim dari CMS.gov  
2. **Preprocessing** – Membersihkan dan mentransformasi data  
3. **EDA (Eksplorasi Data)** – Mengamati distribusi dan tren  
4. **Clustering** – Mengelompokkan pasien berdasarkan diagnosis dan biaya  
5. **ARM (Algoritma Apriori)** – Menemukan pola asosiasi klinis  
6. **Interpretasi** – Mengambil insight dari hasil analisis  

### 📊 Hasil Clustering

| Cluster | Usia | Biaya Rata-Rata | Diagnosis Umum |
|--------:|------|----------------:|----------------|
| 0 | 30–39 tahun | 72 USD | Jantung lemah, diabetes, radang sendi, osteoporosis |
| 1 | 6–58 tahun | 86 USD | Alzheimer, diabetes, depresi, penyakit jantung |
| 2 | 48 tahun | 116 USD | Penyakit berat: jantung, ginjal, paru, Alzheimer, dll. |

### 🔍 3 Pola Asosiasi Klinis Utama (Hasil ARM)

1. **Diabetes → Gagal Jantung**  
   Pasien dengan diabetes memiliki **kemungkinan 2× lebih besar** mengalami gagal jantung.  
   *(Confidence: 68%, Lift: 2.15)*

2. **Radang Sendi → Osteoporosis**  
   Penderita muda dengan radang sendi juga cenderung mengalami osteoporosis.  
   *(Confidence: 61%, Lift: 1.75)*

3. **Alzheimer + Depresi → Penyakit Jantung**  
   Kombinasi Alzheimer dan depresi sering berkaitan dengan penyakit jantung.  
   *(Confidence: 70%, Lift: 2.32)*

### 🧾 Kode Layanan Medis Teratas

5 kode layanan medis yang paling sering muncul:

- **99213** – Kunjungan rawat jalan tingkat sedang (256 klaim)  
- **99214** – Kunjungan rawat jalan tingkat kompleks  
- **36415** – Pengambilan darah vena  
- **85025** – Pemeriksaan darah lengkap (CBC)  
- **99232** – Kunjungan lanjutan rawat inap  

Hal ini mencerminkan rutinitas kontrol, pemeriksaan laboratorium, dan perawatan penyakit kronis.

### 🧠 Kesimpulan

Proyek ini berhasil mengungkap tiga kelompok pasien dengan pola diagnosis dan biaya berbeda. Pola asosiasi menunjukkan keterkaitan kuat antara penyakit kronis seperti diabetes, Alzheimer, dan jantung. Temuan ini dapat dimanfaatkan perusahaan asuransi untuk mendeteksi anomali, meningkatkan efisiensi pengelolaan klaim, dan mendukung keputusan yang lebih objektif.

### 👥 Team

- **Maysahaya Artika M.** (23031554214)
- **AL Zahra Mayluna** (23031554075)  
- **Ayu Ghaniyatur R.** (23031554178)  
