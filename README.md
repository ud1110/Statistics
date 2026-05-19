Guide to the files:

**Statistics.pdf**: A high level theoretical description of the methods to be used.

**1_Convergence_ArtificialData**: Code to see how we can predict convergence (approximately), using an artificial dataset. If the inequality is satisfied, take the mean of everything after equilibration time (or mean of block averages, mean should be the same, but some points are discarded in the blocks, so better take the mean of data after equilibration), and SEM can be taken from any block size, as it is statistically invariant.
