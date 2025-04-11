---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Transformations.aspx
tags:
  - In_Progress
reference: https://www.youtube.com/watch?v=Tmdrjs9xufc&ab_channel=TheOrganicChemistryTutor
Current date: 2025-04-11
---

$f(x)+ 2$  vertical shift graph is gona move up 2 unit 
$f(x) -3$ vertical shift down 3 unti 

$f(x-4)$ horizon tal shift , this shift is 4 unit to the right 
$f(x+3)$ shift to the left 3 unit  

$-f(x)$  reflex over the x-axis 
$f(-x)$ reflex over the y-axis
$-f(-x)$ reflex over the origin 

2$f(x)$ vertical stretch 
$\frac{1}{2}f(x)$ shink vertically 
$f(2x)$ horizontal shink 
$f\left( \frac{1}{2}x \right)$ horizontal stretch 


$y =\sqrt{ x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, { sqrt(\x )  });
 
\end{tikzpicture}
\end{document}


``` 



$y = - \sqrt{ x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {- sqrt(\x )  });
 
\end{tikzpicture}
\end{document}


``` 



$y = \sqrt{ -x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, { sqrt(-\x )  });
 
\end{tikzpicture}
\end{document}


``` 




$y = -\sqrt{ -x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {- sqrt(-\x )  });
 
\end{tikzpicture}
\end{document}


``` 

$y=\mid  x \mid$




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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```




$y= 2\mid x \mid$ 





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {2*-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {2*\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
vertical stretch mean the y value increase 


$y=\frac{1}{2}\mid x \mid$





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:-4, smooth] plot (\x, {0.5*-\x} );
	\draw[thick, blue, domain=0:4, smooth] plot (\x, {0.5*\x } );
   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```

vertical shrink when the y value decrease 


$y=\sqrt{ x }$




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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {sqrt(\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```

$y=\sqrt{ 2x }$ 





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:4, smooth] plot (\x, {sqrt(2*\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
this is a horizontal shrink because the x value is less than what is needed for y to reach 2 

$y=\sqrt{ \frac{1}{2} }x$





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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=0:8, smooth] plot (\x, {sqrt(0.5*\x)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
this is a horizontal stretch because the x value need to be increase in order to reach the same y value 


$y= \sqrt[3]{ x }$ 

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
    \fill (0,3) circle (2pt) node[above right] {$(0,3) $};


    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, {pow(\x, 3)} );

   %%  \draw[dotted, red, domain=-4:0, smooth] plot (\x, {-\x-2} ); %%
%% 	\draw[dotted, red, domain=0:4, smooth] plot (\x, {\x -8} ); %%


\end{tikzpicture}
\end{document}


```
