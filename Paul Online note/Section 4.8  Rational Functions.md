---
title: Adjunction
references: 
tags:
  - In_Progress
reference: 
Current date: 2025-04-16
---
In this final section we will discuss  graphing  rational function .  It's best to start of with a simple one that we can do without all the knowledge in this work 
Let's sketch the graph of $f(x) =\frac{1}{x}$ . First , since this is a rational function we have too be careful with a division by  0 problem . In this equation we need to avoid $x=0$ since that will give division by zero

Now , let plug in some value of x to see what we see 

| x       | f(x)   |
|---------|--------|
| -4      | -0.25  |
| -2      | -0.5   |
| -1      | -1     |
| -0.1    | -10    |
| -0.01   | -100   |
| 0.01    | 100    |
| 0.1     | 10     |
| 1       | 1      |
| 2       | 0.5    |
| 4       | 0.25   |

So , as x get large (both positive and negative) the function keep the sign of x and gets smaller and smaller . Likewise , as we approach $x=0$ the function again keep the same sign of x but start getting quick large 

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
   \draw[red, thick, domain=0.3:3, samples=100] plot (\x, {1/\x});
  \draw[red, thick, domain=-3:-0.3, samples=100] plot (\x, {1/\x});

 
\end{tikzpicture}
\end{document}

```

1. the graph illustrated above is divided into 2 pieces 
2. the graph does not have any interception of any kind 
	recall that a graph will have y-interception at point $(0,f(0))$ . However ,  in this cases we need to avoid $x=0$ and so this  graph will never cross the y axis. It will lean toward it but never touch it 
3. next recall that we can get the x intercept by solving $f(x)=0$ . In rational function , this seem like a hard thing to deal with , but remember that we only need the numerator to be 0 not  the denominator . So try to avoid solution where the solution for $f(x)=0$ will cause the denominator to be 0
4. Finally we get to address that the graph gets very close to the x  and y-axis but never crosses . Since there isn't anything special about axis  it self we'll   use the fact that the x-axis is really the line given by $y=0$ and the y-axis is really the line given by $x=0$ 
5. In our graph as the value of x approaches 
