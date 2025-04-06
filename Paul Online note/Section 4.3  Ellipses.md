---
title: Adjunction
references: 
tags:
  - In_Progress
reference: https://tutorial.math.lamar.edu/Classes/Alg/Ellipses.aspx
Current date: 2025-04-06
---
# #definition 
In the pervious [[Section 3.3  Circles]] we look at graph and circle since circle are a special cases of ellipses we've already got most of the tools under our belt . All we really need to do to get us started is the standard form of ellipse and info about how to interpret it 

here is the standard form of ellipse 
$$
\frac{(x -  h)^2}{a^2} + \frac{(y  - k)^2} { b^2 }   = 1 
$$

Note that  the right side need to be exactly one in order for this too work 
just like with graphing a circle all we need to graph a ellipse is the right most top most bottom most and left most point . 
$$
\begin{array}{l} \\
\text{right most point} ( h + a , k) \\
\text{left most point} (h   -a  , k)
 \\
\text{top most point}( h , k + b)
 \\
\text{bottom most point}(h  , k -b )

\end{array}
$$
## Sketch the graph of each of the following ellipses.

$$
\begin{array}{l} \\
\frac{(x + 2)^2}{9}  +  \frac{( y - 4)^2 }{ 25}  =  1  \\
h    =  -2   \\
k =  4   \\
a  =  3   \\
b   = 5 
\end{array}
$$
$$
\begin{array}{l} \\
\text{right most point} ( 1 , 4) \\
\text{left most point} (   -5  , 4)
 \\
\text{top most point}( -2 , 9 )
 \\
\text{bottom most point}(-2  ,-1 )

\end{array}
$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}
%% \documentclass[pstricks,border=12pt]{standalone} %%
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
	\fill  ( 1 , 4) circle (2pt) node[above left] {$ ( 1 , 4)$};
	\fill (   -5  , 4) circle (2pt) node[above left] {$(   -5  , 4)$};
	\fill ( -2 , 9 )  circle (2pt) node[above left]  {$( -2 , 9 ) $};
	\fill (-2  ,-1 ) circle (2pt) node[above left]{$(-2  ,-1 )$};
    % Draw x-axis

	\draw[thick, blue] (-2,4) ellipse [x radius=3, y radius=5];

    
                    
\end{tikzpicture}
\end{document}
```





$$
\begin{array}{l} \\
\frac{x^2}{49} + \frac{(y  - 3 )^}{} \\
h    =  -2   \\
k =  4   \\
a  =  3   \\
b   = 5 
\end{array}
$$
$$
\begin{array}{l} \\
\text{right most point} ( h + a , k) \\
\text{left most point} (h   -a  , k)
 \\
\text{top most point}( h , k + b)
 \\
\text{bottom most point}(h  , k -b )

\end{array}
$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}
%% \documentclass[pstricks,border=12pt]{standalone} %%
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
	\fill ( 1 , 5 )  circle (2pt) node[above left] {$( 1 , 5 )$};
	\fill ( 5 , 5)  circle (2pt) node[above left] {$( 5 , 5)$};
	\fill ( 3 , 9 )  circle (2pt) node[above left]  {$( 3 , 9 ) $};
	\fill (3,1)  circle (2pt) node[above left]{$(5,-4)$};
    % Draw x-axis

	\draw[thick, blue] (-2,4) ellipse [x radius=3, y radius=5];

    
                    
\end{tikzpicture}
\end{document}
```






$$
\begin{array}{l} \\
\frac{(x + 2)^2}{9}  +  \frac{( y - 4)^2 }{ 25}  =  1  \\
h    =  -2   \\
k =  4   \\
a  =  3   \\
b   = 5 
\end{array}
$$
$$
\begin{array}{l} \\
\text{right most point} ( h + a , k) \\
\text{left most point} (h   -a  , k)
 \\
\text{top most point}( h , k + b)
 \\
\text{bottom most point}(h  , k -b )

\end{array}
$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}
%% \documentclass[pstricks,border=12pt]{standalone} %%
\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    \draw[->] (-4,0) -- (4,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[right] {};
    % Draw tick marks and labels
    \foreach \x in {,-4,-3,-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
        \foreach \y in {-4,-3,-2,-1,1,2,3,4} {
        \draw (0.1,\y) -- (-0.1,\y) node[below] {\y};
    } 
	\fill ( 1 , 5 )  circle (2pt) node[above left] {$( 1 , 5 )$};
	\fill ( 5 , 5)  circle (2pt) node[above left] {$( 5 , 5)$};
	\fill ( 3 , 9 )  circle (2pt) node[above left]  {$( 3 , 9 ) $};
	\fill (3,1)  circle (2pt) node[above left]{$(5,-4)$};
    % Draw x-axis

	\draw[thick, blue] (-2,4) ellipse [x radius=3, y radius=5];

    
                    
\end{tikzpicture}
\end{document}
```

