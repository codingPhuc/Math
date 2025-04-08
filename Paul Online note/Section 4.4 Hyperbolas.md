---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Hyperbolas.aspx
tags:
  - In_Progress
reference: 
Current date: 2025-04-08
---

the next graph we need to look at is the  hybebola . 

![[Pasted image 20250408074105.png]]

![[Pasted image 20250408074110.png]]


Hyperbolas consist of two vaguely parabola shape pieces that open either up and down or left and right. just like a parabola each pieces have it own vertex . Note that these are not parabolas they just resemble them . 

There are also two line on each graph. These line are called asymptotes as the graph show as we make x large (in both the positive and negative sense) the graph of the hyperbolas get closer and closer to the asymptotes .However they are included to make sure we get the sketch correct . The point where the two asymptotes cross is called the hyperbola 

There are two standard form of the hyperbola , one for each directional type shown above 


| Property                    | Horizontal Hyperbola                              | Vertical Hyperbola                                |
| --------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| **Standard Form**           | $$\frac{(x-h)^2}{a^2} - \frac{(y-k)^2}{b^2} = 1$$ | $$\frac{(y-k)^2}{b^2} - \frac{(x-h)^2}{a^2} = 1$$ |
| **Center**                  | $$(h, k)$$                                        | $$(h, k)$$                                        |
| **Opens**                   | Left and right                                    | Up and down                                       |
| **Vertices**                | $$(h+a, k), (h-a, k)$$                            | $$(h, k+b), (h, k-b)$$                            |
| **Slope of Asymptotes**     | $$\pm \frac{b}{a}$$                               | $$\pm \frac{b}{a}$$                               |
| **Equations of Asymptotes** | $$y = k \pm \frac{b}{a}(x - h)$$                  | $$y = k \pm \frac{b}{a}(x - h)$$                  |

Note that the different between the two term is which form have the minus sign . if the y term have the minus sign then the hyperbola will open right and left, if the x term have the minus sign then the hyperbolas will open up and down 

we got the equation of the asymptotes by using the point slopes form of the line and the fact that we know the asymptotes will got through the center of the lines 

##  Sketch the graphs of each of the following hyperbolas 


$$

\frac{(x - 3)^2}{25}  -  \frac{(y + 1 )^2}{49 }  = 1 
$$
the x coordinate  : 

$$
\begin{array}{l} \\
\frac{(x - 3)^2}{25}  -  \frac{(y + 1 )^2}{49 }  = 1   \\
\frac{(x - 3)^2}{25}  =   1 + \frac{(y + 1 )^2}{49 }  \\
(x - 3)^2    =\frac{5}{7}\sqrt{ 49  + (y + 1 )^2 } \\
x    =   3   \mp \frac{5}{7}\sqrt{ 49  + (y + 1 )^2 }  
\end{array}
$$



| Property                    | Horizontal Hyperbola                                      |
| --------------------------- | --------------------------------------------------------- |
| **Standard Form**           | $$\frac{(x - 3)^2}{25}  -  \frac{(y + 1 )^2}{49 }  = 1 $$ |
| **Center**                  | $$(3,-1 )$$                                               |
| **Opens**                   | Left and right                                            |
| **Vertices**                | $$(8, 7), (2, 7)$$                                        |
| **Slope of Asymptotes**     | $$\pm \frac{7}{5}$$                                       |
| **Equations of Asymptotes** | $$y = -1 \pm \frac{7}{5}(x - 3)$$                         |


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola
        \draw[thick, blue, domain=-5:5, samples=200, smooth] 
        plot ({3 - (5/7)* sqrt(49 + (\x  + 1 )^2 )} , \x );
        \draw[thick, blue, domain=-5:5, samples=200, smooth] 
        plot ({3 + (5/7)* sqrt(49 + (\x  + 1 )^2 )} , \x );


    % Right branch
       \draw[dashed, red, domain=-6:6] plot (\x, { -1 - (7/5)*(\x - 3) });
        \draw[dashed, red, domain=-6:6] plot (\x, { -1 + (7/5)*(\x - 3) });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```





$$

\frac{y^2}{9}  - (x  + 2)^2   = 1 
$$
$$

\frac{y^2}{9}  - (x  + 2)^2   = 1 
$$

the y coordinate  : 
$$
\begin{array}{l} \\
\frac{y^2}{9}  - (x  + 2)^2   = 1   \\
\frac{y^2}{9}   = 1  +  (x  + 2)^2   \\
y^2  = 9  + 9(x + 2)^2  \\
y = 3\sqrt{ 1 + (x + 2)^2   } 
\end{array}
$$






| Property                    | Vertical Hyperbola                     |
| --------------------------- | -------------------------------------- |
| **Standard Form**           | $$\frac{y^2}{9}  - (x  + 2)^2   = 1 $$ |
| **Center**                  | $$(-2,  0 )$$                          |
| **Opens**                   | Up and down                            |
| **Vertices**                | $$( -2,1), (-2, -1 )$$                 |
| **Slope of Asymptotes**     | $$\pm \frac{3}{1}$$                    |
| **Equations of Asymptotes** | $$y = \pm 3(x + 2)$$                   |


```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }

    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola 

%%    \draw[thick, blue, domain=-2:3, samples=200, smooth] plot (\x, {3*sqrt(  (( \x^2 - 4)/9 )   ) }); %%  % Right branch of the hyperbola

    %% \draw[thick, blue, domain=-2:3, samples=200, smooth]  plot (\x, {-3*sqrt(   (( \x^2 - 4)/9 )   });  %% % Left branch of the hyperbola

        \draw[thick, blue, domain=-3:-1, samples=200, smooth] 
        plot ( \x  , {3* sqrt(1 + (\x+ 2)^2)});
        \draw[thick, blue, domain=-3:-1, samples=200, smooth] 
        plot ( \x  , {-3* sqrt(1 + (\x+ 2)^2)});
    % Right branch
       \draw[dashed, red, domain=-6:6] plot (\x, {3*(\x + 2 ) });
        \draw[dashed, red, domain=-6:6] plot (\x, {(-3)*(\x + 2 )  });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```















$$

\frac{y^2}{16} -\frac{(x  -2 )^2}{9}  = 1  
$$


the y coordinate  : 
$$
\begin{array}{l} \\
\frac{y^2}{16} -\frac{(x  -2 )^2}{9}  = 1     \\
 \frac{y^2}{16} =   1 + \frac{(x  -2 )^2}{9}   \\
y  = \frac{4}{3}\sqrt{  9 +(x  -2 )^2  }   
\end{array}
$$


| Property                    | Vertical Hyperbola                              |
| --------------------------- | ----------------------------------------------- |
| **Standard Form**           | $$\frac{y^2}{16} -\frac{(x  -2 )^2}{9}  = 1  $$ |
| **Center**                  | $$(2, 0 )$$                                     |
| **Opens**                   | Up and down                                     |
| **Vertices**                | $$(2 , 4), (2, -4)$$                            |
| **Slope of Asymptotes**     | $$\pm \frac{4}{3}$$                             |
| **Equations of Asymptotes** | $$y =  \pm \frac{4}{3}(x - 2)$$                 |




```tikz
\usepackage{amsmath,amssymb}
\usetikzlibrary{decorations.pathreplacing}

\begin{document}
\tikzset{every picture/.style={line width=0.75pt}} % set default line width

\begin{tikzpicture}[x=1cm,y=1cm]
    % Draw axes
    \draw[->] (-7,0) -- (7,0) node[right] {$x$};
    \draw[->] (0,-7) -- (0,7) node[above] {$y$};

    % Tick marks and labels
    \foreach \x in {-6,-5,...,6} {
        \draw (\x,0.1) -- (\x,-0.1) node[below] {\x};
    }
    \foreach \y in {-6,-5,...,6} {
        \draw (0.1,\y) -- (-0.1,\y) node[left] {\y};
    }
y  = \frac{4}{3}( 9 +(x  -2 )^2   )
    % Parameters
    % Center: (h, k) = (0, 0)
    % a = 2, b = 3 → y = ±(3/2)*sqrt(x^2 - 4)
    % Horizontal hyperbola 

%%    \draw[thick, blue, domain=-2:3, samples=200, smooth] plot (\x, {3*sqrt(  (( \x^2 - 4)/9 )   ) }); %%  % Right branch of the hyperbola

    %% \draw[thick, blue, domain=-2:3, samples=200, smooth]  plot (\x, {-3*sqrt(   (( \x^2 - 4)/9 )   });  %% % Left branch of the hyperbola

      \draw[thick, blue, domain=-1:5, samples=200, smooth] 
      plot ( \x  , {(4/3)*sqrt(9 + (\x -2 )^2)}); 
        \draw[thick, blue, domain=-1:5, samples=200, smooth] 
        plot ( \x  , {-(4/3)*sqrt(9 + (\x -2 )^2)}) 
    % Right branch
       \draw[dashed, red, domain=-6:6] plot (\x, {(4/3)*(\x - 2 ) });
        \draw[dashed, red, domain=-6:6] plot (\x, {-(4/3)*(\x - 2 )  });

    % Asymptotes: y = ±(3/2)x
    % Center
    \filldraw[black] (0, 0) circle (2pt) node[below left] {$(0, 0)$};

\end{tikzpicture}
\end{document}

```




# #todo  

- [ ] read this [document on tikz](https://tikz.dev/tikz-plots) 
- [ ] why is it when y is minus the it move from left to right,  when x is minus it move from up to down 
- [ ] prove every single formula here 



| Property                    | Horizontal Hyperbola                              | Vertical Hyperbola                                |
| --------------------------- | ------------------------------------------------- | ------------------------------------------------- |
| **Standard Form**           | $$\frac{(x-h)^2}{a^2} - \frac{(y-k)^2}{b^2} = 1$$ | $$\frac{(y-k)^2}{b^2} - \frac{(x-h)^2}{a^2} = 1$$ |
| **Center**                  | $$(h, k)$$                                        | $$(h, k)$$                                        |
| **Opens**                   | Left and right                                    | Up and down                                       |
| **Vertices**                | $$(h+a, k), (h-a, k)$$                            | $$(h, k+b), (h, k-b)$$                            |
| **Slope of Asymptotes**     | $$\pm \frac{b}{a}$$                               | $$\pm \frac{b}{a}$$                               |
| **Equations of Asymptotes** | $$y = k \pm \frac{b}{a}(x - h)$$                  | $$y = k \pm \frac{b}{a}(x - h)$$                  |
