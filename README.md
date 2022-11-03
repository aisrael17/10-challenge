# 10-challenge
Challenge 10 for the Columbia FinTech Bootcamp

## Technologies
For this project, I used Python 3 and the following external libraries:
* pandas
* hvplot
* sklearn (KMeans, PCA, StandardScaler)
* pathlib (Path)

## Data
We analyzed data on 41 cryptocurrencies, tracking price changes over the past 24 hours, 7 days, 14 days, 30 days, 60 days, 200 days, and 1 year. 

## Project Description

First, I normalized the data using the StandardScaler() module of the sklearn library. Then, I used the elbow method to determine the optimal number of clusters for a K-means clustering analysis. In this case, I determined the optimal number of clusters to be 4. Finally, I completed the K-Means clustering analysis using $k=4$. 

For the second part of this project, I reduced the dimensionality of the data by using Principal Components Analysis with 3 principal components. Then, I repeated the above elbow method determination of optimal $k$ (which also turned out to be 4) and carried out the K-Means Clustering analysis. Finally, I visually compared the results of the second K-Means analysis to the first. 