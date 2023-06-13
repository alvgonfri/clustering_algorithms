<h1 align="center">Clustering Algorithms</h1>
<h5 align="center">By Álvaro González Frías and Álvaro Bernal Caunedo</h5>

## Introduction
In this project we will implement some clustering algorithms like K-Means and DBSCAN. This algorithms will be implemented in Python and will be tested with some datasets. We will also implement some metrics to evaluate the results of the algorithms and we will create a documentation with Overleaf.

The aim of this study is to carry out a comprehensive comparison of ten clustering algorithms. Three evaluation metrics commonly used in the clustering field will be used for the comparison. The clustering field will be used for such a comparison. The objective is to determine which clustering algorithm is more effective as a function of the hyperparameters used, making use of the same data set.

## Table of Contents
- [Abstract](#Abstract)
- [Algorithms](#Algorithms)
- [Datasets](#Datasets)
- [Metrics](#Metrics)
- [Documentation](#Documentation)

## Abstract <div id='Abstract'>
A detailed evaluation of the ten clustering algorithms was carried out using the Silhouette, Davies-Bouldin, and Calinski-Harabasz metrics. The results revealed that clustering algorithms significantly depend on the dataset and the classification objective. Overall, it was observed that K-means, UPGMA, and Mixture of Gaussians achieved the best results in terms of all three metrics for the given dataset. However, it was noted that some algorithms, such as DBSCAN, exhibited suboptimal results. In general, this study provides a useful guide for selecting the most appropriate hyperparameters according to the clustering algorithm used.
  
## Algorithms <div id='Algorithms'>
The algorithms that we have used for the study are as follows:
- BIRCH
- DBSCAN
- K-means
- Mini-Batch K-means
- Mean Shift
- OPTICS
- Spectral Clustering
- Mixture of Gaussians
- PAM
- UPGMA


## Datasets <div id='Datasets'>
Prior to carrying out the analysis, the data set used for the dataset that has been used to carry out this study is presented graphically. It is a dataset containing 1000 elements, each with three characteristics. This allows us to represent them by means of the following three-dimensional graph:
<p align= "center">
<img width="402" alt="Dataset" src="https://github.com/alvgonfri/clustering_algorithms/assets/80347035/696646d3-60e7-49ec-94f8-7c165fe4b148">
</p>

## Metrics <div id='Metrics'>
The metrics that we have used for the study are as follows:
- Silhouette coefficient
- Calinski-Harabasz index
- Davies-Bouldin index

## Documentation <div id='Documentation'>
The documentation of the project is in the main folder of the repository. It is a pdf file called "ClusteringG5.pdf", it has been created with Overleaf and it is in Spanish.
