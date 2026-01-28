## Obsidian Test Bank — LCD $\to$ Polynomial Identity, and the “License” to Equate Coefficients

### A) Type-Recognition (What object did you create?)

- **A1.** You start with an equality of rational expressions  
    $$\frac{P(x)}{Q(x)}=\frac{A(x)}{B(x)}$$  
    with $P,Q,A,B\in F[x]$ and $Q\not\equiv 0$, $B\not\equiv 0$.  
    **Question:** After multiplying both sides by the LCD, what _type_ of statement do you obtain (name it precisely), and in what algebraic object does it live?
    
- **A2.** Same setup as A1.  
    **Question:** Write the _general form_ of what you get after clearing denominators:  
    $$\text{(something in }F[x]\text{)} \equiv \text{(something in }F[x]\text{)}.$$  
    What are the “somethings” in terms of $P,Q,A,B$?
    
- **A3.** In A1, suppose you multiply by $Q(x)B(x)$ instead of the LCD.  
    **Question:** Do you still get a polynomial identity? What changes, and what doesn’t?
    
- **A4.** “Clearing denominators” sometimes produces an implication that is only true where denominators are nonzero.  
    **Question:** State the exact domain-of-validity statement you are allowed to claim _before_ and _after_ multiplying by the LCD.
    

---

### B) The License (Why coefficient-matching is legal)

- **B1.** State a theorem that justifies: if $p(x)\equiv q(x)$ in $F[x]$, then coefficients match term-by-term.  
    **Question:** What is the theorem called (or how would you name it), and what does it _actually_ assert?
    
- **B2.** Prove the coefficient-matching rule using only the definition of polynomial equality in $F[x]$.  
    **Constraint:** Your proof must explicitly say what “$p=q$ in $F[x]$” means.
    
- **B3.** Prove the coefficient-matching rule _without_ using the definition of polynomial equality.  
    **Hint-direction only:** Use a lemma about how many roots a nonzero polynomial of degree $n$ can have.  
    **Question:** Write the proof as a chain of named claims.
    
- **B4.** You have a polynomial identity  
    $$a_0+a_1x+\cdots+a_nx^n \equiv b_0+b_1x+\cdots+b_nx^n.$$  
    **Question:** What polynomial do you form by “bringing everything to one side,” and what must you prove about it to conclude $a_k=b_k$ for all $k$?
    

---

### C) The Engine Lemmas (What you must be able to prove on command)

- **C1. Root bound theorem.**  
    **Task:** Prove: if $f(x)\in F[x]$ is nonzero and $\deg f=n$, then $f$ has at most $n$ distinct roots in $F$.
    
- **C2. Factor theorem step (the cancellation moment).**  
    Assume $f(x)=(x-a)g(x)$ in $F[x]$ with $a\in F$.  
    **Question:** Prove that if $b\neq a$ and $f(b)=0$, then $g(b)=0$.  
    **Follow-up:** Identify exactly where you used that $F$ is a field.
    
- **C3. Identity theorem.**  
    Assume $F$ is infinite.  
    **Task:** Prove: if $p(x),q(x)\in F[x]$ agree on infinitely many inputs $x\in F$, then $p\equiv q$ in $F[x]$.
    
- **C4. LCD-to-identity pipeline.**  
    **Task:** Write a clean “pipeline proof” with three labeled steps:
    
    1. clearing denominators $\Rightarrow$ polynomial identity,
        
    2. polynomial identity $\Rightarrow$ coefficient equalities,
        
    3. coefficient equalities $\Rightarrow$ unknown constants found.
        

---

### D) Trapdoors (Counterexamples that prove you understand the hypotheses)

- **D1. Finite-field trap.**  
    **Task:** Give an example over a finite field $F$ where two different polynomials define the same function $F\to F$.  
    **Question:** Explain why this forces you to distinguish “polynomial equality” from “function equality.”
    
- **D2. Zero-divisor trap.**  
    **Task:** Give a ring $R$ with zero divisors and elements $u,v\in R$ with $u\neq 0$ but $uv=0$.  
    **Question:** Use this to show why “$uv=0$ implies $v=0$” fails, and connect that failure to the step “$(b-a)g(b)=0$ implies $g(b)=0$.”
    
- **D3. Domain-of-validity trap (extraneous solutions).**  
    **Task:** Build a simple rational equation where multiplying by a denominator creates an extra solution that wasn’t valid originally.  
    **Question:** State the correct way to phrase the conclusion so you don’t accidentally accept the extraneous solution.
    

---

If you answer **A1 + B4 + C2** cleanly, you basically own the two hint bullets.