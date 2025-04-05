# #definition  

In this section we want to look at the graph of a quadratic function . The most general form of the quadratic function is 
$$
f(x)   = ax^2   + bx + c
$$
the graph of the  function are called **parabolas** . here are some example of parabolas 
![[Pasted image 20250403173519.png]]
all parabolas are vaguely "U" shaped and they will have a highest and lowest point  called the vertex .  Parabolas may open  up or down and may or may not have a x-intercept but they will almost have a single y-intercept 
parabola that open down will always open down and parabola that open up will always open up . As a result , an parabola does not start opening up if it already start opening down and vice versa 

the dash line in a parabolas is called the axis of symmetry . Every parabolas have a axis of symmetry , additionally the graph in one side of the axis of symmetry is a mirror to another 

intercepts are the point where the graph will cross the x and y axis . We also saw a graph in [[Section 3.1 Graphing#Determine the x-intercepts and y-intercepts for each of the following equations.]] where a graph touch the intercept but does not cross it   
##  sketching Parabolas  

1. Find the vertex .There are simple method to finding this which we will discuss latter 
2. Finding the y intercept $(0,f(0))$ 
3. solve the $f(x)= 0$ intercept if they exits , there are multiple number of solution ranging from 0 to 2 x-intercept 
4. Make sure you got one point in each side of the vertex . Firstly , if the parabola have two x-intercepts we already got these point by solving the quadratic equation . Secondly , if it have only one x-intercepts then we plug in another value of x .  Finally , if there are no x-intercepts then we need to used the y-intercepts and the axis of symmetry to get the second point 
5. Sketch the graph 
Now there are two form of the parabola that we will be looking at. The first form method is easy , while the second form require more work to sketch 
$$
f(x)  = a(x  -  h)^2 + k  
$$
there are two pieces of information about the parabola that we can get form this function . If a is positive then the parabola will open up and if a is negative then the parabola will open down .Secondly , the vertex of the parabola is the point (h, k) . Be careful with sign when getting the vertex 

##  sketch the graph of the following parabolas 


$$
\begin{array}{l}  \\
f(x) =  2(x +  3)^2 - 8   \\

\end{array}
$$

1. Find the vertex .There are simple method to finding this which we will discuss latter  
the vertex of the equation above is $(-3, -8)$ 
2. Finding the y intercept $(0,f(0))$  
$$
\begin{array}{l} 
f(0)  = 2(0 +  3)^2 - 8 \\
f(0)  = 10 
\end{array}
$$
3. solve the $f(x)= 0$ intercept if they exits , there are multiple number of solution ranging from 0 to 2 x-intercept  
$$
\begin{array}{l} 
 2(x +  3)^2 - 8  =0  \\
2(x^2   + 6x + 9 ) - 8  = 0   \\
2x^2  +  12x + 10 = 0  \\
x^2   + 6x  +  5   =0    \\ 
(x   + 5)( x   + 1 ) \\
\left\{  \\
\begin{array}{l}
x  = -5  \\
x =  -1  
\end{array}
\right.
\end{array}
$$

Make sure that you’ve got at least one point to either side of the vertex. This is to make sure we get a somewhat accurate sketch. If the parabola has two xx-intercepts then we’ll already have these points. If it has 0 or 1 xx-intercept we can either just plug in another xx value or use the yy-intercept and the axis of symmetry to get the second point.
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
    \fill (-5, 0) circle (2pt) node[above right] {$(-5, 0) $};
    \fill[red] (-1, 0) circle (2pt) node[above right] {$(-1, 0)$};


    % Draw the parabola
    \draw[thick, blue, domain=-6:0, smooth] plot (\x, {2*(\x +  3)^2 - 8  });
 
\end{tikzpicture}
\end{document}


``` 





$$
\begin{array}{l}  \\
g(x) = -(x -2)^2 - 1  \\
\end{array}
$$

1. Find the vertex .There are simple method to finding this which we will discuss latter  
the vertex of the equation above is $(2, -1)$ 
2. Finding the y intercept $(0,f(0))$  
$$
\begin{array}{l} 
g(0) = -(0 -2)^2 - 1\\
g(0)  = -5
\end{array}
$$
3. solve the $f(x)= 0$ intercept if they exits , there are multiple number of solution ranging from 0 to 2 x-intercept  
#fail 
$$
\begin{array}{l} 
 -(x -2)^2 - 1 = 0   \\
-(x - 2)^2    =  1  \\
 (x - 2)^2   = -  1   
\\
\left\{  \\
\begin{array}{l}
x - 2  = -i  \\
 x-  2 =  i  
\end{array} \\ \\
\implies 
\left\{  \\
\begin{array}{l}
x   = -i  +  2 \\
 x =  i   + 2
\end{array}
\right.
\right.
\end{array}
$$
this  indicate that there is no x intercept  
Make sure that you’ve got at least one point to either side of the vertex. This is to make sure we get a somewhat accurate sketch. If the parabola has two xx-intercepts then we’ll already have these points. If it has 0 or 1 xx-intercept we can either just plug in another xx value or use the yy-intercept and the axis of symmetry to get the second point.
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
    \fill (0,-5) circle (2pt) node[above right] {$(0,-5) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, { -(\x -2)^2 - 1});
 
\end{tikzpicture}
\end{document}


``` 






$$
\begin{array}{l}  \\
h(x)   = x^2   + 4   \\
\end{array}
$$

1. Find the vertex .There are simple method to finding this which we will discuss latter  
the vertex of the equation above is $(0, 4)$ since this indicate that the vertex is above the x axis we concluded that there will not be a x intercept 
2. Finding the y intercept $(0,f(0))$  
$$
\begin{array}{l} 
h(0) =  0^2   + 4  \\
h(0)  = 4 
\end{array}
$$
3. solve the $f(x)= 0$ intercept if they exits , there are multiple number of solution ranging from 0 to 2 x-intercept  
$$
\begin{array}{l} 
x^2   + 4  = 0   \\
x  =  \pm  2i
\\

\end{array}
$$
this  indicate that there is no x intercept  
Make sure that you’ve got at least one point to either side of the vertex. This is to make sure we get a somewhat accurate sketch. If the parabola has two xx-intercepts then we’ll already have these points. If it has 0 or 1 xx-intercept we can either just plug in another xx value or use the yy-intercept and the axis of symmetry to get the second point.
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
    \fill (0,4) circle (2pt) node[above right] {$(0,4) $};


    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, {  (\x)^2   + 4  });
 
\end{tikzpicture}
\end{document}


``` 


##  graph a general  form of a parabola 
We need to understand how to graph a parabola in it general form . 
$$
f(x)  = ax^2  + bx + c  
$$
a just like the old form will determine if a parabola  is open upward or downward . Unlike the pervious we will not get the vertex for free this time 
However it will still be easy to find the vertex for a general form 
$$
\left( -\frac{b}{2a} ,  f\left( -\frac{b}{2a} \right) \right)
$$
all we are doing is computing the x  coordinate from  a and b the plug it into y coordinate  . Not quite as simple but still good enough 
note as well we can still get the free  intercept in this form it is 
$$
f(0)  = a 0^2  + b\cdot 0  + c  
$$




sketch  the graph of each of the following parabolas 
$$
g(x)  = 3x^2 - 6x + 5 
$$
the y  intercept is  : 

$$
\begin{array}{ l}
g(x)  = 3x^2 - 6x + 5   \\
g(0)  = 3\cdot 0^2   - 6\cdot 0  +  5   \\
g(0)  = 5 
\end{array}
$$
the vertex of the equation is 
$$
x =  -\frac{b}{2a}   = \frac{6}{6}   = 1  
$$

$$
\begin{array}{ l}
g(x)  = 3x^2 - 6x + 5   \\
g( 1 )  = 3\cdot  1 ^2   - 6\cdot  1   +  5   \\
g(1)  = 2 
\end{array}
$$
the vertex is $(1,2)$



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
    \fill (0,5) circle (2pt) node[above right] {$(0,5)$};
	\fill (2,5) circle (2pt) node[above right] {$(2,5) $};

    % Draw the parabola
    \draw[thick, blue, domain=0:2, smooth] plot (\x, {  3*(\x)^2 - 6*\x + 5  });
 
\end{tikzpicture}
\end{document}


``` 








sketch  the graph of each of the following parabolas 
$$
g(x)  =  - x^2  +  8x 
$$
the y  intercept is  : 

$$
\begin{array}{ l}
g(x)  =  - x^2  +  8x  \\
g(0)  =  - 0^2  +  8\cdot0 \\
g(0)  = 0 
\end{array}
$$
the vertex of the equation is 
$$
x =  -\frac{b}{2a}   = \frac{-8}{-2}   = 4   
$$

$$
\begin{array}{ l}
g(x)  =- x^2  +  8x   \\
g( 4 )  = - (4)^2  +  8\cdot 4   \\
g(4)  = 16 
\end{array}
$$

the vertex is $(4,16)$



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
    \fill (0,0) circle (2pt) node[above right] {$(0,0)$};

    % Draw the parabola
    \draw[thick, blue, domain=0:5, smooth] plot (\x, {  - (\x)^2  +  8*\x   });
 
\end{tikzpicture}
\end{document}


``` 










sketch  the graph of each of the following parabolas 
$$
g(x)  =   x^2  + 4x  +  4 
$$
the y  intercept is  : 

$$
\begin{array}{ l}
g(x)  =    x^2  + 4x  +  4   \\
g(0)  =   0^2  + 4\cdot 0  +  4 \\
g(0)  = 4  
\end{array}
$$
the vertex of the equation is 
$$
x =  -\frac{b}{2a}   = \frac{-4}{2}   = -2    
$$

$$
\begin{array}{ l}
g(x)  =x^2  + 4x  +  4 \\
g(-2)  =-2^2  + 4\cdot -2   +  4    \\
g(-2)  = 0 
\end{array}
$$

the vertex is $(-2,0)$



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
    \fill (-2,0) circle (2pt) node[above right] {$(-2,0)$};

    % Draw the parabola
    \draw[thick, blue, domain=-4:0, smooth] plot (\x, { (\x)^2  + 4*\x  +  4   });
 
\end{tikzpicture}
\end{document}


``` 



how to take a parabola in general form and convert it into the form 
$$
 f(x)  = a(x  - h )^2  + k 
$$
we should used the method completing the square in [[Section 2.6  Quadratic Equations - Part II#Completing the Square]] 

$$
\begin{array}{l}
f(x)=2x^2−12x+3   \\
f(x)=2x^2−12x+3 + 36  -  36   \\
f(x)=()   -  33
\end{array}
$$
# #todo

- [ ] $f(x)  = a(x  -  h)^2 + k$ where did this formula came from , prove it 