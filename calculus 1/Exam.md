Here’s a clean Obsidian-ready Markdown of the two pages you shared. Math blocks use `$$ … $$`. I preserved problem wording and added short plain-language lines under each formula.

---

# Calculus I–II–III Core (Honors) — Ultra-Composite Final

**Coverage:** Stewart Calculus 9e, Ch. 2–11 (single/multilayer chains, nontrivial series, DE models)  
**Rules:** No calculators. Exact forms only. Every domain and theorem hypothesis must be stated.  
**Conventions:** All objects are maps (f:A\to\mathbb{R}) or (f:A\to\mathbb{R}^2) for a stated set (A). When using IVT/MVT/FTC, state (A) and continuity/differentiability. For parametric/polar, state the parameter interval. For power series, state radius and interval of convergence. For DEs, name type (separable/linear) and solve on appropriate domain.

---

## 2. Limits and Derivatives

### 1. (2.1–2.3, velocity via nontrivial limit)

A particle moves on a line with position (s(t)) for (t>-2).

- (a) Compute (v(0)) using only (v(0)=\lim_{h\to0}\dfrac{s(h)-s(0)}{h}).  
    _Plain:_ Use the limit of the difference quotient at (t=0).
    
- (b) Then find (v(t)) and (a(t)) in closed form.  
    _Plain:_ Differentiate once for velocity, twice for acceleration, on the stated domain.
    
- (c) Determine all (t>-2) such that (v(t)>0) and (a(t)>0).  
    _Plain:_ Solve sign conditions for the first and second derivatives.
    

### 2. (2.2–2.3, high-order cancellation)

Evaluate  
$$  
\lim_{x\to0}\frac{\sin(9x)-9x+\dfrac{(9x)^3}{6}-\dfrac{(9x)^5}{120}}{x^6\ln(1+7x)}.  
$$  
_Plain:_ Use series (or repeated L’Hôpital) to match top’s order with bottom’s order.

### 3. (2.4, (\varepsilon)–(\delta) with nonunit denominator)

Let  
$$  
f(x)=\frac{5x-7}{2x+9}.  
$$  
_Plain:_ A rational function with nonconstant denominator.*

Prove from the (\varepsilon)–(\delta) definition that  
$$  
\lim_{x\to 2} f(x)=\frac{3}{13},  
$$  
_Plain:_ Show outputs stay within (\varepsilon) of (3/13) by constraining (x) within (\delta) of 2.*

and give an explicit (\delta(\varepsilon)).  
_Plain:_ Solve (|f(x)-3/13|<\varepsilon) for (|x-2|<\delta(\varepsilon)).*

### 4. (2.5–2.6, stitched continuity + asymptote)

Define  
$$  
f(x)=  
\begin{cases}  
\dfrac{\sqrt{7x+8}-5}{x-3}, & x\ne 3,[6pt]  
a, & x=3,  
\end{cases}  
\qquad  
g(x)=\dfrac{5x^4-7x^2+3\ln x}{2x^4+x^3}+\dfrac{4}{x},\quad x>0.  
$$  
_Plain:_ (f) is patched at (x=3); (g) is a rational–log mix on ((0,\infty)).*

- (a) Choose (a) so (f) is continuous at (3).  
    _Plain:_ Take (a=\lim_{x\to3} f(x)) by rationalizing the numerator.*
    
- (b) Find all horizontal asymptotes of (g) and prove the limits.  
    _Plain:_ Compare highest powers and the (4/x) tail as (x\to\infty) and (x\to0^+).*
    

### 5. (2.7–2.8, derivative as a function with domain traps)

On (A=(0,\infty)\setminus{1}) define  
$$  
y(x)=\frac{(x^2+4)e^{2x}}{(x-1)^{,3\sqrt{x}}}.  
$$  
_Plain:_ Exponential over a power with (x)-dependent exponent; exclude (x=1).*

Find (y'), the locus of horizontal tangents, and the set where (y) is increasing.  
_Plain:_ Log-differentiate, set (y'=0) for horizontals, and solve (y'>0) for increase.*

---

## 3. Differentiation Rules

### 6. (3.1–3.3, derivative gauntlet with hyperbolics)

Differentiate  
$$  
F(x)=\frac{(4x^2-x+5)^{5},\sin(3x),\cosh(2x)}{x^{5/3},(1+x^{4})}.  
$$  
_Plain:_ Product/quotient/chain with trig and hyperbolic; simplify as (F(x),[\cdots]).*

Present the result as (F(x)[\cdots]).  
_Plain:_ Factor (F(x)) and collect the logarithmic derivative terms.*

### 7. (3.4, ultra-chain with variable exponent) On ((0,\infty)),

$$  
H(x)=\frac{\big[\ln(1+e^{x^2})\big]^{\arctan(\sqrt{x}+1/x)}}{x^{\sqrt{1+\sinh(\ln x)}},(1+x)^{x/(1+x)}};\cdot;e^{,x^{2}/(1+x^{2})}.  
$$  
_Plain:_ A product of several chained parts, including a function to a function power.*

Find (H'(x)) by logarithmic differentiation; express as (H(x)[\cdots]).  
_Plain:_ Differentiate (\ln H), then multiply by (H).*

### 8. (3.5, implicit with mixed transcendental)

On ({(x,y): x>0,\ y>0}),  
$$  
x^{2}+2xy+y^{2}+\ln x+\ln y+\arctan!\Big(\frac{y}{x}\Big)=10.  
$$  
_Plain:_ Implicit relation mixing polynomial, logs, and arctan.*

(a) Show (y) is differentiable near ((1,2)).  
_Plain:_ Check (\partial F/\partial y\neq0) to apply the Implicit Function Theorem.*  
(b) Find (y'(x)).  
_Plain:_ Differentiate both sides; solve for (y').*  
(c) Compute (y'(1)) and (y''(1)).  
_Plain:_ Evaluate the derivative and its derivative at ((1,2)).*

### 9. (3.6, log + inverse trig + power) On ((0,4)),

$$  
u(x)=\frac{\big(\ln(3x^{2}+1)\big)^{4},\arctan(5x)}{x^{5/2},(4-x)^{2/3}}.  
$$  
_Plain:_ Quotient with chained logs, arctan, and fractional powers.*

Find (u'(x)) and factor as far as reasonable.  
_Plain:_ Use log-diff or quotient+product+chain and tidy common factors.*

### 10. (3.7–3.9, rates + exponential in context)

A trough of length (6) m has isosceles triangular cross-section of height (4) m and base (4) m (vertex at bottom). Water inflow is (1.1\ \text{m}^3/\text{min}) and silt reduces effective volume at (0.2\ \text{m}^3/\text{min}). When the water depth is (2.5) m, find (dh/dt).  
_Plain:_ Similar triangles give area vs depth; differentiate volume in time with net inflow.*

### 11. (3.10, linearization with sharp MVT bound)

For (f(x)=(5x+4)^{5/3}) at (x_{0}=1), find (L(x)) and the best bound on  
$$  
\big|f(1.02)-L(1.02)\big|  
$$  
_Plain:_ Use linearization error bounded by (\dfrac{M}{2}|x-1|^{2}) from the MVT/second derivative.*

that you can obtain from (f'') on ([1,1.02]).

### 12. (3.11, hyperbolic composite)

Differentiate  
$$  
y(x)=\sinh(4x),\tanh(2x)-\operatorname{sech}x,  
$$  
_Plain:_ Use identities ( (\sinh)'=\cosh), ((\tanh)'=\operatorname{sech}^{2}), ((\operatorname{sech})'=-\operatorname{sech}\tanh).*

and rewrite purely in (\tanh x) and (\operatorname{sech}x).  
_Plain:_ Convert (\sinh,\cosh) using (\tanh,\operatorname{sech}).*

---

## 4. Applications of Differentiation

### 13. (4.1, absolute extrema with kinks) On ([0,4]),

$$  
f(x)=x^{2/3}(4-x)^{2/3}.  
$$  
_Plain:_ Nondifferentiable at endpoints; check interior criticals and corners.*

Find all absolute extrema; justify each candidate (interior, endpoints, nondifferentiable).

### 14. (4.2, MVT on stitched function)

Let  
$$  
m(x)=  
\begin{cases}  
\sqrt{x+3}+\dfrac{1}{x+4}, & 0\le x\le 2,[6pt]  
\sqrt{x+3}+\dfrac{1}{x+4}+\dfrac{|x-2|}{(x+4)^{2}}, & 2<x\le 5.  
\end{cases}  
$$  
_Plain:_ A piecewise function with an added kink term after (x=2).*

Determine the maximal subintervals of ([0,5]) on which the MVT applies and, on each, write the equation for (c).  
_Plain:_ Require continuity on closed interval and differentiability inside; apply MVT.*

### 15. (4.3–4.5, full shape) For (x>-2),

$$  
F(x)=\frac{(x-1)^{2}\ln(x+2)}{(x+3)^{3/2}}.  
$$  
_Plain:_ Do domain, intercepts, limits near (-2^+), critical points, monotonicity, concavity, inflection.*

### 16. (4.4, L’Hôpital tower)

Evaluate  
$$  
\lim_{x\to0}\frac{e^{5x}-1-5x-\dfrac{25}{2}x^{2}-\dfrac{125}{6}x^{3}}{x^{4}\ln(1+6x)}.  
$$  
_Plain:_ Expand numerator to (x^{4}) and denominator to (x^{4}) using series or repeated L’Hôpital.*

### 17. (4.7, two-shape optimization with cost)

A wire of length (24) m is cut into two pieces. One forms a regular hexagon, the other a circle. The sheet to build the circle costs $2 per m(^2) of area, the hexagon sheet costs $1 per m(^2). Determine the cut that minimizes total cost. Check endpoints.  
_Plain:_ Express areas from perimeters, convert wire split to costs, optimize over split fraction.*

### 18. (4.8, Newton basin)

Let (f(x)=xe^{x}+\ln(1+x)-7) on ((0,\infty)).

- (a) Give the Newton iteration.  
    _Plain:_ (x_{n+1}=x_n-\dfrac{f(x_n)}{f'(x_n)}).*
    
- (b) Show there is a unique root.  
    _Plain:_ Use monotonicity/convexity to prove existence and uniqueness.*
    
- (c) Exhibit an interval where Newton converges monotonically.  
    _Plain:_ Choose a bracket where (f') doesn’t vanish and (f'') controls the step.*
    

### 19. (4.9, antiderivative with negative powers)

Find an antiderivative of  
$$  
\frac{6x^{3}-5x+1}{x^{7/2}}.  
$$  
_Plain:_ Split into powers (x^{\alpha}) and integrate term-by-term.*

---

## 5. Integrals

_(Continues on later pages.)_

---

## Definitions

- **limit:** The value a function approaches as the input approaches a point.
    
- **one-sided limit:** Limit taken from only the left or only the right.
    
- **continuity:** The limit exists at a point, the function value exists, and they are equal.
    
- **derivative:** Instantaneous rate of change; the slope of the tangent line.
    
- **linearization:** Tangent-line approximation (L(x)=f(a)+f'(a)(x-a)) near (x=a).
    
- **MVT:** If (f) is continuous on ([a,b]) and differentiable on ((a,b)), then some (c\in(a,b)) satisfies (f'(c)=\dfrac{f(b)-f(a)}{b-a}).