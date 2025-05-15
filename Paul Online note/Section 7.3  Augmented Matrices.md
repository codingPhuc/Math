---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-05-14"
amount of time: 
learning score:
---
in this section we need to talk about the third method of solving systems of equations . 
For systems with two equation it is much more complicated when compare to the pervious section  , but for system with three or more equation it is easier 

we first need to get some definition out of the way . 

An augmented matrix for a system of equation is a matrix of number where each row represents the constant from one equation( both the coefficient  and constant on the other side of the equal sign) and each column represent all the coefficients for a single variable 




$$
\left[\begin{array}{ccc|c} 
1 & -2 & 3 & 7 \\
2 & 1 & 1 & 4 \\
-3 & 2 & -2 & -10
\end{array}\right]
$$

The first row show us all the constant numbers like the coefficient of x ,y z and the constant left of the equal sign on the left . Similarly , the same is true for the remaining row  . The dash line represent where the equal sign was originally 


Next we will discuss the elementary row operation  . There are three of them and we will give a notation used for each one 
1. **Interchange two Rows** . With this operation we will interchange all entries in row i and row j . The notion  we will used here is $R_{i} \leftrightarrow R_{j}$ . Here is an example 
$$
 \begin{bmatrix}1&-2&3&7\\2&1&1&4\\-3&2&-2&-10\end{bmatrix}R_1\leftrightarrow R_3\begin{bmatrix}-3&2&-2&-10\\2&1&1&4\\1&-2&3&7\end{bmatrix}
$$so we do exactly as the operation say every  entry on the first row move down to the third rows , every entry on the third rows move up to the first row .  
2. **Multiply a Row by a Constant** .In this operation we will multiply row i by a constant c and the notion will be used here is  $cR_{i}$ , note as well that we can divided a row by a constant using the notation$\frac{1}{c}R_{i}$ here is an example  

$$
\left.\left[\begin{array}{rrrr}1&-2&3&7\\2&1&1&4\\-3&2&-2&-10\end{array}\right.\right]\begin{array}{rr}-4R_3\\\to\end{array}\begin{bmatrix}1&-2&3&7\\2&1&1&4\\12&-8&8&40\end{bmatrix}
$$


3.  **Add a Multiple of rows to Another Rows**  In this operation we will replace row i with the sum of row i and constant c , times row  j .The notation that we will be using for this operations is $R_{i} +cR_{j}\xrightarrow{\text{}}Ri$   . Here is and example operation 
$$
 \left.\left[\begin{array}{rrrr}1&-2&3&7\\2&1&1&4\\-3&2&-2&-10\end{array}\right.\right]R_3-4R_1\to R_3\begin{bmatrix}1&-2&3&7\\2&1&1&4\\-7&10&-14&-38\end{bmatrix}
$$

Go  through the individual computation to make sure you followed this  : 
$$
\begin{array}{l} \\
-3  - 4( 1 )  =  -7  \\
2 -  4 ( -2)  =  10   \\
-2  - 4(3)  =  -14  \\
-10   - 4(7)  = -38 
\end{array}
$$
we will start with a system of two equations and two unknowns 
$$
\begin{array}{l}
ax + by  =  p  \\
cx  + dy  = q  
\end{array}
$$
we first will write down the argument matrix 

$$
\left[ \begin{array}{cc|c}  
a  &  b  &  p  \\
c  &  d  &  q 
\end{array} \right] 

$$
and used elementary row operations to convert it into the following matrix 
$$
\left[\begin{array}{cc|c}  
1 &  0  &  h  \\
0  &  1  &  k 
\end{array}\right]
$$
The solution to the system will be  $x=h \text{ and } y=k$
This method is called **Gauss-Jordan Elimination**

$$\begin{array}{l}
 3x - 2 y  =  14   \\
x + 3 y  = 1  
\end{array}
$$

$$
\left[ \begin{array}{cc|c}  
3  &  -2  &  14  \\
1  &  3  &  1  
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
3  &  -2  &  14  \\
1  &  3  &  1  
\end{array} \right] 
R_1\leftrightarrow R_2
\left[ \begin{array}{cc|c}  
1  &  3  &  1     \\
3  &  -2  &  14  \\
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}  
1  &  3  &  1     \\
3  &  -2  &  14  \\
\end{array} \right] 
R_{2}  -3R_1 \to R_2 
\left[ \begin{array}{cc|c}  
1  &  3  &  1     \\
0 &  -11  &  11  \\
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}  
1  &  3  &  1     \\
0 &  1  &  -1  \\
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}  
1  &  3  &  1     \\
0 &  1  &  -1  \\
\end{array} \right] 
R_{1}  -3R_2 \to R_1 
\left[ \begin{array}{cc|c}  
1  &  0  &  4     \\
0 &  1  &  -1  \\
\end{array} \right] 
$$

y  =  -1  
x  =  4  




$$
\begin{array}{l}
3x  -6y = -9  \\
-2x -  2y  = 12  
\end{array}
$$

$$
\left[ \begin{array}{cc|c}
 3 &  -6  &  -9  \\
-2  &  -2  &  12   
\end{array} \right] 
$$

$$
\left[ \begin{array}{cc|c}
 3 &  -6  &  -9  \\
-2  &  -2  &  12   
\end{array} \right] 
-\frac{1}{2}R_{2} \to 
\left[ \begin{array}{cc|c}
 3 &  -6  &  -9  \\
1  &  1  & -6 
\end{array} \right] 
$$



$$
\left[ \begin{array}{cc|c}
 3 &  -6  &  -9  \\
1  &  1  &  -6   
\end{array} \right] 
R_1\leftrightarrow R_2
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 3 &  -6  &  -9  
\end{array} \right] 
$$
$$
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 3 &  -6  &  -9  
\end{array} \right] 
R_{2}  -3R_1 \to R_2 
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 0 &  -9  &  9
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 0 &  -9  &  9
\end{array} \right] 
-\frac{1}{9}R_{9} \to 
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 0 &  1  &  -1 
\end{array} \right] 
$$


$$
\left[ \begin{array}{cc|c}
1  &  1  &  -6    \\
 0 &  1  &  -1 
\end{array} \right] 
R_{1}  -R_2\to R_1 
\left[ \begin{array}{cc|c}
1  &  0  &  -5    \\
 0 &  1  & -1 
\end{array} \right] 
$$
x=     -5
y = -1  



It is important to note that the path we used to get a augmented matrix in the final form is not the only path that we could used . All the path should arrive at the same final augmented matrix however so we could choose the path that feel the easiest . Note as well that different paths may be easier so may well solve the systems differently 

for system of equation with only two  solution , this process seem a little bit more complicated then what we are used to  . However  , for system  of equation that are more than 2 equation , this process is perfect to solve 

$$
\left[\begin{array}{ccc|c}  
1 &  0  &  0   &  p  \\
0  &  1  &  0  &   q   \\
0  &  0  &  1  &  r 
\end{array}\right]
$$
one the argument matrix is in this form  the solution is $x = p,y=q,z=r$ . 

## Solve each of the following systems of equations. 
$$
\begin{array}{l} \\
3x  + y  - 2z   = 2   \\
x   - 2y + z =  3   \\
2x -  y  - 3z  = 3  
\end{array}
$$

$$
\left[\begin{array}{ccc|c}  
3 &  1  &  -2   &  2  \\
1  &  -2 &  1  &   3   \\
2  &  -1  &  -3  &  3 
\end{array}\right]
$$
$$
\left[\begin{array}{ccc|c}  
3 &  1  &  -2   &  2  \\
1  &  -2 &  1  &   3   \\
2  &  -1  &  -3  &  3 
\end{array}\right]
R_1\leftrightarrow R_2
\left[\begin{array}{ccc|c}  
1  &  -2 &  1  &   3    \\
3 &  1  &  -2   &  2  \\
2  &  -1  &  -3  &  3 
\end{array}\right]
$$



$$
\left[\begin{array}{ccc|c}  
1  &  -2 &  1  &   3    \\
3 &  1  &  -2   &  2  \\
2  &  -1  &  -3  &  3 
\end{array}\right]
R_{2}  -3R_1 \to R_2 
\left[\begin{array}{ccc|c}  
1  &  -2 &  1  &   3    \\
0 &  7  &  -5   &  -7  \\
2  &  -1  &  -3  &  3 
\end{array}\right]
$$

$$
\left[\begin{array}{ccc|c}  
1  &  -2 &  1  &   3    \\
0 &  7  &  -5   &  -7  \\
2  &  -1  &  -3  &  3 
\end{array}\right]
R_{2}  -2R_1 \to R_2 
\left[\begin{array}{ccc|c}  
1  &  -2 &  1  &   3    \\
0 &  7  &  -5   &  -7  \\
0  &    &  -3  &  3 
\end{array}\right]
$$