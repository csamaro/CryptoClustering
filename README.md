# CryptoClustering
Use Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

First, we scaled the data to make it more compatible for unsupervised learning.
Then we used KMeans on the original data, predicted the cluster amount, and plotted the results.
After this we optimized the clusters with the Principal Component Analysis to see if we would get different results.

Using the elbow method for KMeans and PCA, the optimal cluster group was seen to be 4 for both.
We can see the comparisons of the plotted line curve to be almost, if not, identical.

The amount of clusters used was seen to be optimal because it reduced the amount of outliers for each cluster.
If we had used less clusters then the size of them would have seen to be significantly bigger.
Alternatively, if we used more clusters then we would have too small of groups. Resulting in less efficient learning.
