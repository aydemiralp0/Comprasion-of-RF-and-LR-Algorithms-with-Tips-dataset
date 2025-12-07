##🎉 Tip Prediction Model — Machine Learning Project

Müşterinin restoran hesabına göre bahşiş miktarını tahmin eden ML projesi

#🚀 Proje Hakkında

Bu proje, restoran müşterilerinin bıraktığı bahşiş miktarını tahmin etmek için geliştirilmiş bir makine öğrenmesi modeli içerir.
Veri seti olarak link = https://www.kaggle.com/datasets/coderanand/tips-dataset

Amaç:

Total Bill
Sex
Smoker
Day
Time
Size

gibi değişkenlere göre tip (bahşiş) tahmini yapan bir regresyon modeli geliştirmek.

#🧠 Kullanılan Algoritmalar

Bu projede iki farklı regresyon modeli test edildi:

Linear Regression

Random Forest Regressor

Performans karşılaştırması yapıldı ve sonuçlar grafikle gösterildi.

#📊 Model Performans Karşılaştırması

Random Forest'ın daha yüksek R² skoru verdiği gözlemlendi.
Linear Regression daha başarılı oldu.
Örnek Fotoğrafı Kodun son satırıından görebilirsiniz


#🛠️ Kullanılan Teknolojiler

Python
Pandas
NumPy
Scikit-Learn
Matplotlib

#🔍 Data Cleaning & Feature Engineering

Veri seti üzerinde şu işlemler uygulanmıştır:
Eksik verilerin kontrolü
Duplicates kontrolü
Negatif değer ayıklaması
One-hot encoding (gender, smoker, vs.)
Histogram ve scatter plot analizleri

Correlation matrix
