# Challenge 18: Cryptocurrencies

## Overview
The purpose of this analysis is to explore unsupervised machine learning and how it can help identify clusters of data with similar characteristics that can be used in decision making. In this analysis, data from a variety of cryptocurrencies are analyzed.

## Methods
Four basic steps were taken in this analysis, which were: 

1- Preprocessing the data for principal component analysis (PCA)
2- Reducing the number of data dimensions using PCA
3- creating clusters in the data using K-means, a method of unsupervised machine learning
4- Visualizing the data

## Results
Data columns that were not needed for analysis were removed, records with null values were dropped, and textual categorical data was transformed into numerical values.

### Figure 1: cleaned data
![Figure 1](/Resources/Fig%20-%20Clean%20data.png)

Once the data were clean, the dimensionality was decreased using PCA

### Figure 2: 3 dimensions created using PCA
![Figure 2](/Resources/Principal%20Components.png)

An elbow plot was then created to get an idea of how many clusters were likely to be present. In this case, the number of clusters was 4.

### Figure 3: Elbow plot, indicating that 4 likely clusters were present
![Figure 3](/Resources/Elbow%20Plot.png)

The data were then fit using K-means with 4 clusters, resulting in the table below.

### Figure 4: Table showing clusters (class)
![Figure 4](/Resources/Table%20with%20class.png)

Once the data were clean, the data were visualized. A sortable table, 3-D plot of clusters, and a graph comparing the total coins mined with the total supply of coins were created.

### Figure 5: Sortable table
![Figure 5](/Resources/Search%20Table.png)

### Figure 6: 3D Table of clusters
![Figure 6](/Resources/3D%20plot.png)

### Figure 7: Scatter plot of total coins mined vs total supply of coins by cluster
![Figure 7]

## Conclusions
There appear to be 4 distinct clusters of data within the dataset of cryptocurrencies. Not understanding the world of cryptocurrency, I will leave the interpretation of the individual currencies within the clusters to the experts. That said, it does appear as though the cryptocurrencies within clusters 2 and 3 behave differently than those in clusters 0 and 1, which may warrant particular attention to those currencies.