# Customer Segmentation using K-Means Clustering
## 📋 About the Project
This project aims to segment customers based on their purchasing behavior using the K-means clustering algorithm. By analyzing data related to Annual Income and Spending Score, the model divides customers into clusters, allowing businesses to better understand customer groups and target their marketing efforts more effectively. This segmentation can help businesses tailor their strategies, improve customer satisfaction, and increase customer retention.

## 🛠 Technologies Used

Programming Language: Python
Libraries:
- numpy - for numerical computations
- pandas - for data manipulation and analysis
- matplotlib & seaborn - for data visualization
- scikit-learn - for implementing the K-means clustering algorithm
## 📑 Project Overview
Steps:

- Loaded libraries including numpy, pandas, matplotlib, seaborn, and KMeans from scikit-learn.
Data Collection & Analysis:

- Gathered and examined customer data, focusing on Annual Income and Spending Score. Checked for any missing values, outliers, or inconsistencies.
Data Visualization:

- Used matplotlib and seaborn to visualize data distribution and explore patterns within spending and income levels.
Feature Selection:

- Selected Annual Income and Spending Score columns to segment customers based on these characteristics.
Determining Number of Clusters:

- Employed Within-Cluster Sum of Squares (WCSS) to identify the optimal number of clusters.
Used the "Elbow Method" to plot WCSS values and determine the point where adding more clusters does not significantly improve the model.
Training the K-means Model:

- Trained the K-means clustering model on the dataset with the identified number of clusters.
- Visualizing the Clusters

- Created visualizations of the clusters to observe customer segments and interpret patterns within each group.
## 🎯 Results
The clustering algorithm successfully segmented customers into distinct groups based on their purchasing behavior. Each cluster represents a unique customer segment with similar income and spending characteristics, aiding targeted marketing strategies.





![cluster](https://github.com/user-attachments/assets/e7cd326c-a72f-4f5d-9e0f-aa8f78c6efb6)







![graphL](https://github.com/user-attachments/assets/6dcf3d04-4602-4c3c-88e9-8da565e389fd)
