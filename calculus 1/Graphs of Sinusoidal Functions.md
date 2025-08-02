---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: "2025-07-31"
amount of time: 
learning score:
---

graph the function $y=3\sin(2x)$  with the attribute  
- astray by  3  
- compress  horizontally by  1/2  



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

    % Right branch
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {3* sin((2* \x) r)});



\end{tikzpicture}
\end{document}

```
if then the graph change by adding one like  
$$
3 \sin2x + 1  
$$
then the graph have an uptick by 1 unit 


|                   | <br><br><br><br>midline | amplitude | period                      |
| ----------------- | ----------------------- | --------- | --------------------------- |
| $y=\sin(x)$       | 0                       | 1         | $2\pi$                      |
| $y=3 \sin 2x$     | 0                       | 3         | $\frac{1}{2}\cdot 2\pi=\pi$ |
| $y = 3 \sin 2 +1$ | 1                       | 3         | $\pi$                       |

example graph the function  y =  3 $3 \sin\left( 2 \left( x - \frac{\pi}{4} \right) \right)$ 
we know that the graph of $3 \sin2x$ is 
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

    % Right branch
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {3* sin((2* \x) r)});



\end{tikzpicture}
\end{document}

```
so the graph of the function  $3 \sin\left( 2 \left( x - \frac{\pi}{4} \right) \right)$  will look like this 

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

    % Right branch
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {3* sin((2* (\x  - 3.14/4)) r)});



\end{tikzpicture}
\end{document}

```
since  
$g(x) =f\left( x-\frac{\pi}{4} \right)$ shifted to the right by $\frac{\pi}{4}$

graph the function 
$$
 y = 3 \sin\left(  2  \left( x - \frac{\pi}{4} \right) \right)  -1  
$$
have a horizontal shifted  by -1  so the attribute of the graph is 
midline being  y = 0   
amplify  by 1  
period $2\pi$ 



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

    % Right branch
  \draw[thick, red, domain=-6.28:6.28, smooth, samples=100]  node[ above] {sin} plot (\x, {3* sin((2* (\x  - 3.14/4)) r) -1});



\end{tikzpicture}
\end{document}

```
## general definition  
for the graph of   $y=A\cos(Bx  - C) +D$ and  $y=A\sin(Bx-C)+D$  with B positive  
we have the midline as : 
$y=D$
amplitude 
$\mid A \mid$
period : 
$\frac{1}{B} \cdot 2\pi=\frac{2\pi}{B}$
horizontal shifted : 
$$
\frac{C}{B}
$$
- to the right if $\frac{C}{B}$ is positive 
- to the left if $\frac{C}{B}$ is negative 

