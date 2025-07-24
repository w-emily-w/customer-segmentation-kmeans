# Customer Segmentation using K-Means Clustering
This project applies K-means clustering to segment mall customers based on their age, annual income, and spending score. The analysis is performed in a Jupyter notebook ([kmeans.ipynb](kmeans.ipynb)) using the [Mall_Customers.csv](Mall_Customers.csv) dataset.

## Features

- Data loading and preprocessing
- Exploratory Data Analysis (EDA) with visualizations
- KMeans clustering on:
  - Annual Income & Spending Score
  - Age & Spending Score
  - Age, Annual Income & Spending Score (3D clustering)
- Elbow method to determine optimal number of clusters
- Cluster visualization and interpretation
- Marketing recommendations for each customer segment

## Usage

1. Clone the repository and open [kmeans.ipynb](kmeans.ipynb) in Jupyter or VS Code.
2. Ensure [Mall_Customers.csv](Mall_Customers.csv) is in the same directory.
3. Run the notebook cells sequentially to reproduce the analysis and visualizations.

## Requirements

- Python 3.11+
- pandas
- matplotlib
- seaborn
- scikit-learn

Install dependencies with:

```sh
pip install pandas matplotlib seaborn scikit-learn
```



