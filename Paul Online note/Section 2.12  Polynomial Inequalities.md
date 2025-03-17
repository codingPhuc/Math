# #definition  
in this section we will be solving  (single )   inequalities that   involve   polynomials    of degree   at least two .  Or  to  put it in a different  perspective  the  polynomials   will not be linear any more  .  As a result , the process we  used  for solving  linear  inequalities  will not be applicable any more 


## step  for solving the  problem  
$$

\begin{array} {l}
x^2  -10   <   3x       \\
x^2    - 3x - 10   < 0     \\
(x -  5) (x +  2 ) <  0  \\
 \left\{
\begin{array}{l}
x -  5  <  0  \\
x +  2 < 0     \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
x   <   5   \\
x  < -2  

\end{array}
\right.
\right. 
\end{array} 
$$



1. get  one zero  on one side of the inequality  ,   it does not  matter which side  is going to be zero   
$$x^2    - 3x - 10   < 0$$
2. if  possible  factor the  Polynomial   , this step  is really  here to simplify the process more than  anything  .     
$$(x -  5) (x +  2 ) <  0$$
3. Determine where the polynomial  is   0  ,  this does  not help   us  solve the equation however  since  know if something  like  0 <   0  is  not a  true  inequality   . However , it will  help  us  get to the right direction 
we  need to understand the the graph in  a  polynomial  function does not  have any break  in them ,  smooth and curve    .  This mean that  when ever the  function change sign  it must be  crossing  zero   

We have already found the crossing point dividing   each region   ,  by using the point we know that this  polynomial  is divided  into 3  region each with their own sign .  If a point exit  in one region  is  a negative sign  then  any other point  in that region will be negative and vice versa  .  So  if the inequality  is not satisfy  for a point in that region  then it is not satisfied for any point in that region  

![[Pasted image 20250317123754.png]]
![[Pasted image 20250317124619.png]]
we can used test  point to test for  inequalities in   each region  , you should make these  test point  simple to plug in 
5. Write down the answer  , by  plugging in the point we can see that the middle region  satisfy the  inequality that is  desire for  our  problem . We conclude this  bases on the fact that when we plug in a  point  and it turn  out  lest  than  0   ,   so  if the inequality  is satisfy  for a point in that region  then it is  satisfied for any point in that region  .  As a result , the interval that we need to find is   $(-2 ,  5)$  



## practice example 
$$\begin{array}{l}
x^2    - 5x  \geq     -6  \\
x^2  - 5x   +  6  \geq   0   \\
(x -  6) (x +  1  ) \geq   0  \\
  \left\{
\begin{array}{l}
x -  6 =    0  \\
x +  1  =   0     \\

\end{array} \\
\implies
\left\{
\begin{array}{l}
x  =      6 \\  
x    =   -1    

\end{array}
\right.
\right.
\end{array}$$

```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-4,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (6,-1.5) -- (6,1.5);
    \draw[dashed] (-1,-1.5) -- (-1,1.5);
    
    % Text annotations
    \node at (7,1.8) {$x = 7$};
    \node at (7,1.2) {$(1)(8) >   0$};
    
    \node at (1,1.2) {$x = 1$};
    \node at (1,0.6) {$(-5)(2) < 0$};
    
    \node at (-2,1.8) {$x = -2$};
    \node at (-2,1.2) {$(-8)(-1) > 0$};
    
\end{tikzpicture}
\end{document}


```

the inequality and  interval  notation  for the solution to this inequality  are    $[-1 ,  6]$

$$\begin{array}{l}
x^4+4x^3−12x^2 ≤0 \\
x^2  (x^2  +  4x  -  12   ) ≤0  \\
x^2(x  +   6) ( x    - 2   )  ≤0 \\

  \left\{
\begin{array}{l}
x +   6 =    0  \\
x^2   =   0     \\
x  -  2   =   0     \\
\end{array} \\
\implies
\left\{
\begin{array}{l}
x   =   -  6   \\
x   =   0     \\
x    =   2      \\
\end{array}
\right.
\right.
\end{array}$$


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-8,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-8,-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-6,-1.5) -- (-6,1.5);
    \draw[dashed] (0,-1.5) -- (0,1.5);
    \draw[dashed] (2,-1.5) -- (2,1.5);
    % Text annotations
    \node at ( -7,1.8) {$x = -7$};
    \node at ( -7,1.2) {$-7^2(-7  +   6) ( -7   - 2   ) >   0$};
    
    \node at ( -4,1.8) {$x = -4$};
    \node at ( -4,1.2) {$-4^2(-4  +   6) ( -4   - 2   ) <   0$};
    
    \node at (1,1.2) {$x = 1$};
    \node at (1,0.6) {$1^2(1 +   6) (1   - 2   ) <   0$};
    
    \node at (4,1.8) {$x = 4$};
    \node at (4,1.2) {$4^2(4  +   6) (4  - 2   ) >   0$};
    
\end{tikzpicture}
\end{document}


```

the inequality and  interval  notation  for the solution to this inequality  are    $[-6 ,  2]$



$$\begin{array}{l}
( x  + 1)(x  - 3)^2 > 0 \\

  \left\{
\begin{array}{l}
(x    -3)^2   =    0  \\
x  +  1     =   0     \\
\end{array} \\
\implies
\left\{
\begin{array}{l}
x       =   3 \\
x      =   -1       \\
\end{array}
\right.
\right.
\end{array}$$


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw x-axis
    \draw[->] (-8,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-8,-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (3,-1.5) -- (3,1.5);
    \draw[dashed] (-1 ,-1.5) -- (-1,1.5);
    % Text annotations
    \node at ( 6,1.8) {$x = 4$};
    \node at ( 6,1.2) {$( 4 + 1)(4 - 3)^2 > 0 $};
    
    \node at ( 2,1.8) {$x = 2$};
    \node at ( 2,1.2) {$(  2 + 1)( 2  - 3)^2 > 0 $};
    
    \node at ( -4,1.8) {$x = -2$};
    \node at (-4,1.2) {$( -2  + 1)(-2  - 3)^2 < 0 $};
    
\end{tikzpicture}
\end{document}


```

so  unlike the pervious solution  we cannot  combine  the interval  notation  into  one   like the above  we need to split it into two since   x  = 3  is not a true  inequality  notation since  $( x  + 1)(x  - 3)^2 > 0$  

so the interval notation  for the above  is  $$
(-1  , 3  )  \cap (3,  +\infty )$$



##   polynomial  that does not factor  
$$\begin{array}{l}
3x^2  -   2x   - 11  > 0 \\
 x =  \frac{1\pm   \sqrt{ 34  }}{  3}   \\

  \left\{
\begin{array}{l}
x   =  \frac{1 - \sqrt{ 34  }}{  3}    \\
x   =  \frac{1 +    \sqrt{ 34  }}{  3}     \\
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
    \draw[->] (-8,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-8,-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (1.6,-1.5) -- (1.6,1.5);
    \draw[dashed] (-1.6 ,-1.5) -- (-1.6,1.5);
    % Text annotations
    \node at ( -3,1.8) {$x = -3$};
    \node at ( -3,1.2) {$3(-3)^2  -   2\cdot -3   - 11 >0$};
    
    \node at ( 0,1.8) {$x = 0$};
    \node at ( 0,1.2) {$3.0^2  -   2 . 0   - 11 <0$};
    
    \node at ( 3,1.8) {$x = 3$};
    \node at (3,1.2) {$3.3^2  -   2 . 3   - 11 >0$};
    
\end{tikzpicture}
\end{document}


```

so the interval notation  for the above  is  $$
(-\infty ,\frac{1 - \sqrt{ 34  }}{  3}   )  \cap (\frac{1 + \sqrt{ 34  }}{  3}   ,  +\infty )$$


# #Practice_Exercise  



$$\begin{array}{l }
u^2+4u≥21   \\
u^2+4u  - 21≥    0   \\
(u    +    7) ( u  -  3)  \\

  \left\{
\begin{array}{l}
x   = -7   \\
x   =  3     \\
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
    \draw[->] (-10,0) -- (7,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-10,-8,-7,-6,-5,-4,-3,-2,-1,0,1,2,3,4,5,6,7} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-7,-1.5) -- (-7,1.5);
    \draw[dashed] (3 ,-1.5) -- (3,1.5);
    % Text annotations
    \node at ( -10,1.8) {$x = -10$};
    \node at ( -10,1.2) {$-10^2+4\cdot -10  - 21 >   0 $};
    
    \node at ( 1,1.8) {$x = 1$};
    \node at ( 1,1.2) {$1^2+4 - 21 < 0   $};
    
    \node at ( 5,1.8) {$x = 5$};
    \node at (5,1.2) {$5^2+4\cdot 5  - 21 >  0 $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(-\infty ,-7   )  \cap (3 ,  +\infty )$$




$$\begin{array}{l }
x^2+8x+12<0   \\
(x +  6)(x   +  2  )<0   \\
  \left\{
\begin{array}{l}
x   = -6   \\
x   =  -2      \\
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
    \draw[->] (-10,0) -- (1,0) node[right] {};
    
    % Draw tick marks and labels
    \foreach \x in {-8,-7,-6,-5,-4,-3,-2,-1,0,1} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    
    % Vertical dashed lines at -2 and 5
    \draw[dashed] (-6,-1.5) -- (-6,1.5);
    \draw[dashed] (-2 ,-1.5) -- (-2,1.5);
    % Text annotations
    \node at ( -3,1.8) {$x = -3$};
    \node at ( -3,1.2) {$-10^2+4\cdot -10  - 21 >   0 $};
    
    \node at ( 1,1.8) {$x = 1$};
    \node at ( 1,1.2) {$1^2+4 - 21 < 0   $};
    
    \node at ( 5,1.8) {$x = 5$};
    \node at (5,1.2) {$5^2+4\cdot 5  - 21 >  0 $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(-\infty ,-7   )  \cap (3 ,  +\infty )$$
