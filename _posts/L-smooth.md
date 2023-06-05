#L_Smooth #L-Lipschitz
# L-smooth and L-Lipschitz continuous

> [(57条消息) L-smooth，L-Lipschiz continuous，continuously differentiable含义理解和区分_SLUMBER_PARTY_的博客-CSDN博客](https://blog.csdn.net/nanfeizhenkuangou/article/details/112655424)


> **L-Lipschitz continuous**: concerns whether the $f(x)$ is smooth (often stronger than simple smoothness verification)
> **L-smooth:** concerns whether $\nabla f(x)$ is L-smooth

# **L-Lipschitz continuous** Definition
Define a function $g: \mathbb{R}^N\rightarrow \mathbb{R}^{M}$ is **L-Lipschitz continuous** if there exists $L < \infty$ , such that 
$$
\Vert{ g(x)-g(z)\Vert}\leq L\cdot\Vert x-z \Vert , \forall x,z\in\mathbb{R}^{N}
$$
# **L-smooth** Definition
Define a differentiable function $f(x)$ L-smooth if it has a **L-Lipschitz continuous** gradient, i.e.,
$$
\exists L < \infty , \Vert \nabla f(x)- \nabla f(z)\Vert_2 \leq L\Vert x-z\Vert_2 \forall x,z\in\mathbb{R}^{N}
$$

**L-smooth is stronger than L-L**!



