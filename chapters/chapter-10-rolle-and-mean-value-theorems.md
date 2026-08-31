<div align="center">

# 📘 Chapter 10: Rolle's Theorem and Mean Value Theorem

### 🟢 Unit 2 — Differential Calculus

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Theorems-purple?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Theorems ki conditions verify karke required point $c$ find karna aur geometrical meaning samajhna.

## 🎯 10.1 Learning Objectives

You will state and verify Rolle's theorem, Lagrange Mean Value Theorem and the generalized Cauchy Mean Value Theorem.

## 10.2 Rolle's Theorem

### Statement

If a function $f$ satisfies:

1. $f$ is continuous on $[a,b]$,
2. $f$ is differentiable on $(a,b)$,
3. $f(a)=f(b)$,

then at least one $c\in(a,b)$ exists such that

$$f'(c)=0.$$

### Hinglish Explanation

Agar graph endpoints par same height se start/end hota hai aur beech mein break ya sharp corner nahi hai, to beech mein at least ek horizontal tangent zaroor milega.

### 🧮 Solved Example 1

Verify Rolle's theorem for

$$f(x)=x^2-4x+3\quad\text{on }[1,3].$$

1. Polynomial is continuous on $[1,3]$.
2. Polynomial is differentiable on $(1,3)$.
3. $f(1)=0$ and $f(3)=0$.

All conditions hold.

$$f'(x)=2x-4.$$

Set $f'(c)=0$:

$$2c-4=0\Rightarrow c=2,$$

and $2\in(1,3)$.

## 10.3 Lagrange Mean Value Theorem

### Statement

If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then at least one $c\in(a,b)$ satisfies

$$
f'(c)=\frac{f(b)-f(a)}{b-a}.
$$

### Geometrical Meaning

At some point, tangent slope equals the slope of the chord joining the endpoints.

### Hinglish Explanation

Complete interval ki average change rate kisi na kisi middle point par exact instantaneous change rate ke equal hoti hai.

### 🧮 Solved Example 2

Verify LMVT for $f(x)=x^2$ on $[1,3]$.

Polynomial is continuous and differentiable.

$$
\frac{f(3)-f(1)}{3-1}=\frac{9-1}{2}=4.
$$

Since $f'(x)=2x$,

$$2c=4\Rightarrow c=2.$$

## 10.4 Rolle's Theorem as a Special Case

If $f(a)=f(b)$, then LMVT gives

$$
f'(c)=\frac{f(b)-f(a)}{b-a}=0.
$$

Therefore, Rolle's theorem is a special case of LMVT.

## 10.5 Cauchy Mean Value Theorem

For suitable functions $f$ and $g$ continuous on $[a,b]$ and differentiable on $(a,b)$, with $g'(x)\ne0$, there exists $c$ such that

$$
\frac{f'(c)}{g'(c)}
=\frac{f(b)-f(a)}{g(b)-g(a)}.
$$

Taking $g(x)=x$ gives Lagrange's theorem.

## 10.6 When a Theorem Cannot Be Applied

### Example 1

$f(x)=|x|$ on $[-1,1]$ is continuous and endpoint values are equal, but it is not differentiable at 0. Rolle's theorem cannot be applied.

### Example 2

$f(x)=1/x$ on $[-1,1]$ is not continuous because it is undefined at 0. LMVT cannot be applied.

## 10.7 Standard Verification Format

In the exam, write these steps:

1. State the function and interval.
2. Verify continuity on the closed interval.
3. Verify differentiability on the open interval.
4. For Rolle, verify $f(a)=f(b)$.
5. Calculate derivative.
6. Solve the theorem equation for $c$.
7. Confirm $c\in(a,b)$.

## 10.8 Applications

Mean value theorems support error estimation, inequalities, monotonicity results and the relation between average and instantaneous speed.

## 💡 10.9 Easy Tricks

- Rolle = CDC + equal endpoints.
- LMVT = CD + chord slope.
- Closed interval for continuity; open interval for differentiability.
- Final $c$ interval ke inside hona chahiye.

## 🚫 10.10 Common Mistakes

1. Conditions verify kiye bina directly derivative solve karna.
2. Open and closed intervals mix karna.
3. Rolle mein endpoint equality miss karna.
4. LMVT slope formula reverse karna.
5. Endpoint value ko $c$ accept karna.

## 📌 10.11 Chapter Summary

Rolle's theorem guarantees a horizontal tangent when a smooth function has equal endpoint values. Lagrange's Mean Value Theorem guarantees a tangent parallel to the endpoint chord. Cauchy's theorem generalizes the result to a ratio of two functions. Each theorem requires continuity and differentiability conditions to be checked before use.

## 🧠 10.12 Quick Revision

- Rolle: continuous + differentiable + equal endpoints → $f'(c)=0$.
- LMVT: $f'(c)=[f(b)-f(a)]/(b-a)$.
- Rolle is a special case of LMVT.
- $c$ lies strictly between $a$ and $b$.

## 🎲 10.13 MCQs

1. Rolle's theorem additionally requires: **Answer: $f(a)=f(b)$**
2. LMVT compares tangent slope with: **Answer: Chord slope**
3. Differentiability is required on: **Answer: $(a,b)$**
4. Continuity is required on: **Answer: $[a,b]$**

## 📝 10.14 Important Exam Questions

1. State and verify Rolle's theorem.
2. State and verify Lagrange MVT.
3. Explain geometrical interpretations.
4. Show that Rolle is a special case of LMVT.
5. Give examples where theorem conditions fail.
