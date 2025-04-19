# 🌾 Clustering Analysis on the Seeds Dataset

This project explores a variety of clustering techniques applied to the Seeds dataset, focusing on how different preprocessing strategies impact performance. The algorithms evaluated include **K-Means**, **Hierarchical Clustering**, and **Mean Shift Clustering**, tested under various combinations of normalization, transformation, and dimensionality reduction using PCA.

## 🔗 Run on Google Colab

Easily view and run the notebook:  
[Open in Google Colab](https://colab.research.google.com/drive/10gAUFsZOWRoXkeMb8dZVphdxn9EEbFnJ?usp=sharing)

## 📊 Dataset Overview

- **Dataset**: Seeds Dataset  
- **Source**: UCI Machine Learning Repository  
- **Description**: Contains measurements of geometrical features of wheat kernels from three distinct varieties, ideal for unsupervised clustering tasks.

## 🤖 Clustering Algorithms Explored

- **K-Means Clustering**
- **Hierarchical Clustering**
- **Mean Shift Clustering**

## ⚙️ Preprocessing Strategies

The clustering algorithms were tested under the following preprocessing configurations:

1. **Raw Data (No Preprocessing)**
2. **Normalization Only**
3. **Transformation + Normalization (T+N)**
4. **Transformation + Normalization + PCA (T+N+PCA)**

---

## 🏆 Key Results

| Evaluation Metric           | Best Outcome                   |
|----------------------------|--------------------------------|
| **Top Performing Algorithm** | K-Means (with T+N+PCA)        |
| **Optimal Number of Clusters** | 3                           |
| **Highest Silhouette Score** | ~0.32 (K-Means with T+N+PCA)  |

K-Means demonstrated the most consistent and accurate performance across all preprocessing scenarios, especially when combined with transformation, normalization, and PCA.

---

## 📉 Visualizations

2D PCA projections were used to visualize clustering outcomes, helping illustrate the separation and structure of the data clusters under each method.

---

## 🧠 Conclusion

- **K-Means** clustering was the most effective and reliable method, particularly with full preprocessing (T+N+PCA).
- **Hierarchical Clustering** improved with normalization but remained less effective overall.
- **Mean Shift** worked reasonably well with raw data but incurred higher computational costs.
- **Three clusters** aligned perfectly with the true number of wheat seed types.
- **Silhouette scores** confirmed the best clustering configuration involved all three preprocessing steps with K-Means.

---

## 📄 Detailed Report

A comprehensive breakdown of results, metrics, and visualizations is available in the full report:  
[Download PDF Report](https://github.com/SamdeepSharma/Clustering/blob/main/Results_Clustering%20(1)%202%20(1).pdf)

## 👤 Author

**Samdeep Sharma**  
102217183
