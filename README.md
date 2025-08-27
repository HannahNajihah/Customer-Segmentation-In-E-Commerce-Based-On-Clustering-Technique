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