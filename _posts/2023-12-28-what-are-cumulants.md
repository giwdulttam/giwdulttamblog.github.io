### What are Moments and Cumulants?



In statistics and probability, quantitative measures called moments are typically used to shape of a distribution. The most commonly encountered moments are the first and second central moments which are typically referred to as the mean and variance of a distribution. The useful thing about moments is that not only do they describe the shape of a distribution, but they also uniquely determine it. In particular, if two distributions have the same collection of moments, then they are the same distribution. In order to keep track of the list of moments for a distribution, it is convient to "string them up on a clothes line" or display them with the help of a moment generating function. The moment generating function is defined as $M_X(t) = \mathbb{E}[e^{Xt}]$. Now to motivate this definition a bit, recall that the follow is true: $M_X(t) = \mathbb{E}[e^{tX}] = \mathbb{E}[ \sum_{k=0}^{\infty} \frac{(tX)^k}{k!} = \mathbb{E}[\sum_{k=0}^{\infty} \frac{t^k X^k}{k!} = \sum_{k=0}^{\infty} \frac{\mathbb{E}[X^k]t^k}{k!}$ and recall that the Taylor series expansion of a function that is infinitely differential at a point $a$ is given by $\sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$ which implies that the moments $m_k = \mathbb{E}[X^k] = f^{(k)}(0)$. This allows us to obtain the moments of a our distribution by differentiating the moment generating function and plugging in zero. 

While moments are an important descriptor of distributions, it turns out that in some situations dealing with the moments of a distribution can be difficult and it is helpful to use a related quantity called cumulants. Similar to moments, the cumulants of a random variable $X$ can also be displayed with the help of a generating function. The cumulant-generating function is defined as the natural logarithm of the moment-generating funciton: $K_X(t) = log\mathbb{E}[e^tX] = \sum_{k = 1}^{\infty}\kappa_n \frac{t^k}{k!}$



One remarkable and deep property is that the relationship between cumulants and moments can be described through partitions of sets. In particular, the centralized nth moment moment can be written as: 

$$\mu_n' = \sum_{\pi \in p(n)}\prod_{B \in \pi}\kappa_{|B|}$$ 

where $p(n)$ denotes the partition of a set $[n]$, $\pi$ denotes a partition and $B$ denotes a block in the partition. Thus in the expression above, the nth centralized moment can be written as the sum of monomials which each correspond to a particul partition of $[n]$. For instance, if $[n] = [11]$, then one term in the expression of $\mu_{11}'$ would be $\kappa_4 \kappa_2 \kappa_5$ and another would be $\kappa_4^2 \kappa_3$ because $4 + 2 + 5$ and $4 + 4 + 3$ are both partitions of $[11]$.














