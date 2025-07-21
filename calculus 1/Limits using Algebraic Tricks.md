---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-07-21
amount of time: "30"
learning score:
---
# #definition  
we will compute a bunch of limit using algebraic tricks  
all of the limit here are in the form $\frac{0}{0}$ form $\lim_{ x \to a }\frac{f(x)}{g(x)}$where f(x)  = 0 and g(x) = 0 

## simplifying limit  
$$
\lim_{ x \to 1 } \frac{x^3-1}{x^2  -1 } = \lim_{ x \to 1 } \frac{(x-1) (x^2 + x +1)  }{(x - 1) (x + 1)}   = \lim_{ x \to 1 }  \frac{x^2 + x +1}{x + 1}  = \frac{3}{2}
$$

simplifying the limit  help with plugging in the value 

$$
\begin{array}{l}  \\
\lim_{ z \to 0 }   \frac{(5-z)^2-25}{z}  \\
 = \lim_{ x \to 0 } \frac{25-10z + z^2  -25}{z}   \\
=\lim_{ x \to 0 } \frac{-10z + z^2 }{z}   \\
=  \lim_{ x \to 0 }  -10 + z \\
 =  -10 
\end{array}
$$


$$
\lim_{ r \to 0 }   \frac{\frac{1}{r + 3}  - \frac{1}{3}}{r}   =  \lim_{ r \to 0 } \frac{\frac{3 -(r + 3)}{(r + 3)\cdot 3}}{r}  =  \lim_{ r \to 0 } \frac{r }{(r + 3)\cdot 3} \cdot \frac{1}{r} 
$$