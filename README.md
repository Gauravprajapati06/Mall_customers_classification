# Mall Customers Clustering Project

This project aims to classify customers based on their spending scores using clustering techniques. The project utilizes the mall customers dataset and employs various methods to determine the optimal number of clusters.

## Project Overview

The main objectives of this project are:
- To analyze the mall customers dataset.
- To classify customers into clusters based on their spending scores.
- To determine the optimal number of clusters using the Elbow Method and WCSS scores.
- To visualize the clusters.

## Dataset

The dataset used in this project contains information about mall customers, including:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Project Structure

The project repository contains the following files:
- `Mall_Customers_Clustering.ipynb`: Jupyter notebook with the complete code for data analysis, clustering, and visualization.
- `README.md`: This README file.
- `data/Mall_Customers.csv`: The dataset used for the analysis.

## Methodology

### Data Analysis

1. **Loading the Dataset**: The dataset is loaded and basic exploratory data analysis (EDA) is performed to understand the structure and characteristics of the data.

2. **Data Preprocessing**: The data is cleaned and prepared for clustering. This includes handling missing values, encoding categorical variables, and scaling numerical features.

### Clustering

1. **Elbow Method**: The Elbow Method is used to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters.

2. **K-Means Clustering**: K-Means clustering is applied to classify the customers into clusters based on their spending scores.

## Results

The optimal number of clusters is determined using the Elbow Method. The customers are classified into clusters, and the clusters are visualized to gain insights into customer segments.
