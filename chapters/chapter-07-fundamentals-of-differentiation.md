<div align="center">

# 📘 Chapter 7: Fundamentals of Differentiation

### 🟢 Unit 2 — Differential Calculus

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Derivative-orange?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Derivative ka meaning, first principle aur basic algebraic rules ko confidently apply karna.

## 🎯 7.1 Learning Objectives

You will understand derivative as slope/rate of change and apply constant, power, sum, difference, product and quotient rules.

## 7.2 Meaning of Differentiation

### English Definition

> Differentiation is the process of finding the instantaneous rate of change of a function with respect to its independent variable.

### Hinglish Explanation

Differentiation batata hai ki input mein very small change hone par output kitni speed se change ho raha hai. Graph par derivative tangent ki slope hoti hai.

Notations:

$$f'(x),\qquad \frac{dy}{dx},\qquad D_xy.$$

## 7.3 Derivative from First Principle

For $y=f(x)$,

$$
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}{h}.
$$

### 🧮 Solved Example 1

Find derivative of $f(x)=x^2$ from first principle.

$$
f'(x)=\lim_{h\to0}\frac{(x+h)^2-x^2}{h}
$$

$$
=\lim_{h\to0}\frac{2xh+h^2}{h}
=\lim_{h\to0}(2x+h)=2x.
$$

## 7.4 Geometrical and Physical Meaning

- Geometrical: $f'(a)$ is slope of tangent at $x=a$.
- Physical: If $s(t)$ is position, then $ds/dt$ is velocity.
- Second derivative $d^2s/dt^2$ is acceleration.

## 7.5 Basic Derivative Rules

### 7.5.1 Constant Rule

$$\frac{d}{dx}(c)=0.$$

### 7.5.2 Power Rule

$$\frac{d}{dx}(x^n)=nx^{n-1}.$$

### 7.5.3 Constant Multiple Rule

$$\frac{d}{dx}[cf(x)]=cf'(x).$$

### 7.5.4 Sum and Difference Rule

$$\frac{d}{dx}[f(x)\pm g(x)]=f'(x)\pm g'(x).$$

### 🧮 Solved Example 2

For

$$y=4x^5-3x^2+7x-9,$$

$$
\frac{dy}{dx}=20x^4-6x+7.
$$

## 7.6 Product Rule

If $y=uv$, then

$$
\frac{dy}{dx}=u\frac{dv}{dx}+v\frac{du}{dx}.
$$

Easy phrase: **First × derivative of second + second × derivative of first.**

### 🧮 Solved Example 3

For $y=x^2(x+3)$,

$$
y'=x^2(1)+(x+3)(2x)=3x^2+6x.
$$

## 7.7 Quotient Rule

If $y=u/v$, then

$$
\frac{dy}{dx}=\frac{v\,du/dx-u\,dv/dx}{v^2}.
$$

### 🧮 Solved Example 4

$$y=\frac{x^2+1}{x}.$$

$$
y'=\frac{x(2x)-(x^2+1)(1)}{x^2}
=\frac{x^2-1}{x^2}.
$$

It can also be simplified first as $y=x+x^{-1}$.

## 7.8 Derivative at a Point

For $y=x^3-2x$, slope at $x=2$:

$$
y'=3x^2-2,
$$

$$
y'(2)=3(4)-2=10.
$$

## 7.9 Higher-Order Derivatives

Successive differentiation gives

$$y',\quad y'',\quad y''',\quad\ldots$$

Example: If $y=x^4$,

$$y'=4x^3,\quad y''=12x^2,\quad y'''=24x,\quad y^{(4)}=24.$$

## 💡 7.10 Easy Tricks

- Polynomial mein each term separately differentiate karein.
- Product rule se pehle expression expand/simplify karna easier ho sakta hai.
- Quotient ko powers mein convert kiya ja sake to calculation shorter hoti hai.
- Final derivative ka dimension/degree mentally check karein.

## 🚫 7.11 Common Mistakes

1. Constant ka derivative constant likhna.
2. Power rule mein exponent reduce na karna.
3. $(uv)'=u'v'$ likhna.
4. Quotient rule numerator order reverse karna.
5. Function value aur derivative value confuse karna.

## 📌 7.12 Chapter Summary

The derivative measures instantaneous change and tangent slope. First principle defines it through a limit. Basic derivative rules simplify constants, powers, sums, products and quotients. Derivatives evaluated at a point give a numerical rate or slope.

## 🧠 7.13 Quick Revision

- First principle: $[f(x+h)-f(x)]/h$ limit.
- $(x^n)'=nx^{n-1}$.
- $(uv)'=uv'+vu'$.
- $(u/v)'=(vu'-uv')/v^2$.
- Derivative at a point = slope there.

## 🎲 7.14 MCQs

1. Derivative of a constant is: **Answer: 0**
2. Derivative of $x^5$ is: **Answer: $5x^4$**
3. Product rule contains: **Answer: Two terms**
4. Denominator in quotient rule is: **Answer: $v^2$**

## 📝 7.15 Important Exam Questions

1. Derive $d(x^2)/dx$ from first principle.
2. Explain geometrical meaning of derivative.
3. State and apply product and quotient rules.
4. Find first and second derivatives of a polynomial.
5. Find tangent slope at a given point.
