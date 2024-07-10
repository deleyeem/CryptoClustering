# CryptoClustering

## Project Overview
This project uses Python and unsupersived learning to predict if cryptocurrensices are affected by 24-hour or 7-day price changes.

## Languages and Libraries
Languages:
- Python

Libraries and Dependencies:
- pandas
- hvplot.pandas
- scikit-learn
    - KMeans
    - PCA
    - StandardScaler

## Description of Process

1. Load the data
2. Prepare the data using StandardScalar() module to normalize data and create a DataFrame.
3. Find best value for k using scaled data
4. Cluster data with K-Means using scaled data
5. Optimize clusters with Principal Component Analysis (PCA)
6. Find vest value for k using PCA data
7. Cluster data with K-Means using PCA data
8. Visualize and analyze 

## Conclusion
The clusters indicate the varied response to 24-hour vs 7-day price changes. The PCA plot clearly identifies distinct groups of cryptocurrencies with varying characteristics of stable vs volatility over the different periods. Overall the modeling and visualizations help identify patterns and groups which can be used to make decisions in trading or strategies.