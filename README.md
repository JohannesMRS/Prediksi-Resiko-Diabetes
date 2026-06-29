# 🩺 Diabetes Risk Prediction Project

[![Python Version](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/)
[![ML Framework](https://img.shields.io/badge/Framework-Scikit--Learn-orange)](https://scikit-learn.org/)

Repository ini berisi project Machine Learning yang bertujuan untuk memprediksi risiko penyakit diabetes pada pasien berdasarkan beberapa indikator medis/kesehatan. Project ini dibuat untuk membantu deteksi dini risiko diabetes menggunakan pendekatan berbasis data.

## Fitur
- Prediksi klasifikasi (Diabetes / Non-Diabetes).
- Preprocessing data otomatis (handling missing values & scaling).

## Dataset
Dataset yang digunakan dalam project ini adalah **[Nama Dataset, misal: Pima Indians Diabetes Dataset]** yang diperoleh dari [Kaggle/Sumber lain].

Fitur-fitur utama yang digunakan untuk prediksi meliputi:
- **Pregnancies**: Jumlah Kehamilan
- **Glucose**: Kadar glukosa plasma.
- **BloodPressure**: Tekanan darah diastolik.
- **BMI**: Body Mass Index.
- **Age**: Usia pasien.
- **SkinThickness**: Ketebalan lipatan kulit trisep
- **Insulin**: Tingkat insulin
- **DiabetesPedigreeFunction**: Riwayat penyakit keluarga

## Pemodelan & Performa
Setelah melalui tahap Eksplorasi Data (EDA) dan Preprocessing, model dilatih menggunakan algoritma:
- **Decision Tree**
- **Random Forest**
- **KNN (K-Nearest Neighbors)**
- **SVM (Support Vector Machine)**

Berikut adalah hasil performa model pada data pengujian (Test Set):

| Metrik | Decision Tree | Random Forest | KNN | SVM |
| :--- | :---: | :---: | :---: | :---: |
| **Accuracy** | 71.33% | 80.33% | 72.33% | 74.67% |
| **Precision** | 71.00% | 83% | 77% | 73% |
| **Recall** | 70.00% | 77% | 64% | 78% |
| **F1-Score** | 71.00% | 79% | 70% | 75% |

## Cara Menjalankan Project

### 1. Clone Repository
```bash
git clone [https://github.com/username-kamu/nama-repo.git](https://github.com/username-kamu/nama-repo.git)
cd nama-repo
