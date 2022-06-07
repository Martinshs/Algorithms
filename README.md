# Algorithms
Some differents algorithms

## Floyd's Algorithm 

In this repository, we show a code for Floyd's algorithm. Also called Voronoid iteration, this is an iterative algorithm finding for equispaced convex
cells in euclidean space. Floyd's algorithm finds the distribution of the cells computing their center of mass and iteratively applying the Voronoid tessellation.
Like the closely related [K-means](https://en.wikipedia.org/wiki/K-means_clustering) clustering algorithm, it repeatedly finds the centroid of each set in the 
partition and then re-partitions the input according to which of these centroids is closest.

After performing this iterative process, we can visualize how Floyd's algorithm converges to obtain an equispaced distribution of convex cells. 

![Floyd iterations](/Floyd_Algorithm/Lloyd_algorithm_P350_S5_Dim2x2_I200_N8_frame1.gif)

In the code you can find diferents functions, using to compute the Voronoid diagram, to compute the center of mass, and to execute al the algoritm. In the 
last part of the code you can find the part of "Setting", in this place you can change the numeber of iteration, the number of cell that you want etc.. 
