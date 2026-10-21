<div align="center">

![Project Banner](assets/banner.png)

# Fraud Detection Clustering

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

<p>Unsupervised customer transaction segmentation using K-Means clustering and PCA visualization.</p>

</div>

---

## Overview

This repository provides an unsupervised machine learning study on customer financial transactions. It uses K-Means clustering to discover natural behavioral groupings without relying on predefined labels, and applies Principal Component Analysis (PCA) to map high-dimensional transactions into interpretable visual spaces.

Downstream supervised models trained on these cluster partitions are documented in [fraud-detection-classification](../fraud-detection-classification).

---

## Clustering Results

The optimal number of clusters was evaluated using the Elbow Method and Silhouette Analysis:

| Metric | Result |
| :--- | :--- |
| Optimal Cluster Count (k) | 2 |
| Silhouette Score | 0.572 |
| Dimensionality Reduction | PCA (2 components) |

<div align="center">

### Cluster Visualization (PCA)
![Cluster Visualization](assets/cluster-visualization.png)

### Silhouette Score Analysis
![Silhouette Score](assets/silhouette-score.png)

</div>

---

## Exploratory Data Analysis

Key exploratory patterns observed during feature analysis:

<div align="center">

### Feature Correlation Heatmap
![Correlation Matrix](assets/correlation-matrix.png)

### Feature Distributions
![Feature Distributions](assets/feature-distributions.png)

### Transaction Distribution by Customer Occupation
![Transaction Boxplot](assets/transaction-boxplot.png)

</div>

---

## Related Repositories

- **fraud-detection-clustering** (this repository): Unsupervised customer segmentation via K-Means.
- [fraud-detection-classification](../fraud-detection-classification): Supervised classification using Decision Tree and Random Forest on cluster labels.

---

## License

MIT: [LICENSE](LICENSE)
