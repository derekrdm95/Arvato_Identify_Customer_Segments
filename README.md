# Arvato_Identify_Customer_Segments
Unsupervised Learning Project by Udacity

## Motivation
The porject is provided by the Udacity unsupervised learning course collaborated with Arvato financial services.
Customer's demography information were provided to identify customer segments.
Principle compnents analysis and kmeans analysis were performed. Cluster representativeness was compared between customer database and national demographic database

## Highlight of the Analysis
-  **A clean function** was written to exclude outlier columns with high proportion of missing value, separate a group of customers since they have too much columns of missing value, perform scaling and one-hot encoding to numeric and categorical variables
-  **PCA Analysis** Principle component analysis was executed and interpreted. We chose number of component to be 60, which keep 80% variance of the data
-  **K-means** K-means cluster analysis put customers into 14 cluster + 1 group of outlier customers. Detailed profile were documented in the notebook. We would find that specific segment is over-represented in the customer database
