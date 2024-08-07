# Customer-Segmentation-using-K-Means-Clustering
# Project Overview:
# 1- Importing Libraries and Data:
Importing the necessary Python libraries for data manipulation, visualization, and modeling, including pandas, numpy, matplotlib, seaborn, and KMeans. Then collected and imported the dataset relevant to customer information, typically including features like annual income and spending score.
# 2- Data Analysis:
Conducted exploratory data analysis (EDA) to understand the dataset's structure, check for missing values, and perform necessary cleaning and preprocessing.
# 3- Feature Selection:
Chose the 'Annual Income' and 'Spending Score' columns as features for the K-Means clustering model. These features are crucial for segmenting customers based on their income and spending behaviors.
# 4- Determining the Number of Clusters:
Utilized the Within-Cluster Sum of Squares (WCSS) method to determine the optimal number of clusters. The WCSS measures the total variance within each cluster, which helps in evaluating the quality of clustering.
# 5- Elbow Method:
Plotted an elbow graph to visualize the WCSS values for different numbers of clusters. This graphical method aids in selecting the optimal number of clusters by identifying the point where the reduction in WCSS begins to slow down, known as the "elbow."
# 6- Optimal Number of Clusters:
Determined that the optimal number of clusters is 5 based on the elbow graph analysis.
# 7- Training the K-Means Model:
Trained the K-Means clustering model using the chosen number of clusters. The model groups the customers into distinct clusters based on their annual income and spending score.
# 8- Visualization:
Visualized the clusters and their centroids using scatter plots. This step helps in interpreting the segmentation results and understanding how customers are distributed across different clusters.
