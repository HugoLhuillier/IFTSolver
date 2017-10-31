# Two dimensional root solver in Julia

-------

<div style="text-align:center">:rotating_light: Work is in progress :rotating_light: </div>

-------

This package contains a routine for finding the roots of a two dimensional system. It is based on [Graspa and Vrahatis (1989)](https://www.math.upatras.gr/~vrahatis/papers/journals/GrapsaV89_INT_J_COMPUT_MATH_28_pp171-181_1989.pdf).

The key idea is to transform the two dimensional problem into a one dimensional problem one via the implicit function theorem, and to then use common 1D solvers to solve the problem, e.g. [Roots.jl](https://github.com/JuliaMath/Roots.jl). The main goal is to improve the robustness of 2D root solver.

# References

* Graspa, T. N. and Vrahatis, M. N. (1989). [The implicit function theorem for solving systems of nonlinear equations in R2](https://www.math.upatras.gr/~vrahatis/papers/journals/GrapsaV89_INT_J_COMPUT_MATH_28_pp171-181_1989.pdf). *International journal of computer mathematics*, 28(1-4):171-181.
