A single value that is used to guess an unknown population parameter

Popular methods of approximating this guess is:
- [[Method of Moments]] (MoM)
- [[Maximum Likelihood]] (MLE)

Use MoM when the [[Probability Mass Function|PMF]] (ie the probability distribution) is unknown.


## Checking Bias

An estimator is considered **biased** if the expected value of the estimator minus the actual value is not 0. 
Example:
$$Bias(\hat\sigma) = E[\hat\sigma] - \sigma^2$$
If the bias is negative, the estimator is underestimating

If the bias is positive, the estimator is overestimating
