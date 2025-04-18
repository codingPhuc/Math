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
we will be restricted by  polynomial with degree of 1 in this exercise .  Lo