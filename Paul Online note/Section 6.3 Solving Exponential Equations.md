---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-08
amount of time: 
learning score:
---


There are two method of solving  exponential equation . One method is simple but require a special form of exponential  equation . The other will work on  more complicated  exponential equation but can get a little messy 
let start by having a look at these simple method  ; 
$$
\text{if } b^x   = b^y  \text{ then } x =  y  
$$
if it isn't then this fact will do us no good 
$$
\begin{array}{l} \\
5^{3x}  =  5^{7x  - 2}    \\
3x  =  7x   - 2   \\
x = \frac{1}{2}
\end{array}
$$

$$
\begin{array}{l}  \\
4^{t^2} = 4^{6 - t}  \\
t^2  = 6 - t\\
t^2   -  6 +  t  =  0    \\
\left \{ 
t =   -3    \\
t =  2   
 \right.
\end{array}
$$

#fail 
$$
\begin{array}{l} \\
3^z   =  9^{z  +  5}    \\
z  =  2z  + 10  \\
 z   = -10   
\end{array}
$$

$$
\begin{array}{l}  \\
4^{5 - 9x}   =  \frac{1}{2^{3(x - 2)}}     \\
2^{2(5 - 9x)}  =  2^{-3(x - 2)}     \\
10  - 18x   =  -3x   +  6      \\
- 15x  =   -4  \\
 x =   \frac{4}{15}   \\
\end{array}
$$

the equation  that we solve  above relieve on the fact that the same base exponential  is the same . However , this is not always correct  . Consider the following 

$$
7^x  =  9 
$$there  is no easy way to find the number x that seven is raise to to get 9 . In fact this is exactly what this equation is asking us to find . The problem here is the x in the exponent , because of that all our knowledge for solving exponent won't do us any good  we need a way to get x out of the exponent . Lucky for us we have way to do that .  Recall this algorithm  from the last section  

$$
\log_{b}{a^r}   =  r \log_{b}a 
$$
