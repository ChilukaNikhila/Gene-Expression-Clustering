# Data Engineering and Machine learning of high-volume gene data
The main goal of the project is to find different clusters in the data. It is said that there are about sixteen different clusters, and have to predict the different test data points correctly on the sixteen different clusters.
# Dataset Description
The dataset contains gene expression data which contains 13177 rows and 13166 columns. It is an unlabeled dataset. The rows represent different samples and columns represent different gene names or features in the dataset. 
# Data Cleaning 
A custom function takes up all the features and reduces the features by taking the average of every feature and selecting only the features that has the average value of three(3) or more than three(3) i.e, >=3, and all the other features with average less than that is completely dropped. Average is a representation of the variance of the data, if the data is completely varied the average would be less or closely equal to zero. Whereas, when the feature is completely interesting that may have more average value like more than 3 for instance. Hence we chose that average as a feature metric to reduce the number of features in the dataset. 


