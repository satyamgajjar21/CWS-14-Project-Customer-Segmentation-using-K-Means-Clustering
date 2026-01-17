# Customer Segmentation using K Means Clustering

A machine learning project that segments customers into distinct groups based on their purchasing behavior using unsupervised learning.  
This project demonstrates clustering analysis, data preprocessing, visualization, and interpretation using the K Means algorithm.

## Table of Contents
1. Overview
2. Problem Statement
3. Dataset Description
4. Features Used
5. Approach
6. Clustering Model
7. Choosing Optimal Number of Clusters
8. Evaluation and Visualization
9. How to Run the Project
10. Results
11. Technologies Used
12. Future Improvements
13. Author

## Overview
Customer segmentation is a key task in marketing and business analytics.  
This project groups customers into meaningful segments so that businesses can better understand customer behavior and design targeted strategies.

The notebook covers data exploration, feature selection, clustering, and result visualization.

## Problem Statement
Given customer related features, group customers into different segments based on similarity.

This is an unsupervised learning problem where no target labels are provided.

## Dataset Description
The dataset contains information about customers and their purchasing behavior.

Each row represents one customer  
Each column represents a customer attribute  
There is no target column since clustering is unsupervised

## Features Used
Common features used for clustering include:
1. Age
2. Annual income
3. Spending score or purchase behavior indicators

Only numerical features are used for effective clustering.

## Approach
1. Load and explore the dataset
2. Perform basic data analysis
3. Select relevant numerical features
4. Scale features if required
5. Apply K Means clustering
6. Visualize customer segments
7. Interpret cluster characteristics

## Clustering Model
This project uses the K Means clustering algorithm.

K Means groups data points by minimizing the distance between points and their assigned cluster centroids.

The algorithm is chosen because:
1. It is simple and efficient
2. It works well for numerical data
3. It provides easily interpretable clusters

## Choosing Optimal Number of Clusters
The optimal number of clusters is determined using methods such as:
1. Elbow method
2. Within cluster sum of squares analysis

These techniques help identify the best value of K.

## Evaluation and Visualization
Clustering results are analyzed using:
1. Cluster visualization plots
2. Centroid analysis
3. Comparison of customer behavior across clusters

Visualization helps understand the characteristics of each segment.

## How to Run the Project
1. Clone the repository to your local system
2. Ensure Python version 3.8 or higher is installed
3. Open the notebook using Jupyter Notebook or Jupyter Lab
4. Run all cells sequentially

## Results
The model successfully segments customers into distinct groups with similar behavior.

These segments can be used for targeted marketing and business decision making.

## Technologies Used
1. Python
2. NumPy
3. Pandas
4. Scikit learn
5. Matplotlib
6. Seaborn
7. Jupyter Notebook

## Future Improvements
1. Try different clustering algorithms such as DBSCAN or Hierarchical clustering
2. Include more customer features
3. Automate cluster interpretation
4. Apply dimensionality reduction techniques
5. Validate clusters using business metrics

## Author
Satyam Gajjar
