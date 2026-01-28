Patty.

Here is the question list in the exact prompt-page style you showed, designed to cover everything we talked about so far. It is Obsidian-pasteable, and every math expression is written to render (only $...$ and $$...$$).

---

# Stewart §7.8 + Spivak — Improper integrals, Cauchy, tails (Prompt Pages)

> [!info] How to use (no answers)  
> Fill each block from memory. Do not compute unless a prompt explicitly asks.  
> Order of attack: ambient system + legality → classify (Type 1/2) → write the correct limit definition → use tail/Cauchy logic → then compute (if needed).

## B. Type 1 improper integrals — infinite interval means a limit of truncations

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- What hypothesis on $f$ makes $\int_a^t f(x),dx$ meaningful for every finite $t>a$? x 
    
- What domain restriction must you silently track even if the notation hides it?
    

### 1) Definitions used on this page

- Write the definition of a Type 1 improper integral by filling in the blank:  
    $$  
    \int_a^{\infty} f(x),dx := \lim_{t\to\infty} \int_a^t f(x),dx.  
    $$
    
- What does “converges” mean in this definition?
    
- What does “diverges” mean in this definition?
    

### 2) Main statement

- Define $A(t)$ and state what it represents:  
    $$  
    A(t) := \int_a^t f(x),dx.  
    $$
    
- Restate convergence of $\int_a^{\infty} f$ as a statement about $\lim_{t\to\infty}A(t)$.
    

### 3) Proof / Justification

- Why is truncation not a trick but the mechanism that makes the definition meaningful?
    
- What is the difference between a statement about $\int_a^t$ (finite) and a statement about $\int_a^{\infty}$ (limit)?
    

### 4) How to use it (operational form)

- Write a 3–6 line recipe: choose $t$ → compute $\int_a^t f$ → take $\lim_{t\to\infty}$ → conclude.
    

### 5) Failure modes / pitfalls

- What is wrong with “plug in infinity” into an antiderivative?
    
- List three distinct ways the limit can fail (give the names, not examples).
    

---

## C. Type 2 improper integrals — infinite discontinuity means one-sided limits and splitting

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- List the three locations for a vertical blow-up: at $a$, at $b$, or at an interior $c$.
    
- What does “integrable on every finite subinterval avoiding the blow-up point” mean in words?
    

### 1) Definitions used on this page

- If $f$ blows up at $b$, write the definition:  
    $$  
    \int_a^b f(x),dx := \lim_{t\to b^-}\int_a^t f(x),dx.  
    $$
    
- If $f$ blows up at $a$, write the definition:  
    $$  
    \int_a^b f(x),dx := \lim_{t\to a^+}\int_t^b f(x),dx.  
    $$
    
- If $f$ blows up at an interior $c$, write the split definition (shape only):  
    $$  
    \int_a^b f(x),dx := \int_a^c f(x),dx + \int_c^b f(x),dx,  
    $$  
    and state how each piece is defined.
    

### 2) Main statement

- For an interior $c$, what must be true about both pieces for the whole integral to converge?
    

### 3) Proof / Justification

- Why is splitting at $c$ logically necessary (what does it prevent)?
    
- Why is “it’s just one point” not a valid argument here?
    

### 4) How to use it (operational form)

- Classification recipe: locate the blow-up point → choose correct one-sided limit(s) → rewrite → then compute.
    

### 5) Failure modes / pitfalls

- What is the common direction mistake: $t\to b^-$ versus $t\to b^+$?
    
- What goes wrong if you write one limit when two are required?
    

---

## D. Cauchy sequences, triangle inequality, and the $\varepsilon/2$ move

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- What structure do you need to even write $|a_n-a_m|<\varepsilon$ with $\varepsilon>0$?
    
- What property of $\mathbb{R}$ is the reason “Cauchy implies convergent” works there?
    

### 1) Definitions used on this page

- Write the full Cauchy definition with quantifiers:  
    $$  
    \forall \varepsilon>0\ \exists N\ \forall m,n\ge N:\ |a_m-a_n|<\varepsilon.  
    $$
    
- State triangle inequality in the exact form you use:  
    $$  
    |x+y|\le |x|+|y|.  
    $$
    

### 2) Main statement

- State “limit implies Cauchy” as a sentence (no proof).
    
- State “Cauchy implies limit” and state the needed hypothesis on the ambient system.
    

### 3) Proof / Justification

- Write the decomposition used in the proof:  
    $$  
    a_n-a_m=(a_n-L)+(L-a_m).  
    $$
    
- Show where triangle inequality is applied (one line).
    
- Explain why $\varepsilon/2$ is chosen: what inequality would you get if each term were only forced to be $<\varepsilon$?
    

### 4) How to use it (operational form)

- If you do not know $L$, what does the Cauchy condition let you test anyway?
    

### 5) Failure modes / pitfalls

- What breaks if you try to claim “Cauchy implies convergent” in $\mathbb{Q}$?
    
- What is the precise mistake in treating “field” as sufficient for Cauchy arguments?
    

---

## E. Cauchy tails for improper integrals — the tail criterion

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- Define $A(t)$ and state what kind of variable $t$ is (index set: real cutoffs).
    
- Translate “$t\to\infty$” into a quantifier phrase (in words).
    

### 1) Definitions used on this page

- Write the Cauchy condition for $A(t)$:  
    $$  
    \forall \varepsilon>0\ \exists T\ \forall u,v\ge T:\ |A(u)-A(v)|<\varepsilon.  
    $$
    
- Write the identity connecting differences to tails:  
    $$  
    A(u)-A(v)=\int_v^u f(x),dx.  
    $$
    

### 2) Main statement

- State the tail criterion for convergence of $\int_a^{\infty} f$:  
    $$  
    \forall \varepsilon>0\ \exists T\ \forall u,v\ge T:\ \left|\int_u^v f(x),dx\right|<\varepsilon.  
    $$
    

### 3) Proof / Justification

- Derive the tail criterion from the Cauchy condition in exactly two lines using $A(u)-A(v)=\int_v^u f$.
    
- Explain in one sentence why this is the analogue of “tail sums” for series.
    

### 4) How to use it (operational form)

- When would you use tail bounds instead of computing $\lim_{t\to\infty}\int_a^t f$ directly?
    
- Write the 3–6 line “tail proof skeleton” (quantifiers first, then bounding steps).
    

### 5) Failure modes / pitfalls

- Why is it dangerous to omit absolute values in the tail criterion?
    
- What is the “type mismatch” mistake with using integer indices $m,n$ instead of real cutoffs $u,v$?
    

---

## F. Two-sided infinity — split definition vs symmetric truncation (principal value trap)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- Write two different candidate meanings of $\int_{-\infty}^{\infty} f(x),dx$ (describe them in words).
    

### 1) Definitions used on this page

- Split definition shape (choose a real $a$):  
    $$  
    \int_{-\infty}^{\infty} f(x),dx := \int_{-\infty}^{a} f(x),dx + \int_{a}^{\infty} f(x),dx  
    $$  
    and state the convergence requirement.
    
- Symmetric truncation (principal value style object):  
    $$  
    \lim_{N\to\infty}\int_{-N}^{N} f(x),dx.  
    $$
    

### 2) Main statement

- State the warning claim: the symmetric limit can exist even when the split improper integral does not.
    
- Name the phenomenon this hides (one sentence).
    

### 3) Proof / Justification

- Explain “fake cancellation” in one sentence.
    
- Explain why splitting prevents fake cancellation in one sentence.
    

### 4) How to use it (operational form)

- When given $\int_{-\infty}^{\infty}$, what rewrite do you do first before any computation?
    

### 5) Failure modes / pitfalls

- What is the mistake in treating the symmetric limit as the definition by default?
    
- What exact condition do you forget if you only check the symmetric truncations?
    

---

## G. Setup-only drills — classification and limit forms (no computing)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions

- For each integral, decide: proper, Type 1, Type 2, or mixed (Type 1 + Type 2 together).
    

### 1) Definitions used on this page

- Define “correct limit setup” (must include direction, one-sidedness, splitting if needed).
    

### 2) Main statement

- Restate the instruction: write the limit form only, do not integrate.
    

### 3) Proof / Justification

- Why is setup-only drilling valuable (what error does it prevent later)?
    

### 4) How to use it (operational form)

- Pipeline: locate infinity or singularity → choose variable and direction → split if needed → write limit(s).
    

### 5) Failure modes / pitfalls

- Wrong approach direction ($t\to b^-$ vs $t\to b^+$).
    
- Missing split at an interior singularity.
    
- Writing one limit where two separate tails are required.
    

---