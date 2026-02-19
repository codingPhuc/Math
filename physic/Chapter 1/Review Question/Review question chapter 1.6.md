


---

title: Order of magnitude + estimation bounds — self-test  
sources:

- Zemansky §1.6
    
- Young & Freedman Ch1 §1.6
    

---

## A) Core definitions and notation

1. Define “order of magnitude” in one sentence. What does “within one order of magnitude” mean quantitatively?


2. If $x = 3.2 \times 10^{7}$, what is its order of magnitude? State your rule (rounding vs floor) explicitly.
    
3. Give two different numbers that have the same order of magnitude as $8 \times 10^{3}$. Explain why.
    
4. Convert $0.00056$ to scientific notation. Then state its order of magnitude.
    
5. Explain the difference between “significant figures” and “order of magnitude.” Give one example where they point in different directions.
    
6. What does it mean to “estimate to one significant digit” in a Fermi-style calculation? Why is that often enough?
    

significant figure is used to indicate a measurement uncertainty. If the input is crude the output result should be scale to match the least precise input and if input are crude estimate then it is best to report a power of 10 scalre estimate 
a significant figure is the measurement of precision of a physical quantity. If the input values is crude then the ouput must be too scale base
## B) Estimation mechanics (Fermi moves)

7. You’re estimating a product $abc$. What is the fastest way to keep the order of magnitude but avoid calculator arithmetic?
    
8. You’re estimating $\frac{A}{B}$ where both $A$ and $B$ are uncertain. What’s the conservative way to bound the ratio?
    
9. If you must approximate $\pi$, which choice is better for upper bounds: $3$ or $3.2$? Justify.
    
10. Explain “back-of-the-envelope dimensional checking.” How can it catch a wrong power of 10?
    
11. You measure length in cm but need meters. What is the most common power-of-10 mistake students make in this conversion, and how do you prevent it systematically?
    
12. Suppose a quantity depends on $r^{3}$. If $r$ is “about 2” but might be anywhere from $1.5$ to $2.5$, how does that uncertainty scale in the result (qualitatively)?
    

## C) Estimation bounds (upper/lower, worst-case, rounding)

13. Define lower bound and upper bound for a measured quantity reported as a rounded decimal (example: $2.3$ m).
    
14. If a length is recorded as $12.4$ cm to the nearest $0.1$ cm, write the interval in inequality form that must contain the true value.
    
15. Same situation, but the instrument is labeled “$\pm 0.1$ cm accuracy.” How is that different from “rounded to nearest $0.1$ cm”?
    
16. If $x \in [a,b]$ and $y \in [c,d]$ with all endpoints positive, write the tightest possible bounds for $xy$ and for $\frac{x}{y}$.
    
17. If $x \in [a,b]$ but $y \in [c,d]$ crosses zero, what goes wrong when trying to bound $\frac{x}{y}$? State the exact issue.
    
18. You have $x = 1000 \pm 5$. Give a bound on the relative (fractional) uncertainty and the percent uncertainty.
    
19. Why can “small percent uncertainty” still produce a big absolute uncertainty for large quantities? Give a one-line explanation.
    
20. When adding quantities with uncertainties, why is it usually safer to add absolute uncertainties, not percent uncertainties?
    

## D) Applications (set up, defend, sanity-check)

21. Estimate the number of heartbeats in an 80-year lifetime. State assumptions as explicit bounds (low/high).
    
22. Estimate how many piano tuners could plausibly exist in Los Angeles. Give a low and a high estimate and defend each.
    
23. Estimate the mass of air in a typical classroom. You may assume reasonable dimensions and air density; show how you choose bounds.
    
24. Estimate the number of grains of rice in a 10 lb bag, with an uncertainty range that you can defend.
    
25. A sheet of paper is about $0.1$ mm thick. Estimate the height of a stack of 500 sheets and give an upper/lower bound if thickness varies by $\pm 20%$.
    
26. You drive $38$ miles at “about 60 mph.” Give a bound on travel time if speed could realistically be 50–70 mph.
    
27. A measurement reads $9.8$ m/s$^{2}$ for $g$. Explain why reporting $g \approx 10$ m/s$^{2}$ is often better for quick estimates, and when it is not.
    
28. You compute an energy and get $2.4 \times 10^{-19}$ J. Convert to eV using $1,\text{eV} \approx 1.6 \times 10^{-19}$ J and state the order of magnitude in eV without detailed arithmetic.
    
29. A result comes out $3 \times 10^{8}$ m/s for a walking speed estimate. What are two independent sanity checks that would catch the error immediately?
    
30. Build a bound: If radius $r$ is measured as $10.0$ cm to the nearest $0.1$ cm, bound the area $A = \pi r^{2}$ and state whether your area uncertainty is closer to $1%$ or $10%$ (no calculator).