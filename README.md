# Garment Worker Productivity — Classification & Clustering

Machine-learning analysis of the UCI *Productivity Prediction of Garment Employees* dataset. Actual productivity is binned into levels and predicted with several classifiers; the data is also explored with three clustering algorithms on PCA-reduced features.

## What's inside

- Data cleaning, outlier handling (z-score), label encoding and scaling
- Classification: Logistic Regression, Random Forest, SVC — accuracy, confusion matrix, classification report
- Clustering: K-Means, DBSCAN, Agglomerative Clustering, visualised in 2-D with PCA

## Dataset

[UCI Machine Learning Repository — Productivity Prediction of Garment Employees](https://archive.ics.uci.edu/dataset/597/productivity+prediction+of+garment+employees) (CC BY 4.0), included in `data/`.

## Run

```bash
pip install pandas numpy scikit-learn scipy matplotlib seaborn jupyter
jupyter notebook garment_productivity_analysis.ipynb
```

The notebook loads `garments_worker_productivity.csv`; run it from the `data/` folder or adjust the path. Comments are in Turkish.
