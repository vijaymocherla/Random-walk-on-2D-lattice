Random Walk Models
======
[Random walk models](https://en.wikipedia.org/wiki/Random_walk) are used across many disciplines to study a wide of variety of processes. Here, I give a few examples of lattice random walks.  

## 2-D Random walks
Here, I show simple examples of discrete Random Walks on a 2D surface with periodic boundary conditions along one direction. 

- We first simulate the many random walks for $\textbf{nSteps}$ for fixed dimension of $X,Y$. 

- Then we trace out the Y-values and try to find the distribution of the random variable x by generating a list of all X-values across runs. 

- This yields the possible probability ditribution. 

The Following are the parameters that are involved :
- $nSteps$: No. of steps the walker takes in each walk
- $nRuns$: No.of Random Walks of nSteps over which we average
- $(x,y)$ : The Boundary conditions for the cylindrical surface
- $P(x)$ : Probability of finding the particle x that we find after tracing values of y
