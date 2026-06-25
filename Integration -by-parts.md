# Integration by Parts

## Basic Formula
$\int u·dv = u·v - \int v·du$

**ILATE Rule:** Pehle wala function `u` select karne ke liye
I = Inverse trig → $sin^{-1}x, tan^{-1}x$  
L = Logarithmic → $lnx, logx$  
A = Algebraic → $x^n, x^2, x$  
T = Trigonometric → $sinx, cosx, tanx$  
E = Exponential → $e^x, a^x$

## Important Formulas
1. $\int x·e^x dx = x·e^x - e^x + C = e^x(x-1) + C$
2. $\int x·lnx dx = \frac{x^2}{2}lnx - \frac{x^2}{4} + C$
3. $\int lnx dx = x·lnx - x + C$
4. $\int x·sinx dx = -x·cosx + sinx + C$
5. $\int x·cosx dx = x·sinx + cosx + C$

## Reduction Formulas
6. $\int sin^n x dx = \frac{-sin^{n-1}x·cosx}{n} + \frac{n-1}{n}\int sin^{n-2}x dx$
7. $\int cos^n x dx = \frac{cos^{n-1}x·sinx}{n} + \frac{n-1}{n}\int cos^{n-2}x dx$

## Example
$\int x·e^x dx$
u = x, dv = $e^x dx$ → du = dx, v = $e^x$
= $x·e^x - \int e^x dx = x·e^x - e^x + C$

**Tip:** 2 functions ho to ILATE se `u` chuno, baaki `dv`
