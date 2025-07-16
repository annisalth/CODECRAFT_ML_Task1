# CODECRAFT_ML_02 : Customer Segmentation using K-Means
# Annisa Luthfi Nabilah - Machine Learning Intern 2025

## Task Objective
The goal of this task is to segment mall customers into distinct groups based on their purchasing behavior. We use the K-Means Clustering algorithm to identify meaningful customer segments using their **Age**, **Annual Income**, and **Spending Score**.

## Dataset Description
- **Source**: Mall_Customers.csv
- **Features Used**:
  - `Age`: Customer's age
  - `Annual Income (k$)`: Annual income in thousands of dollars
  - `Spending Score (1-100)`: Score assigned by the mall based on customer behavior and spending nature

## Tools and Libraries
- Python (Google Colab)
- Pandas
- NumPy
- Scikit-learn
- Seaborn & Matplotlib

## Methodology

### 1. Data Preprocessing
- Selected relevant numerical features
- Standardized features using `StandardScaler` to normalize the data

### 2. Optimal k Determination
- Used **Elbow Method** to identify the ideal number of clusters
- Determined **k = 5** as the optimal number based on the inertia curve

### 3. Clustering with K-Means
- Applied KMeans with `k=5`
- Assigned cluster labels to each customer

### 4. Visualization
- Plotted clusters based on **Annual Income** and **Spending Score**
- Each color represents a different segment
