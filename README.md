# Machine Learning Resources
A selection of machine learning resources

## Libraries
### Numpy
[Introduction to numpy](https://github.com/ageron/handson-ml2/blob/master/tools_numpy.ipynb)
### Pandas
[Introduction to pandas](https://github.com/ageron/handson-ml2/blob/master/tools_pandas.ipynb)
### Matplotlib
[Introduction to matplotlib](https://github.com/ageron/handson-ml2/blob/master/tools_matplotlib.ipynb)

## Books online (or free downloads)

## Topics
### Clustering

#### K Means Clustering

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: K Means Clustering (Siraj Raval)](https://www.youtube.com/watch?v=9991JlKnFmk)                                                              | TBD         |
| [Youtube: K Means Clustering (StatQuest)](https://www.youtube.com/watch?v=4b5d3muPQmA)                                                                | TBD         |
| [Youtube: K Means Clustering (Andrew Ng)](https://www.youtube.com/watch?v=hDmNF9JG3lo)                                                                | TBD         |
| [Youtube: K Means Clustering (Luis Serrano)](https://www.youtube.com/watch?v=QXOkPvFM6NU)                                                             | Hierarchical Clustering too |
| [Youtube: K Means Clustering (Batool Arhamna Haider)](https://www.youtube.com/watch?v=7Qv0cmJ6FsI)                                                    | Within Cluster and Between Cluster Distances     |
| [TowardsDataScience: Understanding K-Means](https://towardsdatascience.com/understanding-k-means-k-means-and-k-medoids-clustering-algorithms-ad9c9fbf47ca) | Also has K-Medoids |

|Library                                                                                                                                                    | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------      | ----------- |
| [sklearn.cluster.KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)                                                   | Standard K Means Clustering (Can initialize random or k-means++)        |
| [sklearn.cluster.MiniBatchKMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.MiniBatchKMeans.html#sklearn.cluster.MiniBatchKMeans) | Mini-Batch K-Means clustering |

##### Questions

- Can K Means handle categorical data?
    - The k-Means algorithm is not applicable to categorical data, as categorical variables are discrete and do not have any natural origin. So computing euclidean distance for such as space is not meaningful. => [twoardsdatascience, also links to kmodes](https://towardsdatascience.com/clustering-algorithm-for-data-with-mixed-categorical-and-numerical-features-d4e3a48066a0)
    - **NOT CHECKED YET** Can [kmodes](https://github.com/nicodv/kmodes) be used for it?

#### Hierarchical Clustering

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Hierarchical Clustering (Luis Serrano)](https://www.youtube.com/watch?v=QXOkPvFM6NU)                                                        | K Means Clustering too |

#### Density Based Clustering (TBD)

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Density Based Clustering (Brian Kent @ Pydata)](https://www.youtube.com/watch?v=5cOhL4B5waU)                                                        | TBD |

|Library                                                                                                                                                    | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------      | ----------- |
| [sklearn.cluster.DBSCAN](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)                                                   | TBD        |
| [scikit-learn-contrib.hdbscan](https://github.com/scikit-learn-contrib/hdbscan)                                                                           | Hiararchical density based clustering |

### Classification
| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Hands on machine learning (Aurélien Geron): Classification notebook](https://github.com/ageron/handson-ml2/blob/master/03_classification.ipynb)      | MNIST, Precision, Recall, Confusion Matrix, ROC         |