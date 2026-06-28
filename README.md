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
| **Semester** | 4 (2025/2026 Genap) |
| **Kelas** | IF401 |
| **Dosen** | Syahid Abdullah, S.Si, M.Kom |

---

## 📋 Identitas Mahasiswa

| Item | Keterangan |
|------|-----------|
| **Nama Lengkap** | Junior Dany Wibisono |
| **NIM** | 250401020098 |
| **Kelas** | IF401 |
| **Program Studi** | PJJ Informatika |

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
├── Pertemuan6_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 6
├── Pertemuan7_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 7
└── Pertemuan9_JuniorDanyWibisono_250401020098.ipynb    # Notebook Pertemuan 9
```

---

## 📝 Daftar Pertemuan

| No. | Topik | Notebook |
|-----|-------|----------|
| **Pertemuan 1** | Pengenalan Data Science | [📓 Buka Notebook](./Pertemuan1_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 2** | Struktur Data Python, NumPy & Pandas | [📓 Buka Notebook](./Pertemuan2_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 3** | Data Cleaning: Missing Values, Outlier & Ekstraksi Data | [📓 Buka Notebook](./Pertemuan3_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 4** | Statistika Dasar & Analisis Data | [📓 Buka Notebook](./Pertemuan4_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 5** | Visualisasi Data | [📓 Buka Notebook](./Pertemuan5_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 6** | Persiapan Data (Encoding, Scaling, Train-Test Split) | [📓 Buka Notebook](./Pertemuan6_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 7** | Pengantar Machine Learning: Regresi Linear | [📓 Buka Notebook](./Pertemuan7_JuniorDanyWibisono_250401020098.ipynb) |
| **Pertemuan 9** | Algoritma Klasifikasi (Bagian 1): Logistic Regression & Decision Tree | [📓 Buka Notebook](./Pertemuan9_JuniorDanyWibisono_250401020098.ipynb) |

### Detail Setiap Pertemuan

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
  - Feature scaling: **MinMaxScaler** (rentang [0, 1]), **StandardScaler** (mean=0, std=1), **RobustScaler** (berbasis median & IQR)
  - **`train_test_split()`** dari scikit-learn dengan parameter `stratify`
  - Pencegahan **data leakage**: split dulu → `fit_transform` di train → `transform` di test
  - Hands-on: pipeline preprocessing end-to-end dataset **Titanic**

- [x] **Pertemuan 7** — Pengantar Machine Learning: Regresi Linear
  - Lanskap ML: **Supervised vs Unsupervised**, **Classification vs Regression**
  - Konsep **Regresi Linear**: persamaan `ŷ = β₀ + β₁x`, interpretasi intercept & slope
  - **Cost function (MSE)** & **Gradient Descent** — scikit-learn pakai **OLS**
  - Implementasi `LinearRegression` scikit-learn: Instantiate → Fit → Predict → Evaluate
  - Metrik evaluasi: **MAE**, **MSE/RMSE**, **R²**
  - Hands-on: pipeline prediksi gaji end-to-end. Hasil: **R² ≈ 0.97**

- [x] **Pertemuan 9** — Algoritma Klasifikasi (Bagian 1): Logistic Regression & Decision Tree
  - Konsep **klasifikasi** sebagai Supervised Learning untuk memprediksi kategori diskret: **Binary vs Multiclass Classification**
  - **Logistic Regression**: fungsi **Sigmoid** σ(z), decision boundary, & pengaruh **threshold** terhadap trade-off Precision–Recall (`predict_proba`)
  - **Decision Tree**: aturan if-else bertingkat, kemurnian split via **Gini Impurity** & Entropy, trade-off **underfitting vs overfitting** (`max_depth`), serta interpretasi `feature_importances_`
  - Metrik evaluasi klasifikasi: **Confusion Matrix** (TP/TN/FP/FN), **Accuracy**, **Precision**, **Recall**, & **F1-Score** — beserta kapan memprioritaskan masing-masing
  - Hands-on: melatih & membandingkan 2 model pada dataset medis **Breast Cancer Wisconsin** (569 sampel, 30 fitur). Hasil: **Logistic Regression Akurasi ≈ 0.982**, mendeteksi **41 dari 42** kasus kanker (Recall malignant 0.976) — unggul atas Decision Tree (Akurasi 0.939)

---

## 🛠️ Tools yang Digunakan

- **Python 3** — bahasa pemrograman utama
- **NumPy** — komputasi numerik & array multidimensi
- **Pandas** — manipulasi dan analisis data tabular
- **Matplotlib** — visualisasi data dasar & dashboard statis
- **Seaborn** — visualisasi data statistik (histplot, boxplot, violin, pairplot)
- **SciPy** — uji statistik (Pearson, Spearman, skewness test)
- **scikit-learn** — preprocessing (encoder, scaler), `train_test_split`, model `LinearRegression`, `LogisticRegression`, `DecisionTreeClassifier`, & metrik evaluasi (regresi & klasifikasi)
- **Requests** — akses REST API
- **Google Colab** — environment notebook berbasis cloud
- **Jupyter Notebook** — format `.ipynb` untuk dokumentasi interaktif
- **GitHub** — version control & portofolio

---

## 🔗 Cara Menjalankan Notebook

1. Klik file `.ipynb` di tabel daftar pertemuan di atas
2. Klik tombol **"Open in Colab"** (atau buka manual via [Google Colab](https://colab.research.google.com))
3. Jalankan setiap sel dengan menekan `Shift + Enter` atau klik **Runtime → Run all**

---

## 📌 Kesimpulan Umum Perjalanan Belajar Data Science (Pertemuan 1–7)

Tujuh pertemuan ini membentuk fondasi yang solid untuk berkarir sebagai Data Scientist. Perjalanan dimulai dari memahami **ekosistem Python** (Pertemuan 1–2), berlanjut ke keterampilan inti berupa **pembersihan data** dan **analisis statistik** (Pertemuan 3–4), kemudian **komunikasi data melalui visualisasi** (Pertemuan 5), hingga akhirnya membangun **pipeline Machine Learning pertama** secara end-to-end (Pertemuan 6–7).

Temuan terpenting dari rangkaian ini adalah bahwa **kualitas data jauh lebih menentukan daripada kecanggihan algoritma** — prinsip *Garbage In, Garbage Out* yang terbukti di setiap tahap. Saya juga memahami bahwa alur kerja yang benar (split → fit di train → transform di test) sangat kritis untuk mencegah *data leakage* yang membuat evaluasi model menjadi tidak valid.

Sebagian dari rencana belajar tersebut kini telah terwujud di **Pertemuan 9**: saya mulai mempelajari **algoritma klasifikasi** dengan **Logistic Regression** dan **Decision Tree** pada dataset medis **Breast Cancer Wisconsin**. Pelajaran kunci dari hands-on ini adalah bahwa **pemilihan metrik harus mengikuti konteks masalah** — untuk diagnosis kanker, **Recall** (jangan sampai melewatkan kasus ganas) jauh lebih kritis daripada Accuracy semata, sehingga Logistic Regression yang mendeteksi 41 dari 42 kasus kanker menjadi pilihan yang lebih aman dibandingkan Decision Tree.

Langkah selanjutnya yang ingin saya pelajari: algoritma klasifikasi lanjutan (**SVM**, **Naive Bayes**, serta metode *ensemble* seperti Random Forest), validasi silang (*cross-validation*), dan penanganan *class imbalance* untuk kasus data dunia nyata yang lebih kompleks.

---

## 📬 Kontak

- **GitHub:** [@juniordw](https://github.com/juniordw)
- **Email:** juniordany09@gmail.com

---

_Repositori ini dibuat sebagai bagian dari aktivitas belajar Data Science, Program Studi PJJ Informatika, Kelas IF401, Universitas UNSIA — Semester Genap 2025/2026._
