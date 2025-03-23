
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

The important question is  how can  we sketch the graph  of a  equation  ?   
This question depend  on how much you know the equation in the first place  . For example  ,   if  we know that the  equation will draw  a line or circle  we can  used  method for determine   equation in these cases .  There  are  also  additional method that we will look at  

Let say that  we do not  know what the equation  is  or   method to  quickly  draft  a graph  . In this cases  , we just need to find  find  point to fill the graph then draw  line connecting them ,  we will  pick  values  x then compute the  y coordinate  in the  equation  then  plot the graph  by the two  value  

sketch the  graph  of $y= (x-1)^2  -4$  
$$
\begin{array}{l}
y= (x-1)^2  -4     \\
x = \pm 2  + 1  \\
\left\{ \begin{array}{l} 
x  =  3  \\
x =   -1  
\end{array} \\
\right.
\end{array}
$$
x   =0     y  =   -3  ,  x   =  -2  y   = 5  ,  x   =  4   y   = 5 

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
    \fill (0,-3) circle (2pt) node[above right] {$(0,-3)$};
    \fill (-2,5) circle (2pt) node[above left] {$(-2,5)$};
    \fill (4,5) circle (2pt) node[above right] {$(4,5)$};

    % Add additional points
 %%    \fill (-3,12) circle (2pt) node[above left] {$(-3,12)$}; %%
    \fill (-1,0) circle (2pt) node[above right] {$(-1,0)$};
    \fill (1,-4) circle (2pt) node[below right] {$(1,-4)$};
    \fill (2,-3) circle (2pt) node[below right] {$(2,-3)$};
    \fill (3,0) circle (2pt) node[above right] {$(3,0)$};

    % Draw the parabola
    \draw[thick, blue, domain=-2:4, smooth] plot (\x, {(\x  -1 )^2 -4});
\end{tikzpicture}
\end{document}


``` 


 in this  axis system  ,  we  only   need to  go as much  as needed   .  since  we  did  not  go  pass  2 with  the plug  in  computation  resulting in  us  not passing 2  for  the graph  we are drawing 

For a smoother graph we increment each  point by  1  on x and 2   on  y  axis  . 
Additionally  ,  you can  see in the  graph that the point is cross on 3  line   2 for the x   horizontal axis  and 1 on the y  vertical  axis , these cross are call  intercepts .  For  further  specification ,  when  the line cross the x axis we call  it  an  x-intercept   ,  and if it cross the  y axis we call  it the y-intercept  

Now  since the  x  intercept cross x-axis  then the y coordinate of the  x-intercept is   0   . Similarly , if the  y-intercept  cross the  x-axis then the x coordinate of the  y-intercepts  is  0  

##  Determine the x-intercepts and y-intercepts for each of the following equations.  
$$
 y  = x^2  + x  - 6
$$
finding the x  intercept  we will need the coordinate  y  to  be   0  

$$
\begin{array} {l}
 x^2  + x  - 6  =     0  \\
(x +  3)(x- 2 )  = 0  \\
\left\{ \begin{array}{l} 
x  =  -3  \\
x =    2  
\end{array} \\
\right.   \\

\end{array} 

$$
so the   x  intercept  of the equation  is  : 
$$
(-3, 0) \cap (2, 0)
$$
finding the y  intercept  we will need the coordinate  x  to  be   0  $$
\begin{array} {l}
  y  =      0^2  + 0  - 6 \\
  y  =      - 6   \\

\end{array} 

$$
so the  y intercept  of the equation is :  
$$
(0, -6) 
$$






$$
  y    = x^2   + 2 
$$
finding the x  intercept  we will need the coordinate  y  to  be   0     

$$
\begin{array} {l}
x^2   + 2  =     0  \\
x   = \pm  \sqrt{ 2 }i  \\
\left\{ \begin{array}{l} 
x  =  + \sqrt{ 2 }i   \\
x =  -  \sqrt{ 2 }i   
\end{array} \\
\right.   \\

\end{array} 

$$
Note that we have  a complex solution  resulting in  us  not having a  x  intercept  

finding the y  intercept  we will need the coordinate  x  to  be   0    

$$
\begin{array} {l}
  y  =    0^2   + 2   \\
  y  =      2     \\

\end{array} 
$$so the  y intercept  of the equation is :    
$$
(0 ,2 )
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
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }



    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, { (\x)^2   + 2 });
\end{tikzpicture}
\end{document}


``` 





$$
  y    = (x  + 1)^2  
$$
finding the x  intercept  we will need the coordinate  y  to  be   0     

$$
\begin{array} {l}
 (x  + 1)^2   =     0  \\
x  + 1   =   0  \\
x  =  -1\\  

\end{array} 

$$
so the   x  intercept  of the equation  is  :   
$$
(-1  , 0  ) 
$$
finding the y  intercept  we will need the coordinate  x  to  be   0    

$$
\begin{array} {l}
  y  =    (0  + 1)^2    \\
  y  =      1     \\

\end{array} 
$$so the  y intercept  of the equation is :    
$$
(0 ,1)
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
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-7,-6,-5,-4,-3,-2,-1,1,2,3,4,5,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    }



    % Draw the parabola
    \draw[thick, blue, domain=-3:1, smooth] plot (\x, {(\x  + 1)^2});
\end{tikzpicture}
\end{document}


``` 


# #Practice_Exercise   
##  construct a table of at least 4 ordered pairs of points on the graph of the equation and use the ordered pairs from the table to sketch the graph of the equation
$$

y  =  3x   +  4  
$$

| x              | y  =  3x   +  4 |
| -------------- | --------------- |
| $-\frac{4}{3}$ | $0$             |
| $2$            | 10              |
| -2             | 1               |
| 3              | 13              |


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



    % Draw the parabola
    \draw[thick, blue, domain=-3:1, smooth] plot (\x, {3*\x   +  4});
\end{tikzpicture}
\end{document}


``` 







$$

y  = 1  - x^2  
$$

| x    | $y  = 1  - x^2$ |
| ---- | --------------- |
| $-1$ | $0$             |
| $1$  | 0               |
| 0    | 1               |
| 3    | -8              |


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


	\fill (-1,0) circle (2pt) node[above right] {$(-1,0)$};  
	\fill (1,0) circle (2pt) node[above right] {$(1,0)$}; 
	\fill (0,1) circle (2pt) node[above right] {$(0,1)$}; 
	\fill (3,-8) circle (2pt) node[above right] {$(3,-8)$}; 
    % Draw the parabola
    \draw[thick, blue, domain=-3:3, smooth] plot (\x, {1  - (\x)^2});
\end{tikzpicture}
\end{document}


``` 









$$

y  = 1  - x^2  
$$

| x    | $y  = 1  - x^2$ |
| ---- | --------------- |
| $-1$ | $0$             |
| $1$  | 0               |
| 0    | 1               |
| 3    | -8              |


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


	\fill (-1,0) circle (2pt) node[above right] {$(-1,0)$};  
	\fill (1,0) circle (2pt) node[above right] {$(1,0)$}; 
	\fill (0,1) circle (2pt) node[above right] {$(0,1)$}; 
	\fill (3,-8) circle (2pt) node[above right] {$(3,-8)$}; 
    % Draw the parabola
    \draw[thick, blue, domain=-3:3, smooth] plot (\x, {1  - (\x)^2});
\end{tikzpicture}
\end{document}


``` 

