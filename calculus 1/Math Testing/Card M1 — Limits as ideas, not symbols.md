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




# Block 2 — Concept Build (25–35 min)

Sections: Stewart 9e §2.2 (limits from tables/graphs), §2.3 (limit laws), §2.4 (precise definition, optional).

## Visual (quick sketches + labels)

Make fast pencil sketches. Add the exact labels.

1. **Corner at 0 (piecewise):**  
    $$  
    f(x)=  
    \left{\begin{array}{l}  
    x+1,& x<0\  
    1-x,& x\ge 0  
    \end{array}\right.  
    $$  
    Label: $x=0$, the left approach value, the right approach value, decision for $\lim_{x\to 0}f(x)$, and $f(0)$.  
    Check: equal one-sided limits?
    
2. **Removable “hole”:** Sketch $y=\dfrac{x^2-4}{x-2}$ with an open circle at $x=2$. Mark the hole and label the limiting value.  
    Check: what single $L$ do nearby $y$’s approach?
    
3. **Jump:** Sketch step $g(x)=\left{\begin{array}{l}2,&x<1\5,&x\ge 1\end{array}\right.$. Put an open circle and a filled dot at $x=1$ correctly.  
    Label: $\lim_{x\to1^-}g(x)$, $\lim_{x\to1^+}g(x)$, “DNE two-sided.”
    
4. **Rational cancel:** Sketch $h(x)=\dfrac{(x-3)(x+1)}{x-3}$ with hole at $x=3$; label the line $y=x+1$ and $h(3)$ undefined.  
    Check: $\lim_{x\to3}h(x)=?$ from the line.
    
5. **Oscillation (contrast only):** Tiny-window sketch of $y=\sin(1/x)$ near $x=0$. Shade the band $[-1,1]$.  
    Label: “oscillatory DNE.”
    

## Audio (60–90 s script to read)

“Limits capture approach, not plug-in. From §2.2, I check left and right values near $a$. If they match, the two-sided limit exists. Removable means the limit exists but the point is missing or different; a jump means the side limits are different. In §2.3, I simplify algebraically using factoring and cancellation **without** substituting at the hole. For example, $\dfrac{x^2-4}{x-2}$ becomes $x+2$ for $x\ne2$, so the limit at $2$ is $4$. If a graph shows different left/right plateaus, like $2$ and $5$, then $\lim_{x\to a}f(x)$ does not exist. If needed, §2.4 gives the precise $\varepsilon$–$\delta$ form: values of $f(x)$ get within any $\varepsilon$ of $L$ once $x$ is within some $\delta$ of $a$.”

## Oral “teacher mode” (you speak; I probe)

Instructions: Answer aloud in ≤20 s per question. Type “next” for the next probe or answer inline; I will escalate.

Q1. In one sentence, what does $\lim_{x\to a}f(x)=L$ mean _without_ plugging in?  
Q2. For $f(x)=\dfrac{x^2-4}{x-2}$, why is it valid to use $x+2$ to find the limit at $x=2$?  
Q3. Give a concrete example where $\lim_{x\to a}f(x)$ exists but $f(a)$ is different. Name the discontinuity.  
Q4. How do you decide DNE at a corner vs a jump? What evidence do you need?  
Q5. State the $\varepsilon$–$\delta$ definition informally, then give $\delta$ in terms of $\varepsilon$ for the function $f(x)=2x$ at $a=3$ as far as you can.  
Q6. What mistake did you make in Q2 earlier, and what’s your new rule?

## Kinesthetic (hands-on at desk)

1. **Card-sort:** On slips, write seven labels: “left limit,” “right limit,” “two-sided limit,” “removable,” “jump,” “oscillatory DNE,” “infinite DNE.” Under each, place one example (formula or sketch).
    
2. **Table-to-limit drill (TI-84):** Use `TABLE SET` to sample $x$ around $a$ with $\Delta x=0.1$, then $0.01$. For $y_1=(x^2-4)/(x-2)$ near $2$ and $y_2=(x-3)|x-3|/(x-3)$ near $3$, record approach values and decide the limit.
    
3. **Explain to a rubber duck:** Read your 60–90 s script to any object; if you stumble, rewrite the sentence.
    

## Plain-language anchors

- “A limit is the value nearby $x=a$, not necessarily at $a$.”
    
- “Equal side limits ⇒ two-sided limit exists; unequal ⇒ DNE.”
    
- “Factor, cancel, then take the limit; never divide by zero.”
    

Say **continue** for Block 3 — Worked Examples, or **reveal-probe** to have me start questioning you from Q1 now.

**Definitions**

- two-sided limit: exists when $\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)=L$.
    
- removable discontinuity: limit exists at $a$ but $f(a)$ is missing/different.
    
- jump discontinuity: side limits exist and are unequal.
    
- oscillatory DNE: outputs swing among values infinitely often near $a$.