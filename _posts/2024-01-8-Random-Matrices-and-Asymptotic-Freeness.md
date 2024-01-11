
### Random Matrices and Asymptotic Freeness


# Random Matrices

A random matrix is defined as a measureable function $A : (\Omega_1, \mathcal{B_1}, \mu_1) \rightarrow (\Omega_2, \mathcal{B_2}, \mu_2)$ between probability spaces where the target space is a set of matrices defined over some field, usually $\mathbb{C}$. Alternatively, a random matrix can be thought of as a matrix whose entries are random variables. 

Now let $A_N \colon (\Omega, \mathcal{B}, \mu) \rightarrow \mathcal{H_N} $ be a Hermitian matrix-valued measurable function defined on a classical probability space. Note that since $\mathcal{H_N}$ are the dimension $N$ Hermitian matrices with complex entries, $\mathcal{H_n}$ is homeomorphic to $\mathbb{C}^{N(N-1)/2}$ as topological spaces. Therefore, we can define a measure on $\mathcal{H_N}$ to be the pushforward measure of the Borel measure on $\mathbb{C}^{N(N-1)/2}$ under the homeomorphism (that is we just take the inverse images of open sets in $\mathcal{H_N}$ and use the Borel measure to get their measure). Since $A_N$ can be thought of as a matrix whose entries are random variables, $h_{ij}$, then since $A_N$ is Hermitian, $h_{ji} = \bar{h_{ij}}$ for $i \neq j$ and $h_{ii} = \bar{h_{ii}}$ which implies that $h_{ii}$ is a real-valued random variable. 

Now we say that $A_N$ is a Gaussian unitary ensemble (GUE) if each $h_{ij}$ with $i < j$ has the form: $h_{ij} = x_{ij} + \sqrt{-1} y_{ij}$, where $1 \leq 1 < j \leq N$ are independent standard Gaussian random variables, each with mean $0$ and variance $\frac{1}{2N}$. This requirement implies that $h_{ii}$ are real-valued independent Gaussian random variables independent from the $x_{ij}$'s and $y_{ij}$'s and have mean $0$ and variance $\frac{1}{N}$. 

Also, let $tr$ denote the normalized trace linear functional on the matrix algebra over $\mathbb{C}$. Thus, observe that $tr(A_N)$ is a random variable. Now let $A_N^{(1)},...,A_N^{(p)}$ be $p$ independent GUE matrices. Then $A_N^{(1)},...,A_N^{(p)} \rightarrow s_1,...,s_p$ as $N \rightarrow \infty$ where $s_1,...,s_p$ are freely independent semicircular elements which implies that $\lim_{N \rightarrow \infty} \mathbb{E}[tr(A_N^{(1)})...A_N^{(p)}] = \phi(s_{1}...s_{p})$. 


## Asymptotic Freeness

# Gaussian and Constant Random Matrices

Consider a sequence $A_N)_{N \geq 1}$ of random matrices with $A_N$ a GUE random matrix. Also, let $(D_N)_{N \geq 1}$ be a sequence of constant (that is deterministic or non-random) matrices with $D_N \in \mathbb{C}^{\bar{N} \times N}$ and assume that $\lim_{N \rightarrow \infty} tr(D_N^{m})$ exists for all $m \geq 1$. Finally, consider $A_N \rightarrow s$ and $D_N \rightarrow d$ as $N \rightarrow \infty$ where $s$ and $d$ are elements in some non-commutative probability space. 

Let $A_N^{(1)},...,A_N^{(p)}$ be $p$ independent GUE matrices and let $D_N^{(1)},...,D_N^{(q)}$ be $q$ constant non-random matrices such that: $D_N^{(1)},...,D_N^{(q)} \rightarrow d_1,...,d_q$ as $N \rightarrow \infty$. Then, $A_N^{(1)},...,A_N^{(p)}, D_N^{(1)},...,D_N^{(q)} \rightarrow s_1,...,s_p, d_1,...,d_p$ as $N \rightarrow \infty$ where $s_i$ are semicircular and $s_1,...,s_p, \{d_1,...,d_p\}$ are free. That is $A_N^{(1)},...,A_N^{(p)}, \{D_N^{(1)},...,D_N^{(q)} \}$ are asymptotically free. 


# Haar Unitary and Constant Matrices

Recall that the unitary matrices are the $N \times N$ complex matrices which satisfy $U^{\star}U = UU^{\star} = I_N$ and are denoted $U(N) \subset \mathbb{C}^{N \times N}$. Also recall that $U(N)$ is a compact group and that the Haar measure can be defined such that $\int_{U(N)} dU = 1$ and that a Haar unitary is a matrix $U_N$ chosen at random from $U(N)$ with respect to the Haar measure. In particular we have the following definition: let $(A, \phi)$ be a non-commutative probability space with $A$ a unital $\star$-algebra. Then, $u \in A$ is called a Haar unitary if $u$ is unitary, that is $u^{\star}u = 1_A = uu^{\star}$ and if $\phi(u^k) = \delta_{0,k}$ for $k \in \mathbb{Z}$. Therefore, a Haar unitary random matrix $U_N \in U(N)$ is a Haar unitary for each $N \geq 1$ with $\phi = \mathbb{E} \circ tr$. 

Similar to the case of Gaussian and constant random matrices, we have the following: Let $A_N$ and $B_N$ be two sequences of constant $N \times N$ matrices with $A_N \rightarrow a$ and $B_N \rightarrow b$. Let $U_N$ be a sequence of Haar unitary random matrices. Then $A_N, U_N B_N U_N^{\star} \rightarrow a,b$, where $a$ and $b$ are free. 






































































