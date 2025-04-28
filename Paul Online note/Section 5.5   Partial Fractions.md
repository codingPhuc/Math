---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/PartialFractions.aspx
Current date: 2025-04-28
---
This section doesn't really have to  do with the rest of this chapter , but since it need to be cover in such a short chapter it will be a good way to cover it  


Let's suppose we add the two rational expression 


$$
 \begin{array}{l}
\begin{gathered}\frac{8}{x+1}-\frac{5}{x-4}=\frac{8\left(x-4\right)}{\left(x+1\right)\left(x-4\right)}-\frac{5\left(x+1\right)}{\left(x+1\right)\left(x-4\right)}\\=\frac{8x-32-(5x+5)}{\left(x+1\right)\left(x-4\right)}\\=\frac{3x-37}{\left(x+1\right)\left(x-4\right)}\end{gathered}
\end{array}
$$

what we  want to do in this section is start with  rational  expression and ask what simpler rational expression did we add or subtract to get the original expression .The process for this is called partial faction  and the result is called partial faction compression 

the compress can be long and sometime messy , however  it is fairly simple . We will start by determine the partial faction decomposition of  
$$
\frac{P(x)}{ Q(x)}
$$
Where both  $P(x)$ and  $Q(x)$ are polynomial and the degree of P(x ) is smaller than the degree of  Q(x)
So  ,  once we've determine  that partial faction can  be done we factor the denominator as completely as possible  . Then for  each factor in the denominator we can use the following table to determine the term(s)  we pick up in fraction  decomposition 


| Factor in denominator | Term  in partial fraction decomposition                                                                                 |
| --------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| $ax +b$<br>           | $\frac{A}{ax + b}$                                                                                                      |
| $(ax+b)^b$            | $\frac{A_1}{ax+b}+\frac{A_2}{\left(ax+b\right)^2}+\cdots+\frac{A_k}{\left(ax+b\right)^k}$                               |
| $ax^2 +bx+c$          | $\frac{Ax+B}{ax^2 +bx +  c}$                                                                                            |
| $(ax^2 +bx + c)^k$    | $\frac{A_1x+B_1}{ax^2+bx+c}+\frac{A_2x+B_2}{\left(ax^2+bx+c\right)^2}+\cdots+\frac{A_kx+B_k}{\left(ax^2+bx+c\right)^k}$ |

Notice that the first and third cases are really special cases of the second and fourth case if we let $k=1$ . Also , it will be possible to factor the polynomial into a linear factor of $(ax + b)$  and $(ax^2 +bx +c)$ some of these factor can be raise to a power

There are several method for determining the coefficient for each terms and we will go over it in the next section 


Example 1 : determine the partial fraction of each of the following  : 
$$
\begin{array} {l}
\frac{8x -  42}{x^2 + 3x  - 18 } 
\end{array}

$$ 
The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{8x - 42}{x^2  +  3x  - 18} =  \frac{8x - 42}{(x + 6)(x  - 3)} 
$$
so  by seeing the result a