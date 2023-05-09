# DVRP-trigger-comparison
Performance comparison of endogenous vs. exogenous reoptimisation triggers on the Uchoa et. al. 2017 Set X VRP benchmarks.

Results data for research paper "Reoptimisation strategies for Dynamic Vehicle Routing Problems with proximity-dependent nodes." 

The Set X entended benchmarks includes three geographical node distribution sets: clusterd (C), random-clustered (RC), and random (R). There are 20 unique  Vehicle Routing Problems (VRP) instances in each set. 

Results are split into two separate experiments: Poisson (classical DVRP with global information availability) and Visibility (DVRP variant with proximity-dependent nodes and local information availability).  

For each trigger (endogenous & exogenous), 120 simulations were run for each parameter value combination (distribution: R, RC, R; degree of dynamism: 0.25, 0.5, 0.75; visibility: 1,5,10,15,20,30,40,50,100). 
