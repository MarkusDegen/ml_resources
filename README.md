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

### Feature Engineering

[Feature Enginnering](feature_engneering/README.md)

### Clustering

Uses
- Additionally [Vincent Warmerdam](https://youtu.be/aICqoAG5BXQ?t=1096) sees the possibility to use an auto encoder and cluster the latent space. This gets outlyer detection and sampling in the latent space for free

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: 4 Basic Types of Cluster Analysis used in Data Analytics (Decisive Data)](https://www.youtube.com/watch?v=Se28XHI2_xE)                                                | TBD |

#### Metrics for clustering

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Assessing the quality of a clustering (Christian Hennig @ PyData)](https://www.youtube.com/watch?v=Mf6MqIS2ql4)                                                | TBD |

| Library                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [sklearn.metrics.homogeneity_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.homogeneity_score.html#sklearn.metrics.homogeneity_score)          | TBD |
| [sklearn.metrics.completeness_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.completeness_score.html#sklearn.metrics.completeness_score)       | TBD |
| [sklearn.metrics.v_measure_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.v_measure_score.html#sklearn.metrics.v_measure_score)                | TBD |
| [sklearn.metrics.adjusted_rand_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.adjusted_rand_score.html#sklearn.metrics.adjusted_rand_score)    | TBD |
| [average silhouette width (ASW), TBD is this sklearn.metrics.silhouette_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.silhouette_score.html)  | TBD |

#### K Means Clustering

| Resource                                                                                                                                                   | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------       | ----------- |
| [Youtube: K Means Clustering (Siraj Raval)](https://www.youtube.com/watch?v=9991JlKnFmk)                                                                   | TBD         |
| [Youtube: K Means Clustering (StatQuest)](https://www.youtube.com/watch?v=4b5d3muPQmA)                                                                     | TBD         |
| [Youtube: K Means Clustering (Andrew Ng)](https://www.youtube.com/watch?v=hDmNF9JG3lo)                                                                     | TBD         |
| [Youtube: K Means Clustering (Luis Serrano)](https://www.youtube.com/watch?v=QXOkPvFM6NU)                                                                  | Hierarchical Clustering too |
| [Youtube: K Means Clustering (Batool Arhamna Haider)](https://www.youtube.com/watch?v=7Qv0cmJ6FsI)                                                         | Within Cluster and Between Cluster Distances     |
| [TowardsDataScience: Understanding K-Means](https://towardsdatascience.com/understanding-k-means-k-means-and-k-medoids-clustering-algorithms-ad9c9fbf47ca) | Also has K-Medoids |

|Library                                                                                                                                                    | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------      | ----------- |
| [sklearn.cluster.KMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)                                                   | Standard K Means Clustering (Can initialize random or k-means++)        |
| [sklearn.cluster.MiniBatchKMeans](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.MiniBatchKMeans.html#sklearn.cluster.MiniBatchKMeans) | Mini-Batch K-Means clustering |

##### Questions

- Can K Means handle categorical data?
    - The k-Means algorithm is not applicable to categorical data, as categorical variables are discrete and do not have any natural origin. So computing euclidean distance for such as space is not meaningful. => [twoardsdatascience, also links to kmodes](https://towardsdatascience.com/clustering-algorithm-for-data-with-mixed-categorical-and-numerical-features-d4e3a48066a0)
    - **NOT CHECKED YET** Can [kmodes](https://github.com/nicodv/kmodes) be used for it?
    - Why can't we just scale to [0;1] or [-1;1] range?

#### Hierarchical Clustering

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Hierarchical Clustering (Luis Serrano)](https://www.youtube.com/watch?v=QXOkPvFM6NU)                                                        | K Means Clustering too |
| [Youtube: Heriarchical Clustering (StatQuest)](https://www.youtube.com/watch?v=7xHsRkOdVwo)                                                           | TBD                    |

#### Density Based Clustering (TBD)

DBSCAN has typically two parameters: **eps** and **minPoints**
- **eps** tells how close data should be to be within the cluster
- **minPoints** says how many points are needed to form a cluster

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Density Based Clustering (Brian Kent @ PyData)](https://www.youtube.com/watch?v=5cOhL4B5waU)                                                | TBD |
| [Youtube: HDBSCAN (John Healy @ PyData)](https://www.youtube.com/watch?v=dGsxd67IFiU)                                                                 | TBD |

|Library                                                                                                                                                    | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------      | ----------- |
| [sklearn.cluster.DBSCAN](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html)                                                   | TBD        |
| [scikit-learn-contrib.hdbscan](https://github.com/scikit-learn-contrib/hdbscan)                                                                           | Hierarchical density based clustering |
| [debacl](https://github.com/CoAxLab/DeBaCl)                                                                                                               | Uses Level Set Trees |

#### Gaussian Mixture Model (TBD)
Clusters are described by Gaussian distributions


### Classification
| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Hands on machine learning (Aurélien Geron): Classification notebook](https://github.com/ageron/handson-ml2/blob/master/03_classification.ipynb)      | MNIST, Precision, Recall, Confusion Matrix, ROC    |

### Pipelines

| Resource                                                                                                                                              | Comment     |
| ----------------------------------------------------------------------------------------------------------------------------------------------------  | ----------- |
| [Youtube: Deploying Machine Learning using sklearn pipelines (Kevin Goetsch @ PyData)](https://www.youtube.com/watch?v=URdnFlZnlaE)                                                | TBD |
| [Youtube: Pandas, Pipelines, and Custom Transformers (Julie Michelman @ PyData)](https://www.youtube.com/watch?v=BFaadIqWlAg)                                                | TBD |
| [Youtube: How you SHOULD code Machine Learning (CodeEmporium)](https://www.youtube.com/watch?v=XvnkUg1yVmk)                                                | TBD |
| [Youtube: Creating Pipelines Using SKlearn- Machine Learning Tutorial (Krish Naik)](https://www.youtube.com/watch?v=w9IGkBfOoic)                                                | TBD |


