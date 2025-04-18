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
Q(x) = 5x^2  _{}
$$