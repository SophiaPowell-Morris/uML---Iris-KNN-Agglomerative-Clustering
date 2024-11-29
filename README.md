# uML---Iris-KNN-Agglomerative-Clustering

## Clustering
Load the Iris.csv into a notebook.

Once the Iris dataset is loaded into the notebook, six different scatter plots with different combinations of variables were generated. For example, sepal length vs petal length.

In each scatter plot:

      - The different species observations with coded with different colours.
      - Determining which plot looks best for clustering

The two most promising plots were selected and a K-Nearest Neighbours model was built, were k = 3 for each of these pairs of features. For each of the two models:

    - Accuracy score was calculated
    - A scatter plot showing the cluster predictions by the model were generated

--------------
## Agglomerative Hierarchical Clustering

The Iris data was loaded into a new notebook again and two features were selected from the data to be used and to scale the data.

Four dendrograms were generated using a combination of single and complete linkage criterias, and Euclidean and Cityblock distance metrics. With the best dendrogram selected. 

Based on the dendrogram an fixed number of cluster was selected inwhich the most dissimilar clusters were shown.

Agglomerative hierarchical clustering was undertaken with the selected numbers of clusters with the same linkage and distance metrics used to generate the chosen dendrogram.

The Silhouette score was used to verify the number of clusters obtained and the success of the clustering method examined. 
