### Cluster Analysis of Wholesale Customers Dataset

#### Overview:

This project performs cluster analysis on the Wholesale customers dataset using three different clustering techniques:
K-Means Clustering
Hierarchical Clustering
Mean Shifting
The goal is to identify distinct groups within the dataset based on customer purchasing behavior.

#### Methods Used:

1. K-Means Clustering:
K-Means divides the dataset into a fixed number of clusters (K) by minimizing the sum of squared distances between data points and their corresponding cluster centroids. The number of clusters (K) must be pre-defined before the algorithm starts.

2. Hierarchical Clustering:
This method builds a hierarchy of clusters that can be represented in a tree-like structure called a dendrogram. It allows for different cluster sizes and doesn’t require a pre-defined number of clusters.

3. Mean Shifting:
A density-based clustering algorithm that shifts each data point towards the densest region of the data. It effectively "shifts" points toward cluster centers, without needing to define the number of clusters beforehand.

#### Data Preprocessing:

The dataset underwent detailed preprocessing to ensure the data is clean and ready for clustering. This involved:

Handling missing values
Standardizing features for consistency
Removing any outliers
Encoding categorical variables

#### Results:

Visualizations: The analysis includes graphs and visualizations (such as dendrograms for hierarchical clustering and scatter plots for K-means and mean shifting results) to better illustrate the clustering process and the identified groups.
Cluster Summary: A summary of each cluster's characteristics, including the average feature values and key insights, has been compiled.

#### Conclusion:

The cluster analysis provides valuable insights into the customer segments within the dataset, helping to identify purchasing patterns that could be used for targeted marketing or business strategy.
