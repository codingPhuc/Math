

# #definition 
we will take a quick  look at circles .  Before that however  , we are going to  take a quick a look at formula   
Given  two  points   $(x_{1} ,  y_{1})$ and  $(x_{2} , y_{2})$ the distance between  them is given  
$$
dm  = \sqrt{(x_{2}   -  x_{1})^2   + (y_{2}  - y_{1})^2  }
$$
So why  is this  formula need  ,  recall that  a circle  is  just  all point of that have the same distance  ,  r is called the  radius of a point , (h,k) called the center . In other word ,if (x , y )  is any point  in the circle, then it will have a distance of r from the center of the center (h,k)  
$$
r  =   \sqrt{  (x - h)^2  + (y  - k)^2  }
$$
or  if we square both the side we will get  : 
$$
r^2 =  (x  -  h)^2    +  (y -  k)^2 
$$
## Write down the equation of a circle 
with radius 8 and center (−4,7)
$$
8^2  =  (x+  4)^2 + (  y  - 7)^2  
$$
do not square out the two term  on the left leaving these terms here will help us quickly identify   the radius  and center of the circle  
Graphing is  circle is easy when we know the  radius  and  center  point . Then  we just need the bottom point , left point , right point  and  top  point . 
These point are simple to find  since we know that the point have a distance of r from the center 
$$
\begin{array}{l} 
\text{right most  point : } (h + r , k ) \\
\text{left most  point : } (h - r , k )  \\
\text{top most  point : } (h , k + r  ) \\
\text{bottom most  point : } (h  , k - r  )
\end{array}
$$
in other words all we need to do  is add r to the  x  or  y coordinates of the  center points to get the  right most point or top most point . Similarly  ,  we can  subtract  x  or  y coordinates of the  center points  to  get the bottom point or left point  
## Determine the center and radius of each of the following circles and sketch the graph of the circle. 
$$
\begin{array}{l }
x^2  + y^2  =1   \\

\end{array}

  
$$
-  the center point of the equation is  (0, 0) 
- the  radius  of the equation is  (1) 

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
    \draw (0,0) circle [radius  = 1cm ]  ;  
    \fill (0,0) circle (2pt) node[above left] {$(0,0)$};
	


    % Draw the parabola
   
\end{tikzpicture}
\end{document}
```





$$
x^2  + (y -3)^2  =  4   
$$
- the center point of the equation is ( 0  , 3 ) 
- the radius  of the equation is  2 


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
    \draw (0,3)  circle [radius  = 2cm ]  ; 
    % Draw the parabola
    \draw[-,dotted ] (-2,3)  -- (2,3)  node[right] {};   
    \draw[-,dotted ] (0,1)  -- (0,5)  node[right] {};  
    \fill (0,3) circle (2pt) node[above left] {$(0,3)$}; 
        \fill  (0,1)  circle (2pt) node[above left] {$ (0,1) $};
            \fill (0,5) circle (2pt) node[above left] {$(0,5)$};
                \fill (-2,3) circle (2pt) node[above left] {$(-2,3)$}; 
                \fill (2,3) circle (2pt) node[above left] {$(2,3)$};
    
                    
\end{tikzpicture}
\end{document}
```



$$
(x  - 1)^2  +  (y  +  4)^2   =  16    
$$
- the center point of the equation is ( 1 ,  -4)
- the radius  of the equation is 4  


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
    \draw (1,-4) circle [radius  = 4cm ]  ;   
    \draw[-,dotted ] (-3,-4)  -- (5,-4)  node[right] {};  
    \draw[-,dotted ] (1,-8)  -- (1,0)  node[right] {}; 
    \fill (5,-4)  circle (2pt) node[above left] {$(5,-4)$};
	\fill (-3,-4)  circle (2pt) node[above left] {$(-3,-4)$};  
	\fill (1,-8)   circle (2pt) node[above left] {$(1,-8) $}; 
	\fill (1,0)  circle (2pt) node[above left] {$(1,0)$}; 
	\fill (1,-4) circle (2pt) node[above left] {$(1,-4)$};

	

    % Draw the parabola
   
\end{tikzpicture}
\end{document}
```

## Determine the center and radius of each of the following.
#fail  

step  1 :  group the  $x^2  \cap  y^2$ together    
$$
\begin{array}{l}
x^2 +  y ^2  +  8x + 7    = 0   \\
 x^2 +  y ^2  +  8x     = -  7 
\end{array}
$$ 
step 2:  for each of the term complete the square on the two term 


$$
\begin{array}{l}
x^2 +  y ^2  +  8x + 7    = 0   \\
 x^2   +  8x  + 16 +  y ^2      = -  7  + 16  \\
(x + 4)^2   + y^2  =  9 
\end{array}
$$
step 3 : since this is the  standard form of the equation of the circle and so we can  pick the center  and radius right  off this . 
$$
\text{center} =  (-4 ,  0)  \;  \text{radius } = \sqrt{  9 } =3  
$$
$$
\begin{array}{l}
x^2 + y^2  -3x + 10y   -1  = 0    \\
x^2 + y^2  -3x + 10y  = 1  \\
x^2  - 3x  + \frac{9}{4}  + y^2 +  10y   +  25   =  \frac{113}{4}  \\
\left( x  - \frac{3}{2} \right)^2   +  (y+ 5)^2  =  \frac{113}{4}   \\
\end{array}
$$ so  now we can pick the center and radius right off this : 
$$
\text{center} =  (\frac{3}{2}  , - 5)  \;  \text{radius } = \sqrt{   \frac{113}{4}  } 
$$


# #Practice_Exercise  

1. Write the equation of the circle with radius 3 and center (6,0) 
$$
(x -  6)^2  +  y^2  = 9
$$
2. Write the equation of the circle with radius $\sqrt{ 7 }$ and center (−1,−9) . 
$$
(x +  1)^2  (x+ 9)^2   = 7
$$

## determine the radius and center of the circle and sketch the graph of the circle. 


$$
\begin{array}{l}
(x - 9)^2  +  (y + 4)^2  = 25     \\
\end{array}

$$
the radius of the circle is  5  , the center point of the circles  is ( 9 , - 4)


$$
\begin{array}{l}
x^2  +  (y - 5)^2   = 4    \\

\end{array}
 
$$