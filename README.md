# Uber Trip Clustering

## Project Overview

This project explores Uber trip patterns using unsupervised
machine learning techniques. The objective is to identify
temporal and geographical patterns in Uber trip data through
exploratory data analysis and clustering algorithms.

## Objectives

- Analyze Uber trip distributions across time and location.
- Perform data cleaning and feature engineering.
- Explore different clustering algorithms.
- Evaluate clustering performance using the Silhouette Score.
- Visualize clusters and trip patterns.

## Dataset

The dataset contains the following features:

| Feature | Description |
|---------|-------------|
| Date/Time | Trip date and time |
| Lat | Latitude |
| Lon | Longitude |
| Base | Uber base identifier |

Additional temporal features are extracted from the timestamp.

## Methodology

1. Exploratory Data Analysis (EDA)
2. Missing value analysis
3. Feature engineering
4. Duplicate removal
5. One-Hot Encoding
6. Outlier removal using IQR
7. Feature standardization using StandardScaler
8. Clustering and evaluation

## Clustering Algorithms

- K-Means
- DBSCAN
- Agglomerative Hierarchical Clustering
- Gaussian Mixture Model (GMM)
- Mean Shift

## Evaluation

The Silhouette Score is used to evaluate cluster quality.

The K-Means experiment evaluates cluster counts from 2 to 10,
with the highest recorded Silhouette Score occurring at k = 4.

Different feature subsets are used across experiments.
Therefore, the results should not be interpreted as a
controlled comparison of all algorithms.

## Technologies and Libraries

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Project Structure

```text
uber-trip-clustering/
├── data/
│   └── uber-data2.csv
├── notebooks/
│   └── uber-trips-clustering-final.ipynb
└── README.md
```

## Future Improvements

- Standardize feature selection across clustering algorithms.
- Improve hyperparameter optimization.
- Evaluate clustering stability.
- Improve geographical cluster visualizations.
- Develop an interactive visualization dashboard.
