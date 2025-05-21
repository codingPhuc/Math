---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-05-19"
amount of time: 
learning score:
---

A non linear system of equation, a non linear system of equation is system in which at least one of the variable have a exponent other than 1 and /or there is a product of variables in one the equations 
To solve these system we will use either the substitution method or elimination method that we first look at when solving the system of equations. The main different is that we may ended getting complex solution in addition to real solution. Just as we saw in the system of equations the real solution will be represented by a coordinate of points where the graphs of the functions intersection 

##  Solve the system of equation  
$$
\begin{array}{l}  
x^2  + y^2  = 10     \\
2x +  y = 1   \\
\left\{ \\
\begin{array}{l} 
y =  1 - 2x   \\
x^2  + (1- 2x)^2   =  10    \\
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
y =  1 - 2x   \\
x^2  +   4x^2  -  4x + 1     =  10    \\
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
y =  1 - 2x   \\
5x^2  -  4x - 9     =   0    \\
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
y =  1 - 2x   \\
\left\{ \\
\begin{array}{l} 
x  =  -\frac{9}{5}  \\
x   = -1 
\end{array}
\right. \\
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
y =  1 - 2x   \\
\left\{ \\
\begin{array}{l} 
x  = \frac{9}{5}  \implies  y  =     -\frac{13}{5}\\
x   = -1 \implies   y  = 3 
\end{array}
\right. \\
\end{array}
\right. \\
\end{array}
$$






$$
\begin{array}{l}  
x^2  - 2y^2  = 2  \\
x \cdot y  = 2   \\
  y =  \frac{2}{x}  \\
x^2  - 2\left( \frac{2}{x} \right)^2 = 2 \\
x^2  - \frac{8}{x^2}= 2  \\
x^4  -  8   = 2x^2 \\
x^4  -  2x^2   -8 = 0  \\
\text{ substitude  } x^2 =  t   \\
t^2   - 2t   - 8 =  0   \\

\left\{ \\
\begin{array}{l} 
t  = 4   \\
t  = - 2 
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
x   = \pm 2 \\
t  = \pm\sqrt{ 2 }i \text{ remove }
\end{array}  
\right. \\
\left\{ \\
\begin{array}{l} 
x   =  2  \implies y =1\\
x = -2 \implies y =-1 
\end{array}  
\right. \\
\end{array}
$$







$$
\begin{array}{l}  
2x^2 + y^2 = 24   \\
x^2   - y^2  = -12  \\
\end{array}
$$




$$
\left[ \begin{array}{cc|c}  
2  &  1 &  24\\
1  &  -1  &  -12 
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
2  &  1 &  24\\
1  &  -1  &  -12 
\end{array} \right] 
R_1\leftrightarrow R_2
\left[ \begin{array}{cc|c}  
1  &  -1  &  -12 \\
2  &  1 &  24 
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1  &  -1  &  -12 \\
2  &  1 &  24 
\end{array} \right] 
R_{2}  -2R_1 \to R_2 
\left[ \begin{array}{cc|c}  
1  &  -1  &  -12 \\
0  &  3 &  48 
\end{array} \right] 
$$

$$
\left[ \begin{array}{cc|c}  
1  &  -1  &  -12 \\
0  &  3 &  48 
\end{array} \right] 
\frac{1}{3}R_{2} \to 
\left[ \begin{array}{cc|c}
1  &  -1  &  -12 \\
0  &  1 & 16
\end{array} \right] 
$$

$$
\left[ \begin{array}{cc|c}
1  &  -1  &  -12 \\
0  &  1 & 16
\end{array} \right] 
R_{1}  +R_2 \to R_1 
\left[ \begin{array}{cc|c}
1  &  0  &  4  \\
0  &  1 & 16
\end{array} \right] 
$$ 


$$
\begin{array}{l}  
x^2 =  4   \\
y^2  = 16    \\
 \left\{ \\
\begin{array}{l} 
x  = \pm  2    \\
 y =  \pm 4 
\end{array}
\right. \\
\end{array}
$$



# #Practice_Exercise 

$$
\begin{array}{l}  
y  = x^2   + 6x  - 8   \\
 y  = 4x  +  7   \\
 4x  +  7 = x^2 + 6x -  8   \\
x^2 + 2x  -15  = 0   \\
\left\{ \\
\begin{array}{l} 
x  = 3  \implies    y =  19  \\
 x  =  -5 \implies  y  =  -13 
\end{array}
\right. \\

\end{array}
$$




$$
\begin{array}{l}  
 y = 1  - 3x    \\
\frac{x^2}{4} + y^2  =  1    \\
\frac{x^2}{4}   + (1 - 3x)^2   = 1   \\
\frac{x^2}{4}  + 9x^2  -6x +  1  =  1   \\
37x^2  -24x   = 0 \\
\left\{ \\
\begin{array}{l} 
x  = 0  \implies    y =  1  \\
 x  =  \frac{24}{37} \implies  y  =  -\frac{35}{37} 
\end{array}
\right. \\

\end{array}
$$






$$
\begin{array}{l}  
 4 = xy \implies y  =  \frac{4}{x}   \\
\frac{x^2}{4}  +\frac{y^2}{25}  =  1   \\
\frac{\left( \frac{4}{y}  \right)^2}{4}  +\frac{y^2}{25}  =  1  \\
\frac{4}{y^2}  +\frac{y^2}{25}   = 1   \\
100 +  y^4   =   25y^2   \\
  y^4   - 25y^2  + 100   = 0  \\
t^2   -  25t  + 100  = 0   \\
 (t  - 5)(t - 20) =  0   \\
\left\{ \\
\begin{array}{l} 
t = 5  \\
t = 20  
\end{array}
\right. \\
\left\{ \\
\begin{array}{l} 
x = \pm \sqrt{ 5 }  \\
x = \pm 2\sqrt{ 5 }  
\end{array}
\right. \\
\end{array}
$$

