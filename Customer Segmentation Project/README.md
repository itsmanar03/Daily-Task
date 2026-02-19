# Customer Segmentation Project 🛍️

This project focuses on analyzing and segmenting customers from a "Mall Customers" dataset based on their shopping behavior, age, and annual income. The goal is to identify distinct groups using various unsupervised learning techniques.

## 📊 Workflow & Steps

### 1. Exploratory Data Analysis (EDA)
* **Data Inspection**: Loaded the dataset and explored the first few rows, info, and summary statistics.
* **Missing & Duplicates**: Checked for missing values and duplicates to ensure data quality.
* **Visual Analysis**: Created distribution plots for Age, Annual Income, and Spending Score.
* **Correlation Analysis**: Used heatmaps to understand the relationships between different customer features.

### 2. Data Preprocessing
* **Feature Selection**: Selected relevant features for the clustering process.
* **Categorical Encoding**: Handled categorical data (like Gender) using One-Hot Encoding.
* **Feature Scaling**: Applied `StandardScaler` to normalize the data, ensuring that all features contribute equally to the distance calculations in clustering.

### 3. Clustering Algorithms
Three different clustering techniques were implemented to compare results:

* **K-Means Clustering**:
    * Used the **Elbow Method** (WCSS) to determine the optimal number of clusters.
    * Evaluated the clusters using the **Silhouette Score**.
    * Visualized the final clusters and their centroids.

* **Hierarchical Clustering**:
    * Generated a **Dendrogram** to visualize the hierarchical relationship between data points and find the natural number of groups.

* **DBSCAN (Density-Based Spatial Clustering)**:
    * Implemented a density-based approach to identify clusters of arbitrary shapes and detect potential **Outliers (Noise)** in the data.

## 🛠️ Tech Stack & Libraries
* **Python**
* **Pandas & NumPy**: For data manipulation and numerical operations.
* **Matplotlib & Seaborn**: For advanced data visualization.
* **Scikit-learn**: For KMeans, DBSCAN, and data scaling.
* **SciPy**: Specifically for generating the Hierarchical Dendrogram.

## 📈 Key Findings
The analysis successfully segmented customers into meaningful groups, such as "High Income - High Spenders" or "Low Income - High Spenders," providing actionable insights for targeted marketing strategies.
