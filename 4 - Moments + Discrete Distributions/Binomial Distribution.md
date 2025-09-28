The total number of successes in a given scenario

## Definition
Let $X =$ the number of observed successes in $n$ [[Bernoulli|bernoulli trials]], the possible values of $X$ is $0,1,2,...,n$

For $x$ successes there are $n-x$ failures

Therefore $X$ has a binomial distribution.


## Properties
$X$ has a binomial distribution if:
- A [[Bernoulli]] experiment a $n$ amount of times.
- All trials are independent
- $p$ (the success probability) is constant
- $X$ is the number of successes in $n$ trials

pmf:
$$P(X=k)=(^n_k)p^k(1-p)^{n-k}$$
expected value:
$$E[X] = np$$
variance:
$$Var[X] = np(1-p)$$
