# 🚢 Titanic Survival Analysis

Titanic yolcu verisi üzerinde keşifsel veri analizi (EDA) 
ve makine öğrenimi ile hayatta kalma tahmini.

## 📊 Proje Özeti

| Metrik | Değer |
|--------|-------|
| Model | Logistic Regression |
| Test Accuracy | %82.7 |
| Test F1-Score (weighted) | 0.82 |
| Veri Seti | 891 yolcu, 12 özellik |

## 🔍 Temel Bulgular

- Cinsiyet en güçlü hayatta kalma göstergesi:
  kadınların %74'ü, erkeklerin yalnızca %19'u hayatta kaldı
- 3\. sınıf kadın yolcular (%50), 1\. sınıf erkek yolculardan
  (%37) daha yüksek hayatta kalma oranına sahip
- 10 yaş altı çocuklarda hayatta kalma oranı %61 —
  genel ortalamanın (38%) çok üzerinde

## 📈 Görseller

### Hayatta Kalma Dağılımı
![survival](images/01_survival_distribution.png)

### Cinsiyet & Sınıf Etkisi
![sex_class](images/02_sex_class_survival.png)

### Korelasyon Haritası
![correlation](images/04_correlation_heatmap.png)

### Confusion Matrix
![confusion](images/05_confusion_matrix.png)

### Feature Importance
![features](images/06_feature_importance.png)

## 🛠️ Kullanılan Teknolojiler

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.0-green)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-1.3-orange)

## 🚀 Çalıştırmak İçin
```bash
git clone https://github.com/KULLANICI_ADIN/titanic-survival-analysis
cd titanic-survival-analysis
pip install -r requirements.txt
jupyter notebook notebooks/titanic_analysis.ipynb
```

## 📁 Proje Yapısı
```
├── data/               # Ham veri
├── notebooks/          # Jupyter notebook
├── images/             # Görselleştirmeler
├── requirements.txt    # Bağımlılıklar
└── README.md
```