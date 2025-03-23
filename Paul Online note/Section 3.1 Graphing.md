
We will start off with a    Rectangular or Cartesian coordinate system  .   This is the standard system  we used to sketch our graph  

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
	\node at ( -5,5) {$\text{Quadrant II}$};
    \node at ( -3,2) {$( -3,2)$}; 
    \node at ( 5,5)  {$\text{Quadrant I}$};
    \node at ( 1,2) {$( 1,2)$};
    
    \node at ( 2,1) {$( 2,1)$};
    \node at ( 1,2) {$( 1,2)  $};

	\node at ( -5,-5)  {$\text{Quadrant III}$};
    \node at ( -1,-3) {$( -1,-3)$}; 
    \node at ( 5,-5)  {$\text{Quadrant IV}$};
    \node at (3,-3) {$(3,-3)$};
    
\end{tikzpicture}
\end{document}


```
the horizontal  and vertical   horizontal and vertical  axes ,  typically called   x-axis and  y axis  ,  divide the  coordinate system  up into  quadrant   as shown  above  . 

-  Quadrant I   x >  0    ,  or  x  positive  y   >  0  or  y positive  
- Quadrant II    x <  0    ,  or  x  negative    y   >  0  or  y positive   
- Quadrant III  x <   0    ,  or  x  negative  y   <  0  or  y  negative  
- Quadrant III  x >   0    ,  or  x  positive   y   <  0  or  y  negative 

each  point in the coordinate system  is define by the order  pair  of the point ( x  ,   y  )   .  The first number listed x  coordinate  of the point and the second  is the y   coordinate of the  point  .  
The point where two axes  cross is called the  origin  and  has the coordinate  ( 0  , 0  ) 

now we  need to discuss graphing an equation  . The first question  is  how can  we graph  a equation ?   a  graph is  set of order  pairs  who equation satisfy    the equation  

for example , the  point ( 2 ,   -3)  is the point on the graph  of   $y=(x−1)^2−4y$ while  (1, 5)   is not on the graph  .  

in this case  we have x    = 2  and  y  =  -3   so  plugging   in gives  
$$
\begin{aligned}&-3\overset{?}{\operatorname*{\operatorname*{=}}}\left(2-1\right)^2-4\\&-3\overset{?}{\operatorname*{\operatorname*{=}}}\left(1\right)^2-4\\&-3=-3\quad\mathrm{OK}\end{aligned}
$$
so the coordinate  does not satisfy the equation   
let  look  at another equation   ( 1  ,  5 ) for example   plugging in these coordinate give  
$$
\begin{aligned}&5\overset{?}{\operatorname*{\operatorname*{=}}}\left(1-1\right)^2-4\\&5\overset{?}{\operatorname*{\operatorname*{=}}}\left(0\right)^2-4\\&5\neq-4\quad\mathrm{NOT~OK}\end{aligned}
$$

