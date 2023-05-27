# CryptoClustering

The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering

Steps

Load and preprocess the data.

Scale the data using StandardScaler.

Find the best value for k using the elbow method.

Cluster cryptocurrencies with K-means using the original scaled data.

Perform PCA to reduce the features to three principal components.

Find the best value for k using the PCA data.

Cluster cryptocurrencies with K-means using the PCA data.

Visualize and compare the results using hvPlot.

Output

Elbow Curve for Original Data

Output

Elbow Curve for Original Data

![elbow_original_data](https://github.com/Zaidality/CryptoClustering/assets/117491346/990f9378-b006-4d7c-95a5-975b93ee17fc)

Elbow Curve for PCA Data

![elbow_pca](https://github.com/Zaidality/CryptoClustering/assets/117491346/4ac8dcd5-1d5d-4b15-be92-0d4ccab900e8)

Scatter plot of Clusters based on original data

![cluster_prediction_original_data](https://github.com/Zaidality/CryptoClustering/assets/117491346/629da061-bcea-4a37-b90c-1e82978287f1)

Scatter plot of CLusters based on PCA Data

![cluster_prediction_pca](https://github.com/Zaidality/CryptoClustering/assets/117491346/b994c0c2-0bc7-45f1-b8bc-fff2c79decfb)

Summary

The conclusion of the project indicates that both the original data model and the PCA model perform best when using 4 clusters. Furthermore, when considering the elbow curve, the PCA data shows a slightly steeper inertia compared to the original data.

The three principal components derived from PCA successfully capture 90% of the variance in the returns of the cryptocurrencies.

Tools Used

Python, Pandas, Scikit-Learn, HvPlot.

