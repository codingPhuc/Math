

# #Definition  of Relation 
A **relation**  is  a set of order pairs 

This seem  like an odd definition ,  but we  need it for the definition  of a function( which is the main  topic of this section) .However, before the definition of a function  let see what a relationship actually is  
think  back to [[Section 3.1 Graphing#Practice_Exercise]] . In the  example we constructed a set of order  pairs to sketch the  graph of $y =(x - 1)^2 - 4$ 
$$
(−2,5)(−1,0)(0,−3)(1,−4)(2,−3)(3,0)(4,5) 
$$ here are the relation  that will form from the set of order pairs 

$$
\begin{aligned}&\{(-2,5)\quad(-1,0)\quad(2,-3)\}\\&\{(-1,0)\quad(0,-3)\quad(2,-3)\quad(3,0)\quad(4,5)\}\\&\{(3,0)\quad(4,5)\}\\&\{(-2,5)\quad(-1,0)\quad(0,-3)\quad(1,-4)\quad(2,-3)\quad(3,0)\quad(4,5)\}\end{aligned}
$$

There are of course many  relation  we could form from the list of order pairs  above , we just want to list a few possible relations to give some example .Note as well that we could get  any order pairs  from the relation and add those into the equation as well 

Why do  we need to used  relation ?  Because some relation  are special and are used in all level of math 

## Definition of a function 
A **function**  is a value , in which each value  from the  first  set of the order pairs is  associated with   exactly one value from the set of second components of the ordered pairs 
example 1  the  following relation is  function 
$$
\{(−1,0)(0,−3)(2,−3)(3,0)(4,5)\}
$$ from the list of  order pairs above we have the following set of first component (the first number of the order pairs) and second component( the second value in the order pairs) 
$$
\text{1st component } : \{-1,0 , 2 ,3, 4\} \; \text{2nd component } : \{0,−3,0,5\} 
$$
notice how the second component have only 1 -3 in  two ordered pairs but we only listed one 
To  see why this is  a relation ,  select a  value from the first component , then plug the value in the order pairs  and list out all  it second components  . The list of  second  component will consist  of  exactly one value 

For example , let look at 2  in the first component . Find a pairs  in the relation that have 2 as the first component , then plug 2 in  . You will see that we will get -3  in the second components 

Note that -3 occur 2 time in the relation, that is perfectly fine  since 3 is a values in the second component . We only need there to be unique  value of the 1 components 

we look  only at one value from the first example . But , it will be the same regardless of other choices 

Example 2  The following relation is  not a function 
$$
\{(6,10)(−7,3)(0,4)(6,−4)\}
$$
Here is the list of second and first components  : 
$$
\text{1st component } : \{6,0,-7\} \; \text{2nd component } : \{10 ,  3 , 4 ,-4 \} 
$$
from the first component let's choose 6.  Now , when  plugging  6 into the relation we will see that 6  have 2 orders pairs (6,10) (6.-4) . The list of second component  associated with 6 is then : 10 , -4  resulting in this being an invalid function since there is 2 second components associated with 6 

even thought there are values like -7 and 0  that have a single pairs does not matter. The function will be invalid if there is  even 1 first component with more then 2 second component associated with it 

##  another definition of a function  
Now let give a working definition of a function to what we are working with. However with the four relations we gave prior to the definition of a function and the relation we used in example 1 we often get the relation from some equation 

it is important to  note that not all relations come form equations .  The relations from the second equation for example was just an order pairs that we wrote down ,  didn't come from any equation . This can also be true for relation that are functions   

However the function that we are using will all come from equation  , they are call the "working" definition of a function . Remember the term working meaning this is a specific type of function we are working with not the general definition like above

## "working definition" of a function 
A **function** , in which  values of x that can be plugged in to get a single value of y  out of the equation 

Before we move on , let examine the parse "that can be plugged into"  . This is  in fact correct since there are values of x that collide  with the constraint of an equation . For example , you cannot divided  by 0 and  you must not square the root of negative number  if you want to get a real number. 

for  the example going forward , we will not deal  with complex number and always going to assume that x and y are real number 
## Determine which of the following are functions and which are not functions 

$$
\begin{array}{l}
x   = -4  , y = 5x + 1  \implies y = 5 \cdot -4  + 1   =  -19  \\
x   = 0 , y = 5x + 1  \implies y = 5 \cdot 0  + 1   = 1   \\
x   = 1 , y = 5x + 1  \implies y = 5 \cdot 1  + 1   = 6 \\
 
\end{array}
$$
bases on the equation  , and number we plug in . We concluded that this is an equation since : 
1. when we plug in one value the value will be multiply by 5 and add by 1 
2. since the output of the equation will always be 1 value is satisfy the constrains of  a function that a plug in values x can yield a values y  
this is a function since you can  plug in  values of x to  get a value of  y 



$$
\begin{array}{l}
x   = -2  , y = x^2  + 1   \implies y =  (-2)^2  +  1    =  5  \\
x   = 0   , y = x^2  + 1   \implies y =  0^2  +1    =   1   \\
x   = 2   , y = x^2  + 1   \implies y =  2^2   + 1   =  5 \\
 
\end{array}
$$
bases on the equation  , and number we plug in . We concluded that this is an equation since : 
1. when we plug in one  x value will be raise to the  power of 2  and added by 1 
2. since the output of the equation will always be 1 value is satisfy the constrains of  a function that a plug in values x can yield a values y  
this is a function since you can  plug in  values of x to  get a value of  y ,  


$$
\begin{array}{l}
x   = -2  , y^2   =  x+ 1  \implies  y = \sqrt{ x+ 1 }   \implies y = \sqrt{ -2 + 1 } = \sqrt{ -1  }  \\
x   = 0   ,  y^2   =  x+ 1  \implies y   = \sqrt{ x+ 1 }     \implies  y = \sqrt{ 0+ 1 }   \\
x   = 2   ,  y^2   =  x+ 1  \implies  y  =  \sqrt{ x+ 1 }    \implies  y = \sqrt{ 2 + 1 } = \pm  \sqrt{ 3 } \\
 
\end{array}
$$ we concluded bases on this equation that  this is not a function since when plug in the value   -2 , it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 



$$
\begin{array}{l}
x   = -2  , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   (x)^2  }   \\
\implies  y =  \sqrt{ 4  -   (3)^2  }   =\sqrt{ -5 }   \\
x   = 0 , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   x^2  }   \\
\implies y =  \sqrt{ 4  -   (0)^2  }     = \pm 4  \\
x   = 2  , x^2 +   y^2   = 4  \\
  y^2   = 4  -   x^2  \\
 y =  \sqrt{ 4  -   x^2  }   \\
\implies y =  \sqrt{ 4  -   (2)^2  }      = 0 \\
 
\end{array}
$$ we concluded bases on this equation that  this is not a function since when plug in the value   9, it create a square root properties and there are no complex number  that are outputted from a function 
additionally  , there should not be two solution for y since that mean that there is a  value of x that can produce values of y contradicting the constraints of what make a function 


We now need to move on to something call the **function  notation** .  Function notation will be use though out most of the equation in this chapter 
let start of  with the following quadratic equation : 
$$
 y   = x^2   - 5x  + 3  
$$

we can used the process similar to what we used in the pervious example to convince our self that this is a function . Since this is a function we denote it as the following 

$$
 f(x) =  x^2  - 5x  +  3 
$$
