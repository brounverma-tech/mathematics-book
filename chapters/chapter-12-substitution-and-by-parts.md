<div align="center">

# 📘 Chapter 12: Substitution and Integration by Parts

### 🟠 Unit 3 — Integral Calculus

![Methods](https://img.shields.io/badge/Methods-Substitution%20%7C%20By%20Parts-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Composite integrals ko substitution aur product-type integrals ko integration by parts se solve karna.

## 🎯 12.1 Learning Objectives

You will select a useful substitution, transform the differential correctly, use LIATE to choose $u$, and apply integration by parts repeatedly.

## 12.2 Integration by Substitution

Substitution reverses the chain rule. If $u=g(x)$ and $du=g'(x)dx$, then

$$
\int f(g(x))g'(x)dx=\int f(u)du.
$$

### Hinglish Explanation

Complicated inner expression ko temporary single variable $u$ maan kar integral simple banaya jata hai.

### 🧮 Solved Example 1

$$
\int2x(x^2+1)^5dx.
$$

Let

$$u=x^2+1,\qquad du=2x\,dx.$$

Then

$$
\int u^5du=\frac{u^6}{6}+C
=\frac{(x^2+1)^6}{6}+C.
$$

### 🧮 Solved Example 2

$$
\int\frac{3x^2}{x^3+4}dx.
$$

Let $u=x^3+4$, so $du=3x^2dx$.

$$
\int\frac{du}{u}=\ln|u|+C
=\ln|x^3+4|+C.
$$

## 12.3 Common Substitution Patterns

$$
\int\frac{f'(x)}{f(x)}dx=\ln|f(x)|+C,
$$

$$
\int f'(x)e^{f(x)}dx=e^{f(x)}+C,
$$

$$
\int f'(x)\cos(f(x))dx=\sin(f(x))+C,
$$

$$
\int\frac{f'(x)}{1+[f(x)]^2}dx=\tan^{-1}(f(x))+C.
$$

## 12.4 Integration by Parts

The product rule gives

$$d(uv)=u\,dv+v\,du.$$

After integration,

$$
\int u\,dv=uv-\int v\,du.
$$

### LIATE Rule

Choose $u$ generally in this priority:

1. Logarithmic
2. Inverse trigonometric
3. Algebraic
4. Trigonometric
5. Exponential

### 🧮 Solved Example 3

Evaluate $\int xe^x dx$.

Take

$$u=x,\quad dv=e^x dx,$$

so

$$du=dx,\quad v=e^x.$$

Therefore,

$$
\int xe^x dx=xe^x-\int e^x dx
=e^x(x-1)+C.
$$

### 🧮 Solved Example 4

Evaluate $\int x\cos xdx$.

Let $u=x$, $dv=\cos xdx$, so $du=dx$, $v=\sin x$.

$$
\int x\cos xdx=x\sin x-\int\sin xdx
=x\sin x+\cos x+C.
$$

## 12.5 Integrating $\ln x$

Write

$$\int\ln xdx=\int1\cdot\ln xdx.$$

Choose $u=\ln x$ and $dv=dx$:

$$
\int\ln xdx=x\ln x-x+C.
$$

## 12.6 Repeated Integration by Parts

For polynomial × exponential/trigonometric, repeat until the polynomial disappears.

### 🧮 Solved Example 5

$$
\int x^2e^xdx.
$$

First application:

$$
=x^2e^x-2\int xe^xdx.
$$

Using the previous result,

$$
=x^2e^x-2e^x(x-1)+C
=e^x(x^2-2x+2)+C.
$$

## 12.7 Substitution in Definite Integrals

When changing variable, either:

1. Change limits to $u$ values, or
2. Return to $x$ before using original limits.

Do not mix both methods.

### 🧮 Solved Example 6

$$
\int_0^1 2x(x^2+1)^2dx.
$$

Let $u=x^2+1$. New limits: $x=0\Rightarrow u=1$, $x=1\Rightarrow u=2$.

$$
\int_1^2u^2du=\left[\frac{u^3}{3}\right]_1^2=\frac73.
$$

## 💡 12.8 Easy Tricks

- Inner expression + its derivative present → substitution.
- Product of unlike function types → by parts.
- LIATE is a guide, not a blind rule; choose what becomes simpler.
- Differentiate the final answer to verify.

## 🚫 12.9 Common Mistakes

1. $dx$ ko $du$ mein correctly convert na karna.
2. Substitution ke baad some $x$ terms leave karna.
3. By-parts formula mein minus sign miss karna.
4. Wrong $u$ choose karke integral more difficult banana.
5. Definite integral ke old and new limits mix karna.

## 📌 12.10 Chapter Summary

Substitution reverses the chain rule by replacing a repeated inner expression. Integration by parts reverses the product rule and is effective for products of logarithmic, inverse-trigonometric, algebraic, trigonometric and exponential functions. Repetition handles polynomial products, and limits must remain consistent during definite substitution.

## 🧠 12.11 Quick Revision

- Substitute $u=g(x)$ when $g'(x)$ is present.
- By parts: $\int u\,dv=uv-\int v\,du$.
- LIATE helps choose $u$.
- $\int\ln xdx=x\ln x-x+C$.

## 🎲 12.12 MCQs

1. Substitution reverses: **Answer: Chain rule**
2. Integration by parts reverses: **Answer: Product rule**
3. First LIATE category is: **Answer: Logarithmic**
4. $\int xe^xdx$ is: **Answer: $e^x(x-1)+C$**

## 📝 12.13 Important Exam Questions

1. Explain substitution with solved examples.
2. State integration by parts.
3. Explain LIATE rule.
4. Evaluate polynomial × exponential/trigonometric integrals.
5. Evaluate a definite integral using substitution.
