---
title: adje
date: 2024-06-03T12:50:42-04:00
references: https://tutorial.math.lamar.edu/Problems/Alg/IntegerExponents.aspx
tags:
  - In_Progress
---

# formula  for integer exponent  
Here's the list of formulas with headings describing their names and proofs for each:
# Exponent Rules and Proofs
Here's the list of formulas with headings describing their names and proofs for each:

**# Exponent Rules and Proofs

## 1. Product Rule for Exponents
**Formula:**  
$$ a^n \cdot a^m = a^{n+m} $$

**Proof:**  
Using the definition of exponents:  
$$ a^n = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}, \quad a^m = \underbrace{a \cdot a \cdot \ldots \cdot a}_{m \text{ times}}. $$  
Multiplying these together gives:  
$$ a^n \cdot a^m = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n+m \text{ times}} = a^{n+m}. $$

---

## 2. Power Rule for Exponents
**Formula:**  
$$ (a^n)^m = a^{nm} $$

**Proof:**  
Using the definition of exponents:  
$$ (a^n)^m = \underbrace{a^n \cdot a^n \cdot \ldots \cdot a^n}_{m \text{ times}}. $$  
Expanding $a^n$:  
$$ a^n = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}. $$  
Therefore:  
$$ (a^n)^m = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n \cdot m \text{ times}} = a^{nm}. $$

---

## 3. Quotient Rule for Exponents
**Formula:**  
$$ \frac{a^n}{a^m} =  
\begin{cases}  
a^{n-m} & \text{if } n \geq m, \\  
\frac{1}{a^{m-n}} & \text{if } n < m,  
\end{cases}
\quad a \neq 0. $$

**Proof:**  
For $n \geq m$, we cancel $m$ terms from the numerator and denominator:  
$$ \frac{\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}}{\underbrace{a \cdot a \cdot \ldots \cdot a}_{m \text{ times}}} = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n-m \text{ times}} = a^{n-m}. $$  

For $n < m$, invert the base:  
$$ \frac{1}{\frac{\underbrace{a \cdot a \cdot \ldots \cdot a}_{m \text{ times}}}{\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}}} = \frac{1}{a^{m-n}}. $$

---

## 4. Distributive Rule of Exponents over Multiplication
**Formula:**  
$$ (ab)^n = a^n b^n $$

**Proof:**  
Using the definition of exponents:  
$$ (ab)^n = \underbrace{(ab) \cdot (ab) \cdot \ldots \cdot (ab)}_{n \text{ times}}. $$  
Rewriting each term:  
$$ (ab)^n = \underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}} \cdot \underbrace{b \cdot b \cdot \ldots \cdot b}_{n \text{ times}} = a^n b^n. $$

---

## 5. Distributive Rule of Exponents over Division
**Formula:**  
$$ \left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}, \quad b \neq 0. $$

**Proof:**  
Using the definition of exponents:  
$$ \left(\frac{a}{b}\right)^n = \underbrace{\frac{a}{b} \cdot \frac{a}{b} \cdot \ldots \cdot \frac{a}{b}}_{n \text{ times}}. $$  
Combine the terms in the numerator and denominator:  
$$ \frac{\underbrace{a \cdot a \cdot \ldots \cdot a}_{n \text{ times}}}{\underbrace{b \cdot b \cdot \ldots \cdot b}_{n \text{ times}}} = \frac{a^n}{b^n}. $$

---

## 6. Negative Exponent Rule for Division
**Formula:**  
$$ \left(\frac{a}{b}\right)^{-n} = \left(\frac{b}{a}\right)^n = \frac{b^n}{a^n}. $$

**Proof:**  
From the negative exponent rule, invert the base:  
$$ \left(\frac{a}{b}\right)^{-n} = \frac{1}{\left(\frac{a}{b}\right)^n}. $$  
Simplify:  
$$ \frac{1}{\frac{a^n}{b^n}} = \frac{b^n}{a^n}. $$

---

## 7. Negative Exponent Rule for Multiplication
**Formula:**  
$$ (ab)^{-n} = \frac{1}{(ab)^n} $$

**Proof:**  
From the negative exponent rule:  
$$ (ab)^{-n} = \frac{1}{(ab)^n}. $$  
Since $(ab)^n = a^n b^n$, we have:  
$$ \frac{1}{(ab)^n} = \frac{1}{a^n b^n}. $$

---

## 8. Reciprocal Rule of Negative Exponents
**Formula:**  
$$ \frac{1}{a^{-n}} = a^n $$

**Proof:**  
From the definition of negative exponents:  
$$ a^{-n} = \frac{1}{a^n}. $$  
Taking the reciprocal:  
$$ \frac{1}{a^{-n}} = \frac{1}{\frac{1}{a^n}} = a^n. $$

---

## 9. Division Rule with Negative Exponents
**Formula:**  
$$ \frac{a^{-n}}{b^{-n}} = \frac{b^n}{a^n}. $$

**Proof:**  
Using the reciprocal rule for negative exponents:  
$$ a^{-n} = \frac{1}{a^n}, \quad b^{-n} = \frac{1}{b^n}. $$  
Substituting into the formula:  
$$ \frac{\frac{1}{a^n}}{\frac{1}{b^n}} = \frac{b^n}{a^n}. $$

---

## 10. Power Rule for Products with Exponents
**Formula:**  
$$ (a^n b^m)^k = a^{nk} b^{mk} $$

**Proof:**  
Using the distributive property of exponents:  
$$ (a^n b^m)^k = \underbrace{(a^n b^m) \cdot (a^n b^m) \cdot \ldots \cdot (a^n b^m)}_{k \text{ times}}. $$  
Combine terms for $a$ and $b$:  
$$ a^{nk} b^{mk}. $$

---

## 11. Power Rule for Fractions with Exponents
**Formula:**  
$$ \left(\frac{a^n}{b^m}\right)^k = \frac{a^{nk}}{b^{mk}}. $$

**Proof:**  
Using the distributive property of exponents:  
$$ \left(\frac{a^n}{b^m}\right)^k = \underbrace{\frac{a^n}{b^m} \cdot \frac{a^n}{b^m} \cdot \ldots \cdot \frac{a^n}{b^m}}_{k \text{ times}}. $$  
Combine terms in the numerator and denominator:  
$$ \frac{\underbrace{a^n \cdot a^n \cdot \ldots \cdot a^n}_{k \text{ times}}}{\underbrace{b^m \cdot b^m \cdot \ldots \cdot b^m}_{k \text{ times}}} = \frac{a^{nk}}{b^{mk}}. $$


$$\begin{aligned}&1\cdot a^na^m=a^{n+m}\\&2\cdot(a^n)^m=a^{nm}\\\\&3\cdot\frac{a^n}{a^m}=\left\{\begin{array}{c}a^{n-m}\\\\\frac1{a^{m-n}}\end{array}\right.,\quad a\neq\\\\&4.\left(ab\right)^n=a^nb^n\\\\&5.\left(\frac ab\right)^n=\frac{a^n}{b^n},\quad b\neq0\\\\&6.\left(\frac ab\right)^{-n}=\left(\frac ba\right)^n=\frac{b^n}{a^n}\\\\&7.\left(ab\right)^{-n}=\frac1{\left(ab\right)^n}\\\\&8.\frac1{a^{-n}}=a^n\\\\&9.\frac{a^{-n}}{b^{-n}}=\frac{b^{m}}{a^n}\\\\&10.\left(a^nb^m\right)^k=a^{nk}b^{mk}\\\\&11.\left(\frac{a^n}{b^m}\right)^k=\frac{a^{nk}}{b^{mk}}\end{aligned}$$

## Practice Problem    
### For problems 1 – 4 evaluate the given expression and write the answer as a single number with no exponents.
$-6^2 +4\cdot{3^2}$ $=-36   +4 \cdot{9} =0$

### For problems 5 – 9 simplify the given expression and write the answer with only positive exponents.


$\frac{2x^{4}y^{-1}}{x^{-6}y^{6}}=\frac{2x^{10}}{y^{9}}$

$$
\left(\frac{2^{2}y^{-1}x^{-3}}{x^{-4}2^{6}y^{4}}\right)^{-4}=\frac{2^{-8}y^{4}x^{12}} {x^{32} z^{-24} y^{-16}}=\frac{z^{16}y^{20}}{x^{20}}
$$ 