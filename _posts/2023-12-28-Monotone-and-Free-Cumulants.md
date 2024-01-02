In this post, we will continue our discussion of moments and cumulants and begin to explore the interactions that arise between random variables by considering non-crossing and monotone partitions. Recall that the relationship between moments (denoted $m_n$, which corresponded to the total number of graphs on a vertex set $[n]$) and cumulants, (denoted $c_n$, which corresponded to the total number of connected graphs on a vertex set $[n]$) was: 

$$m_n(X_1,...,X_n) = \sum_{\pi \in p(n) \prod_{B \in \pi} c_{|B|}(X_i : i \in B)}$$

where the summation was taken over the partitions of the vertex set $n$. Now we can consider a variation of this relationship where the connected graphs on the vertex set $[n]$ are replaced with geometrically connected graphs on the vertex set $[n]$. If we visualize the vertex set $[n]$ as a circle of vertices, then the geometrically connected graphs are the graphs for which you can move from every vertex in the graph to another by moving along the edges (not all geometrically connected graphs are connected as in geometrically connected graphs you can move between two disconnected components if their edges cross). Now, let us denote the number of geometrically connected graphs by $\kappa_n$. In this case, the partitions that we are summing over represent the different geometrically connected components and it turns out that these are non-crossing partitions. More formally, a partition $\pi$ of a set $[m]$ with blocks $\pi = \{B_1,...,B_r\}$ is said to be non-crossing if one cannot find integers $p_1, q_1, p_2, q_2$ such that $1 \leq p_1 \leq q_1 \leq p_2 \leq q_2 \leq m$, $p_1, p_2$ are in the same block of $\pi$, $q_1, q_2$ are in the same block of $\pi$ and the $p_i's$ are not in the same block of $\pi$ as the $q_i's$. Intuitively, when the vertex set is displayed in a circle, these are the partitions for which the convex polygons corresponding to the blocks of the partition do not cross. We will denote the set of partition of $[n]$ by $\mathcal{P}(n)$ and let $\mathcal{NC}(n)$ be the set of all non-crossing partitions of $[n]$. Using non-crossing partitions, we can write:

$$m_n = \sum_{\pi \in \mathcal{NC}(n)} \prod_{B \in \pi}\kappa_{|B|}$$

Similarily we can write: 

$$m_n = \sum_{\pi \in \mathcal{NC}(n)} \prod_{B \in \pi}\kappa_{|B|}(X_i : i \in B)$$

where here $\kappa_$






Now we will discuss monotone cumulants. The analogous...

















