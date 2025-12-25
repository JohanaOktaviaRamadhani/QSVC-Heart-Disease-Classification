# QSVC-Heart-Disease-Classification
## Deskripsi
Proyek ini bertujuan untuk mengembangkan model prediksi penyakit jantung menggunakan algoritma **Quantum Support Vector Classifier (QSVC)**. Pendekatan ini mengintegrasikan **Quantum Machine Learning (QML)** dengan data medis untuk meningkatkan akurasi prediksi penyakit jantung berdasarkan data klinis pasien.

## Fitur
- Menggunakan algoritma **Quantum Support Vector Classifier (QSVC)** untuk klasifikasi penyakit jantung.
- Penerapan **ZZFeatureMap** untuk memetakan data ke ruang fitur kuantum.
- Evaluasi menggunakan metrik seperti **accuracy**, **balanced accuracy**, dan **F1-score**.
- Fokus pada prediksi penyakit jantung menggunakan data klinis dengan dimensi fitur terbatas.

## Dataset
Dataset yang digunakan berisi 500 sampel dengan 6 fitur klinis, yang mencakup variabel target **HeartDisease** (1 untuk positif, 0 untuk negatif). Dataset ini tersedia secara terbuka di **Kaggle** dan digunakan untuk tujuan penelitian dan pembelajaran.

## Hasil Eksperimen
Model **QSVC** berhasil mencapai **akurasi 90%**, **balanced accuracy 89,17%**, dan **F1-score 89,49%**. Hasil eksperimen menunjukkan bahwa model ini memiliki performa yang sebanding dengan model **SVC klasik** dengan **Radial Basis Function (RBF) kernel**.

### Confusion Matrix:
- True Positive: 56
- True Negative: 34
- False Positive: 6
- False Negative: 4
