# Sentiment Analysis Vidio reviews from Google Play Store
This study aims to analyze the sentiment of user reviews on the **Vidio** application and compare the performance of the **Support Vector Machine** model, compare two feature selction techniques: **Chi-Square** and **Information Gain**. The classification is classifying into positive and negative categories.

## 📌 Study Case
The number of streaming application users continues to increase significantly, reflecting the growing role of streaming platforms in digital life. Vidio, a local streaming platform, dominates the Indonesian market and has outperformed foreign competitors. However, vidio still faces challenges in improving user satisfaction, as reflected by its relatively low rating. To remain competitive, it is necessary to enhance the application based on user experience, which can be explored through sentiment analysis.

## 🛠️ Methode
- **Text preprocessing**: case folding, punctuation removal, normalization, tokenization, stemming, stopword removal
- **Feature selection**: Chi-Square & Information Gain
- **Classifier**: SVM
- **Model evaluation**: Blanced accuracy

## 📊 Results
The model using Chi-Square feature selection achieved the best performance with a balanced accuracy of 93,63% outperforming Information Gain. The results show that most user reviews are classified as negative sentiment, suggesting user feedback related to specific aspects of the application. Complaints from Vidio app users include subscription packages that remain inactive despite payment, and difficulties in accessing certain premium content, which in some cases cannot be opened even though users have subscribed according to their selected package.

## 🧪 Tools & Library
- Python
- pandas, numpy
- scikit-learn
- Sastrawi (untuk stemming bahasa Indonesia)
- seaborn, matplotlib

## 🚀 Cara Menjalankan

1. Clone repository:
```bash
git clone https://github.com/username/sentiment-analysis-vidio.git
cd sentiment-analysis-vidio
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Jalankan notebook:
Buka file di folder `notebooks/SA_Vidio_app.ipynb` menggunakan Jupyter Notebook atau Google Colab.

## ✍️ Author
Nama Kamu – [LinkedIn](https://www.linkedin.com/in/namakamu) | [GitHub](https://github.com/username)
