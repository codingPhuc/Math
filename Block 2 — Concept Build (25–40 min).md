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

**V2 [DATA]** Make a two-column table for V1 near $x=0$ with $x=-0.1,-0.01$ and $x=0.01,0.1$.  
Labels: numeric side-limits.  
Check: Explain the match/mismatch between table and graph.

| x        | f(x)      |
| -------- | --------- |
| -0.99999 | 0.00001   |
| .000001  | 0 .999999 |
the limit approaching the value on the right equal to  1 while the limit approaching from the left equal to 0.  so the two limit doesn't match so we concluded that the limit does not exit 
**V3 [CON]** Modify V1 so the right branch is $2-x$ for $x\ge0$.  
Labels: left/right limits at $0$.  
Check: Classify the discontinuity at $0$.
$$
\lim_{ x \to  0^+ }      =     
$$

**Group B: Removable vs jump**  
**V4 [PROC]** Sketch $y=\dfrac{x^2-4}{x-2}$ with a hole at $x=2$.  
Labels: factorization line “$(x-2)(x+2)/(x-2)$,” the hole $(2,4)$, and the extension $f(2)=4$.  
Check: Type of discontinuity? New value to make it continuous?

**V5 [CASE]** Draw a step jump at $x=1$ with left height $3$ and right height $5$. Put a solid dot at $(1,-1)$.  
Labels: $\lim_{x\to1^-}$, $\lim_{x\to1^+}$, $f(1)$.  
Check: Does the two-sided limit exist? Why?

**V6 [ARG]** On the same axes, sketch a function that blows up like $1/(x-2)^2$ at $x=2$.  
Labels: $\pm\infty$ behavior.  
Check: Limit type here?

**Group C: Rational cancellation**  
**V7 [PROC]** Sketch $y=\dfrac{(x-3)(x+1)}{x-3}$ with a hole at $x=3$.  
Labels: hole coordinate, simplified form.  
Check: $\lim_{x\to3} y=$ ?

**V8 [APP]** Sketch $y=\dfrac{|x-3|(x-3)}{x-3}$ for $x\ne3$.  
Labels: express as $|x-3|$.  
Check: $\lim_{x\to3} y=$ ?

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


