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
$$
\begin{array}{l} \\
\frac{4x^2}{(x  - 1 ) ( x    - 2)^2 }    \\
\end{array}
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{4x^2}{(x  - 1 ) ( x    - 2)^2 }     =  \frac{A}{x  - 1 }  +  \frac{B}{x -2  }    +  \frac{C}{(x  -2 )^2  }
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =   ( x  -1  ) ( x  - 2 )^2   
$$
$$
\frac{4x^2}{(x  - 1 ) ( x    - 2)^2 }     =  \frac{A}{x  - 1 }  +  \frac{B}{x -2  }    +  \frac{C}{(x  -2 )^2  }   \frac{A( x  - 2 )^2  + B ( x  -1  ) ( x  - 2 ) +  C ( x  -1  )    }{( x  -1  ) ( x  - 2 )^2   }
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
4x^2  =   A( x  - 2 )^2  + B ( x  -1  ) ( x  - 2 ) +  C ( x  -1  ) 
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
plug in  x  = 1 to find A   : 
$$
 \begin{array}{l} \\
4x^2  =A( x  - 2 )^2  + B ( x  -1  ) ( x  - 2 ) +  C ( x  -1  )   \\
4\cdot 1^2  =A( 1  - 2 )^2  + B ( 1  -1  ) ( x  - 2 ) +  C ( 1  -1  )    \\
A  =       4 
\end{array}
$$
plug in  x  = $2$ to find C  : 
$$
\begin{array}{l} \\
4\cdot  2^2  =A( 2  - 2 )^2  + B ( 2  -1  ) ( 2 - 2 ) +  C ( 2  -1  )   \\       C =   16 \\ 
\end{array}
$$
There is no  x that we can plug in to eliminate  both A  and C  . Instead used the A and C in our last evaluation  in order to get B plug  in a simple number x =  0  : 
$$
\begin{array}{l} \\
 4\cdot 0^2  =   4( 0 -2  )^2 + B ( 0  -1  ) ( 0  - 2 ) + 16 ( 0   -1)     \\
2B  =  0    \\
B  =   0  \\
\end{array}
$$

So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
\frac{4}{x  - 1 }    +  \frac{16}{(x  -2 )^2  } 
$$








$$
\begin{array}{l} \\
\frac{9x+ 25}{(x + 3)^2}   \\
\end{array}
$$

The first thing we should do is factor the denominator as must as we can  .  
$$
\begin{array}{l} \\
\frac{9x+ 25}{(x + 3)^2}   \\
\end{array}
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{9x+ 25}{(x + 3)^2}   =  \frac{A}{x  +  3  }  +  \frac{B}{(x + 3)^2   } 
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =  (x +  3 )^2
$$
$$
\frac{9x+ 25}{(x + 3)^2}    = \frac{A}{x  +  3  }  +  \frac{B}{(x + 3)^2   }   =   \frac{A( x  +  3 ) +   B}{(x  +  3)^2  } 
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
9x+ 25 = A( x  +  3 ) +   B
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
plug in  x  = -3 to find B   : 
$$
 \begin{array}{l} \\
9(-3)+ 25 = A( -3  +  3 ) +   B   \\
  B     =-2      \\
\end{array}
$$

plug in  x  = 0  to find B   :  
$$
 \begin{array}{l} \\
 25  = A( x   +  3 ) +   B  \\
 25  = A( 0   +  3 ) -2   \\
A = \frac{27}{3 }  =  9      \\
\end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
\frac{9}{  x  + 2  }    -  \frac{2}{ (x  +  3)^2 } 
$$






$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)} 
$$



The first thing we should do is factor the denominator as must as we can  .  
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)} 
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)}   =  \frac{A}{x }  +  \frac{B}{(x^2 + 2x - 6) } 
$$
now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =  (x^2 + 2x - 6)x 
$$
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)}  =  \frac{A}{x }  +  \frac{B}{(x^2 + 2x - 6) }   = \frac{ (x^2 + 2x - 6)A + Bx  }{(x^2 + 2x - 6)x } 
$$ 
We need a value A and B  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
8x^2 -12 = (x^2 + 2x - 6)A + Bx
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
plug in  x  = 0  to find A   : 
$$
 \begin{array}{l} \\
8\cdot 0^2 -12  = A( 0  +  3 ) +   B\cdot  0    \\
3A  =  -12   \\
A  =   -4   \\
\end{array}
$$


plug in  x  = 0  to find B   :  
$$
 \begin{array}{l} \\
8(- 1 + \sqrt{  7 })^2 -12 = ((- 1 + \sqrt{  7 })^2 + 2(- 1 + \sqrt{  7 })- 6)A + B(- 1 + \sqrt{  7 }) \\
B  =  8\cdot (- 1 + \sqrt{  7 })   -  \frac{12}{(- 1 + \sqrt{  7 })}   \\
B =  -10 +  6\sqrt{ 7 }   \\
\end{array}
$$



So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
\frac{-10 +  6\sqrt{ 7 }  }{ x }    -  \frac{4}{ x^2  + 2x  - 6 } 
$$










#fail 
$$
\frac{8x^2 -12 }{x (x^2 + 2x - 6)} 
$$



The first thing we should do is factor the denominator as must as we can  .  
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)} 
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)}   =  \frac{A}{x }  +  \frac{Bx + C}{(x^2 + 2x - 6) } 
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =  (x^2 + 2x - 6)x 
$$
$$
\frac{8x^2 -12 }{x(x^2 + 2x - 6)}  =  \frac{A}{x }  +  \frac{Bx + C}{(x^2 + 2x - 6) }   = \frac{ (x^2 + 2x - 6)A  +  x(Bx  + C)  }{(x^2 + 2x - 6)x } 
$$ 
We need a value A , B  and C  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
8x^2 -12 =(x^2 + 2x - 6)A  +  x(Bx  + C)    \\
8x^2  - 12  =  Ax^2   +  2Ax    - 6A  +  Bx^2  + Cx    \\
  8x^2  - 12  =  Ax^2  +  Bx^2    +  2Ax  + Cx     - 6A       \\
8x^2  - 12   =  (A + B)x^2  +  (2A + C) x  -  6A     \\

\end{array}

$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
plug in  x  = 0  to find A   : 
$$
 \begin{array}{l} \\
8\cdot 0^2 -12 = (0^2 + 2\cdot  0  - 6)A  +  0 \cdot (Bx  + C)     \\
A  =  2    \\
\end{array}
$$


since $(A+  B)$ is equal to the exponent of 2 term on the left   we will make  A + B equal :  

$$
\begin{array}{l} \\
A+B = 8    \\
B   =   6
\end{array}
$$

since  $(2A +C)$ is equal to the exponent term on the left : 
$$
\begin{array}{l} \\
2A +C = 0   \\
 C =  -4 
\end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{2}{x }  +  \frac{6x      - 4}{(x^2 + 2x - 6) } 
$$








$$
\frac{3x^3 +  7x  - 4} {(x^2  + 2)^2 }
$$



The first thing we should do is factor the denominator as must as we can  .  
$$
\frac{3x^3 +  7x  - 4} {(x^2  + 2)^2 }
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{3x^3 +  7x  - 4} {(x^2  + 2)^2 } = \frac{Ax  + B}{(x^2  + 2)}  +   \frac{Cx  + D}{(x^2  + 2)^2}
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =  (x^2  + 2)^2
$$
$$
\frac{3x^3 +  7x  - 4} {(x^2  + 2)^2 } = \frac{Ax  + B}{(x^2  + 2)}  +   \frac{Cx  + D}{(x^2  + 2)^2}  =  \frac{ (x^2  + 2) (Ax + B) +  (Cx  + D) }{(x^2  + 2)^2}
$$  
We need a value A , B  and C  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
3x^3 +  7x  - 4  = (x^2  + 2) (Ax + B) +  (Cx  + D)     \\
3x^3 +  7x  - 4  = Ax^3  +  2Ax  + Bx^2  + 2B  +  Cx + D  \\
3x^3 +  7x  - 4  = Ax^3   + Bx^2  +(2A  + C )x   + 2B  + D   \\
\end{array}

$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
since A is equal to the exponent of 3  term on the left  to find A   : 
  
$$
A  =3  
$$

since   B   is equal to the exponent of 2 term on the left   we will make  B equal :  
$$
\begin{array}{l} \\
B  = 0  
\end{array}
$$

since  $(2A +C)$ is equal to the exponent term on the left : 
$$
\begin{array}{l} \\
2A +C = 0   \\
 C =  -6 
\end{array}
$$

since  $(2B  + D )$ is equal to the exponent term on the left : 

$$
\begin{array}{l} \\
2B +  D =  -4  \\
 D  =  -4 
\end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{3x  }{(x^2  + 2)}  -   \frac{6x  + 4}{(x^2  + 2)^2}
$$




# #Practice_Exercise  





$$
\frac{17x  -  53} {x^2  - 2x  - 15 }
$$



The first thing we should do is factor the denominator as must as we can  .  
$$
\frac{17x  -  53} {x^2  - 2x  - 15 } =   \frac{17x  -  53} {(x +  3)(x  - 5) }
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{17x  -  53} {x^2  - 2x  - 15 } =  \frac{A}{x + 3} +  \frac{B}{x -  5 }
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =  (x +  3)(x  - 5) 
$$
$$
\frac{17x  -  53} {x^2  - 2x  - 15 } = \frac{A}{x + 3} +  \frac{B}{x -  5 }  = \frac{A(x  - 5)  +  B(x +  3) }{(x +  3)(x  - 5)  } 
$$  
We need a value A , B  and C  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
17x  -  53  =A(x  - 5)  +  B(x +  3)    \\

\end{array}

$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A we will plug in the x  = -3   : 
  
$$
\begin{array}{l} \\
-8A  =  -104   \\
A  =  13 
\end{array}
  
$$

since   B  we will plug in the x  = 5   :  
$$
\begin{array}{l} \\
8B  =  32   \\
B =  4
\end{array}
$$

So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{13}{x + 3} +  \frac{4}{x -  5 }
$$












$$
\frac{34  - 12x  }{3x^2 - 10x  - 8}
$$



The first thing we should do is factor the denominator as must as we can  .  
$$
\frac{34  - 12x  }{3x^2 - 10x  - 8} =   \frac{34  - 12x  }{3x^2 - 10x  - 8}  =   \frac{34  - 12x  }{(x - 4)(3x   + 2 )} 
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{34  - 12x  }{(x - 4)(3x   + 2 )}    =  \frac{A}{x  -4}  + \frac{B}{3x  + 2 }
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  = (x - 4)(3x   + 2 ) 
$$
$$
\frac{34  - 12x  }{(x - 4)(3x   + 2 )} =  \frac{A}{x  -4}  + \frac{B}{3x  + 2 } =   \frac{A(3x +  2)   + B(x - 4)}{ (x - 4)(3x   + 2 ) }  
$$  
We need a value A , B  and C  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
34  - 12x  = A(3x +  2)   + B(x - 4)    \\
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A we will plug in the x  = 4   : 
  
$$
\begin{array}{l} \\
34  - 12 \cdot 4 = A(3x +  2)   + B(4 - 4)   \\
  A(3\cdot 4  +  2)  = -14  \\
A =  -1  
\end{array}
  
$$

since   B  we will plug in the x  = 5   :  
$$
\begin{array}{l} \\
34  - 12x  = A(3x +  2)   + B(x - 4)    \\
34  - 12\cdot -\frac{2}{3}  = A(3\cdot -\frac{2}{3} +  2)   + B(-\frac{2}{3} - 4)  \\
42 =  + B(-\frac{2}{3} - 4)
B =  -9  
\end{array}
$$

So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
  \frac{-1}{x  -4}  - \frac{9}{3x  + 2 }
$$













$$
\frac{125 + 4x - 9x^2 }{(x -1  ) (x + 3) (x + 4 )}
$$


The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{125 + 4x - 9x^2 }{(x -1  ) (x + 3) (x + 4 )} 
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{125 + 4x - 9x^2 }{(x -1  ) (x + 3) (x + 4 )}    = \frac{A}{x - 1} + \frac{B}{x + 3} + \frac{C}{x+4} 
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  = (x -1  ) (x + 3) (x + 4 )
$$
$$
\frac{A (x + 3) (x + 4 ) +  B(x + 4 )(x -1  )  + C(x -1  ) (x + 3)}{(x -1  ) (x + 3) (x + 4 )}
$$  
We need a value A , B  and C  so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
- 9x^2 + 4x + 125 = A (x + 3) (x + 4 ) +  B(x + 4 )(x -1  )  + C(x -1  ) (x + 3)  \\

\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A we will plug in the x  = 1    : 
  
$$
\begin{array}{l} \\
- 9\cdot  1 ^2 + 4\cdot 1 + 125 = A (1 + 3) (1 + 4 )   \\
120 = 20A   \\
A =  6 
\end{array}
$$

since   B  we will plug in the x  = -3   :  
$$
\begin{array}{l} \\
- 9(-3)^2 + 4\cdot  -3  + 125 =   B(-3 + 4 )(-3 -1  )   \\
-4B  =  32   \\
B =  - 8  
\end{array}
$$

since   B  we will plug in the x  = -4   :  
$$
\begin{array}{l} \\
- 9(-4)^2 + 4\cdot -4 + 125 =  C(-4 -1  ) (-4 + 3)  \\
5C  =  -35   \\
C=  - 7 
\end{array}
$$



So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
\frac{6}{x - 1} - \frac{8}{x + 3} - \frac{7}{x+4} 
$$















$$
\frac{6x + 5}{(2x -1)^2 }
$$

The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{6x + 5}{(2x -1)^2 }
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{6x + 5}{(2x -1)^2 }  =   \frac{A}{(2x-  1 )}   + \frac{B}{(2x - 1)^2}  
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  = (2x-  1 )(2x-  1 )^2  
$$
$$
\frac{A(2x  - 1) +B }{ (2x-  1 )(2x-  1 )^2  }
$$  
We need a value A , B   so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
6x + 5 = A(2x  - 1) +B 
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find B we will plug in the x  = 1/2     : 
  
$$
\begin{array}{l} \\
6\cdot \frac{1}{2 } + 5 = A\left( 2\cdot  \frac{1}{2}  - 1 \right) +B    \\
B    =   8 
\end{array}
$$


since   A  we will plug in the x  = 0     :  
$$
\begin{array}{l} \\
6\cdot  0  + 5  = A(2 \cdot  0   - 1) +  8     \\
A    =   3  \end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{3}{(2x-  1 )}   + \frac{8}{(2x - 1)^2}  
$$













$$
\frac{7x^2  - 17x + 38}{(x + 6) (x -1 )^2}  
$$


The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{7x^2  - 17x + 38}{(x + 6) (x -1 )^2}  
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{7x^2  - 17x + 38}{(x + 6) (x -1 )^2}   =  \frac{A}{x + 6}  + \frac{B}{(x -1 )}  \frac{C}{(x -1 )^2}    
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =(x + 6) (x -1 )^2 
$$
$$
\frac{A(x -1 )^2 +  B(x + 6) (x -1 ) +  C (x + 6) }{(x + 6) (x -1 )^2}
$$  
We need a value A , B   so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
7x^2  - 17x + 38 = A(x -1 )^2 +  B(x + 6) (x -1 ) +  C (x + 6)
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find B we will plug in the x  = -6     : 
  
$$
\begin{array}{l} \\
7\cdot  (-6)^2  - 17\cdot  -6 + 38   =  49A  \\
A    =    8  
\end{array}
$$


since   C  we will plug in the x  = 1     :  
$$
\begin{array}{l} \\
7\cdot 1^2  - 17\cdot 1  + 38    =  7C \\
C    =    4   
\end{array}
$$

since   C  we will plug in the x  = 1     :  
$$
\begin{array}{l} \\
7\cdot  0 ^2  - 17\cdot 0  + 38   = 8(0 -1 )^2 +  B(0 + 6) (0 -1 ) +  4 (0 + 6)\\
B   =    -1    
\end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
\frac{8}{x + 6}  - \frac{1}{(x -1 )} +    \frac{4}{(x -1 )^2}    
$$










$$
\frac{4x^2  -22 x +  7 }{(2x  + 3 ) (x - 2 )^2 }  
$$


The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{4x^2  -22 x +  7 }{(2x  + 3 ) (x - 2 )^2 }  
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{4x^2  -22 x +  7 }{(2x  + 3 ) (x - 2 )^2 }    =  \frac{A}{(2x  + 3 )}  + \frac{B}{(x - 2 )} +    \frac{C}{(x - 2 )^2}    
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =(2x  + 3 ) (x - 2 )^2
$$
$$
\frac{A(x - 2 )^2 +  B(2x  + 3 ) (x - 2 )+  C (2x  + 3 ) }{(2x  + 3 ) (x - 2 )^2}
$$  
We need a value A , B   so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
4x^2  -22 x +  7  = A(x - 2 )^2 +  B(2x  + 3 ) (x - 2 )+  C (2x  + 3 )
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A we will plug in the x  = $-\frac{3}{2}$    : 
  
$$
\begin{array}{l} \\
4\left( -\frac{3}{2} \right)^2  -22 \cdot -\frac{3}{2} +  7  = A\left( -\frac{3}{2} - 2  \right)^2 \\  
A \frac{49}{4}   =    49   \\
A   = 4   
\end{array}
$$


since   C   we will plug in the x  =   2   :  
$$
\begin{array}{l} \\
 4(2)^2  -22 \cdot 2 +  7  =  C (2 \cdot 2  + 3 ) \\
C    =    -3   
\end{array}
$$

since   B  we will plug in the x  = 0   :  
$$
\begin{array}{l} \\
4 \cdot 0^2  -22\cdot 0  +  7  = 4(0 - 2 )^2 +  B(2\cdot 0  + 3 ) (0- 2 )+   -3 (2\cdot 0   + 3 )   \\
B =  0   
\end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{4}{(2x  + 3 )} -    \frac{3}{(x - 2 )^2}    
$$









$$
\frac{3x^2  +  7x +  28 }{x (x^2 +x + 7 ) }  
$$


The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{3x^2  +  7x +  28 }{x (x^2 +x + 7 ) }  
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{3x^2  +  7x +  28 }{x (x^2 +x + 7 ) }    =  \frac{A}{x}  +  \frac{Bx + C }{x^2 +x + 7}
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  = x (x^2 +x + 7 )
$$
$$
\frac{A(x^2 +x + 7 ) + x ( Bx +  C ) }{x (x^2 +x + 7 )}
$$  
We need a value A , B   so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
3x^2  +  7x +  28  =A(x^2 +x + 7 ) + x ( Bx +  C )   \\
3x^2  +  7x +  28  =Ax^2 +Ax + 7A   +  Bx^2  + Cx  \\
3x^2  +  7x +  28  = x^2 (A   + B )  +x(A+ C )   + 7A    
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A  by  comparing it with the constant on the left  : 
  
$$
\begin{array}{l} \\
7A  =   28   \\
A  =   4
\end{array}
$$


  to  find (A   + B )    by  comparing it with the term with exponent of 1  on the left  :  
$$
\begin{array}{l} \\
 B  +  4  =   3\\
B    =  -1
\end{array}
$$

since   (A+ C )     by  comparing it with the term with exponent of 2  on the left   :  
$$
\begin{array}{l} \\
4  + C   = 7  \\
C =   3    
 \end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{4}{x}  +  \frac{-x + 3 }{x^2 +x + 7}
$$












$$
\frac{4x^3  + 16x +  7 }{(x^2  + 4)^2 }  
$$


The first thing we should do is factor the denominator as must as we can  .  

$$
\frac{4x^3  + 16x +  7 }{(x^2  + 4)^2 } 
$$

so  by seeing the result above a partial decomposition is just : 
$$
\frac{4x^3  + 16x +  7 }{(x^2  + 4)^2 }    =  \frac{Ax + B}{(x^2 + 4)} + \frac{Cx + D}{(x^2 + 4)^2}  
$$

now we need to find a common denominator  in the function on the right in order to find the solution where both  the numerator are equal  . to add a rational expression  we need to make sure that the denominator are the same by multiplying it with a LCD  : 
$$
LCD  =(x^2  + 4)^2 
$$
$$
\frac{(Ax + B)(x^2  + 4) + Cx + D   }{(x^2  + 4)^2 }
$$  
We need a value A , B   so that the numerator for the value on the left is the same for the numerator for the value on the right . 
$$
\begin{array}{l} \\
4x^3  + 16x +  7   =(Ax + B)(x^2  + 4) + Cx + D    \\
4x^3  + 16x +  7   =Ax^3 +   Bx^2  +  4Ax +  4B +    Cx + D    \\
4x^3  + 16x +  7   =Ax^3 +   Bx^2  + x(4A +C)  +  4B  + D   \\ 
\end{array}
$$
so there are many possible x that we can  plug in but to make this easy we will plug in a x  that will make either B or A or C  disappear so that we can find the other variable 
to  find A  by  comparing it with the term exponent 3  on the left  : 
  
$$
\begin{array}{l} \\
7A  =   28   \\
A  =   4
\end{array}
$$


  to  find (A   + B )    by  comparing it with the term with exponent of 1  on the left  :  
$$
\begin{array}{l} \\
 B  +  4  =   7\\
B    =    3
\end{array}
$$

since   (A+ C )     by  comparing it with the term with exponent of 2  on the left   :  
$$
\begin{array}{l} \\
4  + C   = 7  \\
C =   3    
 \end{array}
$$


So  by correctly  finding x we manage to get the value A , B and C   we will now plug them in : 
$$
 \frac{4}{x}  +  \frac{3x + 3 }{x^2 +x + 7}
$$
