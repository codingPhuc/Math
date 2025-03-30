

Now we need to discuss  about graphing functions . if we recall from the pervious section we said that $f(x)$ is nothing more than a fancy way of writing y .This mean that we already know how to graph functions . We graph function in exactly the same way we graph equations . If we know ahead of time what the function is a graph of , we can used that information to help us graph , and if we do not know what the function is ahead of time then all we need to do is to plug in some x to compute the value of the funciton (which is really a y value) then plot the point 

$$
\begin{array}{l}
f(x) =   (x - 1)^3 + 1 
\end{array}
 
$$
in this graph we plug in the value of x to get  the value of y , then draw the graph  : 

| $x$ | $f(x)$ | $(x,y)$  |
| --- | ------ | -------- |
| -1  | -7     | (-1, -7) |
| 0   | 0      | (0,0 )   |
| 1   | 1      | (1,1)    |
| 2   | 2      | (2,2)    |
| 3   | 9      | (3,9)    |


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
    \fill (-1, -7) circle (2pt) node[above right] {$(3,0)$};
	\fill (0,0 ) circle (2pt) node[above right] {$(0,0 )$}; 
	\fill (1,1) circle (2pt) node[above right] {$(1,1)$};
	\fill (2,2) circle (2pt) node[above right] {$(2,2)$};
	\fill (3,9)   circle (2pt) node[above right] {$(3,9) $};
    % Draw the parabola
    \draw[thick, blue, domain=-1:2, smooth] plot (\x, {( \x - 1)^3+1});
\end{tikzpicture}
\end{document}


``` 

So  graphing function is pretty much the same as graphing equations 

There is one function we have seen  ,  that have not been  graphed like the first part of this chapter 

##  sketch the graph of the following piecewise function 
$$
\begin{aligned}\bullet\\\\g\left(x\right)=\left\{\begin{array}{ll}-x^{2}+4&\mathrm{if~}x<1\\2x-1&\mathrm{if~}x\geq1\end{array}\right.\end{aligned}
$$
okay when  graphing piecewise function  we are graphing serval function at one, except when we are going to graph them on specific interval .  
what does specific interval mean ? 
