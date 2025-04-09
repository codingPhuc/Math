---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/MiscFunctions.aspx
Current date: 2025-04-09
---
# #definition  
##  Constant Function
this is the easiest  problem we'll  graph though will cause a lot of problem 

$$
f(x)  = c 
$$
where c is some number 
let take a look at  $f(x) =  4$ the biggest problem that student have for these function is that there is no x on the right side to plug into the function . However , this mean that there is no substitution to do . In other word , no matter the value of x we will always get a value of 4 (c in the general cases ) out of the function 

So , every  point has a y coordinate of 4 . This is exactly what is define as the horizontal line . In fact , we can recall that $f(x)$ is nothing more than a fancy way of writing y 

$$
y = 4
$$

this is the equation of the horizontal line 


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
    % Draw the parabola
    \draw[thick, blue, domain=-6:6, smooth] plot (\x, 4);
 
\end{tikzpicture}
\end{document}


``` 


##  Square Root 
Next , we need to take a look at $f(x)  = \sqrt{ x }$ 