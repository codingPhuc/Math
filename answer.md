Hint (focus first):  
Rewrite your explanation using **“right curve minus left curve”** for $x=u(y)$ and $x=v(y)$, and explicitly say that for each fixed $y$, the curve with **larger $x$-value** is the right curve; avoid “on top”/“below” language here.

---

### Score: 6/10

I’m treating this as **Concept Q2 [PROC, CASE]** for Card 13.

---

### Feedback by category

**1) Setup & interpretation**

- Strength: You correctly recognized the situation “region bounded by two curves described as $x$-functions of $y$” and used the notation $x=u(y)$ and $x=v(y)$, matching the problem.
    
- Strength: You understood that the **order of subtraction changes** when the curves switch which one is “on top” / dominant, and you split the integral at the $y$-value where they cross (using $-2,1,2$ in your example).
    
- Weakness: The question asked “how you decide whether to integrate with respect to $x$ or $y$”; you didn’t really address this decision rule. You should explicitly say: _when the region is more naturally described as left/right curves $x=\dots(y)$, integrate with respect to $y$_.
    

**2) Integral formulation**

- Strength: You wrote integrals of the form  
    $\displaystyle \int_{-2}^{1} \big(v(y)-u(y)\big),dy ;+; \int_{1}^{2} \big(u(y)-v(y)\big),dy$,  
    which shows you know the integrand is a **difference of the two functions** and that the order depends on which curve is “larger” on that sub-interval.  
    Plain language: You’re adding up horizontal distances between the two curves over pieces where each one is dominant.
    
- Weakness: You never explicitly said “this is **right minus left** in terms of $x$-values for each fixed $y$,” and you didn’t connect your numeric bounds $-2,1,2$ clearly to the intersection points on your sketch.
    

**3) Execution & algebra**

- Neutral: No numeric computation was required here, so nothing to grade for algebra. Your example bounds are not justified but also not obviously inconsistent with the sketch.
    

**4) Sketch & notation**

- Strength: You drew a coordinate system, labeled $u(y)$ and $v(y)$, and clearly indicated two subregions (green and red) where the “dominant” curve changes.
    
- Weakness: For $x=u(y)$, $x=v(y)$, the comparison should be **horizontal**, but your explanation talks about one graph being “on top” of the other, which is a **vertical** idea. This confuses the geometry.
    
- Weakness: Using the symbol “$\land$” for “and” is nonstandard in this context and could be mistaken for logical conjunction in a different sense.
    

**5) Explanation & structure**

- Strength: You tried to walk through the example with words plus a picture, which is the right instinct for application questions.
    
- Weakness: The core question—“what does ‘right curve minus left curve’ mean?”—is only indirectly answered. You need one clean sentence like:  
    “For each fixed $y$, the curve with larger $x$-coordinate is the **right** curve; area is the integral of (right − left) horizontal distance, integrated with respect to $y$.”
    
- Weakness: Grammar and wording (“fluctuated between each other,” “order at between 2 bound”) make the logic hard to follow; tightening the language would help a lot.
    

---

### Concrete action steps

1. **Rewrite your answer in one paragraph** using the phrase “for each fixed $y$” and “right curve minus left curve,” and explicitly mention: _this is why we integrate with respect to $y$ for $x=u(y)$, $x=v(y)$ problems_.
    
2. **Add one clean general formula** to your notes:  
    $$A = \int_{y=c}^{y=d}\big(x_{\text{right}}(y)-x_{\text{left}}(y)\big),dy,$$  
    with a one-line explanation: “horizontal slices, right minus left, integrated in $y$.”
    
3. **Do 2 examples from Stewart 6.1 / 6.2** where the region is bounded by curves given as $x$-functions of $y$ (or is clearly easier in $dy$), and for each, explicitly write a sentence: “I choose to integrate with respect to $y$ because…”.
    
4. Next time you answer this kind of question, avoid “on top”/“below” for $x=u(y)$, $x=v(y)$; always talk about “to the right” and “to the left.”
    

Review this concept again on **2025-12-08** with at least one new “right-minus-left, integrate in $y$” area problem.

---

**Definitions**

- area between curves (in $y$):  
    For curves $x = u(y)$ and $x = v(y)$ on $y \in [c,d]$,  
    $$A = \int_c^d \big(x_{\text{right}}(y) - x_{\text{left}}(y)\big),dy.$$  
    In words: add up horizontal distances between right and left curves over the $y$-interval.
    
- integrate with respect to $y$:  
    Treat $y$ as the variable that changes; slices are horizontal, and the integrand measures a horizontal length or expression involving $y$.
    
- right-minus-left rule:  
    When using $dy$, the “right curve” is the one with larger $x$ for each $y$; the integrand is $x_{\text{right}}(y) - x_{\text{left}}(y)$ so the distance stays nonnegative.