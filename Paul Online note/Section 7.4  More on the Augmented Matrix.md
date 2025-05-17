---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-17
amount of time: 
learning score:
---
we saw that there were some special  cases in the solution of the two system . We saw that there can be either no solution or infinite solution . In the following we are going to general systems of equations , we will look at how to used augmented matrix to deal with these cases 


## fact 
equations there are exactly three possibility for the solution 
1. there will not be solution 
2. there will be exactly one solution 
3. There will be infinitely  many solution 
I does not matter how complex the system of equation that we got there will always be these three possibility 

This is exactly the possibilities to be when we were looking at two equation . It just turn out that it does not matter how many equation we have . There are still these three possibility 


now let  identify  the first  and last possibility when using the argument matrix for solving . In the pervious section we stated that we wanted to use the row operation to convert the argument matrix into the following 
$$
\left[ \begin{array}{cc|c}  
1  &  0  &  h  \\
0  &  1  &  k  
\end{array} \right]  or  \left[\begin{array}{ccc|c}  
1  &  0  & 0 &  p   \\
 0 &  1  & 0   & q   \\
0  &  0 &  1 &   r \\
\end{array}\right]
$$

depending upon  the number of equations present in the system . It turn out that we should have add a qualifier  "if possible" to this equation , because it isn't always possible to do this . In fact , if it isn't possible to put it into  one of these form then we will know that we are in either the first or last possibility for the solution to the system 

let take  a look at system with two equation example 
$$
\left[ \begin{array}{cc|c}  
1  &  0  &  h  \\
0  &  1  &  k  
\end{array} \right] 
$$

is an augmented matrix we can always convert back to equation. each row represents an  equation  and the first column is the coefficient of  x in the equation while the second columns is the coefficient of y in the equation. The final column is the constant that will be on the right side of the equation 


