# Monte Carlo Vectorized Implementation

Monte Carlo is a technique often used in financial simulation. For example, it is useful to simulate the investment path over a time horizon, with a normal distribution of risks and returns. 

In the simulation package, there are two implementations of such monte-carlo analysis. The for-loop implementation uses nested for loop over each simulation and each month. The vectorized solution uses a matrix to carry both dimensions, and make use of SIMD to speed up.

This results in almost 3000 times improvement of speed, with exactly the same result.
