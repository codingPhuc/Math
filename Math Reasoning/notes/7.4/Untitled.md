---
title: "Stewart §7.4 — Partial Fractions (Prompt Pages)"
source: "Stewart, *Calculus: Early Transcendentals* (9e), §7.4, pp. 507–515"
tags: [math, calculus, integration, partial-fractions, stewart-7.4]
---

# Stewart §7.4 — Partial Fractions (Prompt Pages)

> [!info] How to use (no answers)
> Fill each block **from memory**. Do **not** compute unless a prompt explicitly asks.  
> Order of attack: **proper vs. improper → factor $Q$ → choose Case I–IV form → solve coefficients → integrate**.

---

## A. Proper vs. improper rational functions — make partial fractions legal

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- What is a “rational function” in this section (write the general form)?
- What domain restriction must you silently impose (when is $\\frac{P(x)}{Q(x)}$ defined)?
- What does “degree” mean and what notation does Stewart use for it?

### 1) Definitions used on this page
- Define **proper** rational function (formal degree inequality).
- Define **improper** rational function.
- After each: add one plain-English meaning sentence (“what it’s really saying”).

### 2) Main statement
- State the “preliminary step” result: after long division, what is the decomposition of $\\frac{P(x)}{Q(x)}$ into a polynomial plus a proper fraction?
- What degree condition must the remainder $R(x)$ satisfy?

### 3) Proof / Justification
- Give the justification (in words) for why long division guarantees $\\deg R < \\deg Q$.
- Explain why this matters for the next step (why partial fractions wants “proper”).

### 4) How to use it (operational form)
- In 3–6 lines: “Check degrees → divide → rewrite as $S(x)+\\frac{R(x)}{Q(x)}$ → only decompose $\\frac{R}{Q}$.”

### 5) Failure modes / pitfalls
- What goes wrong if you skip long division when $\\deg P > \\deg Q$?
- Where do people lose the $+C$ after integrating the polynomial part? (Force yourself to write it explicitly.)

---

## B. Partial fractions setup — factoring $Q(x)$ controls the form

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- What are $P,Q,R,S$ here (which ones come from long division)?
- Over what number system are you factoring (real coefficients)?
- What does “irreducible quadratic” mean in this context?

### 1) Definitions used on this page
- Define **linear factor** (Stewart’s form).
- Define **irreducible quadratic factor** and the discriminant condition Stewart states.
- After each: add one plain-English meaning sentence.

### 2) Main statement
- State the allowed “building-block” partial-fraction forms Stewart lists (include exponent placeholders).

### 3) Proof / Justification
- Explain (briefly) why each partial-fraction piece must have numerator degree **less** than denominator degree.
- What would you do otherwise?

### 4) How to use it (operational form)
- Write the 3-step pipeline Stewart uses:
  - long division (if needed)
  - factor $Q$ as far as possible
  - write $\\frac{R}{Q}$ as a sum of the correct partial-fraction forms

### 5) Failure modes / pitfalls
- Factoring mistake: not factoring “as far as possible.”
- Wrong numerator shape over a quadratic factor (e.g., constant instead of linear).
- Solving coefficients before you’ve chosen the *right* form.

---

## C. Case I — distinct linear factors (constants $A_i$ suffice)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- Write the exact hypothesis on $Q(x)$:
  - product of linear factors
  - “no repeats”
  - “no constant multiple of another”
- What does each exclusion prevent?
### 1) Definitions used on this page
- Define “distinct linear factors” in Stewart’s precise sense (include the “constant multiple” clause).
### 2) Main statement
- State Case I: existence of constants $A_1,\\dots,A_k$ such that   $$\\frac{R(x)}{Q(x)} = \\sum_{i=1}^{k} \\frac{A_i}{a_i x + b_i}.$$
### 3) Proof / Justification
- After multiplying by the LCD, what kind of object do you get (what *type* of identity)?
- What is the “license” for equating coefficients once you have a polynomial identity?

[[proof ]]
### 4) How to use it (operational form)
- Describe two tactics for finding coefficients:
  1. equate coefficients after expansion
  2. plug in convenient $x$-values (especially roots of factors after clearing denominators)
- When is tactic (2) faster, and why?
### 5) Failure modes / pitfalls
- Forgetting the LCD multiplication step (or multiplying incorrectly).
- Missing a factor in the denominator.
- Solving for constants but forgetting domain exclusions ($x\\neq$ roots of $Q$ in the original integrand).
---
## D. Case II — repeated linear factors (the “ladder of powers”)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- Suppose $Q(x)$ has $(x-1)^2$ as a factor (or generally $(ax+b)^r$).
- What does “multiplicity $r$” mean operationally?

### 1) Definitions used on this page
- Define “repeated linear factor / multiplicity $r$.”
- Meaning sentence: what repetition forces you to change in the decomposition form?

### 2) Main statement
- Using Stewart’s example pattern: if a linear factor occurs twice, what is the required shape?
- Generalize: if $(ax+b)^r$ divides $Q$, what full ladder must appear?

### 3) Proof / Justification
- Why is it *not* enough to include only $\\frac{A}{ax+b}$ when $(ax+b)^2$ divides $Q$?
- After clearing denominators, what “independence” intuition explains needing the $\\frac{1}{(ax+b)^2}$ term?

### 4) How to use it (operational form)
- After clearing denominators, which evaluations (plugging in the repeated root) kill most terms?
- How do you get the remaining constants (equate coefficients vs. derivatives / successive plugging strategy)?

### 5) Failure modes / pitfalls
- Missing one power (stopping at $\\frac{A}{ax+b}$ instead of going up to $\\frac{A_r}{(ax+b)^r}$).
- Mixing constants between different factor blocks.

---

## E. Case III — irreducible quadratic factors (numerator must be $Ax+B$)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- State the discriminant condition Stewart gives for irreducible quadratics over the reals.
- Domain restriction: when is $\frac{Ax+B}{ax^2+bx+c}$ defined?

### 1) Definitions used on this page
- Define “irreducible quadratic factor.”
- Define the allowed partial-fraction block over such a factor (shape only).

### 2) Main statement
- State the required form: for an irreducible quadratic factor,
  $$\frac{Ax+B}{(ax^2+bx+c)^j}$$
  (and specify what $j$ is in the non-repeated case).

### 3) Proof / Justification
- Core reason the numerator is linear (degree constraint relative to the quadratic denominator).
- Explain the integration “trick”:
  - split $Ax+B$ into a multiple of the derivative of the denominator plus a leftover constant
  - then complete the square

### 4) How to use it (operational form)
- Write the recipe in words:
  - complete the square
  - rewrite numerator as $k(2ax+b)+m$
  - integrate the derivative-over-denominator part as a log
  - integrate the leftover as an arctan-type form (or use the referenced formula)
- Self-check: where does $+C$ appear?

### 5) Failure modes / pitfalls
- Using $A$ instead of $Ax+B$.
- Forgetting completion of the square (can’t see the arctan structure).
- Losing constants during the “match derivative” rewrite.

---

## F. Case IV — repeated irreducible quadratics (quadratic ladder)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- Assume $(ax^2+bx+c)^r$ divides $Q(x)$ with $b^2-4ac<0$.
- What does multiplicity $r$ force you to include?

### 1) Definitions used on this page
- Define “repeated irreducible quadratic factor.”
- Meaning sentence: what must appear for each power $1,\\dots,r$?

### 2) Main statement
- State the Case IV form explicitly. If $q(x)=ax^2+bx+c$, then
  $$\\frac{A_1x+B_1}{q(x)}+\\frac{A_2x+B_2}{q(x)^2}+\\cdots+\\frac{A_rx+B_r}{q(x)^r}.$$

### 3) Proof / Justification
- Why is the numerator linear *for each power*?
- What changes in integration difficulty as the power increases (what techniques show up)?

### 4) How to use it (operational form)
- After solving coefficients: what integration moves do you anticipate (derivative-matching, substitution, recursion/known formulas)?

### 5) Failure modes / pitfalls
- Dropping one power in the ladder.
- Treating $q(x)^2$ like “just another quadratic” (it isn’t; the algebra changes).

---

## G. Decomposition-form drills (no solving) — choose the correct Case(s)

> [!note] Concept / Theory Page

### 0) Objects and standing assumptions
- For each assigned function: identify whether it is **proper** or **improper** first.

### 1) Definitions used on this page
- Define “form of the partial fraction decomposition.”
- What counts as “the form,” and what is forbidden at this stage?

### 2) Main statement
- Restate the instruction exactly: “Write out the form … Do not determine numerical values of coefficients.”

### 3) Proof / Justification
- Why is this drill valuable? (Focus your answer on classification of factor structure before algebra.)

### 4) How to use it (operational form)
- Recipe:
  - factor $Q$
  - classify each factor (distinct/repeated linear; irreducible quadratic; repeated irreducible quadratic)
  - write the corresponding sum with correct numerators

### 5) Failure modes / pitfalls
- Wrong numerator shape over quadratics.
- Missing a term for repeated factors.

---

## Bonus (cross-skill, still §7.4): When can you avoid partial fractions?

> [!tip] Self-check only
- “Is there an obvious $u$ whose derivative is (almost) present?”
- “If yes, can I finish in one log step rather than decomposing?”
- If you choose substitution: what tells you it will terminate cleanly?

---

# Works Cited
- Stewart, James. *Calculus: Early Transcendentals*. 9th ed., Cengage Learning, 2021. Section 7.4, “Integration of Rational Functions by Partial Fractions,” pp. 507–515. :contentReference[oaicite:0]{index=0}
