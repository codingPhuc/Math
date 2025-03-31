




## #definition    

in this topic we are dealing with combining function . This mean to perform basic arithmetic (addition , subtraction , and division   ) . There is one new way of combing functions that we will look into 

let start with basic arithmetic of function . give the two function $f(x)$ and  $g(x)$ we have the following notation and operation 



Sometimes we will drop  (x) part and just write the following 

notice that if put x in the  parenthesis  we often put the number in as well 

$$
\begin{array}{l}
f(x)  = 2 + 3x - x^2    \\
g(x ) = 2x  - 1  
\end{array}
$$
1. $(f+g)(4)$
$$
\begin{array}{l}
(f+g)(4) \\
2+  3\cdot 4   -4^2   + 2\cdot 4  - 1   = 5 
\end{array}
$$


2. $g−f$
$$
\begin{array}{l}
(g-f )\\
2  +  3x   - x^2  - 2x   + 1   = -x^2 + x + 3 
\end{array}
$$
3. $(fg)(x)$
$$
\begin{array}{l}
(fg)(x)\\
(2 + 3x - x^2 )(2x  -  1)   =  4x   +  6x^2 - 2x^3  -  2 -3x+ x^2  = - 2x^3 + 7x^2 - 2  
\end{array}
$$
4. $\left( \frac{f}{g} \right)(0)$

$$
\begin{array}{l}
\left( \frac{f}{g} \right)(0)\\
\frac{2 + 3x - x^2 }{2x  - 1   }    = \frac{2 + 3\cdot 0  - 0^2 }{2\cdot 0  - 1   }  =-2 
\end{array}
$$

Now we need to discuss the new method of combining function . The new method is called **function composition** here is the definition 

give two function $f(x)$  $g(x)$ we have the following definition 
$$
\begin{array}{l}
(f \circ  g) (x)  = f[g(x)]  \\

\end{array}
$$
The **composition  of**  $f(x)$ and   $g(x)$   (again ,  the note the order ) is : 
$$
\begin{array}{l}
(g \circ f) (x) = g [f(x)] \\

\end{array}
$$

there are a few thing to note about function fusion . First this is **NOT** multiplication . Regales  of what the notation suggest  this is not multiplication 

Second,  the order we list the function  is very important , since it can be different depend on the order we listed them 

Finally , function  composition  is similar to function evaluation . We simply put the second function into the first function .  In the definition we used the `[]` instead of the normal `()` to avoid the confusion with different parenthesis , but the evaluation will work the same 

##  Give $f(x)  =2+3x  - x^2$ and $g(x) =2x - 1$ evaluate  each  of the following function 

1. (fg)(x)
$$
\begin{array} {l}
 (fg)(x)  = (2+3x  - x^2)(2x - 1)  \\
 4x   +  6x^2 - 2x^3  -  2 -3x+ x^2    \\
- 2x^3 + 7x^2 - 2  
\end{array} 
$$
2. (f∘g)(x)
$$
\begin{array} {l}
(f∘g)(x) = f[g(x) ] \\
 = (2+3(2x   -1 )  - (2x - 1)^2)  \\
= 2   + 6x   - 3  - (4x^2  - 4x   + 1 )  \\
=  2 + 6x - 3 -  4x^2 + 4x  - 1   \\
= -4x^2 + 10x -2 
\end{array} 
$$
3. (g∘f)(x) 
$$
\begin{array} {l}
(g∘f)(x)  = g [f(x)] \\
= 2(2 +  3x -  x^2 )  - 1  \\
 = 4 + 6x -  2x^2   - 1   \\
= -  2x^2 +  6x   + 3  
\end{array} 
$$

the idea from the pervious  example are important enough to make again . First  , function composite  is NOT  function multiplication . Second , the order in which we do function composition is important . In  most cases we will get different answer with diff order . However , there are also cases where we get the same result with diff order 
## Given $f(x) = x^2 - 3$ and $h(x) =\sqrt{ x+1 }$ evaluate each of the following 
1. (f∘h)(x)
$$
\begin{array} {l}
(f∘h)(x) = f[h(x )] \\
=  (\sqrt{   x + 1  })^2  -3 \\
 = x  + 1  - 3  \\
= x   -  2   
\end{array} 
$$
2. (h∘f)(x)
$$
\begin{array} {l}
(h \circ f )(x) = h[f(x )] \\
=  \sqrt{   x^2  - 3 }\\ 
\end{array} 
$$

3. (f∘f)(x)
$$
\begin{array} {l}
(f∘f)(x) = f[f (x)]\\
= (x^2   - 3  )^2 - 3\\   \\
 = x^4  - 6x^2   + 9 
\end{array} 
$$

4. (h∘h)(8)
$$
\begin{array} {l}
(h∘h)(8)  = h [h(8)]\\
= \sqrt{ \sqrt{ 8 + 1 } + 1 } \\
  = 2
\end{array} 
$$
5. (f∘h)(4) 
$$
\begin{array} {l}
(f∘h)(4)   = f[h(4)]\\
= x   -  2     \\
 =  4 - 2 =  2 
\end{array} 
$$

##  Given  $f(x)  =  3x   - 2$  and $g(x) =\frac{x}{3} + \frac{2}{3}$ evaluate each of the following 

1. (f∘h)(x)
$$
\begin{array} {l}
(f∘g)(x)    =  f[g(x )]  \\
3\left( \frac{x}{3} +  \frac{2}{3} \right)   - 2    \\
x  + 2   -  2  =   x     
\end{array} 
$$

  
(g∘f)(x) 


$$
\begin{array} {l}
(g∘f)(x)      =  g[f(x )]  \\
\frac{3x   - 2}{3}  + \frac{2}{3}  \\
x   
\end{array} 
$$
so this is our  answer it is possible to get the same solution on both  occasion


# #Practice_Exercise  

Given  $h(z)=7z+6$ and $f(z)=4−z$ compute each of the following 
1. (fh)(z)
$$
\begin{array} {l}
(fh)(z)  \\
(7z  + 6 ) (4-  z )   \\
= 14z -  7z^2 +  24 -  6z   \\
 =  -  7z^2 + 22z  + 24 
\end{array} 
$$

2.  (f∘h)(z)
$$
\begin{array} {l}
(h∘f)(z) =h[f(z)]    \\
7(4-z) +  6   \\
28  - 7z  +  6  \\
-7z + 34  
\end{array} 
$$
3.  (h∘f)(z)
$$
\begin{array} {l}
(f∘h)(z) =f[h(z)]  \\
4-  (7z + 6)  \\
4 -  7z  -  6  \\
= - 7z - 2 
\end{array} 
$$
4.  (h∘h)(z) 

$$
\begin{array} {l}
(h∘)h(z) =h[h(z)]  \\
7(7x + 6) + 6    \\
49x  +  42  +  6  \\
49x +   48 \\
\end{array} 
$$


 Given $P(t)=4t^2+3t−1$ and $A(t)=2−t^2$compute each of the following. 
1. (P+A)(t) 
$$
\begin{array} {l}
(P+A)(t)    \\
  4t^2 +  3t  - 1   + 2  -  t^2  \\
3t^2   +  3t + 1 \\
\end{array} 
$$

2.  A−P
$$
\begin{array} {l}
(P+A)(t)    \\
  4t^2 +  3t  - 1 -  2  +  t^2  \\
5t^2  + 3t  - 3  
\end{array} 
$$
3.  (PA)(t)
$$
\begin{array} {l}  \\
(4t^2+3t−1)(2−t^2 )  \\
8t^2+6t−2  -  4t^4 - 3t^3 + t^2   \\
  -  4t^4 - 3t^3  +  9t^2 +6t−2 
\end{array} 
$$
2.  $\left( \frac{P}{A} \right)(−2)$ 
$$
\begin{array} {l}  \\
\frac{4t^2+3t−1}{(2−t^2 ) }  \\
 \frac{4( - 2)^2+3(-2)−1}{(2−(-2)^2 ) }  \\
 \frac{-9}{(2}\\
\end{array} 
$$
Given $f(x)=6x^2$ and $g(x)=x^2+3x−1$compute each of the following. 
3. (gf)(x)
$$
\begin{array} {l}
(gf)(x) \\
6x^2 (x^2    + 3x   -1 )  \\
= 6x^4  +  18x^3  - 6x^2    \\
\end{array} 
$$
4.  (f∘g)(x
$$
\begin{array} {l}
(f∘g)(x) =f[g(z)]    \\
6(x^2+3x−1)^2  \\
= 6(x^2+3x−1)(x^2+3x−1) \\
 = (6x^2  + 18x  - 6) (x^2+3x−1)   \\
 =  6x^4   + 18x^3 -  6x^2 +  18x^3 + 54x^2 -  18x   -  6x^2 - 18x + 6  \\
= 6x^4  + 36x^3 -42x^2 +36x  +  6 
\end{array} 
$$
5.  (g∘f)(x)
$$
\begin{array} {l}
(g∘f)(x)   =   g[f(x)]\\
(6x^2)^2  +  3(6x) -  1   \\
= 36x^4  +  18x -  1  
\end{array} 
$$
6.  (f∘f)(x) 
$$
\begin{array} {l}
(f∘f)(x)   =   g[f(x)]\\
6(6x^2)^2 \\
= 216x^4 
\end{array} 
$$Given $R(t)=√t−2$ and $A(t)=(t+2)^2$, t≥0t≥0 compute each of the following 
7. (R∘A)(t)
$$
\begin{array} {l}
(R∘A)(t)  =   R[A(t)]\\
\sqrt{ (t   + 2)^2   -2  }  \\
\sqrt{t^2    -2  } 
\end{array} 
$$
8.  (A∘R)(t) 
$$
\begin{array} {l}
(A∘R)(t)  =   A[R(x)]\\
(\sqrt{ t  } - 2  +2)^2 \\
t \\
\end{array} 
$$