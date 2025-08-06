# Customer Segmentation using KMeans Clustering

This project focuses on grouping customers of a retail store based on their purchase behavior using the **KMeans clustering algorithm**.

## Topic: What is KMeans Clustering?

**KMeans** is an unsupervised machine learning algorithm used to find patterns in data by grouping similar data points into clusters. In this project, we use KMeans to segment customers based on:
- Annual Income (in $1000s)
- Spending Score (1–100)

## Dataset

**Source**: [Kaggle - Mall Customer Segmentation Data](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data)

## Tasks Performed

- Loaded the dataset from Kaggle.
- Selected relevant features: `Annual Income` and `Spending Score` and scaled the data.
- Determined the optimal number of clusters using the Elbow Method.
- Applied KMeans clustering.
- Visualized the clusters.
- Built a function to predict the customer group for new customers.

## Tools and Frameworks Used

- **Python**: Programming language for data processing and modeling.
- **Pandas**: For data handling and preprocessing.
- **Matplotlib & Seaborn**: For data visualization.
- **Scikit-learn**: For scaling data and applying KMeans algorithm.

##  Result

- Successfully segmented customers into 5 distinct groups based on their income and spending score.
- Built a prediction function that can assign a new customer to a suitable group.
- Centroids revealed clear differences between customer types (e.g., high spenders, low spenders, moderate-income groups, etc.).

## 🎯 What I Learned

- How unsupervised learning works in real-world scenarios.
- The importance of feature scaling in clustering.
- Building a prediction system based on clustering results.

---
## Acknowledgements

Thanks to the [Kaggle community](https://www.kaggle.com/) for hosting this dataset and challenge, and to my internship mentor for this opportunity to apply machine learning to a dataset.


