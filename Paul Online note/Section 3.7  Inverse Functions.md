---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: "2025-04-02"
---
In the last example in the pervious section we look at two function , $f(x) =3x -  2$ and $g(x) =\frac{x}{3}+ \frac{2}{3}$ 
$$
\left(f\circ g\right)\left(x\right)=\left(g\circ f\right)\left(x\right)=x
$$
these are very special function  . Let see what make them so special . Consider the following evaluations   


$$
\begin{array}{l}
f(-1) = 3(-1) -2  =  -5    \\
g(-5) = -\frac{5}{3} +  \frac{2}{3 }  = -\frac{3}{3}  =  -1 
\end{array}

$$
$$
\begin{array}{l}
 g(2) = \frac{2}{3} + \frac{2}{3}  = \frac{4}{3 }\\
f\left( \frac{4}{3} \right) = 3\left( \frac{4}{3} \right) - 2 =  4 - 2  = 2  \\
\end{array}

$$
in the first cases we plugged in $x = -1$ into $f(x)$ and got a value of -5. We need to turn around and plugged x =  -5 into $g(x)$  and got a  value of  -1 , the number we started off with 
In the second case we did something similar . Here we plugged in the value of 2 and got $\frac{4}{3 }$ , we turn around and plug the resulting value into g which give us 2 

Noted however that we are really doing some function composition here 
$$
(g\circ f) (-1 ) =  g[f(-1)]  = g[-5]  = -1 
$$
and the second cases is really  
$$
(f\circ g) (2)   = f [g(2)]  = f\left[ \frac{4}{3} \right]  = 2  
$$
Note as well that both agree with the formula of the pervious section  [[Section 3.6  Combining Functions]]. We get back out of the function the number we previously  plug  into the equation 

So what is going on ? In some way the function cancel out each other , when we plug the value of -1 into f(x) and then plug the resulting value back into  g  for some reason g undid what f have done and gave us the pervious value 
Function pairs that do this  are called **inverse function** . Before defining inverse function and it notation . We need to first look at the definitions  that come with it 

A function is called  **one to one** if no two value of x give the same y .  this is fairly simple definition of **one-to-one**  but it take an example of a function that is not one to one to show just what it mean . Before going further , we should note that this definition of one to one is not the  mathematical equivalent of one to one . Not  Because , operation are not the same, but due to    not used the mathematical notation for explanation 

Now , let see an example of function that is not one to one . The function $f(x) =  x^2$  is not  one - to -one because of both$f(-2) =4$ and $f( 2)= 4$ . In other word , there are two different value of  x that produce the same value of y . Note that we can turn $f(x) =x^2$ into  a one to one function if we restrict our self to $0\leq x<0$ 

Showing that a function is one to one is a tedious and difficult process . For the most part function we are going to be dealing with are one to one 

##  Inverse function 

