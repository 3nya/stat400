You need to know: the [[Probability Mass Function]] (pmf) of the function (requires knowing the type of distribution) and given some samples of it 

Step 1: Put pmf into the likelihood formula
A [[Discrete Random Variable|discrete]] example:
$$L(\lambda) = \Pi_{i = 0}^n f(x_i, \lambda)$$

Step 2: Take the natural log of the function
$$\ln L(\lambda)$$

Step 3: Take the derivative with respect to the variable in mind
$$\frac{d}{d\lambda}\ln L(\lambda)$$
Step 4: Set to zero and solve for variable in mind
$$\frac{d}{d\lambda}\ln L(\lambda) = 0$$
