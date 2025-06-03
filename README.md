# Analisis Sentimen Ulasan Aplikasi Vidio di Google Play Store

Proyek ini menganalisis sentimen pengguna terhadap aplikasi **Vidio** berdasarkan ulasan di Google Play Store. Tujuan dari proyek ini adalah mengklasifikasikan ulasan menjadi sentimen **positif** dan **negatif** menggunakan algoritma **Support Vector Machine (SVM)**, dengan perbandingan dua teknik seleksi fitur: **Chi-Square** dan **Information Gain**.

## 📌 Studi Kasus
Aplikasi Vidio merupakan platform streaming populer di Indonesia. Dengan banyaknya ulasan pengguna, analisis sentimen dapat membantu tim pengembang dalam memahami kebutuhan serta persepsi pengguna.

## 🛠️ Metodologi
- **Pra-pemrosesan teks**: lowercase, stopword removal, stemming
- **Seleksi fitur**: Chi-Square & Information Gain
- **Model klasifikasi**: SVM
- **Evaluasi model**: Akurasi, Confusion Matrix

## 📊 Hasil
Model dengan seleksi fitur Chi-Square memberikan performa lebih baik dibandingkan Information Gain (berdasarkan akurasi dan f1-score).

## 🧪 Tools & Library
- Python
- pandas, numpy
- scikit-learn
- Sastrawi (untuk stemming bahasa Indonesia)
- seaborn, matplotlib

## 🚀 Cara Menjalankan

1. Clone repositori:
```bash
git clone https://github.com/username/sentiment-analysis-vidio.git
cd sentiment-analysis-vidio
```

2. Install dependensi:
```bash
pip install -r requirements.txt
```

3. Jalankan notebook:
Buka file di folder `notebooks/SA_Vidio_app.ipynb` menggunakan Jupyter Notebook atau Google Colab.

## ✍️ Author
Nama Kamu – [LinkedIn](https://www.linkedin.com/in/namakamu) | [GitHub](https://github.com/username)
