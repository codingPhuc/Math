# Test content 
## A) Chapter Plan Cards

[Card M1 — Limits as ideas, not symbols](https://chatgpt.com/share/69117a80-a718-800e-9777-8e3ade8b62da)

- Book: _Stewart Calculus_, 9e — Ch. 1.2 (The Limit of a Function), 1.3 (Calculating Limits), 1.4 (Precise Definitions optional)
    
- Objective: Explain limits from tables, graphs, and simple algebra; contrast left/right/does-not-exist.
    
- Why this chapter: Foundation for intuitive tutoring and later derivative meaning.
    
- Prereqs: Functions, domain/range; piecewise behavior; absolute value.
    
- Key terms/theorems: (\lim_{x\to a}f(x)), one-sided limits, continuity at a point, indeterminate forms.
    
- Worked examples: Piecewise limit at a corner; removable vs jump discontinuity; rational limit with factor cancel.
    
- Exercises set: 1.2 #3–31 odd; 1.3 #5–35 odd; one piecewise from 1.2 even.
    
- Deliverable: 3-min teach-back audio: “When limits exist vs don’t.”
    
- Mastery check (10 min, ≥80%): 5 quick limits incl. one DNE with brief reason.
    
- Est. time: 3h.



# Review loops 

# Block 1 — Diagnostic (5–10 min)

Directions: 1 minute per item. TI-84 allowed for quick numeric checks only. Answer; no solutions yet.

**Q1 [DATA]**  
From the table for $$f(x)=\frac{x^2-4}{x-2}$$ near $$x=2$$:

|x|1.9|1.99|2.01|
|---|---|---|---|
|$$f(x)$$|3.9|3.99|4.01|

Find $$\lim_{x\to 2} f(x)$$ and classify the discontinuity at $$x=2$$ (removable/jump/none).  
In words: Read the approach value from nearby data and name the type.

**Q2 [PROC]**  
$$$$  
f(x)=\begin{cases}  
x+1,& x<0\  
1-x,& x\ge 0  
\end{cases}  
$$$$  
Find $$\lim_{x\to 0^-}f(x)$$, $$\lim_{x\to 0^+}f(x)$$, and $$\lim_{x\to 0}f(x)$$.  
In words: Compute left limit, right limit, then decide if a single limit exists.

**Q3 [CON]**  
A graph has an open circle at $$(1,3)$$ on a left branch approaching $$3$$ as $$x\to 1^-$$. The right branch approaches $$5$$ as $$x\to 1^+$$. There is a solid dot at $$(1,-1)$$. Give $$\lim_{x\to 1^-}f(x)$$, $$\lim_{x\to 1^+}f(x)$$, $$\lim_{x\to 1}f(x)$$, and $$f(1)$$.  
In words: Read left/right approach values and distinguish them from the actual function value.

**Q4 [CASE]**  
Evaluate and classify:  
$$$$  
\lim_{x\to 3}\frac{(x-3)\lvert x-3\rvert}{x-3}  
$$$$  
Does the two-sided limit exist? If not, state why.  
In words: Simplify on each side of $$x=3$$ and compare side limits.

**Q5 [CON]**  
Decide whether the limit exists:  
$$$$  
\lim_{x\to 0}\sin!\left(\frac{1}{x}\right)  
$$$$  
If not, give the specific reason.  
In words: Check for a single approach value vs endless oscillation.

— **HOLD SOLUTIONS** —

**Scoring and routing**  
0–2 correct → Emphasize Block 2 (Concept Build) and Block 3 (Worked Examples); consider Optional Block 7.  
3–4 correct → Proceed as planned; keep Worked Examples strong.  
5 correct → Shorten Block 2; allocate more time to Block 4 drills.

Tag Set legend: DEF, CON, PROC, DATA, ARG, CASE, APP

**Definitions**

- removable discontinuity: A hole; the limit at $$a$$ exists but $$f(a)$$ is missing or different.
    
- jump discontinuity: Left and right limits at $$a$$ both exist but are unequal.
    
- two-sided limit: The common value when $$\lim_{x\to a^-}f(x)=\lim_{x\to a^+}f(x)$$.
    
- oscillation DNE: No single value because outputs keep varying between values near $$a$$.