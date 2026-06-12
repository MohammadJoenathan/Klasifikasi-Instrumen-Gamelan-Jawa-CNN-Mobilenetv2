# 📄 Klasifikasi Instrumen Gamelan Jawa Berdasarkan Bentuk Fisik Menggunakan Convolutional Neural Network (CNN) dengan Transfer Learning MobileNetV2

> 📚 Proyek Computer Vision yang menerapkan metode **Convolutional Neural Network (CNN)** dengan **Transfer Learning MobileNetV2** untuk mengklasifikasikan berbagai instrumen Gamelan Jawa berdasarkan bentuk fisiknya. Model dilatih menggunakan dataset citra instrumen gamelan dan dievaluasi menggunakan **Accuracy, Precision, Recall, F1-Score**, serta **Confusion Matrix**.

---

## 🎯 Tujuan Proyek

* 🎵 Mengembangkan sistem klasifikasi instrumen Gamelan Jawa berbasis citra.
* 🤖 Menerapkan metode CNN dengan Transfer Learning MobileNetV2.
* 🖼️ Mengidentifikasi jenis instrumen gamelan berdasarkan bentuk fisiknya.
* 📊 Mengevaluasi performa model menggunakan berbagai metrik evaluasi.

---

## 🧠 Metode yang Digunakan

### 📌 Metode

* Convolutional Neural Network (CNN)

### 🔍 Pendekatan

* Image Classification

### ⚙️ Arsitektur

* MobileNetV2

### 🚀 Teknik

* Transfer Learning (Pretrained ImageNet)

### 📈 Evaluasi

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 📂 Dataset

Dataset yang digunakan berasal dari:

🎼 **Gamelan Dataset – Roboflow Universe**

### 📋 Kelas Dataset

* Bonang
* Gambang
* Gender
* Gong
* Kempul
* Kendhang
* Kenong
* Rebab
* Saron
* Suling

### 📋 Format Data

* 🖼️ JPG / PNG
* 🇮🇩 Instrumen Gamelan Jawa
* 🎵 Kategori: Alat Musik Tradisional

---

## 🔄 Alur Penelitian

1. 📥 Pengumpulan dataset instrumen Gamelan Jawa.
2. 🧹 Preprocessing citra (resize dan normalisasi).
3. 🔄 Data augmentation untuk meningkatkan variasi data.
4. 🧠 Penerapan Transfer Learning MobileNetV2.
5. 🚀 Training model CNN.
6. 📊 Evaluasi menggunakan Accuracy, Precision, Recall, F1-Score, dan Confusion Matrix.
7. 📈 Analisis hasil klasifikasi.

---

## 🛠️ Library yang Digunakan

| Library                | Fungsi                           |
| ---------------------- | -------------------------------- |
| 🐍 Python              | Bahasa pemrograman utama         |
| ☁️ Google Colab        | Lingkungan pengembangan          |
| 🧠 TensorFlow          | Framework Deep Learning          |
| ⚙️ Keras               | Implementasi CNN dan MobileNetV2 |
| 🔢 NumPy               | Operasi numerik                  |
| 📊 Matplotlib          | Visualisasi grafik               |
| 📈 Seaborn             | Visualisasi Confusion Matrix     |
| 🤖 Scikit-Learn        | Evaluasi model                   |
| 🖼️ ImageDataGenerator | Data Augmentation                |

---

## 🚀 Cara Menjalankan Program

### 1️⃣ Persiapan

* Download dataset Gamelan dari Roboflow Universe.
* Upload dataset ke Google Drive.
* Buka notebook Google Colab.
* Install seluruh library yang dibutuhkan.

### 2️⃣ Eksekusi

Jalankan setiap sel secara berurutan.

### 3️⃣ Output Program

Program akan melakukan:

* 📥 Membaca dataset citra
* 🧹 Preprocessing dan normalisasi data
* 🔄 Data augmentation
* 🧠 Training MobileNetV2
* 📊 Evaluasi model
* 📈 Menampilkan grafik Accuracy dan Loss
* 📋 Classification Report
* 📉 Confusion Matrix

---

## 📊 Hasil Evaluasi

✅ Model CNN dengan Transfer Learning MobileNetV2 berhasil mengklasifikasikan instrumen Gamelan Jawa dengan performa yang sangat baik.

### Hasil Pengujian

* 📌 Accuracy : 95%
* 📌 Precision : 96%
* 📌 Recall : 95%
* 📌 F1-Score : 95%

Evaluasi dilakukan menggunakan:

* 📊 Classification Report
* 📉 Confusion Matrix
* 📈 Accuracy dan Loss Curve

---

## 📚 Topik yang Dipelajari

* 👁️ Computer Vision
* 🧠 Deep Learning
* 🤖 Convolutional Neural Network (CNN)
* 🚀 Transfer Learning
* 📱 MobileNetV2
* 🖼️ Image Classification
* 📊 Evaluasi Model Machine Learning

---

## 👨‍💻 Author

**Mohammad Joenathan Tito Ardiasnyah Prayitno**
🎓 NIM: 2218060
🏫 S1 Teknik Informatika
📍 Institut Teknologi Nasional Malang

---
