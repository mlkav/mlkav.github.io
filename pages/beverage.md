![created](https://img.shields.io/badge/created-12/04/2025-blue)
[![Open Notebook](https://img.shields.io/badge/Open_Notebook_Clustering!-blue?logo=jupyter)](/beverage-sales/notebook-clust.html)
[![Open Notebook](https://img.shields.io/badge/Open_Notebook_Classification!-blue?logo=jupyter)](/beverage-sales/notebook-class.html)
<a href="https://www.linkedin.com/in/maulana-kavaldo/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin" alt="LinkedIn">
</a>
<a href="https://www.dicoding.com/users/mkavaldo/academies" target="_blank">
  <img src="https://img.shields.io/badge/Dicoding_Profile-blue?logo=browser" alt="Dicoding Profile">
</a>

---

# Beverage Sales (Clustering & Classification)

![beverage-sales](https://github.com/user-attachments/assets/0e94870a-e6d5-4ad8-80a0-8b6d9f985b7b)


Proyek ini bertujuan untuk menerapkan teknik *unsupervised learning* dan *supervised learning* dalam mengeksplorasi dan memprediksi pola dari suatu dataset. Dua pendekatan utama yang digunakan adalah **Clustering** (dengan PCA sebagai teknik reduksi dimensi) dan **Classification** menggunakan tiga model yang berbeda.


## Clustering

### Metode
- **Principal Component Analysis (PCA)** digunakan untuk mereduksi dimensi data, memvisualisasikan distribusi data, dan membantu proses clustering.
- **K-Means Clustering** digunakan untuk mengelompokkan data ke dalam beberapa grup berdasarkan kemiripan fitur.

### Langkah-langkah
1. **Preprocessing Data**: Normalisasi dan encoding data numerik dan kategorikal.
2. **Dimensionality Reduction**: Menggunakan PCA untuk mengurangi kompleksitas dan memudahkan visualisasi.
3. **Clustering**: Menerapkan K-Means dan menentukan jumlah cluster optimal dengan **Elbow Method** dan **Silhouette Score**.
4. **Interpretasi**: Analisis karakteristik dari masing-masing cluster setelah dilakukan *inverse transform* ke data asli.

---

## Classification

### Model yang Digunakan
- Random Forest Classifier
- Logistic Regression
- Gradient Boosting Classifier

### Langkah-langkah
1. **Preprocessing**: 
   - Encoding data kategorikal (One-Hot atau Label Encoding)
   - Normalisasi fitur numerik
   - Pembagian data menjadi training dan testing
2. **Training Model**: Melatih ketiga model klasifikasi di atas dengan data training.
3. **Evaluasi**:
   - Evaluasi dilakukan menggunakan metrik **Accuracy**, **Precision**, **Recall**, dan **F1-Score** pada data training dan testing.

### Hasil
Ketiga model klasifikasi menunjukkan performa yang sangat tinggi dengan hasil evaluasi sebagai berikut:

- **Accuracy**: 100%
- **Precision**: 100%
- **Recall**: 100%
- **F1-Score**: 100%

