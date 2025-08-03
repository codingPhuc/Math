---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-03
amount of time: 
learning score: 
reference: https://www.youtube.com/watch?app=desktop&v=L_GApcZZgsE&t=4s&ab_channel=Mario%27sMathTutoring
---



finding the different quotient of a function, the different quotation just another way of finding the slope of a formula without knowing the
# Different Quotient 

for function $y= f(x)$ 

## secant line is 
a line between two points on the slope of a function 

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};
   \draw[->]  (1, 2) -- (2, 4) node[right] {$x$}
	   node[midway, above] {Secant Line};
    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Right branch
       \draw[dashed, red, domain=-3:3] plot (\x, {2^(\x) });

    \filldraw[black] (1, 2) circle (2pt) node[below left] {$(0, 1)$}; 
      \filldraw[black] (2, 4) circle (2pt) node[below left] {$(2, 4)$}; 

\end{tikzpicture}
\end{document}

```

## definition the average rate of change for f(x) on the interval [a, b] is 
The secant line between the two point $(a, f(a))  ) (b , f(b))$  
$$
 m=  \frac{rise}{run}  = \frac{\triangle y}{\triangle x }  = \frac{f(b) -f(a)}{b - a }
$$
Example the average rate of change for $f(x)  =\sqrt{ x }$ on the interval [1,4] is 
$$  
m = \frac{f(4)-f(1)}{4 -1 }   = \frac{\sqrt{ 4 } -\sqrt{ 1 }}{3} =
\frac{2-1}{3} = \frac{1}{3}
$$

A different quotation representation  
the average of change of a the function f(x ) on the intenal is [x, x + h] 
so another way to represent the secant line between the two point is : 
$$
m  =  \frac{f(b) -  f( c)}{ b -a }   = \frac{f(x+h) - f(x )}{h}
$$

example find the and simplify the different quotation for $f(x)= 2x^2  - x  + 3$
different   quotation    $\frac{f(x+h) - f(x)}{h}$ 

first compute the value f(x  +h) : 
$$
\begin{array}
f(x+h) = 2(x+ h)^2  - (x + h) + 3   \\
2 (x+ h ) (x + h  )  - x  -h  + 3   \\
= 2(x^2 + x + h x + h^2 )  - x  - h  + 3  \\
= 2x^2 + 2xh + 2hx  + 2h^2 - x - h  + 3  \\
 =   2x^2 + 4xh + 2h^2 - x -h + 3 
\end{array}
$$


second subtract the equation down   
$$
\begin{array}
f(x+h) - f(x )   =    2x^2  = 4xh  + 2h^2  -x - h + 3 - (2x^2 -x + 3)  \\
= 2x^2 + 4xh  + 2h^2  -x -h + 3  - 2x^2  + x  - 3  \\
= 4xh  + 2h^2 -h  \\
\end{array}

$$

finally find  the most simply form of the equation in this cases is : 
$$
\frac{f(x   +h )- f(x)} { h }  = \frac{4xh + 2h^2  -h}{ h }  =  \frac{h(4x + 2x -1)}{h}  = (4x + 2x -1)
$$

