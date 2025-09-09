# 🧩 Customer Clustering Analysis (With & Without PCA)

This project focuses on customer segmentation in e-commerce by applying clustering techniques to behavioural data. The objective is to identify meaningful customer groups that can support personalisation, targeted marketing, and strategic decision-making. Both approaches — clustering on the original dataset and clustering after applying Principal Component Analysis (PCA) — are compared to assess differences in model interpretability, efficiency, and business insight.  

---

## 📌 Project Overview
- **Data Preprocessing**: Comprehensive cleaning pipeline including missing value handling, outlier treatment with Winsorization, and feature scaling to ensure robust input for clustering models.  
- **Clustering Without PCA**: Implemented MiniBatch KMeans and Agglomerative Clustering (Ward linkage) to group customers directly on the high-dimensional dataset, evaluated with Silhouette Score, Davies-Bouldin Index, and Calinski-Harabasz Index.
- **Clustering With PCA**:  Dimensionality reduction applied to retain 75% of variance, enabling improved visualisation, computational efficiency, and interpretability of clusters.
- **Model Evaluation**: Combination of the Elbow method and multiple evaluation metrics used to determine the optimal number of clusters, with a composite scoring framework for balanced assessment.  
- **Profiling & Interpretation**: Segments were profiled using PCA component loadings, distribution plots, and statistical summaries to provide actionable insights into customer behaviours and preferences.

---
## Key Results

- Dimensionality reduction: Reduced features by 47% (from 15 to 8 components) while preserving 78% of the variance.

- Clustering performance: Improved separation with 50% higher Calinski–Harabasz Index (1438 to 2159).

- Segmentation quality: Achieved a 187% improvement in composite clustering score (0.31 to 0.89).

## Business Implementation Strategy

The findings provide e-commerce businesses with a robust customer segmentation strategy that supports targeted marketing, personalised engagement, and improved customer retention. The best solution was a four-cluster model, each cluster highlights different customer behaviours with clear business actions:

Cluster 1: Moderate buyers with steady activity → build loyalty with bundles, cross-selling, and rewards.

Cluster 2: Low-value, inactive users → reactivation via win-back campaigns and promotions.

Cluster 3: High-value, digitally engaged customers → strengthen loyalty with exclusive offers and premium programmes.

Cluster 4: Frequent, high-value omnichannel buyers → prioritise with VIP benefits and advocacy initiatives.

---

## Run Notebook in Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KYGiFKGdZRg6OGXOKEtvIz-FYKGEIvZP)
