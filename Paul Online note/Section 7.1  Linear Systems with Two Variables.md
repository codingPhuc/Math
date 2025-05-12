---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/SystemsTwoVrble.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-05-12
amount of time: 
learning score:
---
A linear system with two variables is any system that can be written in the form of 
$$
\begin{array}{l}  
ax + by =  p    \\
cx  + dy  = q 
\end{array}
$$
where any constant can be zero with the exception that each equation must have at least one variable in it 
Also , the system is only linear  of the variables are only the first power ,are only numerator and there are no product of variable in any of the equation 
Here is an example of systems with numbers  

$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
3x - y  =  7  \\ 
 2x  + 3y  = 1  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y  =  3x   - 7 \\
 2x  + 3(3x   - 7)  = 1  
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y  =  3x   - 7 \\
11x  - 21  = 1  
\end{array} \right.  \\
\left\{ \begin{array}{l}
y  =  3\cdot  2   - 7    = -1 \\
x  =2  
\end{array} \right. \\
\end{array}
$$

$$
\begin{array}{l}  
3x - y =  7  \\
2x + 3 y = 1  
\end{array}
$$


before solving the equation we must ask what the solution to a system of equation is . A solution to a system of equation is a value of x and a value of y that , when substituted into the equation ,satisfies both equation at the same times 

from the example above  $x = 2$ and $y = -1$ is a solution to the system. This is easy to check 

$$
\begin{array}{l} \\
3\cdot 2 + 1   =  7  \\
2\cdot 2  + 3 \cdot -1 = 1  
\end{array}
$$
So , sure enough a pairs of number is a solution to the system . Do not worry about how we got these values . This will be the very first system that we solve when we get into the example 

For reference , it is very important for the pairs of number to satisfy the equation. For instance , $x=1$ and $y=-4$ will satisfy the first equation , but not the second so it is not a solution to the system. Likewise,  x =-1 and y = 1 will satisfy the second equation but not the first and so can't be a solution to the system



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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, { 3*\x - 7  }); 
     \draw[thick, red, domain=-2:4, smooth] plot (\x, { (-2*\x -1 )/3  }); 
\end{tikzpicture}
\end{document}


``` 

the solution to the two system is where the two line will intersect . So , when solving linear system with two variable we are asking where to two lines will intersect 

We will be looking at two method for solving this equation 

The first method is called **method of substitution** . In this method we will solve one equation for one variable and substitute this into the other equation . This will give us one equation with one variable that we can solve.


## solve each of the following system 



$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
5x +  4y  = 1       \\
3x  -  6y  = 2 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
y =  \frac{5x -1}{4}   \\
3x  - 3(\frac{5x -1}{2})  =2 
\end{array} \right. \\ 
\left\{ \begin{array}{l} 
y =  \frac{5x -1}{4}   \\
6x  - 3(5x -1) =4  
\end{array} \right.  \\
\left\{ \begin{array}{l}
y =  -4   \\
x  = 3 
\end{array} \right. \\
\end{array}
$$





$$ 
\begin{array}{l} \\  
\left\{ \begin{array}{l}
2x + 4 y =  -10     \\
6x +  3 y =  6 
\end{array} \right. \\ 
\left\{ \begin{array}{l}
2x + 4 (2 -2x) =  -10\\  
2 -2x    = y 
\end{array} \right. \\ 
\left\{ \begin{array}{l} 
-6x  =  -18\\  
2 -2x    = y 
\end{array} \right.  \\
\left\{ \begin{array}{l}
y =  -4   \\
x  = 3 
\end{array} \right. \\
\end{array}
$$


