Sequence of independent [[Bernoulli|bernoulli trials]] until the $r$th success occurs.
## Definition
Let $X =$ the number trials needed to observe the $r$th success.

Therefore $X$ has a negative binomial distribution with parameters $r,p$.


## Properties

pmf:
$$f(x) = (^{x-1}_{r-1})p^r(1-p)^{x-r}$$ for $x = r, r+1, r+2, ...$

expected value:
$$E[X] = r/p$$

variance:
$$Var[X] = \frac{r(1-p)}{p^2}$$
