---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-08-14"
amount of time: 
learning score:
---
there are many way of solving equation either by : 
1. factoring the equation 
2. by quadratic formula 
3. Square root method 


$$
\begin{array}{l}  \\
(3x -1)^2 = 12  \\
\left\{ \begin{array}{l}  \\
3x  - 1  = 2\sqrt{ 3 }   \\
3x   - 1  =  -2 \sqrt{ 3 }
\end{array}  \right.  \\
\left\{ \begin{array}{l}  
x   = \frac{2\sqrt{ 3 }  + 1}{3}  \\
x   = \frac{ -2 \sqrt{ 3 } +1}{3}
\end{array}  \right. 
\end{array}
$$


$$
\begin{array}{l} \\
2\sqrt{  x + 4 }  =  x - 3   \\
4x + 16  = x^2  -6x +   9   \\
x^2  -10x - 7  = 0   \\
\text{ used the quadratic equation}  \\
x =  5 + 4\sqrt{ 2 }   \\
x  = 5  - 4\sqrt{ 2 }  \\
\text{ however  plug in } 5-4\sqrt{ 2 }  \\
2\sqrt{ 5 -  4\sqrt{ 2 }  + 4 } \neq 5 - 4\sqrt{ 2 } -3   \\
\implies \text{ only got 1 answer } 5 + 4\sqrt{ 2 }
\end{array}
$$

if you have square of square root double check your answer

given $y= x^2 - x - 6$ 
1. find the x intercept  by plugging in 0 for y 
2. find the y intercept by plugging in 0 for x 
3. draw the chart by plugging in a range of x numbers resulting in y value then connect the point to draw the parabola 


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    \draw[->] (0,-7) -- (0,7) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }

    % Text annotations  
\fill (-2,0) circle (2pt) node[above right] {$ (-2,0) $}; 
\fill (3,0) circle (2pt) node[above right] {$(3,0) $};
    % Draw the parabola
    \draw[thick, blue, domain=-2:3, smooth] plot (\x, {
    (\x)^2 -\x -  6 });
 
 
\end{tikzpicture}
\end{document}


``` 

there are different type of notation when showing the result set notation and interval notation, Gita said that she like to used set notation example (-2,0) etc

![[Pasted image 20250826213704.png]]