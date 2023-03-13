# Credit-Card-Customer-Clustering
Credit Card Customer Clustering (Unsupervised learning) project as a part of my training With SHAI For AI | شاي للذكاء الاصطناعي



Cluster analysis or clustering is the technique of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar (in some sense) to each other than to those in other groups (clusters).



This task requires us to develop a customer segmentation to define a marketing strategy.



Project Steps : 

First I load the data and get insights about it. 

visualization :

I visualized the data to check the distribution of it ,null values , correlation between features ,outliers and categorical and numerical features. 

data cleaning and preprocessing : 

- I filled the null values , dropped unnecessary features .

- Scaling the data for the first time with RobustScaler and tried a clustering algorithm with it, then I tried clustering with power transformer 

- using PCA to select features that covered 95% of data 

Model building : 

I tried three algorithms: Kmeans , Brich , DBSCAN. First time with RobustScaler and then with power transformer and compared the results.

- make 2d and 3d plots for the clusters I get from the algorithm 

-write the observations I get from the plots and choose the best algorithm

You can check the project on GitHub : 



