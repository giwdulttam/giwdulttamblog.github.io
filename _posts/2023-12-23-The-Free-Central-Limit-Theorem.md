The Free Central Limit Theorem:


First recall that the classical central limit theorem says that the limiting distribution of the sum of $N$ independent, identically distributed random variables, each with mean $0$, divided by $\sqrt{N}$ is the normal distribution. In this post will we discuss the case in which these random variables are replaced with non-commutative random variables which are freely independent. 

First a non-commutative probability space $(\mathcal{A},\phi)$ consists of a unital algebra $\mathcal{A}$ and a linear function $\phi: \mathcal{A} \rightarrow \mathbb{C}$, such that $\phi(1_{\mathcal{A}}) = 1$. Any element $a \in \mathcal{A}$ is called a free or non-commutative random variable. 

Now recall the classical notion of independence. Let $(\mathcal{B}, \phi)$ be a commutative probability space, and let $b_1, ..., b_n$ in $\mathcal{B}$ be distinct random variables. Then $b_1,...,b_n$ are (classically) independent if $b_i b_j = b_j b_i$ for $1 \leq i, j \leq n$, and $\phi(b_1 b_2 ... b_n) = 0$ whenever $\phi(b_i) = 0$ for $i \leq i \leq n$. Now the definition of free independence for non-commutative random is as follows: Let $(\mathcal{A}, \phi)$ be a non-commutative probability space and let I be a fixed index set. For each $i \in I$, let $\mathcal{A_i} \subset \mathcal{A}$ be a subalgebra. The subalgebras $(\mathcal{A_i}$ are called freely independent if $\phi(a_1 ... a_k) = 0$ whenever we have the following: 1.) $k$ is a positive integer, 2.) $a_j \in \mathcal{A}_{i(j)}$ with $i(j)$ for all $j = 1,2,...,k$, 3.) $\phi(a_j) = 0$ for all $j = 1,2,...,k$, 4.) neighbouring elements from different subalgebras, $i(1) \neq i(2), i(2) \neq i(3), ... , i(k-1) \neq i(k)$. This idea of free independence can be used in mixed moments calculations. 

Just as the sum of independent and identically distributed random variables in classical probability converges to a normal distribution, in free probability sums of freely independent and identically distributed non-commutative random variables will converge to a semicirular distribution. Consider the following definitions:

Let $(\mathcal{A},\phi)$ be a non-commutative probability space and $T \in \mathcal{A}$. We say that $T$ is a standard semicircular random variable if the n-th moment of $T$ is given by: $\phi(T^n) = \frac{1}{2 \pi} \int_{-2}^{2}t^n \sqrt{4 - t^2} dt$.

Before discussing the central limit theorems, we recall the following definition for random variables be identically distributed and the definition for convergence in distirbution:

A collection of random variables $\{ a_i \}$ for $i \in \mathbb{N}$ is called identically distributed if each random variable $a_i$ for $i \in \mathbb{N}$ has the same probability distribution $\{\phi(a_i^n)\}^{\infty}_{n = 0}$. 

Let $(\mathcal{A_k}, \phi_k)$ for $k \in \mathbb{N}$, and $(\mathcal{A}, \phi)$ be non-commutative probability spaces. Then, if $(b_k)$ for $k \in \mathbb{N}$ is a sequence of non-commutative random variables with $b_k \in \mathcal{A_k}$ and let $b \in \mathcal{A}$, then we say that $b_k$ converges in distribution to $b$, denoted by $b_k \rightarrow b$, if $\lim_{k \rightarrow \infty} \phi_k(b_k^n) = \phi(b^n)$.































