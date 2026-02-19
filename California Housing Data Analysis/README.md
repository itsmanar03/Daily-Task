# California Housing Data Analysis 🏠

This project focuses on the **Exploratory Data Analysis (EDA)** and **Data Preprocessing** of the California Housing dataset. The goal is to clean the raw data and understand the relationships between different housing features before building a predictive model.

## 📋 Project Steps (What I did in this Notebook)

### 1. Data Loading & Inspection
* Imported the dataset using `Pandas`.
* Checked the data structure using `.info()` and `.describe()` to understand the statistical distribution.

### 2. Data Cleaning & Handling Missing Values
* Identified missing values in the `total_bedrooms` column.
* Handled the missing data by **dropping** rows with null values to ensure the quality of the analysis.

### 3. Exploratory Data Analysis (EDA)
* **Visualization**: Created histograms for all numerical features to visualize data distribution and detect skewness.
* **Correlation Analysis**: Generated a **Correlation Matrix** and visualized it using a **Heatmap** to see how features like `median_income` relate to the `median_house_value`.

### 4. Data Preprocessing & Feature Engineering
* **Log Transformation**: Applied a logarithmic scale to skewed features (like `total_rooms`, `total_bedrooms`, `population`, and `households`) to normalize the distribution.
* **One-Hot Encoding**: Converted the categorical column `ocean_proximity` into binary dummy variables for machine learning readiness.
* **Feature Scaling**: Used `StandardScaler` to scale the numerical features, ensuring they are on the same magnitude.

## 🛠️ Tech Stack
* **Python**
* **Pandas**: For data manipulation.
* **NumPy**: For numerical operations.
* **Matplotlib & Seaborn**: For data visualization.
* **Scikit-Learn**: For data scaling and preprocessing.

*Developed as part of a Data Science learning journey.*
