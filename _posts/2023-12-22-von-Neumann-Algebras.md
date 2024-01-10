### von Neumann Algebras

We first recall that a vector space $\mathcal{H}$ over $\mathbb{C}$ is called a $\textbf{Hilbert space}$ if it is equipt with an inner product and is complete in the topology induced by the norm associated with the inner product. Further recall that a $\textbf{bounded operator}$ on a Hilbert space $\mathcal{H}$ is a $\mathbb{C}$-linear map $x: \mathcal{H} \rightarrow \mathcal{H}$ such that: $sup_{\zeta \in \mathcal{H}} \frac{\vert \vert x \zeta \vert \vert}{\vert \vert \zeta \vert \vert} < \infty$ and this supremum is called the operator norm of the operator $x$ and is denoted $\vert \vert x \vert \vert$.

Also recall that the $\textbf{adjoint}$ of the operator $x$, denoted $x^{\star}$, is the unique bounded operator determined by $< x \zeta, \eta > = < \zeta, x^* \eta >$ where $\zeta, \eta \in \mathcal{H}$.  Now note that the set of bounded operators on $\mathcal{H}$ denoted by $\mathcal{B}(\mathcal{H})$ is a $\star$ $\textbf{-algebra}$. 

Recall that a $\star$-algebra is a $\textbf{Banach algebra}$ (that is an associative algebra over $\mathbb{C}$ that is at the same time a Banach space (that is a normed space that is complete in the metric induced by the nrorm) together with an involution satisfying the properties of the adjoint where multiplication is given by composition. Also note since $\mathcal{B}(\mathcal{H})$ is closed under the operation of norm and for all $x \in \mathcal{B}(\mathcal{H})$ we have that $\vert \vert x^{\star} x \vert \vert = \vert \vert x \vert \vert^{2} = \vert \vert x^{\star} \vert \vert^2$, then $\mathcal{B}(\mathcal{H})$ is a $C^{\star}$ $\textbf{-algebra}$.

Now in order to introduce von Neumann algebras, we will first introduce a few topologies on $\mathcal{B}(\mathcal{H})$. The most natural and strongest (or finest) topology on $\mathcal{B}(\mathcal{H})$ is that induced by the operator norm.

Following this, we define the strong operator topology using the notion of strong convergence. First recall that defining a notion of convergence defines a topology as a notion of convergence specifies the open sets of a space. This is because open sets are those sets for which every sequence converging to a point inside of the open set remains entirely inside of the open set after some point - that is open sets are used in the definition of convergence.

Let $(x_{\alpha}) \subset \mathcal{B}(\mathcal{H})$ be a net of bounded operators and let $x \in \mathcal{B}(\mathcal{H})$. Then $(x_{\alpha})$ $\textbf{converges strongly}$ to $x$ if $\lim_{\alpha} \vert \vert (x_{\alpha} - x) \vert \vert = 0$ for all $\zeta \in \mathcal{H}$. In other words, the above says that the distance in the operator norm of applying the operator $(x_{\alpha} - x)$ to a vector $\zeta$ in the Hilbert space is results in the zero vector in the limit. This notion of strong convergence here can be thought of as "pointwise convergence" where as convergence under the operator norm should be thought of as "uniform convergence" as a result of the use of the supremum in the definition. Now we say that the topology induced by strong convergence is called the $\textbf{strong operator topology}$. 

Similarily, we let $(x_{\alpha}) \subset \mathcal{B}(\mathcal{H})$ be a net of bounded operators, and let $x \in \mathcal{B}(\mathcal{H})$. Then we say that $(x_{\alpha})$ $\textbf{converges weakly}$ to $x$ if $\lim_{\alpha} < (x_{\alpha} - x) \zeta, \eta > = 0$ for all $\zeta, eta \in \mathcal{H}$. In other words, for all pairs of vectors $\zeta, \eta \in \mathcal{H}$, applying the operator $(x_{\alpha} - x)$ to $\zeta$ and taking its inner product with $\eta$ gives zero in the limit as the inner product of any vector with zero is zero. The topology induced by this notion of convergence is called the $\textbf{weak operator topology}$. 

Another way to conceptualize the weak and strong operator topologies on $\mathcal{B}(\mathcal{H})$ is as follows: the weak operator topology is the weakest (or coarsest) topology on $\mathcal{B}(\mathcal{H})$ such that functional sending $x \in \mathcal{B}(\mathcal{H})$ to a complex number $< x \zeta, \eta >$ is continuous for all $\zeta, \eta \in \mathcal{H}$.

Now, we say that a unital $\star$-subalgebra $1 \in M \subset \mathcal{B}(\mathcal{H})$ is a $\textbf{von Neumann algebra}$ if it is closed in the weak operator topology. Furthermore, the $\textbf{center}$ of $M$, denoted $\mathcal{Z}$, is the von Neumann subalgebra $M \cap M'$ and if $\mathcal{Z}(M) = \mathbb{C}1$, then $M$ is called a $\textbf{factor}$.

One simple example of a von Neumann algebra is the ring $L^{\infty}(\mathbb{R})$ of essentially bounded measureable functions on the real line (that is the functions on the real line that are measureable and whose absolute value is bounded by some real number almost everywhere in its domain) whose elements act as multiplication operators by pointwise multiplication of functions on the Hilbert space $L^2(\mathbb{R})$ of square-integrable functions (the measureable functions for which the integral of the square of the absolute value is finite). Note that here $L^{\infty}(\mathbb{R})$ is the set of bounded operators and each square integralable function in $L^2(\mathbb{R})$ is a vector in a Hilbert space. 

A simple example of a von Neumann algebra is the following: let $\mathcal{H} = \mathbb{C^d}$ be finite dimensional and $\mathcal{B}(\mathcal{H})$ be the $d \times d$ matrices over $\mathbb{C}$. 

Another example of a von Neumann algebras appears in measures spaces. Let $(X, \Sigma, \mu)$ be a $\sigma-$finite measure space (that is a measure space that has a countable decomposition into measureable sets of finite measure). With $\mathcal{H} = L^2(X, \mu)$, for each $f \in L^{\infty}(X, \mu)$ identify it with the following bounded operator on $\mathcal{H}$: $ m_f \zeta \coloneq f \zeta$ for all $\zeta \in \mathcal{H}$. 

























































