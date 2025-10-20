Remember that :
$$\mu_X = E(X) \quad \mu_Y = E(Y)$$
$$\sigma_X^2 = E[(X - \mu_X)^2] \quad \sigma_Y^2 = E[(Y-\mu_Y)^2]$$

Therefore, the covariance of $X$ and $Y$ is:

$$Cov[X,Y] = E[(X-\mu_X)(Y-\mu_Y)] = \sigma_{XY}$$
$$Cov[X,Y] = E[XY] - E[X]\cdot E[Y]$$


## Calculating $E[XY]$
Discrete:
$$E[XY] = \sum_x\sum_y xy f(x,y)$$
Continuous:
$$\int_x\int_yxyf(x,y) dy dx$$
