1.matrix.ipynb

Numerical experiments on matrix theory related theorems. After inferring the calculation method of $\Delta\mathcal{J}$, we can determine whether there is causal emergence in the macro states after coarse-graining. Next, we will find an optimal matrix $W$ to maximize the degree of causal emergence $\Delta\mathcal{J}$. To solve this problem, we will firstly discuss the upper bounds related with the two terms, the determinism emergence and degeneracy emergence

2.example.ipynb

After knowing how to optimize causal emergence, we can use the theorems we derived to analyze several cases of linear stochastic iteration systems. We will attempt to search for the maximum of causal emergence in systems with known dynamics. We provide three cases, focusing on the applications of determinism emergence, degeneracy emergence, and the manifestation of causal emergence in $\mathcal{R}^3$ space.

3.space.nb

To understand the physical meaning of the solution set, we can use a simple example in the three-dimensional space to visualize our optimal solution set. In specific cases, when $k=2, n=3$, the projection of $W$ in three-dimensional space is a circle. In this case, matrix $W=(w_1^{T},w_2^{T})^{T}\in \mathcal{R}^{2\times 3}$ can be split into two row-vectors, $w_i=(w_{i1},w_{i2},w_{i3}),i=1,2$, in $\mathcal{R}^3$, The eigenvector matrix $V=(v_1,v_2,v_3)\in \mathcal{R}^{3\times 3}$ can be regarded as the combining of three vectors, $v_j=(v_{1j},v_{2j},v_{3j})^T\in \mathcal{R}^3,j=1,2,3$. To visualize the solution set of $W$, we introduce the following case as $\epsilon=\exp(-2\eta)$.
