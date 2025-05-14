---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-13
amount of time: 
learning score:
---


# #definition 
$$
\begin{array}{l}  \\
x - 2y +  3z  = 7  \\
2x + y + z = 4  \\
-3x + 2y -2z  = -10  
\end{array}
$$


We  are going to try to find value of z , y and z will satisfy all three equation at one . We are going to use elimination to eliminate one variable from one of  the equation and two variables from another equation 


in this cases if we multiply the second equation by 2 then it will be easier to eliminate the second and third equation 

$$
\begin{array}{l}
 x -  2y +  3z =  7   \xrightarrow{\text{same}} x - 2y + 3z = 7  \\
2x +  y + z = 4  \xrightarrow{\text{x 2}}  4x +2y + 2z  = 8 \\
-3x  + 2y -2z =  -10 \xrightarrow{\text{same}} -3x + 2y -2z  = -10   
\end{array}
$$
Now with this new system  we will replace the third and second equation with the sum of the first with the second and third 
here is the resulting equation : 
$$
\begin{array}{l} \\
x  - 2y + 3z   = 7   \\
5x  +  5z  =  15  \\
-2x  + z =  -3  
\end{array}
$$
So ,  we've eliminated one of the variables from  two of the equations . Now either eliminate x or z from the third or second  equation . We will used  elimination to do this by multiplying the third  by -5


$$
\begin{array}{l}
x  - 2y + 3z   = 7   \xrightarrow{\text{same}} x  - 2y + 3z   = 7   \\
5x  +  5z  =  15   \xrightarrow{\text{ same}} 5x  +  5z  =  15  \\
-2x  + z =  -3  \xrightarrow{\times\text{ -5}} 10x   -5 z =  15  
\end{array}
$$

Now replace the third and second equation with sum of the second and third 
$$
\begin{array}{l} \\
x  - 2y + 3z   = 7   \\
5x  +  5z  =  15  \\
15x  =  30 
\end{array}
$$
now solve the linear system  with  three solution 
$$
\begin{array}{l}  \\
x =  2   \\
5z  =  15 - 5 \cdot 2   \implies z =   1    \\
2  -  2y  + 3 \cdot 1   = 7 \implies y  = -1  
\end{array}
$$


## example  2 solve the following system  of equation 



$$
\begin{array}{l}  \\
2x  -  4y  +  5z  = -33   \\
4x  - y =  -5  \\
-2x  + 2y - 3z  = 19  
\end{array}
$$


We  are going to try to find value of z , y and z will satisfy all three equation at one . We are going to use elimination to eliminate one variable from one of  the equation and two variables from another equation 


in this cases if we multiply the second equation by -4 and the third equation by 2  then it will be easier to eliminate the second and third equation 

$$
\begin{array}{l}
2x  -  4y  +  5z  = -33   \xrightarrow{\text{same}} 2x  -  4y  +  5z  = -33  \\
4x  - y =  -5  \xrightarrow{\times\text{ -4}}  -16x   + 4y     = 20   \\
-2x  + 2y - 3z  = 19   \xrightarrow{\times\text{2}} -4x  + 4y - 6z  = 38  
\end{array}
$$
Now with this new system  we will replace the third and second equation with the sum of the first with the second and third 
here is the resulting equation : 
$$
\begin{array}{l} \\
 2x  -  4y  +  5z  = -33  \\
-14x  +  5z  =  -13  \\
-2x -z  = 5 
\end{array}
$$
So ,  we've eliminated one of the variables from  two of the equations . Now either eliminate x or z from the third or second  equation . We will used  elimination to do this by multiplying the third  by 5


$$
\begin{array}{l}
2x  -  4y  +  5z  = -33   \xrightarrow{\text{same}} 2x  -  4y  +  5z  = -33  \\
-14x  +  5z  =  -13  \xrightarrow{\text{ same}} -14x  +  5z  =  -13    \\
-2x -z  = 5   \xrightarrow{\times\text{5}} -10x -5z  = 25  
\end{array}
$$

Now replace the third and second equation with sum of the second and third 
$$
\begin{array}{l} \\
 2x  -  4y  +  5z  = -33  \\
-14x  +  5z  =  -13    \\
-24x  = 12 \implies x =  - \frac{1}{2}
\end{array}
$$
now solve the linear system  with  three solution 
$$
\begin{array}{l}  \\
x = - \frac{1}{2} \\
-14x  +  5z  =  -13 \implies z = -4    \\ 
 2x  -  4y  +  5z  = -33  \implies   y = 3  \\

\end{array}
$$


### method 2  



$$
\begin{array}{l}  \\
2x  -  4y  +  5z  = -33   \\
4x  - y =  -5  \\
-2x  + 2y - 3z  = 19  
\end{array}
$$
we see that the second equation have only two variables x and y , with  y having a coefficient of -1 . This make it easy to solve for y 
$$
 y =  4x +  5
$$

substitute the y in the other two  equation and we will get 
$$
\begin{array}{l} \\
2x  -  4( 4x +  5)  +  5z  = -33   \\
-2x  + 2( 4x +  5) - 3z  = 19  
\end{array}
$$

$$
\begin{array}{l} \\
-14x   +  5z  = -13   \\
6x  -3z  = 9     \\
\end{array}
$$
this leave us with a linear system  with two variables .Further more , using the elimination method we will get 



$$
\begin{array}{l}

6x  -3z  = 9 \xrightarrow{\times\text{ 5}} 30x  -15z  = 45   \\
-14x   +  5z  = -13 \xrightarrow{\times\text{3}} -42x   +  15z  = -39 
\end{array}
$$


Now replace the third and second equation with sum second  and first 
$$
\begin{array}{l} \\
30x  -15z  = 45   \\
-12x     =   6   \\
x =   -\frac{1}{2}
\end{array}
$$
now solve the linear system  with  three solution 
$$
\begin{array}{l}  \\
x = - \frac{1}{2} \\
4x  - y =  -5  \\\implies     y = 3  \\ 
 2x  -  4y  +  5z  = -33  \implies z = -4   \\
\end{array}
$$




# #Practice_Exercise  



#fail 
$$
\begin{array}{l}  \\
2x +  5y +  2 z =  -38   \\
3x  - 2y  + 4z = 17  \\
-6x  +   y - 7z=  -12 
\end{array}
$$




We  are going to try to find value of z , y and z will satisfy all three equation at one . We are going to use elimination to eliminate one variable from one of  the equation and two variables from another equation 


in this cases if we multiply the second equation by 2 then it will be easier to eliminate the second and third equation 

$$
\begin{array}{l} \\
-6x  +   y - 7z=  -12  \xrightarrow{\text{same}}  -6x  +   y - 7z=  -12 \\
2x +  5y +  2 z =  -38  \xrightarrow{\times \text{3}}  6x  +  15y  +  6z  = -114  \\
3x  - 2y  + 4z = 17  \xrightarrow{\times \text{2}}  6x  - 4y +  8z  = 34\\
  
\end{array}
$$
Now with this new system  we will replace the third and second equation with the sum of the first with the second and third 
here is the resulting equation : 
$$
\begin{array}{l} \\
 -6x  +   y - 7z=  -12  \\
16y  - z  =  -126  \\
-3y   + z =  22   
\end{array}
$$
So ,  we've eliminated one of the variables from  two of the equations . Now either eliminate x or z from the third or second  equation . We will used  elimination to do this by multiplying the third  by -5


$$
\begin{array}{l}
 -6x  +   y - 7z=  -12 \xrightarrow{\text{same}}  -6x  +   y - 7z=  -12   \\
16y  - z  =  -126    \xrightarrow{\text{ same}} 16y  - z  =  -126   \\
-3y   + z =  24  \xrightarrow{\text{ same}} -3y   + z =  22   
\end{array}
$$

Now replace the third and second equation with sum of the second and third 
$$
\begin{array}{l} \\
x  - 2y + 3z   = 7   \\
16y  - z  =  -126    \\
13 y =  -104 \\
y =   -8   
\end{array}
$$
now solve the linear system  with  three solution 
$$
\begin{array}{l}  \\
y =   -8  \\
-3y   + z =  22     \implies z =   -2    \\
-6x  +   y - 7z=  -12    \implies x  =  3    
\end{array}
$$









$$
\begin{array}{l}  \\
3x  -  9z   = 33  \\
7x - 4y  -z  =  -15  \\
4x + 6y + 5z     =  -6  
\end{array}
$$



we see that the second equation have only two variables x and y , with  y having a coefficient of -1 . This make it easy to solve for y 
$$
3x  -  9z   = 33  \implies  x  =  11   +  3z  
$$

substitute the y in the other two  equation and we will get 
$$
\begin{array}{l} \\
7x - 4(11 + 3x)  -z  =  -15  \\
4x + 6(11 + 3x ) + 5z     =  -6  
\end{array}
$$

$$
\begin{array}{l} \\
 -5x      -z  =  29  \\
22x   + 5z     =  -72  
\end{array}
$$
this leave us with a linear system  with two variables .Further more , using the elimination method we will get 



$$
\begin{array}{l}

 -5x      -z  =  29   \xrightarrow{\times\text{ 5}} -25x        -5z  =  145     \\
22x   + 5z     =  -72  \xrightarrow{same} 22x   + 5z     =  -72   
\end{array}
$$


Now replace the  second equation with sum second  and first 
$$
\begin{array}{l} \\
-3x   =  73  \\
-12x     =   6   \\
x =   -\frac{1}{2}
\end{array}
$$
now solve the linear system  with  three solution 
$$
\begin{array}{l}  \\
x = - \frac{1}{2} \\
4x  - y =  -5  \\\implies     y = 3  \\ 
 2x  -  4y  +  5z  = -33  \implies z = -4   \\
\end{array}
$$


