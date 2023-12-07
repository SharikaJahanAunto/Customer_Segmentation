# Customer Segmentation 

## Overview
This project aims to perform customer segmentation using the k-Means clustering algorithm. The dataset used contains information about customers, including their age, annual income, and spending score. The goal is to categorize customers into distinct groups based on their spending behavior.

## Dataset
The dataset (`Mall_Customers.csv`) consists of the following columns:
- CustomerID: Unique identifier for each customer
- Gender: Gender of the customer (Male/Female)
- Age: Age of the customer
- Annual Income (k$): Annual income of the customer
- Spending Score (1-100): Score assigned based on customer spending behavior

## Data Exploration
- Explored the dataset to understand its structure and characteristics.
- Checked for missing values (no missing values found).
- Selected relevant columns for clustering (Annual Income and Spending Score).

## Choosing the Number of Clusters
- Utilized the Elbow Method to determine the optimal number of clusters.
- Identified the optimum number of clusters as 5.

## Model Training
- Applied the k-Means clustering algorithm with 5 clusters.
- Obtained cluster labels for each data point.

## Visualization
- Plotted clusters and centroids to visualize customer segmentation.
- Each cluster is represented by a distinct color, and centroids are marked in cyan.

## Results
- Successfully segmented customers into 5 clusters based on their annual income and spending score.
- The identified clusters can provide insights into different customer groups and aid in targeted marketing strategies.
