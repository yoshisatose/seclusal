# SECLUSAL: A SupErvised CLUStering ALgorithm

This is the repo for [a blog post in Medium](https://medium.com/@mail_59349/seclusal-a-supervised-clustering-algorithm-33db7a30593d).

The blog post proposes **a supervised clustering method** that partitions data points into *a limited number of clusters with respect to a target variable*, based on *the features specified by the user*.

The resulting clusters have the following characteristics: 
1. The target variable has low variance within a cluster, but has high variance between clusters, and 
2. The data points in a cluster share similar values in the features that are relevant to distinguish the target. 

The method is *robust to the presence of irrelevant features and correlated features*. This supervised clustering method also helps to increase the interpretability of machine learning models.

<img src="https://github.com/yoshisatose/seclusal/blob/main/blog_medium/images/block_function.png" width="600">
<img src="https://github.com/yoshisatose/seclusal/blob/main/blog_medium/images/dendrogram_depth3_colored_thres060.png" width="600">
<img src="https://github.com/yoshisatose/seclusal/blob/main/blog_medium/images/profilling.png" width="600">

# The contents of this repository

- [/datasets/churn_simulated](/datasets/churn_simulated): The sample dataset used in the blog post.
- [/notebooks](/notebooks): The notebook used in the blog post.
- [/blog_medium](/blog_medium): The draft to the blog post in latex format.
- [/codes](/codes): Python library to implement the supervised clustering method (work in progress)
