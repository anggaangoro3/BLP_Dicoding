# 🤖 Proyek Akhir: Belajar Machine Learning untuk Pemula

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Scikit-Learn](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Pandas](https://img.shields.io/badge/Data%20Processing-Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)

> **Submission Akhir Dicoding**: Penerapan teknik *Supervised Learning* (Klasifikasi) dan *Unsupervised Learning* (Clustering) untuk analisis data.

---

## 📑 Daftar Isi

| Bagian | Deskripsi |
| :--- | :--- |
| [**📖 Overview**](#-overview) | Gambaran umum proyek. |
| [**📂 Struktur File**](#-struktur-file) | Penjelasan isi repositori. |
| [**🧠 Modul Klasifikasi**](#-modul-1-klasifikasi) | Analisis *Supervised Learning* (Random Forest/Decision Tree). |
| [**✨ Modul Clustering**](#-modul-2-clustering) | Analisis *Unsupervised Learning* (PCA & K-Means). |
| [**🛠️ Tech Stack**](#️-tech-stack) | *Library* yang digunakan. |

---

## 📖 Overview

Repositori ini berisi penyelesaian proyek akhir untuk kelas **Belajar Machine Learning untuk Pemula**. Proyek ini mendemonstrasikan kemampuan dalam memproses data tabular, membangun model prediksi, dan mengekstraksi pola tersembunyi dari data.

Proyek ini terbagi menjadi dua fokus utama:
1.  **Klasifikasi**: Membangun model untuk memprediksi kategori data menggunakan algoritma seperti *Decision Tree* dan *Random Forest*.
2.  **Clustering**: Mengelompokkan data ke dalam klaster-klaster berdasarkan kemiripan fitur menggunakan teknik reduksi dimensi (*PCA*) dan algoritma clustering.

---

## 📂 Struktur File

Berikut adalah organisasi file dalam repositori ini:

```text
blp_dicoding/
│
├── 📓 Notebooks
│   ├── [Klasifikasi]_Submission_Akhir_BMLP_Azmi_Reza_Anggoro.ipynb  # Notebook utama Klasifikasi
│   └── [Clustering]_Submission_Akhir_BMLP_Azmi_Reza_Anggoro.ipynb   # Notebook utama Clustering
│
├── 💾 Dataset
│   ├── data_clustering.csv          # Dataset utama (Raw)
│   └── data_clustering_inverse.csv  # Dataset hasil pre-processing/inverse transform
│
├── 🧠 Saved Models (.h5)
│   ├── decision_tree_model.h5                  # Model Decision Tree yang telah dilatih
│   ├── explore_RandomForest_classification.h5  # Model Random Forest (Eksplorasi)
│   ├── tuning_classification.h5                # Model hasil Hyperparameter Tuning
│   ├── model_clustering.h5                     # Model Clustering final
│   └── PCA_model_clustering.h5                 # Model PCA untuk reduksi dimensi
│
└── 📄 README.md
