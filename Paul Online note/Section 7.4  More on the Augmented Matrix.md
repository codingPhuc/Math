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

so  if we do that for this case we get  
$$
\begin{array}{l} \\
(1) x +  (0)  y  =     h  \implies  x  =  h    \\
(0) x   +  (1)   y =  k  \implies  y  = k
\end{array}
$$

this is exactly what we said the solution was in the previous section  

This idea of turning an augmented matrix back into equation will be important for the following examples 


## Use augmented matrix to solve each of the following system 

$$
\begin{array}{l} 
x -  y =  6  \\
 -2x    +  2y = 1  
\end{array}
$$

$$
\left[ \begin{array}{cc|c}  
1  &  -1  &  6  \\
-2  &  2  &  1   
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
1  &  -1  &  6  \\
-2  &  2  &  1   
\end{array} \right] 
R_{2}  + 2R_1\to R_2 
\left[ \begin{array}{cc|c}  
1  &  -1  &  6  \\
0  &  0  &  13   
\end{array} \right] 
$$
now  go back to the equation and you see we will get this case 
$$
\begin{array}{l} 
x -  y  =   6    \\
   0  =  13   ??
\end{array}
$$
The first row convert back into the first equation while the second row convert back to nonsense . We know that this is not true  so that mean that there is not solution . Remember , if we reach a solution that does not make sense we have not solution 
However , remember that 

$$
\left[ \begin{array}{cc|c}  
1  &  -1  &  6  \\
0   &  1  &   0  
\end{array} \right] 
$$
this would be  okay since the last row would return the equation  y = 0 so don't get confuse between this case and what we got for the system 






$$
\begin{array}{l} 
2x +  5 y =  -1   \\
 -10x - 25y = 5  
\end{array}
$$


$$
\left[ \begin{array}{cc|c}  
2  &  5  &  -1 \\
-10  &  -25  &  5   
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
2  &  5  &  -1 \\
-10  &  -25  &  5   
\end{array} \right] 
R_{2}  + 5R_1\to R_2 
\left[ \begin{array}{cc|c}  
2  &  5  &  -1 \\
0  &  0  &  0  
\end{array} \right] 
$$
just like the last equation ,  we cannot get the 1  in the second zero in the second row . However , this equation is not nonsense . Let convert it back to an equation 

$$\begin{array}{l} \\
2x   +  5 y =  -1   \\
 0  =  0 
\end{array}
$$

Note however , that if  we use the equation from the augmented matrix this is very easy to do 

$$
x = -\frac{5}{2} y  - \frac{1}{2}
$$
we then write the solution as 

$$
\begin{array}{l} \\
x   =  -\frac{5}{2} t - \frac{1}{2 } \\
y   = t \text{  where  t is any real number}
\end{array}
$$
we get the equation by picking t and plug it into the equation for x .Note however that this is not the equation we get in the first section [[Section 7.1  Linear Systems with Two Variables]] . However , this is okay since there are endless solution resulting in endless equation 
##  solve  the following system of equation using augmented  matrices 

$$
\begin{array}{l} 
3x  - 3y  - 6z  =  -3   \\
2x - 2y  - 4z  =  10   \\
-2x +  3y +  z  = 7 
\end{array}
$$

$$
\left[\begin{array}{ccc|c} 
3 & -3 & -6 & -3 \\
2 & -2 & -4 & 10 \\
-2 & 3 & 1 & 7
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
3 & -3 & -6 & -3 \\
2 & -2 & -4 & 10 \\
-2 & 3 & 1 & 7
\end{array}\right]
\frac{1}{2}R_{2}  \xrightarrow{\text{}}
\left[\begin{array}{ccc|c} 
3 & -3 & -6 & -3 \\
1 & -1 & -2 & 5 \\
-2 & 3 & 1 & 7
\end{array}\right]
$$ 


$$
\left[\begin{array}{ccc|c} 
3 & -3 & -6 & -3 \\
1 & -1 & -2 & 5 \\
-2 & 3 & 1 & 7
\end{array}\right]
R_1\leftrightarrow R_2
\left[\begin{array}{ccc|c} 
1 & -1 & -2 & 5  \\
3 & -3 & -6 & -3  \\
-2 & 3 & 1 & 7
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c} 
1 & -1 & -2 & 5  \\
3 & -3 & -6 & -3  \\
-2 & 3 & 1 & 7
\end{array}\right]
R_{2}  -3R_1 \to R_2 
\left[\begin{array}{ccc|c} 
1 & -1 & -2 & 5  \\
0 & 0 & 0 & -18  \\
-2 & 3 & 1 & 7
\end{array}\right]
$$
now go the argument equation we know that we will have this case 

$$
\begin{array}{l} 
x   -  y  - 2  = 5  \\
0 =  -18  ??  \\
-2x   +  3y   + z   =  7
\end{array}

$$
we know that we will have no solution for the equation above the systems will have no solution 



$$
\begin{array}{l} 
3x  - 3y  -  6z = - 3  \\
2x -  2y  - 4z =  -2   \\
-2x + 3y + z -  7 
\end{array}
$$


$$
\left[\begin{array}{ccc|c} 
3  &  -3   &  -6  &  - 3  \\
2x &   -2y  &  - 4z   &   -2  \\
-2x   &   +  3y  &  + z  &  -7
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
3  &  -3   &  -6  &  - 3  \\
2x &   -2y  &  - 4z   &   -2  \\
-2x   &   +  3y  &  + z  &  -7
\end{array}\right]
R_1\leftrightarrow R_2
\left[\begin{array}{ccc|c} 
 2x &   -2y  &  - 4z   &   -2  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  -7
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
3  &  -3   &  -6  &  - 3  \\
2x &   -2y  &  - 4z   &   -2  \\
-2x   &   +  3y  &  + z  &  -7
\end{array}\right]
\frac{1}{2 }R_1 \xrightarrow{\text{}} 
\left[\begin{array}{ccc|c} 
 2x &   -2y  &  - 4z   &   -2  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  -7
\end{array}\right]
$$