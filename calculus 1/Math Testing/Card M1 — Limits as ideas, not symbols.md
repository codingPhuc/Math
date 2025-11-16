---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/CalcI/CalcI.aspx
tags:
  - In_Progress
learning method: RAP (Read – Answer – Practice)
Current date: 2025-08-24
amount of time:
learning score:
completed: true
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

[[Block 2 — Concept Build (25–40 min)]]