# Garment Worker Productivity — Classification & Clustering

## 🇹🇷 Türkçe

### Proje Hakkında
UCI *Productivity Prediction of Garment Employees* veri seti üzerinde yapılan bir makine öğrenmesi analizidir. Çalışanların gerçekleşen verimlilik değeri (`actual_productivity`) seviyelere ayrılmış ve bu seviyeler farklı sınıflandırma modelleriyle tahmin edilmiştir. Ayrıca veri, PCA ile iki boyuta indirgenerek üç farklı kümeleme algoritmasıyla incelenmiştir.

### Özellikler
- Veri temizleme, z-skoru ile aykırı değer kontrolü, kategorik değişkenlerin kodlanması ve ölçeklendirme
- `actual_productivity` değerinin `pd.cut` ile verimlilik seviyelerine ayrılması
- Sınıflandırma: Lojistik Regresyon, Random Forest ve SVM; doğruluk, karmaşıklık matrisi ve sınıflandırma raporu
- Kümeleme: K-Means, DBSCAN ve Agglomerative Clustering; PCA ile iki boyutlu görselleştirme

### Sonuçlar
| Model | Doğruluk |
| --- | --- |
| Random Forest | **0,78** |
| SVM | 0,65 |
| Lojistik Regresyon | 0,60 |

### Kullanılan Teknolojiler
Python, pandas, NumPy, SciPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

### Kurulum
```bash
git clone https://github.com/afranurbasak/garment-productivity-ml-analysis.git
cd garment-productivity-ml-analysis
pip install pandas numpy scipy scikit-learn matplotlib seaborn jupyter
```
Veri seti (`garments_worker_productivity.csv`) depoda bulunur. Kaynak: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees) (CC BY 4.0).

### Kullanım
```bash
jupyter notebook garment_productivity_analysis.ipynb
```
Not defterini baştan sona çalıştırın. Açıklamalar Türkçedir.

## 🇬🇧 English

### About the Project
A machine-learning analysis of the UCI *Productivity Prediction of Garment Employees* dataset. The employees' actual productivity value (`actual_productivity`) is divided into levels, and these levels are predicted with several classification models. The data is also reduced to two dimensions with PCA and explored with three clustering algorithms.

### Features
- Data cleaning, outlier checks with z-scores, categorical encoding and scaling
- Binning `actual_productivity` into productivity levels with `pd.cut`
- Classification: Logistic Regression, Random Forest and SVM, with accuracy, confusion matrix and classification report
- Clustering: K-Means, DBSCAN and Agglomerative Clustering, visualised in two dimensions with PCA

### Results
| Model | Accuracy |
| --- | --- |
| Random Forest | **0.78** |
| SVM | 0.65 |
| Logistic Regression | 0.60 |

### Technologies
Python, pandas, NumPy, SciPy, scikit-learn, Matplotlib, Seaborn, Jupyter Notebook

### Installation
```bash
git clone https://github.com/afranurbasak/garment-productivity-ml-analysis.git
cd garment-productivity-ml-analysis
pip install pandas numpy scipy scikit-learn matplotlib seaborn jupyter
```
The dataset (`garments_worker_productivity.csv`) is included. Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees) (CC BY 4.0).

### Usage
```bash
jupyter notebook garment_productivity_analysis.ipynb
```
Run the notebook from top to bottom. Explanations are in Turkish.
