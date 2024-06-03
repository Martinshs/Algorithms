# Algorithms
Some different algorithms

## Floyd's Algorithm 

In this repository, we show a code for Lloyd's algorithm. Also called Voronoi iteration, this is an iterative algorithm finding for equispaced convex
cells in Euclidean space. Floyd's algorithm finds the distribution of the cells, computing their center of mass and iteratively applying the Voronoi tessellation.
Like the closely related [K-means](https://en.wikipedia.org/wiki/K-means_clustering) clustering algorithm, it repeatedly finds the centroid of each set in the 
partition and then re-partitions the input according to which of these centroids is closest.

After performing this iterative process, we can visualize how Lloyd's algorithm converges to obtain an equispaced distribution of convex cells. 

![Lloyd iterations](/Floyd_Algorithm/Lloyd_algorithm_P350_S6_Dim2x2_I200_N8.gif)

In the code, you can find different functions used to compute the Voronoi diagram, compute the center of mass, and execute all the algorithms. In the 
In the last part of the code, you can find the part "Setting"; in this place, you can change the number of iterations, the number of cells you want, etc. 
