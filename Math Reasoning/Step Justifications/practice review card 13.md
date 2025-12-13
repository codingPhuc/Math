
Here are washer-method practice problems only.  
No solutions are below; ask me to “reveal Q#–Q#” when you want answers.

---

### Q1 [PROC, APP] – Between two curves, around the x-axis

Let $R$ be the region in the first quadrant bounded by  
$y = \sqrt{x}$ and $y = 1$ for $0 \le x \le 1$.

(a) Sketch the region $R$. Label the curves and the intersection points.  
(b) Rotate $R$ about the $x$-axis.

- Identify the **outer radius** $R(x)$ and **inner radius** $r(x)$ at a typical $x$.
    
- Set up the volume integral using the washer method.  
    (c) Evaluate the integral to find the exact volume.
    

---

### Q2 [PROC, CASE, APP] – “True hole” between two curves

Let $R$ be the region bounded by  
$y = x^2$ and $y = 4$ for $x$ between their intersection points.

(a) Find the $x$-values where $y = x^2$ and $y = 4$ intersect.  
(b) Sketch $R$ and shade it.  
(c) Rotate $R$ about the $x$-axis.

- Decide which function gives the outer radius and which gives the inner radius.
    
- Write the volume as a washer-method integral in $x$.  
    (d) Compute the exact volume.
    

---

### Q3 [PROC, CASE] – Between curve and line, around a shifted horizontal axis

Consider the region in the first quadrant bounded by  
$y = x$, $y = 3$, and the $y$-axis ($x=0$).

(a) Sketch the region. Mark intersection points clearly.  
(b) Rotate this region about the line $y = -1$.

- For a typical $x$ between the left and right bounds, express
    
    - the **outer radius** $R(x)$ (distance from axis $y=-1$ to the top curve),
        
    - the **inner radius** $r(x)$ (distance from axis $y=-1$ to the lower curve).  
        (c) Set up the washer-method integral for the volume, then evaluate it.
        

---

### Q4 [PROC, CASE, APP] – Vertical washers (integrate in $y$)

Let $R$ be the region bounded by the curves  
$x = y^2$ and $x = 4$ for $y$ between their intersection points.

(a) Sketch the region $R$ and label the curves.  
(b) Rotate $R$ about the $y$-axis.

- Take **horizontal** slices (so use washers, integrating with respect to $y$).
    
- Identify $x_{\text{right}}(y)$ and $x_{\text{left}}(y)$ and translate these into outer and inner radii as functions of $y$.  
    (c) Set up the volume integral in $y$ using the washer method and evaluate it.
    

---

### Q5 [PROC, CON] – Curve above axis, around a shifted line

The region $R$ is bounded by the curve  
$y = \ln x$ (natural log), the $x$-axis ($y=0$), and the vertical lines $x = 1$ and $x = e$.

(a) Sketch $R$ on $[1,e]$.  
(b) Rotate $R$ about the line $y = -2$.

- Write formulas for the outer radius $R(x)$ and inner radius $r(x)$ in terms of $x$.  
    (c) Set up the washer-method integral for the volume, then compute it exactly.
    

---

### Q6 [PROC, APP, ARG] – Decide disk vs washer, then solve

The region $R$ is bounded by the curves  
$y = 2x - x^2$ and the $x$-axis ($y=0$) where they intersect.

(a) Find the intersection points between $y = 2x - x^2$ and $y = 0$.  
(b) Sketch the region $R$ and shade it.  
(c) Consider rotating $R$ about

1. the $x$-axis, and
    
2. the line $y = -3$.  
    For each axis of rotation:
    

- Decide whether the cross-sections are disks or washers.
    
- If they are washers, identify $R(x)$ and $r(x)$.  
    (d) For the axis $y = -3$, set up and evaluate the washer-method integral.
    

---

How to use these

1. Pick 2–3 problems (e.g., Q1, Q2, Q4).
    
2. For each:
    
    - Draw a careful sketch.
        
    - Write $R(x)$ and $r(x)$ (or $R(y), r(y)$).
        
    - Set up the integral.
        
    - Then compute the volume.
        
3. When you want feedback, say something like:
    
    - “Card 13 – rate my answer (Washer Q1–Q2)” and paste your work for Q1–Q2.
        

---

**Definitions**

- washer method: Volume-of-revolution technique where each cross-section perpendicular to the axis is a ring with an outer radius $R$ and inner radius $r$; volume is  
    $$V = \int \pi\big(R^2 - r^2\big),d(\text{variable}).$$  
    Plain language: Add up ring volumes = big circle minus small circle at each slice.
    
- outer radius $R$: Distance from the axis of rotation to the **farther** curve for that slice.
    
- inner radius $r$: Distance from the axis of rotation to the **nearer** curve (or hole) for that slice.
    
- vertical vs horizontal slices:
    
    - Vertical slice → integrate in $x$: radius is a function of $x$.
        
    - Horizontal slice → integrate in $y$: radius is a function of $y$.