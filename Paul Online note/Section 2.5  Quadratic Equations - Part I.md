

# #definition  
Quadratic  Equation   
Standard from of a quadratic equation is 

$$
ax^2   + b x + c =   0  \; a \neq  0  
$$
The only requirement  is that we have  x^2  in the equation  . We guarantee this term  by the requirement  $a\neq0$  . Note  that b and c can be 0  
There are  many way to solve a  quadratic equation . We will be presenting 4  way . For the first two  method it is easy to implement but does not work  for all cases  . On the other  hand,  the last two method  will always work  but require more attention  to  work 


##  solving by factoring  
we are solving the equation first by  factoring them  . we will implement  the following  thing ;  

$$if ;\  ab = 0  \;  then \; either \; a = 0  \; and \; or b  = 0 $$ 

This fact is called the **zero factor property** or **zero factor principle**  .  All the fact  is saying that if the product of the two term is  0  then at least one have to be zero to start with  
Note that this method only work if the product of the terms is zero . To solve a  quadratic equation by  factoring we first must move all the terms over to one side of the equation . Doing it this way serve two purpose   .First is converting  the quadratic into a form that can be factor  .  Secondly  ,  to  have zero  factor there must be  a zero  on one side of the equation . 
Let show  a couple of example  . If you need to understand  more deeply factoring go to[[Factoring Polynomials]] 


$$
\begin{array}  {l} 
x^2  - x  =  12   \\
x^2  -  x  - 12  =  0     \\
(x  - 4)(x  +  3 ) =    0    \\
\left\{
\begin{array}{l}
x  - 4 = 0  \\
y + 3 = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  = 4 \\
y =  - 3  \\

\end{array}
\right.
\right. 

\end{array}  


$$
$$
\begin{array}  {l} 
x^2    +  40    =  -14x     \\ 
x^2    +  14x  +  40   =  0  \\
(x  +  10  ) ( x  +   4 )  =  0    \\
 \\
\left\{
\begin{array}{l}
x  +  10  = 0  \\
x  +   4 = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  = -10  \\
y =  - 4 \\

\end{array}
\right.
\right. 
\end{array}  
$$

$$
\begin{array}  {l} 
y^2   +  12y  +  36   =  0   \\
(y   +  6) ( y + 6 )  =  0   \\
\left\{
\begin{array}{l}
y   +  6  = 0  \\
y   +  6 = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  = -6  \\
y =  - 6 \\

\end{array}
\right.
\right. 

\end{array}  
$$




$$
\begin{array}  {l} 
4m^2−1=0   \\
(2m +  1) (2m  - 1)  =  0 \\
\left\{
\begin{array}{l}
2m +  1  = 0  \\
2m  - 1 = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  =-\frac{1}{2} \\
y =  \frac{1}{2} \\

\end{array}
\right.
\right. 
\end{array}  
$$




$$
\begin{array}  {l} 
3x^2=2x+8  \\
3x^2  -  2x   -  8  =  0   \\
(x    -  2 ) ( 3x +   4 )     =    0   \\
 \\
\left\{
\begin{array}{l}
x    -  2  = 0  \\
3x +   4  = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  =2\\
y =  -\frac{4}{3} \\

\end{array}
\right.
\right. 
\end{array}  
$$






$$
\begin{array}  {l} 
10z^2+19z+6= 0   \\
 (2x+3 )  (5x  + 2  )  =     0   \\
 \\
\left\{
\begin{array}{l}
2x+3 = 0  \\
5x  + 2   = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
y  =\frac{-2}{5}\\
y =  -\frac{-3}{2} \\

\end{array}
\right.
\right.   
\end{array}  
$$


$$
\begin{array}  {l} 
  
5x^2=2x  \\
5x^2  -  2 x  =  0    \\
x(5x  - 2  )     =    0  \\

\left\{
\begin{array}{l}
5x  - 2   = 0  \\
x= 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
x =  0 \\
x =  \frac{2}{5} \\

\end{array}
\right.
\right.   
\end{array}  
$$


work  on another types of problems since they are also  Quadratic Equation  
$$
\begin{array}  {l} 
  
\frac{1}{x+ 1}  =   1   -  \frac{5}{2x -  4  }   \\
(2x  -  4)  =   (2x  -  4)(x + 1 )       -  5(x + 1 )     \\
2x  - 4    =    2x^2   +  2x   -  4x   -  4    -  5 x - 5   \\
-2x^2 + 9x   + 5    =  0   \\
2x^2  -9x   - 5  = 0  \\
( 2x   + 1  )  (x   - 5)  =   0   \\


\left\{
\begin{array}{l}
x   - 5  = 0  \\
2x   +  1 = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
x =  5\\
x =   -  \frac{1}{2} \\

\end{array}
\right.
\right.   
\end{array}  
$$
neither of them are value of x we need to avoid so the solution is  both 

$$
\begin{array}  {l} 
x   +  3  +  \frac{3}{x -  1 }  =  \frac{4  - x } { x   -  1 }  \\
x(x   -  1  )   +  3(x   -  1 )  +  3    =   4  - x    \\
x^2    - x  +  3x - 3    +  3  =   4   -  x    \\
x^2  +     3x     - 4   =  0   \\
(x +  4)(x    -  1  )  =    0   \\
  

\left\{
\begin{array}{l}
x +  4  = 0  \\
x    -  1  = 0   \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
x =   - 4\\
x = 1  \\

\end{array}
\right.
\right.   
\end{array}  
$$ we see that the solution to the problem  is   x = -4  , because when plug in  -1  it will create an error  

let used equation  with larger than two degree   ?  

$$
\begin{array}  {l} 
5x^3  -  5x^2   - 10x =  0    \\
x  (5x^2  -  5x  - 10 ) =  0      \\
x  (x -  2  ) (x  + 1  )  =   0   \\
  

\left\{
\begin{array}{l}
x =  2 \\
x     = - 1   \\
x   = 0 
\end{array}
\right.   
\end{array}  
$$ 


#  Square Root  property  
$$
p^2   =   d   \; then  \;  p =  \pm   \sqrt{ d }
$$

$$
\begin{array}  {l} 
x^2   -  100  =    0   \\
x  (5x^2  -  5x  - 10 ) =  0      \\
x  (x -  2  ) (x  + 1  )  =   0   \\
  

\left\{
\begin{array}{l}
x =  2 \\
x     = - 1   \\
x   = 0 
\end{array}
\right.   
\end{array}  
$$