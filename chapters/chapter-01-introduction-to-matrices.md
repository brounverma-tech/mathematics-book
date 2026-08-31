<div align="center">

# 📘 Chapter 1: Introduction to Matrices

### 🔵 Unit 1 — Algebra

![Level](https://img.shields.io/badge/Level-Beginner-brightgreen?style=flat-square)
![Language](https://img.shields.io/badge/Explanation-English%20%2B%20Hinglish-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-success?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Matrix ka meaning, notation, order, elements aur equality ko zero level se samajhna.

## 🎯 1.1 Learning Objectives

Is chapter ko complete karne ke baad aap:

1. Matrix ko define kar sakenge.
2. Rows, columns, order aur elements identify kar sakenge.
3. Matrix notation $A=[a_{ij}]$ samajh sakenge.
4. Two matrices ki equality test kar sakenge.
5. Real-life data ko matrix form mein represent kar sakenge.

## 🗣️ 1.2 Difficult Words: Pronunciation and Meaning

| Word | Pronunciation | Simple Meaning |
|---|---|---|
| Matrix | मैट्रिक्स | Numbers ka rectangular arrangement |
| Row | रो | Horizontal line |
| Column | कॉलम | Vertical line |
| Element | एलिमेंट | Matrix ke andar ek value |
| Order | ऑर्डर | Rows × columns |
| Rectangular | रेक्टैंगुलर | Aayatakar arrangement |
| Corresponding | कॉरिस्पॉन्डिंग | Same position par present |

## 💡 1.3 Meaning of a Matrix

### 1.3.1 English Definition

> A matrix is a rectangular arrangement of numbers, symbols or expressions organized in horizontal rows and vertical columns.

### 1.3.2 Hinglish Explanation

Matrix numbers ko **rows aur columns** mein arrange karne ka systematic method hai. Jaise class ke students ke marks ko table mein likha jata hai, waise hi mathematical table ko matrix form mein show kiya ja sakta hai.

Example:

$$
A=\begin{bmatrix}
2&5&7\\
1&4&9
\end{bmatrix}
$$

Is matrix mein 2 horizontal rows aur 3 vertical columns hain.

## 1.4 Rows, Columns and Order

### 1.4.1 Row

Matrix ki horizontal arrangement ko row kehte hain.

For $A$ above:

- First row: $2,5,7$
- Second row: $1,4,9$

### 1.4.2 Column

Matrix ki vertical arrangement ko column kehte hain.

- First column: $2,1$
- Second column: $5,4$
- Third column: $7,9$

### 1.4.3 Order of a Matrix

If a matrix has $m$ rows and $n$ columns, its order is

$$
m\times n.
$$

Therefore, matrix $A$ has order $2\times3$.

> [!IMPORTANT]
> Order likhte time **rows first** aur **columns second** likhe jate hain.

## 1.5 Matrix Notation

A matrix is commonly represented by a capital letter:

$$
A=[a_{ij}]_{m\times n}.
$$

Here:

- $A$ = matrix name
- $a_{ij}$ = element in row $i$ and column $j$
- $m$ = number of rows
- $n$ = number of columns

For

$$
B=\begin{bmatrix}3&8\\6&1\\4&7\end{bmatrix},
$$

$b_{21}=6$ because 6 lies in the second row and first column. Similarly, $b_{32}=7$.

## 1.6 General Form of a Matrix

An $m\times n$ matrix can be written as

$$
A=\begin{bmatrix}
a_{11}&a_{12}&\cdots&a_{1n}\\
a_{21}&a_{22}&\cdots&a_{2n}\\
\vdots&\vdots&\ddots&\vdots\\
a_{m1}&a_{m2}&\cdots&a_{mn}
\end{bmatrix}.
$$

Total number of elements is

$$
m\times n.
$$

## 1.7 Equality of Matrices

### 1.7.1 Condition

Two matrices $A$ and $B$ are equal when:

1. They have the same order.
2. Their corresponding elements are equal.

Symbolically,

$$
A=B\iff a_{ij}=b_{ij}\text{ for every }i,j.
$$

### 🧮 Solved Example 1

If

$$
\begin{bmatrix}x&2\\3&y\end{bmatrix}
=\begin{bmatrix}5&2\\3&7\end{bmatrix},
$$

find $x$ and $y$.

**Solution:** Corresponding elements must be equal.

$$x=5,\qquad y=7.$$

### 🧮 Solved Example 2

Can a $2\times3$ matrix be equal to a $3\times2$ matrix?

**Solution:** No. Their orders are different, so they cannot be equal even if they contain the same numbers.

## 1.8 Formation of a Matrix from a Rule

### 🧮 Solved Example 3

Form a $2\times3$ matrix $A=[a_{ij}]$ where $a_{ij}=2i+j$.

**Solution:**

$$
a_{11}=2(1)+1=3,\quad a_{12}=4,\quad a_{13}=5,
$$

$$
a_{21}=2(2)+1=5,\quad a_{22}=6,\quad a_{23}=7.
$$

Therefore,

$$
A=\begin{bmatrix}3&4&5\\5&6&7\end{bmatrix}.
$$

## 1.9 Real-Life Applications

Matrices are used in:

1. Student marks and attendance records
2. Computer graphics and image processing
3. Business sales and inventory data
4. Network connections
5. Scientific calculations
6. Machine learning and data analysis
7. Solving simultaneous equations

### Example: Marks Matrix

Suppose three students have marks in Mathematics and Programming:

$$
M=\begin{bmatrix}
75&82\\
68&91\\
88&79
\end{bmatrix}.
$$

Rows represent students and columns represent subjects. Entry $m_{21}=68$ is the second student's Mathematics mark.

## 💡 1.10 Easy Tricks

- **RC Trick:** Row first, Column second.
- $a_{23}$ means row 2, column 3 - not the opposite.
- Total elements = rows × columns.
- Equality means same size + same position values.

## 🚫 1.11 Common Mistakes

1. Order ko columns × rows likhna.
2. $a_{ij}$ mein $i$ aur $j$ ko reverse karna.
3. Different orders wali matrices ko equal maan lena.
4. Total elements ko rows + columns calculate karna.
5. Square brackets ke andar rows ko incorrectly separate karna.

## 📌 1.12 Chapter Summary

A matrix is a rectangular arrangement of elements in rows and columns. Its order is written as number of rows × number of columns. The symbol $a_{ij}$ identifies the element in row $i$ and column $j$. Two matrices are equal only when they have the same order and equal corresponding elements. Matrices provide a compact method for representing and processing organized data.

## 🧠 1.13 Quick Revision

- Matrix = rectangular arrangement.
- Horizontal lines = rows.
- Vertical lines = columns.
- Order = rows × columns.
- $a_{ij}$ = element at row $i$, column $j$.
- Total elements in $m\times n$ matrix = $mn$.
- Equal matrices must have the same order and corresponding entries.

## 🎲 1.14 Multiple-Choice Questions

1. A matrix with 3 rows and 4 columns has order:  
   A. $4\times3$  B. $3\times4$  C. 7  D. 12  
   **Answer:** B

2. In $a_{32}$, the element lies in:  
   A. Row 2, column 3  B. Row 3, column 2  C. Row 3 only  D. Column 2 only  
   **Answer:** B

3. A $2\times5$ matrix contains:  
   A. 7 elements  B. 10 elements  C. 25 elements  D. 3 elements  
   **Answer:** B

4. Two matrices can be equal only when:  
   A. Their determinants are equal  B. Their orders and corresponding entries are equal  C. Their rows are equal  D. Their names are equal  
   **Answer:** B

## 📝 1.15 Important Exam Questions

### Short Answer

1. Define a matrix with an example.
2. Explain order and element notation.
3. State the conditions for equality of matrices.

### Long Answer

1. Explain matrix notation, order, elements and equality with suitable examples.
2. Form a $3\times2$ matrix using $a_{ij}=i+2j$.

### Numerical Practice

1. If $A=[a_{ij}]_{3\times3}$ and $a_{ij}=i-j$, write matrix $A$.
2. Find $x,y,z$ if two given matrices with these variables are equal.
