<div align="center">

# 📘 Chapter 6: Limits and Continuity

### 🟢 Unit 2 — Differential Calculus

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=flat-square)
![Foundation](https://img.shields.io/badge/Foundation-Calculus-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Function ke nearby behaviour ko limit se samajhna aur continuity ki three conditions ko apply karna.

## 🎯 6.1 Learning Objectives

You will understand limits, one-sided limits, limit laws, standard limits, indeterminate forms and continuity of ordinary and piecewise functions.

## 🗣️ 6.2 Important Terms

| Term | Meaning |
|---|---|
| Limit | Function kis value ke paas approach karti hai |
| Approach | Paas jana, exactly equal hona zaroori nahi |
| Left-hand limit | $a$ se chhoti values ki side se approach |
| Right-hand limit | $a$ se badi values ki side se approach |
| Continuous | Graph bina break ke draw ho sake |
| Indeterminate | Form se answer directly decide na ho |

## 6.3 Meaning of a Limit

### English Definition

> The limit of $f(x)$ as $x$ approaches $a$ is the value approached by $f(x)$ when $x$ is taken sufficiently close to $a$.

$$
\lim_{x\to a}f(x)=L.
$$

### Hinglish Explanation

Hum check karte hain ki $x$, $a$ ke very close jane par $f(x)$ kis value ke close ja raha hai. Limit nearby behaviour describe karti hai; $x=a$ hona compulsory nahi.

### 🧮 Solved Example 1

$$
\lim_{x\to2}(3x+1)=3(2)+1=7.
$$

Polynomial continuous hota hai, isliye direct substitution work karti hai.

## 6.4 Left-Hand and Right-Hand Limits

$$
\lim_{x\to a^-}f(x)=\text{LHL},\qquad
\lim_{x\to a^+}f(x)=\text{RHL}.
$$

A two-sided limit exists only when

$$
\text{LHL}=\text{RHL}.
$$

### 🧮 Solved Example 2

Let

$$
f(x)=\begin{cases}
1,&x<0,\\
2,&x\ge0.
\end{cases}
$$

At $x=0$, LHL = 1 and RHL = 2. Since they are unequal,

$$\lim_{x\to0}f(x)\text{ does not exist}.$$

## 6.5 Laws of Limits

If $\lim f(x)=L$ and $\lim g(x)=M$, then

$$
\lim(f\pm g)=L\pm M,
$$

$$
\lim(fg)=LM,
$$

$$
\lim\frac{f}{g}=\frac{L}{M},\quad M\ne0,
$$

$$
\lim[f(x)]^n=L^n.
$$

## 6.6 Standard Limits

Angles must be in radians.

$$
\lim_{x\to0}\frac{\sin x}{x}=1,
$$

$$
\lim_{x\to0}\frac{\tan x}{x}=1,
$$

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}=\frac12,
$$

$$
\lim_{x\to0}\frac{e^x-1}{x}=1,
$$

$$
\lim_{x\to0}\frac{a^x-1}{x}=\ln a,
$$

$$
\lim_{x\to0}\frac{\ln(1+x)}{x}=1,
$$

$$
\lim_{x\to0}(1+x)^{1/x}=e.
$$

### 🧮 Solved Example 3

$$
\lim_{x\to0}\frac{\sin5x}{x}
=5\lim_{x\to0}\frac{\sin5x}{5x}=5.
$$

## 6.7 Indeterminate Forms

Common forms are

$$
\frac00,\quad\frac\infty\infty,\quad0\cdot\infty,\quad\infty-\infty,\quad1^\infty.
$$

These are not answers. They show that simplification is required.

### 6.7.1 Factorization

$$
\lim_{x\to2}\frac{x^2-4}{x-2}
=\lim_{x\to2}\frac{(x-2)(x+2)}{x-2}=4.
$$

### 6.7.2 Rationalization

$$
\lim_{x\to0}\frac{\sqrt{1+x}-1}{x}.
$$

Multiply by the conjugate:

$$
=\lim_{x\to0}\frac{1}{\sqrt{1+x}+1}=\frac12.
$$

## 6.8 Continuity at a Point

A function is continuous at $x=a$ when:

1. $f(a)$ is defined.
2. $\lim_{x\to a}f(x)$ exists.
3. $\lim_{x\to a}f(x)=f(a)$.

### Hinglish Test

**Value present + left/right match + limit equals value.**

### 🧮 Solved Example 4

Find $k$ so that

$$
f(x)=\begin{cases}
kx+1,&x<2,\\
7,&x\ge2
\end{cases}
$$

is continuous at $x=2$.

LHL = $2k+1$, RHL = $f(2)=7$. Therefore,

$$2k+1=7\Rightarrow k=3.$$

## 6.9 Types of Discontinuity

1. **Removable:** A hole; limit exists but function value is missing/different.
2. **Jump:** LHL and RHL are finite but unequal.
3. **Infinite:** Function grows without bound near the point.

## 💡 6.10 Easy Tricks

- First direct substitution try karein.
- $0/0$ mile to factor or rationalize.
- Trigonometric standard limits mein angle radians mein hota hai.
- Continuity ke liye three conditions hamesha write karein.

## 🚫 6.11 Common Mistakes

1. $0/0$ ko answer zero maan lena.
2. LHL/RHL check kiye bina limit exist bolna.
3. Limit aur function value ko same assume karna.
4. $\sin x/x$ standard limit ko non-zero point par direct use karna.

## 📌 6.12 Chapter Summary

Limits describe the value approached by a function near a point. A two-sided limit exists when left- and right-hand limits agree. Standard limits and algebraic simplification handle indeterminate forms. Continuity requires a defined function value, an existing limit and equality between the two.

## 🧠 6.13 Quick Revision

- Two-sided limit → LHL = RHL.
- $0/0$ → simplify, not answer.
- $\lim_{x\to0}\sin x/x=1$.
- Continuity → defined + limit exists + limit equals value.

## 🎲 6.14 MCQs

1. A two-sided limit exists when: **Answer: LHL = RHL**
2. $0/0$ is: **Answer: Indeterminate form**
3. $\lim_{x\to0}\sin3x/x$ is: **Answer: 3**
4. Continuity requires: **Answer: Limit equals function value**

## 📝 6.15 Important Exam Questions

1. Define limit and one-sided limits.
2. State standard limits.
3. Evaluate limits by factorization and rationalization.
4. Explain continuity with three conditions.
5. Find an unknown constant in a piecewise function for continuity.
