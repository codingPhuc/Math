
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
> [  
> I := \int_{2}^{3} \frac{dx}{(x^2-1)^{3/2}}.  
> ]

---

### **Define Substitution (with domain)**

- Explicitly define the substitution.
    
- State the domain of the new variable.
    
- Justify the domain choice (monotonicity / sign control).
    

> _Template:_  
> Let (x = \sec\theta) with (\theta \in [0,\pi/2)).

---

### **Differentiate the Substitution**

- Compute (dx) explicitly.
    
- No skipping.
    

> _Template:_  
> Then (dx = \sec\theta\tan\theta,d\theta).

---

### **Transform the Integrand**

- Rewrite **every part** of the integrand in terms of the new variable.
    
- Use identities explicitly.
    
- Address absolute values / powers.
    

> _Template:_  
> Since (\sec^2\theta - 1 = \tan^2\theta), and (\theta \in [0,\pi/2)) implies (\tan\theta \ge 0), we have  
> [  
> (x^2-1)^{3/2} = (\tan^2\theta)^{3/2} = \tan^3\theta.  
> ]

---

### **Change the Bounds**

- Convert **each endpoint separately**.
    
- Preserve order (monotonicity).
    

> _Template:_  
> When (x=2), (\sec\theta=2), so (\theta=\arccos(1/2)=\pi/3).  
> When (x=3), (\sec\theta=3), so (\theta=\arccos(1/3)).

---

### **Rewrite the Integral**

- Write the transformed definite integral cleanly.
    
- Simplify step-by-step (not all at once).
    

> _Template:_  
> Therefore,  
> [  
> I  
> = \int_{\pi/3}^{\arccos(1/3)}  
> \frac{\sec\theta\tan\theta}{\tan^3\theta},d\theta  
> = \int_{\pi/3}^{\arccos(1/3)} \csc\theta\cot\theta,d\theta.  
> ]

---

### **Integrate**

- Use a known derivative/integral.
    
- No “obvious” or “clearly”.
    

> _Template:_  
> Since (\frac{d}{d\theta}(\csc\theta) = -\csc\theta\cot\theta),  
> [  
> I = \big[-\csc\theta\big]_{\pi/3}^{\arccos(1/3)}.  
> ]

---

### **Evaluate Endpoints**

- Compute trig values carefully.
    
- Use identities or right-triangle reasoning.
    
- Keep signs consistent.
    

> _Template:_  
> [  
> \csc(\pi/3)=\frac{2}{\sqrt3}, \qquad  
> \cos\theta=\frac13 \Rightarrow  
> \sin\theta=\frac{2\sqrt2}{3} \Rightarrow  
> \csc(\arccos(1/3))=\frac{3}{2\sqrt2}.  
> ]

---

### **Final Answer**

- Simplify.
    
- Box the result.
    

> _Template:_  
> [  
> \boxed{I=\frac{2}{\sqrt3}-\frac{3}{2\sqrt2}}.  
> ]

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