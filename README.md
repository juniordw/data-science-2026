# 📊 Data Science 2026

Repositori ini berisi tugas, latihan, dan proyek mata kuliah **Pengantar Data Science** — Program Studi PJJ Informatika.

---

## 👤 Perkenalan

Hai! Saya **Junior Dany Wibisono**, mahasiswa Program Studi **PJJ Informatika** angkatan **2025** dengan NIM **250401020098**.

Saya tertarik dengan **Artificial Intelligence (AI)** dan bercita-cita menjadi seorang **Data Scientist**. Melalui mata kuliah ini, saya berharap dapat membangun fondasi yang kuat dalam bidang Data Science — mulai dari pengolahan data, analisis statistik, hingga pemodelan machine learning.

---

## 📚 Mata Kuliah

| Item | Keterangan |
|------|-----------|
| **Nama Mata Kuliah** | Pengantar Data Science |
| **Kode** | 200302305 |
| **Bobot** | 3 SKS |
| **Semester** | 4 |
| **Dosen** | Syahid Abdullah, S.Si, M.Kom |

---

## 🗂️ Struktur Repositori

```
data-science-2026/
├── README.md                                           # File ini
├── Pertemuan1_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 1
├── Pertemuan2_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 2
├── Pertemuan3_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 3
├── Pertemuan4_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 4
├── Pertemuan5_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 5
└── Pertemuan6_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 6
```

---

## 📝 Daftar Pertemuan

- [x] **Pertemuan 1** — Pengenalan Data Science
  - Definisi Data Science & tiga pilar (Statistika, Ilmu Komputer, Domain Knowledge)
  - Kerangka CRISP-DM (6 fase siklus proyek data)
  - Ekosistem tools: Python, Google Colab, Jupyter Notebook, GitHub
  - Hands-on: menjalankan kode Python pertama di Colab

- [x] **Pertemuan 2** — Struktur Data Python, NumPy & Pandas
  - Struktur data Python: list, tuple, dictionary, set
  - NumPy ndarray: pembuatan, atribut, operasi vektorisasi, fungsi statistik
  - Pandas Series & DataFrame: load CSV, filtering, groupby & agregasi
  - Hands-on: eksplorasi dataset Titanic (Q1–Q6)

- [x] **Pertemuan 3** — Data Cleaning: Missing Values, Outlier & Ekstraksi Data
  - Taksonomi masalah kualitas data (missing, duplikat, inkonsistensi, outlier)
  - Deteksi & penanganan missing values: drop, imputasi median/modus, forward fill
  - Hapus duplikat & normalisasi string (`str.strip()`, `str.title()`, `str.lower()`)
  - Deteksi & penanganan outlier: IQR Fence + capping (`clip`)
  - Ekstraksi data dari REST API publik menggunakan `requests` (JSONPlaceholder)
  - Hands-on: pipeline cleaning dataset `housing_dirty.csv` → `housing_clean.csv`

- [x] **Pertemuan 4** — Statistika Dasar & Analisis Data
  - Statistika deskriptif: mean, median, modus, varians, std, kuartil, IQR, persentil
  - Distribusi data: normal, right-skewed, left-skewed, bimodal; skewness & kurtosis
  - Analisis univariat: histogram, KDE plot, boxplot, violin plot
  - Analisis bivariat: scatter plot, korelasi Pearson & Spearman, heatmap korelasi
  - Hands-on: eksplorasi statistik dataset Iris (6 langkah) dengan Matplotlib & Seaborn

- [x] **Pertemuan 5** — Visualisasi Data
  - 5 prinsip visualisasi efektif: Clarity, Accuracy, Efficiency, Aesthetics, Context
  - Memilih jenis grafik yang tepat: bar, line, histogram, boxplot, scatter, pair plot
  - Matplotlib: Figure & Axes, bar chart, line chart, scatter plot, kustomisasi
  - Seaborn: histplot + KDE, boxplot, violin plot, scatter plot, pair plot
  - Membaca grafik dengan kerangka **What? So what? Now what?**
  - Hands-on: dashboard visualisasi statis 4 panel dari dataset Tips (Matplotlib + Seaborn)

- [x] **Pertemuan 6** — Persiapan Data (Encoding, Scaling, Train-Test Split)
  - Filosofi *Garbage In, Garbage Out* & pipeline persiapan data yang benar
  - Encoding data kategorikal: **Label Encoding**, **One-Hot Encoding** (`drop_first=True` untuk hindari dummy variable trap), **Ordinal Encoding** (dengan urutan eksplisit)
  - Feature scaling: **MinMaxScaler** (rentang [0, 1]), **StandardScaler** (mean=0, std=1), **RobustScaler** (berbasis median & IQR) — beserta visualisasi perbandingannya
  - **`train_test_split()`** dari scikit-learn dengan parameter `stratify` untuk menjaga proporsi kelas pada dataset tidak seimbang
  - Pencegahan **data leakage**: split dulu → `fit_transform` di train → `transform` di test
  - Hands-on: pipeline preprocessing end-to-end dataset **Titanic** (load → impute median/modus → One-Hot Encoding → stratified split 80:20 → StandardScaler pada kolom numerik saja)

---

## 🛠️ Tools yang Digunakan

- **Python 3** — bahasa pemrograman utama
- **NumPy** — komputasi numerik & array multidimensi
- **Pandas** — manipulasi dan analisis data tabular
- **Matplotlib** — visualisasi data dasar & dashboard statis
- **Seaborn** — visualisasi data statistik (histplot, boxplot, violin, pairplot)
- **SciPy** — uji statistik (Pearson, Spearman, skewness test)
- **scikit-learn** — preprocessing (encoder, scaler) & utilitas ML (`train_test_split`)
- **Requests** — akses REST API
- **Google Colab** — environment notebook berbasis cloud
- **Jupyter Notebook** — format `.ipynb` untuk dokumentasi interaktif
- **GitHub** — version control & portofolio

---

## 🔗 Cara Menjalankan Notebook

1. Klik file `.ipynb` di atas
2. Klik tombol **"Open in Colab"** (atau buka manual via [Google Colab](https://colab.research.google.com))
3. Jalankan setiap sel dengan menekan `Shift + Enter` atau klik **Runtime → Run all**

---

## 📬 Kontak

- **GitHub:** [@juniordw](https://github.com/juniordw)
- **Email:** juniordany09@gmail.com

---

_Repositori ini dibuat sebagai bagian dari aktivitas belajar Data Science, Program Studi PJJ Informatika._
