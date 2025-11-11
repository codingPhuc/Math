Here’s a clean Obsidian-ready Markdown of the two pages. Inline math uses `$…$`; display uses `$$…$$`. I kept each problem’s “Plain” line under its formula.

---

# Calculus I–II–III Core (Honors) — Ultra-Composite Final

**Coverage:** Stewart Calculus 9e, Ch. 2–11 (single/multilayer chains, nontrivial series, DE models)  
**Rules:** No calculators. Exact forms only. Every domain and theorem hypothesis must be stated.  
**Conventions:** All objects are maps $f:A\to\mathbb{R}$ or $f:A\to\mathbb{R}^2$ for a stated set $A$. When using IVT/MVT/FTC, state $A$ and continuity/differentiability. For parametric/polar, state the parameter interval. For power series, state radius and interval of convergence. For DEs, name type (separable/linear) and solve on appropriate domain.

---

## 2. Limits and Derivatives

### 1. (2.1–2.3, velocity via nontrivial limit)



$$
\begin{array}{l} \\
s(t)= \frac{(t^2+1)(t+3)^{1/3}e^{3t}  - 9(t+2)^{1/2}}{(t+3)^{1/3}(t+2)^{1/2}}  \\
\ln (s(t) )  = \ln ((t^2+1)(t+3)^{1/3}e^{3t}  - 9(t+2)^{1/2})  -  \frac{15}{2}\ln((t+3)(t+2))  \\
\end{array}
$$
A particle moves on a line with  
$$  
\begin{array}{l} \\
s(t)=\frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}-\frac{9}{(t+3)^{1/3}}  ,\qquad t>-2.     \\
u  = \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}   \\
v  =  \frac{9}{(t+3)^{1/3}}       \\ \\
\ln u  =  \ln\left( \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}} \right)    \\
\ln u  =  \ln((t^2+1)e^{3t})   -     \ln((t+2)^{1/2})   \\
 \ln u  =  \ln(t^2+1)   +  3t\ln(e)   -     \frac{1}{2}\ln(t+2)   \\
\frac{du}{dx }   \frac{1}{u }   =  \frac{2t}{t^2+ 1 } + 3   -  \frac{1}{2(t+ 2 )} \\ 
\frac{du}{dx }     =  \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}  \left[  \frac{2t}{t^2+ 1 } + 3   -  \frac{1}{2(t+ 2 )}  \right]   \\
\ln  v  =   \ln \left( \frac{9}{(t+3)^{1/3}}      \right)  \\
\ln v =   \ln  9   -  \ln((t+3)^{1/3})    \\
\ln v =   \ln  9   -  \frac{1}{3}\ln((t+3))     \\
\frac{dv}{dx}\frac{1}{v}   =     -  \frac{1}{3(t+3)}    \\
\frac{dv}{dx}    =   \frac{9}{(t+3)^{1/3}}  \left[  -  \frac{1}{3(t+3)}  \right]  \\
v(t )   =  u' - v'\\
v(t)  =   \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}  \left[  \frac{2t}{t^2+ 1 } + 3   -  \frac{1}{2(t+ 2 )}  \right]   -  \frac{9}{(t+3)^{1/3}}  \left[  -  \frac{1}{3(t+3)}  \right]  \\
\end{array}
$$  
(a) Compute $v(0)$ using only $v(0)=\displaystyle\lim_{h\to0}\frac{s(h)-s(0)}{h}$.  
_Plain:_ Use the difference-quotient limit at $t=0$.

$$
s(t +  h  )  =  \frac{((t +  h)^2 )e^{3(t+h) }}{ (t+h+2)^{1/2}}     -  \frac{9}{(t +h + 3)^{1/3}}  
$$



$$
\begin{array}{l} \\
v(t ) =  \lim_{ x  \to 0 }    \frac{\frac{((t +  h)^2 )e^{3(t+h) }}{ (t+h+2)^{1/2}}     -  \frac{9}{(t +h + 3)^{1/3}}  - \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}+\frac{9}{(t+3)^{1/3}}  }{h}   \\
v(t ) =  \lim_{ x  \to 0 }    \frac{\frac{((t +  h)^2 )e^{3(t+h) }}{ (t+h+2)^{1/2}}     -  \frac{9}{(t +h + 3)^{1/3}}  - \frac{(t^2+1)e^{3t}}{(t+2)^{1/2}}+\frac{9}{(t+3)^{1/3}}  }{h} 
\end{array}


$$


(b) Then find $v(t)$ and $a(t)$ in closed form.  
_Plain:_ Differentiate once for velocity, twice for acceleration, respecting the domain.


$$
\frac{1}{s(t) }v(t)  = \ln ((t^2+1)(t+3)^{1/3}e^{3t}  - 9(t+2)^{1/2})  -  \frac{15}{2}\ln((t+3)(t+2))
$$
(c) Determine all $t>-2$ such that $v(t)>0$ and $a(t)>0$.  
_Plain:_ Solve sign conditions of $v$ and $a$.


$$

$$




### 2. (2.2–2.3, high-order cancellation)

Evaluate  
$$  
\lim_{x\to0}\frac{\sin(9x)-9x+\dfrac{(9x)^3}{6}-\dfrac{(9x)^5}{120}}{x^6\ln(1+7x)}.  
$$  
_Plain:_ Use series (or repeated L’Hôpital) to match numerator and denominator orders.

### 3. (2.4, $\varepsilon$–$\delta$ with nonunit denominator)

Let $f(x)=\dfrac{5x-7}{2x+9}$. Prove from the $\varepsilon$–$\delta$ definition that  
$$  
\lim_{x\to2}f(x)=\frac{3}{13},  
$$  
and give an explicit $\delta(\varepsilon)$.  
_Plain:_ Solve $\big|f(x)-3/13\big|<\varepsilon$ for a bound $\lvert x-2\rvert<\delta(\varepsilon)$.

### 4. (2.5–2.6, stitched continuity + asymptote)

Define  
$$  
f(x)=  
\begin{cases}  
\dfrac{\sqrt{7x+8}-5}{x-3}, & x\ne3,[6pt]  
a, & x=3,  
\end{cases}  
\qquad  
g(x)=\dfrac{5x^4-7x^2+3\ln x}{2x^4+x^3}+\dfrac{4}{x},\quad x>0.  
$$  
(a) Choose $a$ so $f$ is continuous at $3$.  
_Plain:_ Compute $\lim_{x\to3}f(x)$ by rationalizing; set $a$ to that limit.

(b) Find all horizontal asymptotes of $g$ and prove the limits.  
_Plain:_ Compare dominant terms as $x\to\infty$ and the $4/x$ and $\ln x$ behavior as $x\to0^+$.

### 5. (2.7–2.8, derivative as a function with domain traps)

On $A=(0,\infty)\setminus{1}$ define  
$$  
y(x)=\frac{(x^2+4)e^{2x}}{(x-1)^{,3\sqrt{x}}}.  
$$  
Find $y'$, the locus of horizontal tangents, and the set where $y$ is increasing.  
_Plain:_ Log-differentiate; set $y'=0$ for horizontals; solve $y'>0$ for increase.

---

## 3. Differentiation Rules

### 6. (3.1–3.3, derivative gauntlet with hyperbolics)

Differentiate  
$$  
F(x)=\frac{(4x^2-x+5)^5\sin(3x)\cosh(2x)}{x^{5/3}(1+x^4)}.  
$$  
Present the result as $F(x)[\cdots]$.  
_Plain:_ Use product/quotient/chain; factor $F(x)$ and collect log-derivative terms.

### 7. (3.4, ultra-chain with variable exponent) on $(0,\infty)$

$$  
H(x)=\frac{\big[\ln(1+e^{x^2})\big]^{\arctan(\sqrt{x}+1/x)}}{x^{\sqrt{1+\sinh(\ln x)}}(1+x)^{x/(1+x)}}\cdot e^{,x^{2}/(1+x^{2})}.  
$$  
Find $H'(x)$ by logarithmic differentiation; express as $H(x)[\cdots]$.  
_Plain:_ Differentiate $\ln H$ term-by-term, then multiply by $H$.

### 8. (3.5, implicit with mixed transcendental)

On ${(x,y):x>0,\ y>0}$,  
$$  
x^{2}+2xy+y^{2}+\ln x+\ln y+\arctan!\Big(\frac{y}{x}\Big)=10.  
$$  
(a) Show $y$ is differentiable near $(1,2)$.  
_Plain:_ Check $\partial F/\partial y\ne0$ to apply the Implicit Function Theorem.

(b) Find $y'(x)$.  
_Plain:_ Differentiate implicitly and solve for $y'$.

(c) Compute $y'(1)$ and $y''(1)$.  
_Plain:_ Evaluate derivatives at $(1,2)$.

### 9. (3.6, log + inverse trig + power) on $(0,4)$

$$  
u(x)=\frac{\big(\ln(3x^{2}+1)\big)^{4}\arctan(5x)}{x^{5/2}(4-x)^{2/3}}.  
$$  
Find $u'(x)$ and factor as far as reasonable.  
_Plain:_ Use log-diff or quotient+product+chain; factor common terms.

### 10. (3.7–3.9, rates + exponential in context)

A trough of length $6$ m has isosceles triangular cross-section of height $4$ m and base $4$ m (vertex at bottom). Water inflow is $1.1,\text{m}^3/\text{min}$ and silt reduces effective volume at $0.2,\text{m}^3/\text{min}$. When the water depth is $2.5$ m, find $\dfrac{dh}{dt}$.  
_Plain:_ Use similar triangles for area vs depth; write $V(h)$; differentiate with net inflow.

### 11. (3.10, linearization with sharp MVT bound)

For $f(x)=(5x+4)^{5/3}$ at $x_0=1$, find $L(x)$ and the best bound on  
$$  
\big|f(1.02)-L(1.02)\big|  
$$  
that you can obtain from $f''$ on $[1,1.02]$.  
_Plain:_ Use linearization error $|f(x)-L(x)|\le \dfrac{M}{2}|x-1|^2$ with $M=\max_{[1,1.02]}|f''|$.

### 12. (3.11, hyperbolic composite)

Differentiate  
$$  
y(x)=\sinh(4x)\tanh(2x)-\operatorname{sech}x,  
$$  
and rewrite purely in $\tanh x$ and $\operatorname{sech}x$.  
_Plain:_ Use $(\sinh)'=\cosh$, $(\tanh)'=\operatorname{sech}^2$, $(\operatorname{sech})'=-\operatorname{sech}\tanh$ plus identities.

---

## 4. Applications of Differentiation

### 13. (4.1, absolute extrema with kinks) on $[0,4]$

$$  
f(x)=x^{2/3}(4-x)^{2/3}.  
$$  
Find all absolute extrema; justify each candidate (interior, endpoints, nondifferentiable).  
_Plain:_ Check interior criticals and corners; compare values.

### 14. (4.2, MVT on stitched function)

Let  
$$  
m(x)=  
\begin{cases}  
\sqrt{x+3}+\dfrac{1}{x+4}, & 0\le x\le 2,[6pt]  
\sqrt{x+3}+\dfrac{1}{x+4}+\dfrac{|x-2|}{(x+4)^2}, & 2<x\le 5.  
\end{cases}  
$$  
Determine the maximal subintervals of $[0,5]$ on which the MVT applies and, on each, write the equation for $c$.  
_Plain:_ Require continuity on $[a,b]$ and differentiability on $(a,b)$, then set $f'(c)=\dfrac{f(b)-f(a)}{b-a}$.

### 15. (4.3–4.5, full shape) for $x>-2$

$$  
F(x)=\frac{(x-1)^2\ln(x+2)}{(x+3)^{3/2}}.  
$$  
Give domain, intercepts, behavior as $x\to -2^+$, all critical points and classification, intervals of increase/decrease, concavity, and inflection points.  
_Plain:_ Use limits, $F'$, $F''$, and sign charts.

### 16. (4.4, L’Hôpital tower)

Evaluate  
$$  
\lim_{x\to0}\frac{e^{5x}-1-5x-\dfrac{25}{2}x^2-\dfrac{125}{6}x^3}{x^4\ln(1+6x)}.  
$$  
_Plain:_ Expand numerator and denominator to $x^4$ (series) or apply L’Hôpital repeatedly.

### 17. (4.7, two-shape optimization with cost)

A wire of length $24$ m is cut into two pieces. One forms a regular hexagon, the other a circle. The sheet to build the circle costs $2 per $\text{m}^2$ of area, the hexagon sheet costs $1 per $\text{m}^2$. Determine the cut that minimizes total cost. Check endpoints.  
_Plain:_ Express areas from perimeters; convert split into cost; optimize over the split.

### 18. (4.8, Newton basin)

Let $f(x)=xe^{x}+\ln(1+x)-7$ on $(0,\infty)$.

(a) Give the Newton iteration.  
_Plain:_ $x_{n+1}=x_n-\dfrac{f(x_n)}{f'(x_n)}$.

(b) Show there is a unique root.  
_Plain:_ Use monotonicity/convexity to prove existence and uniqueness.

(c) Exhibit an interval where Newton converges monotonically.  
_Plain:_ Choose a bracket with $f'$ nonzero and $f''$ controlling step size.

### 19. (4.9, antiderivative with negative powers)

Find an antiderivative of  
$$  
\frac{6x^{3}-5x+1}{x^{7/2}}.  
$$  
_Plain:_ Split into powers $x^\alpha$ and integrate term-by-term.

---

## 5. Integrals

_(Continues on later pages.)_

---

### Definitions

- **limit:** The value a function approaches as the input approaches a point.
    
- **one-sided limit:** Limit taken from only the left or only the right.
    
- **continuity:** The limit exists at a point, the value exists, and they are equal.
    
- **derivative:** Instantaneous rate of change; slope of the tangent line.
    
- **linearization:** Tangent-line approximation $L(x)=f(a)+f'(a)(x-a)$ near $x=a$.
    
- **MVT:** If $f$ is continuous on $[a,b]$ and differentiable on $(a,b)$, then some $c\in(a,b)$ has $f'(c)=\dfrac{f(b)-f(a)}{b-a}$. 



$$
\frac{5}{\frac{(t+3)^2}{5}}
$$