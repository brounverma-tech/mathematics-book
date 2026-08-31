<div align="center">

# 📘 Chapter 9: Chain Rule, Implicit and Parametric Differentiation

### 🟢 Unit 2 — Differential Calculus

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Methods](https://img.shields.io/badge/Methods-Chain%20%7C%20Implicit%20%7C%20Parametric-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Composite, implicit aur parametric functions ko correct method se differentiate karna.

## 🎯 9.1 Learning Objectives

You will recognize composite functions, apply chain rule, differentiate equations containing $x$ and $y$, and calculate parametric first and second derivatives.

## 9.2 Chain Rule

If $y=f(u)$ and $u=g(x)$, then

$$
\frac{dy}{dx}=\frac{dy}{du}\cdot\frac{du}{dx}.
$$

For $y=f(g(x))$,

$$y'=f'(g(x))g'(x).$$

### Hinglish Rule

**Outer function ka derivative, inner same; phir inner ka derivative multiply.**

### 🧮 Solved Example 1

$$y=(3x+1)^5.$$

Outer derivative:

$$5(3x+1)^4.$$

Inner derivative = 3. Therefore,

$$y'=15(3x+1)^4.$$

### 🧮 Solved Example 2

$$y=\sin(x^2).$$

$$y'=\cos(x^2)\cdot2x=2x\cos(x^2).$$

## 9.3 General Chain Forms

If $u=u(x)$,

$$
\frac{d}{dx}(u^n)=nu^{n-1}u',
$$

$$
\frac{d}{dx}(\sin u)=\cos u\,u',
$$

$$
\frac{d}{dx}(e^u)=e^u u',
$$

$$
\frac{d}{dx}(\ln|u|)=\frac{u'}u,
$$

$$
\frac{d}{dx}(\tan^{-1}u)=\frac{u'}{1+u^2}.
$$

## 9.4 Implicit Differentiation

When $y$ cannot easily be written alone as a function of $x$, differentiate both sides with respect to $x$. Treat $y$ as a function of $x$.

Important:

$$
\frac{d}{dx}(y^n)=ny^{n-1}\frac{dy}{dx}.
$$

### 🧮 Solved Example 3

For the circle

$$x^2+y^2=25,$$

differentiate:

$$2x+2y\frac{dy}{dx}=0.$$

Therefore,

$$
\frac{dy}{dx}=-\frac{x}{y}.
$$

### 🧮 Solved Example 4

If

$$x^3+y^3=6xy,$$

then

$$
3x^2+3y^2y'=6(y+xy').
$$

Collect $y'$ terms:

$$
y'(3y^2-6x)=6y-3x^2.
$$

Thus

$$
y'=\frac{2y-x^2}{y^2-2x}.
$$

## 9.5 Logarithmic Differentiation

Useful for products, quotients and variable powers.

### 🧮 Solved Example 5

Let $y=x^x$, $x>0$.

Take logarithm:

$$\ln y=x\ln x.$$

Differentiate:

$$
\frac{y'}y=\ln x+1.
$$

Therefore,

$$
y'=x^x(\ln x+1).
$$

## 9.6 Parametric Differentiation

If

$$x=f(t),\qquad y=g(t),$$

then

$$
\frac{dy}{dx}=\frac{dy/dt}{dx/dt},\qquad dx/dt\ne0.
$$

### 🧮 Solved Example 6

If $x=t^2$, $y=t^3$, then

$$
\frac{dy}{dx}=\frac{3t^2}{2t}=\frac{3t}{2}.
$$

## 9.7 Second Parametric Derivative

$$
\frac{d^2y}{dx^2}
=\frac{\dfrac d{dt}\left(\dfrac{dy}{dx}\right)}{dx/dt}.
$$

For the previous example,

$$
\frac d{dt}\left(\frac{3t}{2}\right)=\frac32,
$$

so

$$
\frac{d^2y}{dx^2}=\frac{3/2}{2t}=\frac{3}{4t}.
$$

## 9.8 Standard Parametric Curve

For $x=a\cos t$, $y=a\sin t$,

$$
\frac{dy}{dx}=\frac{a\cos t}{-a\sin t}=-\cot t.
$$

## 💡 9.9 Easy Tricks

- Function ke andar function dikhe → chain rule.
- Implicit equation mein every differentiated $y$ term ke saath $y'$.
- Parametric derivative mein numerator $dy/dt$, denominator $dx/dt$.
- Variable in base and exponent → logarithmic differentiation.

## 🚫 9.10 Common Mistakes

1. Inner derivative miss karna.
2. $d(y^2)/dx=2y$ likhna instead of $2yy'$.
3. Parametric ratio reverse karna.
4. Second derivative mein directly $d/dt$ stop karna.
5. Log differentiation ke end mein $y$ replace na karna.

## 📌 9.11 Chapter Summary

The chain rule differentiates composite functions. Implicit differentiation handles relations where $y$ is not isolated and attaches $dy/dx$ to differentiated $y$ terms. Logarithmic differentiation simplifies variable exponents and long products. Parametric differentiation uses the ratio of derivatives with respect to the parameter.

## 🧠 9.12 Quick Revision

- Chain: outer derivative × inner derivative.
- Implicit: every $y$ derivative includes $y'$.
- $x^x$ uses logarithmic differentiation.
- Parametric: $(dy/dt)/(dx/dt)$.

## 🎲 9.13 MCQs

1. Chain rule applies to: **Answer: Composite functions**
2. $d(y^3)/dx$ is: **Answer: $3y^2y'$**
3. Parametric $dy/dx$ equals: **Answer: $(dy/dt)/(dx/dt)$**
4. Best method for $x^x$: **Answer: Logarithmic differentiation**

## 📝 9.14 Important Exam Questions

1. State and apply the chain rule.
2. Differentiate an implicit curve.
3. Differentiate $x^x$ logarithmically.
4. Find first and second derivatives of a parametric curve.
5. Find slope of the circle $x=a\cos t$, $y=a\sin t$.
