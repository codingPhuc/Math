---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/ZeroesOfPolynomials.aspx
Current date: 2025-04-22
---

Root of zero  of a polynomial is . We say that $x=r$  is a root of zero of a polynomial , $P(x)$ if $P(r)=0$ . In other word  $x=r$ is a root of 0 polynomial  if it is a solution to the equation $P(x)=0$ 

In the next section we need to find all zeros for the given polynomial . So , before that we need to get some idea out of the way regarding zeroes of a polynomials that will help us in that process 


The process for finding root of zero amount to nothing more than solving the equation $P(x)=0$ and we know how to do that for second degree(quadratic) polynomials . So, to help illustrate some of the idea we will be doing some example : 
Let's  first find the zeros  for  $P(x) =x^2 + 2x  - 15$ to do this we simply solve the following equation 

$$
\begin{array}{l } 
x^2 + 2x  - 15   = 0 \\
(x + 5) (x - 3 )   = 0  \\
\left\{  \\
 \begin{array}{l} 
x=  -5   \\
x =  3 \\
\end{array}
 \right.
\end{array}

$$
So , this second degree have two zero roots  . 

Now , let's find the zeros for $P(x) =x^2 -14x+49$ that will mean solving , 
$$
\begin{array}{l}   
x^2  -  14x   +  49  \\
\left \{ \\
 \begin{array}{l}
(x - 7)^2 =   0   \\
x  =  7  
\end{array}
  \right. \\
\end{array}
$$
So ,  this second degree polynomial has a single zero or root . Also recall that when we first looked at these we called a root like this a double root  
We solve each of these by factoring then  use  the zero factor properties on the factor form .  When we first look at the zero factor properties if the produce of the two term was zero then one of the term have to be zero to start of with 

Let take a look at a couple of these 
## Find the zeroes of each of the following polynomials 
$$
P(x)=5x^5−20x^4+5x^3+50x^2−20x−40=5(x+1)^2(x−2)^3
$$
$$
\begin{array}{l} \\
\left\{  \\
 \begin{array}{l} 
(x + 1)^2  =  0  \\
(x - 2)^2  =   0  
\end{array} 

 \right.
 \\
\left\{  \\
 \begin{array}{l} 
x  = -1  \\
x =  2  
\end{array} 

 \right.

\end{array}

$$ 




$$
Q(x)=x^8−4x^7−18x^6+108x^5−135x^4=x^4(x−3)^3(x+5)
$$
$$
\begin{array}{l} \\
\left\{  \\
 \begin{array}{l} 
(x + 5)^2  =  0  \\
(x - 3)^2  =   0    \\
x^4  =  0 
\end{array} 

 \right.
 \\
\left\{  \\
 \begin{array}{l} 
x  = -5  \\
x =  3   \\
x  =  0  
\end{array} 

 \right.

\end{array}

$$ 


$$
R(x)=x^7+10x^6+27x^5−57x^3−30x^2+29x+20=(x+1)^3(x−1)^2(x+5)(x+4)
$$
$$
\begin{array}{l} \\
\left\{  \\
 \begin{array}{l} 
(x +  1 )^3 =  0   \\
(x  - 1 )^2   =  0   \\
(x  + 5 )  =  0   \\
(x+  4)  = 0 
\end{array} 

 \right.
 \\
\left\{  \\
 \begin{array}{l} 
x  = -1   \\
x =  1  \\
x  =  -5   \\
x =   -4   
\end{array} 

 \right.

\end{array}

$$
Now , we've got some terminology out of the way .  If is a zero of a polynomial and the exponent on the term that produced the root is  k , then we have to say that r has a multiplicity of k  . Zero with a multiplicity of 1 are often called simple zero 
For example , the polynomial $P(x) =  x^2-10x+25=(x-5)^2$ will have one zero , x = 5 , and its multiplicity is 2 . In some way we can think of this zero occurring twice in the lists of all zeroes since we could write the polynomials as 

$$
 P(x)  = x^2  - 10x  + 25  = (x - 5)(x - 5)
$$
Written this way the term $x-5$ show up twice and each term gives the same zero , x = 5  . Saying that the multiplicity of a zero is k just a shorthand acknowledge that the zero will occur k times in the list of all zero 
##  List the multiplicities of zeroes of each of the following polynomials  

$$
\begin{array}{l}  \\
P(x)=x^2+2x−15     =  0    \\
(x  +  5)(x  - 3 )   =   0  \\
\left  \{   \\
 \begin{array}{l} 
x =  - 5  \\
x   = 3  
\end{array}
\right.
\end{array}
$$
In this cases we will have two simple zero 


$$
\begin{array}{l}  \\
P(x)=x^2   - 14x  +  49    =  0    \\
(x    -  7)^2   =   0  \\

\end{array}
$$
In this cases we will have one zero with a multiplicity  of  2 





$$
\begin{array}{l}  \\
P(x)= 5x^5  - 20x^4  + 5x^3 + 50x^2  - 20x - 40        \\
 5(x + 1)^2(x - 2)^3  =   0  \\
\end{array}
$$
In this cases we will have two zero , one with a multiplicity of 2 and another with a multiplicity of  3  
$$
\begin{array}{l}  \\
Q(x)=x^8−4x^7−18x^6+108x^5−135x^4=      \\
x^4(x−3)^3(x+5) =   0  \\
\end{array}
$$
In this case we will have three zero  ,one with a multiplicity of 4 , one with multiplicity of 3 and one simple zero 


$$


\begin{array}{l}  \\
R(x)=x^7+10x^6+27x^5−57x^3−30x^2+29x+20   \\
=(x+1)^3(x−1)^2(x+5)(x+4)
\end{array}
$$
 In the final case we’ve got four zeroes. x=−5 which is simple, x=−1 with multiplicity of 3, x=1with multiplicity 2 and x=−4 which is simple.
## Fundamental Theorem of Algebra 
if $P(x)$ is a polynomial degree of n then $P(x)$ will have exactly zeroes , some of which may repeat 

This face say that if you list out all the zeroes and listing each one k times where k is it multiplicity you will have exactly n number in the list . Another way of saying this is that the multiplicity of all the zero will add back into the degree of the polynomial 


We can go  back to the pervious example and verify that this fact is true for the polynomials listed there 

This will be a nice fact in a couple of section to find all zero  in a polynomial .IF we know the upper bound for the number of zero for a polynomial then we will know when we've found all of them and so we can stop looking 

Note as well that some of the zero  may be complex . In this section we have worked with polynomial that have real zero , but this theorem does not only apply to real zero 