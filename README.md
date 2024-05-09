# CryptoClustering

In this task, I'll leverage Python and unsupervised learning to determine whether cryptocurrencies are influenced by 24-hour or 7-day price changes.

Start by loading 'crypto_market_data.csv' into a DataFrame, then examine the data's summary statistics and plot it to understand its structure.

Next, normalize the data using scikit-learn's StandardScaler() module and create a new DataFrame with the scaled data, setting the "coin_id" index from the original DataFrame.

Utilize the elbow method to identify the optimal value for k (number of clusters) using the scaled DataFrame. Then, cluster the cryptocurrencies using K-means with the best k value and visualize the clusters in a scatter plot.

Afterward, perform Principal Component Analysis (PCA) on the scaled DataFrame to reduce the features to three principal components. Determine the total explained variance of these components and create a new DataFrame with the PCA data.

Repeat the elbow method on the PCA data to find the best k value. Cluster the cryptocurrencies using K-means on the PCA data with the optimal k value and visualize the clusters in a scatter plot.

Finally, analyze the impact of using fewer features for clustering with K-Means.

While working on this module, I used Google, Xpert Learning Assistant, Chat GPT, and tutor sessions, which helped me build and run the code.