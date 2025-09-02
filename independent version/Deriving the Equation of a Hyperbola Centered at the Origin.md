---
title: Adjunction
references:
tags:
  - In_Progress
reference: https://courses.lumenlearning.com/odessa-collegealgebra/chapter/deriving-the-equation-of-a-hyperbola-centered-at-the-origin/#:~:text=Solution-,The%20equation%20has%20the%20form%20y2a2%E2%88%92x,0%20%2C%20and%20solve%20for%20y%20.
Current date: 2025-04-14
---

1.  is this the proof for the fractional exponent function ? 
2. Why is b positive ? fractional exponent q can be negative ? 
3. why does b need to be positive when q $\in \left\{ 0 , + , -  \right\}$ 
4. the last sentence just mean that there is one unify way of writing a fractional number 

Definition 5.6.7 introduces **exponentiation for a positive real number $x$ raised to a rational exponent $q$**.

Here's a breakdown of the definition:

- **Positive Real Number ($x$):** The base of the exponentiation, denoted by $x$, must be a **positive real number** ($x > 0$). The process of constructing real numbers from rational numbers is detailed in Chapter 5, where real numbers are defined as formal limits of Cauchy sequences of rational numbers. Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero". 
	- detailed in Chapter 5, where real numbers are defined as formal limits of Cauchy sequences of rational numbers. Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero". 
		- what is a Cauchy sequences ? 
		-  Positive real numbers are also defined based on their Cauchy sequences being "positively bounded away from zero" what does this mean 
- **Rational Number ($q$):** The exponent, denoted by $q$, must be a **rational number**. Rational numbers are expressions of the form $a//b$ (or $a/b$), where $a$ and $b$ are integers and $b$ is non-zero.
	- why is ratinal number express this way ? 
- **Representing $q$ as $a/b$:** To define $x^q$, the rational exponent $q$ is first written as a fraction $a/b$, where $a$ is an integer and $b$ is a positive integer. The sources explain that every rational number $q$ can indeed be expressed in this form, regardless of whether $q$ is positive, negative, or zero.
- **The Formula ($x^q := (x^{1/b})^a$):** Once $q$ is written as $a/b$, $x^q$ is defined as **the $b$-th root of $x$, raised to the power of $a$**.
    - **$x^{1/b}$ (the $b$-th root of $x$):** This term refers to the $b$-th root of $x$, which is formally defined in Definition 5.6.4 as the supremum of the set ${y \in \mathbb{R} : y \geq 0 \text{ and } y^b \leq x}$. Lemma 5.6.5 confirms the existence of such $n$-th roots for non-negative real numbers.
    - **$(...)^a$ (raised to an integer power):** This involves exponentiation by an integer $a$. Definition 5.6.1 covers exponentiation by natural numbers ($x^0 = 1$, $x^{n+1} = x^n \times x$), and Definition 5.6.2 extends this to negative integers ($x^{-n} = 1/x^n$ for non-zero $x$).

**Well-Definedness and Consistency:**

- **Uniqueness of Representation:** A crucial point is that a rational number $q$ can be written as $a/b$ in multiple ways (e.g., $1/2 = 2/4 = 3/6$). Lemma 5.6.8 is dedicated to proving that **different expressions $a/b$ for the same rational $q$ will yield the same value for $x^q$**, thus ensuring that the definition is well-defined.
- **Consistency with Previous Definitions:** This new definition is noted to be **consistent with the earlier definitions of $x^{1/n}$ (nth root) and $x^n$ (integer exponentiation)**, meaning that if $q$ happens to be an integer or a simple reciprocal of an integer, the result from Definition 5.6.7 matches those earlier definitions.

This definition allows for positive real numbers to be raised to any rational power, building upon the foundational concepts of real numbers, rational numbers, integer exponentiation, and nth roots established earlier in the text. The theory of real exponentiation for exponents that are also real numbers (not just rational) is deferred to Section 6.7. 






