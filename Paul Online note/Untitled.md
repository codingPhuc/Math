```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-10,0) -- (7,0) node[right] {};
    \draw[->] (0,-10) -- (0,7) node[right] {};
    % Draw tick marks and labels

    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-1,-1.5) -- (-1,1.5);
    \draw[dashed] (5 ,-1.5) -- (5,1.5);
    % Text annotations
    \node at ( -2,1.8) {$x = -2$};
    \node at ( -2,1.2) {$ \frac{-1}{7}  > 0    $};
    
    \node at ( 0,1.8) {$x = 0$};
    \node at ( 0,1.2) {$\frac{-1}{5}  > 0      $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at (6,1.2) {$7 >  0 $};
    
\end{tikzpicture}
\end{document}


```
