

# limit laws 
suppose 
$$
\lim_{ x \to 7 } f(x)   = 30  \cap \lim_{ n \to 7 }g(x) = 2  
$$
1. one sided limit on the left and on the right are not equal  
```tikz
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
```


2. vertical asymptotes
```tikz
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

```


3. wild behavior 

what is the $$
\lim_{ x \to 7 }    
$$
by plugging  in number for this  function we are using limit law 

suppose that c is a constant and the limt $\lim_{ x \to a }f(x)$  
here are the law n limit 
$$
\lim_{ n \to a }[f(x) + g(x )]   = \lim_{ n \to a }f(x)   +   \lim_{ n \to a }g(x)   
$$
$$
\lim_{ n \to a }[f(x) - g(x )]   = \lim_{ n \to a }f(x)   -   \lim_{ n \to a }g(x)   
$$
$$
\lim_{ n \to a }[cf(x)]   = c 
$$
$$
\lim_{ n \to a }[f(x) + g(x )]   = 
$$
$$
\lim_{ n \to a }[f(x) + g(x )]   = 
$$

find the vertical asymptotes and horizontal asymptotes and holes 
horizontal asymptotes  :  

$$
\begin{array}{l} \\
q(x)  =  \frac{3x^2 + 3x} {2x^3 + 5x^2   - 3x } \\
 =  \frac{x^2}{ x^3}  = \frac{1}{x} \xrightarrow{\text{}}0 
\end{array}

$$


vertical asymptotes : 
$$
\begin{array}{l} \\
q(x)  =  \frac{3x^2 + 3x} {2x^3 + 5x^2   - 3x } \\
 =  \frac{3x(x + 1)}{x(2x^2 + 5x  - 3)}  = \frac{3(x + 1)}{(2x-1)(x + 3)} 
\end{array}
$$
$x=\frac{1}{2}\cap-3$ 


hole  : 
$$
 \frac{3(x + 1)}{(2x-1)(x + 3)}    = \frac{3(0 + 1)}{(2\cdot0-1)(0 + 3) }  = \frac{3}{-3}   = -1 
$$

(0,-1 )
hole by denominator and nominator are both 0 meaning there x is   0 


  
