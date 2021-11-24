K-means is an unsupervised clustering algorithm designed to partition unlabelled 
data into a certain number of distinct groupings. In other words, k-means finds observations 
that share important characteristics and classifies them together into clusters. 
A good clustering solution is one that finds clusters such that the observations 
within each cluster are more similar than the clusters themselves. 

To identify the no. of clusters ‘K’ we visualize the elbow plot: \
![](https://drive.google.com/uc?id=1idWTVc5H8LCWCoJfL8NoPnyt5vH-3jiW) 

The marginal sum of within-cluster distances between individuals & the marginal distance between the 
cluster centers is best at 5 clusters.
To visualize the clusters in a 2D plot we use PCA with 2 components

![](https://drive.google.com/uc?id=1OREoblVlmo3cl0YtXeWCYGn26oD5GEfa)