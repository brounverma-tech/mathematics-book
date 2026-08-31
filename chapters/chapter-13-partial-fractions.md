<div align="center">

# 📘 Chapter 13: Integration by Partial Fractions

### 🟠 Unit 3 — Integral Calculus

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Rational%20Functions-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Rational function ko correct partial-fraction form mein split karke integrate karna.

## 🎯 13.1 Learning Objectives

You will identify proper and improper fractions, factor denominators, write decompositions for linear/repeated/quadratic factors and calculate constants.

## 13.2 Rational Functions

A rational function has the form

$$
\frac{P(x)}{Q(x)},\qquad Q(x)\ne0,
$$

where $P$ and $Q$ are polynomials.

## 13.3 Proper and Improper Fractions

- Proper: $\deg P<\deg Q$.
- Improper: $\deg P\ge\deg Q$.

Improper fraction ko polynomial division se proper fraction mein convert karein.

### 🧮 Solved Example 1

$$
\frac{x^2+1}{x+1}=x-1+\frac2{x+1}.
$$

Therefore,

$$
\int\frac{x^2+1}{x+1}dx
=\frac{x^2}{2}-x+2\ln|x+1|+C.
$$

## 13.4 Distinct Linear Factors

If

$$Q(x)=(x-a)(x-b),$$

write

$$
\frac{P(x)}{(x-a)(x-b)}
=\frac A{x-a}+\frac B{x-b}.
$$

### 🧮 Solved Example 2

$$
\frac{3x+5}{(x+1)(x+2)}
=\frac A{x+1}+\frac B{x+2}.
$$

Multiply by the denominator:

$$3x+5=A(x+2)+B(x+1).$$

Set $x=-1$: $2=A$. Set $x=-2$: $-1=-B$, so $B=1$.

Thus

$$
\int\frac{3x+5}{(x+1)(x+2)}dx
=2\ln|x+1|+\ln|x+2|+C.
$$

## 13.5 Repeated Linear Factors

For $(x-a)^n$, include every power:

$$
\frac{P(x)}{(x-a)^n}
=\frac{A_1}{x-a}+\frac{A_2}{(x-a)^2}+\cdots+\frac{A_n}{(x-a)^n}.
$$

### Example Form

$$
\frac{2x+3}{(x-1)^2(x+2)}
=\frac A{x-1}+\frac B{(x-1)^2}+\frac C{x+2}.
$$

## 13.6 Irreducible Quadratic Factors

For a quadratic factor that cannot be factored over real numbers, use a linear numerator:

$$
\frac{P(x)}{x^2+1}=\frac{Ax+B}{x^2+1}.
$$

For a repeated quadratic:

$$
\frac{Ax+B}{x^2+1}+\frac{Cx+D}{(x^2+1)^2}+\cdots
$$

## 13.7 Mixed Factor Example

### 🧮 Solved Example 3

Decompose

$$
\frac{x+1}{x(x^2+1)}.
$$

Write

$$
\frac{x+1}{x(x^2+1)}=\frac A{x}+\frac{Bx+C}{x^2+1}.
$$

Then

$$
x+1=A(x^2+1)+x(Bx+C).
$$

Comparing coefficients:

$$A=1,\quad A+B=0\Rightarrow B=-1,\quad C=1.$$

Therefore,

$$
\int\frac{x+1}{x(x^2+1)}dx
=\int\left[\frac1x+\frac{-x+1}{x^2+1}\right]dx.
$$

$$
=\ln|x|-\frac12\ln(x^2+1)+\tan^{-1}x+C.
$$

## 13.8 Methods for Finding Constants

1. Substitute roots of the denominator.
2. Compare coefficients of equal powers.
3. Use a combination of both.

## 13.9 Step-by-Step Procedure

1. Check properness.
2. Divide if improper.
3. Factor denominator completely.
4. Write correct partial-fraction form.
5. Clear denominator.
6. Find constants.
7. Integrate each simple term.
8. Differentiate or recombine to check.

## 💡 13.10 Easy Tricks

- Root substitution quickly removes terms.
- Repeated factor → every power must appear.
- Quadratic factor → numerator must be linear.
- Log answers need absolute values for linear factors.

## 🚫 13.11 Common Mistakes

1. Improper fraction ko directly decompose karna.
2. Denominator completely factor na karna.
3. Repeated powers skip karna.
4. Quadratic factor par constant numerator use karna.
5. $\ln|x-a|$ mein absolute value miss karna.

## 📌 13.12 Chapter Summary

Partial fractions reduce a proper rational function into simpler fractions. The denominator's factor type determines the decomposition. Constants are obtained through substitution or coefficient comparison. Each resulting term can then be integrated using logarithmic, inverse-trigonometric or substitution formulas.

## 🧠 13.13 Quick Revision

- Proper first; divide if improper.
- Distinct linear → one constant term per factor.
- Repeated linear → include all powers.
- Quadratic → linear numerator.
- Clear denominator, then find constants.

## 🎲 13.14 MCQs

1. Partial fractions apply directly to: **Answer: Proper rational functions**
2. For $(x-a)^2$, required terms are: **Answer: $A/(x-a)+B/(x-a)^2$**
3. Numerator over irreducible quadratic is: **Answer: Linear**
4. Improper fraction first needs: **Answer: Polynomial division**

## 📝 13.15 Important Exam Questions

1. Distinguish proper and improper fractions.
2. Explain all standard decomposition forms.
3. Integrate using distinct linear factors.
4. Integrate a rational function with repeated factor.
5. Solve a mixed linear-quadratic factor example.
