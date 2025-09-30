Let the number of occurrence sof some event in a given continuous interval be counted. Then, we have an **approximate** Poisson process with parameter $\lambda > 0$ if the following conditions are satisfied:
- Number of occurences in nonoverlapping subintervals are independent
- Probability of one occurrence of length $h$ is $\lambda h$
- Probability of 2 or more occurrences in a short subinterval is essentially 0.

$\lambda$ represents the rate!!

Examples:
- Number of customers that shoe up to a restaurant between 5:00pm to 6:00pm. 

## Properties
pmf: for $x = 0,1,2,...$
$$f(x) = \frac{\lambda^xe^{-\lambda}}{x!}$$
expected value:
$$E[X] = \lambda$$
variance:
$$Var[X] = \lambda$$
