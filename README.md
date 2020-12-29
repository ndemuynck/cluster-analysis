# cluster-analysis

## what

Perform cluster analysis on Pokemon dataset

## when 

29th of December 2020

## who 

BeCode student

## how

Data preprocessing:
- Get rid or replace nan values
- Transform categorical features into numerical ones with .get_dummies method orOneHotEncoder;
- Scaling (standardization);
- Weighing of features if necessary;
-------
Unsupervised machine learning:
- Perform KMeans clustering on multiple features:
- Rewrite function distance_to_other_clusers so it can be applied on a dataframe with multiple features;
- Experiment with other cluster techniques such as DBSCAN, Spectral clustering, etc (10 in total) on the same dataset but only with 2 features;
- Evaluate the cluster techniques using Silhouette score, Calinski Harabasz score and Davies Bouldin score.
