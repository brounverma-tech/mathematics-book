<div align="center">

# 📘 Chapter 2: Types and Algebra of Matrices

### 🔵 Unit 1 — Algebra

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=flat-square)
![Language](https://img.shields.io/badge/Explanation-English%20%2B%20Hinglish-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Matrix ke important types aur addition, subtraction, scalar multiplication, product aur transpose ko clearly solve karna.

## 🎯 2.1 Learning Objectives

After completing this chapter, you will be able to identify matrix types, perform matrix operations, test whether a product exists, and use transpose properties.

## 🗣️ 2.2 Important Terms

| Term | Simple Meaning |
|---|---|
| Square matrix | Same number of rows and columns |
| Diagonal | Main diagonal ke outside all entries zero |
| Identity | Diagonal entries 1 and remaining entries 0 |
| Scalar | Equal diagonal entries |
| Transpose | Rows aur columns interchange karna |
| Symmetric | $A^T=A$ |
| Skew-symmetric | $A^T=-A$ |

## 2.3 Types of Matrices

### 2.3.1 Row Matrix

One row wali matrix:

$$A=[2\;5\;7].$$

### 2.3.2 Column Matrix

One column wali matrix:

$$A=\begin{bmatrix}2\\5\\7\end{bmatrix}.$$

### 2.3.3 Rectangular Matrix

Rows and columns unequal, such as $2\times3$.

### 2.3.4 Square Matrix

Rows = columns. A square matrix can have a determinant and inverse.

### 2.3.5 Zero or Null Matrix

Every element is zero. It is denoted by $O$.

### 2.3.6 Diagonal Matrix

A square matrix whose non-diagonal entries are zero:

$$
D=\begin{bmatrix}3&0&0\\0&-2&0\\0&0&5\end{bmatrix}.
$$

### 2.3.7 Scalar Matrix

A diagonal matrix with equal diagonal entries:

$$S=4I=\begin{bmatrix}4&0\\0&4\end{bmatrix}.$$

### 2.3.8 Identity Matrix

Diagonal entries are 1:

$$I_3=\begin{bmatrix}1&0&0\\0&1&0\\0&0&1\end{bmatrix}.$$

Identity multiplication does not change a compatible matrix: $AI=IA=A$.

### 2.3.9 Upper and Lower Triangular Matrices

- Upper triangular: entries below the main diagonal are zero.
- Lower triangular: entries above the main diagonal are zero.

### 2.3.10 Symmetric and Skew-Symmetric

$$A\text{ is symmetric if }A^T=A.$$

$$A\text{ is skew-symmetric if }A^T=-A.$$

Every diagonal element of a skew-symmetric matrix is zero.

## 2.4 Addition and Subtraction

Matrices must have the same order.

$$
(A\pm B)_{ij}=a_{ij}\pm b_{ij}.
$$

### 🧮 Solved Example 1

Let

$$A=\begin{bmatrix}1&2\\3&4\end{bmatrix},\quad B=\begin{bmatrix}5&-1\\2&0\end{bmatrix}.$$

Then

$$A+B=\begin{bmatrix}6&1\\5&4\end{bmatrix},$$

$$A-B=\begin{bmatrix}-4&3\\1&4\end{bmatrix}.$$

Important properties:

$$A+B=B+A,$$

$$A+(B+C)=(A+B)+C,$$

$$A+O=A.$$

## 2.5 Scalar Multiplication

Multiply every element by the scalar:

$$kA=[ka_{ij}].$$

For $A=\begin{bmatrix}1&-2\\0&3\end{bmatrix}$,

$$3A=\begin{bmatrix}3&-6\\0&9\end{bmatrix}.$$

## 2.6 Matrix Multiplication

If $A$ is $m\times n$ and $B$ is $n\times p$, then $AB$ exists and has order $m\times p$.

> **Inner dimensions must match; outer dimensions give the answer's order.**

$$
(AB)_{ij}=\sum_{k=1}^{n}a_{ik}b_{kj}.
$$

### 🧮 Solved Example 2

$$
A=\begin{bmatrix}1&2\\3&4\end{bmatrix},\quad
B=\begin{bmatrix}2&0\\1&5\end{bmatrix}.
$$

$$
AB=\begin{bmatrix}
1(2)+2(1)&1(0)+2(5)\\
3(2)+4(1)&3(0)+4(5)
\end{bmatrix}
=\begin{bmatrix}4&10\\10&20\end{bmatrix}.
$$

But

$$BA=\begin{bmatrix}2&4\\16&22\end{bmatrix}\ne AB.$$

Therefore matrix multiplication is generally not commutative.

Properties:

$$A(BC)=(AB)C,$$

$$A(B+C)=AB+AC,$$

$$AI=IA=A.$$

## 2.7 Transpose of a Matrix

Transpose is obtained by interchanging rows and columns.

$$
A=\begin{bmatrix}1&2&3\\4&5&6\end{bmatrix}
\Rightarrow
A^T=\begin{bmatrix}1&4\\2&5\\3&6\end{bmatrix}.
$$

Properties:

$$
(A^T)^T=A,\qquad (A+B)^T=A^T+B^T,
$$

$$
(kA)^T=kA^T,\qquad (AB)^T=B^TA^T.
$$

## 2.8 Symmetric–Skew Decomposition

Every square matrix $A$ can be written as

$$
A=\frac12(A+A^T)+\frac12(A-A^T).
$$

The first part is symmetric and the second part is skew-symmetric.

## 💡 2.9 Easy Tricks

- Addition: same order.
- Multiplication: inside same, outside answer.
- Product is row × column.
- Transpose of product reverses order: $(AB)^T=B^TA^T$.

## 🚫 2.10 Common Mistakes

1. Different-order matrices ko add karna.
2. Matrix product mein corresponding entries multiply karna.
3. $AB=BA$ assume karna.
4. Product ka incorrect order likhna.
5. $(AB)^T=A^TB^T$ likhna.

## 📌 2.11 Chapter Summary

Matrices are classified by shape and element pattern. Addition and subtraction require equal orders, while multiplication requires matching inner dimensions. Matrix multiplication is associative and distributive but usually not commutative. Transpose interchanges rows and columns and reverses the order of factors in a product.

## 🧠 2.12 Quick Revision

- Identity matrix behaves like number 1 in multiplication.
- Zero matrix behaves like 0 in addition.
- Diagonal → scalar → identity is a special-type hierarchy.
- Symmetric: $A^T=A$.
- Skew-symmetric: $A^T=-A$.
- $AB$ can exist even when $BA$ does not.

## 🎲 2.13 MCQs

1. Which operation requires equal matrix orders? **Answer: Addition**
2. A diagonal matrix with all diagonal entries 1 is called: **Answer: Identity matrix**
3. If $A$ is $2\times3$ and $B$ is $3\times4$, order of $AB$ is: **Answer: $2\times4$**
4. $(AB)^T$ equals: **Answer: $B^TA^T$**
5. Diagonal entries of a skew-symmetric matrix are: **Answer: Zero**

## 📝 2.14 Important Exam Questions

1. Explain any eight types of matrices with examples.
2. State and verify properties of transpose.
3. Multiply two given matrices and show that $AB\ne BA$.
4. Express a square matrix as the sum of symmetric and skew-symmetric matrices.
