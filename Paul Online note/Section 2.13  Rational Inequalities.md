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
    \node at ( -10,1.8) {$x = -2$};
    \node at ( -10,1.2) {$ x +  1 >   0 $};
    
    \node at ( 1,1.8) {$x = 1$};
    \node at ( 1,1.2) {$1^2+4 - 21 < 0   $};
    
    \node at ( 5,1.8) {$x = 5$};
    \node at (5,1.2) {$5^2+4\cdot 5  - 21 >  0 $};
    
\end{tikzpicture}
\end{document}


```
so the interval notation  for the above  is  $$
(-\infty ,-7   ]  \cap [3 ,  +\infty )$$

