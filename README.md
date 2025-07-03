# 🐱🐶 CNN - Cat vs Dog Image Classification

Sebuah proyek deep learning berbasis Convolutional Neural Network (CNN) untuk mengklasifikasikan gambar antara **kucing** dan **anjing**. Proyek ini ditulis menggunakan Python dan framework Keras dengan backend TensorFlow.

## 📌 Deskripsi

Tujuan dari proyek ini adalah membangun model klasifikasi gambar sederhana yang mampu membedakan apakah sebuah gambar berisi **kucing** atau **anjing**. Dataset yang digunakan merupakan subset dari dataset **Dogs vs. Cats** yang tersedia di Kaggle.

Model CNN dirancang untuk melakukan feature extraction dari gambar dan melakukan prediksi dua kelas: `Cat` atau `Dog`.

---

## 🛠 Teknologi yang Digunakan

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn
- Google Colab / Jupyter Notebook

---

## 📁 Struktur Direktori

CNN-Cat-Dog-Classification/
│
├── dataset/
│ ├── train/
│ │ ├── cat.0.jpg
│ │ ├── dog.1.jpg
│ │ └── ...
│ └── test/
│ ├── 1000.jpg
│ └── ...
│
├── model/
│ └── cat_dog_cnn_model.h5 # File model hasil training
│
├── cat_dog_classifier.ipynb # Notebook utama
├── requirements.txt # Library yang dibutuhkan
└── README.md # Dokumentasi proyek