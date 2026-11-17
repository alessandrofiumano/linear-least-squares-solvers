
# Project 20 (Non-ML)

(P) is the linear least squares problem

$$
\min_{w} \|Xw-y\|
$$

where $X$ is the (tall thin) matrix from the ML-cup dataset by prof. Micheli, and $y$ is a random vector.

(A1) is thin QR factorization with Householder reflectors (lecture 10)

(A2) is LDL factorization with pivoting applied to the square symmetric linear system

$$
\begin{bmatrix}
I & X \\
X^T & 0
\end{bmatrix}
\begin{bmatrix}
r \\
w
\end{bmatrix}
=
\begin{bmatrix}
y \\
0
\end{bmatrix}
$$

*(augmented system).*

No off-the-shelf solvers allowed.
