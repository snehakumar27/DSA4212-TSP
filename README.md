# DSA4212-TSP

**Contributors**: Ee Wei En Barnabas, Sneha Kumar, Han Xiao Guang 

**Objectives**: Find an optimal permutation of a tour of 1000 cities to visit each city once and return to the initial city with the shortest possible distance. This is known as the Travelling Salesman Problem, a popular NP-hard problem in computer science. To find the global optimal for such a problem, the only guaranteed way is to use a brute-force approach: compute the distance for all possible permutations of the cities. However, given 1000 cities, that would mean 1000! permutations. This value is in the order of 102567, which would take too long to calculate, making the brute force approach highly inefficient. Hence, this project would explore strategies and heuristics to locally optimise the permutations to obtain a solution that is as close as possible to the global optimal.

**Dataset**: All cities are within a 1 by 1 unit of grid that contains 1000 points. 

**Methods**: A combination of deterministic methods, including Nearest Neighbor and 2-Opt, as well as stochastic methods, including Simmulated Annealing and ACO, were explored. 

**Results**: The 2-opt algorithm with the output of the Nearest Neighbours algorithm as an initial state achieves the lowest total distance for the given set of cities with a distance of 25.06 units. 
