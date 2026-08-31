<div align="center">

# 📘 Chapter 3: Determinants, Minors and Cofactors

### 🔵 Unit 1 — Algebra

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Calculation-orange?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Determinant calculate karna, minors/cofactors find karna aur properties se calculations short karna.

## 🎯 3.1 Learning Objectives

You will learn the determinant of $2\times2$ and $3\times3$ matrices, minors, cofactors, expansion, properties, singularity and applications.

## 🗣️ 3.2 Important Terms

| Term | Meaning |
|---|---|
| Determinant | Square matrix se associated scalar value |
| Minor | One row and one column delete karke bacha determinant |
| Cofactor | Signed minor |
| Expansion | Row/column se determinant evaluate karna |
| Singular | Determinant zero |
| Non-singular | Determinant non-zero |

## 3.3 Determinant of a $2\times2$ Matrix

For

$$A=\begin{bmatrix}a&b\\c&d\end{bmatrix},$$

$$|A|=ad-bc.$$

### 🧮 Solved Example 1

$$
\begin{vmatrix}3&2\\5&4\end{vmatrix}=3(4)-2(5)=12-10=2.
$$

## 3.4 Determinant of a $3\times3$ Matrix

For

$$A=\begin{bmatrix}a&b&c\\d&e&f\\g&h&i\end{bmatrix},$$

expansion along the first row gives

$$
|A|=a(ei-fh)-b(di-fg)+c(dh-eg).
$$

### 🧮 Solved Example 2

Evaluate

$$
\begin{vmatrix}1&2&3\\0&4&5\\1&0&6\end{vmatrix}.
$$

$$
=1(24-0)-2(0-5)+3(0-4)
$$

$$=24+10-12=22.$$

## 3.5 Minor of an Element

The minor $M_{ij}$ is found by deleting row $i$ and column $j$.

For

$$A=\begin{bmatrix}1&2&3\\4&5&6\\7&8&9\end{bmatrix},$$

$$M_{23}=\begin{vmatrix}1&2\\7&8\end{vmatrix}=8-14=-6.$$

## 3.6 Cofactor of an Element

$$C_{ij}=(-1)^{i+j}M_{ij}.$$

Sign pattern:

$$
\begin{bmatrix}+&-&+\\-&+&-\\+&-&+\end{bmatrix}.
$$

Since position $(2,3)$ has a negative sign,

$$C_{23}=-M_{23}=6.$$

## 3.7 Cofactor Expansion

A determinant may be expanded along any row or column:

$$|A|=a_{i1}C_{i1}+a_{i2}C_{i2}+\cdots+a_{in}C_{in}.$$

> Choose the row or column containing maximum zeros. Isse calculation fast aur safe hoti hai.

## 3.8 Properties of Determinants

1. $\det(A^T)=\det(A)$.
2. Interchanging two rows or columns changes the sign.
3. Equal or proportional rows/columns make the determinant zero.
4. If one row/column is all zero, determinant is zero.
5. Multiplying one row by $k$ multiplies the determinant by $k$.
6. $R_i\to R_i+kR_j$ does not change the determinant.
7. For triangular matrices, determinant = product of diagonal entries.
8. $\det(AB)=\det(A)\det(B)$.
9. $\det(I)=1$.

### 🧮 Solved Example 3: Property Method

$$
D=\begin{vmatrix}1&2&3\\2&4&6\\4&5&6\end{vmatrix}.
$$

Second row is twice the first row. Therefore, $D=0$ without expansion.

### 🧮 Solved Example 4: Triangular Matrix

$$
\begin{vmatrix}2&1&4\\0&3&5\\0&0&-2\end{vmatrix}
=2(3)(-2)=-12.
$$

## 3.9 Singular and Non-Singular Matrices

For a square matrix $A$:

- $|A|=0$ → singular → inverse does not exist.
- $|A|\ne0$ → non-singular → inverse exists.

## 3.10 Application: Area of a Triangle

For vertices $(x_1,y_1)$, $(x_2,y_2)$ and $(x_3,y_3)$,

$$
\text{Area}=\frac12\left|
\begin{vmatrix}
x_1&y_1&1\\x_2&y_2&1\\x_3&y_3&1
\end{vmatrix}\right|.
$$

### 🧮 Solved Example 5

Find the area of the triangle $(0,0)$, $(4,0)$ and $(2,3)$.

$$
\text{Area}=\frac12\left|0-0+4(3)\right|=6\text{ square units}.
$$

## 💡 3.11 Easy Tricks

- $2\times2$: cross multiply and subtract.
- Cofactor signs start with plus and alternate.
- Zero-heavy row/column se expansion karein.
- Proportional rows dikhein to answer directly zero.

## 🚫 3.12 Common Mistakes

1. Minor aur cofactor ko same samajhna.
2. Middle term ka minus sign miss karna.
3. Wrong row/column delete karna.
4. Row interchange ke baad determinant sign change na karna.
5. Non-square matrix ka determinant calculate karna.

## 📌 3.13 Chapter Summary

A determinant is a scalar defined for square matrices. Minors are smaller determinants obtained by deletion, and cofactors attach alternating signs to minors. Cofactor expansion evaluates larger determinants. Determinant properties often reduce calculation. A zero determinant identifies a singular matrix, while a non-zero determinant guarantees invertibility.

## 🧠 3.14 Quick Revision

- $2\times2$ determinant = $ad-bc$.
- $C_{ij}=(-1)^{i+j}M_{ij}$.
- Sign pattern: $+,-,+$ / $-,+,-$ / $+,-,+$.
- Equal/proportional rows → determinant 0.
- Triangular determinant → diagonal product.
- $|A|\ne0$ → inverse exists.

## 🎲 3.15 MCQs

1. Determinant is defined for: **Answer: Square matrices**
2. $C_{12}$ has which sign? **Answer: Negative**
3. If two rows are equal, determinant is: **Answer: Zero**
4. Determinant of identity matrix is: **Answer: 1**
5. A matrix with determinant zero is: **Answer: Singular**

## 📝 3.16 Important Exam Questions

1. Define minor and cofactor with an example.
2. Evaluate a $3\times3$ determinant by cofactor expansion.
3. State and explain any six properties of determinants.
4. Prove that a determinant is zero when two rows are proportional.
5. Find the area of a triangle using determinants.
