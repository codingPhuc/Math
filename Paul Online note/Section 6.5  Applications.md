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
20  =  e^{0.195 \cdot  t }   \\
 0.195 \cdot  t    = \ln 20   \\
t   = 15.3627\\
\end{array}
$$
Carbon 14 dating works by measuring the amount of Carbon 14 (a radioactive element) that is in a fossil. All living things have a constant level of Carbon 14 in them and once they die it starts to decay according to the formula, 

$$
Q   = Q_{0} e^{  
−0.000124t}
$$
where t is in years and Q0Q0 is the amount of Carbon 14 present at death and for this example let’s assume that there will be 100 milligrams present at death.

1. How much Carbon 14 will there be after 1000 years?
$$
\begin{array}{l}
Q   = Q_{0} e^{  −0.000124t}   \\
Q   = 100 e^{  −0.000124\cdot 1000}   \\
Q   =  88.338 milligrams \\

\end{array}
$$

2. How long will it take for half of the Carbon 14 to decay?

$$
\begin{array}{l}
 50   = 100 e^{  −0.000124t}    \\
 50   = 100 e^{  −0.000124t}   \\
e^{  −0.000124t}   = \frac{1}{2  }  \\
−0.000124t   =  \ln(\frac{1}{2  } )  \\
t =  5589.89661742
\end{array}
$$


## Earthquake  Intensity  
The **Richter scale** is commonly used to measure the intensity of an earthquake. There are many different ways of computing this based on a variety of different quantities. We are going to take a quick look at the formula that uses the energy released during an earthquake.

If EE is the energy released, measured in joules, during an earthquake then the magnitude of the earthquake is given by, 


$$
 M  = \frac{2}{3 } \log \left( \frac{E}{E_{0}} \right)
$$

where  $E_{0}   =  10^{4\cdot 4}$ 
If $8×10^{14}$ joules of energy is released during an earthquake what was the magnitude of the earthquake? 



$$
\begin{array}{l}
M  = \frac{2}{3 } \log \left( \frac{8\cdot  10^{14}}{10^{4.4}} \right)  \\
=   
7.002
\end{array}
$$



 How much energy will be released in an earthquake with a magnitude of 5.9?


$$
\begin{array}{l}
5.9 = \frac{2}{3 } \log \left( \frac{E}{10^{4.4}} \right)  \\
8.85  =  \log \left( \frac{E}{10^{4.4}} \right)    \\
10^{8.85}   =  \frac{E}{10^{4.4}  }  \\
E  =  13.25 
\end{array}
$$


We have $10,000 to invest for 44 months. How much money will we have if we put the money into an account that has an annual interest rate of 5.5% and interest is compounded
 
1. quarterly
 2. monthly
 3. continuously 

$$
\begin{array}{l} \\
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  } \\
A  = 10000\left( 1  + \frac{0.055}{4} \right)^{\frac{11}{3} \cdot 4 } \\
A = 12217
\end{array}
$$


$$
\begin{array}{l} \\
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  } \\
A  = 10000\left( 1  + \frac{0.055}{12} \right)^{\frac{11}{3} \cdot 12} \\
A = 12228 
\end{array}
$$

$$
A =   10000e^{0.055 \cdot 11/3} =  12234 
$$


We are starting with $5000 and we’re going to put it into an account that earns an annual interest rate of 12%. How long should we leave the money in the account in order to double our money if interest is compounded

1. quarterly

$$
\begin{array}{l} \\
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  } \\
10000  = 5000\left( 1  + \frac{0.12}{4} \right)^{t\cdot 4 }  \\
2 = \left( 1  + \frac{0.12}{4} \right)^{t\cdot 4 }    \\
\log_{1.03} 2   = 4t  \\
t = 5.86 \\
A = 12217
\end{array}
$$
 1. monthly
$$
\begin{array}{l} \\
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  } \\
10000  = 5000\left( 1  + \frac{0.12}{12} \right)^{t\cdot 12 }  \\
2 = \left( 1  + \frac{0.12}{12} \right)^{t\cdot 12 }    \\
\log_{1.01} 2   = 12t  \\
t = 5.80 \\
A = 12217
\end{array}
$$
 2. continuously


$$
\begin{array}{l} \\
A  = P\left( 1  + \frac{r}{m} \right)^{t \cdot m  } \\
10000  = 5000\left( 1  + \frac{0.12}{4} \right)^{t\cdot 4 }  \\
2 = \left( 1  + \frac{0.12}{4} \right)^{t\cdot 4 }    \\
\log_{1.03} 2   = 4t  \\
t = 5.86 \\
A = 12217
\end{array}
$$


A population of bacteria initially has 250 present and in 5 days there will be 1600 bacteria present.

1. Determine the exponential growth equation for this population.
2. How long will it take for the population to grow from its initial population of 250 to a population of 2000?



We initially have 100 grams of a radioactive element and in 1250 years there will be 80 grams left.

1. Determine the exponential decay equation for this element.
2. How long will it take for half of the element to decay?
3. How long will it take until there is only 1 gram of the element left?