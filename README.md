# Data-Mining-and-Classification-of-Climate-and-Video-Data
## Project Overview
This project focuses on the application of data mining techniques to two distinct datasets: climate data and video frame data. Through data preprocessing, feature selection, dimensionality reduction, clustering, and classification techniques, the project aims to extract meaningful patterns and insights from these datasets.

## Features
### Data Preprocessing
Involves scaling, dimensionality reduction, handling outliers, and normalization.
### Clustering
Applied techniques like K-means, DBSCAN, and Gaussian Mixture Models (GMM) for unsupervised learning.
### Classification
Utilized classifiers such as Random Forest, Support Vector Machine (SVM), and Logistic Regression to classify data.
### Principal Component Analysis (PCA)
Used to reduce dimensionality and improve clustering and classification efficiency.
## Datasets
### Climate Data
Contains meteorological parameters such as humidity, wind speed, and pressure.
Used for clustering analysis after preprocessing steps like standardization and correlation analysis.
### Video Frame Data
Extracted from video streams, containing two main features: width and length.
Used for classification tasks to predict object types using machine learning models.

## Methodology
### Data Preprocessing
Scaling and Normalization: Standardization and MinMax scaling were applied to ensure all features are on a comparable scale.
Outlier Handling: Outliers were either omitted or transformed based on their impact on the analysis.
PCA used to reduce the dimensionality of the climate data, making the clustering process more efficient and interpretable.
### Clustering Techniques
K-means Clustering: Applied after PCA, the elbow method was used to determine the optimal number of clusters.
DBSCAN: This density-based clustering method was used for identifying irregularly shaped clusters and handling outliers.
Gaussian Mixture Models (GMM): Probabilistic clustering method allowing more flexibility in cluster shapes and sizes.
### Classification Techniques
Random Forest Classifier: Used to classify video frame data. The model achieved a high accuracy with stable cross-validation performance.
Support Vector Machine (SVM): Achieved near-perfect classification accuracy in distinguishing object types in video frame data.
Logistic Regression: Demonstrated high accuracy in predicting video stream labels, with consistent performance across multiple cross-validation folds.
## Results
### Clustering Analysis:
K-means: Identified 4 distinct clusters after dimensionality reduction using PCA. The elbow method confirmed the optimal number of clusters.
DBSCAN: Produced two clusters, but further tuning of parameters such as epsilon and min_samples is needed for better performance.
GMM: Achieved good silhouette scores, showing promise in handling non-spherical clusters.
### Classification Analysis:
Random Forest: Achieved high accuracy and provided useful insights into feature importance.
SVM: Excelled in classifying video data with an accuracy score of 1.00.
Logistic Regression: Showed perfect classification on test data with high precision and recall.
