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
\tikzset{every picture/.style={line width=0.75pt}} %set default line width to 0.75pt        

\begin{tikzpicture}[x=0.75pt,y=0.75pt,yscale=-0.5,xscale=0.5]
% Plot a convex function on a x-y system
% Draw the x-axis
\draw  (0,300) -- (400,300);
% Draw the y-axis
\draw  (200,0) -- (200,400);
% Draw the function
\draw  [fill=cyan!40!white, draw opacity=1, fill opacity = 0.2][line width=1.1]  (50,50) .. controls (100,300) and (150,300)  .. (250,150) .. controls (300,150)  .. (350,50);
\draw (150,100) node   {$\mathrm{epi}(f)$};

% Draw a level sets
\draw [dashed] (90,200) -- (90,300);
\draw [dashed] (220,200) -- (220,300);
% Highligh the x-axis from 90 to 220 by drawing a rectangle around it
\draw [fill=red!40!white, line width=1.1, draw opacity=0, fill opacity=0.2] (90,300-10) rectangle (220,300+10);
% Put a curly brace to indicate the level set
\draw [decoration={brace,amplitude=10pt},decorate,xshift=0pt,yshift=0pt] (220,310) -- (90,310) node [black,midway,xshift=0pt,yshift=-20pt] {$\mathrm{level}(\alpha)$};

% ...
\end{tikzpicture}
\end{document}
```
