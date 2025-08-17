---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/CalcI/ExpFunctions.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-17
amount of time: 
learning score:
---

# #definition 

## **Question 1:** According to the sources, what is the general form of an exponential function, and what are the restrictions on the base (b)? 

That's a very good and comprehensive answer! You've accurately identified all the restrictions on the base (b) and, more importantly, you've clearly explained _why_ those restrictions are in place, demonstrating a strong understanding of the underlying concepts.

**Your Answer Breakdown:**

- You correctly stated that the base **should not be equal to zero or one**.
- You correctly stated that the base **should be greater than zero** ((b > 0)).
- You provided the correct reasoning for avoiding (b=0) and (b=1): they would both result in a **constant function**.
- You also correctly explained why negative values for (b) are avoided: they can lead to **complex numbers** for certain exponents, which is undesirable for the type of functions studied in this context. For example, as the source shows, ({\left( { - 4} \right)^{\frac{1}{2}}} = \sqrt { - 4} = 2i).

The only thing missing from your answer was the explicit general form of the exponential function itself, which is (f\left( x \right) = {b^x}). However, given the depth of your explanation regarding the restrictions and their rationale, you've clearly grasped the core idea.

**Rating:** 9/10

**Correct Answer Review:** The general form of an exponential function is (f\left( x \right) = {b^x}). The restrictions on the base (b) are:

- **(b > 0)**.
- **(b \ne 1)**.

These restrictions are in place because:

- If (b = 1), the function becomes (f\left( x \right) = 1^x = 1), which is a **constant function**, not an exponential function.
- If (b = 0), it also results in a **constant function** (for (x > 0)).
- If (b < 0) (negative values), for certain fractional exponents, the function would result in **complex numbers** (e.g., ({\left( { - 4} \right)^{\frac{1}{2}}} = \sqrt { - 4} = 2i)), which is avoided in the definition of an exponential function to ensure real number outputs.

Great job on this first question!

Let's move on to the next one.

## **Question 2:** Based on the properties discussed in the sources, what is the range of an exponential function (f\left( x \right) = {b^x})?








## _look at a couple of exponential functions._  
sketch the graph of$f(x) =2^x$ and $g(x)=\left( \frac{1}{2} \right)^x$ 


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
 \node[blue] at (-3, 1) {$f(x) = 2^x$};
    \node[red] at (3, 1) {$f(x) = \left(\frac{1}{2}\right)^x = 2^{-x}$};
    % Draw the parabola
    \draw[thick, blue, domain=-2:2, smooth] plot (\x, {2^(\x)})  ;
    \draw[thick, red, domain=-2:4, smooth] plot (\x, {(1/2)^(\x)}) ;
\end{tikzpicture}
\end{document}


``` 


sketch the graph of $h(t)=1- 5e^{1- \frac{t}{2}}$


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

    \node[red] at (3, 1) {$h(t)=1- 5e^{1- \frac{t}{2}}$};
    % Draw the parabola

    \draw[thick, red, domain=0:4, smooth] plot (\x, {1 -  5 *e^(1-(\x)/2)}) ;
\end{tikzpicture}
\end{document}


``` 
