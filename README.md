# genetic-algorithms
A Node.js framework for implementing and testing genetic algorithms.

## Genetic Algorithms
Genetic Algorithms are used in AI as a special kind of directed search based on the principles
of evolution and natural selection. There is a population of individuals (phenotypes) whose 
properties are encoded in their genotype. The algorithm iterates through individuals and
evaluates them using a fitness function and assigns each phenotype a score. It is then used
in deciding which members of the population should be kept and chosen for reproduction more
often than others, and which members are to die. Genetic Algorithms have a number of 
applications in Computer Science and in industry, and can be a fun way to learn about 
concepts from AI, such as how to define a problem, make hypotheses and test them by
designing and running experiments.

A designer of a genetic algorithm must consider a number of things specific to the problem
at hand: which evaluation function to use, how to represent individuals and when to consider
search completed. In addition to that, there are many properties that can affect how fast
a particular algorithm converges and the maximum score that can be achieved. These include
whether to use generational (batch) or steady-state (sequential) evaluations of a population,
chances of mutations and cross-overs, parent selection technique, etc. This framework aims
to contribute a collection of different techniques so that an appropriate one can be selected
for each problem. We hope that it will provide a bootstrap for experimenting with GAs and
their parameters and lead to novel approaches and amazing applications in Computer Science.

## Resources and Bibliography
- [An Overview of Genetic Algorithms: Part  Fundamentals, David Beasley et al.](http://home.ifi.uio.no/~jimtoer/GA_Overview1.pdf)
- L Davis, Handbook of Genetic Algorithms, 1991
- J. Holland, Adaptation in Natural and Artificial Systems, The MIT Press; Reprint edition 1992 (originally published in 1975).
- J. Holland, Hidden Order: How Adaptation Builds Complexity, Helix Books; 1996.

