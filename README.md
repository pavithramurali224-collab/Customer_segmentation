# Customer_segmentation
This documentation explains the process of performing customer segmentation using the K-Means clustering algorithm. The dataset includes features such as Age, Annual Income, and Spending Score, which are used to group customers into distinct clusters.

Google Colab Link
Access the notebook here:
https://colab.research.google.com/drive/1SvGB1kjLka1t9b5q0W-kpvsAaRhenQ0E?usp=sharing
1. Import Required Libraries
The following libraries are used in the script:
- pandas: for handling the dataset
- matplotlib: for plotting clusters
- StandardScaler: for normalizing feature values
- KMeans: for clustering customers
2. Dataset Preparation
A sample dataset is created with 10 customers, containing CustomerID, Age, Annual Income (k$), and Spending Score (1–100). The data is loaded into a DataFrame, and a preview is printed for inspection.
3. Feature Selection
The selected features used for clustering are:
- Age
- Annual Income (k$)
- Spending Score (1–100)
4. Feature Scaling
StandardScaler is applied to normalize the numerical features. This step ensures that all variables contribute equally to the distance calculations used in clustering.
5. K-Means Clustering
K-Means is applied with 3 clusters (n_clusters=3). The algorithm assigns a cluster label to each customer, which is added to the DataFrame as a new column.
6. Visualization
A scatter plot is generated using Annual Income and Spending Score, with points colored based on their cluster. This visualization helps understand customer distribution and patterns.
7. Conclusion
This process successfully segments customers into meaningful groups using the K-Means clustering algorithm. These clusters can be used for personalized marketing and business analysis.
