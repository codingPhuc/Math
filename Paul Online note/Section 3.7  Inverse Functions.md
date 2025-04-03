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
Given  two one-to-one function $f(x) \text{ and } g(x)$ if  $$
(f \circ g)(x ) = x  \text{ And } (g\circ f)(x)  = x 
$$
then we can say that $f(x)$ and $g(x)$ are inverse of each other  . More specifically we will say that g(x ) is the inverse of f(x) and denote it by $$
g(x)  = f^{-1}(x) 
$$
likewise , we could say that f(x) is the inverse of g(x) and denote it by 
$$
f(x) = g^{-1}(x)
$$
The notation that we use really depend on the  problem . In  most cases either is   acceptable 
For the function we start this section with we could write two of the following set of notation  
$$
f(x)   =  3x   -2  \quad f^{-1} (x)  =  \frac{x}{3} + \frac{2}{3}
$$

$$
g(x)  =  \frac{x}{3} + \frac{2}{3}  \quad g^{-1}(x)  = 3x - 2 
$$

we need to remember the -1  is not a inverse exponent [[Integer Exponents]] . When dealing with inverse function remember 
$$
f^{-1}(x)  = \frac{1}{f(x)}
$$
## Finding the inverse of a functions 
given $f(x)$ we want to find the inverse of $f^{-1}(x)$  
1. first replace the value $f(x)$ with y . This is to make the rest of the process easier 
2. replace every x with y and every y with x 
3. Solve the equation from step 2 for y . This is the step where mistake are often made 
4. Replace y with $f^{-1}(x)$ . In other word, manage to find the inverse at this point 
5. verify this by checking that $(f\circ f^{-1})(x)  =x$ and $(f^{-1}\circ f)(x) =x$ are both true 


In the verification step there is a real need to check $(f\circ f^{-1})(x)  =x$ and $(f^{-1}\circ f)(x) =x$ are both true  . For the majority of cases you only need to check one , but there are some outlier cases where the second check is necessary 


$$
f(x)   = 3x  - 2 \text{ find } f^{-1}(x)  
$$
$$
g(x) \sqrt{ x  -3  } \text{ find } g^{-1}(x) , x \geq 0  
$$
$$
h(x)  = \frac{x+ 4} {2x   - 5}   \text{ find } h^{-1}(x)
$$

there is an interesting relation between the graph  of  a function and it inverse 
