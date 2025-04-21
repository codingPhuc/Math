---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: "2025-04-17"
---
In this section we need to take a look at dividing polynomials . This is something we will be doing off and on though out the rest of this chapter . 



$$
\frac{5x^3   -  x^2  +    0 x   +  6  }{x  -4}
$$
we need to  write down the term in decreasing order .  Making sure to not make any mistake we add in a missing term  with a zero coefficient  

Now  we need to ask what we need to multiply  by  $x - 4$  to get the first term in the numerator polynomial . In this cases $5x^2$ so multiply $x-4$  by $5x^2$  then subtract the numerator polynomial by the multiply result  

![[Pasted image 20250417203328.png]] 
the new polynomial is called the remainder .We continue the process until the degree of the remainder is less then the degree of the **divisor** or the denominator polynomial  which is $x -4$ 

recall in [[Polynomials]] that the degree is the highest power of the polynomial  , while a constant is a polynomials with a degree of 0  

![[Pasted image 20250417203642.png]]

okay so the solution to our equation is  : 
$$
\frac{5x^3 - x^2  + 6} {x - 4}  = 5x^2  +  19x  +  76  + \frac{310}{x - 4}
$$
we can  also  write down a more easy  to look at solution 
$$
5x^3 - x^2  + 6    = ( x - 4)( 5x^2  +  19x  +  76)  +  310  
$$
we will be restricted by  polynomial with degree of 1 in this exercise .  Long division can be implemented for more general form of polynomial but we will not go into detail in this section 

the degree of 1 polynomial divisor will be seen so much in this exercise that we can implement  something called a **synthetic division** that work wonder full for this kind of problem .  In order to use synthetic division we must be dividing a polynomial by a linear term in the form x−r If we aren’t then it won’t work. 
let redo the previous  exercise by synthetic division 
$$
\text{synthetic division to divide } 5x^3 - x^2 + 6  \text{ by } x - 4
$$

First, let's notice that in this case  $r=4$ 
Now we need to set up the process . There are many different notation to do this , but we will be using the following 
![[Pasted image 20250417210346.png]] 
the number to right is the coefficients of the terms in  descending exponent   . Missing term are acknowledge with a coefficient of zero 
![[Pasted image 20250417210559.png]]
First we  put the first number down into the third row un change . Second , we multiply the number we just put down by r in $x-r$ in this cases 4  into the second row . Third , subtract it by the number in the first row . Finally , continue until we reach the last number 

## Division  Algorithm 
Given a polynomial P(x) with degree at least 1  and any number r there is another polynomial $Q(x)$ ,called the quotient ,with the degree less than the degree of $P(x)$ and a number $R$ called the remainder such that 
$$
P(x)  = (x  - r) Q(x)  + R
$$
Note as well that Q(x) and R are unique , or in other word , there is only one Q(x) and  R that will work for a given P( x) and r 

so the one example we've down  to this point we can see that : 
$$
Q(x) = 5x^2  +  19x  + 76  \text{ and  } R =  310
$$



##  Used  synthetic division to do each of the following 

$$
2x^3  - 3x  - 5 \text{ by } x+ 2 
$$
$$
2 \mid 2 \; 0 \; -3 \; -5 
$$

| -2  | 0   | -3  | -5  |
| --- | --- | --- | --- |
|     | 4   | 8   | -10 |
| 2   | -4  | 5   | -15 |
|     |     |     |     |
$$
(2x^3  -  4x^2  +  5x)(x  +  2) -  15 
$$
$$
4x^4   - 10x^2 + 1  \text{ by } x - 6
$$
$$
6 \mid 4 \; 0 \; -10 \;  0  \; 1  
$$

| 6   | 4   | 0   | -10 | 0   | 1    |
| --- | --- | --- | --- | --- | ---- |
|     |     | 24  | 144 | 804 | 4824 |
|     | 4   | 24  | 134 | 804 | 4825 |
$$
(4x^4  +  24x^3  - 10x^2 +  804x )(x  -  6) +  4825 
$$

why are we diving our function like this , the answer will be that in a later section ,we want to get our hand on the $Q(x)$ 

There are many reason for this we are going to make heavy usage of later on . Let first start with a division algorithm 

$$
P(x)    = (x - r) Q(x) + R
$$

Now let evaluate our function $P(x)$  by plugging in r  . Let used the division algorithm instead of the equation of P(x)
$$
\begin{array}{l }
P(r)  =  (r - r ) Q(r)  + R   \\
=  (0) Q( r) +  R  \\
=  R 
\end{array}

$$


Now, that’s convenient. The remainder of the division algorithm is also the value of the polynomial evaluated at rr. So, from our previous examples we now know the following function evaluations.
$$
 \begin{gathered}\operatorname{If}P(x)=5x^3-x^2+6\mathrm{~then~}P(4)=310\\\operatorname{If}P(x)=2x^3-3x-5\mathrm{~then~}P\left(-2\right)=-15\\\mathrm{If~}P(x)=4x^4-10x^2+1\mathrm{~then~}P\left(6\right)=4825\end{gathered}
$$

This is a very quick method for evaluating polynomials. For polynomials with only a few terms and/or polynomials with “small” degree this may not be much quicker that evaluating them directly. However, if there are many terms in the polynomial and they have large degrees this can be much quicker and much less prone to mistakes than computing them directly.

As noted, we will be using this fact in a later section to greatly reduce the amount of work we’ll need to do in those problems.


# #Practice_Exercise  

Divide  $3x^4  -5x^2 + 3$ by  $x+ 2$ 

$$
2x^3  - 3x  - 5 \text{ by } x+ 2 
$$
$$
2 \mid 2 \; 0 \; -3 \; -5 
$$

| -2  | 0   | -3  | -5  |
| --- | --- | --- | --- |
|     | 4   | 8   | -10 |
| 2   | -4  | 5   | -15 |
|     |     |     |     |
