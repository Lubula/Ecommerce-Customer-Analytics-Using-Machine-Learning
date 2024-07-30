# E-Commerce-Customer-Behavior-Analysis

## Overview: 
This repository contains Jupyter notebooks and related resources for analyzing e-commerce customer behavior using various machine learning and deep learning techniques. The primary objective is to predict customer churn and segment customers based on their behavior using a combination of supervised and unsupervised learning methods. The project is structured into the following key components.

### Notebooks & Repository layout 

0. dataset: E-Commerce _Customer_Behavior.csv

1. Data Preprocessing And Build Neural Networks: 
      -  A. Feedforward Neural Networks: Utilizes a feedforward neural network to predict customer churn based on various features.
      -  B. Recurrent Neural Networks (RNN): Investigates the use of RNNs to to predict customer churn based on various features.
      -  C. Model performance and evaluation of RNN and FNN
      -  D. Not using Convolutional Neural Networks (CNN): do not have image-related features in dataset


   Unsupervised Learning Models:
2.  Clustering: Implements K-Means, Hierarchical, and DBSCAN clustering algorithms to segment customers based on their behavior.

3.   Dimensionality Reduction:
- Principal Component Analysis (PCA): Reduces the dimensionality of the dataset using PCA to visualize high-dimensional data and improve model performance.
- t-Distributed Stochastic Neighbor Embedding (t-SNE): Applies t-SNE to visualize the dataset in lower dimensions, preserving local structure.
- Uniform Manifold Approximation and Projection (UMAP): Explores UMAP as an alternative dimensionality reduction technique for visualizing complex datasets.

### Data
The dataset (data/E-Commerce _Customer_Behavior.csv) contains anonymized information about e-commerce customer behavior. It includes various features such as session details, transaction history, and churn status. Refer to the dataset documentation for more details about each feature.

License
This project is licensed under the MIT License
