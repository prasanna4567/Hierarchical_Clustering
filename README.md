# Hierarchical_Clustering

Python implementation of hierarchical clustering from scratch(Single, Complete and average linkages).

Function Description:
find_clusters(dists,linkage,no_of_clusters)

  -> dists: distance/similarity matrix

  -> linkage: 'single','complete','average'  

  -> no_of_clusters: No of clusters at which clustering can be halted.
                By default, ends with a single cluster.

Output: 

Prints the updated distance matrix, minimum_distance in the distance matrix and resulting clusters with names for 
every iteration till the number of clusters are equal to the given parameter 'no_of_clusters'

Reference: https://github.com/hhundiwala/hierarchical-clustering
