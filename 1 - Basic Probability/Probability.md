Statistic is a function of data
Statistic**s** refers to the study of the collection/analysis/interpretation of data

Probability uses **sampling** from the (known) population to learn about (unknown) data.

Statistics uses **inference** from (known) samples to learn about the (unknown) population.

## Random experiments
**Outcome space** (aka sample space) $S$ - the collection of all possible outputs
An **Event** is a collection of outcomes in $S$. If a random experiment was performed and the outcome was $A$, event $A$ has occured. 

$A \subseteq B$  - $A$ is the subset of $B$  -- everything in $A$ is also in $B$. 
$A \subset B$ - $A$ is the proper subset of $B$  -- $A$ is strictly smaller $B$. 

$A^C, A^{'}$ - Stands for the complement of $A$ (not $A$)


**Probability** is a real value set function $P$ that assigns, to each event $A$ in the sample space $S$, a number $P(A)$, the probability of the event $A$.
Properities:
- $P(A) \geq 0$
- $P(S) = 1$ (something from $S$ has to happen) *Law of total probability*
- If $A_1, A_2, ...$ are events and $A_i \cap A_j = \theta, i \neq j$ (they are disjoint) then:
	- $P(A_1 \cup A_2 \cup ... \cup A_k) = P(A_1) + P(A_2) + ... + P(A_k)$ 
	 for each positive integer $k$ for an infinite (but countable) number of events
		*This is the additive property for disjoint outcomes (make sure to state this, no need to prove)*  

**Complement rule**
$P(A) = 1 - P(A')$

**Probability of empty set)**
$P(\emptyset) = 0$

If $A \subset B, P(A) \leq P(B)$

For any event $A$, $P(A) \leq 1$


Obviously,
$P(A) = \frac{A}{S}$
$A$ = numbre of interest outcomes, $S$ = number of all outcomes


**DeMorgan's Law**
(if its the complement of you can reverse everything inside)
$P(A \cup B)' = P(A' \cap B')$
$P(A \cap B)' = P(A' \cup B')$

