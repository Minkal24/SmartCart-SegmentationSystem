# SmartCart Customer Segmentation System

## 📌 Overview

SmartCart Customer Segmentation System is an Unsupervised Machine Learning project that groups customers into meaningful segments based on their purchasing behavior. The project helps businesses better understand customer patterns and supports data-driven marketing strategies by identifying customers with similar characteristics.


## 🎯 Objective

The primary objective of this project is to segment customers into distinct groups using clustering techniques. Customer segmentation enables businesses to:

* Identify high-value customers
* Design personalized marketing campaigns
* Improve customer satisfaction
* Increase customer retention
* Support better business decision-making

## 📊 Dataset Information

The dataset contains customer information related to shopping behavior and purchasing patterns used for customer segmentation.

> **Note:** The dataset (`smartcart_customers.csv`) is not included in this repository.

## ⚙️ Project Workflow

1. Data Collection
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling
5. Dimensionality Reduction using PCA
6. Finding the Optimal Number of Clusters using the Elbow Method
7. Cluster Validation using the Silhouette Score
8. Customer Segmentation using K-Means Clustering
9. Customer Segmentation using Agglomerative Clustering
10. Visualization and Analysis of Customer Segments


## 🤖 Machine Learning Techniques Used

### 🔹 Principal Component Analysis (PCA)

* Reduced data dimensions while preserving important information.
* Improved clustering visualization and computational efficiency.

### 🔹 K-Means Clustering

* Unsupervised Machine Learning algorithm used to group similar customers.
* Segmented customers based on purchasing behavior.
* Generated meaningful customer clusters for business analysis.

### 🔹 Agglomerative Clustering

* Hierarchical clustering algorithm using **Ward Linkage**.
* Compared clustering performance with K-Means.
* Helped analyze customer groups using a hierarchical approach.

### 🔹 Elbow Method

* Used to determine the optimal number of clusters (K).
* Identified the point where increasing the number of clusters no longer significantly improved clustering performance.

### 🔹 Silhouette Score

* Evaluated the quality of clustering.
* Measured how well customers fit within their assigned clusters.
* Validated the effectiveness of the selected clustering solution.

## 📈 Results

* Successfully segmented customers into meaningful groups using **K-Means Clustering**.
* Determined the optimal number of clusters using the **Elbow Method**.
* Evaluated clustering quality using the **Silhouette Score**.
* Applied **Agglomerative Clustering (Ward Linkage)** to compare results with K-Means.
* Used **PCA** to visualize customer clusters effectively.
* Generated actionable customer segments that can support targeted marketing and business decision-making.

-
## 💼 Business Applications

This project can help businesses to:

* Understand customer purchasing behavior
* Identify premium and loyal customers
* Improve targeted marketing campaigns
* Recommend personalized products
* Increase customer retention
* Support data-driven business strategies

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 🏆 Conclusion

This project demonstrates the practical application of Unsupervised Machine Learning for customer segmentation. K-Means Clustering was used to identify customer groups, while the Elbow Method and Silhouette Score were used to determine and validate the optimal number of clusters. Agglomerative Clustering was also implemented to compare clustering results using a hierarchical approach. Additionally, Principal Component Analysis (PCA) was applied for dimensionality reduction and cluster visualization. Together, these techniques provide meaningful business insights that can help organizations improve customer targeting, enhance marketing strategies, and make data-driven decisions.

---

## 👨‍💻 Author

**Minkal**




