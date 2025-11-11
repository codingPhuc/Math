---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-11-11
amount of time:
learning score:
---



Here’s the diagnostic, cleaned for Obsidian. Inline math uses $...$. Block math uses $$...$$.

# Limits — Block 1 Diagnostic (5–10 min)

Directions: 1 minute per item. TI-84 allowed for quick numeric checks only. No solutions here.

**Q1 [DATA]**  
From the table for $f(x)=\frac{x^2-4}{x-2}$ near $x=2$:

|x|1.9|1.99|2.01|
|---|---|---|---|
|f(x)|3.9|3.99|4.01|

Find $\lim_{x\to 2} f(x)$ and classify the discontinuity at $x=2$ (removable/jump/none).  
Ans: ______
$$
\begin{array}{l} \\
 f(x)  = \lim_{x\to 2} f(x) \frac{x^2  - 4}{x- 2 }    = \lim_{x\to 2} f(x)  \frac{ 2^2  -4}{ 2  -2 }  =  \frac{0}{0} \implies \text{ undefine }  \\
 \lim_{x\to 2}  \frac{(x  - 2)(x+ 2)}{  x - 2 }   =   \lim_{x\to 2}  (x+ 2 )   =  2 +  2   = 4  
\end{array}
$$
therefore the function $f(x)$ have a removable discontinuity,  because we can factor the function to remove the discontinuity 

**Q2 [PROC]**  
$$ 

f(x)= 
\left\{ \begin{array} {l}  
x+1,& x<0\\
1-x,& x\ge 0  
\end{array}   \right.

$$  
Find $\lim_{x\to 0^-}f(x)$, $\lim_{x\to 0^+}f(x)$, and $\lim_{x\to 0}f(x)$.  
Ans: ______
$$
\begin{array}{l}  \\
\lim_{  x \to  0^[-] }     =  1 -  0.99999   =  0.00001 \implies \lim_{ x  \to  0^- }     f(x)  =   0      \\ \\
\lim_{   x \to  0^+   }   =  1.000001    + 1  =  2    \implies  \lim_{ x  \to  0^+  }    f(x)    = 2   \\
\lim_{  x  \to 0  }  =  \text{ undefind }     
\end{array}
$$
**Q3 [CON]**  
A graph has an open circle at $(1,3)$ on a left branch approaching $3$ as $x\to 1^-$. The right branch approaches $5$ as $x\to 1^+$. There is a solid dot at $(1,-1)$. Give $\lim_{x\to 1^-}f(x)$, $\lim_{x\to 1^+}f(x)$, $\lim_{x\to 1}f(x)$, and $f(1)$.  
Ans: ______

$$
\begin{array}{l} \\
\lim_{x     \to  1+  }    =  5      \\
\lim_{  x \to  1^-  }   =  3 \\
\lim_{  x \to  1 }     = \text{undefind} \text{ ( the left hand limit does not equal the right hand limit)}   \\
 f(1 ) =   3     
\end{array}
 
   
$$

**Q4 [CASE]**  
Evaluate and classify:  
$$  
\lim_{x\to 3}\frac{(x-3)\lvert x-3\rvert}{x-3}  
$$  
Does the two-sided limit exist? If not, state why.  
Ans: ______
yes the limit does exit because left handed limit equal to right handed  limit at  x =  0 
**Q5 [CON]**  
Decide whether the limit exists:  
$$  
\lim_{x\to 0}\sin!\left(\frac{1}{x}\right)  
$$
If not, give the specific reason.  
Ans: the limit does not exit, because the value of sin is represented in the unit circle and fluturated around -1 and 1. For any small changes in the value 0.0001 or 0.00002 can cause the output of the sin function to be completely different. As a result, the limit in the left and right could not fall into one singular value therefore the limit at $x\xrightarrow{\text{}}0$ does not exit  ______

HOLD SOLUTIONS. Say “reveal” for keys or “continue” for Block 2.

---

**Tag Set legend**  
DEF, CON, PROC, DATA, ARG, CASE, APP

# Definitions

limit $\lim_{x\to a}f(x)$: the value $f(x)$ approaches as $x$ gets arbitrarily close to $a$.  
one-sided limit: approach from left $x\to a^-$ or right $x\to a^+$.  
removable discontinuity: limit exists at $a$ but $f(a)$ is missing/different.  
jump discontinuity: left and right limits exist but are unequal.  
oscillation DNE: no single value due to endless back-and-forth near $a$. 

Score: 4/5.

Targeted hint [PROC]: For piecewise at a point, take side-limits by substituting into the correct branch formula, then compare. Do not estimate with near-numbers.

---

##  Keys + 1-line diagnostics

**Q1** Correct idea, notation off.  
Limit and type:  
$$  
\lim_{x\to2}\frac{x^2-4}{x-2}  
=\lim_{x\to2}\frac{(x-2)(x+2)}{x-2}  
=\lim_{x\to2}(x+2)=4  
$$  
Plain: Values approach 4; the hole at $x=2$ is removable.

**Q2** Incorrect.  
$$  
\lim_{x\to0^-}f(x)=\lim_{x\to0^-}(x+1)=1,\quad  
\lim_{x\to0^+}f(x)=\lim_{x\to0^+}(1-x)=1,\quad  
\lim_{x\to0}f(x)=1  
$$  
Plain: Both sides go to 1, so the two-sided limit is 1.

**Use this piecewise form when needed**  
$$  
f(x)=  
\left{\begin{array}{l}  
x+1,& x<0\  
1-x,& x\ge0  
\end{array}\right.  
$$

**Q3** Partially correct; $f(1)$ wrong.  
$$  
\lim_{x\to1^-}f(x)=3,\quad  
\lim_{x\to1^+}f(x)=5,\quad  
\lim_{x\to1}f(x)\text{ DNE},\quad  
f(1)=-1  
$$  
Plain: Left approaches 3, right 5, so no single limit; the filled dot gives $f(1)=-1$.

**Q4** Correct conclusion; tighten reasoning.  
$$  
\frac{(x-3)|x-3|}{x-3}=  
\begin{cases}  
x-3,& x>3\  
-(x-3),& x<3  
\end{cases}  
=|x-3|\quad (x\ne3)  
$$  
$$  
\lim_{x\to3}\frac{(x-3)|x-3|}{x-3}=0  
$$  
Plain: Both sides go to 0 at $x=3$; limit exists and equals 0.

**Q5** Correct.  
$$  
\lim_{x\to0}\sin!\left(\frac{1}{x}\right)\ \text{does not exist}  
$$  
Plain: Outputs oscillate between $-1$ and $1$ infinitely often near $0$.

---

### Error log → minimal fixes

- **Q2 side-limits**: For $x\to0^-$ use $x+1$; for $x\to0^+$ use $1-x$.
    
- **Q3 value vs limit**: $f(1)$ is the y-value of the filled dot, not the approach values.
    
- **Q1 notation**: Never write $f(x)=\lim_{x\to a}f(x)$; limits are numbers, not functions.
    

Say “continue” for Block 2 or “drill me on my mistakes.”

Definitions

- side-limit: Limit from one side, e.g., $x\to a^-$ or $x\to a^+$.
    
- removable discontinuity: Limit exists but the point is missing/different.
    
- jump discontinuity: Side-limits exist but are unequal.
    
- oscillatory DNE: Values keep changing without settling to one number.

[[]]
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

**V3 [CON]** Modify V1 so the right branch is $2-x$ for $x\ge0$.  
Labels: left/right limits at $0$.  
Check: Classify the discontinuity at $0$.

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


