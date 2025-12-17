
Excellent question. What you are asking for is exactly how people **learn to write rigorous mathematics**: by internalizing a _fixed structural template_ and a _self-audit checklist_.

Below are **two tools** you can reuse for _any_ Stewart/Spivak-style computation with substitutions.

---

# 1️⃣ Canonical **Format Template** (Definition-Driven, Not Numbered)

This is a **structural skeleton**.  
When grading, instructors subconsciously expect this order.

You do **not** need to write section headers in an exam, but you should _mentally_ follow them.

---

### **Problem Setup**

- State the quantity to be computed.
    
- Introduce notation if helpful.
    

> _Example:_  
> Let  
> $$[  
> I := \int_{2}^{3} \frac{dx}{(x^2-1)^{3/2}}.  
> ] $$

---

### **Define Substitution (with domain)**

- Explicitly define the substitution.
    
- State the domain of the new variable.
    
- Justify the domain choice (monotonicity / sign control).
    

> _Template:_  
>$$ Let (x = \sec\theta) with (\theta \in [0,\pi/2)).$$

---

### **Differentiate the Substitution**

- Compute (dx) explicitly.
    
- No skipping.
    

> _Template:_  
> $$Then (dx = \sec\theta\tan\theta,d\theta).$$

---

### **Transform the Integrand**

- Rewrite **every part** of the integrand in terms of the new variable.
    
- Use identities explicitly.
    
- Address absolute values / powers.
    

> _Template:_  
> Since (\sec^2\theta - 1 = \tan^2\theta), and (\theta \in [0,\pi/2)) implies (\tan\theta \ge 0), we have  
> $$[  
> (x^2-1)^{3/2} = (\tan^2\theta)^{3/2} = \tan^3\theta.  
> ]$$

---

### **Change the Bounds**

- Convert **each endpoint separately**.
    
- Preserve order (monotonicity).
    

> _Template:_  
$$> When (x=2), (\sec\theta=2), so (\theta=\arccos(1/2)=\pi/3).  
> When (x=3), (\sec\theta=3), so (\theta=\arccos(1/3)).$$

---

### **Rewrite the Integral**

- Write the transformed definite integral cleanly.
    
- Simplify step-by-step (not all at once).
    

> _Template:_  
> Therefore,  
$$> [  
> I  
> = \int_{\pi/3}^{\arccos(1/3)}  
> \frac{\sec\theta\tan\theta}{\tan^3\theta},d\theta  
> = \int_{\pi/3}^{\arccos(1/3)} \csc\theta\cot\theta,d\theta.  
> ]$$

---

### **Integrate**

- Use a known derivative/integral.
    
- No “obvious” or “clearly”.
    

> _Template:_  
$$> Since (\frac{d}{d\theta}(\csc\theta) = -\csc\theta\cot\theta),  
> [  
> I = \big[-\csc\theta\big]_{\pi/3}^{\arccos(1/3)}.  
> ]$$

---

### **Evaluate Endpoints**

- Compute trig values carefully.
    
- Use identities or right-triangle reasoning.
    
- Keep signs consistent.
    

> _Template:_  
>$$ [  
> \csc(\pi/3)=\frac{2}{\sqrt3}, \qquad  
> \cos\theta=\frac13 \Rightarrow  
> \sin\theta=\frac{2\sqrt2}{3} \Rightarrow  
> \csc(\arccos(1/3))=\frac{3}{2\sqrt2}.  
> ]
$$
---

### **Final Answer**

- Simplify.
    
- Box the result.
    

> _Template:_  
>$$ [  
> \boxed{I=\frac{2}{\sqrt3}-\frac{3}{2\sqrt2}}.  
> ]$$

---

# 2️⃣ **Rigor Self-Audit Checklist** (Use This Before Submitting)

Print this mentally before turning in work.

---

## ✅ Definitions & Domains

- ☐ Did I **define every new variable**?
    
- ☐ Did I state the **domain** of substitution variables?
    
- ☐ Did I justify sign choices (e.g. (\tan\theta \ge 0))?
    

---

## ✅ Algebra & Identities

- ☐ Did I justify identities used (e.g. (\sec^2-1=\tan^2))?
    
- ☐ Did I handle powers like ((u^2)^{3/2}) correctly?
    
- ☐ Did I avoid illegal cancellations?
    

---

## ✅ Definite Integral Mechanics

- ☐ Did I **change bounds**, not revert to (x)?
    
- ☐ Did I preserve bound order?
    
- ☐ Did I justify monotonicity if needed?
    

---

## ✅ Calculus Steps

- ☐ Did I justify every antiderivative used?
    
- ☐ Did I avoid skipping differentiation/integration steps?
    
- ☐ Did I check that the integrand stayed continuous on the interval?
    

---

## ✅ Trigonometric Evaluation

- ☐ Did I compute (\sin,\cos,\csc) consistently?
    
- ☐ Did I use right-triangle logic where appropriate?
    
- ☐ Did I avoid mixing (\sin) with (\csc)?
    

---

## ✅ Presentation (Spivak / Enderton Standard)

- ☐ One logical step per line
    
- ☐ No “clearly”, “obvious”, or handwaving
    
- ☐ Every implication is justified
    
- ☐ Final answer boxed and simplified
    

---

### Bottom line

If you:

- follow the **format** above, and
    
- check your work against the **checklist**,
    

your solutions will read as **fully rigorous** by Stewart standards and _respectable_ even under Spivak/Enderton scrutiny.

If you want, next time you solve a problem, you can say

> “Audit this using the checklist”  
> and I’ll mark it exactly like a strict grader.





I will treat this as **Assignment type = computation** and the **problem** as:  
[  
\int_{2}^{3}\frac{dx}{(x^{2}-1)^{3/2}}.  
]

Also: you required **page-level citations** from the three PDFs. I cannot currently extract page numbers from your PDFs in this chat session, so every nontrivial fact below is flagged with **“Citation needed”** and I tell you exactly what to search inside the PDFs to supply the missing citations.

---

## A) Verdict

**Correctness = FAIL** (final value is incorrect; bounds/sign handling and trig-value evaluation errors).  
**Rigor = FAIL**, **Rigor Score = 42/100** (fatal gaps + no citation discipline).

---

## B) Line-by-line audit (your steps, reconstructed from the image)

### (1) (\displaystyle \int_{2}^{3}\frac{dx}{(x^{2}-1)^{3/2}})

- **Status:** OK.
    

### (2) “(x=\sec\theta), (dx=\sec\theta\tan\theta,d\theta)”

- **Status:** OK but **Unjustified**.
    
- **Issue type:** Missing hypothesis / missing definition.
    
- **Fix:** State a domain to make (\theta) well-defined and signs consistent, e.g. (\theta\in[0,\pi/2)) since (x\in[2,3]\subset[1,\infty)).
    
- **Citation needed:** Stewart §7.2 “Trigonometric substitution,” specifically the case (x^2-a^2) with (x=a\sec\theta); also derivative (\frac{d}{d\theta}(\sec\theta)=\sec\theta\tan\theta).  
    **Search in PDF:** `7.2`, `Trigonometric Substitution`, `x = sec`, `d/dx sec`, `sec x tan x`.
    

### (3) “Bounds: ([2,3]) and (x=\sec\theta\Rightarrow [\pi/3,\arccos(1/3)])”

- **Status:** Partly OK but **Unjustified** and then used incorrectly.
    
- **Issue type:** Missing hypothesis; case split missing.
    
- **Fix:** You must justify monotonicity: on ([0,\pi/2)), (\sec\theta) is increasing, so bounds preserve order:  
    [  
    x=2\Rightarrow \theta=\arcsec(2)=\arccos(1/2)=\pi/3,\quad  
    x=3\Rightarrow \theta=\arcsec(3)=\arccos(1/3).  
    ]  
    And since (2<3), the (\theta)-bounds must be (\pi/3) to (\arccos(1/3)) (not reversed).
    
- **Citation needed:** Stewart (or Spivak) on change of variables for definite integrals + Stewart trig-sub section showing how to convert bounds.  
    **Search:** `change of variables`, `definite integral substitution`, `arcsec`, `bounds`, `sec is increasing`.
    

### (4) You write the substituted definite integral with bounds **(\arccos(1/3)) to (\pi/3)** (reversed).

- **Status:** **Invalid** (sign error).
    
- **Issue type:** Illicit inference (bound order).
    
- **Fix:** Correct to  
    [  
    \int_{\pi/3}^{\arccos(1/3)} \frac{\sec\theta\tan\theta}{(\sec^2\theta-1)^{3/2}},d\theta.  
    ]
    
- **Citation needed:** same as (3).
    

### (5) Replace (\sec^2\theta-1) by (\tan^2\theta), hence ((\sec^2\theta-1)^{3/2}=(\tan^2\theta)^{3/2}=\tan^3\theta)

- **Status:** Algebra/trig idea is right but **Unjustified**.
    
- **Issue type:** Missing hypothesis.
    
- **Fix:** Explicitly note (\theta\in[0,\pi/2)\Rightarrow \tan\theta\ge 0), so ((\tan^2\theta)^{3/2}=|\tan\theta|^3=\tan^3\theta).
    
- **Citation needed:** Stewart trig identities ( \sec^2\theta=1+\tan^2\theta) and sign handling in trig-sub procedure.  
    **Search:** `sec^2 = 1 + tan^2`, `Pythagorean identities`, `tan theta >= 0`, `absolute value`.
    

### (6) Simplify to (\displaystyle \int \frac{\sec\theta}{\tan^2\theta},d\theta = \int \frac{\cos\theta}{\sin^2\theta},d\theta = \int \csc\theta\cot\theta,d\theta)

- **Status:** OK (once (4) and (5) are fixed).
    

### (7) (\displaystyle \int \csc\theta\cot\theta,d\theta = -\csc\theta + C)

- **Status:** OK but **Unjustified**.
    
- **Issue type:** Missing theorem/reference.
    
- **Fix:** Cite the standard trig integral (or derive from ((\csc\theta)'=-\csc\theta\cot\theta)).
    
- **Citation needed:** Stewart table of derivatives/integrals for (\csc) and (\cot) or derivative of (\csc\theta).  
    **Search:** `derivative of csc`, `integral of csc cot`, `table of integrals`.
    

### (8) Evaluation step: you write something equivalent to (-\csc(\pi/3)+\csc(\arccos(1/3)))

- **Status:** **Invalid** as written, because it follows from the **reversed bounds** in (4).
    
- **Issue type:** Illicit inference (propagated from bound error).
    
- **Fix:** With correct bounds (\pi/3 \to \arccos(1/3)),  
    [  
    \Big[-\csc\theta\Big]_{\pi/3}^{\arccos(1/3)}=-\csc(\arccos(1/3))+\csc(\pi/3).  
    ]
    

### (9) Trig evaluation at the endpoints

- **Status:** **Invalid / inconsistent.**
    
- **What’s wrong:**
    
    - (\csc(\pi/3)) is **not** (\sqrt3/2). Since (\sin(\pi/3)=\sqrt3/2), we have (\csc(\pi/3)=2/\sqrt3).
        
    - You computed (\sin\theta=2\sqrt2/3) from (\cos\theta=1/3) correctly, but then your final line uses (2\sqrt2/3) where **(\csc\theta)** should be (3/(2\sqrt2)).
        
- **Fix:** Use  
    [  
    \csc(\pi/3)=\frac{2}{\sqrt3},\qquad  
    \cos\theta=\frac13\Rightarrow \sin\theta=\frac{2\sqrt2}{3}\Rightarrow \csc\theta=\frac{3}{2\sqrt2}.  
    ]
    
- **Citation needed:** Stewart trig values / right-triangle method; identity (\sin^2+\cos^2=1).  
    **Search:** `special angles`, `sin(pi/3)`, `sin^2 + cos^2 = 1`.
    

### (10) Final answer (\displaystyle -\frac{\sqrt3}{2}+\frac{2\sqrt2}{3})

- **Status:** **Invalid** (does not match the correct evaluation).
    
- **Correct value:**  
    [  
    \boxed{\int_{2}^{3}\frac{dx}{(x^{2}-1)^{3/2}}=\frac{2}{\sqrt3}-\frac{3}{2\sqrt2}}.  
    ]
    

---

## C) Missing dependencies (exact statements needed + what to search)

To meet your own “Enderton/Spivak-level” citation rule, you need page citations for:

1. **Trig substitution case** (x=a\sec\theta) for (\sqrt{x^2-a^2}) and related sign conventions.  
    **Search Stewart:** `7.2 Trigonometric Substitution`, `x = a sec θ`.
    
2. **Change of variables in definite integrals** (how bounds transform).  
    **Search Stewart:** `Substitution Rule`, `definite integral substitution`, `change of variables`.  
    **Search Spivak:** `substitution`, `change of variables`, `definite integrals`.
    
3. **Trig identity** (\sec^2\theta-1=\tan^2\theta) and **sign**: ((\tan^2)^{3/2}=|\tan|^3).  
    **Search Stewart:** `Pythagorean identities`, `sec^2`.
    
4. **Derivative/integral**: (\frac{d}{d\theta}(\csc\theta)=-\csc\theta\cot\theta) (equivalently (\int \csc\theta\cot\theta,d\theta=-\csc\theta+C)).  
    **Search Stewart:** `derivative of csc`, `integral of csc cot`.
    
5. (Optional Enderton-style) a brief standard about **stating hypotheses/definitions before use**.  
    **Search Enderton:** `proof`, `definitions`, `rules of inference`, `justification`.
    

If you paste the relevant pages (screenshots are fine), I will replace every “Citation needed” with exact page numbers.

---

## D) Scores

### Rigor rubric breakdown (100)

- **Logic & justification completeness (40): 14/40**  
    Bound order error; endpoint trig evaluation inconsistent; multiple unstated sign/domain justifications.
    
- **Definitions & hypotheses stated (20): 8/20**  
    No stated (\theta)-domain; no monotonicity/sign conditions.
    
- **Citation discipline (20): 0/20**  
    No page-level citations provided (and I cannot extract them without your excerpts).
    
- **Notation & structure (20): 20/20**  
    Overall flow is recognizable and mostly well-organized.
    

**Total: 42/100.**

### Correctness /10

**3/10** (method is appropriate, but execution has fatal sign and evaluation errors).

---

## E) Minimal Fix List (smallest edits to reach RIGOR-PASS)

1. State: “Let (x=\sec\theta) with (\theta\in[0,\pi/2)).”
    
2. Correct bounds: (x=2\Rightarrow\theta=\pi/3), (x=3\Rightarrow\theta=\arccos(1/3)), and write the integral with **lower (\pi/3)** and **upper (\arccos(1/3))**.
    
3. Insert one line: “Since (\theta\in[0,\pi/2)), (\tan\theta\ge0), so ((\tan^2\theta)^{3/2}=\tan^3\theta).”
    
4. Fix endpoint evaluations:
    
    - (\csc(\pi/3)=2/\sqrt3).
        
    - (\csc(\arccos(1/3))=3/(2\sqrt2)).
        
5. Add the required citations to Stewart/Spivak for trig-sub + substitution for definite integrals + trig derivative/integral facts.
    

---

## F) Rewritten Solution (LaTeX, terse formal)
$$
[  
I:=\int_{2}^{3}\frac{dx}{(x^{2}-1)^{3/2}}.  
]  
Let (x=\sec\theta) with (\theta\in[0,\pi/2)). Then (dx=\sec\theta\tan\theta,d\theta) and  
[  
x^{2}-1=\sec^{2}\theta-1=\tan^{2}\theta.  
]  
Since (\theta\in[0,\pi/2)), we have (\tan\theta\ge0), hence ((x^{2}-1)^{3/2}=(\tan^{2}\theta)^{3/2}=\tan^{3}\theta). Also,  
[  
x=2 \Rightarrow \sec\theta=2 \Rightarrow \theta=\arccos(1/2)=\pi/3,\qquad  
x=3 \Rightarrow \sec\theta=3 \Rightarrow \theta=\arccos(1/3).  
]  
Therefore,  
[  
I=\int_{\pi/3}^{\arccos(1/3)}\frac{\sec\theta\tan\theta}{\tan^{3}\theta},d\theta  
=\int_{\pi/3}^{\arccos(1/3)}\frac{\sec\theta}{\tan^{2}\theta},d\theta  
=\int_{\pi/3}^{\arccos(1/3)}\frac{\cos\theta}{\sin^{2}\theta},d\theta  
=\int_{\pi/3}^{\arccos(1/3)}\csc\theta\cot\theta,d\theta.  
]  
Since (\frac{d}{d\theta}(\csc\theta)=-\csc\theta\cot\theta),  
[  
I=\Big[-\csc\theta\Big]_{\pi/3}^{\arccos(1/3)}  
=-\csc(\arccos(1/3))+\csc(\pi/3).  
]  
Now (\sin(\pi/3)=\sqrt3/2), so (\csc(\pi/3)=2/\sqrt3). If (\cos\theta=1/3) and (\theta\in[0,\pi/2)), then  
[  
\sin\theta=\sqrt{1-\cos^{2}\theta}=\sqrt{1-\frac19}=\frac{2\sqrt2}{3},  
\quad\text{so}\quad  
\csc(\arccos(1/3))=\frac{3}{2\sqrt2}.  
]  
Hence  
[  
\boxed{I=\frac{2}{\sqrt3}-\frac{3}{2\sqrt2}}.  
]
$$
---

If you paste (or screenshot) the **Stewart pages** covering §7.2 trig substitution and the derivative/integral of (\csc), I will replace each “Citation needed” with exact **Stewart p.__ / Spivak p.__ / Enderton p.__** and recompute the rigor score under your rubric.