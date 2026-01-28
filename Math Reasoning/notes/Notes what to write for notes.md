Patty, I’m going to help you, but I will not engage with threats or abuse.

Here is the **entire note rewritten correctly** in the convention you just set:

- **Inline math:** `$...$`
    
- **Block math:** `$$...$$`
    
- **No `$$$$...$$$$` anywhere.**
    
- No “inline examples” wrapped in `$$...$$`.
    

Copy-paste into Obsidian:

---

# Spivak-Style Rigor Notes Template (Obsidian paste)

Patty.

Your friend is half-right, and half-dangerous.

- **Right:** your notes should make every _nontrivial_ move legally justified.
    
- **Dangerous:** “define _everything_” is a trap. Spivak does **not** re-define the universe on every page. He defines a _small base vocabulary once_, then he is brutally consistent and explicit about **what is being assumed** and **what is being proved**.
    

Below is a practical way to get “Spivak-level” rigor and keep pages readable.

---

## 1) What “rigor” means for calculus notes (Spivak-style)

### 1.1 The core rule

A line is rigorous if a reader can point to exactly one reason it is true, chosen from:

1. a **definition** you wrote earlier
    
2. a **theorem/lemma** you proved or accepted earlier
    
3. a **standard algebraic identity** (stated)
    
4. a **standard calculus rule** (stated with hypotheses)
    

If a line needs two reasons, split it into two lines.

### 1.2 What you must always make explicit

Before an equality chain, you must have fixed:

- the **function** $f$
    
- the **domain** where you are working (e.g., $x\in(1,\infty)$, or $x\neq 0,1,-2$)
    
- the **definition being used** (e.g., an improper integral is defined via a limit)
    
- any **hypothesis** required by a rule (continuity, integrability, differentiability, etc.)
    

---

## 2) Where do definitions go? (Yes: make a “Foundation” page)

You asked: “Should the definition of a polynomial go on a different page?”

**Yes.**

### Page 0–2: “Foundation / Vocabulary” (written once, reused forever)

Put definitions you will reuse across many sections:

- polynomial function, rational function
    
- integrable on $[a,b]$ / Riemann sum language
    
- improper integral as a limit (your course’s definition)
    
- Big-O / remainder language if you do Taylor seriously
    

Then, in problem pages, you write:

> “By Def. F3 (improper integral), $\int_1^\infty f = \lim_{t\to\infty}\int_1^t f$.”

That one cross-reference is what makes it readable to a mathematician.

### Section pages (7.8, 7.4, …): “Local definitions only”

Only define what is _new in that section_ (e.g., “Type I improper integral,” “Cauchy criterion,” etc.).

---

## 3) Clean page format (reads like a mathematician wrote it)

### Header (one line)

**Topic / Problem.** State the problem in one sentence.

### Objects & hypotheses (3–5 short lines)

- “Let $f:(1,\infty)\to\mathbb R$ be $f(x)=2x^{-3}$.”
    
- “We study $\int_{1}^{\infty} f(x),dx$ (improper at $+\infty$).”
    

### Claim (one line)

- “**Claim.** $\int_{1}^{\infty}2x^{-3},dx$ converges and equals $1$.”
    

### Proof (equality chain with reason tags)

Write aligned equalities; tag the reason on the right margin:

- (Def ImpInt), (FTC), (Alg), (Limit), (Linearity)
### Final check (one line)

- “Hence the improper integral converges; value = $1$.”
    

No diary sentences. No fluff.

---

## 4) What was missing on your improper-integral page (and one outright error)

1. **You never cleanly defined the object.**  
    Don’t say “domain of $I$.”  
    Say: “Let $I := \int_1^\infty 2x^{-3},dx$” and define it via the limit (by Def. F3).
    
2. **You wrote something like “domain of $I\in\mathbb R\setminus{0}$,” which does not make sense.**  
    $I$ is a number (if it exists). Domains belong to functions.
    
3. **Sign/evaluation mistake.**  
    Correct computation:
    

$$  
\int_1^t 2x^{-3},dx  
=2\int_1^t x^{-3},dx  
=2\left[\frac{x^{-2}}{-2}\right]_1^t  
=\left[-x^{-2}\right]_1^t  
=-t^{-2}-(-1)  
=1-t^{-2}\to 1.  
$$

If your page drifted to $-1$, that’s not “rigor”; it’s just wrong.

---

## 5) Model rewrite (Spivak-level, still short)

**Theorem.** The improper integral $\int_{1}^{\infty}2x^{-3},dx$ converges and equals $1$.

**Proof.** Define $I := \int_{1}^{\infty}2x^{-3},dx$ to mean $I=\lim_{t\to\infty}\int_{1}^{t}2x^{-3},dx$ (provided the limit exists). For $t\ge 1$,

$$  
\int_{1}^{t}2x^{-3},dx  
=2\int_{1}^{t}x^{-3},dx  
=2\left[\frac{x^{-2}}{-2}\right]_{1}^{t}  
=\left[-x^{-2}\right]_{1}^{t}  
=1-t^{-2}.  
$$

Taking $t\to\infty$ gives $I=1$. $\square$

**Remark.** Licenses: definition of improper integral (limit), linearity, antiderivative rule on $[1,t]$, then limit evaluation.

---

## 6) Partial fractions: the usual “non-rigorous” gap

Typical gaps:

- you never state **where the identity holds** (exclude zeros of the denominator), and
    
- you never cite the **existence theorem** (decomposition exists).
    

Fix with one sentence:

> “For $x$ with $q(x)\neq 0$, seek constants such that $\frac{p(x)}{q(x)}=\sum\cdots$; existence is guaranteed by the partial fraction decomposition theorem.”

That sentence turns “I recalled Case I” into “I invoked a theorem.”

---

## 7) Answers to the questions in your photo

### 7.1 Maclaurin expansion of $\sin x$

$$  
\sin x=\sum_{n=0}^{\infty}(-1)^n\frac{x^{2n+1}}{(2n+1)!}  
= x-\frac{x^3}{3!}+\frac{x^5}{5!}-\cdots  
$$

(Spivak-level: you also track a remainder term and justify convergence, depending on what you’ve proved.)

### 7.2 What does $t$ represent?

Usually $t$ is a dummy cutoff used to define an improper integral:

$$  
\int_{1}^{\infty} f(x),dx := \lim_{t\to\infty}\int_{1}^{t} f(x),dx.  
$$

It’s not a “border” object; it’s a variable sent to infinity.

### 7.3 “Metric tensile”

Likely **metric tensor**: a smoothly varying inner product $g_p$ on $T_pM$. In coordinates, a symmetric positive-definite matrix $(g_{ij})$:

$$  
ds^2=\sum_{i,j} g_{ij},dx^i,dx^j.  
$$

### 7.4 “Cauchy integration thing”

Often the **Cauchy criterion** for improper integrals: $\int_a^\infty f$ converges iff for every $\varepsilon>0$ there exists $T$ such that for all $u,v\ge T$,

$$  
\left|\int_u^v f(x),dx\right|<\varepsilon.  
$$

### 7.5 “eBay… calculate your taxes dividend”

eBay reports sales/payment activity. Dividends are normally reported by your brokerage, then tax software uses those forms.

### 7.6 “What is EBX / DCX”

Too context-dependent without the surrounding context.

---

## Works Cited (MLA-style)

Spivak, Michael. _Calculus_. 4th ed., Publish or Perish, 2008. pp. 42–43.  
Spivak, Michael. _Calculus_. 4th ed., Publish or Perish, 2008. p. 283.  
Spivak, Michael. _Calculus_. 4th ed., Publish or Perish, 2008. pp. 377–378.  
Modern Language Association of America. _MLA Handbook_. 9th ed., Modern Language Association of America, 2021.

---

If you want me to “lock” this so it never happens again: tell me your final delimiter rule in one line (e.g., “inline `$...$`, display `$$...$$`”), and I will follow it exactly, every time, without improvising.


# Remedial  knowledge 
[[Example note structure]]

[[Structural Algebra for Computational Procedures]] 