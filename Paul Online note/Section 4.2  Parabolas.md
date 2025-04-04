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
    \fill (1, 1) circle (2pt) node[above right] {$(1, 1) $};
    \fill[red] (1, 3) circle (2pt) node[above right] {$(1, 3)$};


    % Draw the parabola
    \draw[thick, blue, domain=-2:1, smooth] plot (\x, {-(\x)^2  + 4});
    \draw[thick, red, domain=1:3, smooth] plot (\x, {2*\x  - 1});
\end{tikzpicture}
\end{document}


``` 

# #todo

- [ ] $f(x)  = a(x  -  h)^2 + k$ where did this formula came from , prove it 