# Block 2 — Concept Build (25–40 min)

Focus: one-sided vs two-sided limits, removable vs jump, and algebraic cancellation. Stewart 9e §§2.2–2.4. TI-84 allowed.

---

## Visual (draw/label/map) — 9 minis

Do each sketch in ~60–90 s. Add the listed labels. Answer the “Check.”  
— **HOLD SOLUTIONS** —

**Group A: Piecewise corners (one-sided limits)**  
**V1 [PROC]** Sketch the graph of  
$$  
f(x)=  
\left\{\begin{array}{l}  
x+1,& x<0\\  
1-x,& x\ge 0  
\end{array}\right.  
$$  
Labels: open/closed circles at $x=0$, $f(0)$, $x\to0^-$ value, $x\to0^+$ value.  
Check: Does $\lim_{x\to0}f(x)$ exist?
![[IMG_1885.jpg]]
**V2 [DATA]** Make a two-column table for V1 near $x=0$ with $x=-0.1,-0.01$ and $x=0.01,0.1$.  
Labels: numeric side-limits.  
Check: Explain the match/mismatch between table and graph.

| $x^-$ | f(x)      | $x^+$ | f(x) |
| ----- | --------- | ----- | ---- |
| -0.1  | 0.9       | 0.1   |      |
| -0.01 | 0 .999999 | 0.01  |      |
the limit approaching the value on the right equal to  1 while the limit approaching from the left equal to 0.  so the two limit doesn't match so we concluded that the limit does not exit 
**V3 [CON]** Modify V1 so the right branch is $2-x$ for $x\ge0$.  
Labels: left/right limits at $0$.  
Check: Classify the discontinuity at $0$.
$$
\lim_{ x \to  0^+ }   2  - x      = 1.999999  = 2   
\lim_{  x  \to   0^- }    x + 1   =   0.00001 
$$

**Group B: Removable vs jump**  
**V4 [PROC]** Sketch $y=\dfrac{x^2-4}{x-2}$ with a hole at $x=2$.  
Labels: factorization line “$(x-2)(x+2)/(x-2)$,” the hole $(2,4)$, and the extension $f(2)=4$.  
Check: Type of discontinuity? New value to make it continuous?
this is a removable discontinuity, because the function is valid at x = 2 when fully factor out 
**V5 [CASE]** Draw a step jump at $x=1$ with left height $3$ and right height $5$. Put a solid dot at $(1,-1)$.  this is easy ignore, next time add in a function 
Labels: $\lim_{x\to1^-}$, $\lim_{x\to1^+}$, $f(1)$.  
Check: Does the two-sided limit exist? Why?
the two sided limit does not exit because the right hand  limit does not equal to the left hand limit 


**V6 [ARG]** On the same axes, sketch a function that blows up like $1/(x-2)^2$ at $x=2$.  
Labels: $\pm\infty$ behavior.  
Check: Limit type here
asymptotic  limit  


**Group C: Rational cancellation**  
**V7 [PROC]** Sketch $y=\dfrac{(x-3)(x+1)}{x-3}$ with a hole at $x=3$.  
Labels: hole coordinate, simplified form.  
Check: $\lim_{x\to3} y=$ ? 
$$
y=\dfrac{(x-3)(x+1)}{x-3}    =  \lim_{ x  \to 3v }     x + 1    \implies 3 + 1  = 4  
$$
![[IMG_1886.jpg]]

**V8 [APP]** Sketch $y=\dfrac{|x-3|(x-3)}{x-3}$ for $x\ne3$.  
Labels: express as $|x-3|$.  
Check: $\lim_{x\to3} y=$ ?


$$
\lim_{  x \to  3  }   = y=\dfrac{|x-3|(x-3)}{x-3}       
$$
this is a removable discontinuous 
  ![[IMG_1887 1.jpg]]
**V9 [CON]** Draw a wildly oscillating wave near $x=0$ to represent $\sin(1/x)$.  
Labels: dense hits at $y=\pm1$.  
Check: State the DNE reason precisely.

Refs: §2.2 tables/graphs; §2.3 algebraic limits; §2.4 precise definitions.

---

## Audio (60–90 s speak-aloud script)

Read verbatim:

“Today I’m deciding when a limit exists. A limit is the number $L$ that $f(x)$ approaches as $x$ gets close to $a$ from both sides. I check left and right: if they match, the two-sided limit exists. A hole means a **removable** discontinuity; different side heights mean a **jump**; blow-up or endless oscillation means **DNE**.

Example 1: $f(x)=\dfrac{x^2-4}{x-2}$.  
$$  
\lim_{x\to2}f(x)=\lim_{x\to2}\frac{(x-2)(x+2)}{x-2}=\lim_{x\to2}(x+2)=4  
$$  
Plain: values crowd around $4$; define $f(2)=4$ to remove the hole.

Example 2 (piecewise):  
$$  
f(x)=  
\left\{\begin{array}{l}  
x+1,\ x<0\\  
1-x,\ x\ge0  
\end{array}\right.  
$$  
Left at $0$ is $1$, right at $0$ is $1$, so $\lim_{x\to0}f(x)=1$ even if $f(0)$ were different.

Example 3: $\sin(1/x)$ near $0$ has no single approach value because it keeps hitting numbers between $-1$ and $1$. So the limit DNE by oscillation.”

---

## Oral (“teacher mode”)

Speak answers out loud. I will drill deeper after each reply. Start:

1. “In one sentence, what does $\lim_{x\to a}f(x)=L$ assert?”  
    Follow-up if vague: “Does it claim anything about $f(a)$? Be explicit.”
    
2. “For  
    $$  
    f(x)=  
    \left\{\begin{array}{l}  
    x+1,\ x<0\\  
    1-x,\ x\ge0  
    \end{array}\right.  
    $$  
    give $\lim_{x\to0^-}f(x)$ and $\lim_{x\to0^+}f(x)$, and justify which formula you used.”  
    Follow-up: “State the two-sided limit and the discontinuity type, if any.”
    
3. “Name three distinct DNE patterns and give a one-line example of each.”
    
4. “Why can a graph have $f(a)\ne L$ even when $\lim_{x\to a}f(x)=L$? Provide a numeric table that shows this.”
    

**Rating rubric (0–2 each):** Accuracy, Clarity, Justification, Vocabulary. I’ll score on request.

---

## Kinesthetic (hands-on)

1. **Card-sort, 12 cards**  
    Make three piles: _Removable_, _Jump_, _Other DNE_. On each card write: a sketch cue, a minimal formula, and a 6–10 word reason. Sort, then explain each pile in 30 s.
    
2. **TI-84 micro-tables**  
    For $f(x)=\dfrac{x^2-4}{x-2}$, build a table around $x=2$ with increments $0.1, 0.01, 0.001$. Record the approach value. Repeat for $g(x)=\dfrac{(x-3)(x+1)}{x-3}$ near $x=3$.
    
3. **Piecewise builder**  
    Write three original piecewise functions in your template that create: a hole, a jump, and continuity with different formulas. Verify side-limits symbolically.
    
4. **Explain-to-object**  
    Explain to a pen what a side-limit is in 20 s, then repeat using only numbers (no variables).
    

Refs: §2.2 reading tables/graphs; §2.3 cancellation; §2.4 wording of definitions.

---

## Plain-language anchors

- “Limits care about the approach, not the point.”
    
- “Two sides, one number ⇒ limit exists.”
    
- “Different side heights ⇒ jump; hole with a value to fill ⇒ removable.”
    

Say **continue** for Block 3 or **reveal** when worked example solutions appear.

---

### Definitions

limit: The number $L$ approached by $f(x)$ as $x$ nears $a$.  
one-sided limit: Approach from left ($x\to a^-$) or right ($x\to a^+$).  
removable discontinuity: Limit exists at $a$, but $f(a)$ is missing/different.  
jump discontinuity: Side-limits exist but are unequal.  
oscillation DNE: Outputs vary without settling to one value near $a$.





# Error note 
Score 6/10. Not yet passing (target ≥8). Biggest issue: mis-reading side-limits from tables and sloppy labeling.

Targeted hint — Tables→Limits: For $x\to a^-$ plug values like $a-10^{-k}$ into the **left-hand** formula; for $x\to a^+$ use $a+10^{-k}$ in the **right-hand** formula. Do not subtract “almost-$a$” from $1$ unless that’s the given formula.

## Itemized notes

- **V1 (piecewise sketch):** Template correct but the function body wasn’t fully rendered in the PDF; be sure the two branches appear and mark the open/closed dots at $x=0$. Label $f(0)$ explicitly.
    
- **V2 (table near $0$):** Your claimed left limit $0$ is wrong for $x+1$; it should be $1$. Your table mixes numbers that don’t come from the correct branch. State: $\lim_{x\to0^-}(x+1)=1$, $\lim_{x\to0^+}(1-x)=1$.
    
- **V3 (change right branch to $2-x$):** Right idea, but you computed the left side wrong again. Should be $\lim_{x\to0^-}(x+1)=1$ and $\lim_{x\to0^+}(2-x)=2$ → **jump** at $0$.
    
- **V4 ($\tfrac{x^2-4}{x-2}$ hole):** Classification right: **removable**; say explicitly “continuous if $f(2)=4$,” not “valid when fully factored.”
    
- **V5 (step at $x=1$):** Do not skip with “easy ignore.” You needed labels $\lim_{x\to1^-}$, $\lim_{x\to1^+}$, and $f(1)=-1$; justify “two-sided limit DNE (jump).”
    
- **V6 ($1/(x-2)^2$):** Use standard language “**infinite limit**; diverges to $+\infty$ on both sides,” not “asymptotic limit.” Two-sided finite limit **does not exist**.
    
- **V7 ($\tfrac{(x-3)(x+1)}{x-3}$):** Good: limit $=4$. Also mark the hole at $(3,4)$.
    
- **V8 ($\tfrac{|x-3|(x-3)}{x-3}$):** Finish the argument: for $x\ne3$, this equals $|x-3|$ so $\lim_{x\to3}y=0$ and the discontinuity is **removable** with $f(3)=0$. Your line is incomplete.
    
- **V9 ($\sin(1/x)$):** State the reason: **oscillation** between $-1$ and $1$ yields no single approach value. Put this in the check.
    

## Quick fixes you can paste into Obsidian

- **Side-limit answers for V2:**  
    $$  
    \lim_{x\to0^-}(x+1)=1,\quad \lim_{x\to0^+}(1-x)=1,\quad \lim_{x\to0}f(x)=1  
    $$  
    Plain: both sides give $1$.
    
- **V3 classification (right branch $2-x$):**  
    $$  
    \lim_{x\to0^-}(x+1)=1,\quad \lim_{x\to0^+}(2-x)=2\ \Rightarrow\ \text{jump at }0  
    $$  
    Plain: side heights differ, so two-sided limit DNE.
    
- **V6 language:**  
    $$  
    \lim_{x\to2}\frac{1}{(x-2)^2}=+\infty\quad\text{(diverges; no finite limit)}  
    $$  
    Plain: grows without bound from both sides.
    
- **V8 rewrite:**  
    $$  
    \frac{|x-3|(x-3)}{x-3}=|x-3|\ (x\ne3),\quad \lim_{x\to3}|x-3|=0  
    $$  
    Plain: hole at $(3,0)$; set $f(3)=0$ for continuity.
    

## Next actions

1. Redo V2–V3 tables with correct branch formulas.
    
2. Add missing labels and the actual $f(1)$ in V5.
    
3. Replace “asymptotic limit” with “infinite limit” in V6.
    
4. Complete V8 check with limit value and continuity fix.
    

**Progress log** — Block 2 Visuals | 2025-11-11 11:00 PT | Score: 6/10 | Mistakes: side-limits/tables; labels/notation; classification language | Recurrence: side-limits recurring from Diagnostic | Trend: ↗ improving.

### Definitions

limit: number approached by $f(x)$ as $x$ nears $a$.  
one-sided limit: approach from $x\to a^-$ or $x\to a^+$.  
removable discontinuity: hole; define $f(a)=\lim_{x\to a}f(x)$ to fix.  
jump discontinuity: side-limits exist but differ.  
infinite limit: values grow unbounded; no finite limit.
