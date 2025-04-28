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
so  by seeing the result above a partial decomposition is just : 
$$
\frac{8x - 42}{x^2   +   3x  - 18}  =  \frac{A}{x+6}  +  \frac{B}{x - 3}
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =    (x  + 6) (x  - 3)
$$
$$
\frac{8x - 42}{x^2   +   3x  - 18}  =  \frac{A (x  - 3) + B(x  +  6) }{(x+6)(x - 3 )} 
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
8x   - 42  =   A(x  - 3) + B (x   +  6)
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A disappear so that we can find the other variable 
plug in  x  = 3 to find B  : 
$$
 \begin{array}{l} \\
 8 \cdot  3  -  42  = A( 3  -3) +  B  ( 3 + 6 )    \\
9B  =  -18   \\
B =  -2  
\end{array}
$$
plug in  x  = -6 to find B  : 
$$
\begin{array}{l} \\
8x   - 42  =   A(x  - 3) + B (x   +  6)  \\
8\cdot  -6  - 42  =   A( - 6 - 3) + B (-6   +  6)  \\
-9  A  =   -90   \\
A  =  10  
\end{array}
$$

So  by correctly  finding x we manage to get the value A and B  we will now plug them in : 

$$
\frac{8x  - 42 }{x^2 +  3x  - 18 }   = \frac{10}{x+ 6}   + -\frac{2}{x - 3}  = \frac{10}{ x + 6}  - \frac{2}{x - 3}
$$




#fail 
$$
\begin{array}{l} \\
\frac{9 -  9 x } {2x^2   +  7x - 4 }       \\

\end{array}

$$

The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }   = \frac{9 -  9 x } {(2x - 1) (x  + 4)} 
$$
so  by seeing the result above a partial decomposition is just : 
$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }    =  \frac{A}{2x - 1}  +  \frac{B}{x +4}
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =    (2x   -1 ) (x  +  4 )
$$
$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }     =  \frac{A (x  +  4) + B(2x  - 1 ) }{(2x   -1 ) (x  +  4 )} 
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
9 -  9 x  =  A (x  +  4) + B(2x  - 1 )
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A disappear so that we can find the other variable 
plug in  x  = -4 to find B  : 
$$
 \begin{array}{l} \\
9 -  9 \cdot  -4   =  A (-4   +  4) + B(2\cdot  -4  - 1 )   \\
-9B  =  45    \\
B =   -5 
\end{array}
$$
plug in  x  = $\frac{1}{2}$ to find A  : 
$$
\begin{array}{l} \\
9 -  9 \cdot   \frac{1}{2} =  A \left(   \frac{1}{2} +  4 \right) + B\left( 2\cdot  \frac{1}{2}  - 1  \right)  \\ 
  \frac{9}{2}A   =  \frac{9}{2} \\
 A  =   1 \\
A  =  10  
\end{array}
$$

So  by correctly  finding x we manage to get the value A and B  we will now plug them in : 

$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }    =  \frac{1}{2x - 1}  -  \frac{5}{ (x +4)}
$$






$$
\begin{array}{l} \\
\frac{4x^2}{(x  - 1 ) ( x    - 2)^2 }    \\
\end{array}
$$

The first thing we should do is factor the denominator as must as we can  .  


so  by seeing the result above a partial decomposition is just : 
$$
\frac{4x^2}{(x  - 1 ) ( x    - 2)^2 }     =  \frac{A}{x  - 1 }  +  \frac{B}{x -2  }    +  \frac{C}{(x  -2 )^2  }
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =    (2x   -1 ) (x  +  4 )
$$
$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }     =  \frac{A (x  +  4) + B(2x  - 1 ) }{(2x   -1 ) (x  +  4 )} 
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
9 -  9 x  =  A (x  +  4) + B(2x  - 1 )
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A disappear so that we can find the other variable 
plug in  x  = -4 to find B  : 
$$
 \begin{array}{l} \\
9 -  9 \cdot  -4   =  A (-4   +  4) + B(2\cdot  -4  - 1 )   \\
-9B  =  45    \\
B =   -5 
\end{array}
$$
plug in  x  = $\frac{1}{2}$ to find A  : 
$$
\begin{array}{l} \\
9 -  9 \cdot   \frac{1}{2} =  A \left(   \frac{1}{2} +  4 \right) + B\left( 2\cdot  \frac{1}{2}  - 1  \right)  \\ 
  \frac{9}{2}A   =  \frac{9}{2} \\
 A  =   1 \\
A  =  10  
\end{array}
$$

So  by correctly  finding x we manage to get the value A and B  we will now plug them in : 

$$
\frac{9 -  9 x } {2x^2   +  7x - 4 }    =  \frac{1}{2x - 1}  -  \frac{5}{ (x +4)}
$$


