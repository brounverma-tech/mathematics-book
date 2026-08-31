<div align="center">

# 📘 Chapter 16: Polar Form, Euler's Formula and Roots

### 🔴 Unit 4 — Complex Theory

![Level](https://img.shields.io/badge/Level-Intermediate-yellow?style=flat-square)
![Topics](https://img.shields.io/badge/Topics-Polar%20%7C%20Euler%20%7C%20De%20Moivre%20%7C%20Roots-blue?style=flat-square)

</div>

> [!TIP]
> **Chapter Goal:** Complex number ko polar/exponential form mein write karke powers aur nth roots efficiently find karna.

## 🎯 16.1 Learning Objectives

You will convert rectangular to polar form, use Euler's formula, multiply/divide polar numbers, apply De Moivre's theorem and find nth roots and roots of unity.

## 16.2 Modulus and Amplitude

For $z=x+iy\ne0$,

$$
r=|z|=\sqrt{x^2+y^2}.
$$

Let $\theta$ be the angle made with the positive real axis:

$$\theta=\arg z.$$

The principal argument is commonly chosen in $(-\pi,\pi]$. The general argument is

$$\theta+2k\pi,\qquad k\in\mathbb Z.$$

## 16.3 Polar Form

Since

$$x=r\cos\theta,\qquad y=r\sin\theta,$$

we get

$$
z=r(\cos\theta+i\sin\theta).
$$

The expression $\cos\theta+i\sin\theta$ is sometimes written as $\operatorname{cis}\theta$.

### 🧮 Solved Example 1

Write $z=1+i$ in polar form.

$$r=\sqrt{1^2+1^2}=\sqrt2,$$

and the point is in the first quadrant with $\theta=\pi/4$.

$$
z=\sqrt2\left(\cos\frac\pi4+i\sin\frac\pi4\right).
$$

### 🧮 Solved Example 2: Quadrant Check

For $z=-1+\sqrt3i$,

$$r=2.$$

The point lies in quadrant II, so $\theta=2\pi/3$:

$$
z=2\left(\cos\frac{2\pi}{3}+i\sin\frac{2\pi}{3}\right).
$$

## 16.4 Euler's Formula

$$
e^{i\theta}=\cos\theta+i\sin\theta.
$$

Therefore,

$$z=re^{i\theta}.$$

Important consequences:

$$
\cos\theta=\frac{e^{i\theta}+e^{-i\theta}}2,
$$

$$
\sin\theta=\frac{e^{i\theta}-e^{-i\theta}}{2i}.
$$

Euler's identity:

$$e^{i\pi}+1=0.$$

## 16.5 Multiplication and Division in Polar Form

If

$$z_1=r_1e^{i\theta_1},\qquad z_2=r_2e^{i\theta_2},$$

then

$$
z_1z_2=r_1r_2e^{i(\theta_1+\theta_2)},
$$

$$
\frac{z_1}{z_2}=\frac{r_1}{r_2}e^{i(\theta_1-\theta_2)}.
$$

### Hinglish Meaning

Multiplication mein moduli multiply aur angles add hote hain. Division mein moduli divide aur angles subtract hote hain.

## 16.6 De Moivre's Theorem

For integer $n$,

$$
[r(\cos\theta+i\sin\theta)]^n
=r^n[\cos(n\theta)+i\sin(n\theta)].
$$

### 🧮 Solved Example 3

Find $(1+i)^8$.

Since

$$1+i=\sqrt2\operatorname{cis}\frac\pi4,$$

$$
(1+i)^8=(\sqrt2)^8\operatorname{cis}(2\pi)=16.
$$

### 🧮 Solved Example 4

Find $(\sqrt3+i)^6$.

$$\sqrt3+i=2\operatorname{cis}\frac\pi6.$$

Thus

$$
(\sqrt3+i)^6=2^6\operatorname{cis}\pi=-64.
$$

## 16.7 nth Roots of a Complex Number

If

$$z=r\operatorname{cis}\theta,$$

then its $n$ distinct nth roots are

$$
w_k=r^{1/n}
\operatorname{cis}\left(\frac{\theta+2k\pi}{n}\right),
$$

where

$$k=0,1,2,\ldots,n-1.$$

These roots are equally spaced on a circle of radius $r^{1/n}$.

### 🧮 Solved Example 5

Find fourth roots of 16.

Write $16=16\operatorname{cis}(0+2k\pi)$.

$$
w_k=2\operatorname{cis}\frac{2k\pi}{4},\qquad k=0,1,2,3.
$$

The roots are

$$2,\quad2i,\quad-2,\quad-2i.$$

## 16.8 nth Roots of Unity

The equation

$$z^n=1$$

has roots

$$
\omega_k=e^{2\pi ik/n},\qquad k=0,1,\ldots,n-1.
$$

They lie on the unit circle and form a regular $n$-gon.

## 16.9 Cube Roots of Unity

$$
1,\qquad
\omega=-\frac12+\frac{\sqrt3}{2}i,\qquad
\omega^2=-\frac12-\frac{\sqrt3}{2}i.
$$

Important identities:

$$1+\omega+\omega^2=0,$$

$$\omega^3=1,$$

$$\frac1\omega=\omega^2.$$

## 16.10 Geometrical Interpretation of Roots

All nth roots:

- have equal modulus $r^{1/n}$,
- differ in argument by $2\pi/n$,
- form a regular polygon centred at the origin.

## 💡 16.11 Easy Tricks

- Rectangular → modulus first, quadrant-based angle second.
- Powers: multiply angle by $n$.
- Roots: divide all possible angles by $n$.
- Exactly $n$ distinct nth roots; use $k=0$ to $n-1$.

## 🚫 16.12 Common Mistakes

1. $\tan^{-1}(y/x)$ se quadrant automatically correct assume karna.
2. General angle $\theta+2k\pi$ omit karna while finding roots.
3. Radius ka nth root na lena.
4. $k=1$ to $n$ use karke duplicate/missing root create karna.
5. Degrees and radians mix karna.

## 📌 16.13 Chapter Summary

Polar form expresses a complex number through magnitude and direction. Euler's formula converts it to exponential form. Multiplication and division become operations on moduli and arguments. De Moivre's theorem handles integer powers, while the general root formula produces equally spaced roots. Roots of unity form regular polygons on the unit circle.

## 🧠 16.14 Quick Revision

- $z=r(\cos\theta+i\sin\theta)=re^{i\theta}$.
- Multiplication → moduli multiply, arguments add.
- De Moivre → power on modulus, multiply angle.
- nth roots → $r^{1/n}$ and $(\theta+2k\pi)/n$.
- Roots of unity lie on unit circle.

## 🎲 16.15 MCQs

1. Polar modulus of $1+i$ is: **Answer: $\sqrt2$**
2. Euler's formula is: **Answer: $e^{i\theta}=\cos\theta+i\sin\theta$**
3. Number of distinct nth roots is: **Answer: $n$**
4. Roots of unity have modulus: **Answer: 1**
5. $1+\omega+\omega^2$ is: **Answer: 0**

## 📝 16.16 Important Exam Questions

1. Convert complex numbers into polar form.
2. State and apply Euler's formula.
3. State and use De Moivre's theorem.
4. Find nth roots of a complex number.
5. Derive and explain properties of cube roots of unity.
