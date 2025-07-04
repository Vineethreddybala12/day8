# Task 8: 
Clustering with K-Means – Mall Customer Segmentation

 📌 Objective :

To perform unsupervised learning using the K-Means clustering algorithm to segment mall customers based on key attributes.

 📁 Dataset:

**Mall_Customers.csv** – contains demographic data and spending habits of mall customers.

 Features Used:
- Gender (encoded)
- Age
- Annual Income (k$)
- Spending Score (1–100)

 🔧 Tools & Libraries
- Python
- pandas
- matplotlib, seaborn
- scikit-learn (KMeans, StandardScaler, PCA, silhouette_score)

 🧠 Concepts Covered
- K-Means clustering
- Elbow Method to determine optimal number of clusters
- Silhouette Score for evaluation
- PCA for dimensionality reduction
- Cluster visualization

 📊 Process

1. **Data Preprocessing**:
   - Dropped `CustomerID`
   - Encoded `Gender`
   - Standardized features

2. **Model Training**:
   - Used KMeans from scikit-learn
   - Elbow method used to determine optimal `K` (chosen K=5)
   - Fitted KMeans model and assigned cluster labels

3. **Evaluation**:
   - Silhouette Score was computed to evaluate clustering performance

4. **Visualization**:
   - PCA used for 2D visualization of clusters
   - Cluster plots based on spending and income


