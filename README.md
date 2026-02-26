# Numerical Methods for Nonlinear Systems

This repository is based on the research work:

"Numerical Methods for Solving Systems of Nonlinear Equations"

It presents theoretical foundations and computational implementations of classical numerical methods used to solve:

- Systems of nonlinear equations
- Nonlinear boundary value problems

---

## Implemented Methods

### 1. Newton Method (Multivariable)
- Uses the Jacobian matrix
- Quadratic convergence
- Linear system solved at each iteration

### 2. Broyden Method (Quasi-Newton)
- Jacobian-free update strategy
- Sherman–Morrison formula
- Superlinear convergence

### 3. Finite Difference Method
- Discretization of nonlinear boundary value problems
- Tridiagonal Jacobian structure
- LU factorization (Crout method)

---

## Mathematical Background

The project covers:

- Nonlinear systems definition
- Convergence orders
- Jacobian and Hessian matrices
- Vector norms (L2 and L∞)

---

## Project Structure (Initial Version)

src/ → Core implementations  
docs/ → Research document and theory  
notebooks/ → Numerical demonstrations  

---

## Author

Mathurin Nkinassi Dougoua  
MSc Mathematical & Computational Finance  
Université de Montréal
