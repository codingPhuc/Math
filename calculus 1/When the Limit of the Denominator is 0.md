---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-07-21
amount of time: 
learning score:
---
# #definition  

$$
\lim_{  x  \to  a }   \frac{f(x)}{g(x)}  = \lim_{ x \to a }   \frac{f(x)}{\lim_{ x \to a } g(x)} 
$$
provided  that $g(x)\neq 0$ 

## what if lim g(x)  = 0 ?  
either one of these cases : 
1.   lim g(x) = 0  
2. lim f(x)  = 0 and lim g(x)  =0 
the reason for this is that if we find
$$
\lim_{ x \to 3 } -\frac{4X}{x-3}  x =  \lim_{ x  \to 3 }  
$$


| x    | $-\frac{4x}{x-3}$                    |
| ---- | ------------------------------------ |
| 2.9  | 116  =   $-\frac{12}{-0.1}=120$      |
| 2.99 | 1196 =   $-\frac{12}{-0.01}=1200$    |
| 2.99 | 11996 =   $-\frac{12}{-0.001}=12000$ |
$$
\lim_{ x \to 3 } -\frac{4X}{x-3}  x = \frac{-}{-}   =  + 
$$


| x     | $-\frac{4x}{x-3}$ |
| ----- | ----------------- |
| 3.1   | -124              |
| 3.01  | -1204             |
| 3.001 | -12004            |
$$
\lim_{ x \to 3 } -\frac{4X}{x-3}  x = \frac{-}{+}   =  - 
$$


when  it say that the equation is approaching -3  from the left and the right and left (3^+, 3^-) it mean that the denomination will evaluate to a positive infinity or a negative infinity bases on the solution given. 


example : 
$$
 \lim_{ x \to -4 }  \frac{5x}{\mid x+ 4 \mid }  
 
$$

$$
\mid  x+ 4  \mid  \implies  \{\begin{array}{l} \\
x+ 4  \implies   x+ 4 > 0 ( x > -4) \\
-(x+ 4 )  \implies  x+ 4 < 0 ( x < -4) 
\end{array}
$$
$$
\lim_{ x \to -4^- }   = \frac{5x}{\cdot - ( x+ 4 ) }   =  \frac{1}{+}  =  - 
$$

$$
\lim_{ x \to -4^+}   = \frac{5x}{ \cdot ( x+ 4 ) }   =  \frac{-}{+}  =  - 
$$


#todo 
I don't understand the 
$$
\lim_{ x \to -4^+}   = \frac{5x}{ \cdot ( x+ 4 ) }   =  \frac{-}{+}  =  - 
$$
 I mean if x =  5 since it trying to approach  -4 from the right would the above be a positive not a negative, or do we only deal in the infinite fraction range close to -4 like -3.999 and -4.00001 and that ?  