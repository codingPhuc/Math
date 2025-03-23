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
    \node at ( -3,2) {$( -3,2)$};
    \node at ( 1,2) {$( 1,2)$};
    
    \node at ( 2,1) {$( 2,1)$};
    \node at ( 1,2) {$\frac{-1}{5}  > 0      $};
    
    \node at ( -1,-3) {$x = 6$};
    \node at (3,-3) {$7 >  0 $};
    
\end{tikzpicture}
\end{document}


```
