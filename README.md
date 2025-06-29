
# Milk Quality Classification (Machine Learning Project)

**Project ini adalah tugas besar mata kuliah Sistem Cerdas yang berfokus pada pengembangan model machine learning untuk klasifikasi kualitas susu menggunakan data Milk Quality dari Kaggle.**


## 📂 Deskripsi Proyek

Industri susu memerlukan quality control yang ketat untuk menjaga kualitas produk. Pengujian manual memakan waktu & biaya.  
Pada proyek ini, kami membangun model machine learning yang dapat mengklasifikasikan kualitas susu berdasarkan parameter fisikokimia seperti pH, suhu, rasa, aroma, kandungan lemak, kekeruhan, dan warna.

**Tujuan utama:**
- Mengembangkan model klasifikasi kualitas susu yang akurat dan efisien
- Membandingkan performa beberapa algoritma ML
- Menangani masalah data imbalance
- Menentukan fitur terpenting untuk prediksi kualitas susu

## 🗂️ Dataset

Dataset yang digunakan:  
**Milk Quality Data Set**  
File dataset sudah disediakan di repo ini (`milknew.csv`).

## 🛠️ Library yang Digunakan

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- imbalanced-learn

## Metode yang Digunakan
Beberapa metode dan teknik machine learning yang digunakan dalam proyek ini:

Decision Tree Classifier
Digunakan untuk klasifikasi dan analisis feature importance.

K-Nearest Neighbors (KNN)
Untuk membandingkan performa model berbasis tetangga terdekat.

Naive Bayes (GaussianNB)
Untuk klasifikasi berbasis probabilitas.

Stratified K-Fold Cross Validation
Digunakan untuk validasi model dengan membagi data menjadi beberapa fold yang proporsional terhadap kelas.

SMOTE (Synthetic Minority Oversampling Technique)
Untuk menangani masalah data imbalance (jumlah data pada kelas target yang tidak seimbang).

Feature Selection (SelectFromModel)
Untuk memilih fitur/variabel paling penting dalam menentukan kualitas susu.




