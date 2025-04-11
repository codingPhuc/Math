---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/Transformations.aspx
Current date: 2025-04-09
---
In this section we are going to go though simple graph that are going to help us solve simple problem . This section is called **transformations** 

## vertical Shifts 
The first transformation that we will be looking at is a vertical shift 
Given the graphs of $f(x)$ the graph of $g(x)=f(x) + c$ will be the graph of $f(x)$ shifted up by $c$ units if c is positive and or down by c units if c is negative 


$$
g(x)  =  x^2 + 3  
$$


### Using transformations sketch the graph of the following functions. 

1. Find the vertex .There are simple method to finding this which we will discuss latter   
the vertex of the equation above is $(0,3)$ since this indicate that the vertex is above the x intersect . We concluded that there will not be a x intercepts 
2. Finding the y intercept $(0,f(0))$   
$$
\begin{array}{l} \\
g(x)  =  x^2  + 3   \\
g(0 )   =  3   
\end{array}
$$

3. solve the $f(x)= 0$ intercept if they exits , there are multiple number of solution ranging from 0 to 2 x-intercept  
since the vertex , y intercept are the same and both are positive number . We concluded that y does not a x-intercept since 

$$
x^2  + 3    = 0 
x = \pm  \sqrt{ 3 }i
$$

here we will draw the graph of $x^2$ first , then draw the graph when it  shift up by 3 unit which is $x^2 + 3$  
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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^2  + 3  });
    \draw[dotted, red, domain=-2:2, smooth] plot (\x, { (\x)^2   });
 
\end{tikzpicture}
\end{document}


``` 




$$
\begin{array}{l}  \\
\sqrt{  x } - 5   = f(x )   \\
\sqrt{  x }  - 5  =  y   \\ 
\end{array}
$$
this is not  a line function like [[Section 3.2  Lines]] so we will not perform anything to get the equation of the lines 




first  we draw the graph of $\sqrt{ x }$ (the dotted line graph bellow) down by 5 . Again from a coordinate stand point , we subtract 5 from the y coordinate on points on $\sqrt{ x }$
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
    \draw[thick, blue, domain=0:6, smooth] plot (\x, {sqrt(\x)});
        \draw[dotted, red, domain=0:6, smooth] plot (\x, {sqrt(\x) -5});
 
 
\end{tikzpicture}
\end{document}


```




## Horizontal shift 
These are simple  as well but there is one bit we need to be careful with 
given a graph of $f(x)$ the graph of $g(x) =g(x+ c)$ will be the graph of $f(x)$ shift left by c unit of c is positive and right by c unit if c is negative 

Now we need to be careful here . A positive value of c will negatively shift the graph while a negative value of c will positively shift the graph . This is the opposite of the vertical shift that we cover above 

### Using transformations sketch the graph of the following functions 

$$
\begin{array}{l}  \\
h(x  ) =  (x + 2 )^3  \\
\end{array}
$$

since $h(x  ) =  (x + 2 )^3$ then we concluded that  $f(x) = x^3$ since $h(x) =  (x + 2 )^3\implies f(x+2) = (x+ 2)^2$ so there is a 2  unit shift so we need to subtract 2  from  

| x   | h(x) |
| --- | ---- |
| 0   |      |
| 1   | 1    |
| -1  | 1    |
| 2   | 2    |
| -2  | 2    |
