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


## **What does Property 1, concerning limits and multiplicative constants, allow us to do when evaluating a limit?** 

### #human_explaination 
That make me find my answer Let me refine my answer So they probably won in limit mean that you can remove the constant algorithm limit meaning the constant can be removed as I outside the limit wake up when applying the When Olympic applied the constant will be moved outside of the limit enabling us to more easily factor

### #ai_explaination 
That's a much better explanation, you've definitely refined your understanding of Property 1!

**Rating: 9/10**

You've correctly identified the core idea: **Property 1** allows you to **"factor" a multiplicative constant out of a limit**. This means that when you have a constant multiplied by a function within a limit, you can move that constant to the outside of the limit expression before evaluating the limit of the function.

As stated in the sources: [\mathop {\lim }\limits_{x \to a} \left[ {cf\left( x \right)} \right] = c\mathop {\lim }\limits_{x \to a} f\left( x \right)] In simpler terms, you can **move the constant `c` outside the limit operator**. This is exactly what was done in Example 1, where `3` and `5` were factored out of their respective limits.

Your phrasing "remove the constant algorithm limit" and "wake up when applying the When Olympic applied" is a bit unclear, but the underlying concept of moving the constant outside to "more easily factor" is correct and directly aligns with the source's description of factoring the constant out.

Now, let's revisit the question about Property 2, since your initial answer was closer to that concept.

## **What is the core idea behind Property 2 regarding limits?**
### #human_explaination 
The quality behind poverty too regarding limit it back we can apply to limit into individual term instead of a term that get connected by a sign Basically we can apply limit to individual terms either by multiplication addition subtraction and so on

### #ai_explaination 

That's a very good explanation of Property 2! You've captured the essence of what it allows us to do.

**Rating: 8/10**

You are correct that **Property 2** allows us to **apply the limit to individual terms** when they are connected by addition or subtraction.

The core idea is that when taking the limit of a sum or difference of functions, you can find the limit of each function separately and then combine those individual limits with the appropriate sign.

As the sources state: [\mathop {\lim }\limits_{x \to a} \left[ {f\left( x \right) \pm g\left( x \right)} \right] = \mathop {\lim }\limits_{x \to a} f\left( x \right) \pm \mathop {\lim }\limits_{x \to a} g\left( x \right)] This means, to take the limit of a sum or difference, "all we need to do is **take the limit of the individual parts and then put them back together with the appropriate sign**". This property is not limited to just two functions but works for any number of functions separated by "+" or "-" signs. Example 1 clearly demonstrates this, where the limit of a polynomial with three terms is broken down into three separate limits using Property 2.

While your answer broadly mentioned "multiplication addition subtraction and so on," Property 2 specifically addresses sums and differences. Other properties (like Property 3 for multiplication and Property 4 for division) handle those operations separately, but the general principle of breaking down a limit into individual parts is consistent across these.

---

**Question:**  
### Under what condition can you take the limit of a quotient  
$$
\lim_{x \to a} \frac{f(x)}{g(x)}
$$  
using the quotient rule?



---

4. **Explain why lim⁡x→axn=an\lim_{x \to a} x^n = a^n is valid. What limit property does this depend on?**  

---

5. **Why does the limit of a constant function lim⁡x→ac=c\lim_{x \to a} c = c?**  


---

6. **In Example 1, how is the limit lim⁡x→−2(3x2+5x−9)\lim_{x \to -2} (3x^2 + 5x - 9) calculated using limit properties?**  

---

7. **What does it mean for a function to be “nice enough” in the context of evaluating limits?**  

---

8. **List three types of functions that are always “nice enough” for all xx.**  
    _Answer:_


---

9. **Under what restriction is xn\sqrt[n]{x} “nice enough” when nn is even?**  

---

10. **In Example 3, why can the limit be computed by direct substitution despite the complicated expression?**  

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