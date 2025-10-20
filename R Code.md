
## [[Binomial Distribution]]
```r
dbinom(x, size, prob, log = FALSE)
pbinom(q, size, prob, lower.tail = TRUE, log.p = FALSE)
# x = number of successes
# size = total amountof trials

# Example usage:
# X is Binomial(n = 10, p = 0.30)
# P(X = 2)
dbinom(2, 10, 0.3) 
# P(X <= 2)
pbinom(2, 10, 0.3)
# P (1 <= X <= 5)
sum(dbinom(1:5, 10, 0.3)) 
```

## [[Negative Binomal Distribution]]
```r
dnbinom(x, size, prob, mu, log = FALSE)
pnbinom(q, size, prob, mu, lower.tail = TRUE, log.p = FALSE)
# x/q = number of FAILURES before target number of successes occur

# Example usage:
# X ~ NegBinom(r = 2, p = 0.30)
# If X=5, then Y=3. Then,...
# P(X = 5) = P(Y = 3) = ...
dnbinom(3, 2, 0.30)           # using pmf

# P(X <= 5) = P(Y <= 3) = ...
pnbinom(3, 2, 0.30)           # using cdf

```

## [[Geometric Distribution]]
```r
dgeom(x, prob, log = FALSE)
pgeom(q, prob, lower.tail = TRUE, log.p = FALSE)

# x/q = number of FAILURES before first success

# Example usage:
# X ~ Geometric(p = 0.30)
# If X=5, then Y=4. Then,...
# P(X = 5) = P(Y = 4) = ...
dgeom(4, 0.30)                # using pmf

# P(X <= 5) = P(Y <= 4) = ...
pgeom(4, 0.30)                # using cdf
```

## [[Exponential Distribution]]
```R
dexp(x, rate = 1, log = FALSE)
pexp(q, rate = 1, lower.tail = TRUE, log.p = FALSE)

# rate (lambda) = 1 / theta

# Example usuage:
# X ~ Exponential(θ = 7), note that rate = λ = 1/7

# P(X = 4)
dexp(4, 1/7)              # using pmf

# P(X <= 5)
pexp(5, 1/7)              # using cdf
```
## [[Gamma Distribution]]
```R
dgamma(x, shape, rate = 1, scale = 1/rate, log = FALSE)
pgamma(q, shape, rate = 1, scale = 1/rate, lower.tail = TRUE,
       log.p = FALSE)
       
# rate (lambda) = 1 / theta

# Example usage:
# X ~ Gamma(α = 3, θ = 2), note that rate = λ = 1/2

# P(X = 4)
dgamma(4, 3, 1/2)              # using pmf

# P(X <= 5)
pgamma(5, 3, 1/2)              # using cdf
```

## [[Normal Distribution]]
```R
# For all norm distributions, you must specifiy
# mean and sd

# Example usage:
# X ~ Normal(0, 1)
# For probability at a specific point
dnorm(x, mean = 0, sd = 1)

# For cummulative probability from -infty to a given point
pnorm(x, mean = 0, sd = 1)

# For value given the distribution and percentile
# Asking for 0.75 means the 75th percentile (ie the 3rd quartile)
qnorm(0.75, mean = 0, sd = 1)
```
