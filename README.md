# CryptoClustering

# Description

Using Unsupervised learning models to analyse Cryptocurrency data.

The data set is imported and plotted. Scikit-learn's Standard Scaler is used to normalize the data.

A for loop is used to determine the appropriate target number of clusters for the data. Sckikit-learn's KMeans model is initatied with that number and then fit to the data. KMeans is used to assign each data point to a cluster. The result is plotted to show the clustering.

Scikit learn's Principal Component Analysis is applied to the scaled data to reduce the number of features. The same process of determining a target number of clusters is repeated and KMeans clusters the principal components. 

The result is plotted, which reveals that after reducing features the clusters are much tighter, indicating that the data points in each cluster have more in common with each other.

# Authors and Acknowledgements

Thanks to the instructional team and especially to Scikit-learn developers and documentation.
