
Given a joint probability table like this:

|     |     | X    | X    | X    |
| --- | --- | ---- | ---- | ---- |
|     |     | 1    | 2    | 3    |
| Y   | 1   | 0.05 | 0.05 | 0.25 |
| Y   | 2   | 0.05 | 0.25 | 0.35 |
The [[Marginal Distribution|marginal pmf]] can be found like 

$$P_X(x) = \sum_{y \in R_Y} P_{XY}(x, y)$$
in the above example,
$f_X(1) = f(1, 1) + f(1,2)$
(summation of all the X=1 probabilities added up)
