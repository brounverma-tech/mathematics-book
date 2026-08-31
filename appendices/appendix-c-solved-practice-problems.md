# 📎 Appendix C: Solved Practice Problems

## C.1 Algebra

### Problem 1: Matrix Product

Given

$$
A=\begin{bmatrix}1&2\\0&3\end{bmatrix},\quad
B=\begin{bmatrix}4&1\\2&5\end{bmatrix},
$$

find $AB$.

**Solution:**

$$
AB=\begin{bmatrix}
1(4)+2(2)&1(1)+2(5)\\
0(4)+3(2)&0(1)+3(5)
\end{bmatrix}
=\begin{bmatrix}8&11\\6&15\end{bmatrix}.
$$

### Problem 2: Determinant

$$
\begin{vmatrix}2&1&0\\3&-1&2\\1&4&5\end{vmatrix}
$$

$$
=2[(-1)(5)-2(4)]-1[3(5)-2(1)]
$$

$$=2(-13)-13=-39.$$

### Problem 3: Inverse

For $A=\begin{bmatrix}3&1\\2&1\end{bmatrix}$,

$$|A|=3-2=1,$$

$$
A^{-1}=\begin{bmatrix}1&-1\\-2&3\end{bmatrix}.
$$

### Problem 4: Linear Equations

Solve $2x+y=7$, $x-y=2$.

Adding after suitable elimination gives $3x=9$, so $x=3$ and $y=1$.

## C.2 Differential Calculus

### Problem 5: Limit

$$
\lim_{x\to3}\frac{x^2-9}{x-3}
=\lim_{x\to3}(x+3)=6.
$$

### Problem 6: Continuity

Find $k$ if $f(x)=kx+2$ for $x<1$ and $f(x)=5$ for $x\ge1$ is continuous at 1.

$$k+2=5\Rightarrow k=3.$$

### Problem 7: Mixed Derivative

$$y=x^2e^x.$$

$$y'=2xe^x+x^2e^x=e^x(x^2+2x).$$

### Problem 8: Implicit Derivative

For $x^2+xy+y^2=7$:

$$2x+(xy'+y)+2yy'=0.$$

$$
y'(x+2y)=-(2x+y),
$$

$$
y'=-\frac{2x+y}{x+2y}.
$$

### Problem 9: LMVT

For $f(x)=x^3$ on $[0,2]$:

$$
\frac{f(2)-f(0)}{2}=4.
$$

Since $f'(x)=3x^2$,

$$3c^2=4\Rightarrow c=\frac{2}{\sqrt3}$$

in $(0,2)$.

## C.3 Integral Calculus

### Problem 10: Basic Integral

$$
\int(6x^2-4x+3)dx=2x^3-2x^2+3x+C.
$$

### Problem 11: Substitution

$$
\int\frac{2x}{x^2+5}dx.
$$

Let $u=x^2+5$. Then

$$=\ln(x^2+5)+C.$$

### Problem 12: By Parts

$$
\int x\sin xdx.
$$

Take $u=x$, $dv=\sin xdx$, so $v=-\cos x$:

$$
=-x\cos x+\int\cos xdx
=-x\cos x+\sin x+C.
$$

### Problem 13: Partial Fractions

$$
\int\frac{dx}{(x-1)(x+1)}.
$$

$$
\frac1{(x-1)(x+1)}=\frac12\left(\frac1{x-1}-\frac1{x+1}\right).
$$

Thus

$$
=\frac12\ln\left|\frac{x-1}{x+1}\right|+C.
$$

### Problem 14: Definite Integral

$$
\int_0^1(3x^2+2)dx=[x^3+2x]_0^1=3.
$$

## C.4 Complex Numbers

### Problem 15: Division

$$
\frac{2+3i}{1-i}
=\frac{(2+3i)(1+i)}2
=\frac{-1+5i}{2}.
$$

### Problem 16: Polar Form

For $z=-\sqrt3-i$:

$$r=2,$$

point lies in quadrant III, so a principal argument is $-5\pi/6$ (equivalently $7\pi/6$).

$$
z=2\operatorname{cis}\left(-\frac{5\pi}{6}\right).
$$

### Problem 17: Cube Roots of 8

$$8=8\operatorname{cis}(2k\pi).$$

$$
w_k=2\operatorname{cis}\frac{2k\pi}{3},\quad k=0,1,2.
$$

Roots:

$$2,\quad-1+\sqrt3i,\quad-1-\sqrt3i.$$
