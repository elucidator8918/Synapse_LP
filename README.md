# Synapse_LP

Conclusion:
Compare ARI values of KMeans and Agglomerative Clustering. Mention below which one is better among the two. Also, specify reasons to support your claim

Agglomerative clustering is better than Kmeans for the dataset with the ARI value of 0.49 and 0.41 respectively.
Agglo performs better as its a sequential process i.e. bottom-top approach whereas Kmeans is a simultaneous process of making K-sets. 
In this dataset, none of the clusters are comparable to each other, making Kmeans a poor algo for the dataset.
Agglo is useful in cases where you want to make decisions about how coarsely or finely you want to group your data, or what resolution you want your data in.
Hence, Agglo performing better makes sense as none of the clusters such as 1 - walking, 2 - going up the stairs are comparable and they can be finely differentiated.

Research about DB-SCAN Clustering Algortihm: https://www.remnote.com/a/-textit-db-scan-clustering-algortihm-/63681c5f2ddf65ff8a89b210
