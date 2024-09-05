# Customer-Segmentation-DataMining
Unleash the power of data to find your perfect customers! This project uses machine learning to segment retail customers based on their personality, buying habits, and demographics — helping businesses target the right audience and boost sales.  

## Overview

This project aims to segment customers for a retail company using machine learning techniques. By analyzing customer data such as demographics, purchasing behavior, and marketing responses, we can create targeted marketing strategies to improve sales and customer loyalty.

## Problem Statement

A retail company wants to better understand its customer base to enhance marketing efforts and boost sales. The primary goal is to use data mining techniques to segment customers based on their personalities and behaviors, ultimately tailoring marketing efforts to the ideal customer groups.

## Data Description

The dataset used in this project contains information on customer demographics, purchasing history, and marketing campaign responses. Key features include:

- **Demographics**: Age, income, education, marital status, etc.
- **Purchases**: Amount spent on various products like wines, fruits, meat, etc.
- **Marketing Responses**: Reactions to different marketing campaigns.
- **Purchasing Channels**: Online, catalog, and in-store purchases.

Data Source: [Kaggle: Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)

## Data Processing

- **Cleaning**: Addressed missing values and removed outliers.
- **Feature Engineering**: Created new features like customer age, total spending, and campaign acceptance rates.
- **Dimension Reduction**: Applied techniques like Principal Component Analysis (PCA) to reduce data dimensionality.

## Modeling

Utilized several unsupervised machine learning algorithms for clustering:

1. **K-Means**: Selected as the best model based on Silhouette Score.
2. **Other Models**: Hierarchical Clustering, Mean Shift, Affinity Propagation, Spectral Clustering, and Birch.

Optimal clusters were determined using the Elbow Method.

## Results

The K-Means algorithm identified four customer segments:

1. **Elite Customers**: High income, high spenders, prefer quality.
2. **Good Customers**: Moderate to high spenders, value deals.
3. **Economic Customers**: Lower income, practical purchases.
4. **Ordinary Customers**: Diverse, lower spenders.

These segments help in designing targeted marketing strategies.

## Impact

The project provides actionable insights for the retail company to improve marketing efforts, enhance customer engagement, and increase overall sales by focusing on the specific needs and preferences of each customer segment.

## How to Use

1. Clone the repository.
2. Follow the provided Jupyter notebooks for data processing and modeling steps.
3. Adjust parameters or data as needed for further analysis or adaptation to different datasets.

## Conclusion

By leveraging machine learning, this project demonstrates how businesses can use customer data to segment their audience, allowing for more personalized and effective marketing strategies.
