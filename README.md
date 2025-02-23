# An Exact Theory of Causal Emergence for Linear Stochastic Iteration Systems

After coarse-graining a complex system, the dynamics of its macro-state may exhibit more pronounced causal effects than those of its micro-state. This phenomenon, known as causal emergence, is quantified by the indicator of effective information. However, two challenges confront this theory: the absence of well-developed frameworks in continuous stochastic dynamical systems and the reliance on coarse-graining methodologies. In this study, we introduce an exact theoretic framework for causal emergence within linear stochastic iteration systems featuring continuous state spaces and Gaussian noise. Building upon this foundation, we derive an analytical expression for effective information across general dynamics and identify optimal linear coarse-graining strategies that maximize the degree of causal emergence when the dimension averaged uncertainty eliminated by coarse-graining has an upper bound. Our investigation reveals that the maximal causal emergence and the optimal coarse-graining methods are primarily determined by the principal eigenvalues and eigenvectors of the dynamic system's parameter matrix, with the latter not being unique. To validate our propositions, we apply our analytical models to three simplified physical systems, comparing the outcomes with numerical simulations, and consistently achieve congruent results. 

## 1.matrix.ipynb

Numerical experiments on matrix theory related theorems. After inferring the calculation method of $\Delta\mathcal{J}$, we can determine whether there is causal emergence in the macro states after coarse-graining. Next, we will find an optimal matrix $W$ to maximize the degree of causal emergence $\Delta\mathcal{J}$ as
```math
\Delta\mathcal{J}=\mathop{\ln\frac{|\det(WAW^\dagger)|^\frac{1}{k}}{|\det(A)|^\frac{1}{n}}}_{Degeneracy Emergence}+\mathop{\ln\frac{|\det(\Sigma)|^\frac{1}{2n}}{|\det(W\Sigma W^{T})|^\frac{1}{2k}}}_{Determinism Emergence}
```
To solve this problem, we will firstly discuss the upper bounds related with the two terms, the determinism emergence and degeneracy emergence.

## 2.example.ipynb

After knowing how to optimize causal emergence, we can use the theorems we derived to analyze several cases of linear stochastic iteration systems. We will attempt to search for the maximum of causal emergence in systems with known dynamics. We provide three cases, focusing on the applications of determinism emergence, degeneracy emergence, and the manifestation of causal emergence in $\mathcal{R}^3$ space.

![image](https://github.com/user-attachments/assets/0f425c57-d45d-48e7-b9d7-83d7190af6c9)


## 3.space.nb

To understand the physical meaning of the solution set, we can use a simple example in the three-dimensional space to visualize our optimal solution set. In specific cases, when $k=2, n=3$, the projection of $W$ in three-dimensional space is a circle. In this case, matrix $W=(w_1^{T},w_2^{T})^{T}\in \mathcal{R}^{2\times 3}$ can be split into two row-vectors, $w_i=(w_{i1},w_{i2},w_{i3}),i=1,2$, in $\mathcal{R}^3$, The eigenvector matrix $V=(v_1,v_2,v_3)\in \mathcal{R}^{3\times 3}$ can be regarded as the combining of three vectors, $v_j=(v_{1j},v_{2j},v_{3j})^T\in \mathcal{R}^3,j=1,2,3$. To visualize the solution set of $W$, we introduce the following case as $\epsilon=\exp(-2\eta)$.

![image](https://github.com/user-attachments/assets/38ec0c61-0fe3-40ef-80f6-bc348da362b3)

