### Credit Card Customer Segmentation Using K-Means Clustering

## Project Overview

This project was completed as an early introduction of unsupervised machine learning and clustering using a Kaggle dataset. The goal was to identify groups of customers with similar spending and payment behaviors using K-Means clustering and dimensionality reduction techniques. It has been preserved and lightly revised for presentation. 

## Objectives

- Apply K-means clustering to real-world customer data
- Evaluate clusters using the Elbow Method and Silhouette Score
- Identify patterns using customer segmentation

## Dataset: Credit Card Dataset for Clustering (Kaggle)

https://www.kaggle.com/datasets/arjunbhasin2013/ccdata

## Methodology

1. Data cleaning and missing value treatment
2. Yeo-Johnson power transformation
3. Min-Max feature scaling
4. Principal Component Analysis (PCA)
5. K-Means clustering
6. Cluster evaluation using:
   - Elbow Method
   - Silhouette Score
   - Inertia

## Results

- The Elbow Method suggested five clusters.
- Silhouette analysis suggested four clusters.
- Both solutions were evaluated before selecting the five-cluster model for interpretation.
- Distinct customer groups emerged based on spending behavior, installment usage, and cash advance activity.
- Analysis demonstrated how clustering can be used to support customer segmentation and behavioral profiling.

## Visualizations

## Repository Files

├── CreditCardClustering.ipynb
├── CreditCardClustering_Report.pdf
├── figures/
└── README.md
