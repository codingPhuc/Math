---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-08-25"
amount of time: 
learning score:
---

# #definition 
 
Here are **10 questions** based on the content from **Paul's Online Notes: Section 2.4 - Limit Properties**, each with a clear focus on concepts, examples, and terminology:

---

1. **What is the limit property that allows you to factor out a constant from a function inside a limit?**  
    _Answer:_  
    If cc is a constant, then lim⁡x→a[cf(x)]=clim⁡x→af(x)\lim_{x \to a} [c f(x)] = c \lim_{x \to a} f(x). This is known as the constant multiple rule.
    

---

2. **Which limit property justifies breaking up the limit of a sum or difference into individual limits?**  
    _Answer:_  
    lim⁡x→a[f(x)±g(x)]=lim⁡x→af(x)±lim⁡x→ag(x)\lim_{x \to a} [f(x) \pm g(x)] = \lim_{x \to a} f(x) \pm \lim_{x \to a} g(x)
    

---

3. **Under what condition can you take the limit of a quotient lim⁡x→af(x)g(x)\lim_{x \to a} \frac{f(x)}{g(x)} using the quotient rule?**  
    _Answer:_  
    You can apply the rule if lim⁡x→ag(x)≠0\lim_{x \to a} g(x) \ne 0
    

---

4. **Explain why lim⁡x→axn=an\lim_{x \to a} x^n = a^n is valid. What limit property does this depend on?**  
    _Answer:_  
    This is a special case of the power rule: lim⁡x→a[f(x)]n=[lim⁡x→af(x)]n\lim_{x \to a} [f(x)]^n = [\lim_{x \to a} f(x)]^n, with f(x)=xf(x) = x
    

---

5. **Why does the limit of a constant function lim⁡x→ac=c\lim_{x \to a} c = c?**  
    _Answer:_  
    Because a constant function does not change, its value is the same everywhere, so the limit is just the constant itself.
    

---

6. **In Example 1, how is the limit lim⁡x→−2(3x2+5x−9)\lim_{x \to -2} (3x^2 + 5x - 9) calculated using limit properties?**  
    _Answer:_  
    Split into three limits using sum rule, factor constants using the constant multiple rule, and apply known limits:  
    3(−2)2+5(−2)−9=12−10−9=−73(-2)^2 + 5(-2) - 9 = 12 - 10 - 9 = -7
    

---

7. **What does it mean for a function to be “nice enough” in the context of evaluating limits?**  
    _Answer:_  
    It means the function behaves well around the point of interest—no discontinuities or undefined behavior—so lim⁡x→af(x)=f(a)\lim_{x \to a} f(x) = f(a)
    

---

8. **List three types of functions that are always “nice enough” for all xx.**  
    _Answer:_
    

- Polynomials
    
- Sine and cosine functions
    
- Exponential functions axa^x, exe^x
    

---

9. **Under what restriction is xn\sqrt[n]{x} “nice enough” when nn is even?**  
    _Answer:_  
    The function is “nice enough” for x≥0x \ge 0 to avoid complex numbers.
    

---

10. **In Example 3, why can the limit be computed by direct substitution despite the complicated expression?**  
    _Answer:_  
    Because all functions involved (square root, exponential, logarithmic, trigonometric) are “nice enough” at x=3x = 3, and no domain restrictions are violated.
    

---

Let me know if you want these in **Anki format**, **multiple choice**, or **with diagram-based prompts**.












 Compute the value of the following limit.   
$$
\begin{array}{l} 
\lim_{  x \to  2 }   (3x^2  +  5x -  9)     \\
\lim_{  x \to  2 }3    \lim_{  x \to  2 } x^2 +  \lim_{  x \to  2 } 5 \lim_{  x \to  2 }  x     - \lim_{  x \to  2 }9  \\
3  \cdot  2^2  +   \cdot  5 \cdot 2 -    9   \\
  =  -7
\end{array}
$$

evaluate the  following limit 
$$
\begin{array}{l} 
\lim_{  z \to 1 }     \frac{6  -  3z + 10z^2 }{-2z^4   + 7z^3  + 1 }   \\
 =   \frac{ \lim_{  z \to 1 } (6  -  3z + 10z^2)}{ \lim_{  z \to 1 }  (-2z^4   + 7z^3  + 1 )}  \\
 =  \frac{ 6  -   3 \cdot 1    +  10 \cdot 1  }{ -2 \cdot 1   +  7 \cdot  3 + 1 }  \\
=   4\\  
\end{array}
$$


$$
\begin{array}{l} 
\lim_{ x \to  3 }  \left( - \sqrt[5] {x   }  +   \frac{e^x}{1 + \ln(x)  } + \sin(x)\cos(x) \right)  \\
-3^{1/5 }   +  \frac{e^3}{ 1 +  \ln (3)}  + \sin(3) \cdot  \cos (3)   \\
=    
\end{array}
$$