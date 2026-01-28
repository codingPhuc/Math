---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-12-31
amount of time:
learning score:
---
# Spivak-Style Rigor Notes Template (Obsidian paste)

Patty.

You want a **repeatable page structure** that lets you explain a concept like a mathematician without drowning in definitions. Here’s the template, then a fully written _model page_ you can copy.

---

## A. Template: “Concept / Theory” page (one page, readable, rigorous)

**Title.** _Concept name_ — one-line purpose (why it exists)

**0) Objects and standing assumptions** (2–5 lines)

- Fix the ambient universe (what kind of objects, what field/ring, what variable).
    
- State the domain restrictions that make expressions legal.
    

**1) Definitions used on this page** (only what is actually used)

- Definition (short, formal).
    
- Immediately after each definition: one “meaning sentence” in plain English.
    

**2) Main statement** (choose one label)

- **Theorem/Proposition:** the central fact you will reuse.
    
- **Lemma:** a technical tool you will reuse inside this section.
    
- **Corollary:** a quick consequence you’ll invoke later.
    

**3) Proof / Justification**

- If you **prove**: keep it tight; every line has a license (Def/Lemma/Alg/Calc).
    
- If you **cite**: write “(Cited)” and give the exact source; still state hypotheses.
    

**4) How to use it (operational form)** (very short)

- A 3–6 line “recipe” in words: what you check first, what you rewrite, what you solve for.
    

**5) Failure modes / pitfalls**

- 3–6 bullets: domain exclusions, hidden hypotheses, typical algebra traps.
    

That’s it. This structure forces rigor without turning your notes into a dictionary.

---

## B. Model page: Partial Fraction Decomposition (written in the structure above)

**Partial Fraction Decomposition** — rewriting a rational function into simpler terms that are easier to integrate and analyze.

### 0) Objects and standing assumptions

Let $F$ be a field (typically $\mathbb R$). Let $P,Q\in F[x]$ with $Q\neq 0$.  
Define the rational function $f(x)=\frac{P(x)}{Q(x)}$ on the domain $D={x\in F: Q(x)\neq 0}$.

### 1) Definitions used on this page

**Definition (Proper rational function).** $P/Q$ is **proper** if $\deg P < \deg Q$.  
Meaning: the fraction is “smaller” than $1$ at infinity; no polynomial part is hiding inside.

**Definition (Polynomial identity).** An equality $A(x)=B(x)$ of polynomials means the two polynomials are the same element of $F[x]$.  
Meaning: if it holds as polynomials, it holds for all $x$, and coefficients must match.

### 2) Main statements

**Lemma (Division Algorithm in $F[x]$).**  
For polynomials $P,Q\in F[x]$ with $Q\neq 0$, there exist unique $S,R\in F[x]$ such that  
$$  
P = SQ + R,\qquad \deg R < \deg Q.  
$$  
Interpretation: every rational function splits as  
$$  
\frac{P}{Q} = S + \frac{R}{Q},  
$$  
where $R/Q$ is proper.

**Theorem (Partial fraction form: distinct linear factors).**  
Assume $Q$ factors in $F[x]$ as  
$$  
Q(x)=c\prod_{i=1}^n (x-a_i),  
$$  
with $c\in F^\times$ and the $a_i$ distinct.  
Then for every proper rational function $R(x)/Q(x)$ there exist unique constants $A_1,\dots,A_n\in F$ such that on the domain $D$,  
$$  
\frac{R(x)}{Q(x)}=\sum_{i=1}^n \frac{A_i}{x-a_i}.  
$$

(Extensions you can list on the same page as “Variants,” not as new pages: repeated linear factors produce towers $\frac{A_{i,1}}{x-a_i}+\cdots+\frac{A_{i,k}}{(x-a_i)^k}$; irreducible quadratics require linear numerators.)

### 3) Proof / Justification (what you write in notes)

- **Division step:** Apply the Division Algorithm to write $P=SQ+R$ with $\deg R<\deg Q$. (License: Lemma)
    
- **Decomposition step:** Because $Q$ is a product of distinct linear factors, the theorem guarantees constants $A_i$ giving the sum form on $D$. (License: Theorem; you may cite if your course treats it as given)
    
- **Solving for constants:** Multiply by $Q(x)$ to get a polynomial identity in $F[x]$. Then determine $A_i$ by coefficient matching or evaluation at $x=a_i$ (where legal after clearing denominators). (License: polynomial identity)
    

### 4) How to use it (operational form)

- If $\deg P\ge \deg Q$, first replace $P/Q$ by $S + R/Q$ using the Division Algorithm.
    
- Factor $Q$ (over the relevant field).
    
- Write the **correct template** for numerators: constants over linear factors, linear over irreducible quadratic, and “tower” terms for repeats.
    
- Clear denominators to get a polynomial identity.
    
- Solve for the unknown coefficients.
    

### 5) Failure modes / pitfalls

- Forgetting the domain restriction $Q(x)\neq 0$ (the identity is on $D$, not at poles).
    
- Using the wrong numerator shape (e.g., putting a constant over an irreducible quadratic; it must be linear).
    
- Skipping the division step when $\deg P\ge \deg Q$.
    
- Treating an equality that holds for “some $x$” as a polynomial identity (you need “for all $x$” after clearing denominators).
    

---

If you want, I’ll do the same model-page treatment for **polynomial division lemma** (since your notes currently describe long division in words) and for **why coefficient matching is valid**. Those two are the backbone of your Section 7.4 write-up.