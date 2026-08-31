<div align="center">

# 📘 Chapter 8: Derivatives of Special Functions

### 🟢 Unit 2 — Differential Calculus

![Topics](https://img.shields.io/badge/Topics-Trig%20%7C%20Inverse%20Trig%20%7C%20Log%20%7C%20Exp-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Trigonometric, inverse trigonometric, exponential aur logarithmic functions ke derivatives learn aur apply karna.

## 🎯 8.1 Learning Objectives

You will memorize the standard formulas, use them in expressions and identify common signs and domain restrictions.

## 8.2 Trigonometric Derivatives

Angles are measured in radians.

$$
\frac{d}{dx}(\sin x)=\cos x,
$$

$$
\frac{d}{dx}(\cos x)=-\sin x,
$$

$$
\frac{d}{dx}(\tan x)=\sec^2x,
$$

$$
\frac{d}{dx}(\cot x)=-\csc^2x,
$$

$$
\frac{d}{dx}(\sec x)=\sec x\tan x,
$$

$$
\frac{d}{dx}(\csc x)=-\csc x\cot x.
$$

### 🧮 Solved Example 1

Differentiate

$$y=3\sin x-2\cos x+\tan x.$$

$$
y'=3\cos x+2\sin x+\sec^2x.
$$

## 8.3 Inverse Trigonometric Derivatives

$$
\frac{d}{dx}(\sin^{-1}x)=\frac1{\sqrt{1-x^2}},
$$

$$
\frac{d}{dx}(\cos^{-1}x)=-\frac1{\sqrt{1-x^2}},
$$

$$
\frac{d}{dx}(\tan^{-1}x)=\frac1{1+x^2},
$$

$$
\frac{d}{dx}(\cot^{-1}x)=-\frac1{1+x^2},
$$

$$
\frac{d}{dx}(\sec^{-1}x)=\frac1{|x|\sqrt{x^2-1}},
$$

$$
\frac{d}{dx}(\csc^{-1}x)=-\frac1{|x|\sqrt{x^2-1}}.
$$

> $\sin^{-1}x$ means inverse sine, not $1/\sin x$.

## 8.4 Exponential Functions

$$
\frac{d}{dx}(e^x)=e^x,
$$

$$
\frac{d}{dx}(a^x)=a^x\ln a,qquad a>0.
$$

### 🧮 Solved Example 2

$$
\frac{d}{dx}(5^x+2e^x)=5^x\ln5+2e^x.
$$

## 8.5 Logarithmic Functions

$$
\frac{d}{dx}(\ln x)=\frac1x,
$$

$$
\frac{d}{dx}(\log_a x)=\frac1{x\ln a}.
$$

The more general real form is

$$
\frac{d}{dx}\ln|x|=\frac1x,qquad x\ne0.
$$

### 🧮 Solved Example 3

For

$$y=x^2\ln x,$$

use the product rule:

$$
y'=2x\ln x+x.
$$

## 8.6 Mixed Functions

### 🧮 Solved Example 4

Differentiate

$$y=e^x\sin x.$$

$$
y'=e^x\sin x+e^x\cos x
=e^x(\sin x+\cos x).
$$

### 🧮 Solved Example 5

Differentiate

$$y=\frac{\ln x}{x}.$$

$$
y'=\frac{x(1/x)-\ln x}{x^2}
=\frac{1-\ln x}{x^2}.
$$

## 8.7 Formula Memory Patterns

- Sine becomes cosine.
- Cosine becomes negative sine.
- Tan becomes sec square.
- Cot and cosec formulas carry a negative sign.
- $e^x$ stays unchanged.
- Log becomes reciprocal.
- Inverse sine/cosine use $\sqrt{1-x^2}$.
- Inverse tangent/cotangent use $1+x^2$.

## 💡 8.8 Easy Tricks

- Trigonometric formulas ko pairs mein learn karein.
- Negative signs ko red-flag points ki tarah mark karein: cos, cot, cosec, inverse cos, inverse cot, inverse cosec.
- $a^x$ mein $\ln a$ extra factor hota hai; $e^x$ mein $\ln e=1$.

## 🚫 8.9 Common Mistakes

1. $\sin^{-1}x$ ko cosecant samajhna.
2. Derivative of cosine ka minus sign miss karna.
3. $a^x$ ke derivative mein $\ln a$ bhoolna.
4. $\log_a x$ aur $\ln x$ formulas mix karna.
5. Product/quotient rule required hone par only individual formula use karna.

## 📌 8.10 Chapter Summary

Standard formulas make special-function differentiation direct. Trigonometric derivatives follow paired patterns, inverse trigonometric derivatives use algebraic denominators, exponential derivatives preserve the exponential, and logarithmic derivatives produce reciprocals. Product and quotient rules combine these formulas in larger expressions.

## 🧠 8.11 Quick Revision

- $(\sin x)'=\cos x$.
- $(\cos x)'=-\sin x$.
- $(\tan x)'=\sec^2x$.
- $(e^x)'=e^x$.
- $(a^x)'=a^x\ln a$.
- $(\ln x)'=1/x$.
- $(\tan^{-1}x)'=1/(1+x^2)$.

## 🎲 8.12 MCQs

1. Derivative of $\cos x$ is: **Answer: $-\sin x$**
2. Derivative of $e^x$ is: **Answer: $e^x$**
3. Derivative of $\tan^{-1}x$ is: **Answer: $1/(1+x^2)$**
4. $\sin^{-1}x$ denotes: **Answer: Inverse sine**

## 📝 8.13 Important Exam Questions

1. Write all trigonometric derivative formulas.
2. Write inverse trigonometric derivative formulas.
3. Differentiate expressions containing exponential and logarithmic functions.
4. Solve mixed product/quotient examples.
