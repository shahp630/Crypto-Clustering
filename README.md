# Crypto-Clustering

![download](https://github.com/shahp630/Crypto-Clustering/assets/133065460/776617dc-e1d8-4b51-8d03-ee79bc8a9b55)

## What You're Creating

In this Challenge, you’ll combine your financial Python programming skills with the new unsupervised learning skills that you acquired in this module.

You’ll create a Jupyter notebook that clusters cryptocurrencies by their performance in different time periods. You’ll then plot the results so that you can visually show the performance to the board.

The CSV file that’s provided for this Homework contains the price change data of cryptocurrencies in different periods.

## Steps Required:

* Import the Data (provided in the starter code)
* Prepare the Data (provided in the starter code)
* Find the Best Value for k Using the Original Data
* Cluster Cryptocurrencies with K-means Using the Original Data
* Optimize Clusters with Principal Component Analysis
* Find the Best Value for k Using the PCA Data
* Cluster the Cryptocurrencies with K-means Using the PCA Data
* Visualize and Compare the Results

  ## Clustering

Clustering Using Originial Data:

![Screenshot (8)](https://github.com/shahp630/Crypto-Clustering/assets/133065460/907bfcaa-d337-46a3-a148-c78ce3d8c51f)

Crypto Cluster Scatter

![Screenshot (9)](https://github.com/shahp630/Crypto-Clustering/assets/133065460/a79a4954-574e-429f-9212-975b18d68d89)

![download](https://github.com/shahp630/Crypto-Clustering/assets/133065460/2ee39821-4ea7-4193-81e9-f89fc61ea6d5)


### Optimize Clusters with Principal Component Analysis

In this section, you will perform a principal component analysis (PCA) and reduce the features to three principal components.

1. Create a PCA model instance and set `n_components=3`.

2. Use the PCA model to reduce to three principal components. View the first five rows of the DataFrame. 

3. Retrieve the explained variance to determine how much information can be attributed to each principal component.

4. Answer the following question: What is the total explained variance of the three principal components?

5. Create a new DataFrame with the PCA data. Be sure to set the `coin_id` index from the original DataFrame as the index for the new DataFrame. Review the resulting DataFrame.

![Screenshot (12)](https://github.com/shahp630/Crypto-Clustering/assets/133065460/64bd2976-5100-4ae2-824c-c1654b2c432a)


