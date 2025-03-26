

# #definition 
we will take a quick  look at circles .  Before that however  , we are going to  take a quick a look at circle 
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
    \draw[-,dotted ] (0,3)  -- (2,3)  node[right] {};  
    \fill (0,3) circle (2pt) node[above left] {$(0,3)$};
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
    \draw[-,dotted ] (1,-4)  -- (5,-4)  node[right] {};  
     \draw[-,dotted ] (1,-4)  -- (1,0)  node[right] {}; 
    \fill (1,-4)  circle (2pt) node[above left] {$(1,-4)$};
	
	

    % Draw the parabola
   
\end{tikzpicture}
\end{document}
```

## determind the  