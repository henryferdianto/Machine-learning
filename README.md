# Machine Learning - Image Classification (Rock Paper Scissors)

> **TL;DR** — Proyek klasifikasi gambar menggunakan TensorFlow/Keras untuk mengenali tangan manusia saat bermain Batu-Gunting-Kertas.

---

## 🔬 Project Overview

Proyek ini bertujuan untuk membangun model *deep learning* yang dapat mengklasifikasikan gambar tangan manusia ke dalam tiga kategori: **Batu**, **Gunting**, atau **Kertas**.

Dataset yang digunakan berisi ribuan gambar tangan dengan berbagai latar belakang yang telah dipisahkan menjadi data training dan data validasi.

## 🛠️ Tech Stack

- **Python** (Bahasa Pemrograman)
- **TensorFlow & Keras** (Deep Learning Framework)
- **Matplotlib** (Visualisasi hasil training)
- **Google Colab** (Environment pengerjaan)

## 📊 Hasil & Metodologi

1.  **Data Augmentation**: Menggunakan `ImageDataGenerator` untuk meningkatkan variasi data.
2.  **Model Architecture**: Menggunakan Convolutional Neural Network (CNN) dengan beberapa layer `Conv2D`, `MaxPooling2D`, dan `Dropout` untuk mencegah overfitting.
3.  **Training**: Model dilatih hingga mencapai akurasi tertentu menggunakan callback.

## 🚀 Cara Menjalankan

1.  Buka file `rockpaperscissor.ipynb` di [Google Colab](https://colab.research.google.com/).
2.  Pastikan runtime menggunakan GPU untuk proses training yang lebih cepat.
3.  Jalankan semua cell secara berurutan.

---

## 📜 License

Project ini dilisensikan di bawah [MIT License](LICENSE).
