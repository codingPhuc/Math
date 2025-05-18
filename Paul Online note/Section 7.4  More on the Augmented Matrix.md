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
# #definition 

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
-2x + 3y + z =  7 
\end{array}
$$


$$
\left[\begin{array}{ccc|c} 
3  &  -3   &  -6  &  - 3  \\
2x &   -2y  &  - 4z   &   -2  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
3  &  -3   &  -6  &  - 3  \\
2x &   -2y  &  - 4z   &   -2  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
R_1\leftrightarrow R_2
\left[\begin{array}{ccc|c} 
 2x &   -2y  &  - 4z   &   -2  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
 2x &   -2y  &  - 4z   &   -2  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
\frac{1}{2 }R_1 \xrightarrow{\text{}} 
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
3  &  -3   &  -6  &  - 3  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right]
R_{2}  -3R_1 \to R_2 
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
0  &  0   &  0  &  0  \\
-2x   &   +  3y  &  + z  &  7
\end{array}\right] 
R_{2}  + 2R_1 \to R_2  
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
0  &  0   &  0  &  0  \\
0   &   +  1y  & -3z  &  5
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
0  &  0   &  0  &  0  \\
0   &   +  1y  & -3z  &  -9
\end{array}\right]
R_1\leftrightarrow R_3
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
0   &   +  1y  & -3z  &  -9 \\
0  &  0   &  0  &  0 
\end{array}\right]
$$
$$
\left[\begin{array}{ccc|c} 
 1x &   -1y  &  - 2z   &   -1  \\
0   &   +  1y  & -3z  &  5 \\
0  &  0   &  0  &  0 
\end{array}\right]
R_{1}  + R_2\to R_1 
\left[\begin{array}{ccc|c} 
 1x &   0  &  - 5z   &   4   \\
0   &   +  1y  & -3z  &  5 \\
0  &  0   &  0  &  0 
\end{array}\right]
$$

one we reach this point we can go back to the equation 

$$
\begin{array}{l} \\
x -  5z  =  4  \\
 y  - 3z  =  5 
\end{array}
$$
both of these equation contain z  so we'll move that to the other side of the equation 
$$
\begin{array}{l} \\
x  =  4   +  5z   \\
 y =  5 +  3z 
\end{array}
$$
this mean we  can pick the z value for free we will write the solution as 

$$
\begin{array}{l} \\
x  =  4   +  5t   \\
 y =  5 +  3t  \text{ where t is any real number} \\
z = t 
\end{array}
$$



# #Practice_Exercise   




$$
\begin{array}{l} 
x -  7y  = -11   \\
5x +  2y     =  -  18 
\end{array}
$$


$$
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
5 &   2   &    -18 
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
5 &   2   &    -18 
\end{array} \right] 
R_{2}  - 5R_1\to R_2 
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
0 &   37   &    37   
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
0 &   37   &    37   
\end{array} \right] 
\frac{1}{37}R_{2} \to 
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
0 &   1   &    1  
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1   &   - 7  &   -11   \\
0 &   1   &    1  
\end{array} \right] 
R_{1}  +  7R_2\to R_1 
\left[ \begin{array}{cc|c}  
1   &    0   &   -4    \\
0 &   1   &    1  
\end{array} \right] 
$$
so the solution to the equation is  
$$
\begin{array}{l}  
x =  - 4   \\
y =  1  
\end{array}
$$










$$
\begin{array}{l} 
7x -  8 y  = -12   \\
-4x  +  2y  =  3 
\end{array}
$$


$$
\left[ \begin{array}{cc|c}  
7 &   - 8   &  -12  \\
-4 &  2   &  3  
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
7 &   - 8   &  -12  \\
-4 &  2   &  3  
\end{array} \right] 
\frac{1}{7}R_{1} \to 
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
-4 &  2   &  3  
\end{array} \right]
$$



$$
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
-4 &  2   &  3  
\end{array} \right]
R_{2}  +  4R_1\to R_2 
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
 0  &   -\frac{18}{7}   &    -\frac{27}{7}  
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
 0  &   1    &    -\frac{27}{7}  
\end{array} \right] 
 -\frac{18}{7}R_{1} \to 
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
 0  &   1    &   \frac{3}{2 }
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1 &   - \frac{8}{7}   &  -\frac{12}{7}  \\
 0  &   1    &   \frac{3}{2 }
\end{array} \right] 
R_{1}  +  \frac{8}{7}R_2\to R_1
\left[ \begin{array}{cc|c}  
1  &  0  & 0  \\
 0  &   1    &   \frac{3}{2 }
\end{array} \right] 
$$

so the solution to the equation is  
$$
\begin{array}{l}  
x =  0   \\
y =  \frac{3}{2}  
\end{array}
$$









$$
\begin{array}{l} 
3x  +  9 y  = -6   \\
-4x  - 12y  =  8 
\end{array}
$$


$$
\left[ \begin{array}{cc|c}  
3 &   9  &   -6   \\
-4   &   -12  &    8 
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
3 &   9  &   -6   \\
-4   &   -12  &    8 
\end{array} \right] 
\frac{1}{3}R_{1} \to 
\left[ \begin{array}{cc|c}  
1 &   3  &   -2   \\
-4   &   -12  &    8 
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}  
1 &   3  &   -2   \\
-4   &   -12  &    8 
\end{array} \right] 
R_{2}  +  4R_1\to R_2 
\left[ \begin{array}{cc|c}  
1 &   3  &   -2   \\
0   &   0  &    0 
\end{array} \right] 
$$



we concluded that the system is dependance  bases since the row $R_{2}$  have all it entries equal  to zero  
so we have the solution 

$$
\begin{array}{l}
x  +  3 y  =  -2  \implies x   =   -2   - 3t \\
y  = t  
\end{array}
$$










$$
\begin{array}{l} 
6x  - 5y  =  8  \\
 -12x + 2y = 0 
\end{array}
$$

$$
\left[ \begin{array}{cc|c}  
6 &   -5  &   8  \\
-12  &  2  &    0 
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
6 &   -5  &   8  \\
-12  &  2  &    0 
\end{array} \right] 
R_{2}  +  2R_1 \to R_2 
\left[ \begin{array}{cc|c}  
6 &   -5  &   8  \\
0  &  -8   &    16  
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
6 &   -5  &   8  \\
0  &  -8   &    16  
\end{array} \right] 
\frac{1}{6}R_{1} \to 
\left[ \begin{array}{cc|c}  
1 &   -\frac{5}{6}  &   \frac{4}{3}  \\
0  &  -8   &    16  
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}  
1 &   -\frac{5}{6}  &   \frac{4}{3}  \\
0  &  -8   &    16  
\end{array} \right] 
\frac{1}{-8}R_{2} \to 
\left[ \begin{array}{cc|c}  
1 &   -\frac{5}{6}  &   \frac{4}{3}  \\
0  &  1   &    -2
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}  
1 &   -\frac{5}{6}  &   \frac{4}{3}  \\
0  &  1   &    -2
\end{array} \right] 
R_{1}  +  \frac{5}{6}R_2\to R_1 
\left[ \begin{array}{cc|c}  
1 &   0  &   -\frac{1}{3}  \\
0  &  1   &    -2
\end{array} \right] 
$$

$$
\begin{array}{l} \\
x =  -\frac{1}{3}   \\
y =  -2  
\end{array}
$$








$$
\begin{array}{l} 
5x - 25y  = 3   \\
-2x  + 10 y  = 2 
\end{array}
$$

$$
\left[ \begin{array}{cc|c}  
5 &   -25  &   3   \\
-2  &  10  &   2  
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
5 &   -25  &   3   \\
-2  &  10  &   2  
\end{array} \right] 
\frac{1}{5}R_{1} \to 
\left[ \begin{array}{cc|c}  
1 &   -5  &   \frac{3}{5}   \\
-2  &  10  &   2  
\end{array} \right] 
$$




$$
\left[ \begin{array}{cc|c}  
1 &   -5  &   \frac{3}{5}   \\
-2  &  10  &   2  
\end{array} \right] 
R_{2}  +  2R_1\to R_2 
\left[ \begin{array}{cc|c}  
1 &   -5  &   \frac{3}{5}   \\
0 &   0   &   \frac{16}{5}  
\end{array} \right] 
$$

the system is inconsistent . Therefore , there is no solution to the system of equation 










$$
\begin{array}{l} 
2x +  3y  =  20  \\
7x + 2y =  53  
\end{array}
$$

$$
\left[ \begin{array}{cc|c}  
2   &  3  &   20   \\
7  &  2    &  53  
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
2   &  3  &   20   \\
7  &  2    &  53  
\end{array} \right] 
\frac{1}{2}R_{1} \to 
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
7  &  2    &  53  
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
7  &  2    &  53  
\end{array} \right] 
R_{2} -  7R_1 \to R_2
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
0 &  -\frac{17}{2}   & - 17   
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
0 &  -\frac{17}{2}   &  -17   
\end{array} \right]
-\frac{2}{17}R_{2} \to 
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
0 &  1   &  2    
\end{array} \right]
$$


$$
\left[ \begin{array}{cc|c}  
1   &  \frac{3}{2}  &   10   \\
0 &  1   &  2    
\end{array} \right]
R_{1}   -\frac{3}{2}R_2 \to R_1
\left[ \begin{array}{cc|c}  
1   &  0  &  7   \\
0 &  1   &  2    
\end{array} \right]
$$
$$
\begin{array}{l} \\
x =  7  \\
y =  2  
\end{array}
$$














$$
\begin{array}{l} 
2x + 5y + 2z  =  -38  \\
3x - 2y  +  4z  = 17  \\
-6x +  y -  7z  = -12 
\end{array}
$$

$$
\left[\begin{array}{ccc|c} 
2  &   5  &   2  &   -38  \\
3 &  -2   &  4 &   17   \\
-6 &  1   &   -7 &   -12 
\end{array}\right]
$$
$$
\left[\begin{array}{ccc|c} 
2  &   5  &   2  &   -38  \\
3 &  -2   &  4 &   17   \\
-6 &  1   &   -7 &   -12 
\end{array}\right]
\frac{1}{2}R_{1} \to 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
-6 &  1   &   -7 &   -12 
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
-6 &  1   &   -7 &   -12 
\end{array}\right]
R_{3} +   2R_2 \to R_3
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
0  &   -3  &  1 &  22  
\end{array}\right]
R_{2}   -3R_1 \to R_2
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  -\frac{19}{2}    &  1 &   74    \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  -\frac{19}{2}    &  1 &   74    \\
0  &   -3  &  1 &  22  
\end{array}\right]
-\frac{2}{19}R_2 \to 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   -3  &  1 &  22  
\end{array}\right]
R_3+ 3R_2\to r_{3} 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  \frac{13}{19} &  -\frac{26}{19}  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  \frac{13}{19} &  -\frac{26}{19}  
\end{array}\right]
 \frac{19}{13}R_3\to 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
$$




$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
R_1  -\frac{5}{2}R_2\to R_{1} 
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
R_2  + \frac{2}{19}R_3\to R_{2} 
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
R_1 - \frac{24}{19}R_3\to R_{1} 
\left[\begin{array}{ccc|c} 
1  &   0 &  0 &   3  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
$$




$$
\begin{array}{l} \\
x =  3   \\
y = -8  \\
z = -2  
\end{array}
$$











$$
\begin{array}{l} 
3x  - 9 z  =  33  \\
7x  - 4y  - z  =  -15   \\
-6x  +  y  - 7z =  -12 
\end{array}
$$

$$
\left[\begin{array}{ccc|c} 
3 &  0  &   -9  &  33   \\
7 &  -4 &  -1  &  -15   \\
-6 &    1 &   -7 &  -12 
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c} 
3 &  0  &   -9  &  33   \\
7 &  -4 &  -1  &  -15   \\
-6 &    1 &   -7 &  -12 
\end{array}\right]
R_{3} +   2R_1 \to R_3
\left[\begin{array}{ccc|c} 
3 &  0  &   -9  &  33   \\
7 &  -4 &  -1  &  -15   \\
0  &    1 &   -25 &  54  
\end{array}\right]
$$





$$
\left[\begin{array}{ccc|c} 
3 &  0  &   -9  &  33   \\
7 &  -4 &  -1  &  -15   \\
-6 &    1 &   -7 &  -12 
\end{array}\right]
\frac{1}{3}R_{1} \to 
\left[\begin{array}{ccc|c} 
1 &  0  &   -3  &  11    \\
7 &  -4 &  -1  &  -15   \\
-6 &    1 &   -7 &  -12 
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
-6 &  1   &   -7 &   -12 
\end{array}\right]
R_{3} +   2R_2 \to R_3
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
3 &  -2   &  4 &   17   \\
0  &   -3  &  1 &  22  
\end{array}\right]
R_{2}   -3R_1 \to R_2
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  -\frac{19}{2}    &  1 &   74    \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  -\frac{19}{2}    &  1 &   74    \\
0  &   -3  &  1 &  22  
\end{array}\right]
-\frac{2}{19}R_2 \to 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   -3  &  1 &  22  
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   -3  &  1 &  22  
\end{array}\right]
R_3+ 3R_2\to r_{3} 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  \frac{13}{19} &  -\frac{26}{19}  
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  \frac{13}{19} &  -\frac{26}{19}  
\end{array}\right]
 \frac{19}{13}R_3\to 
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
$$




$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
R_1  -\frac{5}{2}R_2\to R_{1} 
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c} 
1  &   \frac{5}{2}  &   1  &   -19  \\
0 &  1   &  -\frac{2}{19} &  - \frac{148}{19}    \\
0  &   0   &  1 &  -2
\end{array}\right]
R_2  + \frac{2}{19}R_3\to R_{2} 
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
$$


$$
\left[\begin{array}{ccc|c} 
1  &   0 &   \frac{24}{19}  &   \frac{9}{19}  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
R_1 - \frac{24}{19}R_3\to R_{1} 
\left[\begin{array}{ccc|c} 
1  &   0 &  0 &   3  \\
0 &  1   & 0  &  - 8   \\
0  &   0   &  1 &  -2
\end{array}\right]
$$




$$
\begin{array}{l} \\
x =  3   \\
y = -8  \\
z = -2  
\end{array}
$$


