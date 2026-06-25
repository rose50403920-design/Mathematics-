# Integration by Substitution / u-Substitution

## Basic Formula
$\int f(g(x))·g'(x) dx = \int f(u) du$ , where u = g(x) aur du = g'(x)dx

## Common Substitutions
1. $\int \frac{f'(x)}{f(x)} dx = ln|f(x)| + C$ 
   → u = f(x) rakho

2. $\int [f(x)]^n · f'(x) dx = \frac{[f(x)]^{n+1}}{n+1} + C$ , n ≠ -1
   → u = f(x) rakho

3. $\int e^{f(x)} · f'(x) dx = e^{f(x)} + C$
   → u = f(x) rakho

## Trig Substitutions
4. $\int \frac{1}{a^2 + x^2} dx = \frac{1}{a} tan^{-1}\frac{x}{a} + C$
   → x = a·tanθ rakho

5. $\int \frac{1}{\sqrt{a^2 - x^2}} dx = sin^{-1}\frac{x}{a} + C$
   → x = a·sinθ rakho

6. $\int \sqrt{a^2 - x^2} dx = \frac{x}{2}\sqrt{a^2-x^2} + \frac{a^2}{2}sin^{-1}\frac{x}{a} + C$

## Example
$\int 2x·cos(x^2) dx$
u = x² rakho → du = 2x dx
= $\int cos(u) du = sin(u) + C = sin(x^2) + C$

**Tip:** Jab integrand me koi function + uska derivative dono hon, to substitution lagao
