# Clustering-Analysis-on-Cancer-Dataset
This project explores clustering techniques applied to a dataset containing features related to breast cancer characteristics. The primary aim is to preprocess the data, perform clustering, and analyze the results to gain insights into the data patterns.

**Features**
Data loading and exploration
Data preprocessing (handling null values, scaling)
Hierarchical clustering visualization using dendrograms
Agglomerative clustering implementation
KMeans clustering with optimal cluster determination
Visualizations of clustering results and evaluation metrics

**Requirements**
Python 3.x
Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

**Key Steps in Analysis**
Data Loading: Load the dataset and check its dimensions and basic statistics.
Data Preprocessing: Handle missing values, drop unnecessary columns, and scale the features.
Clustering:
Apply hierarchical clustering and visualize with a dendrogram.
Use Agglomerative Clustering and evaluate the clusters.
Implement KMeans clustering and determine the optimal number of clusters using the WCSS method.
Evaluation: Assess clustering performance using silhouette scores and visualize the results.

**Conclusion**
In this project, we applied various clustering techniques to analyze cancer dataset. Through careful data preprocessing and exploration, we successfully identified meaningful patterns in the data. The use of WCSS allowed us to determine an optimal number of clusters, ensuring that our model effectively captured the inherent structure within the data.

The silhouette score of 68.3% indicates that our clustering results are quite strong, reflecting a high degree of separation between clusters. This score suggests that the clusters formed are well-defined and that the data points within each cluster are closely related to one another. Overall, our analysis not only demonstrates the effectiveness of clustering techniques but also provides valuable insights into the characteristics of breast cancer features, contributing to further understanding and potential clinical applications.



