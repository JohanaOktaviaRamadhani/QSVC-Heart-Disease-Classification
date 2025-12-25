# QSVC-Heart-Disease-Classification
## Deskripsi
Proyek ini bertujuan untuk mengembangkan model prediksi penyakit jantung menggunakan algoritma **Quantum Support Vector Classifier (QSVC)**, yang merupakan aplikasi dari **Quantum Machine Learning (QML)**. Dalam penelitian ini, model QSVC diimplementasikan untuk mengklasifikasikan data klinis pasien jantung, dengan menggunakan dataset yang berisi informasi mengenai faktor-faktor risiko seperti usia dan kadar kolesterol.

Model ini menggabungkan pendekatan komputasi kuantum dengan teknik pembelajaran mesin untuk meningkatkan akurasi dan stabilitas dalam klasifikasi medis, terutama di era perangkat kuantum **Noisy Intermediate-Scale Quantum (NISQ)**.

## Fitur
- Penggunaan **Quantum Support Vector Classifier (QSVC)** untuk klasifikasi penyakit jantung.
- Penerapan **ZZFeatureMap** untuk pemetaan data ke ruang fitur kuantum.
- Pembelajaran dengan dataset yang mencakup 6 fitur klinis.
- Evaluasi menggunakan metrik klasifikasi standar seperti **accuracy**, **balanced accuracy**, dan **F1-score**.
- Kemampuan untuk menangani dataset medis dengan dimensi fitur terbatas.

## Dataset
Dataset yang digunakan dalam proyek ini berisi 500 sampel dengan 6 fitur klinis dan variabel target yang menunjukkan status penyakit jantung (positif/negatif). Dataset ini diambil dari platform **Kaggle** dan dapat digunakan untuk tujuan penelitian dan pembelajaran.

## Instalasi
### Persyaratan
- Python 3.x
- `qiskit`
- `scikit-learn`
- `numpy`
- `matplotlib`

### Instalasi via pip
1. Clone repository ini:
   ```bash
   git clone https://github.com/username/Quantum-Heart-Disease-Prediction.git
   cd Quantum-Heart-Disease-Prediction
