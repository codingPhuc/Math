---
title: Adjunction
references_1: https://www.youtube.com/watch?v=Kq-nj_UoAqg&t=34s&ab_channel=Mathispower4u
tags:
  - In_Progress
reference_2: https://tutorial.math.lamar.edu/Classes/Alg/CombineFunctions.aspx
Current date: 2025-04-14
---
W are going to be looking at the same thing as parabolas . However,  we will drive into the general view of this application . Many  graph have a **symmetry** to them 

Symmetry can be used full in graphing equation since if we know one portion of the graph then we should know the other as well . 
In this section we want to look at three types of symmetry 
1. A graph is said to be symmetric on the x-axis if $(a,b)$ is on the graph then $(a,-b)$ is also on the graph 

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
    \draw[thick, blue, domain=-2:2, smooth] plot ( { (\x)^2  + 3  } ,\x );

 
\end{tikzpicture}
\end{document}


``` 


2. A graph is said to be **symmetric** about the y-axis if whenever $(a, b)$ is on the graph so then $(-a , b)$ .Here is the sketch of the graph that is symmetric 

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
    \draw[thick, blue, domain=-2:2, smooth] plot (\x  , { (\x)^2  + 3  });

 
\end{tikzpicture}
\end{document}


``` 


3. A graph is said to be **about the origin** if whenever $(a, b)$ is on the graph so is $(-a  , - b)$ . Here is the sketch of the graph that is symmetric on the origin  

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


Note that most graph does not have this kind of symmetry . Also , it is possible for a graph to have one kind of symmetry . For example , the graph of the circle center at the origin exhibit all three symmetries 

##  Tests for Symmetry  
we've some fairly simply test for each different type of symmetry 
1. A graph will have symmetry about the x-axis if we get the equivalent equation when  y are replace with  -y 
2. A graph will get  symmetry about the y-axis if we get an equivalent equation when all the x are replace with -x  
3. A graph will have symmetry  about the origin if we get an equivalent equation  when all the y are replace with  $-y$ and all the $x$ are replace with $-x$ 

## Determine the symmetry of each of the following equations.


$$
\begin{array}{l}  \\
y = x^2 -  6x^4  + 2  \\
f(-x )   = (-x)^2 -  6(-x)^4  + 2  =   x^2    - 6x^4  + 2   \\
\end{array}
$$
so we concluded that the equation is equivalent when  -x  
$$
\begin{array}{l}  \\
y = x^2 -  6x^4  + 2  \\
- f(x )   = - x^2 +   6x^4  -  2   \\
\end{array}
$$

so we concluded that the equation is not equivalent when -y . Additionally , since the  equation is not equivalent when -y  it is not symmetric on the x axis  and origin but is symmetric on the y axis 


$$
y =  2x^3    - x^5 
$$

| equation                       | -y                                                                                             | -x                                                                                                            | origin                                                                                                         | is equivalent                                                                                             |
| ------------------------------ | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| $y =  2x^3    - x^5$           | $-y = 2x^3    - x^5$                                                                           | $y =  -2x^3    + x^5$                                                                                         | $- y =  -2x^3    + x^5$                                                                                        | we concluded that the equation is equivalent to the origin since we just need to multiply both side by -1 |
| $y^4 +x^3 -5x  =  0$           | $$\begin{array}{l }<br>(-y)^4 +x^3 -5x  =  0 \\<br>y^4 +x^3  - 5x = 0  <br><br>\end{array}$$   | $$\begin{array}{l }<br>(y)^4 + (-x)^3 +5x  =  0  \\<br>(y)^4 - (x)^3 +5x  =  0<br>\end{array}$$               | $$\begin{array}{l }<br>(-y)^4 + (-x)^3 +5x  =  0  \\<br>(y)^4 - (x)^3 +5x  =  0<br>\end{array}$$               | we concluded that the equation is only symmetric on the x-axis                                            |
| $y = x^3   + x^2+x+1$          | $-y = x^3   + x^2+x+1$                                                                         | $$ \begin{array}{l} \\<br>y = (-x)^3   + (-x)^2-x+1  \\<br> y =  - x^3 +  x^2   - x  + 1<br>\end{array}<br>$$ | $$ \begin{array}{l} \\<br>y = (-x)^3   + (-x)^2-x+1  \\<br> -y =  - x^3 +  x^2   - x  + 1<br>\end{array}<br>$$ | we concluded that the equation is not symmetric on any axis or origin                                     |
| $$<br>x^2 + y^2 =  1<br>$$<br> | $$<br>\begin{array}{l}<br>x^2  + (-y)^2  =  1   \\<br> x^2  + y^2  =  1  <br>\end{array}<br>$$ | $$<br>\begin{array}{l}<br>(-x)^2  + (y)^2  =  1   \\<br>x^2  + y^2  =  1  <br>\end{array}<br>$$               | we concluded that the equation is symmetric on all axis and orgin                                              |                                                                                                           |
|                                |                                                                                                |                                                                                                               |                                                                                                                |                                                                                                           |



# #Practice_Exercise  


Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
x =  4y^6  -  y^2  
$$
x-axis 

$$
\begin{array}{l} \\
x =  4(-y )^6  -  (-y)^2     \\
x  =   4(y)^6  -   y^2
\end{array}

$$
since the sign  on negative  $y_{1}$ does   match the sign in  $y$ . We concluded that  the equation is  equivalent on the x axis 

y-axis 

$$
\begin{array}{l} \\

- x  =   4(y)^6  -   y^2
\end{array}

$$
since the sign  on negative  $y_{1}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the y axis 

origin 

$$
\begin{array}{l} \\
-x =  4(-y )^6  -  (-y)^2     \\
-x  =   4(y)^6  -   y^2
\end{array}
$$
since the sign on the $-y_{2}$ does not match   y   . We concluded that the equation is not symmetric on the origin 









Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
\frac{y^2}{ 4}  = 1 + \frac{x^2}{9}
$$
x-axis 

$$
\begin{array}{l} \\
\frac{(-y)^2}{ 4}  = 1 + \frac{x^2}{9}  \\
\frac{y^2}{ 4}  = 1 + \frac{x^2}{9}
\end{array}

$$
since the sign  on negative  $y_{1}$ does   match the sign in  $y$ . We concluded that  the equation is  equivalent on the x axis 

y-axis 

$$
\begin{array}{l} \\
\frac{y^2}{ 4}  = 1 + \frac{(-x)^2}{9}  \\
\frac{y^2}{ 4}  = 1 + \frac{(x)^2}{9}
\end{array}

$$
since the sign  on negative  $y_{1}$ does   match the sign in  $y$ . We concluded that  the equation is  equivalent on the y axis 

origin 

$$
\begin{array}{l} \\
\frac{(-y)^2}{ 4}  = 1 + \frac{(-x)^2}{9}  \\
\frac{y^2}{ 4}  = 1 + \frac{(x)^2}{9}
\end{array}
$$
since the sign on both part of the equation in $y_{2}$  match the sign in the equation y . We concluded that the equation in symmetric on the origin 







Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
x^2  =  7 y -  x^3  + 2 
$$
x-axis 

$$
\begin{array}{l} \\
(-x)^2  =  7 y -  (-x)^3  + 2  \\
(x)^2  =  7 y +  (x)^3  + 2 \end{array}

$$
since the sign  on negative  $y_{2}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the x axis 

y-axis 

$$
\begin{array}{l} \\
x^2  =  7\cdot -y -  x^3  + 2   \\
x^2  =  -7 y -  x^3  + 2  
\end{array}

$$
since the sign  on negative  $y_{2}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the y axis 

origin 

$$
\begin{array}{l} \\
(-x)^2  =  7 -y -  (-x)^3  + 2  \\
(x)^2  =  -7 y +  (x)^3  + 2 
\end{array}
$$
since the sign on the $-y_{2}$ does not match   y   . We concluded that the equation is not symmetric on the origin 







Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
y =  4x^2   +  x^6  - x^8 
$$
x-axis 

$$
\begin{array}{l} \\
y =  4(-x)^2   +  (-x)^6  - (-x)^8  \\
y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign  on negative  $y_{1}$    match the sign in  $y$ . We concluded that  the equation is  symmetric  on the y axis 

y-axis 
$$
\begin{array}{l} \\
- y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign  on negative  $y_{2}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the x axis 

origin 

$$
\begin{array}{l} \\
-y =  4(-x)^2   +  (-x)^6  - (-x)^8  \\
-y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign on the $-y_{2}$ does not match   y   . We concluded that the equation is not symmetric on the origin 






Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
y =  4x^2   +  x^6  - x^8 
$$
x-axis 

$$
\begin{array}{l} \\
y =  4(-x)^2   +  (-x)^6  - (-x)^8  \\
y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign  on negative  $y_{1}$    match the sign in  $y$ . We concluded that  the equation is  symmetric  on the y axis 

y-axis 
$$
\begin{array}{l} \\
- y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign  on negative  $y_{2}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the x axis 

origin 

$$
\begin{array}{l} \\
-y =  4(-x)^2   +  (-x)^6  - (-x)^8  \\
-y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign on the $-y_{2}$ does not match   y   . We concluded that the equation is not symmetric on the origin 






Determine if the graphs of the equation would be symmetrical about the x-axis , y-axis , or the origin 


$$
y =  7x + 4x^5 
$$
x-axis 

$$
\begin{array}{l} \\
y =  - 7x + 4(-x)^5  \\
y =  7x -4(x)^5  \end{array}
$$
since the sign  on negative  $y_{1}$    match the sign in  $y$ . We concluded that  the equation is  symmetric  on the y axis 

y-axis 
$$
\begin{array}{l} \\
y =  7x + 4(x)^5 \end{array}

$$
since the sign  on negative  $y_{2}$ does not  match the sign in  $y$ . We concluded that  the equation is not equivalent on the x axis 

origin 

$$
\begin{array}{l} \\
-y =  4(-x)^2   +  (-x)^6  - (-x)^8  \\
-y   =   4x^2   +  x^6  - x^8 \end{array}

$$
since the sign on the $-y_{2}$ does not match   y   . We concluded that the equation is not symmetric on the origin 
