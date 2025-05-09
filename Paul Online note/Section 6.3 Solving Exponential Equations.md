---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-08
amount of time: 30 +
learning score:
---


There are two method of solving  exponential equation . One method is simple but require a special form of exponential  equation . The other will work on  more complicated  exponential equation but can get a little messy 
let start by having a look at these simple method  ; 
$$
\text{if } b^x   = b^y  \text{ then } x =  y  
$$
if it isn't then this fact will do us no good 
$$
\begin{array}{l} \\
5^{3x}  =  5^{7x  - 2}    \\
3x  =  7x   - 2   \\
x = \frac{1}{2}
\end{array}
$$

$$
\begin{array}{l}  \\
4^{t^2} = 4^{6 - t}  \\
t^2  = 6 - t\\
t^2   -  6 +  t  =  0    \\
\left \{ 
t =   -3    \\
t =  2   
 \right.
\end{array}
$$

#fail 
$$
\begin{array}{l} \\
3^z   =  9^{z  +  5}    \\
z  =  2z  + 10  \\
 z   = -10   
\end{array}
$$

$$
\begin{array}{l}  \\
4^{5 - 9x}   =  \frac{1}{2^{3(x - 2)}}     \\
2^{2(5 - 9x)}  =  2^{-3(x - 2)}     \\
10  - 18x   =  -3x   +  6      \\
- 15x  =   -4  \\
 x =   \frac{4}{15}   \\
\end{array}
$$

the equation  that we solve  above relieve on the fact that the same base exponential  is the same . However , this is not always correct  . Consider the following 

$$
7^x  =  9 
$$there  is no easy way to find the number x that seven is raise to to get 9 . In fact this is exactly what this equation is asking us to find . The problem here is the x in the exponent , because of that all our knowledge for solving exponent won't do us any good  we need a way to get x out of the exponent . Lucky for us we have way to do that .  Recall this algorithm  from the last section  

$$
\log_{b}{a^r}   =  r \log_{b}a 
$$
note to avoid  confusion with x  we replace x in this with an a . the important part is that we take an exponent  and move it to the font of the term 
So , if we had , 

$$
\log_{b}7^x 
$$

we could use this property as follow 
$$
x\log_{b}7 
$$
the reality  is that we can use any logarithm to do this so we should pick one that we are good at . This mean that we will be working with common logarithm and natural  logarithm 
$$
\begin{array}{l}  \\
7^x  =  9   \\
\log 7^x  =  \log 9 \\
x   \log 7  = \log 9  \\
x =  \frac{\log 9}{\log 7}  = 1.129150069
\end{array}
$$
also be careful  to not make the following mistake   
$$
\frac{\log 9}{\log 7}  = 1.129150069  \neq  0.2513144283    =  \ln\left( \frac{9}{7} \right)
$$

$$
\begin{array}{l}
2^{4y  + 1}   - 3^{y} =  0   \\
\log{2^{4y  + 1}  }   - \log{3^{y} }    =0   \\
(4y + 1)\log{2}  - y\log{3}  =   0  \\
 4y\log{2} - y\log{3}   + \log{2}     = 0  \\
y( 4\log{2} -  \log{3}   ) = - \log{2}  \\
y  =  −0.414072245
\end{array}
$$

$$
\begin{array}{l}
e^{t +  6}  = 2  \\
\ln {e^{t +  6} }  = \ln{2} \\
(t+ 6)   =  \ln{2}  \\
   t = −5.30685202 
\end{array}
$$


$$
\begin{array}{l}
e^{t +  6}  = 2  \\
\ln {e^{t +  6} }  = \ln{2} \\
(t+ 6)   =  \ln{2}  \\
   t = −5.30685202 
\end{array}
$$
noted how we didn't take the exponent out right always due to the following properties 
$$
\ln e^{f(x)}    =  f(x)
$$
this simply the process for us  


#fail 
$$
\begin{array}{l}
10^{5 - x}  = 8     \\
2^{5 - x}  \cdot  5^{5 -x } = 2^{3}   \\
5^{5 -x }   =  2^{-2+x }  \\
(5 -x ) \ln{5}   = (-2+x ) \ln{2}   \\
 5\ln{5}  - x\ln{5}  =  -2 \ln{2} +x\ln{2}   \\
 x  =5 
\end{array}

 
$$

$$
\begin{array}{l}
10^{5 - x}  = 8  \\
\log{10^{5- x}}   =   \log{8}  \\
5-x  =  \log{8}  \\
x  =  - \log{8}   +  5 = 4.096910013
\end{array}
$$

$$
\begin{array}{l}  \\
  5e^{2x  +4}   - 8 =   0   \\
\ln{5e^{2x  +4}}     =  \ln{2^3}     \\
\ln 5 +   \ln e^{2x  +4}  =  3\ln2   \\
\ln 5 +  2x  +4   = 3 \ln2    \\
x  = −1.76499819 
\end{array}
$$


# #Practice_Exercise  

$$
\begin{array}{l}  \\
6^{2x}  =   6^{1-3x  }   \\
2x  =   1 - 3x   \\
5x   = 1    \\
x  = \frac{1}{5} 
\end{array}
$$


$$
\begin{array}{l}  \\
5^{1 -x   }   =  25   \\
5^{1 -x }  =  5^2     \\
1-x  =  2   \\
x  =  -1  
\end{array}
$$


$$
\begin{array}{l}  \\
8^{x^2}  =   8^{3x + 10}\\
x^2 =   3x + 10   \\
x^2  =  3x + 10    \\
x^2   - 3x  - 10  =   0   \\ \\
\left \{  \\
 \begin{array}{l}
t =   -3    \\
t =  2   
\end{array}
 \right.
\end{array}
$$




$$
\begin{array}{l}  \\
7^{4-x }  =  7^{4x}  \\
4 - x   =   4x    \\
x  =  \frac{4}{5}x   
\end{array}
$$

