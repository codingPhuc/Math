# #definition   
in this chapter we will be solving  rational  inequation  .   It is the same process as solving  [[Section 2.12  Polynomial Inequalities]] 
$$
\frac{x + 1}{ x - 5} \leq    0  

$$
We do  not  solve it the same way we solve rational  expression  . With equation the first thing  we did  was  clear out the denominator by  multiplying it  with the less  common denominator  .   However    , that solution will not work  this  time  
Since we do not  know  if the denominator will be a positive or negative value   ,  because  if we were to  multiply  the   sign of the comparator will switch  side  leading  to  un predictable out  come  for  our equation  . To make thing  worse , recall that the solution of x  for the equation can be  both  positive and negative 
1. the first step  is to  get zero  on  one side 
2. the second step is to factor   the  numerator and the denominator   
3. the third step  is to determine  where  both the numerator and denominator are  0  
 for the example above we  have   numerator :$x=−1$ denominator : $x=5$ 
 there are two  reason  why we need the  to find the 0   value  in both the denominator and numerator   :  
	1.  the first reason is that we need to find the region  where the rational  expression may change sign  similar too   [[Section 2.12  Polynomial Inequalities]]  
	2. the second reason  is that we need to figure  out  where to  avoid  value that  make the denominator  0    

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-10,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-10,-8,-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
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
so the interval notation  for the above  is  $$
[-1 ,5 ) $$


##  solving inequalities for  polynomial  in rational expression  

$$\begin{array}{l}
\frac{x^2  + 4x  +  3}{ x -  1   }  > 0 \\
\frac{(x  + 1) ( x + 3  )}{ x -  1   }  > 0    \\
  \left\{
\begin{array}{l} 
x =  -1   \\
x  =  -3   \\
x  = 1    \\
\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-1,-1.5) -- (-1,1.5);
    \draw[dashed] (-3 ,-1.5) -- (-3  ,1.5); 
    \draw[dashed] (1 ,-1.5) -- (1,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{(-5  + 1) ( -5+ 3  )}{ -5 -  1   }  <0    $};
    
    \node at ( -2,1.8) {$x = -2$};
    \node at ( -2,1.2) {$\frac{(-2  + 1) ( -2+ 3  )}{ -2 -  1   }  > 0    $};
    
    \node at ( 0,1.8) {$x = 0$};
    \node at ( 0,1.2) {$\frac{(0  + 1) ( 0 + 3  )}{ 0 -  1   }  < 0  $};
    
    \node at ( 2,1.8) {$x = 2$};
    \node at ( 2,1.2) {$\frac{(2  + 1) ( 2+ 3  )}{ 2 -  1   }  >0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(-3  ,  -1    )    \cap (1 ,    + \infty  )    $$




$$\begin{array}{l}
\frac{x^2    -  16 }{ (x -  1 )^2    }  > 0 \\
\frac{(x +  4) ( x  -4  )}{ (x -  1 )^2    }  > 0    \\
  \left\{
\begin{array}{l} 
x =  -4  \\
x  =  +  4    \\
x  =    1     \\
\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-4,-1.5) -- (-4,1.5);
    \draw[dashed] (1 ,-1.5) -- (1  ,1.5); 
    \draw[dashed] (4 ,-1.5) -- (4,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{(-5 +  4) ( -5 -4  )}{ (-5 -  1 )^2    }  > 0  $};
    

    \node at ( 0,1.8) {$x = 0$};
    \node at ( 0,1.2) {$\frac{(0 +  4) ( 0  -4  )}{ (0 -  1 )^2    }  <  0   $};
    
    \node at ( 2,1.8) {$x = 2$};
    \node at ( 2,1.2) {$\frac{(2 +  4) ( 2  -4  )}{ (2 -  1 )^2    }  <  0    $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$\frac{(6 +  4) ( 6   -4  )}{ (6  -  1 )^2    }  > 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(-4  ,   1   )    \cap (1 ,   4  )    $$





##  Don't have zero   at one side of the  inequation  





$$\begin{array}{l}
\frac{3x     + 1  }{   x +  4    }  \geq 1 \\
\frac{3x     + 1  }{   x +  4    }    -  1  \geq 0     \\
\frac{3x     + 1   -  x   -   4   }{   x +  4    }      \geq 0    \\
\frac{2x    -   3     }{   x +  4    }      \geq 0   \\
  \left\{
\begin{array}{l} 
x =  \frac{3}{2} \\
x  =  -  4    \\

\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (1.5,-1.5) -- (1.5,1.5);
    \draw[dashed] (-4 ,-1.5) -- (-4,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{2 .  -5    -   3     }{   -5 +  4    }   > 0  $};
    

    \node at ( 0,1.8) {$x = 0$};
    \node at ( 0,1.2) {$\frac{2.  0  -   3     }{   0 +  4    }  <  0   $};

    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$\frac{2 .  6    -   3     }{   6 +  4    }  > 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(  - \infty    ,    -  4     )    \cap \left[\frac{3}{2} ,   \infty \right)    $$





$$\begin{array}{l}
\frac{x  -  8    }{   x   }  \leq   3  - x    \\
\frac{x  -  8    }{   x   }  +  x  - 3   \leq  0     \\
\frac{x  -  8    +   x^2   - 3x   }{   x   }   \leq  0    \\
\frac{  x^2   - 2x   -8    }{   x   }   \leq  0  \\
\frac{ (x  -  4  ) (x +  2  )    }{   x   }   \leq  0  \\ \\ 
  \left\{
\begin{array}{l} 
x =  4 \\
x  =  - 2   \\
x   =   0      \\

\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-2,-1.5) -- (-2 ,1.5);
    \draw[dashed] (0,-1.5) -- (0,1.5);
    \draw[dashed] (4 ,-1.5) -- (4,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{ (-5  -  4  ) (-5 +  2  )    }{   -5   }  > 0  $};
    
    \node at ( -1,1.8) {$x = -1$};
    \node at ( -1,1.2) {$\frac{ (-1 -  4  ) (-1+  2  )    }{   -1   }  >   0   $};

	\node at ( 2,1.8) {$x =  2$};
    \node at ( 2 ,1.2) {$\frac{ (2 -  4  ) (2 +  2  )    }{   2  } <  0   $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$\frac{ (6  -  4  ) (6 +  2  )    }{   6   }  > 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(  0   ,    4     ]      $$

#  #Practice_Exercise   



$$\begin{array}{l}
\frac{4  -  x    }{   x   +  3   }  > 0     \\

  \left\{
\begin{array}{l} 
x =  4 \\
x  =   -  3     \\
\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-3,-1.5) -- (-3 ,1.5);
    \draw[dashed] (4 ,-1.5) -- (4,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{4  +  5   }{   -5  +  3   } <  0  $};
    
	\node at ( 2,1.8) {$x =  2$};
    \node at ( 2 ,1.2) {$\frac{4  -  2   }{   2   +  3   } >   0   $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$\frac{4  -  6    }{   6   +  3   } < 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(  -3  ,    4     )       $$




$$\begin{array}{l}
\frac{2z - 5     }{  z   - 7     }  \leq 0    \\

  \left\{
\begin{array}{l} 
x =  \frac{5}{2} \\
x  =     7  \\

\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-2,0) -- (10 ,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-2,-1,0,1,2,3,4,5,6,7,8  , 9 , 10 } {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (2.5,-1.5) -- (2.5 ,1.5);
    \draw[dashed] (7,-1.5) -- (7,1.5);
    % Text annotations

    \node at ( -1,1.8) {$x = -1$};
    \node at ( -1,1.2) {$\frac{2. -1  - 5     }{  -1  - 7     } >   0   $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$\frac{2. 6 - 5     }{  6  - 7     } < 0    $};
    
    \node at ( 9,1.8) {$x = 9$};
    \node at ( 9,1.2) {$\frac{2. 9 - 5     }{  9   - 7     }  > 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
[  \frac{5}{2} ,    7     )      $$




$$\begin{array}{l}
\frac{  w^2+5w−6    }{   w   -3     }     
≥  0  \\
 \frac{ ( w  +   6)  ( w -1  )   }{   w   -3     }  \\ 
  \left\{
\begin{array}{l} 
x =  3 \\
x  =  - 6 \\
x   =   1       \\

\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-6,-1.5) -- (-6 ,1.5);
    \draw[dashed] (1,-1.5) -- (1,1.5);
    \draw[dashed] (3 ,-1.5) -- (3,1.5);
    % Text annotations
	    
    \node at ( -7,1.8) {$x = -7$};
    \node at ( -7,1.2) {$ \frac{ ( -7  +   6)  ( -7 -1  )   }{  -7   -3     }  <   0   $};

	
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$ \frac{ ( -5  +   6)  ( -5 -1  )   }{  -5  -3     }   > 0  $};


	\node at ( 2,1.8) {$x =  2$};
    \node at ( 2 ,1.2) {$ \frac{ ( 2  +   6)  ( 2 -1  )   }{   2   -3     }  <  0   $};
    
    \node at ( 6,1.8) {$x = 6$};
    \node at ( 6,1.2) {$ \frac{ ( 6  +   6)  ( 6 -1  )   }{   6   -3     }   < 0    $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
[  -6  ,    1    ]      $$





$$\begin{array}{l}
\frac{3x+8    }{   x  -1     } < -2     \\
\frac{3x+8    }{   x  -1     }  + 2  <    0    \\
\frac{3x+8  + 2x    -2     }{   x  -1     }  +   <    0    \\
\frac{5x+6     }{   x  -1     }    <    0     \\ 
  \left\{
\begin{array}{l} 
x =  -\frac{6}{5} \\
x  =  1  \\

\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-1.2,-1.5) -- (-1.2 ,1.5);
    \draw[dashed] (1,-1.5) -- (1,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$\frac{5 .  -5+6     }{  -5 -1     } > 0  $};
    
    \node at ( 0,1.8) {$x =   0 $};
    \node at ( 0 ,1.2) {$\frac{5 . 0 +6     }{   0 -1     } <  0   $};

	\node at ( 2,1.8) {$x =  2$};
    \node at ( 2 ,1.2) {$\frac{5 . 2 +6     }{ 2 -1     } >   0   $};
    

    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
( -\frac{6}{5}  ,   1     )      $$










$$\begin{array}{l}
u  \leq   \frac{4}{u  - 3 }       \\
u  - \frac{4}{u  - 3 }      \leq       0   \\
 \frac{  u^2     -3u   -  4}{u  - 3 }   \\
 \frac{ (   u   -4) ( u   + 1  )}{u  - 3 }   \\  \\
  \left\{
\begin{array}{l} 
x =  4 \\

x  = 3 \\ 
x  =  -1  \\
\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-1,-1.5) -- (-1 ,1.5);
    \draw[dashed] (3,-1.5) -- (3,1.5);
    \draw[dashed] (4,-1.5) -- (4,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$ \frac{ (   -5   -4) ( -5  + 1  )}{-5 - 3 }  < 0  $};
    
    \node at ( 0,1.8) {$x =   0 $};
    \node at ( 0 ,1.2) {$ \frac{ (   0   -4) ( 0   + 1  )}{0  - 3 }  > 0   $};

	    
    \node at ( 3.5,1.8) {$x =   03.5$};
    \node at ( 3.5 ,1.2) {$ \frac{ (   3.5  -4) ( 3.5 + 1  )}{3.5  - 3 }  <  0   $};
    
	\node at ( 6,1.8) {$x =  6$};
    \node at ( 6 ,1.2) {$ \frac{ (   6   -4) ( 6  + 1  )}{6 - 3 }  >   0   $};
    

    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
( -\infty  ,   -1     ]    \cap ( 3   ,4]      $$




$$\begin{array}{l}
\frac{t^3−6t^2}{t -2  }    >0  \\
\frac{t^2 (t   -  6  ) }{t -2  }    >0   \\
  \left\{
\begin{array}{l} 
x =  6 \\

x  = 2 \\ 
x  =  0  \\
\end{array} \\

\right.
\end{array}$$



```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-7,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (0,-1.5) -- (0 ,1.5);
    \draw[dashed] (2,-1.5) -- (2,1.5);
    \draw[dashed] (6,-1.5) -- (6,1.5);
    % Text annotations
	\node at ( -5,1.8) {$x = -5$};
    \node at ( -5,1.2) {$ \frac{-5^2 (-5  -  6  ) }{-5 -2  }   > 0  $};
    
    \node at ( 1,1.8) {$x =   1 $};
    \node at ( 1 ,1.2) {$ \frac{1^2 (1   -  6  ) }{1 -2  }  > 0   $};

	    
    \node at ( 3,1.8) {$x =   3$};
    \node at ( 3 ,1.2) {$ \frac{3^2 (3  -  6  ) }{3 -2  }   <  0   $};
    
	\node at ( 6,1.8) {$x =  6$};
    \node at ( 6 ,1.2) {$ \frac{t^2 (t   -  6  ) }{t -2  }  >   0   $};
    

    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
( -\infty  ,   -1     ]    \cap ( 3   ,4]      $$


