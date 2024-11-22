This project demonstrates the implementation of clustering techniques using the Iris dataset from the sklearn library. The dataset consists of 150 samples with four features related to the morphology of iris flowers. Clustering, being an unsupervised learning technique, aims to group similar data points based on inherent patterns without utilizing the species labels provided in the dataset.

To achieve this, two clustering algorithms, KMeans and Hierarchical Clustering, were applied to the dataset. The data was preprocessed by normalizing the feature values to ensure fair comparison and proper performance of the clustering algorithms. The KMeans algorithm was used to divide the dataset into three clusters by iteratively assigning data points to the nearest centroid and updating the centroids. To visualize the clusters, the dataset was reduced to two dimensions using Principal Component Analysis (PCA), and the clusters were plotted in a 2D space.

Hierarchical Clustering was also implemented, where a dendrogram was created to represent the hierarchical structure of the data. The Ward linkage method was used to calculate the distance between clusters, and the dendrogram was truncated to show the last thirty merges. Cluster labels were then extracted by cutting the dendrogram into three clusters, which were also visualized in 2D using the PCA components.

The project concludes with a detailed comparison of the two clustering methods, highlighting their effectiveness and suitability for the Iris dataset. All the code and results are provided in a Jupyter Notebook, which has been uploaded to a GitHub repository for submission.
