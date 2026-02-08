## A. exercise classification

subject + subtopic

- calculus (Spivak), chapter 12 inverse functions
    
- subtopic: one-one (injective) restrictions to intervals, using monotonicity and derivatives
    

deliverable type

- classify (not compute) all intervals $[a,b]$ on which each given function is one-one (injective)
    

difficulty (1–5)

- 3/5: conceptually simple (injective ⇐ monotone), but you must be precise about “all intervals” and about where monotonicity changes
    

exercise statement (as used below)

- “On which intervals $[a,b]$ will the following functions be one-one? (i) $f(x)=x^3-3x^2$. (ii) $f(x)=x^5+x$. (iii) $f(x)=(1+x^2)^{-1}$.”
    

## B. concept atoms

definitions / objects / notation assumed

- interval $[a,b]$, restriction of a function to a subset
    
- one-one (injective): $f(x)=f(y)\Rightarrow x=y$ (on the stated domain)
    
- increasing / decreasing (strict): $x<y\Rightarrow f(x)<f(y)$ and analog for decreasing
    
- derivative and its sign; critical points where $f'(x)=0$ or $f'$ undefined
    
- for (iii): domain is all $\mathbb R$, plus the “even function” trap ($f(x)=f(-x)$) if you don’t restrict the interval correctly
    

techniques and proof patterns likely required (high-level only)

- monotonicity criterion via derivative sign: $f'(x)>0$ on an interval $\Rightarrow$ $f$ increasing there; $f'(x)<0\Rightarrow$ decreasing
    
- “monotone $\Rightarrow$ one-one” (short direct proof from the definition)
    
- partitioning $\mathbb R$ into intervals where the derivative keeps a constant sign (monotonicity intervals)
    
- trap-handling: intervals that cross a turning point (where monotonicity switches) typically break one-one-ness for continuous differentiable functions
    

## C. prerequisite dag + minimal cut set

dag nodes (definitions/lemmas/techniques)

- N1. definition: one-one (injective) function
    
- N2. definition: increasing/decreasing (strict)
    
- N3. lemma: increasing (or decreasing) on an interval $\Rightarrow$ one-one on that interval
    
- N4. tool: mean value theorem (MVT) (the engine behind monotonicity-from-derivative in Spivak)
    
- N5. corollary (Spivak): $f'(x)>0$ on an interval $\Rightarrow$ $f$ is increasing there; $f'(x)<0\Rightarrow$ decreasing
    
- N6. technique: compute derivatives (product/chain rules; polynomial rules; reciprocal rule)
    
- N7. technique: sign analysis of $f'(x)$ (solve $f'(x)=0$, test intervals)
    
- N8. symmetry trap: even functions cannot be one-one on intervals containing both $x$ and $-x$ unless interval is one-sided (conceptual check)
    

edges (“requires”)

- N5 requires N4
    
- N3 requires N2 and N1
    
- N7 requires N6
    
- solving the exercise requires (N1, N3, N5, N6, N7) plus N8 as a correctness check for part (iii)
    

minimal cut set (smallest set that unlocks the exercise)

- {N1, N2, N3, N5, N6, N7}
    
- add N8 if you want to avoid the most common wrong answer pattern on (iii)
    

## D. learning path split

## D1. minimum-to-solve

1. lock definitions (N1, N2)
    

- you must be able to write “one-one” and “increasing” without handwaving
    

2. lock the core implication (N3)
    

- prove (once) that monotone $\Rightarrow$ one-one, from the definition
    

3. lock the derivative-to-monotone bridge (N5, backed by N4)
    

- you don’t need to re-prove MVT from scratch, but you must know the hypotheses and how Spivak uses it to get monotonicity from the sign of $f'$
    

4. lock execution skills (N6, N7)
    

- differentiate each $f$, find where $f'(x)=0$, and determine on which subintervals $f'$ keeps one sign
    

5. sanity checks (N8)
    

- especially for $f(x)=(1+x^2)^{-1}$, remember $f(x)=f(-x)$, so intervals that include symmetric points usually fail injectivity
    

## D2. mastery extensions

- strengthen to “nondecreasing/nonincreasing” vs “strictly increasing/decreasing” (Spivak later revisits this distinction)
    
- learn alternative injectivity tests: horizontal line test (graph-based), or direct algebraic injectivity proofs for special forms
    
- practice writing “all intervals $[a,b]$ such that …” as a clean classification statement (this is more logic than calculus)
    

## E. reading map (project folder only)

N1. one-one (injective) + inverse function connection

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 12 “Inverse Functions” (early part, around the definitions and first theorems; book pages 231–236 as labeled in the text)
    
- why it matters: the exercise literally asks when the function is one-one, i.e., when an inverse could exist on that interval
    
- priority: must
    

N2. increasing/decreasing definition

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 11 “Significance of the Derivative”, definition of increasing/decreasing
    
- why it matters: one-one will be proven via monotonicity, and you must use the correct strict definition
    
- priority: must
    
question :  
- I get corollary 1, but what does  function define on two or more interval mean  ?

N5 (+N4). derivative sign implies monotonicity (Spivak’s corollary, using MVT)

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 11, Corollary 3: if $f'(x)>0$ then $f$ increasing; if $f'(x)<0$ then $f$ decreasing
    
- why it matters: this is the standard bridge from calculus to injectivity on intervals
    
- priority: must
    

N6. derivative computation rules

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 11 (rules used throughout the chapter examples), plus wherever your copy states product/chain rules (earlier derivative chapters)
    
- why it matters: you cannot classify monotonicity intervals without correct $f'(x)$
    
- priority: must
    

N7. sign analysis of derivatives (critical points → test intervals)

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 11 discussion around using $f'$ to study increasing/decreasing (same neighborhood as Corollary 3)
    
- why it matters: the deliverable is “all intervals,” which comes from partitioning by where $f'$ changes sign
    
- priority: must
    

N8. symmetry/even-function trap (conceptual)

- resource pointer: MATH-CALC-SPIVAK-4E.pdf, chapter 11 short discussion of even/odd graph symmetry (even: reflect in the $y$-axis; odd: rotate about origin)
    
- why it matters: part (iii) is even; injectivity fails on many intervals unless you restrict correctly
    
- priority: should
    

(optional backup if Spivak feels too terse)

- MATH-CALC-STEWART.pdf: sections on increasing/decreasing tests via derivatives (supporting intuition)
    
- MATH-CAL-APOSTOL.pdf: more formal function/injectivity language (if you want extra rigor)
    

## F. theorem/lemma toolkit (typical solutions) + hypotheses checklists

T1. definition (one-one)

- statement: $f$ is one-one on $D$ iff for all $x,y\in D$, $f(x)=f(y)\Rightarrow x=y$.
    
- checklist: domain $D$ must be explicit (here $D=[a,b]$).
    

T2. lemma (monotone implies one-one)

- statement: if $f$ is increasing on an interval $I$, then $f$ is one-one on $I$. Same for decreasing.
    
- checklist: you must be using strict monotonicity (not merely nondecreasing).
    

T3. mean value theorem (MVT)

- statement: if $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then there exists $c\in(a,b)$ with $f'(c)=\dfrac{f(b)-f(a)}{b-a}$.
    
- checklist: continuity on closed interval, differentiability on open interval.
    

T4. corollary (Spivak): sign of derivative gives monotonicity

- statement: if $f'(x)>0$ for all $x$ in an interval, then $f$ is increasing there; if $f'(x)<0$, then decreasing
    
- checklist: differentiable on the interval; strict inequality holds throughout (or you handle endpoints carefully).
    

T5. symmetry observation (trap-preventer)

- statement: if $f$ is even, $f(x)=f(-x)$. Therefore any domain containing both $x$ and $-x$ (with $x\neq 0$) cannot make $f$ one-one.
    
- checklist: confirm evenness and that the interval actually contains a nonzero symmetric pair.
    

## G. readiness checks + short answer key

micro-questions (write 1–3 lines each; no full solutions)

1. write the definition of “one-one on $[a,b]$” using quantifiers.
    
2. write the definition of “increasing on $[a,b]$” using quantifiers.
    
3. prove in 3–5 lines: increasing on an interval $\Rightarrow$ one-one on that interval.
    
4. state MVT and list its hypotheses (no proof).
    
5. explain in one sentence why Corollary 3 (derivative sign $\Rightarrow$ monotonicity) depends on MVT.
    
6. compute $f'(x)$ for $f(x)=x^3-3x^2$ (just the derivative).
    
7. compute $f'(x)$ for $f(x)=x^5+x$ (just the derivative).
    
8. compute $f'(x)$ for $f(x)=(1+x^2)^{-1}$ (just the derivative).
    
9. given a factored derivative like $f'(x)=k\cdot x(x-2)$, what are the only points where the sign can change?
    
10. explain what you do after finding the critical points: how do you decide the sign of $f'$ on each subinterval?
    
11. trap: if $f'(x)=0$ at one point in $(a,b)$, does that automatically mean $f$ is not one-one on $[a,b]$? say yes/no and give a one-sentence justification.
    
12. trap: if $f$ is even, can it ever be one-one on an interval containing $0$? answer depends; state the condition on the interval.
    

short answer key (definitions/checks only)

1. one-one: $f(x)=f(y)\Rightarrow x=y$ for all $x,y\in[a,b]$.
    
2. increasing: if $x<y$ then $f(x)<f(y)$ for all $x,y\in[a,b]$.
    
3. use contradiction: if $x<y$ but $f(x)=f(y)$, violates strict inequality.
    
4. MVT: hypotheses = continuous on $[a,b]$, differentiable on $(a,b)$.
    
5. Corollary 3 is an application of MVT to $a<b$ to force $f(b)-f(a)$ to have the sign of $f'$ somewhere, ruling out “wrong order.”  
    6–8) answer should be a correct derivative expression (no sign conclusion needed).
    
6. zeros/undefined points of $f'$.
    
7. pick a test point in each interval or reason by factor signs.
    
8. no; a single critical point can occur in a function that is still one-one (you need monotonicity failure, not merely $f'(c)=0$).
    
9. yes, but only if the interval does not contain both $x$ and $-x$ for any $x\neq 0$ (one-sided intervals).
    

if you want, paste your current attempt on exercise 7 (even a messy one), and I’ll point to exactly which node in the dag you’re missing and which 2–3 pages to reread first.