In this post, we will continue our discussion of moments and cumulants and begin to explore the interactions that arise between random variables by considering non-crossing and monotone partitions. A partition $\pi$ of a set $[m]$ with blocks $\pi = \{B_1,...,B_r\}$ is said to be non-crossing if one cannot find integers $p_1, q_1, p_2, q_2$ such that $1 \leq p_1 \leq q_1 \leq p_2 \leq q_2 \leq m$, $p_1, p_2$ are in the same block of $\pi$, $q_1, q_2$ are in the same block of $\pi$ and the $p_i's$ are not in the same block of $\pi$ as the $q_i's$. Intuitively these are the partitions for which the lines representing blocks do not cross. An example of non-crossing partitions are shown below:


<div style="float: right; margin-left: 20px;">
    <img src="https://github.com/giwdulttam/giwdulttam.github.io/assets/112978414/7047a641-ea51-4614-81f7-b0819d5dcf49" alt="Alt Text" width="300"/>
</div>


Denote the set of partition of $[n]$ by $\mathcal{P}(n)$ and let $\mathcal{NC}(n)$ be the set of all non-crossing partitions of $[n]$. Now 






Therefore, we define the monotone cumulants of a probability measure with finite moments of all orders by 

$$m_n = \sum_{(\pi, \lambda) \in \mathcal{LP}(n)} \frac{r(\pi)}{|\pi|!}$$
