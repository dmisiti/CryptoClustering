# CryptoClustering

In this analysis, Python was utilized to display unsupervised learning models of clustering and ultimately make predictions about cryptocurrency data.

First, the data was scaled using the `StandardScaler()` module from `scikit-learn`.

Then, K-Means modeling was applied to the scaled data in order to appropriately cluster the data. 

The data was clustered in two separate instances:
- Using the original scaled data.
- Performing a PCA on the orginal scaled data, reducing the feature to three principal components, and then using this PCA data.

All coding and resuting visualization and analysis are shown in the Jupyter Notebook file `Crypto_Clustering.ipynb`.

The data was pulled from the CSV `crypto_market_data.csv`, stored in the Resources folder in this repository.
