

Now we need to discuss  about graphing functions . if we recall from the pervious section we said that $f(x)$ is nothing more than a fancy way of writing y .This mean that we already know how to graph functions . We graph function in exactly the same way we graph equations . If we know ahead of time what the function is a graph of , we can used that information to help us graph , and if we do not know what the function is ahead of time then all we need to do is to plug in some x to compute the value of the funciton (which is really a y value) then plot the point 

$$
\begin{array}{l}
f(x) =   (x - 1)^3 + 1 
\end{array}
 
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
