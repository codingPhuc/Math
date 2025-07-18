---
title: Adjunction
date: 2025-02-05
references: https://youtu.be/0EnklHkVKXI?feature=shared
tags:
  - In_Progress
reference:
---

# Table of Contents
- [Table of Contents](#table-of-contents)
- [Definition](#definition)
  - [What is Factoring](#what-is-factoring)
  - [Complete Factorization](#complete-factorization)
  - [Factoring Polynomial](#factoring-polynomial)
- [Formula](#formula)
  - [Greatest Common Factor](#greatest-common-factor)
  - [Quick Technique for Factoring](#quick-technique-for-factoring)
  - [Perfect Square Trinomial](#perfect-square-trinomial)
    - [Sum Form](#sum-form)
    - [Difference Form](#difference-form)
  - [Difference of Squares](#difference-of-squares)
  - [Sum of Cubes](#sum-of-cubes)
  - [Difference of Cubes](#difference-of-cubes)
- [Practice Exercise](#practice-exercise)
  - [Factoring Quadratic Polynomials](#factoring-quadratic-polynomials)
    - [Factoring Polynomials (a = 1)](#factoring-polynomials-a--1)
  - [Different of Square Factoring](#different-of-square-factoring)
    - [Factoring Quadratic Polynomials with GCF](#factoring-quadratic-polynomials-with-gcf)
  - [Factoring Quadratic Polynomials with Greater than 2 Degree](#factoring-quadratic-polynomials-with-greater-than-2-degree)
    - [Factoring Polynomials (Trinomials) in General](#factoring-polynomials-trinomials-in-general)
  - [Solving Factor Polynomials](#solving-factor-polynomials)

# Definition
## What is Factoring
Factoring is the process of determining what we multiply to get a given quantity.
$$
12 = (2)(6)
$$
$$
12 = (-2)(-6)
$$
There are many other ways to [[Factor]] 12, but these are the most common ones.

## Complete Factorization
The process of breaking down a factor to its prime numbers.
$$
12 = (2)(2)(3)
$$

## Factoring Polynomial
Factoring polynomial is the same process. We continue to factor until we cannot factor again.
$$
x^2 - 16 = (x + 4)(x - 4)
$$
Likewise, this is not a complete factor.
$$
x^4 - 16 = (x^2 + 14)(x^2 - 14)
$$
The complete factor of the above is:
$$
x^4 - 16 = (x^2 + 4)(x + 2)(x - 2)
$$

# Formula
## Greatest Common Factor
The best thing to do is use the greatest common factor to see if there is a factor that is common to all terms.
$$
a(b+c) = ab + ac
$$
1. **Common Factor**  
   Example: 
   - 12: (**1**,12), (**2**,6), (3,**4**)  
   - 28: (**1**,28), (**2**,14), (**4**,7)  
   Factors that appear the most in two or more variables:
   - $12x^2$: 1, 2, 3, 4, 6, 12, x, $x^2$
   - $15x^4$: 1, 3, 5, 15, x, $x^2$, $x^3$, $x^4$
2. **Greatest Common Factors (Biggest Shared Factors)**
   - In the first equation, the greatest common factor is 4.
   - In the second equation, the greatest common factor is $3x^2$.

## Quick Technique for Factoring
The diamond technique:
$$
ax^2 + bx + c
$$
![[6.2 Factorings 2025-02-05 15.42.40.excalidraw]]
$$
(x + \#1)(x + \#2)
$$
$$
\begin{aligned}
\left\{
\begin{array}{l}
\text{if } a = 1 \to \text{ do diamond factor} \\
a \neq 1 \to \text{ do group factor}
\end{array}
\right.
\end{aligned}
$$

What to check for in the first term polynomial:
- Is it in order?
- Is the first term positive? (Helps identify if you factor out a negative)
- Factor out the GCF
- Then use the diamond method to factor and simplify further

Proof:
$$
x^2 - 13xy + 30y^2 = x^2 - 10xy - 3xy + 30y^2 = x(x - 10y) - 3y(x - 10y) = (x - 3y)(x - 10y)
$$
![[Factoring Polynomials 2025-02-06 12.35.58.excalidraw]]
- The answer gives us the correct value for factoring.

## Perfect Square Trinomial
### Sum Form
$$
a^2 + 2ab + b^2 = (a + b)^2
$$
### Difference Form
$$
a^2 - 2ab + b^2 = (a - b)^2
$$

## Difference of Squares
$$
a^2 - b^2 = (a + b)(a - b)
$$

## Sum of Cubes
$$
a^3 + b^3 = (a + b)(a^2 - ab + b^2)
$$
- The sum of cubes and the difference of cubes have different signs in the first and second parentheses.

## Difference of Cubes
$$
a^3 - b^3 = (a - b)(a^2 + ab + b^2)
$$
- The sum of cubes and the difference of cubes have different signs in the first and second parentheses.

# Practice Exercise
Find the GCF of: $-18y^2, -63y^3, 27y^4$
1. Start with the lowest number in the equations:
   - $-18x^2$: (1, 18), (9, 2), $y^2$
2. Here we see that 9 is divided by 63 and 27.
3. So the GCF is $9y^2$.

$$
49x - 35 = 7(7x - 5)
$$
This uses the [[Factoring Polynomials#greatest common factor]] 7.

Find the GCF of: $5x^2y^4(2n + n) - (2n + n)$
4. We can see that the right and left equations are separated by a negative sign.
5. We can see there is a common factor (2n + n).
6. So we will factor out (2n + n) in the term we will get:
   $$(2n + n)(5x^2y^4 - 1)$$

Find the GCF of: $xy + 2x + 3y + 6$
1. First, we will get rid of the common factor on the two equations from the left and right:
   $$x(y + 2) + 3(y + 2)$$
2. Then we will put the common factor (y + 2) out of the term:
   $$(y + 2)(x + 3)$$

Find the GCF of: $3a^2 + 4ab + 3a + 4b$
3. First, we will switch the position of 4ab and 3a:
   $$3a^2 + 3a + 4ab + 4b$$
4. Then we will get rid of the common factor on the two equations from the left and right:
   $$3a(a + 1) + 4b(a + 1)$$
5. Then we will put the (a + 1) out of the term:
   $$(a + 1)(3a + 4b)$$

## Factoring Quadratic Polynomials
$$
4x^2 + 10x - 6 = (2x - 1)(2x + 6)
$$

### Factoring Polynomials (a = 1)
$$
x^2 + 6x - 9 = (x + 3)(x + 3) = (x + 3)^2
$$

## Different of Square Factoring
1. Are the terms in order?
2. Is the first term positive?
3. Is there a GCF?
4. Then count the number of terms:
$$
a^2 - b^2 = (a + b)(a - b)
$$
Exercise:
$$
x^2 - 16 = x^2 - 4^2 = (x - 4)(x + 4)
$$
1. Yes
2. Yes
3. No
4. The number of terms is 2

$$
y^2 + 64 \neq
$$
1. No
2. Yes
3. No
4. The number of terms is 2
$$
\to \text{ there is no way to do the diamond problem}
$$

$$
y^2 - \frac{25}{81} = y^2 - \left(\frac{5}{9}\right)^2 = (y - \frac{5}{9})(y + \frac{5}{9})
$$
1. Yes
2. Yes
3. No
4. The number of terms is 2

$$
9y^3 - 25y = y(9y^2 - 25) = y(3y - 5)(3y + 5)
$$
1. Yes
2. Yes
3. Yes
4. The number of terms is 2

$$
80y^4 - 5 = 5(16y^4 - 1) = 5(4y^2 - 1)(4y^2 + 1)
$$
1. Yes
2. Yes
3. Yes
4. The number of terms is 2

### Factoring Quadratic Polynomials with GCF
What to check for in the first term polynomial:
- Is it in order?
- Is the first term positive? (Helps identify if you factor out a negative)
- Factor out the GCF
- Then use the diamond method to factor and simplify further

$$
5x^5 - 25x^4 - 30x^3 = 5x^3[x^2 - 5x - 6] = 5x^3(x - 6)(x + 1)
$$
$$
3x^4 - 3x^3 - 36x^2 = 3x^2(x^2 - x - 12) = 3x^2(x - 4)(x + 3)
$$

## Factoring Quadratic Polynomials with Greater than 2 Degree
Solving this equation by using the [[Factoring Polynomials#Difference of Squares]]:
$$
x^4 - 25 = (x^2 + 5)(x^2 - 5)
$$
$$
x^4 + x^2 - 20 = (x^2 - 4)(x^2 + 5) = (x - 2)(x + 2)(x^2 + 5)
$$

### Factoring Polynomials (Trinomials) in General
Exercise:
$$
\begin{array}{l}
2x^2 + 13x - 7 \\
= 2x^2 - 1x + 14x - 7 \\
= x(2x - 1) + 7(2x - 1) \\
= (x + 7)(2x - 1)
\end{array}
$$
![[6.2 Factorings 2025-02-05 16.14.11.excalidraw]]

$$
\begin{array}{l}
8x^2 - 22x + 5 \\
= 2x(4x - 1) - 5(4x - 1) \\
= (2x - 5)(4x - 1)
\end{array}
$$
![[6.2 Factorings 2025-02-05 16.21.50.excalidraw]]

Factoring the greatest common division before using the diamond method:
$$
\begin{array}{l}
6xy^2 + 33xy - 18x \\
= 3x[2y^2 + 11y - 6] \\
= 3x[2y^2 + 12y - y - 6] \\
= 3x[2y(y + 6) - (y + 6)] \\
= 3x(y + 6)(2y - 1)
\end{array}
$$
![[6.2 Factorings 2025-02-05 16.24.19.excalidraw]]

Factoring using the diamond method does not have to be $x^2, x$:
$$
\begin{array}{l}
25x^4 - 20x + 4 \\
= 25x^4 - 10x^2 - 10x^2 + 4 \\
= 5x^2(5x^2 - 2) - 2(5x^2 - 2) \\
= (5x^2 - 2)(5x^2 - 2) \\
= (5x^2 - 2)^2
\end{array}
$$
![[6.2 Factorings 2025-02-05 16.39.55.excalidraw]]

## Solving Factor Polynomials
$$
\begin{array}{l}
y^2 - 3y - 18 = 0 \\
(y - 6)(y + 3) = 0
\end{array}
$$
$$
\left\{
\begin{array}{l}
y - 6 = 0 \\
y + 3 = 0
\end{array}
\right.
\implies
\left\{
\begin{array}{l}
y = 6 \\
y = -3
\end{array}
\right.
$$

$$
\begin{array}{l}
y^2 + 5y + 6 = 0 \\
(y + 3)(y + 2) = 0
\end{array}
$$
$$
\left\{
\begin{array}{l}
y + 2 = 0 \\
y + 3 = 0
\end{array}
\right.
\implies
\left\{
\begin{array}{l}
y = -2 \\
y = -3
\end{array}
\right.
$$

$$
\begin{array}{l}
25y^2 - 29y + 4 = 0 \\
25y(y - 1) - 4y(y - 1) = 0 \\
(25y - 4y)(y - 1) = 0
\end{array}
$$
$$
\left\{
\begin{array}{l}
y - 1 = 0 \\
25y - 4 = 0
\end{array}
\right.
\implies
\left\{
\begin{array}{l}
y = 1 \\
y = \frac{4}{25}
\end{array}
\right.
$$

$$
\begin{array}{l}
y(y - 4) = 5 \\
y(y - 4) - 5 = 0 \\
y^2 - 4y - 5 = 0 \\
(y - 5)(y + 1) = 0
\end{array}
$$
$$
\left\{
\begin{array}{l}
y + 1 = 0 \\
y - 5 = 0
\end{array}
\right.
\implies
\left\{
\begin{array}{l}
y = -1 \\
y = 5
\end{array}
\right.
$$

$$
\begin{array}{l}
(3y - 2)(2y^2 - 13y + 15) = 0 \\
(3y - 2)(y + 1)(2y - 15) = 0
\end{array}
$$
$$
\left\{
\begin{array}{l}
3y - 2 = 0 \\
2y - 15 = 0 \\
y + 1 = 0
\end{array}
\right.
\implies
\left\{
\begin{array}{l}
y = \frac{2}{3} \\
y = -1 \\
y = \frac{15}{2}
\end{array}
\right.
$$
