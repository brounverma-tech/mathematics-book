<div align="center">

# 📘 Chapter 14: Definite Integrals and Their Properties

### 🟠 Unit 3 — Integral Calculus

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Definite%20Integral-purple?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Definite integral ko antiderivative, signed area, properties aur limit of a sum ke through understand karna.

## 🎯 14.1 Learning Objectives

You will evaluate definite integrals, use the Fundamental Theorem, apply symmetry and reflection properties, and understand the Riemann-sum definition.

## 14.2 Meaning of a Definite Integral

$$
\int_a^bf(x)dx
$$

represents signed accumulation from $x=a$ to $x=b$.

### Hinglish Explanation

Graph aur $x$-axis ke beech ka area, direction/sign ke saath definite integral se represent hota hai. Above-axis part positive aur below-axis part negative hota hai.

## 14.3 Fundamental Theorem of Calculus

If $F'(x)=f(x)$, then

$$
\int_a^bf(x)dx=F(b)-F(a).
$$

Notation:

$$
[F(x)]_a^b=F(b)-F(a).
$$

### 🧮 Solved Example 1

$$
\int_0^2(x^2+1)dx
=\left[\frac{x^3}{3}+x\right]_0^2
=\frac{14}{3}.
$$

No $+C$ is needed in a definite answer.

## 14.4 Basic Properties

$$
\int_a^af(x)dx=0,
$$

$$
\int_a^bf(x)dx=-\int_b^af(x)dx,
$$

$$
\int_a^bf(x)dx=\int_a^cf(x)dx+\int_c^bf(x)dx,
$$

$$
\int_a^b[kf(x)]dx=k\int_a^bf(x)dx,
$$

$$
\int_a^b(f\pm g)dx=\int_a^bfdx\pm\int_a^bgdx.
$$

## 14.5 Reflection Property

$$
\int_a^bf(x)dx=\int_a^bf(a+b-x)dx.
$$

Therefore,

$$
\int_a^bf(x)dx
=\frac12\int_a^b[f(x)+f(a+b-x)]dx.
$$

For $[0,a]$:

$$
\int_0^af(x)dx=\int_0^af(a-x)dx.
$$

## 14.6 Even and Odd Functions

If $f(-x)=f(x)$, $f$ is even:

$$
\int_{-a}^{a}f(x)dx=2\int_0^af(x)dx.
$$

If $f(-x)=-f(x)$, $f$ is odd:

$$
\int_{-a}^{a}f(x)dx=0.
$$

### 🧮 Solved Example 2

$$
\int_{-2}^{2}(x^3+x^2)dx.
$$

$x^3$ is odd and contributes zero. $x^2$ is even:

$$
=2\int_0^2x^2dx
=2\left[\frac{x^3}{3}\right]_0^2
=\frac{16}{3}.
$$

## 14.7 Definite Integral as a Limit of a Sum

Divide $[a,b]$ into $n$ equal parts:

$$\Delta x=\frac{b-a}{n}.$$

Then

$$
\int_a^bf(x)dx
=\lim_{n\to\infty}\sum_{r=1}^{n}
f\left(a+r\frac{b-a}{n}\right)\frac{b-a}{n}.
$$

This is a Riemann sum: many thin rectangles approach exact signed area.

Useful sums:

$$
\sum_{r=1}^{n}r=\frac{n(n+1)}2,
$$

$$
\sum_{r=1}^{n}r^2=\frac{n(n+1)(2n+1)}6,
$$

$$
\sum_{r=1}^{n}r^3=\left[\frac{n(n+1)}2\right]^2.
$$

### 🧮 Solved Example 3

Evaluate $\int_0^1x\,dx$ as a limit of a sum.

Here $\Delta x=1/n$, $x_r=r/n$.

$$
\int_0^1x\,dx
=\lim_{n\to\infty}\sum_{r=1}^{n}\frac rn\cdot\frac1n
$$

$$
=\lim_{n\to\infty}\frac1{n^2}\cdot\frac{n(n+1)}2
=\frac12.
$$

## 14.8 Area vs Signed Area

If a curve goes below the $x$-axis, integral may be negative or may cancel positive area. Total geometric area requires splitting intervals and using absolute values where needed.

## 💡 14.9 Easy Tricks

- Symmetric interval $[-a,a]$ par even/odd test first.
- Limits reverse → sign reverse.
- Property se calculation short ho to direct integration avoid karein.
- Definite integral mein $+C$ nahi.

## 🚫 14.10 Common Mistakes

1. Upper minus lower order reverse karna.
2. Definite answer mein $+C$ add karna.
3. Odd/even property non-symmetric limits par use karna.
4. Signed area ko total geometric area samajhna.
5. Riemann sum mein $\Delta x$ miss karna.

## 📌 14.11 Chapter Summary

A definite integral measures signed accumulation over a fixed interval. The Fundamental Theorem evaluates it through antiderivatives. Algebraic, reflection and symmetry properties reduce calculation. The Riemann-sum definition explains the integral as the limit of increasingly fine rectangular approximations.

## 🧠 14.12 Quick Revision

- Definite integral = $F(b)-F(a)$.
- Reverse limits → negative sign.
- Even function on $[-a,a]$ → double $[0,a]$.
- Odd function on $[-a,a]$ → zero.
- Riemann sum includes function value × interval width.

## 🎲 14.13 MCQs

1. $\int_a^af(x)dx$ equals: **Answer: 0**
2. Reversing limits: **Answer: Changes sign**
3. Odd function over $[-a,a]$: **Answer: Integral is zero**
4. Definite integral answer includes $+C$: **Answer: No**

## 📝 14.14 Important Exam Questions

1. State the Fundamental Theorem of Calculus.
2. Prove reflection property.
3. Explain even and odd symmetry.
4. Evaluate an integral using properties.
5. Evaluate a definite integral as a limit of a sum.
