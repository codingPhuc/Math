Session objective: Master limits from tables, graphs, and algebra; decide when limits exist (one-sided vs DNE); prep a 3-min teach-back and pass a 5-item mastery check ≥80%.

3-hour timeline mapped to your Pomodoro rule (30-7, long 15 after 4):

- Cycle 1 (30+7): Block 0 → Block 1.
    
- Cycle 2 (30+7): Block 2 start.
    
- Cycle 3 (30+7): Block 2 finish → Block 3 start.
    
- Cycle 4 (30+15): Block 3 finish.
    
- Final 24 min: Block 4 warm-up. Later blocks on “continue.”
    

Citations: Stewart Calculus, 9e — §2.2 The Limit of a Function; §2.3 Calculating Limits Using the Limit Laws; §2.4 The Precise Definition of a Limit (optional). Drills: book-only.

# Block 0 — Setup (5 min)

Materials checklist

- Stewart 9e §2.2–§2.4 (physical/PDF).
    
- Blank paper or notebook + pencil.
    
- TI-84 (checks only; no CAS/Desmos/Wolfram).
    
- Timer set to 30-7 Pomodoro; long break 15 after cycle 4.
    

Workspace prep

- Phone on Do Not Disturb. One tab: textbook. One stack of paper labeled “Rules I Forgot.”
    

Today’s Objective

- Explain and classify limits from tables, graphs, and simple algebra. Decide existence via one-sided agreement.
    

# Block 1 — Diagnostic (5–10 min)

Instructions

- 5 items. 1 minute each. No calculator for answers. TI-84 allowed after to sanity-check numerics. Write a one-line reason per answer.
    
- Scoring and routing:  
    0–2 correct → Emphasize Block 2 Visual + definitions.  
    3–4 correct → Balance Block 2 and Block 3.  
    5 correct → Shorten Block 2; go heavier on Block 3 and Block 4.
    

DIAGNOSTIC — cold start (Stewart §2.2–§2.3)

- Q1 [DATA, CON]: Table: (x={1.9,,1.99,,2.01,,2.1}). Values (f(x)={3.9,,3.99,,4.01,,4.1}). Decide (\lim_{x\to2} f(x)) and whether (f(2)) must equal that value. Ans: ____
    
- Q2 [CASE, CON]: Graph cue: At (x=1), left-hand trace tends to (2), right-hand trace tends to (5); a filled dot sits at ((1,7)). Classify: limit exists? continuity? Give the type of discontinuity if any. Ans: ____
    
- Q3 [PROC]: Compute (\displaystyle \lim_{x\to3}\frac{x^2-9}{x-3}). Show the algebraic step that justifies your answer. Ans: ____
    
- Q4 [CASE, DEF]: Piecewise (g(x)=\begin{cases} |x-4|/(x-4), & x\neq4\ 0, & x=4\end{cases}). Decide (\lim_{x\to4^-}g(x)), (\lim_{x\to4^+}g(x)), and (\lim_{x\to4}g(x)). Brief reason. Ans: ____
    
- Q5 [PROC, CON]: Using limit laws only, evaluate (\displaystyle \lim_{x\to0}\left(3x^2+4x+5\right)). State which law justifies moving the limit inside. Ans: ____
    

-- HOLD SOLUTIONS --  
Say “reveal” to see concise solutions with one-sentence reasoning.

Tag Set legend  
DEF = definition; CON = conceptual distinction; PROC = procedure/algorithm; DATA = table/graph; ARG = argument/evidence; CASE = case/classification; APP = application

Say “continue” when you’re ready for Block 2.

Definitions

- limit: The value a function’s outputs approach as the input approaches a point.
    
- one-sided limit: A limit taken from only the left or only the right.
    
- continuity at a point: (f(a)) defined, (\lim_{x\to a}f(x)) exists, and equals (f(a)).
    
- removable discontinuity: Two one-sided limits agree but differ from (f(a)) or (f(a)) undefined.
    
- jump discontinuity: Two one-sided limits exist and are unequal.
    
- indeterminate form: An algebraic form like (0/0) that requires simplification before taking a limit. 

- Q1 [DATAf, CON]: Table: (x={1.9,,1.99,,2.01,,2.1}). Values (f(x)={3.9,,3.99,,4.01,,4.1}). Decide (\lim_{x\to2} f(x)) and whether (f(2)) must equal that value. Ans:  
I don't know what htis mean, is this the proof where one input value will be map to one ouput value thing then this question is correct 
- Q2 [CASE, CON]: Graph cue: At (x=1), left-hand trace tends to (2), right-hand trace tends to (5); a filled dot sits at ((1,7)). Classify: limit exists? continuity? Give the type of discontinuity if any. Ans:  
the limit does not exit since left hand limit does not equal to right hand limit 



- Q3 [PROC]: Compute  Show the algebraic step that justifies your answer. Ans:  

 $$
\begin{array}{l}  \\
\left( \displaystyle \lim_{x\to3}\frac{x^2-9}{x-3} \right).
= \frac{(3)^2   -  9}{3 -3}  =   \frac{0}{0} \implies \text{ undefind}  \\
\lim_{ x \to 3 }  \frac{(x  - 3)(x + 3)}{x - 3}  = \lim_{ x  \to 3 }  x + 3      = 3 + 3  =   6
\end{array}
 
$$

![[Pasted image 20251109223329.png]]  
Q4 :  
$$
\begin{array}
\lim_{  x  \to   4- }  \frac{\mid x -  4 \mid }{x - 4}    =   -1    \\
\lim_{   x  \to  4^+  }   \frac{\mid x -  4 \mid }{x - 4}      =  1  \\
\lim_{   x  \to 4 }    \frac{\mid x -  4 \mid }{x - 4}     = 0 \\
\end{array} 
$$
for $\lim_{ n \to 4^-1 }$ it appoarching from left to right so the closet number apporaching 4 is a number that is smaller than 4 for demostraction purposed l