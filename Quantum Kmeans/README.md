# Quantum Clustering Implementation

## Description

This code provides Quantum Clustering implementation from scratch. Quantum clustering is a method of clustering data points based on quantum algorithms, offering potential advantages over classical clustering methods in certain scenarios.
Quantum clustering leverages principles from quantum computing to cluster data points into distinct groups. 

## Functions 

1. init_state()
Initialize the ground state of a qubit.

2. encode_data(X)
Encode input data using RY gates to transform them into quantum states.

3. kMeansInitCentroids(encoded_data, K)
Initialize K centroids to be used in K-means on the dataset.

4. computeCentroids(encoded_data, idx, K)
Compute new centroids by computing the means of the data points assigned to each centroid.

5. calculateFid(encoded_data_point, centroid)
Calculate the fidelity between two quantum states, represented by the inner product.

6. findClosestCentroids(encoded_data, centroids)
Compute centroid memberships for every data sample by finding the closest centroid for each sample.

7. quantumClustering(X, n_clusters, max_iterations)
Perform the quantum clustering algorithm, including data encoding, centroid initialization, assigning data points to clusters, and updating centroids iteratively.
