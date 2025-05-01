# Kelompok_5_Tugas03_Classification

# Klasifikasi Penyakit Jantung (Heart Disease Classification)

## Pendahuluan
Proyek ini bertujuan untuk mengklasifikasikan ada tidaknya penyakit jantung pada pasien berdasarkan berbagai atribut medis dan demografis. Dengan menggunakan empat algoritma supervised learning (Logistic Regression, K-Nearest Neighbors, Naïve Bayes, dan Decision Tree), kami mengembangkan dan membandingkan model klasifikasi untuk memprediksi penyakit jantung secara akurat.

## Informasi Proyek
- **Mata Kuliah:** Machine Learning
- **Dosen Pengampu:** Alim Misbullah, S.Si., M.S.
- **Kelompok:** 5
- **Anggota Kelompok:**
  - Mila Lestari (2208107010002)
  - Zahra Zafira (2208107010040)
  - Pryta Rosela (2208107010046)
  - Cut Sula Fhatia Rahma (2208107010048)
  - Widya Nurul Sukma (2208107010054)

## Dataset
Dataset Klasifikasi Penyakit Jantung berisi informasi medis dan demografis pasien yang digunakan untuk memprediksi keberadaan penyakit jantung.

**Dataset:** [Heart Failure Prediction Dataset]https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

**Fitur:**
- **Informasi Demografis:** 
  - Age (Usia)
  - Sex (Jenis Kelamin)
- **Pengukuran Medis:** 
  - RestingBP (Tekanan Darah Istirahat)
  - Cholesterol (Kolesterol)
  - FastingBS (Gula Darah Puasa)
  - MaxHR (Detak Jantung Maksimum)
  - Oldpeak (Depresi ST)
- **Observasi Klinis:** 
  - ChestPainType (Jenis Nyeri Dada)
  - RestingECG (EKG Istirahat)
  - ExerciseAngina (Angina Akibat Olahraga)
  - ST_Slope (Kemiringan Segmen ST)

**Variabel Target:**
- HeartDisease (0 = Tidak, 1 = Ya)

## Metodologi

### Pemahaman dan Eksplorasi Data
1. **Analisis Statistik Deskriptif:** Ringkasan statistik untuk fitur numerik dan kategorikal
2. **Visualisasi Data:** Distribusi variabel, hubungan antar fitur, dan korelasi dengan target
3. **Analisis Korelasi:** Identifikasi hubungan antara fitur dan target klasifikasi

### Pra-pemrosesan Data
1. **Penanganan Missing Values:** Pemeriksaan dan penanganan nilai yang hilang
2. **Encoding Variabel Kategorikal:** Transformasi variabel kategori menjadi numerik
3. **Standarisasi/Normalisasi:** Penskalaan fitur numerik
4. **Train-Test Split:** Pembagian data untuk pelatihan dan evaluasi model

### Implementasi Model
1. **Logistic Regression:** Model dasar untuk klasifikasi biner
2. **K-Nearest Neighbors (KNN):** Algoritma berbasis jarak untuk klasifikasi
3. **Naïve Bayes:** Metode probabilistik berdasarkan teorema Bayes
4. **Decision Tree:** Model berbasis aturan untuk klasifikasi

### Evaluasi Model
- **Confusion Matrix:** Visualisasi prediksi benar dan salah
- **Metrik Klasifikasi:** Akurasi, Presisi, Recall, F1-Score
- **Kurva ROC dan AUC:** Evaluasi performa diskriminatif model
- **Loss Value:** Analisis fungsi kerugian model

## Cara Penggunaan

### Prasyarat
- Python 3.8+
- Library yang diperlukan: numpy, pandas, matplotlib, seaborn, scikit-learn

### Instalasi
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Eksekusi
1. Clone repositori
   ```bash
   git clone https://github.com/WidyaNurulSukma/Kelompok_5_Tugas03_Classification.git
   ```
2. Navigasi ke direktori proyek
   ```bash
   cd Kelompok_5_Tugas03_Classification
   ```
3. Jalankan notebook Jupyter
   ```bash
   jupyter notebook Heart_Disease_Classification.ipynb
   ```

## Visualisasi
Proyek ini mencakup berbagai visualisasi:
- Distribusi fitur dan target
- Heatmap korelasi antar variabel
- Boxplot dan barplot untuk analisis fitur berdasarkan target
- Confusion matrix untuk setiap model
- Kurva ROC untuk perbandingan performa model
- Visualisasi tree untuk model Decision Tree
- Grafik perbandingan metrik evaluasi antar model

## Hasil Analisis
- Perbandingan performa keempat algoritma (Logistic Regression, KNN, Naïve Bayes, Decision Tree) dalam klasifikasi penyakit jantung
- Identifikasi fitur-fitur paling signifikan dalam prediksi penyakit jantung
- Evaluasi kelebihan dan kekurangan masing-masing model
- Analisis trade-off antara interpretabilitas dan akurasi model

## Kesimpulan
Melalui proyek ini, kami telah mengimplementasikan dan membandingkan empat algoritma klasifikasi untuk prediksi penyakit jantung. Hasil analisis menunjukkan perbedaan performa antar model, dengan masing-masing algoritma memiliki kelebihan dan keterbatasannya sendiri.

Model terbaik berdasarkan metrik evaluasi adalah [nama model], yang menunjukkan akurasi tertinggi dalam memprediksi penyakit jantung. Faktor-faktor seperti [fitur-fitur penting] ditemukan sebagai prediktor paling signifikan untuk penyakit jantung.

Implementasi model klasifikasi ini memiliki potensi aplikasi dalam sistem pendukung keputusan klinis untuk membantu diagnosis awal penyakit jantung berdasarkan faktor risiko dan indikator klinis.

## Link Video Presentasi
[Link akan ditambahkan setelah presentasi]
