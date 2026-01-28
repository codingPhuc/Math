# Section 7.8 (Improper Integrals) — Study Plan (Obsidian)

## A) Concept spine for Section 7.8 (Improper Integrals)

### 1) Prerequisites map (with citations)

- **P1. Limits as “stabilization of finite approximations”**  
    You will use limits to replace illegal endpoint values like $\infty$ or a blow-up point. Stewart explicitly frames §7.8 as extending the definite integral by taking limits when the interval is infinite or the integrand has an infinite discontinuity.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.543, heading “Improper Integrals”; note the reference to infinite discontinuity in §5.2.)_
    
- **P2. Definite integral as (signed) area on a finite interval**  
    The entire intuition of §7.8 is “area of an infinite region = limit of areas of truncated finite regions.” Stewart builds Type 1 from an area-truncation story under $y=\frac{1}{x^2}$.  
    _(MATH-CALC-STEWART.pdf, §7.8, pp.543–544, “Type 1: Infinite Intervals”; Figures 1–2 discussion.)_
    
- **P3. Infinite discontinuity / vertical asymptotes**  
    Type 2 is “infinite in the vertical direction,” so you need the idea of a vertical asymptote and one-sided approach. Stewart explicitly distinguishes Type 1 (horizontal unboundedness) vs Type 2 (vertical unboundedness).  
    _(MATH-CALC-STEWART.pdf, §7.8, p.546, “Type 2: Discontinuous Integrands”.)_
    
- **P4. Basic integration technique selection (Calc I level)**  
    Many problems reduce to: compute $\int_a^t f$ (ordinary), then take a limit; so any technique you already use for definite integrals may show up inside that “truncate → integrate → limit” pipeline. Stewart’s exercise directions are explicitly “evaluate if convergent, otherwise determine divergence.”  
    _(MATH-CALC-STEWART.pdf, §7.8 Exercises, “5–48… Evaluate… if convergent; otherwise determine divergence.”)_
    

---

### 2) Core definitions + notation (with citations)

- **D1. Type 1 improper integral (infinite interval)**  
    Stewart’s Definition 1 formalizes “integrate on $[a,t]$ then send $t\to\infty$” and similarly for $(-\infty,b]$.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.543, heading “Definition of an Improper Integral of Type 1”.)_
    
- **D2. Convergent vs divergent (for improper integrals)**  
    Stewart: convergent if the defining limit exists as a finite number; divergent otherwise.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.543, Definition 1 after parts (a)–(b).)_
    
- **D3. Type 2 improper integral (infinite discontinuity)**  
    Stewart’s Definition 3 is one-sided: you approach the discontinuity from the side where the function is defined; for an interior discontinuity at $c$, you must split into $\int_a^c+\int_c^b$, and the total is defined only if both converge.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.546, “Definition of an Improper Integral of Type 2”.)_
    
- **D4. The “area interpretation” (the intuition you are after)**  
    For $f\ge 0$, Stewart explicitly defines the area of the infinite region as the value of the convergent improper integral; the key phrase is that $\int_a^\infty f$ is the limit of the area under $f$ from $a$ to $t$.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.543, after Definition 1, “Any of the improper integrals… interpreted as an area… limit as $t\to\infty$ of the area…”.)_
    

---

### 3) Core results + what each buys you (with citations)

- **R1. “Infinite region can have finite area” (why improper integrals are not just a technicality)**  
    Stewart’s opening example shows  
    $$\int_1^\infty \frac{1}{x^2},dx$$  
    converges to $1$, i.e., the region extends infinitely but its accumulated area stabilizes. This gives you the central intuition: convergence means “added tail area eventually becomes negligible.”  
    _(MATH-CALC-STEWART.pdf, §7.8, pp.543–544, Figures 1–2 discussion and conclusion “area… approaches 1”.)_
    
- **R2. $p$-test benchmark for tails: $\int_1^\infty \frac{1}{x^p},dx$**  
    Stewart summarizes Example 4: convergent if $p>1$, divergent if $p\le 1$. This buys you a “decay-rate ruler”: if your integrand behaves like $\frac{1}{x^p}$ for large $x$, you can often decide convergence quickly.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.546, “We summarize the result of Example 4…”.)_
    
- **R3. Type 2 is “vertical tail area,” with one-sided limits and mandatory splitting**  
    This buys you correctness: you cannot treat a blow-up point as if it were an ordinary endpoint; you must approach it from the appropriate side, and for interior blow-ups you must check both sides independently.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.546, Definition 3 (a)–(c) and the vertical-direction discussion.)_
    
- **R4. Comparison Theorem (improper integrals): bounding buys you decisions without explicit antiderivatives**  
    Stewart states the core comparison logic: if $0\le f\le g$ and $\int g$ converges then $\int f$ converges; if $0\le g\le f$ and $\int g$ diverges then $\int f$ diverges. This buys you “convergence by inequality,” the main non-memorization tool in §7.8.  
    _(MATH-CALC-STEWART.pdf, §7.8, p.549, heading “Comparison Theorem for Improper Integrals”.)_
    

---

### 4) Canonical problem types

(Referenced directly from Stewart’s §7.8 exercise categories; these are the skills the section expects.)

- **C1.** Classify proper vs improper; rewrite as limits.  
    _(MATH-CALC-STEWART.pdf, §7.8 Exercises, “1–4 Determine whether… proper or improper…”.)_
    
- **C2.** Type 1 evaluation / convergence decision (truncate to $t$, integrate, take $\lim_{t\to\infty}$).  
    _(MATH-CALC-STEWART.pdf, §7.8 Exercises, “5–48… Evaluate… if convergent; otherwise determine divergence.”)_
    
- **C3.** Type 2 evaluation / convergence decision (one-sided limits; split at interior singularities).  
    _(MATH-CALC-STEWART.pdf, §7.8, Definition 3; and §7.8 Exercises same directive.)_
    
- **C4.** Comparison-based decisions (no explicit evaluation).  
    _(MATH-CALC-STEWART.pdf, §7.8, “Comparison Theorem…”.)_
    
- **C5.** Mixed Type 1 + Type 2 (split to isolate each “bad behavior”).  
    _(MATH-CALC-STEWART.pdf, §7.8 Exercises, “65–68… both Type 1 and Type 2.”)_
    

---

## B) Action plan by subtopic (ordered by dependency)

### Subtopic 1 — The one mental model you need: “improper integral = limit of ordinary integrals”

#### 1) Learn (exact targets + key extract items)

- **Primary target (authoritative):**  
    MATH-CALC-STEWART.pdf, §7.8, pp.543–544, heading “Improper Integrals” + “Type 1: Infinite Intervals” and the truncation-area narrative.
    
- **Key extract items (5–12):**
    
    - “Improper” means either (i) infinite interval or (ii) infinite discontinuity.
        
    - Infinite region does not automatically imply infinite area; you must test via a limit of truncated areas.
        
    - The truncation parameter $t$ is not a trick; it is the definition’s mechanism for making sense of “area up to infinity.”
        
    - Your “concept check”: convergence = tail contribution eventually stops changing the accumulated area (use the “approaches 1” language).
        
- **Secondary (project-source, intuition-focused):**  
    MATH-CALC-SPIVAK-4E.pdf, Ch. 14 (FTC), around p.301, Problem 25: “The limit … is called an ‘improper integral’.” This reinforces the “improper integral is a limit” identity from a more rigorous voice.
    

#### 2) Mastery targets (I can…)

- I can explain in one sentence why $\int_a^\infty$ must be defined as a limit, not as “plug in infinity” (Stewart’s truncation story).
    
- I can translate “finite accumulated area” into “the limit of truncated areas exists.”
    
- I can identify whether the “infinite-ness” is horizontal (Type 1) or vertical (Type 2) just from the problem’s geometry/algebra.
    

#### 3) Self-test (closed notes)

- **Recall quiz (5–10):**
    
    - State, in words, what quantity $A(t)=\int_a^t f(x),dx$ represents in the geometry picture.
        
    - What does it mean (conceptually) that $\lim_{t\to\infty}A(t)$ exists?
        
    - Give two different ways an integral can be improper (interval vs integrand).
        
    - Explain the phrase “infinite in a horizontal direction” vs “infinite in a vertical direction.”
        
    - Why does “region is infinite” not imply “area is infinite”? Cite the Stewart example idea.
        
- **Practice (from PDFs; grouped by training goal):**
    
    - Easy (classification): Stewart §7.8 Exercises 1–4 (proper vs improper; rewrite).
        
    - Medium (basic truncate→integrate→limit): Stewart §7.8 Exercises 5–12.
        
    - Hard (mixed behavior / trickier setups): Stewart §7.8 Exercises 65–68 (both Type 1 and Type 2).
        

#### 4) Error-correction loop

- **Threshold:** <85% on the classification + limit-setup step (you must write the correct limit form before computing).
    
- **Remediation:**
    
    - Re-read Stewart §7.8 opening (pp.543–544) and rewrite the “truncation story” from memory in 6 lines.
        
    - Micro-drill: redo 1–4 (setup only), then 5–8 (full).
        

---

### Subtopic 2 — Type 1 definition: “tails” and why splitting matters

#### 1) Learn

- **Primary target:**  
    MATH-CALC-STEWART.pdf, §7.8, p.543, “Definition of an Improper Integral of Type 1” parts (a)–(c), and the area interpretation immediately after.
    
- **Key extract items:**
    
    - The exact limit-definition pattern for $\int_a^\infty$ and $\int_{-\infty}^b$.
        
    - Convergent/divergent is a statement about the limit’s existence as a finite number.
        
    - $\int_{-\infty}^{\infty}$ is defined via a split (part (c)); it is not “one symmetric limit” by default.
        
    - Why this is the right geometry: area from $a$ to $t$ then $t\to\infty$.
        
- **Secondary intuition (project-source):**  
    Spivak warns about “another kind of improper integral” (the two-sided case defined as a sum of two one-sided improper integrals). This is exactly the conceptual trap to avoid. (MATH-CALC-SPIVAK-4E.pdf, around p.301, Problem 27.)
    

#### 2) Mastery targets

- I can set up the correct limit form for any Type 1 integral without computing it.
    
- I can explain why $\int_{-\infty}^{\infty}$ requires two separate convergence checks (split definition).
    
- I can interpret convergence as “the tail contributes vanishing additional area.”
    

#### 3) Self-test

- **Recall quiz:**
    
    - Write Definition 1(a), 1(b), 1(c) from memory.
        
    - What does part (c) allow you to choose arbitrarily, and why is that useful?
        
    - Explain the conceptual difference between $\lim_{t\to\infty}\int_{-t}^{t}$ and the split definition (use Spivak’s warning).
        
- **Practice:**
    
    - Easy: Stewart 1–4 (setup discipline).
        
    - Medium: Stewart 5–21 odd (your course assigns a big chunk starting at 5; treat early odds as warm-up).  
        _(MATH-185-HW-PROBLEMS.pdf, “7.8 #5–37 odds…”.)_
        
    - Hard: Stewart 33–37 odd (later odds are typically more decision-heavy) + 49, 51, 53.  
        _(MATH-185-HW-PROBLEMS.pdf, “7.8 #5–37 odds, #49,51,53”.)_
        

#### 4) Error-correction loop

- **Threshold:** <80% correct on (i) writing the right limit(s), (ii) stating whether convergence requires one or two checks.
    
- **Remediation:**
    
    - Re-read Definition 1 + area interpretation (p.543) and rewrite it as a “two-line schema” you can apply mechanically.
        
    - Micro-drill (2–5 problems): pick 5 from your assigned odds in 5–37; do setup only; then compute only after setup is correct.
        

---

### Subtopic 3 — The $p$-test intuition: “how fast must the tail die?”

#### 1) Learn

- **Primary target:**  
    MATH-CALC-STEWART.pdf, §7.8, p.546, “We summarize the result of Example 4…” (the benchmark $\int_1^\infty \frac{1}{x^p},dx$).
    
- **Key extract items:**
    
    - The threshold $p=1$ is the cliff: $p>1$ converges, $p\le 1$ diverges.
        
    - Concept translation: $p>1$ means tails shrink fast enough that the total added area stabilizes; $p\le 1$ means tails shrink too slowly (use Stewart “area approaches a number” language).
        

#### 2) Mastery targets

- I can decide convergence of $\int_1^\infty x^{-p},dx$ instantly from $p$.
    
- I can use $\frac{1}{x^p}$ as a comparison target for other tails (even before integrating).
    
- I can explain why “$f(x)\to 0$” is not sufficient for convergence (slow-decay tails; “area may still not stabilize”).
    

#### 3) Self-test

- **Recall quiz:**
    
    - State the $p$-test in one line.
        
    - Give a tail-decay explanation of why $p=1$ is the boundary (no computations, just “how much area is left in the tail?”).
        
- **Practice (from your PDFs):**
    
    - Medium: From your assigned set 7.8 #5–37 odd, flag every integrand whose large-$x$ behavior resembles $\frac{1}{x^p}$, and predict converge/diverge before computing.  
        _(Assignment list in MATH-185-HW-PROBLEMS.pdf.)_
        
    - Hard: Stewart 65–68 (mixed issues force you to isolate tails + singularities; good for not memorizing formulas).
        

#### 4) Error-correction loop

- **Threshold:** <80% accuracy on “predict converge/diverge before integrating” for 10 problems.
    
- **Remediation:**
    
    - Re-read Stewart’s $p$-test summary (p.546) and rewrite it as “decay-rate ruler.”
        
    - Micro-drill: choose 3–5 from your assigned odds where your prediction failed; redo with comparison-first thinking (no integration until your comparison statement is written).
        

---

### Subtopic 4 — Type 2 definition: “vertical tails,” one-sided limits, and splitting at $c$

#### 1) Learn

- **Primary target:**  
    MATH-CALC-STEWART.pdf, §7.8, p.546, “Type 2: Discontinuous Integrands” + “Definition of an Improper Integral of Type 2” (a)–(c).
    
- **Key extract items:**
    
    - Type 2 intuition: region is infinite vertically (near a vertical asymptote), so you truncate near the asymptote: $t\to b^-$ or $t\to a^+$.
        
    - The definition is one-sided by design (you approach from where the function exists).
        
    - Interior singularity at $c$ forces splitting and requires both sides to converge.
        
    - Example 5 explicitly labels “improper because … vertical asymptote,” so you train the recognition reflex.
        

#### 2) Mastery targets

- I can detect the blow-up point (endpoint vs interior) and write the correct one-sided limit(s).
    
- I can state and apply the “both halves must converge” rule for an interior discontinuity.
    
- I can explain Type 2 as “vertical tail area” in the same truncation language as Type 1.
    

#### 3) Self-test

- **Recall quiz:**
    
    - Write Definition 3(a)–(c) from memory (including the directions of approach).
        
    - For an interior blow-up at $c$, what exact two limits must exist?
        
    - Explain the sentence: “Here the region is infinite in a vertical direction.”
        
- **Practice:**
    
    - Easy: Stewart 1–4 (some are Type 2 classification).
        
    - Medium: Stewart 5–37 odd (your assigned core), focusing on those with denominators that vanish at endpoints/interior points. _(Assignment list.)_
        
    - Hard: Stewart 65–68 (explicitly “both Type 1 and Type 2”).
        

#### 4) Error-correction loop

- **Threshold:** <85% on the “setup step” (correct split + correct one-sided arrows).
    
- **Remediation:**
    
    - Re-read Definition 3 + the vertical-tail paragraph (p.546) and rewrite the schema: “identify discontinuity → choose side(s) → limit.”
        
    - Micro-drill: do 3 problems from your assigned odds where you previously forgot to split or used the wrong approach direction.
        

---

### Subtopic 5 — Comparison Theorem: the anti-memorization tool

#### 1) Learn

- **Primary target:**  
    MATH-CALC-STEWART.pdf, §7.8, p.549, heading “Comparison Theorem for Improper Integrals,” including the “not valid in reverse direction” caution.
    
- **Key extract items:**
    
    - The two usable directions: upper-bound to prove convergence; lower-bound to prove divergence.
        
    - The caution: converses fail (don’t infer convergence of $g$ from convergence of $f$).
        
    - Intuition translation: you’re bounding “area you care about” by “area you already understand” (tie back to the area interpretation).
        
- **Secondary (project-source, more rigorous framing):**  
    Spivak Problem 25(c): if $0<g(x)<f(x)$ and $\int f$ exists, then $\int g$ exists—this is the same comparison idea stated in a proof-oriented style. (MATH-CALC-SPIVAK-4E.pdf, p.301, Problem 25(c).)
    

#### 2) Mastery targets

- I can choose an appropriate comparison target (usually $\frac{1}{x^p}$) and justify the inequality on the relevant interval.
    
- I can decide whether I’m trying to prove convergence or divergence and pick the inequality direction accordingly.
    
- I can articulate, in one sentence, why comparison is concept-first: it avoids computing antiderivatives.
    

#### 3) Self-test

- **Recall quiz:**
    
    - State both parts of the Comparison Theorem and the hypothesis $0\le f\le g$.
        
    - Give one reason the reverse direction is invalid.
        
    - Which benchmark from Stewart do you most often compare to for tails?
        
- **Practice:**
    
    - Medium: from your assigned set 7.8 #5–37 odd, pick 8 problems and attempt comparison-first decisions before any integration. _(Assignment list.)_
        
    - Hard: include 49, 51, 53 from the assignment (these are commonly where comparison/structure matters more).
        
    - Optional hard (concept stress-test): Stewart 56 (graph-based convergence decision).
        

#### 4) Error-correction loop

- **Threshold:** <80% on “choose a correct comparator and inequality” (even if the final conclusion is right by luck, this must be right).
    
- **Remediation:**
    
    - Re-read the Comparison Theorem statement (p.549) and rewrite it as two boxed implication templates.
        
    - Micro-drill: 2–5 problems from your assigned set where you got stuck; for each, write only: (i) comparator, (ii) inequality, (iii) theorem direction, then stop. Compute only after that’s correct.
        

---

### Subtopic 6 — Course alignment: your required practice set (MATH-185)

#### 1) Learn

- **Target:**  
    MATH-185-HW-PROBLEMS.pdf, HW entry for §7.8 listing required problems (anchor “7.8”).
    
- **Key extract items:**
    
    - Your required set is: Stewart §7.8 **#5–37 odd, #49, #51, #53, #69** (this is the spine of your mastery practice).
        

#### 2) Mastery targets

- I can tag each assigned problem as Type 1 / Type 2 / mixed before doing any algebra.
    
- I can write the correct limit definition immediately (no hesitation).
    
- I can choose between “evaluate directly” vs “comparison theorem” based on whether a clean antiderivative path exists.
    

#### 3) Self-test

- **Recall quiz (ritual):**
    
    - For each assigned problem you attempt, force a 10-second pre-step: “Type? Limit form? Comparator?”
        
- **Practice (grouping the required set by training objective; use this ordering):**
    
    - Easy (build the pipeline): #5–15 odd (truncate → integrate → limit).
        
    - Medium (more choice-making): #17–37 odd.
        
    - Hard (concept/strategy): #49, #51, #53, #69 (often where comparison or careful setup is the real skill).
        

#### 4) Error-correction loop

- **Threshold:** <90% on setup correctness across the assigned set (setup errors are fatal in §7.8).
    
- **Remediation:**
    
    - Re-read Stewart Definition 1 + Definition 3 and rewrite both schemas from memory.
        
    - Micro-drills (2–5 problems): pick the last 2–5 you missed; redo with “setup-only pass” first, then a “compute pass.”
        

---

## C) Supplemental resources NOT in my PDFs

### 1) Rigorous textbook (for conceptual clarity + clean definitions)

- Courant, Richard, and Fritz John. _Introduction to Calculus and Analysis, Vol. 1._ 1999 reprint (original mid-20th c.). Springer.  
    **Why it helps THIS topic:** it treats integrals and limits as a single conceptual machine, so “improper integral = limit” feels inevitable rather than a patch.  
    **How to use:** read the section on integrals defined via limiting processes; then re-derive Stewart’s Type 1 and Type 2 definitions in your own words.
    

### 2) Intuition/visual resource (for the “infinite region, finite area” picture)

- Dawkins, Paul. _Paul’s Online Math Notes: Improper Integrals_ (web notes).  
    **Why it helps:** multiple graphs + verbal explanations of “tail area,” plus many examples that emphasize _why_ convergence happens.  
    **How to use:** skim the visuals first; then, for each Stewart assigned problem, write a one-line “tail story” (horizontal tail vs vertical tail) before computing.
    

### 3) Problem source with solutions/hints (for lots of targeted practice with feedback)

- Ayres, Frank, and Elliott Mendelson. _Schaum’s Outline of Calculus._ McGraw-Hill.  
    **Why it helps:** huge banks of solved improper-integral problems; you can compare your setup (limits/splits) directly to worked solutions.
    

### Optional proof/rigor reference (only if you want the comparison theorem to feel “obvious”)

- Abbott, Stephen. _Understanding Analysis._ 2nd ed., 2015. Springer.  
    **Why it helps:** formalizes convergence ideas and comparison principles so Stewart’s Comparison Theorem reads like a natural corollary of order + limits.
    

### Works Cited (supplementals)

- Abbott, Stephen. _Understanding Analysis._ 2nd ed., 2015. Springer.
    
- Ayres, Frank, and Elliott Mendelson. _Schaum’s Outline of Calculus._ McGraw-Hill.
    
- Courant, Richard, and Fritz John. _Introduction to Calculus and Analysis, Vol. 1._ Springer, 1999.
    
- Dawkins, Paul. _Paul’s Online Math Notes: Improper Integrals._ Web platform.