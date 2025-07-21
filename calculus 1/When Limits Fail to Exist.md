
$$
\lim_{ x \to 7 } f(x)   = 30  \cap \lim_{ n \to 7 }g(x) = 2  
$$
1. one sided limit on the left and on the right are not equal  
```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Axes
    \draw[->] (-3,0) -- (3,0) node[right] {};
    \draw[->] (0,-2) -- (0,2) node[above] {};

    % Ticks
    \foreach \x in {-2,-1,0,1,2} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-1,1} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Step function
    \draw[blue, thick] (-3,1) -- (0,1);
    \draw[blue, thick] (0,-1) -- (3,-1);
    \filldraw[white] (0,1) circle (2pt); % open circle
    \draw[blue] (0,1) circle (2pt);
    \fill[blue] (0,-1) circle (2pt);     % closed circle
\end{tikzpicture}
\end{document}
```


2. vertical asymptotes
```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width


\begin{tikzpicture}[x=1cm,y=1cm]
    \draw[->] (-3,0) -- (5,0) node[right] {};
    \draw[->] (0,-4) -- (0,4) node[above] {};

    % Ticks
    \foreach \x in {-2,-1,0,1,2,3,4} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-3,-2,-1,1,2,3} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Asymptote
    \draw[dashed, red] (1,-4) -- (1,4);

    % Graph of 1/(x-1)
    \draw[domain=-2.9:0.9, smooth, thick, blue] plot(\x,{1/(\x - 1)});
    \draw[domain=1.1:4.9, smooth, thick, blue] plot(\x,{1/(\x - 1)});
\end{tikzpicture}
\end{document}


```


3. wild behavior 
```tikz

```
```tikz 

\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=10cm, y=3cm]
    \draw[->] (-0.2,0) -- (0.2,0) node[right] {};
    \draw[->] (0,-1.2) -- (0,1.2) node[above] {};

    % Ticks
    \foreach \x in {-0.2,-0.1,0.1,0.2} {
        \draw (\x,0.05) -- (\x,-0.05);
    }
    \foreach \y in {-1,1} {
        \draw (0.01,\y) -- (-0.01,\y) node[left] {\y};
    }

    % Plot sin(1/x)
    \draw[domain=0.01:0.2, smooth, variable=\x, thick, blue] plot ({\x},{sin(1/\x r)});
    \draw[domain=-0.2:-0.01, smooth, variable=\x, thick, blue] plot ({\x},{sin(1/\x r)});
\end{tikzpicture}

\end{document}
```

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width


\begin{tikzpicture}[x=10cm, y=3cm]
    \draw[->] (-0.2,0) -- (0.2,0) node[right] {};
    \draw[->] (0,-1.2) -- (0,1.2) node[above] {};

    % Ticks
    \foreach \x in {-0.2,-0.1,0.1,0.2} {
        \draw (\x,0.05) -- (\x,-0.05);
    }
    \foreach \y in {-1,1} {
        \draw (0.01,\y) -- (-0.01,\y) node[left] {\y};
    }

    % Plot sin(1/x)
    \draw[domain=0.01:0.2, smooth, variable=\x, thick, blue] plot ({\x},{sin(1/\x r)});
    \draw[domain=-0.2:-0.01, smooth, variable=\x, thick, blue] plot ({\x},{sin(1/\x r)});
\end{tikzpicture}

\end{document}


```
