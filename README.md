# Exploratory Data Analysis (EDA): Dinamika Kualitas Udara Kolkata (2015-2024)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white)
![License](https://img.shields.io/badge/License-CC0_1.0-lightgrey?style=for-the-badge)


## Ringkasan Proyek
Repositori ini berisi laporan komprehensif Proyek 1 mata kuliah **Statistika dan Probabilitas (ET234101)**. Analisis ini mengeksplorasi tren temporal, karakteristik statistik deskriptif, distribusi probabilitas, serta anomali polusi udara di kota Kolkata selama 10 tahun (2015–2024) menggunakan Python di dalam Jupyter Notebook.

**Mata Kuliah:** Statistika dan Probabilitas (ET234101)  
**Proyek:** Proyek 1 - Analisis Eksplorasi Data Kualitas Udara  

## Identitas Kelompok 06
1. **Deka Panji Kinarayana** - 5027261024
2. **Keisha Alvanna Delinda** - 5027261063
3. **Radya Hermawan Putra** - 5027261115

## Topik
**Smart City** (Kualitas Udara / *Air Quality*)

## Sumber Dataset
* **Nama Dataset:** Synthetic Kolkata Air-Quality Time-Series
* **Tautan (Link):** [Hugging Face - karan-0123/air-quality](https://huggingface.co/datasets/karan-0123/air-quality)
* **Lisensi:** Creative Commons CC0 1.0 Universal (`cc0-1.0`) — Domain Publik, bebas digunakan, disalin, dan didistribusikan.
* **Deskripsi Singkat:** Dataset ini mencakup 87.672 baris data pencatatan per jam dari tahun 2015 hingga 2024, berisi parameter polutan utama ($PM_{2.5}$, $PM_{10}$, $NO_2$, $CO$, $SO_2$, $O_3$) serta variabel cuaca pendukung.

## 3 Temuan Utama
1. **Distribusi Polusi Miring ke Kanan (Right-Skewed):** Sebagian besar waktu kualitas udara berada pada tingkat rendah (median $PM_{2.5} = 47,38\ \mu g/m^3$), namun terdapat lonjakan ekstrem berkala yang menarik nilai rata-rata keseluruhan menjadi lebih tinggi ($57,83\ \mu g/m^3$).
2. **Dampak Pandemi COVID-19:** Tren tahunan menunjukkan penurunan tingkat polusi yang drastis pada tahun 2020 akibat pembatasan aktivitas (*lockdown*), di mana batas bawah distribusi data menyentuh titik minimum absolut sensor ($15,0\ \mu g/m^3$).
3. **Korelasi Emisi Kendaraan ($NO_2$ dan $PM_{2.5}$):** Analisis sebaran menunjukkan adanya hubungan positif antara peningkatan kadar gas buang Nitrogen Dioksida ($NO_2$) dan konsentrasi partikulat halus ($PM_{2.5}$).

## Referensi
1. **Dataset:** Karan-0123. (2024). *Synthetic Kolkata Air-Quality Time-Series*. Hugging Face. Diakses dari [https://huggingface.co/datasets/karan-0123/air-quality](https://huggingface.co/datasets/karan-0123/air-quality)
2. **Buku Referensi:** Penerbit Mafy. (2025). *Statistika Probabilitas Modern dengan Python: Aplikasi di Dunia Informatika*. Diakses dari [https://penerbitmafy.com](https://penerbitmafy.com/wp-content/uploads/2025/11/STATISTIKA-PROBABILITAS-MODERN-DENGAN-PYTHON-APLIKASI-DI-DUNIA-INFORMATIKA.pdf)
3. **Panduan Analisis Data:** Dataquest. *Basic Statistics in Python & Probability*. Diakses dari [https://www.dataquest.io](https://www.dataquest.io/blog/basic-statistics-in-python-probability/)
4. **Panduan Pembelajaran & Materi Kuliah:** myITS Classroom. Institut Teknologi Sepuluh Nopember. Diakses dari [https://classroom.its.ac.id](https://classroom.its.ac.id)
5. **Panduan Teknis Penulisan & Sintaks:** TeachBooks. *Syntax Exercises*. Diakses dari [https://teachbooks.io](https://teachbooks.io/template/syntax_exercises/010.html)
6. **Panduan Format Penulisan:** IBM. *Markdown Jupyter Cheatsheet*. Diakses dari [https://www.ibm.com](https://www.ibm.com/docs/en/db2-event-store/2.0.0?topic=notebooks-markdown-jupyter-cheatsheet)

## Struktur Repositori
```text
proyek1-eda-kelompok-06/
│
├── data/
│   └── air_quality.csv          # Dataset mentah pencatatan polusi udara
├── eda_kelompok_06.ipynb        # Notebook utama kompilasi analisis lengkap
└── README.md                    # Dokumentasi proyek
```

## Cara Menjalankan Notebook


```bash
git clone https://github.com/nyx-org/proyek1-eda-kelompok-06.git
cd proyek1-eda-kelompok-06