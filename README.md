# KMeans_Clustering_Stocks

Clustering stocks using KMeans

In this exercise, you'll cluster companies using their daily stock price movements (i.e. the dollar difference between the closing and opening prices for each trading day). You are given a NumPy array movements of daily price movements from 2010 to 2013, where each row corresponds to a company, and each column corresponds to a trading day.

Some stocks are more expensive than others. To account for this, include a Normalizer at the beginning. The Normalizer will separately transform each company's stock price to a relative scale before the clustering begins.

Normalizer vs StandardScaler

Note that Normalizer() is different to StandardScaler(). While StandardScaler() standardizes features by removing the mean and scaling to unit variance, Normalizer() rescales each sample - here, each company's stock price - independently of the other.

This dataset was obtained from the Yahoo! Finance API.

Got below things & more idea.

1. Normalize the data set.

2. Create an instance of KMeans called 'clusters' with no. of clusters.

3. Find the right number of clusters

4. Using k-means, it has been discovered which companies stock prices move together on the stock exchange.

5. Analyze different cluster of KMeans

6. Analyze same cluster

7. ** We can invest and see if it increases profit for stocks.
