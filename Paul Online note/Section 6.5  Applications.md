in this final section of the chapter we will look at applications of exponential and logarithm function 

## Compound Interest 

This application is compound interest and there are two application that we will be looking at . 

If were to Put P dollar into an account that earns interest rate of r (written as decimal) for t years (yes , it must be years) 

1. If interest is compound m times per year we will have 
$$
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  }
$$

dollars after t year 
2. if interest i compound continuously then  we will have 
$$
A =   Pe^{r \cdot t}
$$
dollar after t years  


Example 1 We are going to invest $100,000 in an account that earns interest at a rate of 7.5% for 54 months. Determine how much money will be in the account if,
1. interest is compounded quarterly.
$$
A  = 100,000\left( 1  + \frac{7.5}{12} \right)^{4.5 \cdot 12}  = 139706.68 
$$

2. interest is compounded monthly.
$$
A  = 100,000\left( 1  + \frac{7.5}{4} \right)^{4.5 \cdot 4 }  = 1399996 
$$
3. interest is compounded continuously. 


$$
A =  100000 \cdot e^{0.075 \cdot 4.5}   = 140143   
$$
As pointed out in the first part of this example it is important to not round too much before the final answer 
$$
\begin{array}{l} \\
A = 100000 \left( 1 + \frac{0.075}{4}  \right)^{4 \cdot 4.5 }  \\
= 100000 \cdot (1.019[1.01875])^{18}   \\
 =  100000 (1.403[1.403250844])  \\
  = 140,300.00 
\end{array}
$$
due to the continuous cutting off of decimal the value is off by 593.31 . As a result , as a general  rules of thumb do not cut of decimal number until the final point 

##  Let’s now look at a different kind of example with compounding interest.  
We are going to put $2500 into an account that earns interest at a rate of 12%. If we want to have $4000 in the account when we close it how long should we keep the money in the account if,
1. we compound interest continuously.
$$
\begin{array}{l} \\
4000 =   2500e^{0.12 \cdot t}   \\
e^{0.12 \cdot t}  = 1.6  \\
0.12 \cdot t =  \ln 1.6  \\
t =  \frac{\ln{1.6}}{0.12}   = 3.917 
\end{array}
$$





2. we compound interest 6 times a year.  
$$
\begin{array}{l}
4000  = 2500 \cdot \left( 1  + \frac{0.12}{6} \right)^{t \cdot 6  }   \\
\frac{8}{5}   =  \left( 1  + \frac{0.12}{6} \right)^{t \cdot 6  }   \\
\log_{\frac{51}{50} } \frac{8}{5}  =   t\cdot 6   \\
t =  \frac{\left( \log_{\frac{51}{50} } \frac{8}{5} \right)}{6}   \\
= 3.956  
\end{array}
$$


## Exponential  Growth and decay  

there are many qualities  out there in the world that is govern by the  by the equation 
$$
Q  =  Q_{0}e^{k\cdot  t}
$$
where $Q_{0}$ is positive and is the amount initially present at $t=0$ and k is a non zero constant . If k is positive then the equation will grow without bound and will be called the $exponential\; growth$ equation . Likewise , if k is negative than the equation will be zero  and is called the **exponential decay**  equation  

Short term population growth is often modeled by the exponential growth equation and the decay of a radioactive element is governed the exponential decay equation.

The growth of a colony of bacteria is given by the equation,
$$
\begin{array}{l}
 Q = Q_{0}e^{0.195 \cdot  t}     \\

\end{array}
 
$$If there are initially 500 bacteria present and t is given in hours determine each of the following.

1. How many bacteria are there after a half of a day?
$$
\begin{array}{l}
 Q = Q_{0}e^{0.195 \cdot  t}      \\
Q = 500e^{0.195 \cdot  12 }  =  5190.61  \\
\end{array}
$$

2. How long will it take before there are 10000 bacteria in the colony?

$$
\begin{array}{l}
 Q = Q_{0}e^{0.195 \cdot  t}      \\
10000 = 500e^{0.195 \cdot  t }   \\
 \\
\end{array}
$$
