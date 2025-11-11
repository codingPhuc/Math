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
Ans: the limit does not exit, beca ______

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