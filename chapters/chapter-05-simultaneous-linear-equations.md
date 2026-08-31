<div align="center">

# 📘 Chapter 5: Simultaneous Linear Equations

### 🔵 Unit 1 — Algebra

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Methods](https://img.shields.io/badge/Methods-Matrix%20%7C%20Cramer%20%7C%20Gauss-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Simultaneous equations ko matrix, inverse, Cramer's rule, Gaussian elimination aur consistency method se solve karna.

## 🎯 5.1 Learning Objectives

You will convert equations to matrix form, solve them by different methods and classify systems as unique, inconsistent or infinitely solvable.

## 5.2 Linear Equation and System

A linear equation in variables $x,y,z$ has each variable to power one, such as

$$2x+3y-z=5.$$

Two or more equations considered together form a simultaneous system.

## 5.3 Matrix Form

The system

$$
a_1x+b_1y=c_1,
$$

$$
a_2x+b_2y=c_2
$$

can be written as

$$AX=B,$$

where

$$
A=\begin{bmatrix}a_1&b_1\\a_2&b_2\end{bmatrix},\quad
X=\begin{bmatrix}x\\y\end{bmatrix},\quad
B=\begin{bmatrix}c_1\\c_2\end{bmatrix}.
$$

## 5.4 Inverse Matrix Method

If $|A|\ne0$,

$$X=A^{-1}B.$$

### 🧮 Solved Example 1

Solve

$$x+y=5,\qquad 2x+3y=12.$$

$$
A=\begin{bmatrix}1&1\\2&3\end{bmatrix},\quad
A^{-1}=\begin{bmatrix}3&-1\\-2&1\end{bmatrix}.
$$

$$
X=A^{-1}B
=\begin{bmatrix}3&-1\\-2&1\end{bmatrix}
\begin{bmatrix}5\\12\end{bmatrix}
=\begin{bmatrix}3\\2\end{bmatrix}.
$$

Therefore, $x=3$ and $y=2$.

## 5.5 Cramer's Rule

For $AX=B$ with $\Delta=|A|\ne0$,

$$x_i=\frac{\Delta_i}{\Delta}.$$

For two variables,

$$
\Delta=\begin{vmatrix}a_1&b_1\\a_2&b_2\end{vmatrix},
$$

$$
\Delta_x=\begin{vmatrix}c_1&b_1\\c_2&b_2\end{vmatrix},\qquad
\Delta_y=\begin{vmatrix}a_1&c_1\\a_2&c_2\end{vmatrix}.
$$

Then

$$x=\frac{\Delta_x}{\Delta},\qquad y=\frac{\Delta_y}{\Delta}.$$

### 🧮 Solved Example 2

For the same system,

$$\Delta=1,quad\Delta_x=3,quad\Delta_y=2.$$

Therefore $x=3$, $y=2$.

## 5.6 Gaussian Elimination

Use row operations on the augmented matrix $[A|B]$ to create an upper-triangular system, then use back substitution.

### 🧮 Solved Example 3

Solve

$$x+y+z=6,$$

$$2x-y+z=3,$$

$$x+2y-z=2.$$

Augmented matrix:

$$
\left[\begin{array}{ccc|c}
1&1&1&6\\
2&-1&1&3\\
1&2&-1&2
\end{array}\right].
$$

Apply $R_2\to R_2-2R_1$ and $R_3\to R_3-R_1$:

$$
\left[\begin{array}{ccc|c}
1&1&1&6\\
0&-3&-1&-9\\
0&1&-2&-4
\end{array}\right].
$$

Replace $R_2\leftrightarrow R_3$, then eliminate $y$ from row 3:

$$
\left[\begin{array}{ccc|c}
1&1&1&6\\
0&1&-2&-4\\
0&0&-7&-21
\end{array}\right].
$$

Thus $z=3$, $y=2$ and $x=1$.

## 5.7 Gauss-Jordan Method

Continue row operations until the coefficient matrix reaches reduced row-echelon form. The solution is then read directly.

## 5.8 Consistency and Rank

For $AX=B$:

- Unique solution: $\operatorname{rank}(A)=\operatorname{rank}([A|B])=$ number of unknowns.
- Infinitely many solutions: equal ranks, but common rank < number of unknowns.
- No solution: $\operatorname{rank}(A)\ne\operatorname{rank}([A|B])$.

### Simple Interpretation

- Two different intersecting lines → one solution.
- Same line → infinitely many solutions.
- Parallel distinct lines → no solution.

## 5.9 Method Selection

| Situation | Recommended Method |
|---|---|
| Small square system | Cramer or inverse |
| Large system | Gaussian elimination |
| Rank or RREF needed | Gauss-Jordan |
| Singular system | Rank/consistency test |

## 💡 5.10 Easy Tricks

- Variables ka order har equation mein same rakhein.
- Missing variable ka coefficient zero hota hai.
- Cramer's rule mein correct column replace karein.
- Final values ko original equations mein substitute karke check karein.

## 🚫 5.11 Common Mistakes

1. Constant ko coefficient matrix mein include karna.
2. Row operation only coefficient side par apply karna.
3. Cramer's rule when $\Delta=0$ use karna.
4. Back substitution ka order wrong rakhna.
5. Ranks calculate kiye bina consistency decide karna.

## 📌 5.12 Chapter Summary

Simultaneous linear equations can be represented compactly as $AX=B$. A non-singular square system has a unique solution obtainable by inverse or Cramer's rule. Gaussian and Gauss-Jordan elimination use elementary row operations and work efficiently for larger systems. Rank comparison identifies unique, infinite and inconsistent systems.

## 🧠 5.13 Quick Revision

- Matrix form: $AX=B$.
- Inverse method: $X=A^{-1}B$.
- Cramer: $x_i=\Delta_i/\Delta$.
- Gaussian method → upper triangular + back substitution.
- Unequal ranks → no solution.

## 🎲 5.14 MCQs

1. In $AX=B$, $X$ contains: **Answer: Unknown variables**
2. Cramer's rule requires: **Answer: $\Delta\ne0$**
3. Gaussian elimination creates: **Answer: Upper-triangular form**
4. Unequal coefficient and augmented ranks mean: **Answer: No solution**

## 📝 5.15 Important Exam Questions

1. Solve a $3\times3$ system by Cramer's rule.
2. Solve simultaneous equations using inverse matrix method.
3. Explain Gaussian and Gauss-Jordan methods.
4. State the rank conditions for consistency.
5. Compare different methods of solving linear systems.
