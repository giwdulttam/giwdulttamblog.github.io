
### Random Matrices and Asymptotic Freeness


# Random Matrices

A random matrix is defined as a measureable function $A : (\Omega_1, \mathcal{B_1}, \mu_1) \rightarrow (\Omega_2, \mathcal{B_2}, \mu_2)$ between probability spaces where the target space is a set of matrices defined over some field, usually $\mathbb{C}$. Alternatively, a random matrix can be thought of as a matrix whose entries are random variables. 

Now let $A_N:$ $(\Omega, \mathcal{B}, \mu)$ $\rightarrow \mathcal{H_N}$ be a Hermitian matrix-valued measurable function defined on a classical probability space. Recall that the Hermitian matrices are the complex square matrices that are equal to their own conjugate transpose. Note that since $\mathcal{H_N}$ are the dimension $N$ Hermitian matrices with complex entries, $\mathcal{H_n}$ is homeomorphic to $\mathbb{C}^{N(N-1)/2}$ as topological spaces. Therefore, we can define a measure on $\mathcal{H_N}$ to be the pushforward measure of the Borel measure on $\mathbb{C}^{N(N-1)/2}$ under the homeomorphism (that is we just take the inverse images of open sets in $\mathcal{H_N}$ and use the Borel measure to get their measure). Since $A_N$ can be thought of as a matrix whose entries are random variables, $h_{ij}$, then since $A_N$ is Hermitian, $h_{ji} = \bar{h_{ij}}$ for $i \neq j$ and $h_{ii} = \bar{h_{ii}}$ which implies that $h_{ii}$ is a real-valued random variable. 

One of the main subjects of interest in random matrix theory is finding the asymptotic eigenvlaue distribution, that is the distribution of eigenvalues of the $N \times N$ random matrix as $N \rightarrow \infty$. Recall that all of the eigenvalues of self-adjoint or Hermitian matrices are real. In order to simplify things, we will restrict our attention to the Hermitian random matrices as the eigenvalue distribution of non-Hermitian matrices is more complicated.

Now we define an $N \times N$ Gaussian random matrix to be the self-adjoint matrix $X_N = \frac{1}{\sqrt{N}}(x_{ij})^{N}$ where $i,j = 1$ such that the entries $\{ x_{ij} \}$ where $i \geq j$ are independent and identically distributed complex (real for $i = j$) Gaussian random variables with mean $\mathbb{E}[x_{ij}] = 0$ and variance $\mathbb{E}[x_{ij} \bar{x}_{ij}] = 1$. One interesting fact is that for large $N$, the eigenvalue distribution of these matrices approaches the a semicircular distribution. 

Having introduced the eigenvalue distribution for a basic family of random matrices, we will now look at a similar case for several matrices. Now consider the sequences $X_N$ and $Y_N$ of self-adjoint $N \times N$ matrices such that both sequences have an asymptotic eigenvalue distribution as $N \rightarrow \infty$. We will now investigate the asymptotic eigenvalue distribution of the sequences of $p(X_N, Y_N)$ where $p$ is a polynomial in the non-commuting random variables $X_N$ and $Y_N$, (we also require that $p$ is a self-adjoint polynomial). 

Now we will use the moment method to analyze the limit distribution of these random matrices. Observe that the information of the eigenvalue distribution of a self-adjoint matrix is captured by the trace of the powers of the matrix, that is $tr(A^{k})$ for all powers of $A$. This is because the trace of a self-adjoint matrix (recall that self-adjoin matrices are just complex analogues of real symmetric matrices which are diagonalizable) is invariant under conjugation with unitaries. To see this fact, recall that the trace is invariant under similarity transforms which include conjugation and note that when conjugating a matrix $A$ by a matrix $B$ by $BAB^{-1}$ the eigenvalues remain the same because the determinant of the conjugated matrix has the same determinant as the original matrix as conjugation can be thought of as changing the basis of the transformation. In others words, the spectral theorem with states that a Hermitian matrix $A$ can be diagonalized by by a unitary matrix $U$ such that $A = U^{\dagger}AU$ where D$ is a diagonal matrix whose diagonal elements are the eigenvalues of $A$. Thus, we have that for $k \in \mathbb{N}$ that $\frac{1}{N}(\lambda_1^k + ... + \lambda_N^k) = tr(A^k)$, where $\lambda_i$ are the eigenvalues of $A$. Therefore, we can study the eigenvalue distribution of $A$ by studying the trace of powers, $tr(A^k)$. 

Consider the sequences $X_N$ and $Y_N$ which are assumed to have almost surely an asymptotic eigenvalue distribution and recall that we would like to understand the asymptotic eigenvalue distribution of $p(X_N, Y_N)$, the non-commutative polynomials in $X_N$ and $Y_N$. Thus we investigate $tr(p(X_N, Y_N)^k)$ as $N \rightarrow \infty$ for all $k \in \mathbb{N}$ and all polynomials $p$. In order to understand this we will need to examine the mixed moments of these to non-commutative random variables. 

Consider the following example: Let $X_N$ and $Y_N$ be $N \times N$ random matrices which have asymptotic eigenvalue distributions for $N \rightarrow \infty$. Also let $X_N$ be independent of $Y_N$ (the entries are independent) and require that $Y_N$ is a unitary invariant ensemble which means that the entries in $Y_N$ do not change under unitary conjugation and thus for unitary $N \times N$ matrix, $U_N Y_N U_N^{\star}$ is equivalent to the ensemble $Y_N$. 

One example of this is two independent Gaussian random matrices $X_N$ and $Y_N$. Then it follows that as $N \rightarrow \infty$, $tr(X_N^{n_1} Y_N^{m_1}...X_N^{n_k} Y_N^{m_k})$ (that is each term in the non-commutative polynomaisl $p(X,Y)$ can be computed using the number of non-crossing pairings of...








Now, two sequences of matrices $(X_N)$ for $N \in \mathbb{N}$ and $(Y_N)$ for $N \in \mathbb{N}$ are asymptotically free if $lim_{N \rightarrow \infty} tr((X_{X}^{n_1} - \lim_{M \rightarrow \infty}tr(X_M^{n_1}) 1)(Y_N^{m_1} - \lim_{M \rightarrow \infty}tr(Y_{M}^{m_1}1)...(X_{M}^{n_k} - \lim_{M \rightarrow \infty}tr(X_M^{n_k})1)(Y_{N}^{m_k} - \lim_{M \rightarrow \infty} tr(Y_M^{m_k} 1)) = 0$. 


We also the following theorem of Voiculescu: Consider $N \times N$ random matrices $X_N$ and $Y_N$ such that: both $X_N$ and $Y_N$ have almost surely an asymptotic eigenvalue distributions for $N \rightarrow \infty$; $X_N$ and $Y_N$ are independent; $Y_N$ is a unitary invariant ensemble. Then, $X_N$ and $Y_N$ are almost surely asymptotically free. 












----------------------------------------------------------------------------------------------------------------------

# Gaussian and Constant Random Matrices

Consider $(A_N)$ (where $N \geq 1$) a sequence of random matrices with $A_N$ a GUE random matrix. Also, let $(D_N)$ (where $N \geq 1$) be a sequence of constant (that is deterministic or non-random) matrices with $D_N \in \mathbb{C}^{\bar{N} \times N}$ and assume that $\lim_{N \rightarrow \infty} tr(D_N^{m})$ exists for all $m \geq 1$. Finally, consider $A_N \rightarrow s$ and $D_N \rightarrow d$ as $N \rightarrow \infty$ where $s$ and $d$ are elements in some non-commutative probability space. 

Let $A_N^{(1)},...,A_N^{(p)}$ be $p$ independent GUE matrices and let $D_N^{(1)},...,D_N^{(q)}$ be $q$ constant non-random matrices such that: $D_N^{(1)},...,D_N^{(q)} \rightarrow d_1,...,d_q$ as $N \rightarrow \infty$. Then, $A_N^{(1)},...,A_N^{(p)}, D_N^{(1)},...,D_N^{(q)} \rightarrow s_1,...,s_p, d_1,...,d_p$ as $N \rightarrow \infty$ where $s_i$ are semicircular and $s_1,...,s_p, \{d_1,...,d_p\}$ are free. That is $A_N^{(1)},...,A_N^{(p)}, \{D_N^{(1)},...,D_N^{(q)} \}$ are asymptotically free. 


# Haar Unitary and Constant Matrices

Recall that the unitary matrices are the $N \times N$ complex matrices which satisfy $U^{\star}U = UU^{\star} = I_N$ and are denoted $U(N) \subset \mathbb{C}^{N \times N}$. These are also the matrices for which $U^{-1} = U^{\star}$ and are the complex matrices with orthonormal columns (the complex analogues of the orthogonal matrices) and thus preserve inner products. Also recall that $U(N)$ is a compact group and that the Haar measure can be defined such that $\int_{U(N)} dU = 1$ and that a Haar unitary is a matrix $U_N$ chosen at random from $U(N)$ with respect to the Haar measure. In particular we have the following definition: let $(A, \phi)$ be a non-commutative probability space with $A$ a unital $\star$-algebra. Then, $u \in A$ is called a Haar unitary if $u$ is unitary, that is $u^* u = 1_A = u u^*$ and if $\phi(u)^k = \delta_{0,k}$ for $k \in \mathbb{Z}$. Therefore, a Haar unitary random matrix $U_N \in U(N)$ is a Haar unitary for each $N \geq 1$ with $\phi = \mathbb{E} \circ tr$. 

Similar to the case of Gaussian and constant random matrices, we have the following: Let $A_N$ and $B_N$ be two sequences of constant $N \times N$ matrices with $A_N \rightarrow a$ and $B_N \rightarrow b$. Let $U_N$ be a sequence of Haar unitary random matrices. Then $A_N, U_N B_N U_N^{\star} \rightarrow a,b$, where $a$ and $b$ are free. 






































































