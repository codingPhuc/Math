---
title: Adjunction
references: https://www.youtube.com/watch?v=T0HyWIFbsHQ
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/SolveQuadraticEqnsII.aspx
Current date: 2025-03-12
---

# #definition  
In  section  [[Section 2.5  Quadratic Equations - Part I]]  we look  at solving  Quadratic equation using square root method  and  factoring method . But this have it own  problem  ,  not all equation  can be apply these two method 
In this section  we will look at two method the first is **completing the square**  and the   quadratic  formula  for solving  the equation 

$$ax^2+bx+c=0\; a≠0$$
## Completing the Square 
The process  call completing the Square  ,  like it suggest need to  completed  the square inorder to solve the equation  .  So  let first  define what completing the square is   
$$x^2  + bx $$ 
we  notice that the  x^2  have a coefficient  of one .  That is require  in order to do this     .  Now  ,  to this let add $\left( \frac{b}{2} \right)^2$ doing this give the following **factorable**  equation  


$$x^2  + bx  +  \left( \frac{b}{2} \right)^2  =  \left( x + \frac{b}{2} \right)^2 $$ this process  is call  **completing the square** 

$$ x^2 -   16x + 64      =  ( x -   8  )^2    $$ 

$$y^2   +  7y + \frac{49}{4}  = \left( x +  \frac{7}{2} \right)^2$$ 
## example   2 used  completing the square to solve the  following  quadratic  equation 
 
$$x^2  -   6x  + 1  =  0   $$
 **Step 1** **:** Divide the equation by the coefficient of the _x2_ term. Recall that completing the square required a coefficient of one on this term and this will guarantee that we will get that. We don’t need to do that for this equation however.  

$$x^2  -   6x   =  -1     $$
**Step 2 :** Set the equation up so that the xx’s are on the left side and the constant is on the right side.
$$x^2  -   6x + \left(   -\frac{6}{ 2 } \right)^2   =  -1  +   9     $$
**Step 3 :** Complete the square on the left side. However, this time we will need to add the number to both sides of the equal sign instead of just the left side. This is because we have to remember the rule that what we do to one side of an equation we need to do to the other side of the equation.  
$$x^2  -   6x + 9  =  -1  +   9     $$
**Step 4 :** Now, at this point notice that we can use the square root property on this equation. That was the purpose of the first three steps. Doing this will give us the solution to the equation. 
$$
\begin{array}  {l} 
(x    -  3)^2  =    8   \\
 x   -   3  =  \pm  2\sqrt{ 2 }  \\
x    =    \pm  2\sqrt{ 2 }  +  3   \\
\end{array} 
     $$

	
$$
\begin{array}  {l} 
2x^2   + 6x  +  7   =  0      \\
2x^2   + 6x    =   -  7\\
2x^2   +   6x    = -7    \\
x^2   +   3x    = -\frac{7}{2}  \\
  x^2   +   3x   +   \frac{9}{4}  = -\frac{7}{2}  +   \frac{9}{4}    \\
\left( x  +  \frac{3}{2} \right)^2    =  -\frac{5}{4}     \\
  x  +  \frac{3}{2}       =  \pm \sqrt{ \frac{5}{4}     }\cdot i    \\
x =    \pm \sqrt{ \frac{5}{4}       }\cdot i       - \frac{3}{2} 
\end{array} 
     $$

		
$$
\begin{array}  {l} 
3x^2   -  2x  -    1  =  0      \\
3x^2   -  2x =    1\\
x^2     -  \frac{2}{3} x   =   \frac{1}{3}   \\
x^2     -  \frac{2}{3} x  +    \left( -  \frac{1}{ 3 } \right)^2      =   \frac{1}{3}   +    \left( -  \frac{1}{ 3 } \right)^2   \\
\left( x - \frac{1}{3}  \right)^2     =  \frac{4}{9} \\
 x - \frac{1}{3}     = \pm   \frac{2}{3  } \\
x  =    \pm \frac{2}{3} +   \frac{1}{3} 
 \end{array} 
     $$


completing  the square is a long process  that can cause a lot of mistake   .  So  , we rarely actually used it  to solve  problem   

##  Quadratic Formula 
this is the final  solution to solving quadratic equation  an will always work  and you can remember the formula as well  

$$ax^2     +    bx     + c     =  0  $$
first  we must  have quadratic  equation in the standard form as noted  above 


$$x^2     +    \frac{bx}{a}     + \frac{c}{a}     =  0  $$
 then we need to divide both side by   a  to get a coefficient  of  one o n  the $x^2$  term  
 $$x^2     +    \frac{bx}{a}    =    - \frac{c}{a}      $$
 next the constant need to be move to the right side of the equation  
$$
\left( \frac{b}{2a} \right)^2  =      \frac{b^2}{4a^2} 
$$
now we need to compute the number needed to complete  the square  .  This is one half the coefficient  of  x  
 $$x^2     +    \frac{bx}{a}  +  \frac{b^2}{4a^2}    =    \frac{b^2}{4a^2}    - \frac{c}{a}      $$
  $$  \left( x  + \frac{b}{2a} \right)^2    =    \frac{b^2}{4a^2}    - \frac{4ac}{4a^2}      $$ 
 
now add the   number needed to complete the square to both side of the equation    . Then used  the common  denominator on the right  side to simplify thing  

$$   x  =    \pm  \frac{\sqrt{ b^2 - 4ac }  }{2a^2}        - \frac{b}{2a}     $$ 
solve for x we also  simply  the square root a little 

$$   x  =    \pm  \frac{\sqrt{ b^2 - 4ac   }   -  b  }{2a^2}      $$
As a last step we will notice that we’ve got common denominators on the two terms and so we’ll add them up. Doing this gives,

## used the quadratic  formula to solve  each of the following 


$$x^2   + 2x    = 7     \implies  x^2   + 2x   -7   =  0 $$ 
we will have    a as  1   ,  b  as  2 and  c  as     - 7
so when plug into the formula  x will be  
$$   x  =    \pm  \frac{\sqrt{ 2^2 - 4\cdot 1 \cdot  -7     }   -  2  }{2}    \implies  \pm 2\sqrt{ 2 }  - 1   $$
$$3q^2    + 11    = 5q     \implies  3q^2  - 5q     + 11    =    0   $$ 
we will have    a as  3   ,  b  as  -5 and  c  as    11 
so when plug into the formula  x will be  
$$    x  =    \pm  \frac{\sqrt{ (-5)^2 - 4\cdot 3  \cdot  11     }    +  5    }{2\cdot 3^2}  \implies  \pm 2\sqrt{ 2 }  - 1   $$