# cross_entropy_method
The cross-entropy (CE) method is a Monte Carlo method for importance sampling and optimization. It is applicable to both combinatorial and continuous problems, with either a static or noisy objective.

The method approximates the optimal importance sampling estimator by repeating two phases:

1. Draw a sample from a probability distribution.
2. Minimize the cross-entropy between this distribution and a target distribution to produce a better sample in the next iteration.

Reuven Rubinstein developed the method in the context of rare event simulation, where tiny probabilities must be estimated, for example in network reliability analysis, queueing models, or performance analysis of telecommunication systems. The method has also been applied to the traveling salesman, quadratic assignment, DNA sequence alignment, max-cut and buffer allocation problems.


