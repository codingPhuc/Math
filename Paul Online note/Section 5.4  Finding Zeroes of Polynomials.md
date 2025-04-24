---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/FindingZeroesOfPolynomials.aspx
Current date: 2025-04-24
---

We've been talking about  zeroes of polynomial and why we need them for a couple of section now . We haven't , however , really talk about them for polynomial greater than 2 
. In Addition  in this section we will give a process that will find all rational (_i.e._ integer or fractional) zeroes of a polynomial  . We will providing a process that work if the number of rational zeros solutions >=2, if the number of rational zeros solution < 2  this process will not work 


## Rational Root Theorem 
if the rational number $x=\frac{b}{c}$ is a zero of the $n^{th}$ degree polynomial   
$$
 P (x  )  = sx^n + \dots + t 
$$
where all coefficients are integer then b will be a factor of t and c will be a factor of s 
Note that the  zero must be reduce to the lowest term in order for this to work 

verify that the root of the following polynomial satisfy the  rational root theorem : 
$$
P (x )  = 12 x^3 -  41x^2 - 38 x  + 40  = (x  - 4) (3x - 2) (4x + 5 )
$$

$$
\begin{array}{l}
x = \frac{2}{ 3}   \\
x  = -\frac{5}{4}  \\  \\
x = \frac{4}{1}
\end{array}
$$
we then check if the zeros solution denominator will be a factor of s and the numerator will be a factor of t 
$t =  40=2\cdot 2\cdot 2\cdot 5$ 
$s = 12=3\cdot 4$
$s = 12=-3\cdot-4$
since the numerator and denominator of the two solution are factor of t and s we concluded that the polynomial satisfy the  rational root theorem

This theorem is important because it allow us to find out the number of combination for zeros solution rational number and it let us verify the rational number solution 

$$
\begin{array}{l} \\
P(x) = x^4 -7x^3 + 17x^2 - 17x + 6     \\
\end{array}
$$

what this is saying that if $x=\frac{b}{c}$ is to be a zero of $P(x)$ then  b must be a factor of 6 and c must be a factor of 1 . Also we cannot forget negative factor 
all possible factor of 1 and 6  . Here they are  : 
$$
\begin{array}{l} \\
t = 6  =  \pm 1   ;  \pm 2   ; \pm 3 ; \pm 6 \\
s = 1    = \pm 1   
\end{array}
$$

Now list all the possible solution to factor the numerator and denominator  . We need to first simply the faction as must as possible then apply the $\pm$ sign  .  Note The possible rational zeros are just simplified fractions where the **numerator is a factor of the constant term** and the **denominator is a factor of the leading coefficient**   , in other word you just need to make sure b and c belong to the list of possible faction of t and s 
so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }  = \pm 1    \\
\frac{\pm 2}{\pm 1 }  = \pm 2 \\
\frac{\pm 3}{\pm 1 }  = \pm 3 \\
\frac{\pm 6}{\pm 1 }  = \pm 6 \\

\end{array}
$$
so it look like we will have 8 possible rational zero 
$$
\begin{array}{l} \\
P(x)  =   2x^4 + x^3 + 3x^2 +  3x - 9   \\

\end{array}
$$ 
the factor of t and s is : 
$$
\begin{array}{l} \\
t = -9  =  \pm 1     ; \pm 3 ; \pm 9  \\
s = 2    =  \pm 1  ;  \pm 2   
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 2 }   \\
\frac{\pm 3}{\pm 2 }   \\
\frac{\pm 9}{\pm 2 } \\
\frac{\pm 1 }  {\pm 1} \\
\frac{\pm 3 } {\pm 1} \\
\frac{\pm 9 } {\pm 1}
\end{array}
$$

#Fact 
	If $P(x)$ is a polynomial and we know that  P(a ) > 0 and P(b) < 0 then somewhere between a and b is a zero of P(x)  . 
	What is this telling us is that if we evaluate the one point and it above the x-axis and evaluate another point causing it to be bellow the x-axis  then there must be a point that cross the x-axis where the equation y is zero 
note however this this fact does not tell us what the zero is it just tell us that there exist a zero if one result of the equation is negative while the other is positive 
##  Process for finding Rational Zeros 
1. use the rational root theorem to list all possible rational zeroes of the polynomial $P( x)$
2. we will try the number  we get in the first step until one of them create a solution for us.  Let suppose the zero is  $x=r$ , then we will know that it's a zero because $P(r) =0$ . Once this has been determined that it is  in fact a zero write the original polynomial as  $$
P(x) =  (x - r)  Q(x )
$$
3. repeat the process using $Q(x)$ this time instead of P(x .) This repeating will continue until we reach a second degree polynomial . At this point  we can solve this directlly for the remaining  zeroes 

To simplify the second step we will use synthetic division . This will simplify our life in several way . [[Section 5.1  Dividing Polynomials]] 

also , in the evaluate step it is usually easiest to evaluate at the possible integer zeroes first and then go back and deal with any fractions if we have to 

Determine all the zeroes of $P(x) =x^4 -   7x^3+17x^2  - 17x + 6$   


the factor of t and s is : 
$$
\begin{array}{l} \\
t = 6  =  \pm 1     ;   \pm 2  ;  \pm 3    ; \pm 6  \\
s = 1   =  \pm 1   
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 2}{\pm 1 }     =  \pm 2   \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 4 }  {\pm 1}  =  \pm 4  \\
\frac{\pm 5 } {\pm 1}   =  \pm 5 \\
\frac{\pm 6 } {\pm 1}  =  \pm 6 
\end{array}
$$
$$
f(1 )  =  1 -  7  + 17  -  17 +  6 =   0  
$$
so we will have one solution f(1) that cause the equation to be zero 


$$
\text{Divide } x^4 -   7x^3+17x^2  - 17x + 6  \text{ by }  x   -  1     
$$
$$
1 \mid 1 \; -7 \;  17 \; -  17  \;  6      
$$

we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 

|     | 1   | -7  | 17  | -17 | 6                    |
| --- | --- | --- | --- | --- | -------------------- |
| -1  | 1   | -8  | 25  | -43 | $48  =P(-1)  \neq 0$ |
| 1   | 1   | -6  | 11  | -6  | $0  =P(1)  \neq 0$   |

$$
(  x^3  -  6x^2  + 11x - 6     )(x   - 1 )
$$ 

the factor of t and s is : 
$$
\begin{array}{l} \\
t = -6  =  \pm 1     ;   \pm 2  ;  \pm 3    ; \pm 6  \\
s = 1   =  \pm 1   
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  1  \\
\frac{\pm 2}{\pm 1 }     =  \pm 2   \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 4 }  {\pm 1}  =  \pm 4  \\
\frac{\pm 5 } {\pm 1}   =  \pm 5 \\
\frac{\pm 6 } {\pm 1}  =  \pm 6 
\end{array}
$$
since we already found out that -1  is not a zero solution for $P(x)$ we do not need to calculate it here  
$$
f(1 )  = 1^3  -  61^2  + 111 - 6    =   0  
$$



$$
\text{Divide } x^3  -  6x^2  + 11x - 6   \text{ by }  x   -  1     
$$
$$
1 \mid 1 \; -6 \;  11 \; -  6        
$$

| 1   | 1   | -6  | 11  | -6  |
| --- | --- | --- | --- | --- |
|     |     | 1   | -5  | 6   |
|     | 1   | -5  | 6   | 0   |

$$
( x^2   - 5x   +  6 )(x   - 1 )^2   =  (x - 3)(x - 2  )(x - 1 )^2 
$$

Before moving on to the next example let's also note that we can now completely factor the polynomial 
$$
P(X)    = x^4 - 7x^3 + 17x^2  - 17x + 6 
$$
we know for each zero solution , we will be given the corresponding factor form and that each exponent in the factor form is the multiplicity of that zero 










Determine all the zeroes of $P(x) =   2x^4 + x^3 + 3x^2 + 3x-9$   

the factor of t and s is : 
$$
\begin{array}{l} \\
t =  \pm 1     ;  \pm 3    ; \pm 9   \\  \\
s = 2  =  \pm 1      ;  \pm 2    
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 9 } {\pm 1}  =  \pm 9   \\
 \pm \frac{ 1}{ 2 }    \\
\pm \frac{ 3}{ 2 }  \\ 
\pm \frac{ 9 } { 2}  
\end{array}
$$

we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 

|     | 2   | 1   | 3   | 3   | -9                  |
| --- | --- | --- | --- | --- | ------------------- |
| -1  | 2   | -1  | 4   | -1  | $2  =P(-1)  \neq 0$ |
| 1   | 2   | 3   | 6   | 9   | $0  =P(1)  \neq 0$  |

$$
(  2x^3    + 3x^2  +  6x  +  9   )(x   - 1 )
$$ 

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 9 =  \pm 1     ;  \pm 3    ; \pm 6  \\
s = 2   =  \pm 1    ;  \pm 2 
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  1  \\
\frac{\pm 3}{\pm 1 }     =  \pm 3   \\
\frac{\pm 9}{\pm 1 }   =  \pm 9 \\  \\

 \pm \frac{ 1}{ 2 }    \\
\pm \frac{ 3}{ 2 }  \\ 
\pm \frac{ 9 } { 2}  
\end{array}
$$
since we already found out that -1  is not a zero solution for $P(x)$ we do not need to calculate it here  

|                | 2   | 3   | 6   | 9                                     |
| -------------- | --- | --- | --- | ------------------------------------- |
| 1              | 2   | 5   | 11  | $20  =P(1)  \neq 0$                   |
| -3             | 2   | -3  | 12  | $-27  =P(1)  \neq 0$                  |
| -9             | 2   | -15 |     | $P(-9)  \neq 0$                       |
| $\frac{1}{2}$  | 2   | 4   | 8   | $P\left( \frac{1}{2} \right)  \neq 0$ |
| $-\frac{3}{2}$ | 2   | 0   | 6   | $P(-\frac{3}{2})  = 0$                |

$$
( 2x^2  + 6  )( 2x + 3  ) (x   - 1 )   
$$
since  
$$
\begin{array}{l} 
2x^2  + 6   =  0    \\
x    = \pm \sqrt{ 3 }  i 
\end{array}
$$
we will have simple  2 zero solution that is  
$$
-\frac{3}{2 }    ;  1  
$$
and two imaginary solution 
$$
 \sqrt{  3 }  ,   - \sqrt{ 3 }
$$







# #Practice_Exercise  

$$
f(x )  =  2x^3  - 13x^2  + 3x + 18 
$$

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 18  =   \pm 1   ;  \pm 2      ;  \pm 3     ;  \pm 6     ;    \pm     9 ; \pm 18    \\  \\
s = 2  =  \pm 1      ;  \pm 2    
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 9 } {\pm 1}  =  \pm 9   \\ \\
\frac{\pm 2}{\pm 1 }   =  \pm 2  \\
\frac{\pm 6}{\pm 1 }   =  \pm 6 \\
\frac{\pm 18 } {\pm 1}  =  \pm 18   \\
 \pm \frac{ 1}{ 2 }    \\
\pm \frac{ 3}{ 2 }  \\ 
\pm \frac{ 9 } { 2}   \\
\pm \frac{ 6}{ 2 }    = \pm  3  \\ 
\pm \frac{ 18 } { 2}    = \pm 6
\end{array}
$$
$$
f(x )  =  2x^3  - 13x^2  + 3x + 18 
$$
we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 

|     | 2   | -13 | 3   | 18                 |
| --- | --- | --- | --- | ------------------ |
| -1  | 2   | -15 | 18  | $0 =P(-1)  = 0$    |


$$
(  2x^2   - 15x  + 18   )(x   +  1 )  = (x   - 6)(2x  - 3)(x +1)
$$ 
so there are three simple zeros  in the solution that is : 
$$
6  ; x = \frac{3}{2}    ; x  =-1  
$$









Determine all the zeroes of $P(x) =   x^4  - 3x^3  - 5x^2 + 3x + 4$   

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 4 =   \pm 1     ;  \pm 2  ;  \pm 4   \\  \\
s = 1  =  \pm 1        
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 2}{\pm 1 }   =  \pm 2 \\
\frac{\pm 4 } {\pm 1}  =  \pm  4  \\

\end{array}
$$

we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 

|     | 1   | -3  | -5  | 3   | 4                  |
| --- | --- | --- | --- | --- | ------------------ |
| -1  | 1   | -4  | -1  | 4   | $0  =P(4)  = 0$    |


$$
(  x^3  - 4x^2 - x  + 4 )(x   +  1 )
$$ 

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 4 =   \pm 1     ;  \pm 2  ;  \pm 4   \\ 
s = 1  =  \pm 1   
\end{array}
$$



so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  -1  \\
\frac{\pm 3}{\pm 1 }     =  \pm 3   \\
\frac{\pm 4}{\pm 1 }   =  \pm 4 \\ 
\end{array}
$$


|     | 1   | -4  | -1  | 4   |
| --- | --- | --- | --- | --- |
| 1   | 1   | -3  | -4  | 0   |


$$
(x^2  -3x  -4 )(x -  1)(x+ 1 )  = (x-4)(x  -1  )(x + 1 )^2

$$

we will have simple 2  zero solution that is  
$$
x  = 4  ; x  = 1  
$$
and  one zero solution with the multiplicity of 2 
$$
x =  -1  
$$









Determine all the zeroes of $P(x) =   2x^4  - 7x^3 - 2x^2 + 28x - 24$   

the factor of t and s is : 
$$
\begin{array}{l} \\
t = -24  =   \pm 1     ;  \pm 2   ; \pm 3  ;  \pm 4   ; \pm 6  ;  \pm 8   ;  \pm 12  ;  \pm   24  \\
s = 2  =  \pm 1       ;  \pm 2   
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 2}{\pm 1 }   =  \pm 2 \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 4 } {\pm 1}  =  \pm  4  \\   
\frac{\pm 6}{\pm 1 }   =  \pm 6  \\
\frac{\pm 8}{\pm 1 }   =  \pm 8 \\
\frac{\pm 12  } {\pm 1}  =  \pm  12  \\   
\frac{\pm 24  } {\pm 1}  =  \pm  24  \\
\frac{\pm 1}{\pm 2 } \\
\frac{\pm 3}{\pm 2 }   \\

\end{array}
$$

we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 
$P(x) =   2x^4  - 7x^3 - 2x^2 + 28x - 24$   

|     | 2   | -7  | -2  | 28  | -24             |
| --- | --- | --- | --- | --- | --------------- |
| 2   | 2   | -3  | -8  | 12  | $0  =P(2)  = 0$ |


$$
(  2x^3  - 3x^2 - 8 x  + 12 )(x     - 2   )
$$ 

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 12=    \pm 1     ;  \pm 2   ; \pm 3  ;  \pm 4   ; \pm 6  ;  \pm 8   ;  \pm 12   \\
s = 2  =  \pm 1    ; \pm 2    
\end{array}
$$



so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 2}{\pm 1 }   =  \pm 2 \\
\frac{\pm 3}{\pm 1 }   =  \pm 3 \\
\frac{\pm 4 } {\pm 1}  =  \pm  4  \\   
\frac{\pm 6}{\pm 1 }   =  \pm 6  \\
\frac{\pm 8}{\pm 1 }   =  \pm 8 \\
\frac{\pm 12  } {\pm 1}  =  \pm  12  \\   
\frac{\pm 1}{\pm 2 } \\
\frac{\pm 3}{\pm 2 }   \\
\end{array}
$$

$$
(  2x^3  - 3x^2 - 8 x  + 12 )(x     - 2   )
$$

|     | 2   | -3  | -8  | 12              |
| --- | --- | --- | --- | --------------- |
| 2   | 2   | 1   | -6  | $0  =P(2)  = 0$ |


$$
(2x^2  +  x -  6)(x - 2)^2   =  ( x   + 2 )( 2x  - 3 )(x - 2)^2   

$$

we will have simple 2  zero solution that is  
$$
 x  = -\frac{2}{3}  ;  x  =2  
$$
and  one zero solution with the multiplicity of 2
$$
x =  -2 
$$











Determine all the zeroes of $P(x) =   8x^5+36x^4+46x^3+7x^2−12x−4$   

the factor of t and s is : 
$$
\begin{array}{l} \\
t  = -4   =       \pm 1     ;  \pm 2    ;  \pm 4           \\
s =8  =   \pm 1     ;  \pm 2    ;  \pm 4  ;  \pm 8 
\end{array}
$$


so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\
\frac{\pm 1}{\pm 1 }   =  \pm 1  \\
\frac{\pm 2}{\pm 1 }   =  \pm 2 \\
\frac{\pm 4 } {\pm 1}  =  \pm  4  \\   
 \frac{\pm 1}{\pm 8}   =  \pm \frac{1}{8}  \\
\frac{\pm 2}{\pm 8}   =  \pm \frac{1}{4} \\
\frac{\pm 4 } {\pm 8}  =  \pm  \frac{1}{2 }  \\   
\end{array}
$$

we will now do the synthetic calculation zero this time dropping the middle row for quicker syntax 
$P(x) =   8x^5+36x^4+46x^3+7x^2−12x−4$   

|     | 8   | 36  | 46  | 7   | -12 | -4  |
| --- | --- | --- | --- | --- | --- | --- |
| -2  | 8   | 20  | 6   | -5  | -2  | 0   |


$$
(  8x^4   + 20x^3 +  6x^2 -  5x- 2  )(x     +  2   )
$$ 

the factor of t and s is : 
$$
\begin{array}{l} \\
t = -2 =   \pm 2    \\
s = 8    =  \pm 2   ;   \pm 4   ;   \pm 8  
\end{array}
$$



so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\

\frac{\pm 8}{\pm 2 }   =  \pm 4\\
\frac{\pm 4 } {\pm 2}  =  \pm  2  \\   
\frac{\pm 2}{\pm 8}   =  \pm \frac{1}{4} \\
\frac{\pm 4 } {\pm 8}  =  \pm  \frac{1}{2 }  \\   
\end{array}
$$


$$
(  8x^4   + 20x^3 +  6x^2 -  5x- 2  )(x     +  2   )
$$

|     | 8   | 20  | 6   | -5  | -2  |
| --- | --- | --- | --- | --- | --- |
| +2  | 8   | 4   | -2  | -1  | 0   |


$$
(8x^3  +  4x^2 - 2x  - 1 )(x + 2)^2   

$$

the factor of t and s is : 
$$
\begin{array}{l} \\
t = 1  \\
s = 8    =  \pm 2   ;   \pm 4   ;   \pm 8  
\end{array}
$$



so the list of  possible rational zeros of this polynomial is : 
$$
\begin{array}{l} \\

\frac{\pm 1}{\pm 2 }   =  \pm 4\\
\frac{\pm 1} {\pm 4}  =  \pm  2  \\   
\frac{\pm 1}{\pm 8}   =  \pm \frac{1}{4} \\ 
\end{array}
$$

$$
(8x^3  +  4x^2 -2x  -  1 )(x + 2)^2   

$$ 


|      | 8   | 4   | -2  | -1  |
| ---- | --- | --- | --- | --- |
| -0.5 | 8   | 0   | -2  | 0   |

$$
\left( x-\frac{1}{2} \right)(x+ 2)^2(8x^2 -  2 )     = \left( x-\frac{1}{2} \right)(x-2)^2\left( 2x+\frac{1}{2} \right)\left(  2x  - \frac{1}{2} \right)
$$
