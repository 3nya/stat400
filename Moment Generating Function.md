> also [[Moments]]
## Definition

Let $X$ be a [[Discrete Random Variable]] with a [[Probability Mass Function]] pmf $f(x)$ and sample space $S$.

If there is a positive number $h$ such that 

$$E(e^{tX}) = \sum_{x \in S} e^{tx} f(x)$$

exists and is finite for $-h < t < h$, then the function is defined by

$$M(t) = E(e^{tX})$$
is the **moment generating function of** $X$ , also the distribution of $X$. 

### Example
Sample space of $X$ is $S = \{a,b,c,...\}$

$M(t) = e^{ta}f(a) + e^{tb}f(b)+e^{tc}f(c)+...$