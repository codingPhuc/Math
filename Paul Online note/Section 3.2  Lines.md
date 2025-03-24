---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
reference: 
Current date: 2025-03-24
---
let start the section  off with  a  quick  mathematical definition of  a line  .  Any equation that can be written  in the form  ,  
$$Ax +  By   =  C $$ 
is  a  line    ,  as long as   A  and  B  are  not  simultaneously   0 .  It is  okay if one of them  is  0  , we  just can't have  both as  0   . Note that this is sometime call the **standard form** of the line 

a  line  is define  by  two  point that are on the line .  Given  two  points that are on the line  we can graph the line   and write down the equation of the line . This fact will be used in serval  point  in the equation 

a **slope** in the line is the level of  steepness of  lines  and can be used too  measure  whether  a line is increasing  or decreasing as we move from  left to right  . Here are the definition of    a slop of a  line 

given  2  points  $(x_{1}  ,  y_{1}) \cap  (x_{2} ,  y_{2})$ the slope of the  given line is 
$$
 m = \frac{y_{2} - y_{1}}{x_{2} -y_{1}}
$$
In other words  the slope is the different in the y  values  divided by the different  in the x  value .  do  not worry about the   subscripts(define the different version of the variable ) on the  variable   

do  not worry  about which  point should  be first and which  point should be second  .  Because regardless of the order we can still  determine the different  of the slope

there is also  a  geometric  equation for the slope  and line  as well  . You will hear the slope and line define as follow 
$$
 m  = \frac{rise}{run}
$$

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    \draw[->] (0,-7) -- (0,7) node[right] {}; 
    \draw[->] (-1,-1) -- (6,6) node[right] {}; 
    \draw[-,dotted ] (6,6) -- (6,-1) node[right] {}; 
    \draw[-,dotted ] (6,-1) -- (-1,-1) node[right] {}; 
    \draw[<->] (-1,-2) -- (6,-2) node[midway ,  below] {$\text{rise}  =  x_{2} -  x_{1}$};   
    \draw[<->] (7,6) -- (7,-1) node[midway ,  right] {$\text{rise}  =  y_{2} -  y_{1}$};
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }

    % Text annotations  
    \fill (6,6)  circle (2pt) node[above right] {$(6,6)$};
    \fill (6,-1) circle (2pt) node[above left] {$(6,-1)$};
    \fill (-1,-1)  circle (2pt) node[above right] {$(-1,-1) $};

    % Add additional points
 %%    \fill (-3,12) circle (2pt) node[above left] {$(-3,12)$}; %%

    % Draw the parabola

\end{tikzpicture}
\end{document}


``` 
if   we have the equation of the slope  which is  a fraction  of    $m  = \frac{rise}{run}$  ,  and a point on the  line as   $(x_{1}, y_{1})$ , then we can  easily find the second  point on that line .  Note  however  ,  if the slop  is negative  then the  minus sign  should be  place on the numerator not  the denominator , because it indicate a clear downward trend instead  of  a left or right direction  which will be confusing 


so  bases  on the  $m  = \frac{rise}{run}$  and  $m = \frac{y_{2} - y_{1}}{x_{2} -y_{1}}$ we can  get the  second point $(x_{2},  y_{2} )$ by   using the rise( downward or upward trend)   and  run  ( right direction)   to move to  move the point  up or down  and  too  the right  to  get $(x_{2},  y_{2} )$
$$
\begin{array}{l}
x_{2}  =    x_{1}  +  run  \\ 
y_{2}  =  y_{1}  +  rise  
\end{array}
$$

## Determine the slope of each of the following lines. Sketch the graph of each line. 
The line  that contains the two points (-2 ,  -3)  and   (3,1 )  
$$ 
\begin{array}{l}
m  = \frac{rise}{run}   \\
m  =   \frac{  1  +  3 }{3    +   2 }   \\
m  =  \frac{5}{4}
\end{array}
$$



The line  that contains the two points  
(−1,5) and (0,−2)  
$$ 
\begin{array}{l}
m  = \frac{rise}{run}   \\
m  =   \frac{    -2  -  5 }{  0   + 1   }   \\
m  =  -7
\end{array}
$$




The line  that contains the two points  (−3,2) and (5,2) 
$$ 
\begin{array}{l}
m  = \frac{rise}{run}   \\
m  =   \frac{  2   -2 }{ 5 + 3  }   \\
m  =  0
\end{array}
$$



The line  that contains the two points (4,3) and (4,−2)
$$ 
\begin{array}{l}
m  = \frac{rise}{run}   \\
m  =   \frac{    - 2    -3  }{ 4-4 }   \\
m  =  -\frac{5}{0}  \\
m  =  undefine  
\end{array}
$$ 

we can use   this set of examples  to see the general  fact about the line . First we  can see that the larger the number ( ignoring  any minus sign )  the steeper the line .  So ,  the slope help  us know  how step the  line is  

if the slope is  a negative number than the line will increase  from  left  to right . If the slope is a  positive number then the line will decrease  from  left to right 
we now  look  at special  form of the equation   .  A  horizontal line with a yy-intercept of bb will have the equation,   $$
   y  =  b 
$$Likewise, a vertical line with an xx-intercept of aa will have the equation,  

$$
  x  =  a 
$$
The next special line we need to look at is the **point-slope  form**  of  the line . This form  is very useful for writing the equation of the line  . If we know the line passes  though  the point $(x_{1} , y_{1})$ and has a slope of m then the point-slope form of the equation of the line is 
$$
   y -y_{1}  =  m(x  - x_{1})$$ 
   Write down the equation of the line that passes through the two points (−2,4)and (3,−5)
$$
   4  +  5  =  m(-2  - 3)$$
   