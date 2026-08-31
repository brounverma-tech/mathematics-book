<div align="center">

# 📘 Chapter 15: Introduction and Algebra of Complex Numbers

### 🔴 Unit 4 — Complex Theory

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Complex%20Algebra-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Complex number ka meaning, algebra, conjugate, modulus, argument aur geometrical representation samajhna.

## 🎯 15.1 Learning Objectives

You will identify real and imaginary parts, perform four algebraic operations, use conjugates, find modulus/argument and represent sum and difference geometrically.

## 🗣️ 15.2 Important Terms

| Term | Meaning |
|---|---|
| Imaginary unit | $i$ where $i^2=-1$ |
| Real part | $a$ in $a+ib$ |
| Imaginary part | $b$ in $a+ib$ |
| Conjugate | Imaginary sign reversed |
| Modulus | Origin se distance |
| Argument/Amplitude | Positive real axis se angle |
| Argand plane | Complex numbers ka coordinate plane |

## 15.3 Need for Complex Numbers

The equation

$$x^2+1=0$$

gives

$$x^2=-1.$$

No real number has square $-1$. We define

$$i=\sqrt{-1},\qquad i^2=-1.$$

## 15.4 Standard Form

### English Definition

> A complex number is a number of the form $z=a+ib$, where $a,b\in\mathbb R$ and $i^2=-1$.

$$\operatorname{Re}(z)=a,\qquad\operatorname{Im}(z)=b.$$

### Hinglish Explanation

Complex number real aur imaginary components ko combine karta hai. $a$ real part hai aur $b$ imaginary coefficient.

For $z=3-5i$:

$$\operatorname{Re}(z)=3,\qquad\operatorname{Im}(z)=-5.$$

## 15.5 Types of Complex Numbers

- Purely real: $b=0$.
- Purely imaginary: $a=0$ and $b\ne0$.
- Zero complex number: $a=b=0$.
- Equal complex numbers: real parts equal and imaginary parts equal.

## 15.6 Powers of $i$

$$
i^0=1,\quad i^1=i,\quad i^2=-1,\quad i^3=-i,\quad i^4=1.
$$

The cycle repeats every 4.

### 🧮 Solved Example 1

Find $i^{47}$.

Divide exponent by 4. Remainder is 3, so

$$i^{47}=i^3=-i.$$

## 15.7 Addition and Subtraction

For $z_1=a+ib$, $z_2=c+id$:

$$
z_1+z_2=(a+c)+i(b+d),
$$

$$
z_1-z_2=(a-c)+i(b-d).
$$

### 🧮 Solved Example 2

If $z_1=3+4i$ and $z_2=1-2i$,

$$z_1+z_2=4+2i,$$

$$z_1-z_2=2+6i.$$

## 15.8 Multiplication

$$
(a+ib)(c+id)=(ac-bd)+i(ad+bc).
$$

### 🧮 Solved Example 3

$$
(2+3i)(1-4i)=2-8i+3i-12i^2=14-5i.
$$

## 15.9 Conjugate

The conjugate of $z=a+ib$ is

$$\bar z=a-ib.$$

Properties:

$$z+\bar z=2\operatorname{Re}(z),$$

$$z-\bar z=2i\operatorname{Im}(z),$$

$$z\bar z=a^2+b^2=|z|^2,$$

$$\overline{z_1z_2}=\bar z_1\bar z_2.$$

## 15.10 Division

Multiply numerator and denominator by the denominator's conjugate:

$$
\frac{a+ib}{c+id}
=\frac{(a+ib)(c-id)}{c^2+d^2}.
$$

### 🧮 Solved Example 4

$$
\frac{3+i}{2-i}
=\frac{(3+i)(2+i)}{(2-i)(2+i)}
=\frac{5+5i}{5}=1+i.
$$

## 15.11 Modulus

For $z=a+ib$,

$$|z|=\sqrt{a^2+b^2}.$$

Properties:

$$|z_1z_2|=|z_1||z_2|,$$

$$\left|\frac{z_1}{z_2}\right|=\frac{|z_1|}{|z_2|},$$

$$|z_1+z_2|\le|z_1|+|z_2|.$$

For $z\ne0$,

$$
\frac1z=\frac{\bar z}{|z|^2}.
$$

### 🧮 Solved Example 5

For $z=3+4i$,

$$|z|=5,\qquad \bar z=3-4i,\qquad \frac1z=\frac{3-4i}{25}.$$

## 15.12 Argand Plane and Argument

$z=a+ib$ is represented by point $(a,b)$.

- Horizontal axis = real axis.
- Vertical axis = imaginary axis.
- Modulus = distance from origin.
- Argument $\theta$ = angle from positive real axis.

The argument must be chosen according to the quadrant.

## 15.13 Geometrical Sum and Difference

- $z_1+z_2$ follows vector/parallelogram addition.
- $z_1-z_2$ is the vector from the point $z_2$ to the point $z_1$.
- $|z_1-z_2|$ is the distance between points $z_1$ and $z_2$.

### Locus Example

$$|z-(2+i)|=3$$

represents a circle with centre $(2,1)$ and radius 3.

## 💡 15.14 Easy Tricks

- Powers of $i$: exponent mod 4.
- Division: denominator conjugate multiply.
- Modulus follows Pythagoras.
- $|z-z_0|=r$ means circle centred at $z_0$.

## 🚫 15.15 Common Mistakes

1. Imaginary part ko $ib$ likhna instead of $b$.
2. $i^2=1$ use karna.
3. Division mein only denominator ko conjugate multiply karna.
4. Argument ka quadrant ignore karna.
5. Conjugate mein real part ka sign change karna.

## 📌 15.16 Chapter Summary

Complex numbers extend the real system through $i^2=-1$. Algebra is performed by combining real and imaginary parts. Conjugation helps division, modulus measures distance and argument measures direction. On the Argand plane, complex addition and subtraction behave like vector operations.

## 🧠 15.17 Quick Revision

- $z=a+ib$.
- $i^2=-1$ and powers repeat every 4.
- $\bar z=a-ib$.
- $|z|=\sqrt{a^2+b^2}$.
- $z\bar z=|z|^2$.
- $|z_1-z_2|$ = distance.

## 🎲 15.18 MCQs

1. $i^{10}$ equals: **Answer: $-1$**
2. Conjugate of $2-3i$: **Answer: $2+3i$**
3. Modulus of $3+4i$: **Answer: 5**
4. $|z-z_0|=r$ represents: **Answer: Circle**

## 📝 15.19 Important Exam Questions

1. Define a complex number and its parts.
2. Perform algebraic operations on complex numbers.
3. Explain conjugate and modulus properties.
4. Divide two complex numbers in standard form.
5. Explain geometrical sum, difference and locus.
