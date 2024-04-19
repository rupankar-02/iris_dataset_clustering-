# iris_dataset_clustering-
K-means clustering is a popular unsupervised machine learning algorithm used for clustering data points into K distinct groups (clusters). The goal of K-means clustering is to partition a dataset into K clusters, where each data point belongs to the cluster with the nearest mean (centroid).

k-means algorithm steps:

1. Choose the number of clusters \( K \).
   Randomly initialize \( K \) cluster centroids (points in the feature space) within the range of the dataset.

2.  For each data point, calculate the distance (commonly Euclidean distance) to each centroid.
    Assign the data point to the cluster whose centroid is closest (i.e., has the smallest distance).

3. After all data points are assigned to clusters, calculate the new centroids of the clusters.
   Each new centroid is computed as the mean of all data points assigned to that cluster.

4.Iterate the assignment and update steps until either the centroids converge (i.e., stop changing significantly) or a maximum number of iterations is reached.

5. The algorithm converges when the assignments of data points to clusters no longer change significantly between iterations, or when a stopping criterion (such as maximum iterations) is met.

6.  The final output of the K-means algorithm is \( K \) clusters, each characterized by its centroid.
