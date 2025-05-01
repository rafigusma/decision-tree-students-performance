# 🌟 Klasifikasi Nilai Matematika Siswa dengan Decision Tree

Proyek ini bertujuan membangun model klasifikasi menggunakan algoritma **Decision Tree** untuk memprediksi apakah nilai matematika seorang siswa tergolong **tinggi** atau **rendah** berdasarkan atribut demografis dan akademik dari dataset *StudentsPerformance.csv*.

## 📂 Dataset

Dataset yang digunakan adalah `StudentsPerformance.csv`, yang berisi informasi berikut:
- Jenis kelamin
- Grup etnis
- Tingkat pendidikan orang tua
- Jenis makan siang
- Kursus persiapan ujian
- Nilai matematika, membaca, dan menulis

## ⚙️ Langkah-Langkah Analisis

1. **Import Dataset** – Membaca file CSV ke dalam DataFrame.
2. **Preprocessing** – Mengubah label menjadi numerik dan menambahkan label kategori untuk nilai matematika (tinggi/rendah).
3. **Visualisasi** – Menampilkan data dan distribusi menggunakan seaborn dan matplotlib.
4. **Modeling** – Membangun dan melatih model Decision Tree.
5. **Evaluasi** – Menilai akurasi model menggunakan confusion matrix dan classification report.

## 🛠 Tools & Library

- Python
- pandas
- matplotlib
- seaborn
- scikit-learn

## 🔍 Hasil

Model Decision Tree mampu memprediksi label dengan akurasi yang cukup baik, dan memberikan interpretasi visual melalui struktur pohon keputusan.

## 📁 Cara Menjalankan

1. Pastikan Anda memiliki file `StudentsPerformance.csv` di direktori kerja Anda.
2. Jalankan notebook `DecisionTree_StudentsPerformance.ipynb` menggunakan Jupyter Notebook atau Google Colab.
3. Ikuti setiap langkah yang telah ditulis di dalam notebook untuk melakukan preprocessing, pelatihan model, dan evaluasi.

## 📌 Catatan

- Proyek ini cocok sebagai studi kasus untuk pemula yang ingin memahami algoritma Decision Tree.
- Tidak memerlukan GPU untuk dijalankan.

