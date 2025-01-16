# Chronic-Kidney-Disease-Using-Clustering

This repository contains a project focused on the risk prediction of chronic kidney disease using clustering techniques. The workflow includes data preprocessing, clustering, and evaluation of results.

# Table of Contents

Project Overview

Features

Technologies Used

Setup and Usage

Dataset

Results



# Project Overview

Chronic kidney disease (CKD) is a significant public health concern. This project utilizes clustering algorithms to identify patterns and groupings in CKD-related data, aiming to provide insights into risk factors and patient groupings.

# Features

**Data Preprocessing**:

Handling missing values using imputation techniques.

Standardizing and scaling features.

Encoding categorical variables.

Clustering Algorithms:

K-Means clustering for partitioning data into clusters.

Agglomerative hierarchical clustering for a tree-based clustering approach.

DBSCAN (Density-Based Spatial Clustering of Applications with Noise) for identifying clusters in noisy datasets.

**Evaluation Metrics**:

Silhouette score to measure the quality of clusters.

Visual inspection of clustering results using dimensionality reduction techniques like PCA.

**Visualization**:

Scatter plots for cluster visualization.

Heatmaps for data exploration.

Dendrograms for hierarchical clustering insights.

**Technologies Used**

Python

Jupyter Notebook

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, scipy

# Dataset

The dataset contains anonymized patient data related to chronic kidney disease risk factors. It includes both numerical and categorical features that are preprocessed before applying clustering algorithms.

# Results

**Clustering Performance**:

K-Means identified clear groupings in patient data, with a silhouette score indicating cluster quality.

Hierarchical clustering provided insights into nested groupings, which were visualized using a dendrogram.

DBSCAN successfully identified noise and outliers in the dataset, improving data segmentation.

**Visualization Insights**:

PCA-reduced plots highlighted cluster separations.

Heatmaps revealed correlations and distributions within clusters.
