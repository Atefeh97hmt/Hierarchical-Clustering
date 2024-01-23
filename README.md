# Hierarchical Clustering
This repository contains a Python script for performing Hierarchical Clustering on a dataset of customers. Hierarchical Clustering is a method of cluster analysis that builds a hierarchy of clusters. It can be visualized as a dendrogram, and clusters are formed by cutting the dendrogram at a certain level.

## Prerequisites
Before running the script, ensure you have the following prerequisites installed:
- Python 3
- Libraries: NumPy, Matplotlib, Pandas, scikit-learn, and SciPy

## Getting Started
1. Clone the repository:
   - git clone https://github.com/Atefeh97hmt/Hierarchical-Clustering
   - cd Hierarchical-Clustering
2. Install the required libraries
3. Download the dataset (`Customers.csv`) and place it in the root directory.
4. Run the script:
   python hierarchical_clustering.py

## Description
- Importing Libraries: The necessary libraries (NumPy, Matplotlib, Pandas, scikit-learn, SciPy) are imported.
- Importing Dataset: The customer dataset (`Customers.csv`) is loaded, and the relevant features are selected.
- Dendrogram: The script uses a dendrogram to visualize the hierarchical clustering process and determine the optimal number of clusters.
- Hierarchical Clustering: The Hierarchical Clustering algorithm is applied to the dataset using Agglomerative Clustering.
- Visualizing Clusters: The script visualizes the clusters by plotting the data points. The clusters are determined by cutting the dendrogram at a specific level.

## Results
The script generates a plot showing the clusters of customers based on their annual income and spending score. Each cluster is assigned a different color, and the clusters are labeled accordingly.

## Customization
You can customize the script by adjusting the number of clusters (`n_clusters`) and other parameters in the AgglomerativeClustering class.

## Author
- Atefeh Hemmati
- Contact: Hemmati.atefeh97@gmail.com
