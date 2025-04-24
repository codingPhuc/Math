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
2. Evaluate the polynomial  at the number from the first step  until we find a zero  .  Let suppose the zero is  $x=r$ , then we will know that it's a zero because $P(r) =0$ . Once this has been determined that it is  in fact a zero write the original polynomial as  $$
P(x) =  (x - r)  Q(x )
$$
3. repeat the process using $Q(x)$ this time instead of P(x .) This repeating will continue until we reach a second degree 