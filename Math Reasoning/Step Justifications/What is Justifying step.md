
2. **What your friend is doing in the picture**

The problem is essentially  
$$  
\int \cos^3\theta ,\sin\theta, d\theta.  
$$

Your friend is not just solving it; they are **justifying each step using general rules**:

1. **Substitution (u-sub)**  
    They set  
    $$  
    u = \cos\theta  
    $$  
    then differentiate:  
    $$  
    du = -\sin\theta,d\theta.  
    $$  
    From this they solve for (\sin\theta,d\theta):  
    (\sin\theta,d\theta = -du).
    
2. **Rewrite the integral in (u)**  
    $$  
    \int \cos^3\theta ,\sin\theta, d\theta  
    = \int u^3(-du)  
    = -\int u^3,du.  
    $$  
    Here they’re using the **constant multiple rule**:  
    (\int \alpha f(x),dx = \alpha\int f(x),dx.)
    
3. **Use the general power rule**  
    They recall the template  
    $$  
    \int u^n,du = \frac{u^{n+1}}{n+1} + C,  
    $$  
    then plug in (n=3):  
    $$  
    -\int u^3,du = -\frac{u^4}{4} + C.  
    $$
    
4. **Back-substitute** (not fully written but implied):  
    $$  
    -\frac{u^4}{4} + C = -\frac{\cos^4\theta}{4} + C.  
    $$
    

So this page is basically an **annotated calculation**: a worked example where each move is justified by a named rule (substitution, constant multiple rule, power rule, etc.). It’s _not_ a big theorem proof, but it is “proof-style” reasoning applied to a routine integral.

---

3. **What you are trying to learn (and how)**
    

You’re aiming at _two_ skills:

### A. Justifying each operation in a solution

Goal: every transformation you make comes from a known rule.

For this, you can:

- Make a small “rule list” inside your `Step Justifications` folder:
    
    - algebra: distributive law, factoring, solving for du, etc.
        
    - calculus: substitution, constant multiple rule, linearity, power rule, FTC I & II.
        
- For each homework solution, write it like this:
    
    1. (u := \cos\theta) (definition of substitution)
        
    2. (du = -\sin\theta,d\theta) (differentiate using chain rule)
        
    3. (\sin\theta,d\theta = -du) (algebra: solve for (\sin\theta,d\theta))
        
    4. (\int \cos^3\theta \sin\theta,d\theta = -\int u^3,du) (substitution + constant multiple rule)
        
    5. (= -\dfrac{u^4}{4} + C) (power rule for integrals)
        
    6. (= -\dfrac{\cos^4\theta}{4} + C) (back-substitution).
        

This is exactly the style your friend is using.

Useful symbols here:

- `:=` for definitions: (u := \cos\theta).
    
- `⇒` for “so”: (\sin\theta,d\theta = -du ⇒ \int \cos^3\theta\sin\theta,d\theta = -\int u^3,du).
    

I’ll keep pointing out such symbols whenever you upload math.

### B. Writing full mathematical proofs

That lives in your `Proofs` folder. Those are for statements like:

- “If (f) is continuous on ([a,b]), then it has an antiderivative.”
    
- “If (n) is even, then (n^2) is even.”
    

Enderton is more for this side: using symbols like  
(\forall, \exists, \to, \leftrightarrow, \land, \lor, \neg, \vdash, \models)  
to structure logical proofs.

For now, a good rule of thumb:

- **Solution justification:** short chains of equalities/implications with rule names in parentheses.
    
- **Proof:** a full paragraph (or list) where you start from hypotheses and logically derive the conclusion, often using quantifiers and logic symbols.
    

When you paste more handwritten math, I’ll:

- suggest notation (like `:=`, `⇒`, `∴`, quantifiers, etc.) to compress your words, and
    
- tell you whether the page belongs in `Step Justifications` or `Proofs`.
    

---

### Definitions

- substitution (u-sub): Technique where you define (u := g(x)) to simplify an integral, replacing (g(x)) and (dx) with (u) and (du).
    
- constant multiple rule: (\displaystyle \int \alpha f(x),dx = \alpha \int f(x),dx) for constant (\alpha).
    
- power rule for integrals: (\displaystyle \int u^n,du = \frac{u^{n+1}}{n+1} + C) for (n \neq -1).
    
- annotated solution: A worked problem where each step is justified by a named algebra or calculus rule.
    
- proof: A logically complete argument that shows a statement must be true given certain assumptions.