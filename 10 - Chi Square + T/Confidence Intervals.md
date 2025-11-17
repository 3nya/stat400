$$\text{statistic }\pm \text{(critical value)(standard error of the statistic)}$$

## For proportion
Standard error:
$$s_{\hat{p}} = \sqrt{\frac{\hat{p}(1- \hat{p})}{n}}$$

Critical value:
Found on the [[Reading Normal Table|normal table]]. Keep in mind that the critical value is $z_{\alpha / 2}$ remember to divide significance by 2 (to account for both directions).

**Upper/Lower Bound CI**:
When calculating an upper/lower bound CI, the critical value is $z_\alpha$!!!

Upper bound: statistic + (critical value)(SE of statistic)
Lower bound: statistic - (critical value)(SE of statistic)


## For population mean
Standard error:

If $\sigma$ is unknown and using a [[T Distribution|t distribution]]
$$s_{\bar{X}} = \frac{s}{\sqrt{n}}$$

$$s_{\bar{X}} = \frac{\sigma}{\sqrt{n}}$$

## For variance

$$(\frac{(n-1)s^2}{\chi^2_{\alpha/2}}, \frac{(n-1)s^2}{\chi^2_{1- \alpha/2}})$$
Notice the difference between the difference chi-square $\chi^2$ values.

**Upper bound**$$(0, \frac{(n-1)s^2}{\chi^2_{1- \alpha}})$$

**Lower bound**$$(\frac{(n-1)s^2}{\chi^2_{\alpha}}, \infty)$$
