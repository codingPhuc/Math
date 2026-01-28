
According to a document from **2021** (the Stewart Calculus text in your vault), **Chapter 11** is explicitly titled **“Sequences, Series, and Power Series”** and is organized into **§11.1–§11.11**.  
Assumption (so the mapping is precise): by “section 11 of Stewart calculus,” you mean **Stewart, Chapter 11** in **MATH-CALC-STEWART.pdf** (the one whose ToC lists §11.1 at p.724).

---

# A) Concept spine for Sequences, Series, and Power Series (Stewart Ch. 11)

## 1) Prerequisites map (with citations)

**P0. Sigma notation fluency** (turn “$\sum$” into a concrete sum; recognize index shifts).

- Stewart points you to **Appendix E (Sigma Notation)**.
    

**P1. Limits + continuity mindset** (because sequences are limits of functions on $\mathbb{N}$, and series are limits of partial sums).

- Stewart frames early chapters as building “limits and derivatives,” “differentiation rules,” and “applications of differentiation.”
    

**P2. Improper integrals** (needed for the Integral Test and remainder estimates).

- Stewart explicitly has **§7.8 Improper Integrals** and then later **§11.3 The Integral Test and Estimates of Sums**.
    

**P3. Differentiation/integration rules + higher derivatives** (Taylor polynomials/series, term-by-term manipulations).

- Chapter 11 culminates in **§11.10 Taylor and Maclaurin Series** and **§11.11 Applications of Taylor Polynomials**.
    

## 2) Core definitions + notation (with citations)

**Sequences.** A (real) sequence is a function on the natural numbers; standard notation is ${a_n}_{n=1}^\infty$ or ${a_n}$.

**Bounded/monotone sequences.**

- Bounded above/below; increasing/decreasing; monotone means increasing or decreasing.
    

**Series and partial sums.** Given $\sum_{n=1}^\infty a_n$, define partial sums $s_n=\sum_{i=1}^n a_i$; the series **converges** iff $\lim_{n\to\infty}s_n$ exists (and equals the series “sum”).

**Geometric series.** $\sum_{n=0}^\infty ar^n$ converges for $|r|<1$ with sum $\frac{a}{1-r}$; diverges for $|r|\ge 1$.

**Alternating series; absolute vs conditional convergence.**

- $\sum (-1)^{n-1}b_n$ alternating form; Alternating Series Test criteria appear in §11.5.
    
- Absolute convergence: $\sum |a_n|$ converges; conditional: $\sum a_n$ converges but $\sum |a_n|$ diverges.
    

**Ratio test.** Theorem statement with $L=\lim |a_{n+1}/a_n|$; convergence for $L<1$, divergence for $L>1$, inconclusive at $L=1$.

**Power series.** A power series centered at $a$ is $\sum_{n=0}^\infty c_n(x-a)^n$; §11.8 develops convergence behavior (interval/radius ideas).

**Taylor polynomials and remainder (Taylor’s Theorem).** $P_n(x)=\sum_{k=0}^n\frac{f^{(k)}(a)}{k!}(x-a)^k$ and $R_n(x)=\frac{f^{(n+1)}(c)}{(n+1)!}(x-a)^{n+1}$.

## 3) Core results + what each buys you (with citations)

**R1. Monotone Sequence Theorem** → a convergence machine when you can show monotone + bounded (common in recursively defined sequences).

**R2. “Series = limit of partial sums”** → turns every convergence question into a limit question about $s_n$.

**R3. Geometric series** → the single most reused template for turning algebra into a sum, and for building power series by manipulation.

**R4. Integral Test + remainder estimates** → lets you (i) decide convergence for “function-like” terms $a_n=f(n)$, and (ii) bound the tail error $R_n$.

**R5. Alternating Series Test + alternating remainder bound** → fast convergence checks and built-in error control for alternating sums.

**R6. Ratio/Root tests** → best tools for factorials, exponentials, and powers; also the standard route to radius of convergence for power series.

**R7. Term-by-term differentiation/integration of power series** → converts known series into new ones (e.g., build $\ln(1+x)$ from geometric).

**R8. Taylor/Maclaurin series + Taylor’s Inequality** → approximation with certified error bounds; basis of “series methods.”

## 4) Canonical problem types

1. **Compute $\lim a_n$** (explicit formula; squeeze; compare to integral; monotone/bounded).
    
2. **Decide convergence/divergence of $\sum a_n$** (pick the right test; justify).
    
3. **Estimate sums / error** using Integral Test remainder or Alternating remainder.
    
4. **Find interval/radius of convergence** for power series; endpoints separately. (Power series section + ratio/root test.)
    
5. **Represent functions as power series** via algebra + term-by-term operations.
    
6. **Taylor polynomial approximations + bounds** (Taylor’s Theorem / Taylor’s Inequality).
    

---

# B) Action plan by subtopic (ordered by dependency)

Below, each subtopic’s “Learn” targets include (i) Stewart Chapter 11 page anchors from the ToC, and (ii) your course vault’s **Lecture Video** and **HW problem** mappings when available.

---

## Subtopic 1 — §11.1 Sequences

### 1) Learn (targets + 5–12 key extract items)

**Primary reading (Stewart):** §11.1 starts at **p.724**.  
**Course video (vault):** “11.1 sequences and series” is listed in your lecture-video sheet.

**Key extract items (pull these into your notes, verbatim-level precise):**

1. Sequence as a **function** with domain $\mathbb{N}$; notation ${a_n}$.
    
2. Definitions: bounded above/below; increasing/decreasing; monotone.
    
3. Monotone Sequence Theorem (statement).
    
4. Typical proof skeleton used there (bounded → limit exists).
    
5. “Limit of a sequence” as the organizing goal of §11.1 (what you compute/justify).
    
6. Exercise families: monotonicity/boundedness checks are explicitly grouped late in the section exercises.
    

### 2) Mastery targets (3–8 “I can…”)

- I can translate between **formula**, **graph**, and **verbal behavior** of ${a_n}$ (increasing? bounded?).
    
- I can prove convergence by **monotone + bounded** and clearly state which bound and which monotonicity I used.
    
- I can compute limits of standard explicit sequences and recognize when monotone/bounded is the intended method (especially recurrences).
    
- I can classify a given sequence as bounded/unbounded and increasing/decreasing from definitions.
    

### 3) Self-test (closed notes)

**Recall quiz (5–10 prompts):**

1. State “bounded above” and “increasing” precisely.
    
2. What does “monotone” mean?
    
3. State the Monotone Sequence Theorem. What hypotheses must be checked?
    
4. If a sequence is bounded but not monotone, does the theorem apply? Why not?
    
5. What is the conceptual difference between proving “converges” vs computing the limit?
    

**Practice (from your PDFs; grouped + what each trains):**  
Your course HW sheet assigns specific §11.1 exercises: **1, 2, 7, 8, 18, 22, 24, 36, 42, 46, 49, 53, 61, 65, 67, 71, 72, 83, 84, 89, 90, 93, 94, 101, 102, 103, 105.**

- **Easy (mechanics: compute/recognize):** 1, 2, 7, 8, 18, 22, 24.
    
- **Medium (structure: justify monotone/bounded; less routine limits):** 36, 42, 46, 49, 53, 61, 65, 67, 71, 72.
    
- **Hard (full convergence arguments; monotone/bounded and/or recurrence behavior):** 83, 84, 89, 90, 93, 94, 101–105.  
    (These align with the section’s explicit late-exercise clusters on monotonicity/boundedness and recursively defined sequences.)
    

### 4) Error-correction loop

- **Threshold:** if you score **<80%** on a 10-problem mix (easy/medium/hard), remediate.
    
- **Remediation (exact):**
    
    1. Re-read §11.1 focusing only on definitions + Monotone Sequence Theorem statement.
        
    2. Rewrite from memory: the definitions + theorem, then check against text.
        
    3. Micro-drill: redo 3 “medium” problems and 2 “hard” problems you missed, writing the monotone/bounded checks as labeled bullets.
        

---

## Subtopic 2 — §11.2 Series

### 1) Learn (targets + 5–12 key extract items)

**Primary reading:** §11.2 starts at **p.738**.  
**Course video:** “11.2 sequences and series” appears in your lecture-video list.

**Key extract items:**

1. Definition of **partial sums** $s_n$ and convergence of $\sum a_n$ via $\lim s_n$.
    
2. Geometric series test + closed-form sum $\frac{a}{1-r}$.
    
3. “Telescoping” as a partial-sum simplification pattern (in §11.2’s problem ecology).
    
4. The meaning of “diverges” here: partial sums fail to approach a finite limit.
    

### 2) Mastery targets

- I can rewrite a series problem as a **partial-sum limit** problem and decide convergence from $s_n$.
    
- I can instantly recognize geometric form (or reduce to it) and apply the correct case $|r|<1$ vs $|r|\ge 1$.
    
- I can compute sums of telescoping series by writing $s_n$ explicitly and simplifying.
    
- I can explain why “value of the series” is not “sum of infinitely many numbers,” but $\lim s_n$.
    

### 3) Self-test (closed notes)

**Recall quiz:**

1. Define $s_n$ for $\sum_{n=1}^\infty a_n$.
    
2. What does it mean for the series to converge?
    
3. State the geometric series sum and convergence condition.
    
4. Why can two different-looking expressions define the same series (index shifts)?
    

**Practice (your HW mapping):** §11.2 exercises assigned: **1, 2, 3, 5, 6, 8, 11, 13, 14, 15, 18, 19, 23, 24, 29, 30, 35, 39, 41, 42, 47, 48, 49, 50, 53, 55, 56, 63, 64, 69, 70, 71, 72, 73.**

- **Easy:** 1–6, 8, 11, 13–15 (build $s_n$, basic convergence, geometric recognition).
    
- **Medium:** 18–24, 29–30, 35, 39, 41–42 (telescoping and more algebraic manipulation).
    
- **Hard:** 47–50, 53, 55–56, 63–64, 69–73 (multi-step identification; trickier partial sums).
    

### 4) Error-correction loop

- **Threshold:** <80% correct on a 12-problem set (4/4/4 by difficulty).
    
- **Remediation:** reread the partial-sum definition and geometric-series theorem; rewrite them from memory; redo 2 missed easy + 2 missed medium + 1 missed hard, each time explicitly writing $s_n$ first.
    

---

## Subtopic 3 — §11.3 The Integral Test and Estimates of Sums

### 1) Learn

**Primary reading:** §11.3 starts at **p.747**.  
**Course video:** “11.3 Integral test” appears in your lecture-video list.

**Key extract items:**

1. Integral Test hypotheses: $f$ continuous, positive, decreasing; $a_n=f(n)$.
    
2. Integral Test conclusion: $\sum a_n$ converges iff $\int_1^\infty f(x),dx$ converges.
    
3. Remainder estimate inequalities bounding $R_n=\sum_{i=n+1}^\infty a_i$ by integrals.
    
4. Dependency link: you must know improper integrals (§7.8).
    

### 2) Mastery targets

- I can verify Integral Test hypotheses (especially “decreasing”) without handwaving.
    
- I can convert a series into an improper integral decision problem (and back).
    
- I can bound a tail error $R_n$ to guarantee a decimal accuracy target.
    

### 3) Self-test

**Recall quiz:**

1. State the Integral Test (all hypotheses).
    
2. What is $R_n$ and what do the inequalities say?
    
3. Why does “decreasing” matter (geometric picture: rectangles vs area)?
    

**Practice (your HW mapping):** §11.3 assigned: **4, 6, 7, 11, 14, 15, 16, 17, 20, 21, 22, 25, 30, 31, 32, 34, 37, 38, 39, 40.**

- **Easy:** 4, 6, 7, 11, 14–17 (apply test cleanly).
    
- **Medium:** 20–22, 25, 30–32 (more involved integrals / hypothesis checking).
    
- **Hard:** 34, 37–40 (remainder estimates / accuracy demands).
    

### 4) Error-correction loop

- **Threshold:** if you cannot correctly (i) verify hypotheses and (ii) set up $\int_1^\infty f$ in **3 consecutive problems**, remediate.
    
- **Remediation:** reread the theorem statement + remainder bounds; rewrite the hypotheses list as a checklist; redo 2 missed “hard” problems slowly, explicitly writing the inequality chain for $R_n$.
    

---

## Subtopic 4 — §11.4 The Comparison Tests

### 1) Learn

**Primary reading:** §11.4 starts at **p.759** and explicitly includes **Direct Comparison Test** and **Limit Comparison Test** subheads in the ToC.  
**Course video:** “11.4 Comparison tests” is listed in your lecture-video sheet.

**Key extract items:**

1. The decision logic: compare to a known convergent/divergent benchmark (usually $p$-series or geometric).
    
2. Distinguish “$\le$ comparison” (direct) vs “limit of ratio” comparison (limit comparison).
    
3. Practice taxonomy in the section: large blocks of “determine whether converges/diverges” problems.
    

### 2) Mastery targets

- I can choose an intelligent comparison target (geometric vs $p$-series) and justify why it is comparable.
    
- I can execute a limit comparison cleanly (no algebra drift).
    
- I can explain why comparison tests are _not_ about computing sums—only convergence.
    

### 3) Self-test

**Recall quiz:**

1. When does direct comparison fail to be convenient even if true?
    
2. What does the limit comparison ratio need to approach (qualitatively) to be useful?
    
3. Name two benchmark series you always keep ready.
    

**Practice (your HW mapping):** §11.4 assigned: **3, 5, 6, 10, 12, 13, 14, 18, 19, 20, 21, 22, 23, 25, 27, 28, 32, 33, 34, 35, 36, 37, 38, 39, 40, 41, 42, 43, 44.**

- **Easy:** 3, 5, 6, 10, 12–14 (basic comparisons).
    
- **Medium:** 18–23, 25, 27–28, 32–36 (more choice/justification).
    
- **Hard:** 37–44 (subtle comparisons; higher algebra load).
    

(Also, Stewart’s own exercise block indicates many “determine convergence/divergence” items, useful for timed drills.)

### 4) Error-correction loop

- **Threshold:** if you pick the wrong benchmark series in **≥2 of 6** medium problems, remediate.
    
- **Remediation:** re-read the test statements (focus: what inequality/limit you need); then do a “benchmark-only” drill: for each missed problem, write _two_ plausible benchmarks, then pick one and justify comparability in one sentence.
    

---

## Subtopic 5 — §11.5 Alternating Series and Absolute Convergence

### 1) Learn

**Primary reading:** §11.5 starts at **p.768**.  
**Course video:** “11.5 Alternating series” appears in your lecture list.

**Key extract items:**

1. Alternating Series Test hypotheses (decreasing $b_n$ and $b_n\to 0$) and conclusion.
    
2. Alternating remainder estimate: $|R_n|\le b_{n+1}$.
    
3. Definitions: absolute vs conditional convergence.
    

### 2) Mastery targets

- I can apply AST and _prove_ (check) “decreasing” correctly (often via derivative test).
    
- I can compute/guarantee decimal accuracy using $|R_n|\le b_{n+1}$.
    
- I can decide absolute vs conditional by testing $\sum |a_n|$ appropriately.
    

### 3) Self-test

**Recall quiz:**

1. State AST precisely.
    
2. What’s the remainder bound and how do you use it for “within $10^{-k}$”?
    
3. Define absolute convergence.
    

**Practice (your HW mapping):** §11.5 assigned: **1, 3, 4, 5, 6, 8, 12, 13, 14, 16, 18, 20, 22, 23, 24, 26, 27, 28, 30, 31, 32, 33.**

- **Easy:** 1, 3–6, 8 (basic AST checks).
    
- **Medium:** 12–16, 18, 20, 22–24 (mix with absolute/conditional decisions).
    
- **Hard:** 26–33 (error bounds + combined-test judgment calls).
    

### 4) Error-correction loop

- **Threshold:** if you miss **any** remainder-estimate problem, remediate immediately (those are “free points” when structured).
    
- **Remediation:** rewrite the inequality $|R_n|\le b_{n+1}$ from memory and do 3 quick “choose $n$ for accuracy” drills using your missed items.
    

---

## Subtopic 6 — §11.6 The Ratio and Root Tests

### 1) Learn

**Primary reading:** §11.6 starts at **p.775**.  
**Course video:** “11.6 Ratio test” appears in your lecture-video list.

**Key extract items:**

1. Ratio Test theorem statement (the $L<1$, $L>1$, $L=1$ trichotomy).
    
2. Why it works: comparison to a geometric series (the proof uses that structure).
    
3. Problem ecology: factorials/exponentials/powers (choose ratio/root when those show up). (Section placement + standard usage.)
    

### 2) Mastery targets

- I can compute $L=\lim |a_{n+1}/a_n|$ efficiently and correctly simplify.
    
- I can recognize when Ratio Test will be inconclusive (often “$L=1$”) and pivot fast.
    
- I can connect ratio outcomes to interval of convergence later in §11.8.
    

### 3) Self-test

**Recall quiz:**

1. State the Ratio Test precisely.
    
2. Why does $L<1$ imply convergence? What benchmark series is hiding?
    
3. Give a “red flag” form where ratio test is usually the best first move.
    

**Practice (your HW mapping):** §11.6 assigned: **1, 2, 3, 4, 5, 7, 9, 10, 12, 13, 14, 15, 16, 17, 21, 22, 23, 24, 25, 26, 27, 28.**

- **Easy:** 1–5, 7 (straight ratio computations).
    
- **Medium:** 9–17 (more algebra / absolute values / parameters).
    
- **Hard:** 21–28 (pivoting after inconclusive behavior; trickier forms).
    

### 4) Error-correction loop

- **Threshold:** if simplification errors occur in **≥2** problems, remediate (ratio test is algebra-sensitive).
    
- **Remediation:** redo 5 medium problems _only writing simplification steps_; check against final form before taking the limit; then redo 2 hard problems with a “plan sentence” first (“ratio test because factorial/exponential present”).
    

---



## B) Action plan by subtopic (ordered by dependency) — continued

### Subtopic 7 — Power series: radius + interval of convergence (Stewart §11.8)

**1) Learn (exact PDF targets + key extract items)**

- **Text:** _MATH-CALC-STEWART.pdf_, §11.8 **“Power Series”** (begins around p. 781 in this PDF’s ToC).
    
- **Lecture:** _MATH-185-LECTURE-VIDEOS.pdf_ (the list includes an **11.8** lecture).
    
- **Homework assignments:** _MATH-185-HW-PROBLEMS.pdf_ §11.8 problems **1–25** (assigned).
    

**Key extract items (pull these into your notes verbatim-ish, with your own examples):**

1. Definition of a **power series** centered at (a): (\sum_{n=0}^\infty c_n (x-a)^n).
    
2. What it means to “**converge for a given (x)**” (turns into an ordinary numeric series).
    
3. Definition of **radius of convergence** (R) and **interval of convergence** ((a-R,a+R)) plus endpoint testing. (Stewart explicitly emphasizes interval + radius here.)
    
4. The standard workflow: **Ratio Test / Root Test** to get a strict inequality (|x-a|<R), then **separate endpoint tests** (x=a\pm R).
    
5. The three “degenerate” cases: (R=0) (only converges at (x=a)), (R=\infty) (converges for all (x)), and finite positive (R).
    
6. How algebraic manipulations affect (R) (mostly: they don’t, unless you change the series).
    

**2) Mastery targets (“I can…”)**

- I can compute (R) for a power series via Ratio/Root Test and state the **candidate interval** ((a-R,a+R)).
    
- I can **test endpoints correctly** and state the final **interval of convergence** with bracket/parenthesis accuracy.
    
- I can recognize when Ratio Test is “inconclusive” at endpoints and switch to a different test.
    
- I can sanity-check results (e.g., if coefficients look factorial, expect large (R); if (n!) in numerator, expect small (R), etc.).
    

**3) Self-test (closed notes)**  
**Recall quiz (answer from memory):**

1. Define radius of convergence and interval of convergence.
    
2. Why do we _always_ test endpoints separately?
    
3. Give one example each of (R=0), (R=\infty), and finite (R).
    
4. If Ratio Test gives (|x-a|<3), what are the only remaining tasks?
    
5. What does it mean for a power series to be centered at (a)?
    

**Practice (from your PDFs; grouped by training purpose)**

- **Routine radius/interval workflow:** §11.8 assigned **1–25**; do them in 3 passes:
    
    - Pass 1 (warm-up): first ~1/3 of the set (focus: getting (R)).
        
    - Pass 2 (core): middle ~1/3 (focus: endpoint test correctness).
        
    - Pass 3 (hard): last ~1/3 (focus: messy algebra + choosing the right endpoint test).
        

**4) Error-correction loop**

- **Threshold:** if you score **<80% correct** on a 10-problem slice, remediate immediately.
    
- **Remediation protocol (exact):**
    
    1. Re-read Stewart §11.8 only until the definition + workflow is clear (stop early; do not reread the whole section).
        
    2. Rewrite from memory a 6-line “algorithm card”: _test → inequality → endpoints → final interval_.
        
    3. Micro-drill **5 endpoint-only problems**: take any 5 problems you already solved and redo _only the endpoint step_ (no Ratio/Root Test).
        

---

### Subtopic 8 — Power series as function machines (Stewart §11.7 + §11.9)

This is the hinge skill: turning known series into new ones by legal operations.

**1) Learn (exact PDF targets + key extract items)**

- **Text:**
    
    - _MATH-CALC-STEWART.pdf_ §11.7 **“Power Series”** (term-by-term differentiation/integration rules).
        
    - _MATH-CALC-STEWART.pdf_ §11.9 **“Representations of Functions as Power Series”** (use geometric series + manipulations to represent functions).
        
- **Lecture:** there is an **11.9** lecture listed in _MATH-185-LECTURE-VIDEOS.pdf_.
    
- **Homework assignments:**
    
    - §11.7 problems **1–20** (assigned).
        
    - §11.9 problems **1–29** (assigned).
        

**Key extract items**

1. The “power series behave like polynomials” rules _within the interval of convergence_:  
    [  
    \sum a_n x^n \Rightarrow \frac{d}{dx}\sum a_n x^n=\sum n a_n x^{n-1},\quad \int\sum a_n x^n dx=\sum \frac{a_n}{n+1}x^{n+1}  
    ]  
    Stewart states these term-by-term rules explicitly for power series.
    
2. **Geometric series** as the generator: start from (\frac{1}{1-x}=\sum_{n=0}^\infty x^n) (and shifted/scaled variants), then substitute and integrate/differentiate.
    
3. How to track the **new interval of convergence** after substitution (the inequality transforms; endpoints still need checking).
    
4. Pattern recognition: rational functions (\to) geometric; logs/arctan (\to) integrate geometric variants; many others (\to) algebra + these moves.
    

**2) Mastery targets (“I can…”)**

- I can turn (\frac{1}{1-u(x)}) into (\sum (u(x))^n) and state the resulting convergence condition (|u(x)|<1).
    
- I can differentiate/integrate a known power series and correctly update indices and constants.
    
- I can produce a power series for a function and state the interval of convergence _correctly_, not “by vibes.”
    
- I can choose the shortest route: substitute first vs integrate first vs differentiate first.
    

**3) Self-test (closed notes)**  
**Recall quiz**

1. State Stewart’s term-by-term differentiation/integration rules for power series.
    
2. Why is the interval of convergence important when you manipulate a series?
    
3. If (f(x)=\sum c_n (x-a)^n), what is (f'(x)) as a series?
    
4. Starting from (\frac{1}{1-x}=\sum x^n), what is a clean way to get a series for (\ln(1-x))? (Just name the move, don’t compute.)
    
5. What must you always do after you transform the convergence condition? (Endpoints.)
    

**Practice (from your PDFs)**

- **Skill: term-by-term mechanics** → §11.7 assigned **1–20**.
    
- **Skill: build function series from geometric** → §11.9 assigned **1–29**.
    
- Suggested grouping:
    
    - Easy: problems that are “direct geometric substitution.”
        
    - Medium: problems requiring 1 integration/differentiation step.
        
    - Hard: problems requiring 2+ steps _and_ careful interval tracking.
        

**4) Error-correction loop**

- **Threshold:** <80% on a set of 10 (or “I keep blowing the interval”).
    
- **Remediation:**
    
    1. Re-copy the two term-by-term rules and annotate _when they’re legal_ (inside the convergence interval).
        
    2. Do **5 “interval-only” drills**: for 5 problems, ignore series algebra and compute only the correct interval after substitution.
        
    3. Redo 3 missed problems with a forced checklist: “base series → transform → inequality → endpoints.”
        

---

### Subtopic 9 — Taylor polynomials + Taylor/Maclaurin series (Stewart §11.10)

**1) Learn (exact PDF targets + key extract items)**

- **Text:** _MATH-CALC-STEWART.pdf_ §11.10 **“Taylor and Maclaurin Series”** (begins around p. 795 in this PDF’s ToC).
    
- **Lecture:** _MATH-185-LECTURE-VIDEOS.pdf_ includes **11.10**.
    
- **Homework assignments:** §11.10 problems **3–39** (assigned).
    

**Key extract items**

1. Definition of the **(n)-th Taylor polynomial** at (a):  
    [  
    T_n(x)=\sum_{k=0}^n \frac{f^{(k)}(a)}{k!}(x-a)^k  
    ]
    
2. Definition of the **Taylor series** (\sum_{k=0}^\infty \frac{f^{(k)}(a)}{k!}(x-a)^k) and the “center” (a). Stewart states this directly.
    
3. **Maclaurin series** is the special case (a=0).
    
4. Workflow: (i) compute derivatives pattern, (ii) evaluate at (a), (iii) write series, (iv) recognize known expansions to avoid repeated differentiation.
    
5. Interpretation: Taylor polynomials as local approximations (ties to linearization, but higher order). (Stewart uses this approximation framing leading into remainder/error.)
    

**2) Mastery targets (“I can…”)**

- I can compute (T_n(x)) at a given center (a) and write the Taylor series template without mistakes.
    
- I can recognize when it’s smarter to use a known base expansion + Subtopic 8 operations instead of brute-force derivatives.
    
- I can distinguish: “Taylor series exists” vs “Taylor series equals the function” (convergence-to-(f) is extra).
    
- I can produce Maclaurin expansions for standard functions and shift centers as needed.
    

**3) Self-test (closed notes)**  
**Recall quiz**

1. State the formulas for (T_n(x)) and the Taylor series at center (a).
    
2. What is the Maclaurin series?
    
3. What information do you need to build (T_n)?
    
4. What’s the difference between (T_n) and the Taylor series?
    
5. Name two ways to get a Taylor series: (A) derivatives definition, (B) power-series algebra from known series.
    

**Practice (from your PDFs)**

- §11.10 assigned **3–39** (do in three clusters):
    
    - Cluster 1: pure computation of (T_n).
        
    - Cluster 2: recognize/derive standard series (sin, cos, (e^x), (\ln(1+x)), (\arctan x), etc.).
        
    - Cluster 3: “use a series to approximate a value.”
        

**4) Error-correction loop**

- **Threshold:** <80% or recurring derivative/index mistakes.
    
- **Remediation:**
    
    1. Rewrite (T_n) formula from memory twice, then check against Stewart.
        
    2. Do a 10-minute “index hygiene” drill: rewrite (\sum_{k=0}^n) with (k\to k+1), re-express from (k=1), etc.
        
    3. Redo 3 missed problems with a forced structure: “derivatives table → values at (a) → polynomial.”
        

---

### Subtopic 10 — Error bounds + Applications of Taylor polynomials (Stewart §11.11)

**1) Learn (exact PDF targets + key extract items)**

- **Text:** _MATH-CALC-STEWART.pdf_ §11.11 **“Applications of Taylor Polynomials”** (begins around p. 811 in this PDF’s ToC).
    
- **Lecture:** _MATH-185-LECTURE-VIDEOS.pdf_ lists **11.6 + 11.7 combined** and separate 11.8–11.10; if there is no 11.11 lecture in your list, you’ll lean harder on the text here.
    
- **Homework assignments:** §11.11 problems **1–36** (assigned).
    

**Key extract items**

1. Definition of the **remainder** (R_n(x)=f(x)-T_n(x)) and why we care (accuracy).
    
2. Stewart’s “three methods” to estimate error: graphing/computation; Alternating Series Estimation Theorem when applicable; and **Taylor’s Inequality** in general.
    
3. **Taylor’s Inequality (Theorem 11.10.9)**: if (|f^{(n+1)}(x)|\le M), then  
    [  
    |R_n(x)| \le \frac{M}{(n+1)!}|x-a|^{n+1}.  
    ]  
    (Stewart states this explicitly.)
    
4. How to _choose (M)_ (bound the ((n+1))-st derivative on an interval).
    
5. Using error bounds to pick (n) for a target tolerance.
    

**2) Mastery targets (“I can…”)**

- I can bound (|R_n(x)|) using Taylor’s Inequality by selecting a valid (M) and plugging into the formula.
    
- I can decide whether Alternating Series Estimation applies and prefer it when it’s tighter/easier.
    
- I can translate “approximate to within (10^{-k})” into a concrete inequality that solves for (n).
    
- I can justify approximation intervals (e.g., “for (x) in ([a-h,a+h]), the error is < …”).
    

**3) Self-test (closed notes)**  
**Recall quiz**

1. Define (R_n(x)).
    
2. State Taylor’s Inequality and what (M) means.
    
3. List Stewart’s three error-estimation methods.
    
4. When does Alternating Series Estimation apply?
    
5. What’s the main “hard step” in Taylor’s Inequality in practice? (Choosing (M).)
    

**Practice (from your PDFs)**

- §11.11 assigned **1–36** (do as):
    
    - Easy: compute (T_n) and write (R_n) setup.
        
    - Medium: choose (M) correctly on an interval.
        
    - Hard: solve for minimal (n) meeting an accuracy requirement.
        

**4) Error-correction loop**

- **Threshold:** if your chosen (M) is wrong twice in a row, stop and remediate (this error snowballs).
    
- **Remediation:**
    
    1. Re-read only the paragraph where Stewart introduces Taylor’s Inequality and the role of bounding (|f^{(n+1)}|).
        
    2. Do 3 micro-drills: given an interval and a derivative formula, produce a correct (M) (no Taylor polynomial work).
        
    3. Redo the last missed problem with a written “(M)-justification” line before any computation.
        

---

## C) Supplemental resources NOT in my PDFs

### 1) Rigorous textbook (for clean theory + proofs)

**Apostol, Tom M. _Calculus, Volume 1._** (widely used for a more proof-aware treatment of sequences/series; good when you want the logic behind convergence tests and power series machinery).  
**How to use for _this_ topic:** read the sequence/series chapters _only_ to strengthen: (i) what convergence means, (ii) why tests work, (iii) uniform convergence intuition around power series (optional).

### 2) Intuition/visual resource (to make Taylor/power series feel inevitable)

**3Blue1Brown — “Taylor series”** (excellent geometric/intuition framing for what Taylor polynomials are doing). ([3Blue1Brown](https://www.3blue1brown.com/lessons/taylor-series?utm_source=chatgpt.com "Taylor series - 3Blue1Brown"))  
**How to use:** watch/read once before §11.10–§11.11; then rewatch after you can compute series, to lock in “approximation” meaning.

### 3) Problem source with solutions/hints (extra reps beyond assigned work)

**Paul’s Online Math Notes — Calculus II Power Series practice problems (with worked solutions).** ([Paul's Online Math Notes](https://tutorial.math.lamar.edu/problems/calcii/powerseries.aspx?utm_source=chatgpt.com "Calculus II - Power Series (Practice Problems)"))  
**How to use:** after each Stewart homework block, do 5–10 Paul’s problems targeting your weakness (interval endpoints, function-to-series transformations, etc.).

### Optional: strong lecture notes + solved exercises (very aligned to your Stewart Chapter 11)

**MIT OpenCourseWare 18.01 — Taylor’s Series lecture + notes** (Jerison). ([MIT OpenCourseWare](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/resources/lecture-38-taylors-series/?utm_source=chatgpt.com "Lecture 38: Taylor's Series | Single Variable Calculus"))  
And OCW solved material on operations on power/Taylor series. ([MIT OpenCourseWare](https://ocw.mit.edu/courses/18-01sc-single-variable-calculus-fall-2010/e5f4299378ee87484d49640281ca1828_MIT18_01SCF10_ex100sol.pdf?utm_source=chatgpt.com "Operations on Power Series Related to Taylor Series"))  
**How to use:** if Stewart’s exposition feels procedural, use MIT’s notes to rebuild the conceptual story, then return to Stewart problems.

### Optional proof/rigor reference (only if you want real-analysis-level foundations)

**Rudin, Walter. _Principles of Mathematical Analysis._** (for sequences/series rigor; overkill for Calc II grades, but unbeatable if you want the bedrock).

---

## Works Cited

- Apostol, Tom M. _Calculus, Volume 1_. Wiley.
    
- Dawkins, Paul. _Paul’s Online Math Notes: Calculus II — Power Series (Notes/Practice Problems/Solutions)._ ([Paul's Online Math Notes](https://tutorial.math.lamar.edu/problems/calcii/powerseries.aspx?utm_source=chatgpt.com "Calculus II - Power Series (Practice Problems)"))
    
- Jerison, David (MIT OpenCourseWare). _18.01 Single Variable Calculus — “Taylor’s Series” lecture and notes._ ([MIT OpenCourseWare](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/resources/lecture-38-taylors-series/?utm_source=chatgpt.com "Lecture 38: Taylor's Series | Single Variable Calculus"))
    
- OpenStax. _Calculus, Volume 2 — Power Series and Functions._ ([OpenStax](https://openstax.org/books/calculus-volume-2/pages/6-1-power-series-and-functions?utm_source=chatgpt.com "6.1 Power Series and Functions - Calculus Volume 2"))
    
- Rudin, Walter. _Principles of Mathematical Analysis_. McGraw-Hill.
    
- Sanderson, Grant (3Blue1Brown). _Taylor series._ ([3Blue1Brown](https://www.3blue1brown.com/lessons/taylor-series?utm_source=chatgpt.com "Taylor series - 3Blue1Brown"))
    
- Stewart, James. _Calculus_. Cengage Learning, 2021. (Your vault PDF: _MATH-CALC-STEWART.pdf_.)
    
- _MATH-185-HW-PROBLEMS.pdf_ (assigned exercise ranges for §§11.8–11.11).
    
- _MATH-185-LECTURE-VIDEOS.pdf_ (lecture mapping for §§11.8–11.10).