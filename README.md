# Sigorta Ödemesi Tahminlemesi

---
## Tanım
Bu proje AI Summer Camp'22 kapsamında geliştirdiğimiz ilk projedir. Bu projede [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance?datasetId=13720)'dan almış olduğumuz Kişisel Tıbbi Maliyet verilerini kullandık. Kişilerin sigorta ödemelerini tahmin etmek için yaş, cinsiyet, çocuk sayısı ve yaşadığı bölge gibi bilgileri kullanarak bir regresyon modeli kurduk.

## Model Geliştirmesi
* Veri hazırlama kısmında kategorik veriler için OneHotEncoder kullandık.
* Sayısal veriler için MinMaxScaler kullandık.
* Linear Regression, Random Forest, XGBoost, KNN ve LGBM modellerini kullandık ve sonuçlarını karşılaştırdık.
* İlk yaptığımız denemelerde XGBoost ile en iyi sonucu elde ettiğimizden dolayı XGBoost ile devam ettik.
* XGBoost ile GridSearchCV kullanarak en iyi sonucu elde etmeye çalıştık.

## Grup Üyeleri
- Yasin Tarakçı - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)
- Cansu Karahan - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)
- Gülnur Özgür - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)
- Hatice İkbal Göllüce - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)
- Kübra Küçükkartal - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)
- Ali Mert Kocaman - [GitHub](https://github.com/ysntrkc) | [LinkedIn](https://www.linkedin.com/in/yasintarakci)