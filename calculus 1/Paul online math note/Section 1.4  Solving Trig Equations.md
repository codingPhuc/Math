---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-05
amount of time: 
learning score: https://tutorial.math.lamar.edu/Classes/CalcI/TrigEquations.aspx
---
# #definition 


##  Trig Equations  exercise


### practice 1 
$$
\begin{array}{l} 
2\sin (5x) =-\sqrt{ 3 }\text{ on } [-\pi,2\pi] \\
\sin(5x)  =  -\frac{\sqrt{ 3 }}{2} [-\pi,2\pi]  \\
\frac{\pi}{3}\left( \frac{1}{2} , \frac{\sqrt{ 3 }}{2} \right)  \implies \text{ reflection over x axis and origin} \\
  \pi + \frac{\pi}{3}  = \frac{4\pi}{3} \text{  over origin}   \\
x  =   \frac{4\pi}{15}    \\
 -\frac{\pi}{3} + 2\pi =  \frac{5\pi}{3} \text{ reflection over x axis}  \\
x  =    \frac{\pi}{3}   
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{5\pi}{3} \cap \frac{{4}\pi}{3}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
5x =  \frac{4\pi}{3} + 2\pi n  \implies  x =  \frac{4\pi}{15} + \frac{2\pi n}{5}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$

$$
5x =  \frac{5\pi}{3} + 2\pi n  \implies  x =  \frac{\pi}{3}  + \frac{2\pi n}{5}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$

given  n  = 0   : 
$$\begin{array}{l}
\frac{4\pi}{15} + \frac{2\pi}{5}  \cdot 0   = \frac{4\pi}{15}  < 2\pi\\
\frac{5\pi}{15}    + \frac{2\pi}{5}  \cdot 0   = \frac{5\pi}{15}  < 2\pi  \\  \\
\frac{4\pi}{15} - \frac{2\pi}{5}  \cdot 0   = \frac{4\pi}{15}  > -\pi\\
\frac{5\pi}{15}    - \frac{2\pi}{5}  \cdot 0   = \frac{5\pi}{15}  > -\pi  \\   
\end{array}
 
$$

given  n  = 1   : 
$$\begin{array}{l}
\frac{4\pi}{15} + \frac{2\pi}{5}  \cdot 1   = \frac{2\pi}{3} < 2\pi\\
\frac{5\pi}{15}    + \frac{2\pi}{5}  \cdot 1   = \frac{11\pi}{15}  < 2\pi  \\  \\
\frac{4\pi}{15} - \frac{2\pi}{5}  \cdot 1   = -\frac{2\pi}{15}   > -\pi\\
\frac{5\pi}{15}    - \frac{2\pi}{5}  \cdot 1   = -\frac{1\pi}{15}  > -\pi  \\   
\end{array}
 
$$




given  n  = 2   : 
$$\begin{array}{l}
\frac{4\pi}{15} + \frac{2\pi}{5}  \cdot 2   = \frac{16\pi}{15}   < 2\pi\\
\frac{5\pi}{15}    + \frac{2\pi}{5}  \cdot 2   = \frac{17\pi}{15}< 2\pi  \\  \\
\frac{4\pi}{15} - \frac{2\pi}{5}  \cdot 2   =\frac{-8\pi}{15}  > -\pi\\
\frac{5\pi}{15}    - \frac{2\pi}{5}  \cdot 2   = \frac{-7\pi}{15}> -\pi  \\   
\end{array}
$$


the there are also additional solution from  $0 <n<5\cap-1<n<-4$ 



### practice 2 

in the above solution we are trying to find the interval of the sin(5x) it self not only the x, so here we will be 

![[Pasted image 20250808085447.png]]
$$
\begin{array}{l} \\
\sin(2x)  = - \cos (2x )  on \left[ -\frac{3\pi}{2}, \frac{3\pi}{2}  \right]  \\ 
\frac{\sin(2x  )}{\cos(2x)}  = -1   \\
\tan(2x) =  -1   \\
\implies \frac{\pi}{4} \text{ reflection over the x axis and  y axis} \\
 \frac{7\pi}{4}  \text{ the reason why is } \frac{- \sin\left( \frac{\sqrt{ 2 }}{2} \right)}{   \left( \cos \left( \frac{\sqrt{ 2 }}{2}  \right) \right)}  =  -1 \\
 \frac{3\pi}{4}  \text{ the reason why is } \frac{\sin\left( \frac{\sqrt{ 2 }}{2} \right)}{   \left(- \cos \left( \frac{\sqrt{ 2 }}{2}  \right) \right)}  =  -1 \\
\end{array}
$$



There are many way to write different angle on a unit. Sometime it will be $\frac{3\pi}{4}\cap  \frac{7\pi}{4}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
2x =   \frac{7\pi}{4}  + \pi n  \implies  x = \frac{7\pi}{8}   +  \frac{\pi n}{2}   \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$

$$
2x =  \frac{3\pi}{4} + \pi n  \implies  x =  \frac{3\pi}{8} + \frac{\pi n}{2}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$


given  n  = 0   : 
$$\begin{array}{l}
 \frac{7\pi}{8}   +  \frac{\pi 0}{2}   = \frac{7\pi}{8}   < \frac{3\pi}{2}\\
 \\  
 \frac{3\pi}{8} + \frac{\pi 0}{2} =  \frac{3\pi}{8}  < \frac{3\pi}{2}\\
\end{array}
$$

given  n  = -1   : 
$$\begin{array}{l}
 \frac{7\pi}{8}   +  \frac{\pi \cdot -1}{2}   = \frac{3\pi}{8} >  -\frac{3\pi}{2}\\
 \\  
 \frac{3\pi}{8} + \frac{\pi \cdot  -1 }{2} = -\frac{\pi}{8}   > -\frac{3\pi}{2}\\
\end{array}
$$

given  n  = 1  : 
$$\begin{array}{l}
 \frac{7\pi}{8}   +  \frac{\pi \cdot 1}{2}   = \frac{11\pi}{8}  < \frac{3\pi}{2}\\
 \\  
 \frac{3\pi}{8} + \frac{\pi \cdot 1 }{2} = \frac{7\pi}{8}    < \frac{3\pi}{2}\\
\end{array}
$$

given  n  =    -2 : 
$$\begin{array}{l}
 \frac{7\pi}{8}   +  \frac{\pi \cdot -2}{2}   = -\frac{1}{8}\pi>  -\frac{3\pi}{2}\\
 \\  
 \frac{3\pi}{8} + \frac{\pi  \cdot -2}{2} = \frac{4\pi}{15}  > -\frac{5\pi}{8}\\
\end{array}
$$


### practice 3 


$$
\begin{array}{l} \\
\cos(3x)   = 2  \\ 



\end{array}
$$


there are no solution for this equation since the solution for sin and cos remain in the range of $\cos \in (-1,1) \cap  \sin \in(-1,1)$ therefore it can never be greater than 1 and it definitely can't be 2, there are not solution for this equation 

# #Practice_Exercise 

![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
4\sin(3t) = 2  \\
\sin 3t  = \frac{1}{2}  \\
 \implies \frac{\pi}{6} \text{ reflected  over y axis } \\
   \text{  over y axis }   \\
x  =   \frac{5\pi}{6}  \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{5\pi}{6} \cap \frac{\pi}{6}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
3t =   \frac{5\pi}{6}  + 2\pi n  \implies t =   \frac{5\pi}{18}  + \frac{2\pi n}{3}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
3t =   \frac{\pi}{6}  + 2\pi n  \implies t =   \frac{\pi}{18}  + \frac{2\pi n}{3}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
There are a infinite amount of possible solution since there is no  fixed range the value fall in 





![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
4\sin(3t) = 2  \left[ 0, \frac{4\pi}{3} \right] \\
\sin 3t  = \frac{1}{2}  \left[ 0, \frac{4\pi}{3} \right]  \\
 \implies \frac{\pi}{6} \text{ reflected  over y axis } \\
   \text{  over y axis }   \\
x  =   \frac{5\pi}{6}  \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{5\pi}{6} \cap \frac{\pi}{6}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
3t =   \frac{5\pi}{6}  + 2\pi n  \implies t =   \frac{5\pi}{18}  + \frac{2\pi n}{3}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
3t =   \frac{\pi}{6}  + 2\pi n  \implies t =   \frac{\pi}{18}  + \frac{2\pi n}{3}  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$

given  n  =    0 : 
$$\begin{array}{l}
 \frac{5\pi}{18}  + \frac{2\pi 0}{3}    =  \frac{5\pi}{18} < \frac{4\pi}{3} \\
 \\  
  \frac{\pi}{18}  + \frac{2\pi 0}{3} =   \frac{\pi}{18}  < \frac{4\pi}{3}\\
\end{array}
$$




given  n  =    1 : 
$$\begin{array}{l}
 \frac{5\pi}{18}  + \frac{2\pi 1}{3}    =  \frac{17\pi}{18} < \frac{4\pi}{3} \\ 
  \frac{\pi}{18}  + \frac{2\pi 1}{3} =   \frac{13\pi}{18}   < \frac{4\pi}{3}\\
\end{array}
$$


so it look like there are four solution to the interval 





![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
2\cos \left(  \frac{x}{3}  \right)  +  \sqrt{ 2  }  =  0   \\
 \cos \left(  \frac{x}{3}  \right)     = - \frac{\sqrt{ 2 }}{2} \\
\implies \frac{\pi}{4} \text{ reflected  over x axis and origin }  \\
\frac{3\pi}{4}  \text{ reflected over the x axis }  \\
\frac{5\pi}{4} \text{  reflected over the origin }   \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{9\pi}{4} \cap \frac{5\pi}{4}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
\frac{x}{3} =   \frac{3\pi}{4}  + 2\pi n  \implies  x  =   \frac{9\pi}{4}  + 6\pi n  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
\frac{x}{3} =   \frac{5\pi}{4}   + 2\pi n  \implies  x  =   \frac{15\pi}{4}   + 6\pi n  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
so there are  multiple number of solution bases on the above equation 










![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
2\cos \left(  \frac{x}{3}  \right)  +  \sqrt{ 2  }  =  0  [-7\pi,  7\pi ]  \\
 \cos \left(  \frac{x}{3}  \right)     = - \frac{\sqrt{ 2 }}{2} [-7\pi,  7\pi ] \\
\implies \frac{\pi}{4} \text{ reflected  over x axis and origin }  \\
\frac{3\pi}{4}  \text{ reflected over the x axis }  \\
\frac{5\pi}{4} \text{  reflected over the origin }   \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{9\pi}{4} \cap \frac{5\pi}{4}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
\frac{x}{3} =   \frac{3\pi}{4}  + 2\pi n  \implies  x  =   \frac{9\pi}{4}  + 6\pi n  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
\frac{x}{3} =   \frac{5\pi}{4}   + 2\pi n  \implies  x  =   \frac{15\pi}{4}   + 6\pi n  \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
so there are  multiple number of solution bases on the above equation 

given  n  =    0 : 
$$\begin{array}{l}
 \frac{9\pi}{4}  + 6\pi  \cdot 0    =   \frac{9\pi}{4}     < 7\pi \\ 
 \frac{15\pi}{4}   + 6\pi 0  =   \frac{15\pi}{4}     <  7\pi \\
\end{array}
$$
there are only 2 solution to this equation 



![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
4 \cos(6x ) =  \sqrt{  12  }  \in  \left[  0, \frac{\pi}{2} \right]   \\
\cos(6x) =  \frac{\sqrt{ 12 }}{4} = \frac{\sqrt{ 3 }}{2 }  \left[  0, \frac{\pi}{2} \right]  \\
\implies \frac{\pi}{6} \text{ reflected  over y axis }  \\
\frac{5\pi}{4}  \text{ reflected over the y axis }  \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{\pi}{6} \cap \frac{5\pi}{4}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
6x=  \frac{\pi}{6}  + 2\pi n  \implies  x  =    \frac{\pi}{36}  + \frac{\pi n}{3}    \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
6x =   \frac{5\pi}{4}   + 2\pi n  \implies  x  =      \frac{5\pi}{24}   + \frac{\pi n}{3}    \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
so there are  multiple number of solution bases on the above equation 

given  n  =    0 : 
$$\begin{array}{l}
 \frac{9\pi}{4}  + 6\pi  \cdot 0    =   \frac{9\pi}{4}     < 7\pi \\ 
 \frac{15\pi}{4}   + 6\pi 0  =   \frac{15\pi}{4}     <  7\pi \\
\end{array}
$$ 


$$\begin{array}{l}
 \frac{9\pi}{4}  + 6\pi  \cdot -1    =  -\frac{15}{4}\pi  > -7\pi \\ 
 \frac{15\pi}{4}   + 6\pi -1  =  -\frac{9}{4} \pi   >  -7\pi \\
\end{array}
$$

there are only 4 solution to this equation 



![[Pasted image 20250808085447.png]]

$$
\begin{array}{l} 
8\tan x - 5   = 3   \in  \left[ -\frac{\pi}{2} , \frac{3\pi}{2}  \right]  \\
\tan x = 1     \in  \left[ -\frac{\pi}{2} , \frac{3\pi}{2}  \right] \\
\implies \frac{\pi}{4} \text{ reflected  over the origin }  \\
\frac{5\pi}{4}  \text{  reflected  over the origin }  \\
  \end{array}
$$


There are many way to write different angle on a unit. Sometime it will be $\frac{\pi}{4}  \cap \frac{5\pi}{4}$ that we want for a solution, sometime many more so we need  a formula for every possible solution : 
$$
2x=  \frac{\pi}{4}  + 2\pi n  \implies  x  =   \frac{\pi}{8} + \pi n \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
$$
2x =   \frac{5\pi}{4}   + 2\pi n  \implies  x  =      \frac{5\pi}{8}   + \pi n     \left\{ \text{ n } \in Z |  (-\infty , \infty )\right\} 
$$
so there are  multiple number of solution bases on the above equation 

given  n  =    0 : 
$$\begin{array}{l}
\frac{\pi}{8} + \pi 0  =   \frac{\pi}{8}    < \frac{3\pi}{2}   \\ 
  \frac{5\pi}{8}   + \pi 0  =     \frac{5\pi}{8}      <  \frac{3\pi}{2}   \\
\end{array}
$$ 

given  n  =    1 : 

$$\begin{array}{l}
\frac{\pi}{8} + \pi   =  \frac{9}{8}\pi    < \frac{3\pi}{2}  \\ 
\end{array}
$$


given  n  =    -1 : 
$$\begin{array}{l}
\frac{\pi}{8} - \pi  =   \frac{9\pi}{4}     > -\frac{\pi}{2}\pi \\ 
  \frac{5\pi}{8}   - \pi  =   \frac{15\pi}{4}     >  -\frac{\pi}{2}\pi \\
\end{array}
$$

given  n  =     : 
$$\begin{array}{l}
\frac{\pi}{8} + \pi n  =   \frac{9\pi}{4}     > -\frac{\pi}{2}\pi \\ 
  \frac{5\pi}{8}   + \pi n  =   \frac{15\pi}{4}     >  -\frac{\pi}{2}\pi \\
\end{array}
$$

there are only 4 solution to this equation 



 



