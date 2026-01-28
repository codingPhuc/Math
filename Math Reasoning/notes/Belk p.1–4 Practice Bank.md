# Belk p.1–4 Practice Bank

Source: David Belk, _Number Theory with Polynomials_, pp. 1–4.

Topics: formal polynomials vs functions, degree/monic, division algorithm, divisibility, gcd, Bézout, irreducible.  

---

## A. Definitions and “state the theorem” questions

1. Define “polynomial over a field $F$” and explain what “$x$ is an indeterminate” is meant to prevent. (Belk p.1)
    
2. Belk says a polynomial is a formal sum, not a function.  
    a. State precisely what “two polynomials are equal” means in these notes.  
    b. Give an example of two different polynomials in $F[x]$ that define the same function $F\to F$, and explain what property of $F$ makes this possible. (Belk p.1)
    
3. Define $\deg(f)$, leading term, leading coefficient, and monic. Give one monic and one non-monic example in $\mathbb Q[x]$. (Belk p.1)
    
4. State Theorem 1 (Polynomial Division) exactly, including the inequality required of the remainder. (Belk p.2)
    
5. Define $f\mid g$ in $F[x]$. Then rewrite the definition without the symbol $\mid$ using “there exists $q$ such that …”. (Belk p.3)
    
6. Explain why “$F$ is a field” matters for the claim “any nonzero constant $c\in F^\times$ divides every polynomial.” (Belk p.3)
    
7. Define $\gcd(f,g)$ as Belk defines it, and explain why “monic” is built into the definition. (Belk p.3)
    
8. State Theorem 2 (Bézout’s Lemma) in Belk’s form. (Belk p.4)
    
9. Define “irreducible polynomial” as Belk defines it, and explain why he restricts to monic divisors. (Belk p.4)
    

---

## B. Proof questions

10. In the proof of Theorem 1, define  
    $$  
    h(x)=f(x)-a_mb_n^{-1}x^{m-n}g(x).  
    $$  
    Prove that either $h=0$ or $\deg(h)<\deg(f)$. Your proof must identify the leading term that cancels. (Belk p.2)
    
11. Prove uniqueness in Theorem 1: if  
    $$  
    q_1g+r_1=q_2g+r_2,\quad \deg(r_1)<\deg(g),\ \deg(r_2)<\deg(g),  
    $$  
    then $q_1=q_2$ and $r_1=r_2$. (Belk p.2–3)
    
12. Prove: if $f\mid g$ and $f\mid h$, then $f\mid (g+h)$. (Belk p.3)
    
13. Prove: if $f\mid g$ and $g\mid h$, then $f\mid h$. (Belk p.3)
    
14. Prove: if $c\in F^\times$, then $c\mid f$ for every $f\in F[x]$. Then explain why this can fail if $F$ is replaced by a general ring. (Belk p.3)
    
15. Let $f=qg+r$. Prove carefully: the common divisors of $f$ and $g$ are exactly the common divisors of $g$ and $r$. (Belk p.4)
    
16. Assume $f=qg+r$ and you already know $a,b$ such that $ag+br=d$. Prove the “lift” step:  
    $$  
    bf+(a-bq)g=d.  
    $$  
    (Belk p.4)
    

---

## C. Computation / construction questions

17. Divide in $\mathbb Q[x]$: $f(x)=x^5-2x^3+x-1$ by $g(x)=x^2-x+1$. Find $q,r$ with $\deg r<\deg g$. (Belk p.2)
    
18. Work in $\mathbb Z_5[x]$. Divide $f(x)=x^4+4x+3$ by $g(x)=x^2+2$. Give quotient and remainder in $\mathbb Z_5[x]$. (Belk p.2)
    
19. Over $\mathbb Q[x]$, compute $\gcd(f,g)$ for $f(x)=x^4-1$, $g(x)=x^3-1$, and output the gcd in monic form. (Belk p.3–4)
    
20. For the same $f,g$ in (19), find $a(x),b(x)\in\mathbb Q[x]$ such that  
    $$  
    a(x)f(x)+b(x)g(x)=\gcd(f,g).  
    $$  
    (Belk p.4)
    
21. In $\mathbb R[x]$, determine whether $x^2+1\mid x^4+1$. Either produce $q\in\mathbb R[x]$ with $x^4+1=(x^2+1)q$, or prove no such $q$ exists. (Belk p.3)
    
22. Let $f(x)=3x^4+6x^2$ and $g(x)=9x^2$ in $\mathbb Q[x]$.  
    a. Find a gcd $d(x)$.  
    b. Convert it to Belk’s gcd (monic). (Belk p.3)
    

---

## D. Conceptual “explain why” questions

23. Explain precisely why nonzero constants in $F[x]$ play the role of $\pm1$ in $\mathbb Z$ (divisibility + units). (Belk p.3)
    
24. In Theorem 1, explain exactly where the field property is used and what breaks if leading coefficients are not invertible. (Belk p.2)
    
25. Belk defines irreducible using monic divisors. Explain what ambiguity appears if you omit “monic” from the definition. (Belk p.4)
    

---

## Works Cited

Belk, David. _Number Theory with Polynomials_. Cornell University, pp. 1–4. 

- **Autism Learning Partners (Intake):** `intake@autismlearningpartners.com` [Autism Learning Partners](https://autismlearningpartners.com/contact-us/?utm_source=chatgpt.com)
    
- **Cynthia Bautista, PsyD (Heredia Therapy Group):** `dr.cindy@herediatherapy.com` [Semel Institute+1](https://teams.semel.ucla.edu/peers/telehealth-certified-usa/california-los-angeles-county?utm_source=chatgpt.com)
    
- **Heredia Therapy Group (general inbox):** `info@herediatherapy.com` [Providence Directory+1](https://phppd.providence.org/BaseSearch/Provider/View/114055019146735?PlanName=&utm_source=chatgpt.com)
    
- **Arol Behavioral Health Services (Lora Chon’s org):** `info@arolbehavioralhealthservicesllc.com` [ArolBHServices](https://www.arolbhservices.com/contact)