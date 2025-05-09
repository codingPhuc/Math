---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-09
amount of time: 20 +
learning score:
---

In this section we will now take a look at solving logarithm equation , equation with logarithm in them .  in particular  , we will be looking at which term is a logarithm and we will also look at equation in that all but one term in the equation is a logarithm and the term without the logarithm  is a constant 

Before we move on remember the constrain that we can only plug positive number into a logarithm . This will be important down the road 

$$
\text{ if } \log_{b}y  \text{  then  }  x =  y 
$$

if we've got two logs in the problem ,  one on either side of the equal with both a coefficient  of one and the same base . Then we can drop the logarithms 
## Solve each of the following equations.  

$$
\begin{array}{l}
2 \log_{9}{\sqrt{ x }   }  - \log_{9}{(6x  -1 )}  = 0    \\
 \log_{9}{x }   =    \log_{9}{(6x  -1 )}       \\
x    =  6x  -1   \\
x  = \frac{1}{5}    \\
\end{array}
$$



$$
\begin{array}{l}
\log x   + \log (x  -1 )  =  \log (3x + 12)   \\
\log (x  -1 )x    =   \log (3x + 12)     \\
x( x  -1 )  =  3x + 12   \\
x^2  -4x  -  12  =   0   \\
\left\{  \\
 \begin{array}{l} 
x=  6 \\
x =  -2\\
\end{array}
 \right.
\end{array}
$$
Now , we must check them in the original equation. 
checking x  =  6 
$$
\log 6  + \log (6 -1)  =  \log( 3  \cdot 6   + 12 )    \implies log6+log5=log30
$$
no negative log for this number 

checking x = -2  
$$
\log -2   + \log (-2  -1 )  =  \log (3\cdot  -2   + 12)
$$
we don't need to go any further there is a negative number in the second terms 
be careful with the thinking that we didn't take  -2  because it was a negative number . We didn't take it because when plug into the equation it produce a negative logarithm 
. The same line of reason can be said about x = 6 , we didn't take it because it was a positive number , but because when  plug in there is no logarithm that is less than  0 






$$
\begin{array}{l}
\ln 10  - \ln(7 - x ) =  \ln  x   \\
 \ln \frac{10}{(7 - x )}  =  \ln x  \\
\frac{10}{7 -x}  =  x     \\
10 =   -x^2 + 7x   \\
  x^2   - 7x  + 10   =    0   \\
\left\{  \\
 \begin{array}{l} 
x=  5  \\
x =  2 \\
\end{array}
 \right.
\end{array}
$$

checking  x =2   
$$
\begin{array}{l}
 \ln 10   -  \ln( 7 -2 )   = \ln 2 \\  \ln 10   -  \ln( 5)   = \ln 2  \\
\end{array}
$$
this one is okay 
checking x = 5 
$$
\begin{array}{l}
 \ln 10   -  \ln( 7 -5)   = \ln 5 \\  \ln 10   -  \ln( 2)    = \ln 5  \\
\end{array}
$$
this one is okay 
in this cases both solution satisfy the condition  


we need to take a look at the second kind of logarithm equation that we will be solving . This equation will have a term one being logarithm and the other that does not have a logarithm will be a constant 

## solve each of the following equation 

$$
\begin{array}{l}
\log_{5} (2x  + 4)  = 2  \\
\log_{5} (2x  + 4)   =  \log_{5}32  \\
 2x  + 4  =  32    \\
x  =  14 \\

\end{array}

$$



$$
\begin{array}{l}
\log x  =  1  - \log(x - 3)  \\
\log x  = \log 10  -  \log(x - 3)      \\
x =   \frac{10}{x - 3}  \\
x^2  -3x  - 10   =0 \\ 
\left\{  \\
 \begin{array}{l} 
x= 5   \\
x =  -2 \\
\end{array}
 \right.
\end{array}

$$



checking  x =5   
$$
\begin{array}{l}
\log 5  =  1  - \log(5- 3) \\ \log 5  =  1  - \log(2)  \\
\end{array}
$$
this one is okay 
checking x = -2 
$$
\begin{array}{l}
\log -2  =  1  - \log(-2 -  3) \\ \log -2  =  1  - \log(-5) \\
\end{array}
$$

this one is not okay since the logarithm from  of the second term on the right side of the equal sign  is negative 
in this case only the solution x =  5 satisfy the condition 



$$
\begin{array}{l}
\log_{2}(x^2  - 6x)  =  3 +  \log_{2}(1 - x)    \\
\log_{2}(x^2  - 6x)  =  \log_{2}8 +  \log_{2}(1 - x)    \\
  \log_{2}(x^2  - 6x)  =  \log_{2}(8\cdot  (1 - x) )   \\
x^2  - 6x   =  8  -  8x    \\
x^2 +  2x    - 8   =  0   \\
\left\{  \\
 \begin{array}{l} 
x=  -4   \\
x =  2 \\
\end{array}
 \right.
\end{array}

$$



checking  x =-4
$$
\begin{array}{l}
\log_{2}((-4)^2  - 6\cdot -4)  =  3 +  \log_{2}(1 + 4) \\ \log_{2}(40)  =  3 +  \log_{2}(5) \\
\end{array}
$$
this one is okay 
checking x = 2 
$$
\begin{array}{l}
\log_{2}((2)^2  - 6\cdot 2)  =  3 +  \log_{2}(1 -2 )\\ \log_{2}((2)^2  - 6\cdot 2)  =  3 +  \log_{2}(-1 )\\
\end{array}
$$

this one is not okay since the logarithm from  of the second term on the right side of the equal sign  is negative 
in this case only the solution x =  -4  satisfy the condition 


# #Practice_Exercise  



$$
\begin{array}{l}
\log_{4}(x^2 - 2x)  = \log_{4}(5x  -12 )  \\
x^2 - 2x  =  5x  - 12   \\
x^2  -7x  + 12   = 0   \\
\left\{  \\
 \begin{array}{l} 
x=  -4   \\
x =  -3  \\
\end{array}
 \right.
\end{array}
$$



$$
\begin{array}{l}
\log(6x)  - \log(4 -x )  = \log3   \\
\log\left( \frac{6x}{4-x}  \right)  =   \log 3   \\
 \frac{6x}{4-x} = 3   \\
 6x  =  12  -3x    \\
 x  =  \frac{4}{3}\\
\left\{  \\
 \begin{array}{l} 
x=  -4   \\
x =  2 \\
\end{array}
 \right.
\end{array}

$$

checking  x = -4
$$
\begin{array}{l}
\log(6 \cdot  -4)  - \log(4 + 4 )  = \log3 \\ \log(-24)  - \log(8  )  = \log3  \\
\end{array}
$$
this one is not okay since the logarithm from  of the first term on the left side of the equal sign  is negative 
checking x = 2
$$
\begin{array}{l}
\log(6\cdot 2)  - \log(4 -2 )  = \log3     \\
\log(12)  - \log(2 )  = \log3  
\end{array}
$$

this one is not okay since the logarithm from  of the second term on the right side of the equal sign  is negative 













$$
\begin{array}{l}
\ln x  + \ln (x  + 3)  = \ln (20 -  5x)  \\
\ln(x(x  + 3))  = \ln (20 -  5x)     \\
x^2   +  3x  =  20 -  5x   \\
x^2 + 8x  - 20  = 0   \\  
\left\{  \\
 \begin{array}{l} 
x=  -10     \\
x =  2 \\
\end{array}
 \right.
\end{array}

$$





checking  x = - 10 
$$
\begin{array}{l}
\ln - 10   + \ln (- 10   + 3)  = \ln (20 -  5\cdot - 10  )  
\end{array}
$$
this one is not okay since the logarithm from  of the first term on the left side of the equal sign  is negative 
checking x = 2
$$
\begin{array}{l}
\ln 2+ \ln (2 + 3)  = \ln (20 -  5\cdot 2)    \\
\ln 2+ \ln (5)  = \ln (10)   
\end{array}
$$

this one is okay  




#fail 


$$
\begin{array}{l}
\log_{3}(25  -x^2)  =  2   \\
\log_{3}(25  -x^2)  =  \log_{3}9  \\
25  -x^2  =  9    \\
x^2 = 16 \\  
\left\{  \\
 \begin{array}{l} 
x=  -4   \\
x =  4 \\
\end{array}
 \right.
\end{array}

$$
checking  x = - 4
$$
\begin{array}{l}
\log_{3}(25  -(-4)^2)  =  2    \\
\log_{3}(9)   =2   
\end{array}
$$
this on is okay 
checking x = 4
$$
\begin{array}{l}
\log_{3}(25  -(4)^2)  =  2    \\
\log_{3}(9)   = 2   
\end{array}
$$

this one is okay  

since both solution satisfy the condition that the logarithm form should not be negative , we take both the solution 







$$
\begin{array}{l}
\log_{2}(x  +1  ) - \log_{2}(2-x) =  3   \\
\log_{2}(x  +1  )  =  \log_{2}(2-x) + \log_{2}8   \\
x + 1   = 16  - 8x    \\
 9x  =  15  \\
x =  \frac{5}{3}

\end{array}

$$





$$
\begin{array}{l}
\log_{4}(-x)   + \log_{4}(6-x ) =  2 \\
\log_{4}(-x (6-x) ) =  \log_{4}16  \\
-x (6-x)   =16   \\
 x^2  - 6x  -  16 =  0    \\
\left\{  \\
 \begin{array}{l} 
x=  -8  \\
x =  2  \\
\end{array}
 \right.

\end{array}

$$



checking  x = - 8
$$
\begin{array}{l}
\log_{4}(8)   + \log_{4}(6 + 8 ) =  2 \\
\log_{4}(8)   + \log_{4}(14 ) =  2  
\end{array}
$$
this on is okay 
checking x = 4
$$
\begin{array}{l}
\log_{2}(x  +1  ) - \log_{2}(2-x) =  3    \\
\log_{3}(9)   = 2   
\end{array}
$$

this one is okay  

since both solution satisfy the condition that the logarithm form should not be negative , we take both the solution 


