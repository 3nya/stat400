The **Bernoulli** experiement represents a experiment with only 2 results (success/fail). A bernoulli trial implies that the experiment defined above was done a constant $n$ **independent** amount of times. The success probability $p$ remains the same.

An example of an bernoulli experiment is tossing a fair coin $p = 0.5$. 

An example of an bernoulli trial is tossing a fair coin $p = 0.5$ -- $n$ amount of times

## Properties
If a random variable $X$ has a **bernoulli distribution**
$X = \{0, 1\}$ 

### pmf:
$$f(x) =p^x(1-p)^{1-x}$$

### expected value:
$$E[X] = \sum_{x = 0}^1 xp^x(1-p)^{1-x} = 0(1-p)+1(p)=p$$
Key observation: the expected value is $p$.

### variance:
$$Var[X] = \sum_{x = 0}^1 (x-p)^2p^x(1-p)^{1-x} = p(1-p)$$
