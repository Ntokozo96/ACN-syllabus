---
_db_id: 235
content_type: project
flavours:
- python
learning_outcomes:
- data_sci_unsupervised_learning
- data_sci_k_means
- data_sci_cluster_optimisation
- data_sci_cluster_metrics
pre: '<b>MEDIUM: </b>'
prerequisites:
  hard:
  - projects/data-science-specific/statistical-thinking
  - projects/data-science-specific/logistic-regression
  - topics/data-science-specific/clustering
  - topics/jupyter-notebooks-best-practices
  - topics/data-science-specific/data-science-methodology
ready: true
story_points: 8
submission_type: repo
tags:
- kmeans
- sklearn
- clustering
title: K-Means Clustering Assignment
---

## Pre-requisites

Read through the K-Means Tutorials at {{< contentlink path="topics/data-science-specific/clustering" >}} before starting this project.

## Clustering whisky distilleries according to tasting Profiles

Data: [Whisky Tasting Profiles](whisky.csv)

Use K-Means clustering to cluster whisky distilleries by their tasting profile. Use the elbow or silhouette method to find the optimal number of clusters.

To see how successful clustering was, report relevant metrics (e.g. silhouette, adjusted rand index, etc.) and create a plot showing the different distilleries, their classes according to the k-Means clustering, and the distance between points. You can use `sklearn.manifold` to get Euclidean distances between points.

Describe the main differences between the cluster - what are the factors that differ between classes?