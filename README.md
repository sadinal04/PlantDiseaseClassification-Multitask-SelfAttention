# 🌿 Multi-Task Deep Learning for Plant & Leaf Disease Classification

## 📌 Deskripsi Project

Project ini bertujuan untuk membangun model **Deep Learning berbasis Convolutional Neural Network (CNN)** dengan pendekatan **multi-task learning** yang mampu mengidentifikasi jenis tanaman dan mendeteksi penyakit pada daun hanya dari satu gambar input. Model ini juga mengintegrasikan **self-attention mechanism** untuk meningkatkan performa dalam memahami fitur penting pada citra.

---

## 🎯 Tujuan

* Mengembangkan model klasifikasi multi-task dalam satu arsitektur
* Meningkatkan efisiensi dibandingkan model single-task
* Membantu deteksi penyakit tanaman secara otomatis dan cepat

---

## 🧠 Metodologi

* Arsitektur utama: CNN (Convolutional Neural Network)
* Pendekatan: Multi-Task Learning
* Feature enhancement: Self-Attention
* Input: Gambar daun tanaman
* Output:

  * Kelas tanaman
  * Kelas penyakit daun

---

## 📊 Dataset

Dataset yang digunakan berisi berbagai jenis tanaman dengan kondisi daun sehat maupun berpenyakit.

Dataset pada penelitian ini berasal dari dua sumber dataset publik:

* **Plants Disease Dataset** oleh Rahma dan Silvia (2024) dari Mendeley Data:
  https://data.mendeley.com/datasets/b6cj8k8x3g/2

* **Rice Leaf Disease Dataset** dari Kaggle:
  https://www.kaggle.com/datasets/dedeikhsandwisaputra/rice-leafs-disease-dataset

### 📁 Detail Dataset

**1. Cabai (*Capsicum spp.*) — 3 Kelas**

* Bacterial leaf spot: 465
* Yellow leaf curl virus: 465
* Healthy: 465

**2. Jagung (*Zea mays*) — 4 Kelas**

* Cercospora leaf spot gray: 711
* Common rust: 711
* Northern leaf blight: 711
* Healthy: 711

**3. Kentang (*Solanum tuberosum*) — 3 Kelas**

* Early blight: 1582
* Late blight: 1582
* Healthy: 1582

**4. Padi (*Oryza sativa*) — 4 Kelas**

* Bacterial Leaf Blight: 438
* Brown Spot: 438
* Healthy: 438
* Leaf Blast: 438

**5. Tomat (*Solanum lycopersicum*) — 8 Kelas**

* Bacterial spot: 745
* Early blight: 745
* Late blight: 745
* Leaf mold: 745
* Mosaic virus: 745
* Yellow leaf curl virus: 745
* Septoria spot: 745
* Healthy: 745

Total dataset yang digunakan dalam penelitian ini adalah **14.801 citra daun**, dengan pembagian:

* Data training: **72%**
* Data validasi: **18%**
* Data testing: **10%**

Pembagian dilakukan menggunakan metode **stratified sampling** untuk menjaga distribusi data tetap seimbang.


### 📌 Total Dataset

**16,697 gambar**

---

## ⚙️ Teknologi yang Digunakan

* Python
* TensorFlow / PyTorch
* NumPy & Pandas
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 🚀 Cara Menjalankan Project

1. Clone repository:

```bash
git clone https://github.com/sadinal04/PlantDiseaseClassification-Multitask-SelfAttention.git
```

2. Masuk ke folder project:

```bash
cd project-name
```

3. Jalankan notebook:

```bash
jupyter notebook
```

---

## 📈 Hasil

Model menunjukkan performa yang sangat baik dalam melakukan klasifikasi secara simultan:

* Akurasi klasifikasi tanaman–penyakit: **98,31%** (1.456 prediksi benar dari 1.481 data uji)
* Akurasi klasifikasi jenis tanaman: **99,53%**
* Akurasi klasifikasi penyakit daun: **98,72%**

---

## ⚡ Performa & Efisiensi

Model tidak hanya akurat, tetapi juga ringan dan efisien:

* Jumlah parameter: **136.291**
* Ukuran model: **1,64 MB**
* Waktu inferensi: **57,92 ms per citra** (~17 citra/detik)

---

## 📌 Keunggulan Project

* Multi-task dalam satu model
* Lebih efisien secara komputasi
* Menggunakan self-attention untuk meningkatkan performa

---

## 🔮 Pengembangan Selanjutnya

* Deploy ke web atau mobile app
* Menambah dataset yang lebih besar dan beragam

---

## 👤 Author

**Sadinal Mufti**
Data Science | Machine Learning | AI Enthusiast
