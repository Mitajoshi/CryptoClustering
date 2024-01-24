# CryptoClustering

## Purpose:
Predicting if cryptocurrencies are affected by 24-hour or 7-day price changes - using  Unsupervised Learning.

In this study, the knowledge of Python coding and  Unsupervised Learning is utilized to predict if cryptocurrencies are affected by 24-hour or 7-day price changes. 

## Instructions:
In order to successfully run the code in the Jupyter Notebook file, Crypto_Clustering_MJoshi.ipynb, download that file along with the crypto_market_data.csv data file stored in the Resource folder in this repository, maintaining the current directory structure for correct loading of data using the python code. 


## Procedure: 
In this exercise, the original dataset was first scaled and then the optimal k-value was discovered using the elbow method. The data was then clustered using the ideal k-value and the k-means algorithm. The data was clustered into two neat groups. There appeared to be 2 outlier labels. 
The dataset was then run through the PCA method to reduce the features of the original dataset. The optimal k-value was again determined for the datset with fewer features and it appears that it is the same as with the original dataset. The PCA dataframe was then analysed using the k-means algorithm and similar clusters were obtained. 

![image](https://github.com/Mitajoshi/CryptoClustering/assets/142932546/a7bfb900-b6c1-4904-a33c-50b314056dc9)
k-value comparison


![image](https://github.com/Mitajoshi/CryptoClustering/assets/142932546/22eebb82-ee04-4770-8b99-90bd0ffd805c)
cluster comparison

## Conclusion:
After visually comparing both cluster maps, it can be confirmed that those clusters labeled 1 & 3 are outliers. It can also be inferred that by using fewer features to cluster the data using K-Means, both the clusters labelled 0 & 2 in the above example, appear to be better formed, grouped in a tighter formation. The most important inference here is that even with fewer features, which means smaller sample size compared to the original population of data, the clustering was still performed in a similar manner as before. Therefore, it appears that there was no significant loss of data by using fewer features with the PCA method, which managed to still retain majority of the patterns and information from the original dataset.






