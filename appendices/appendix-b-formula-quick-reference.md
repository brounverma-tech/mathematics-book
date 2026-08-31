# 📎 Appendix B: Complete Formula Quick Reference

## B.1 Matrices

$$
(A\pm B)_{ij}=a_{ij}\pm b_{ij}
$$

$$
(AB)_{ij}=\sum_{k=1}^{n}a_{ik}b_{kj}
$$

$$
(AB)^T=B^TA^T
$$

$$
A=\frac12(A+A^T)+\frac12(A-A^T)
$$

## B.2 Determinants and Inverse

$$
\begin{vmatrix}a&b\\c&d\end{vmatrix}=ad-bc
$$

$$
C_{ij}=(-1)^{i+j}M_{ij}
$$

$$
\operatorname{adj}(A)=[C_{ij}]^T
$$

$$
A^{-1}=\frac{\operatorname{adj}(A)}{|A|},\quad |A|\ne0
$$

$$
\begin{bmatrix}a&b\\c&d\end{bmatrix}^{-1}
=\frac1{ad-bc}\begin{bmatrix}d&-b\\-c&a\end{bmatrix}
$$

$$
(AB)^{-1}=B^{-1}A^{-1}
$$

## B.3 Simultaneous Equations

$$AX=B\Rightarrow X=A^{-1}B$$

$$x_i=\frac{\Delta_i}{\Delta}$$

Consistency:

- Unique: $\operatorname{rank}(A)=\operatorname{rank}([A|B])=n$.
- Infinite: equal ranks $<n$.
- None: unequal ranks.

## B.4 Standard Limits

$$
\lim_{x\to0}\frac{\sin x}{x}=1,qquad
\lim_{x\to0}\frac{\tan x}{x}=1
$$

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}=\frac12
$$

$$
\lim_{x\to0}\frac{e^x-1}{x}=1
$$

$$
\lim_{x\to0}\frac{a^x-1}{x}=\ln a
$$

$$
\lim_{x\to0}\frac{\ln(1+x)}x=1
$$

## B.5 Differentiation Rules

$$
\frac{d}{dx}(x^n)=nx^{n-1}
$$

$$
(uv)'=u'v+uv'
$$

$$
\left(\frac uv\right)'=\frac{vu'-uv'}{v^2}
$$

$$
\frac{dy}{dx}=\frac{dy}{du}\frac{du}{dx}
$$

## B.6 Special Derivatives

| Function | Derivative |
|---|---|
| $\sin x$ | $\cos x$ |
| $\cos x$ | $-\sin x$ |
| $\tan x$ | $\sec^2x$ |
| $\cot x$ | $-\csc^2x$ |
| $\sec x$ | $\sec x\tan x$ |
| $\csc x$ | $-\csc x\cot x$ |
| $e^x$ | $e^x$ |
| $a^x$ | $a^x\ln a$ |
| $\ln x$ | $1/x$ |
| $\sin^{-1}x$ | $1/\sqrt{1-x^2}$ |
| $\cos^{-1}x$ | $-1/\sqrt{1-x^2}$ |
| $\tan^{-1}x$ | $1/(1+x^2)$ |

Parametric:

$$
\frac{dy}{dx}=\frac{dy/dt}{dx/dt}
$$

$$
\frac{d^2y}{dx^2}=
\frac{d(dy/dx)/dt}{dx/dt}
$$

## B.7 Mean Value Theorems

Rolle:

$$f(a)=f(b)\Rightarrow f'(c)=0$$

Lagrange:

$$
f'(c)=\frac{f(b)-f(a)}{b-a}
$$

## B.8 Standard Integrals

$$
\int x^ndx=\frac{x^{n+1}}{n+1}+C,\quad n\ne-1
$$

$$
\int\frac{dx}{x}=\ln|x|+C
$$

$$
\int e^xdx=e^x+C,qquad
\int a^xdx=\frac{a^x}{\ln a}+C
$$

| Integrand | Integral |
|---|---|
| $\sin x$ | $-\cos x+C$ |
| $\cos x$ | $\sin x+C$ |
| $\sec^2x$ | $\tan x+C$ |
| $\csc^2x$ | $-\cot x+C$ |
| $\sec x\tan x$ | $\sec x+C$ |
| $\csc x\cot x$ | $-\csc x+C$ |

$$
\int\frac{dx}{a^2+x^2}=\frac1a\tan^{-1}\frac xa+C
$$

$$
\int\frac{dx}{\sqrt{a^2-x^2}}=\sin^{-1}\frac xa+C
$$

Substitution:

$$
\int f(g(x))g'(x)dx=\int f(u)du
$$

By parts:

$$
\int u\,dv=uv-\int v\,du
$$

## B.9 Definite Integral Properties

$$
\int_a^bf(x)dx=F(b)-F(a)
$$

$$
\int_a^bf(x)dx=-\int_b^af(x)dx
$$

$$
\int_{-a}^{a}f(x)dx=
\begin{cases}
2\int_0^af(x)dx,&f\text{ even},\\
0,&f\text{ odd}.
\end{cases}
$$

## B.10 Complex Numbers

$$z=a+ib,qquad i^2=-1$$

$$\bar z=a-ib$$

$$|z|=\sqrt{a^2+b^2}$$

$$z\bar z=|z|^2$$

$$
z=r(\cos\theta+i\sin\theta)=re^{i\theta}
$$

De Moivre:

$$
[r(\cos\theta+i\sin\theta)]^n
=r^n(\cos n\theta+i\sin n\theta)
$$

nth roots:

$$
w_k=r^{1/n}\left[
\cos\frac{\theta+2k\pi}{n}
+i\sin\frac{\theta+2k\pi}{n}
\right]
$$

for $k=0,1,\ldots,n-1$.
