### What are Cumulants?



In statistics and probability, quantitative measures called moments are typically used to shape of a distribution. The most commonly encountered moments are the first and second central moments which are typically referred to as the mean and variance of a distribution. The useful thing about moments is that not only do they describe the shape of a distribution, but they also uniquely determine it. In particular, if two distributions have the same collection of moments, then they are the same distribution. In order to keep track of the list of moments for a distribution, it is convient to "string them up on a clothes line" or display them with the help of a moment generating function. The moment generating function is defined as $M_X(t) = \mathbb{E}[e^{Xt}]$. Now to motivate this definition a bit, recall that the follow is true: $M_X(t) = \mathbb{E}[e^{tX}] = \mathbb{E}[\sum_{k=0}^{\infty} \frac{(tX)^k}{k!} = \mathbb{E}[\sum_{k=0}^{\infty} \frac{t^k X^k}{k!} = \sum_{k=0}^{\infty} \frac{\mathbb{E}[X^k]t^k}{k!}$ and recall that the Taylor series expansion of a function that is infinitely differential at a point $a$ is given by $\sum_{n=0}^{\infty} \frac{f^{(n)}(a)}{n!}(x-a)^n$ which implies that the moments $m_k = \mathbb{E}[X^k] = f^{(k)}(0)$. This allows us to obtain the moments of a our distribution by differentiating the moment generating function and plugging in zero. 
















