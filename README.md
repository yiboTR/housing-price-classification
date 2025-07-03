# 🏡 Housing Price Classification with Scikit-learn

Bu proje, Kaliforniya'daki konut fiyatlarını "Ucuz" (0) ve "Pahalı" (1) olarak sınıflandırmak için **Lojistik Regresyon** modeli kullanır. Sınıflandırma eşiği: **$200,000**  
Veri kümesi `scikit-learn`'ün `fetch_california_housing()` fonksiyonu ile alınmıştır.

---

## 📌 Proje Hedefi

Evlerin çeşitli özelliklerine bakarak (örneğin: gelir, oda sayısı, konum), evin **pahalı mı ucuz mu** olduğunu tahmin etmek.

---

## 📁 Proje Yapısı

housing-price-classification/
├── data/
│ └── housing.csv
├── notebook/
│ └── AmesHousing_Classification.ipynb
├── README.md
└── requirements.txt

---

## ⚙️ Kullanılan Teknolojiler

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn (LogisticRegression)

---

## 🧪 Kullanılan Özellikler

- `median_income`, `housing_median_age`, `total_rooms`, `total_bedrooms`, vs.
- `ocean_proximity`: rastgele atanmış konumsal kategori (one-hot encoding uygulandı)
- Hedef değişken: `is_expensive` (1: Pahalı, 0: Ucuz)

---

## 🧠 Modelleme Süreci

1. Verinin yüklenmesi ve işlenmesi
2. One-hot encoding ile kategorik verinin dönüştürülmesi
3. Verinin normalize edilmesi (`StandardScaler`)
4. Model eğitimi: `LogisticRegression`
5. Değerlendirme: Accuracy, Confusion Matrix, Classification Report

---

## 📊 Model Performansı (Örnek)

- ✅ Accuracy: **%83.75**
- 🧾 Confusion Matrix:
[[2087 290]
[ 381 1370]]
- 🧠 Classification Report:
- Precision (1): 0.83
- Recall (1): 0.78
- F1-score (1): 0.80

---

## 🚀 Nasıl Çalıştırılır?

1. `housing.csv` dosyasını `data/` klasörüne koyun  
2. `notebook/AmesHousing_Classification.ipynb` dosyasını Google Colab ya da Jupyter Notebook ile açın  
3. Tüm hücreleri sırayla çalıştırın

---

## 📚 Öğrenilenler

- Lojistik regresyon ile sınıflandırma modeli kurma
- Gerçek dünya verisine uygun hedef belirleme ve etiketleme
- Kategorik verileri sayısal hale getirme (one-hot encoding)
- Model başarı metriklerini yorumlama (Precision, Recall, F1)

---

## 👤 Yazar

- **Yiğitcan Yıldız**  
- [🔗 LinkedIn](https://www.linkedin.com/in/yibotr/) • [🐙 GitHub](https://github.com/yiboTR)
