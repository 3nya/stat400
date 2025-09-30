
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