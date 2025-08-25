---
title: Adjunction
references: https://tutorial.math.lamar.edu/Classes/Alg/Lines.aspx
tags:
  - In_Progress
learning method: Vault + Read + Recall + Practice  (VRRP Method)
Current date: 2025-08-23
amount of time:
learning score:
---


# #definition 


Here are **10 key questions** you can ask an AI (or use for review) based on the main concepts from **Section 2.2: The Limit** from Paul’s Online Math Notes:

---

### 📘 **Topical Review Questions from Section 2.2: The Limit**

## **What is the intuitive (working) definition of a limit?**

### #human_explaination 
OK so the limit of the function FX we can denote at L as L L**** Apostolic A as X approach a hey Cortana provided we can make to the limit L as possible meaning it is there will be a sufficient number of exits our X that gets sufficiently close to a it basically all the exact packets constantly must satisfy a range of course not think of it like you like L Max satisfy that it must be 0.001 Weighing courses to a or like maybe 0.1 think of L at the the cusick approximation that we are allowed to consider back or exit will satisfy in order to create a limit and then it goes to like two points that we need to consider when talking about limit is that the value of X means to approach a from both the left and the right mean it need to be either larger than a or like smaller than A and the other thing that we need to consider it back it cannot be the value of a like we cannot plug a into the function itself but we need to select X or the value X that is the cost to A basically or the value X that also rounding in the range specified by the limit L


## **Why does the value of a function at a point not matter when computing the limit at that point?**
 
## **How do you estimate a limit using a table of values?**

## **What does it mean for a function to approach a value from both sides? Why is this important?**

## **When does a limit not exist?**

## **Why might estimating a limit from a table give the wrong answer?**

## **What does the graph of a function tell you about the limit?**
     
## **How can two functions have the same limit at a point even if one is undefined there?**
   
## **What are common mistakes students make when evaluating limits?**

## **What is the significance of one-sided limits in determining whether a two-sided limit exists?**



$$
\begin{array}{l} \\
\lim_{  x \to 2 } \frac{x^2 + 4x  - 12}{ x^2 - 2x  }   \\
\end{array}
$$


| x     | f(x)      |
| ----- | --------- |
| 1.9   | 4.157     |
| 1.99  | 4.01507   |
| 1.999 | 4.0015007 |
| 2.1   | 3.857     |
| 2.01  | 3.985     |
| 2.001 | 3.9985    |
we need to  note two thing :  
1. first the domain of the function does not accept x = 2  it will cause an undefine error if it does 
2. from the table we can see that the function is going to 4 as x approach 2  


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
    % Draw the parabola

   
      \draw[very thick, red, domain=2.1:4, smooth] plot(\x, {((\x)^2 + 4*\x - 12)/((\x)^2 - 2*\x)}); 
          \draw[very thick, red, domain=1:1.9, smooth] plot(\x, {((\x)^2 + 4*\x - 12)/((\x)^2 - 2*\x)});
\end{tikzpicture}
\end{document}


``` 

 Estimate the value of the following limit : 
 $$
\lim_{ x \to  2 }  g(x)  \text{ where }   ,  g(x)   =   \left\{ \begin{array}{l}  
\frac{x^2 + 4x   -12 }{x^2 -2x}  \text{ if } x\neq 2  \\
6  \text{ if } x = 2 \\
\end{array}  \right.
$$


| x     | g(x)      |
| ----- | --------- |
| 1.9   | 4.157     |
| 1.99  | 4.01507   |
| 1.999 | 4.0015007 |
| 2.1   | 3.857     |
| 2.01  | 3.985     |
| 2.001 | 3.9985    |
| 2     | 6         |




#fail 

$$
\begin{array}{l}  \\
g(x)  =  \lim_{ t \to 0 } \cos\left(  \frac{\pi}{t} \right)     \\
\end{array}
$$

| x      | g(x) |
| ------ | ---- |
| -0.1   | 1    |
| -0.01  | 1    |
| -0.001 | 1    |
| 0.1    | 1    |
| 0.01   | 1    |
| 0.001  | 1    |

if we guess the value of the limit is at 1 then we would be wrong consider these value : 

$$
f\left( \frac{1}{2001} \right)   = -1  
$$
$$
f\left( \frac{2}{2001} \right)    = 0   
$$
$$
f\left( \frac{4}{4001} \right)  =  \frac{\sqrt{ 2 }}{2}
$$




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
    % Draw the parabola

    \draw[thick,red,domain=0.1:3,samples=200]
    plot (\x,{cos( pi/\x r)});
    \draw[thick,red,domain=-3:-0.1,samples=200]
    plot (\x,{cos( pi/\x r)});
\end{tikzpicture}
\end{document}


``` 



as we can see in the graph the function oscillations increase in speed closer to T as we are getting 
this function does not setter in a single number so the limit does not exit 


$$
\lim_{  t \to 0 }  H(t)  where ,  H(t)   =   \left\{ \begin{array}{l}  
 0 \text{ if }  t <   0  \\
1 \text{ if } t \geq  0 
\end{array}   \right. 
$$


| x      | g(x) |
| ------ | ---- |
| -0.1   | 0    |
| -0.01  | 0    |
| -0.001 | 0    |
| 0.1    | 1    |
| 0.01   | 1    |
| 0.001  | 1    |

![[Pasted image 20250824130249.png]]




# #todo 
- [ ]  what does this sentence mean ? _There are many functions out there in the world that we can make as close to_ _L_ _for specific values of_ _x_ _that are close to_ _a__, but there will be other values of_ _x_ _closer to_ _a_ _that give functions values that are nowhere near close to_ _L_  
- [ ] why does 0.01  cause the graph to  result in 0  and if  it is other digit after the decimal point it is different ? 
- [ ] what make  L and a different is L just a way of saying the limit of the function getting closer and closer to basically the function is getting close to a, so why do we need to both make it closer to a and L. Or does it mean that the limit should exit in a close range, a range that we define to get us the best result of x satisfying L condition like this : 
 f(x) no more than 0.001 away from L. This means that we want one of the following

$f(x)−L<0.001$ if f(x) is larger than 
$L−f(x)<0.001$ if f(x) is smaller than L
where L is a the limit or value that we want the function to be closest to a 
L is the domain we put on x, to get the range of f(x) that satisfy L 



