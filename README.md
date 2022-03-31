# Ratio_of_NDS
presenting a simple framework for generating normal distributed performance samples and identifying Non-dominated solutions for a high variety of different settings


Simple function that computes the ratio of non dominated solutions for a normal distributed set of performances.
it can be used to evaluate pareto front in higher dimensions (for normal distrubuted observations in N-dimensions).

NDS_counter(N,D,dist) where
    #N = number of observations
    #D = number of dimensions
    #dist = 0 for uniform distribution
    #dist = 1 for normal distribution
    
Only package dependency is Numpy 
