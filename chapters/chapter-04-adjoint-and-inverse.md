<div align="center">

# 📘 Chapter 4: Adjoint and Inverse of a Matrix

### 🔵 Unit 1 — Algebra

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Inverse-orange?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Adjoint form karna aur matrix inverse ko adjoint aur row-operation methods se calculate karna.

## 🎯 4.1 Learning Objectives

You will learn the cofactor matrix, adjoint, inverse, inverse properties, Gauss-Jordan method and matrix equations.

## 4.2 Meaning of Inverse

### English Definition

> The inverse of a square matrix $A$ is a matrix $A^{-1}$ such that $AA^{-1}=A^{-1}A=I$.

### Hinglish Explanation

Number ke case mein $a\cdot(1/a)=1$ hota hai. Matrix ke case mein inverse ke saath multiplication karne par identity matrix milti hai.

Inverse exists only if

$$|A|\ne0.$$

## 4.3 Cofactor Matrix and Adjoint

First calculate every cofactor:

$$C=[C_{ij}].$$

Then transpose the cofactor matrix:

$$\operatorname{adj}(A)=C^T.$$

## 4.4 Inverse by Adjoint Method

$$
A^{-1}=\frac{\operatorname{adj}(A)}{|A|},\qquad |A|\ne0.
$$

For a $2\times2$ matrix,

$$
A=\begin{bmatrix}a&b\\c&d\end{bmatrix},
$$

$$
A^{-1}=\frac1{ad-bc}\begin{bmatrix}d&-b\\-c&a\end{bmatrix}.
$$

### 🧮 Solved Example 1

Find the inverse of

$$A=\begin{bmatrix}2&1\\5&3\end{bmatrix}.$$

**Step 1: Determinant**

$$|A|=2(3)-1(5)=1.$$

**Step 2: Interchange diagonal entries and change signs of off-diagonal entries**

$$
\operatorname{adj}(A)=\begin{bmatrix}3&-1\\-5&2\end{bmatrix}.
$$

**Step 3: Divide by determinant**

$$
A^{-1}=\begin{bmatrix}3&-1\\-5&2\end{bmatrix}.
$$

## 4.5 Verification of Inverse

Always check one product:

$$AA^{-1}=I.$$

This catches sign and arithmetic mistakes.

## 4.6 Inverse by Gauss-Jordan Method

Write the augmented matrix:

$$[A\mid I].$$

Apply elementary row operations until the left side becomes identity:

$$[A\mid I]\longrightarrow[I\mid A^{-1}].$$

### 🧮 Solved Example 2

For

$$A=\begin{bmatrix}1&1\\2&3\end{bmatrix},$$

start with

$$
\left[\begin{array}{cc|cc}1&1&1&0\\2&3&0&1\end{array}\right].
$$

Apply $R_2\to R_2-2R_1$:

$$
\left[\begin{array}{cc|cc}1&1&1&0\\0&1&-2&1\end{array}\right].
$$

Apply $R_1\to R_1-R_2$:

$$
\left[\begin{array}{cc|cc}1&0&3&-1\\0&1&-2&1\end{array}\right].
$$

Therefore,

$$A^{-1}=\begin{bmatrix}3&-1\\-2&1\end{bmatrix}.$$

## 4.7 Properties of Inverse

$$
(A^{-1})^{-1}=A,
$$

$$
(AB)^{-1}=B^{-1}A^{-1},
$$

$$
(A^T)^{-1}=(A^{-1})^T,
$$

$$
(kA)^{-1}=\frac1kA^{-1}\quad(k\ne0),
$$

$$
|A^{-1}|=\frac1{|A|}.
$$

## 4.8 Solving Matrix Equations

If $AX=B$, multiply by $A^{-1}$ on the left:

$$X=A^{-1}B.$$

If $XA=B$, multiply by $A^{-1}$ on the right:

$$X=BA^{-1}.$$

> Order cannot be changed because matrix multiplication is not commutative.

## 4.9 Applications

Matrix inverse is used in systems of equations, computer graphics, coordinate changes, encryption, data science and numerical modelling.

## 💡 4.10 Easy Tricks

- Determinant first; if zero, stop.
- $2\times2$: swap main diagonal, change off-diagonal signs.
- Product inverse reverses order.
- Final answer ko identity multiplication se verify karein.

## 🚫 4.11 Common Mistakes

1. Determinant check kiye bina inverse calculate karna.
2. Cofactor matrix ko transpose na karna.
3. $(AB)^{-1}=A^{-1}B^{-1}$ likhna.
4. Matrix equation mein wrong side se multiply karna.
5. Row operations only on left half apply karna.

## 📌 4.12 Chapter Summary

The inverse of a non-singular square matrix reverses the effect of the matrix. It can be found through the adjoint formula or Gauss-Jordan row reduction. The determinant decides whether an inverse exists. Inverse properties preserve transpose and reverse product order.

## 🧠 4.13 Quick Revision

- Inverse condition: $|A|\ne0$.
- Adjoint = transpose of cofactor matrix.
- $A^{-1}=\operatorname{adj}(A)/|A|$.
- $[A|I]\to[I|A^{-1}]$.
- $AX=B\Rightarrow X=A^{-1}B$.

## 🎲 4.14 MCQs

1. Inverse exists when determinant is: **Answer: Non-zero**
2. Adjoint is the transpose of: **Answer: Cofactor matrix**
3. $(AB)^{-1}$ equals: **Answer: $B^{-1}A^{-1}$**
4. $AA^{-1}$ equals: **Answer: $I$**

## 📝 4.15 Important Exam Questions

1. Define adjoint and inverse.
2. Find inverse of a $3\times3$ matrix by adjoint method.
3. Find inverse using elementary row operations.
4. Prove $(AB)^{-1}=B^{-1}A^{-1}$.
5. Solve a matrix equation of the form $AX=B$.
