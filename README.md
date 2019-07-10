## About MNIST Dataset
- MNIST dataset consist of 60k handwritten images of numbers from 0-9 and is commonly used for training various image processing systems.
- It can be downloaded from [here](https://www.kaggle.com/c/digit-recognizer/data).
- For more information on MNIST dataset, visit this [page](https://en.wikipedia.org/wiki/MNIST_database).

## About t-SNE
- T-distributed Stochastic Neighbour Embedding (t-SNE) is a machine learning algorithm for visualization developed by Laurens van der Maaten and Geoffrey Hinton.
- The very first research paper for t-SNE was published in  2008.
- t-SNE is very good for visualization in 2-d.

## Some other dimensionality reduction technques are:
- Principal Component Analysis (PCA)
- Multi-Dimensional Scaling (MDS)
- Sammon Mapping
- Graph based techniques

I also have a repository on PCA. Check it out [here](https://github.com/deveshSingh06/Principal-Component-Analysis-PCA-on-MNIST-dataset).

## Difference between PCA and t-SNE:
- One of the prime differences between PCA and t-SNE is that PCA preserves only the global structure of the data while t-SNE preserves the local structure of the data and can choose to preserve the global structure as well.
- PCA only cares about the direction that maximizes variance and not distances between points. On the other hand, t-SNE preserves the local structure by keeping the distances between points intact(though scale/range might change).

## Main terms in t-SNE:
- Neighbourhood: The neighbourhood of a given point are the points that fall under a given distance from that point.
- Embedding: Embedding is converting a point, in d-dimensions, to a point in 2-d(or according to the need) for visualization purpose.

## Geometric interpretation of t-SNE:
- In t-SNE, the distances between a given point, in d-dimensions, and the points in its neighbourhood are preserved.
- When the given point is embedded to a point in 2-d, the actual distances between the given point and the points in its neighbourhood are similar(might be same or slightly different) to the distances that were in d-dimensions.
- Also, there is NO GAURANTEE that the distances between the given point and the points NOT in its neighbourhood are preserved/similar.
