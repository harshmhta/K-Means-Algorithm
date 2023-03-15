# K-Means++ Algorithm in Python for Clustering the Iris Dataset

This project implements the k-means++ algorithm in Python and uses it to cluster the Iris dataset from the UCI Machine Learning Repository. The aim of this project is to demonstrate how to implement the k-means++ algorithm and use it to cluster the Iris dataset.

## Dataset Description

The Iris dataset contains 150 samples with 4 features each. The features are sepal length (cm), sepal width (cm), petal length (cm), and petal width (cm). The dataset also includes class labels for each sample. There are three classes: Iris Setosa, Iris Versicolour, and Iris Virginica.

## Data Preprocessing

We will create a new dataset with two features by computing the ratio of raw features: x = (x1, x2) where x1 = (sepal length/sepal width) and x2 = (petal length/petal width). We will plot the data to observe the clusters in data and use the class label to color the data points for better illustration of clusters.

## Algorithm Implementation

We will implement the k-means++ algorithm in Python. The k-means++ algorithm is an extension of the k-means algorithm. It selects the initial centroids in a way that maximizes the distance between them. This makes the algorithm more robust and less likely to converge to a suboptimal solution.

## Clustering the Dataset

We will cluster the modified Iris dataset with two features explained above. We will run our algorithm 50 times over the data with different values of clusters k = 1, 2, 3, 4, 5 and plot the accuracy (x and y axes should be the number of clusters and the clustering objective, respectively). Based on the above plot, we will decide the number of final clusters and justify our answer.

For the chosen number of clusters, we will create a plot showing how objective changes with the number of iterations. We will also create a plot with the data colored by assignment, and the cluster centers.

## Files in the Repository

iris.data: The dataset in CSV format.

iris.names: Description of the dataset.

clustering.py: Python file for clustering the Iris dataset.

## Dependencies

Python 3

numpy

pandas

matplotlib

scikit-learn

## Running the Code

To run the code, open clustering.py. The output plots will be displayed.

## References

UCI Machine Learning Repository: Iris Dataset, https://archive.ics.uci.edu/ml/datasets/iris

Arthur, D. and Vassilvitskii, S. (2007). "K-means++: The Advantages of Careful Seeding". Proceedings of the Eighteenth Annual ACM-SIAM Symposium on Discrete Algorithms. pp. 1027–1035.

## Academic Integrity Statement
Please note that all work included in this project is the original work of the author, and any external sources or references have been properly cited and credited. It is strictly prohibited to copy, reproduce, or use any part of this work without permission from the author.

If you choose to use any part of this work as a reference or resource, you are responsible for ensuring that you do not plagiarize or violate any academic integrity policies or guidelines. The author of this work cannot be held liable for any legal or academic consequences resulting from the misuse or misappropriation of this work.

In summary, any unauthorized copying or use of this work may result in serious consequences, including but not limited to academic penalties, legal action, and damage to personal and professional reputation. Therefore, please use this work only as a reference and always ensure that you properly cite and attribute any sources or references used.
