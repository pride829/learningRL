System identification?
Associative - the best action depends on the situation?
sample-average method

The 10-armed Testbed: Reward might be varied, so the alogorithm needs to explore to find the best reward.

2.4 
Using a formula to achive incremental estimation.

2.5
Give more weight to recent rewards
Recency-weighted average.
Formula 2.7 specified the conditions required to assure convergence of (? true action values?)
Constant step-size parameter makes the estimate never completely converge. This is actually desirable in a nonstationary environment.
$$
q_*(a)=E[R_t|A_t=a]
$$

2.6
optimistic initial values
