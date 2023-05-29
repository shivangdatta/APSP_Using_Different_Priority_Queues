# APSP_Using_Different_Priority_Queues
Implemented Johnson’s graph algorithm to find the shortest path between all pairs of nodes .
Used different data structures as priority queues in the dijkstra subroutine namely 1D array, binary heap , binomial heap and fibonacci heap and analyzed their performance.
It was found that fibonacci heap was asymptotically superior than the rest specially in the case of dense graphs,due to amortized extract min cost O(logn) and decrease key cost O(1).
