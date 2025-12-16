### Block 2 — Concept Build (Oral Review Only)

Use these as **60–90 second speaking prompts**. Answer out loud first; then either (a) type a short summary of what you said, or (b) roughly transcribe yourself.

After you answer a few, you can say:  
`Card 1 – rate my oral answer (Concept Q1–Q3)` (or whichever you did).

(Primary source: **Spivak, 4e, “Integrals”** definitions + Theorem 2 criterion + Appendix “Riemann Sums.”)

---

## Oral Concept Prompts

**Q1 [DEF, CON]**  
Explain what a **partition** of ([a,b]) is. Then explain what a **refinement** is (informally: “adding more cut points”).  
Plain-language: A partition is a “cut list” that breaks ([a,b]) into smaller intervals; a refinement makes the cuts finer.

[[answer]]

---

**Q2 [DEF, PROC]**  
Define (m_i) and (M_i) on each subinterval ([t_{i-1},t_i]), then define the **lower sum** (L(f,P)) and **upper sum** (U(f,P)).

[  
m_i=\inf{f(x):t_{i-1}\le x\le t_i},\quad M_i=\sup{f(x):t_{i-1}\le x\le t_i}.  
]  
Plain-language: (m_i) is the lowest value of (f) on the slice; (M_i) is the highest.

[  
L(f,P)=\sum_{i=1}^n m_i(t_i-t_{i-1}),\quad U(f,P)=\sum_{i=1}^n M_i(t_i-t_{i-1}).  
]  
Plain-language: Add “min-height rectangles” for (L), “max-height rectangles” for (U).

[[answer]]

---

**Q3 [CON, ARG]**  
Explain why **refining a partition pushes** (L(f,P)) **up** and (U(f,P)) **down** (or at least doesn’t move them the wrong way).  
Plain-language: When you split an interval into smaller ones, the “best inside-rectangles” can only improve, and the “smallest cover-rectangles” can only tighten.

[[answer]]

---

**Q4 [DEF, CON]**  
State the “sup/inf” definition of **integrable on ([a,b])** using “all lower sums” and “all upper sums.”

[  
f\text{ integrable}\iff \sup_P L(f,P)=\inf_P U(f,P).  
]  
Plain-language: There is exactly **one number** that all lower sums stay below and all upper sums stay above—so the estimates squeeze to a single value.

[[answer]]

---

**Q5 [DEF, CON]**  
State **Theorem 2 (ε-criterion)** for integrability and restate it in one plain sentence.

[  
f\text{ integrable on }[a,b]\iff \forall\varepsilon>0\ \exists P:\ U(f,P)-L(f,P)<\varepsilon.  
]  
Plain-language: You can make the “upper-minus-lower gap” as small as you want by choosing a fine enough partition.

[[answer]]

---

**Q6 [CASE, ARG]**  
Spivak’s “single spike” function: (f(x)=0) for (x\ne 1), (f(1)=1) on ([0,2]). Explain why it is integrable by describing how to pick a partition so that (U-L<\varepsilon).  
Plain-language: Put the spike in a **tiny** subinterval so the overestimate area becomes tiny.

[[answer]]

---

**Q7 [CASE, CON]**  
Explain why the function “(1) on rationals, (0) on irrationals” is **not** integrable (what do (m_i) and (M_i) become on every subinterval, and what happens to (U-L)?).  
Plain-language: Every interval contains both types, so the lower estimate is always “all zeros” while the upper estimate is always “all ones.”

[[answer]]

---

**Q8 [CON, APP]**  
Connect **Riemann sums** to (L(f,P)) and (U(f,P)): explain why _any_ Riemann sum for a fixed partition lies between them, and what that means conceptually.

[  
L(f,P)\le \sum_{i=1}^n f(x_i)(t_i-t_{i-1})\le U(f,P).  
]  
Plain-language: Picking sample points gives a “middle estimate” trapped between the best under- and over-estimates.

[[answer]]

---

**Q9 [PROC, APP]**  
Your supplemental: (f(x)=\sin x) on ([0,5\pi/6]) with (P={0,\pi/4,3\pi/4,5\pi/6}). Explain (no calculations) how you find each (m_i) and (M_i) on each subinterval—what you check and why.  
Plain-language: On each slice, you decide whether (\sin x) is increasing/decreasing and whether an interior peak occurs, then pick the smallest/largest value accordingly.

[[answer]]

---

How to use now:

1. Pick **2–3 prompts** (e.g., Q2, Q5, Q9).
    
2. Speak **60–90 seconds** each.
    
3. Paste a rough transcript.
    
4. Ask: `Card 1 – rate my oral answer (Concept Q2–Q5)`.
    

---

### Definitions

- partition: A finite set (P={t_0,\dots,t_n}) with (a=t_0<\cdots<t_n=b).
    
- refinement: A new partition that contains all points of the old partition (and possibly more).
    
- lower sum (L(f,P)): Sum of “infimum height × width” over the partition’s subintervals.
    
- upper sum (U(f,P)): Sum of “supremum height × width” over the partition’s subintervals.
    
- integrable: The condition (\sup_P L(f,P)=\inf_P U(f,P)), equivalently the ε-gap criterion.