<div align="center">

# 📘 Chapter 11: Introduction to Integration

### 🟠 Unit 3 — Integral Calculus

![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Antiderivatives-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Integration ko differentiation ke inverse ke roop mein samajhna aur standard formulas apply karna.

## 🎯 11.1 Learning Objectives

You will understand antiderivatives, indefinite integrals, the constant of integration and standard algebraic, trigonometric, exponential and logarithmic integrals.

## 🗣️ 11.2 Important Terms

| Term | Meaning |
|---|---|
| Integration | Derivative se original family of functions find karna |
| Integrand | Integral sign ke andar function |
| Antiderivative | Jiska derivative given function ho |
| Indefinite integral | Without limits integral |
| Constant of integration | Arbitrary constant $C$ |

## 11.3 Meaning of Integration

### English Definition

> Integration is the process of finding a function whose derivative is the given function.

If $F'(x)=f(x)$, then

$$
\int f(x)\,dx=F(x)+C.
$$

### Hinglish Explanation

Differentiation function ko derivative mein convert karta hai. Integration derivative se original function ki family recover karta hai.

Example:

$$
\frac{d}{dx}(x^2)=2x
\Rightarrow
\int2x\,dx=x^2+C.
$$

## 11.4 Why $+C$ Is Necessary

$$
\frac{d}{dx}(x^2)=\frac{d}{dx}(x^2+5)=\frac{d}{dx}(x^2-9)=2x.
$$

Different constants derivative mein disappear ho jate hain. Therefore the reverse answer represents a family:

$$x^2+C.$$

## 11.5 Basic Properties

$$
\int[f(x)\pm g(x)]dx
=\int f(x)dx\pm\int g(x)dx,
$$

$$
\int kf(x)dx=k\int f(x)dx.
$$

## 11.6 Algebraic Integrals

For $n\ne-1$,

$$
\int x^n dx=\frac{x^{n+1}}{n+1}+C.
$$

Special case:

$$
\int\frac1x dx=\ln|x|+C.
$$

### 🧮 Solved Example 1

$$
\int(4x^3-3x^2+2)dx
=x^4-x^3+2x+C.
$$

## 11.7 Exponential and Logarithmic Integrals

$$
\int e^x dx=e^x+C,
$$

$$
\int a^x dx=\frac{a^x}{\ln a}+C,
$$

$$
\int\frac{dx}{ax+b}=\frac1a\ln|ax+b|+C.
$$

## 11.8 Trigonometric Integrals

$$
\int\sin x\,dx=-\cos x+C,
$$

$$
\int\cos x\,dx=\sin x+C,
$$

$$
\int\sec^2x\,dx=\tan x+C,
$$

$$
\int\csc^2x\,dx=-\cot x+C,
$$

$$
\int\sec x\tan x\,dx=\sec x+C,
$$

$$
\int\csc x\cot x\,dx=-\csc x+C,
$$

$$
\int\tan x\,dx=\ln|\sec x|+C,
$$

$$
\int\cot x\,dx=\ln|\sin x|+C,
$$

$$
\int\sec x\,dx=\ln|\sec x+\tan x|+C.
$$

## 11.9 Inverse-Trigonometric Standard Forms

$$
\int\frac{dx}{\sqrt{a^2-x^2}}
=\sin^{-1}\left(\frac xa\right)+C,
$$

$$
\int\frac{dx}{a^2+x^2}
=\frac1a\tan^{-1}\left(\frac xa\right)+C,
$$

$$
\int\frac{dx}{x^2-a^2}
=\frac1{2a}\ln\left|\frac{x-a}{x+a}\right|+C.
$$

### 🧮 Solved Example 2

$$
\int\frac{dx}{9+x^2}
=\frac13\tan^{-1}\left(\frac x3\right)+C.
$$

## 11.10 Verification by Differentiation

Differentiate the final answer. If its derivative equals the original integrand, the integral is correct.

Example:

$$
\frac{d}{dx}\left(\frac{x^4}{4}+C\right)=x^3.
$$

## 💡 11.11 Easy Tricks

- Power rule: exponent +1, then divide by new exponent.
- $n=-1$ is the log exception.
- Derivative table ko reverse direction mein read karein.
- Indefinite integral mein $+C$ compulsory.

## 🚫 11.12 Common Mistakes

1. $+C$ omit karna.
2. $\int x^{-1}dx$ par power rule lagana.
3. $\int\sin xdx$ ka sign wrong karna.
4. Constant multiple ko incorrectly integrate karna.
5. Answer verify na karna.

## 📌 11.13 Chapter Summary

Integration reverses differentiation and produces a family of antiderivatives. The constant $C$ represents all functions having the same derivative. Linearity allows term-by-term integration. Standard formulas cover algebraic, trigonometric, exponential, logarithmic and inverse-trigonometric forms.

## 🧠 11.14 Quick Revision

- $\int f(x)dx=F(x)+C$.
- Power: $x^{n+1}/(n+1)$ for $n\ne-1$.
- $\int dx/x=\ln|x|+C$.
- $\int e^x dx=e^x+C$.
- Integrate term by term.

## 🎲 11.15 MCQs

1. Integrand is: **Answer: Function inside integral sign**
2. Constant of integration is: **Answer: $C$**
3. $\int x^2dx$ equals: **Answer: $x^3/3+C$**
4. $\int\cos xdx$ equals: **Answer: $\sin x+C$**

## 📝 11.16 Important Exam Questions

1. Explain integration as inverse differentiation.
2. Why is the arbitrary constant necessary?
3. Write the standard integration formulas.
4. Solve mixed algebraic and trigonometric integrals.
5. Verify an integral by differentiation.
