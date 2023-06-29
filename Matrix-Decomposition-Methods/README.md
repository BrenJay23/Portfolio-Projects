# Matrix Decomposition Methods using NumPy
## Introduction
This repository provides an implementation of various matrix decomposition methods using the NumPy library. Matrix decomposition is a fundamental technique in linear algebra that decomposes a matrix into a product of simpler matrices. These decomposition methods play a crucial role in various applications, including solving linear systems, eigenvalue computations, least squares fitting, and data compression, which are vital for understanding AI algorithms.
## Implemented Algorithms
The repository offers the following matrix decomposition algorithms:
1. **Gaussian Elimination:** This algorithm transforms a matrix into row-echelon form by performing a sequence of elementary row operations. It is commonly used to solve systems of linear equations.
2. **LU Decomposition:** LU decomposition factors a matrix into the product of a lower triangular matrix (L) and an upper triangular matrix (U). It is widely used for solving systems of linear equations, matrix inversion, and computing determinants.
3. **QR Decomposition:** QR decomposition decomposes a matrix into the product of an orthogonal matrix (Q) and an upper triangular matrix (R). It is employed for solving least squares problems, eigenvalue computations, and numerical stability.
4. **Householder Reflections:** This method uses Householder reflections to reduce a matrix to tridiagonal or bidiagonal form. It is useful for eigenvalue computations, matrix diagonalization, and symmetric matrix reduction.
5. **QR Algorithm with Givens Rotation:** The QR algorithm iteratively applies QR decomposition using Givens rotation to compute eigenvalues and eigenvectors of a matrix. It is a powerful method for eigenvalue computations and diagonalization.
6. **Singular Value Decomposition (SVD):** SVD decomposes a matrix into the product of three matrices: U, Σ, and Vᵀ. It is widely used in data compression, image processing, and dimensionality reduction.
