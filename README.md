# uML---Iris-KNN-Agglomerative-Clustering

Load the Iris.csv into a notebook.

Plot six different scatter plots with the different combinations of the variables. For example, sepal length vs petal length.

In each scatter plot:

      - Code the different species observations with different colours.
      - Which of these plots looks the most promising for separating into clusters?

Select two of the most promising plots and build a K-Nearest Neighbours model with k = 3 for each of these pairs of features. For each of these two models:

    - What is the accuracy of your model?
    - Create a scatter plot showing the clusters predicted by the model.

--------------
Load the Iris data set. Select two features from the data to use in this exercise and scale the data.

Using single and complete linkages, and Euclidean and Cityblock distance metrics, print dendrograms for the different combinations of these. You should have 4 dendrograms. Different distance metrics are listed here.

Pick one dendrogram to go forward with.

Choose a fixed number of clusters based on the dendrogram of your choice. These should be the most dissimilar clusters.

Run agglomerative hierarchical clustering with that number of clusters (and the linkage method and distance metric used for that dendrogram).

Verify the clusters you obtained by using the Silhouette score and comment on your confidence in your clustering solution.
