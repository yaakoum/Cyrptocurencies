# Cryptocurrencies

## Summary 

Used unsupervised machine learning techniques to analyze cryptocurrency data. Worked primarily with the K-means algorithm, the main unsupervised algorithm that groups similar data into clusters. Also implemented principal component analysis (PCA), which employs many different features. Preprocessed data for unsupervised learning, Clustered data using the K-means algorithm, and Determined the best amount of centroids for K-means using the elbow curve.

## Overview 

### Preprocessed the Data for PCA

Used knowledge of Pandas, to preprocess the dataset in order to perform PCA. 
- Used Crypto Data CSV which has all the cryptocurrencies being traded and mined
- Got dummies was then utilized for the purpose of creating variables for text features
- Finally, the data was standardized with StandardScaler()

### Reduced Data Dimensions Using PCA

Used knowledge of how to apply the Principal Component Analysis (PCA) algorithm, reduced the dimensions of the crypto DataFrame to three principal components and placed these dimensions in a new DataFrame.

### Clustering Cryptocurrencies Using K-means

To complete this deliverable, the K-algorithm was applied in order to cluster the cryptocurencies using the PCA data using the following steps:
- Creating an elbow curve to identify the best K-value
- Making predictions on the cryptocurrency K-clusters
- Lastly, producing a new DataFrame with the same index as crypto_df, but has the columns:
  - Algorithm
  - ProofType
  - TotalCoinsMined
  - TotalCoinSupply
  - PC 1
  - PC 2
  - PC 3
  - CoinName
  - Class

### Visualizing Cryptocurencies Results 

Used knowledge of creating scatter plots with Plotly Express and hvplot, visualized the distinct groups that correspond to the three principal components, then created a table with all the currently tradable cryptocurrencies using the hvplot.table() function.

## Results 

![Screen Shot 2021-03-01 at 12 25 28 PM](https://user-images.githubusercontent.com/16258584/109551787-9cd7bf00-7a96-11eb-84eb-95b7049619d7.png)

![Screen Shot 2021-03-01 at 12 25 41 PM](https://user-images.githubusercontent.com/16258584/109551788-9e08ec00-7a96-11eb-8ef3-fee9fba3f4d8.png)

![Screen Shot 2021-03-01 at 12 25 14 PM](https://user-images.githubusercontent.com/16258584/109551790-9e08ec00-7a96-11eb-8bc3-c64e4b505315.png)
