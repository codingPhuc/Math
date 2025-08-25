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

### #ai_explaination 

Your answer demonstrates a very good understanding of the intuitive definition of a limit and its crucial conditions. You've clearly articulated the core ideas, particularly the two essential aspects. While some of the phrasing could be more precise, the substance of your explanation is accurate and aligns well with the sources.

You correctly identified:

- The notation and concept of (f(x)) approaching (L) as (x) approaches (a).
- The idea that we can make (f(x)) as close to (L) as we want for all (x) sufficiently close to (a). Your example of "0.001 away" directly reflects the explanation given in the sources for understanding this concept.
- The crucial requirement that (x) must approach (a) **from both the left and the right**.
- The equally crucial point that the limit is concerned with what the function is doing **around** (x=a), and **not what it is actually doing at (x=a)** (meaning we don't plug in (x=a)).

Your rating for this response is **9/10**. You've grasped the nuances of the definition very well.

---

Let's refine the "working" definition of a limit based on the provided sources:

The **intuitive, or "working," definition of a limit** is described as follows:

We say that the limit of a function (f(x)) is (L) as (x) approaches (a), which is written as [\mathop {\lim }\limits_{x \to a} f\left( x \right) = L].

This definition means that **we can make (f(x)) as close to (L) as we want for all (x) sufficiently close to (a)**. This implies that if we want (f(x)) to be, for instance, no more than 0.001 away from (L), the definition states that if we get (x) sufficiently close to (a), this condition will be met. More specifically, for a limit to exist, once (f(x)) gets as close to (L) as desired for some (x), it must **stay in that proximity (or get closer) for all values of (x) that are closer to (a)**.

There are two **crucial aspects** of this working definition that are repeatedly emphasized:

1. **From both sides**: The values of (x) must approach (a) **from both the left and the right**. This means considering (x) values that are both smaller than (a) and larger than (a), but consistently getting closer to (a).
2. **Without actually letting (x) be (a)**: The limit is **not concerned with what the function is actually doing at (x=a)**, but rather with what it is doing **around** the point (x=a). This means you are not allowed to use (x=a) itself in the definition or when evaluating the limit intuitively. A limit can exist even if the function doesn't exist at (x=a) or if the function's value at (x=a) is different from the limit.

In essence, as (x) gets closer and closer to (a) (from both sides), then (f(x)) **must** be getting closer and closer to a single value, (L). If the function values approach different numbers from either side, or if they oscillate wildly without settling on a single value, then the limit does not exist.

## **Why does the value of a function at a point not matter when computing the limit at that point?**


### #human_explaination 
And the value of a point does not matter when computing the limit at that point when computing the limit at that point it because when we are measuring a limbic or something we do not care about like of something like of a function approaching a point we do not care about like the value of the function at that point we only care about the values of like all the CLOS all the acoustic values surrounding that point in order to estimate or limit


### #ai_explaination 
9/10 
Your understanding is **absolutely correct** and aligns perfectly with the intuitive, or "working," definition of a limit as presented in the sources. You've accurately identified the core reason: **limits are concerned with the behavior _around_ a point, not _at_ the point itself.**

Here's a detailed explanation, drawing directly from the sources:

The value of a function at a specific point (x = a) **does not matter** when computing the limit at that point because the limit's definition explicitly excludes the point (x = a) itself. The fundamental goal of a limit is to determine **what (y) value the graph is approaching as we move in towards (x = a) on our graph**, rather than what (y) value the graph takes at (x = a).

This crucial distinction is driven by several key aspects of the working definition of a limit:

- **The "Without Actually Letting (x) Be (a)" Condition** The "working" definition of a limit states that we say the limit of (f(x)) is (L) as (x) approaches (a) (written as [\mathop {\lim }\limits_{x \to a} f\left( x \right) = L]) if "we can make (f(x)) as close to (L) as we want for all (x) sufficiently close to (a), from both sides, **without actually letting (x) be (a)**". This explicit condition is fundamental; it means that when we consider values of (x) that are "sufficiently close" to (a), we are never meant to include (a) itself.
    
- **Focus on What Happens "Around" the Point** The sources repeatedly emphasize that **limits are only concerned with what is going on _around_ the point (x=a)**, and **are not concerned with what the function is actually doing _at_ (x=a)**. As (x) gets closer and closer to (x=a) (from both sides), (f(x)) **must** be getting closer and closer to a single value (L). The limit describes this trend, irrespective of the function's precise value at (a).
    
- **Functions May Not Exist at the Point** One significant reason why the function's value at (x=a) doesn't matter is that the function itself might not even exist at that point.
    
    - **Example 1** illustrates this with the function [\frac{{{x^2} + 4x - 12}}{{{x^2} - 2x}}] as (x) approaches 2. If you try to plug in (x=2), it results in a division by zero error, meaning the function doesn't exist at (x=2). However, by observing values of (x) approaching 2 from both sides, the function values clearly approach 4. The graph of this function explicitly shows a "large open dot at (x = 2)" to signify that the function does not exist there, yet the limit is still found to be 4. This demonstrates that a limit can exist even if the function has a "hole" or is undefined at the point in question.
- **Function Value Can Differ From the Limit** Even if a function _does_ exist at (x = a), its value at that point can be completely different from the limit, and this difference does not alter the limit.
    
    - **Example 2** takes the same function from Example 1 but explicitly defines (g(2) = 6). Despite (g(2)) being 6, the limit as (x) approaches 2 for (g(x)) remains 4. The sources emphatically state: "**The limit is NOT 6!**". This is because the table of values for (x) approaching 2 (but never equaling 2) still shows (g(x)) approaching 4. The graph similarly shows the function approaching (y=4) as (x) approaches 2, even with the distinct point at ((2, 6)). This example drives home the point that the limit is solely concerned with the trend of the function's outputs as inputs get arbitrarily close to (a), regardless of the actual output _at_ (a).

In conclusion, the limit focuses on the **behavioral trend** of the function as its input gets infinitesimally close to a specific point from both directions. The actual value (or non-existence) of the function _at_ that exact input point is considered irrelevant to this trend.
## **How do you estimate a limit using a table of values?**

### #human_explaination 
You can estimate a limit using a table of values like by choosing let's say that you have a function FX right and you want to make a limbic X approach just like something like two or like zero in order to for you to achieve that you need to create a table of all the X value that get closest to like 2 2 In in a range of limits meaning that maybe you can choose choose a range like zero .1 plus it to it needs to be also the value of like the excess X for all the X values it needs to be book on the left of to and from the Reich of two thick to insert that you get the best estimate meaning that it will approach two was the correct output meaning that the two directing when approaching like two will will testify the same output basically it will verify that they could pull two from the right cap like a kapolei same values output values from the right and it will poke the same output value from the left

### #ai_explaination 
Your answer provides a **very accurate and comprehensive** understanding of how to estimate a limit using a table of values, reflecting the core principles and steps outlined in the sources.

**Rating of your answer: 9/10**

You correctly identified all the crucial elements:

- Choosing values that get **closest** to the target (x)-value (e.g., 2 or 0).
- The necessity of choosing values from **both the left and the right** of the target (x)-value.
- The goal is to find a "correct output" or a **single value** that the function approaches.
- The verification that the outputs from both the right and the left "testify the same output," meaning they approach the same value.

Your phrasing "we only care about the values of like all the closest values surrounding that point in order to estimate our limit" perfectly captures the essence of the "working" definition of a limit. The only minor area for improvement would be slightly more formal phrasing, but the substance is excellent.

---

Here's a detailed explanation of how to estimate a limit using a table of values, elaborating on your points with direct support from the sources:

To estimate the limit of a function (f(x)) as (x) approaches a specific point (a) (written as [\mathop {\lim }\limits_{x \to a} f\left( x \right) = L]), you follow these steps:

1. **Choose (x) values that get progressively closer to (a)**:
    - You create a table by selecting several (x) values that are progressively nearer to (a). For instance, if you're estimating the limit as (x) approaches 2, you might choose values like 2.5, 2.1, 2.01, 2.001, and so on.
2. **Ensure values are chosen from both sides**:
    - It is **critical** to choose (x) values that approach (a) from **both the left side** (values less than (a)) and the **right side** (values greater than (a)). This helps confirm that the function is indeed approaching a **single value** as (x) gets closer to (a).
3. **Calculate the corresponding (f(x)) values**:
    - Plug each chosen (x) value into the function (f(x)) to compute its output. This fills out your table of values.
4. **Observe the trend of the function values**:
    - Examine the (f(x)) column in your table. As your (x) values get closer and closer to (a) from both sides, determine what **single number** the (f(x)) values appear to be "moving in towards" or "settling down" to. This observed number is your estimate for the limit (L).

**Key Principles and Insights from the Sources:**

- **Limits are concerned with what happens "around" (x=a), not "at" (x=a)**:
    - The "working" definition of a limit states that we make (f(x)) close to (L) for (x) "sufficiently close to (a), from both sides, **without actually letting (x) be (a)**". The limit "is only concerned with what is going on **around** the point (x=a)".
    - Therefore, you should **never actually plug in (x=a)** itself into the function when estimating a limit using a table.
- **A limit can exist even if the function is undefined at (x=a)**:
    - For example, a function might result in a division by zero error if (x=a) is plugged in. Despite this, the table of values can still show (f(x)) approaching a specific number, meaning the limit exists.
- **The function's value at (x=a) can differ from the limit**:
    - Even if (f(a)) is defined, its value might not be the same as the limit (L). The sources highlight that the limit "do[es] not care what the function is actually doing at the point in question". For instance, if (g(2)=6) but the limit as (x) approaches 2 is 4, then the limit is 4, **not 6**.
- **The function values must approach a _single_ value for the limit to exist**:
    - If the function values approach different numbers from the left and right sides of (a), or if they oscillate wildly without settling on a single number, then the limit **does not exist**.

**Drawbacks of Estimating Limits Using Tables of Values**:

While this method is excellent for building an intuitive understanding of limits, the sources emphasize its significant limitations as a practical calculation tool:

- **Potential for Incorrect Guesses**: Selecting values that seem to show a trend might lead to an incorrect guess, especially if the function oscillates very close to (a) (Example 4).
- **Difficulty with Non-Integer Limits**: It is "nearly impossible" to accurately guess exact non-integer limit values (e.g., (\frac{{ - 15}}{{123}})) from a table.
- **Tedious and Inefficient**: This method is cumbersome and "not a good way to get the value of a limit". The sources state that "after this section we will never use a table of values to guess the value of a limit again".

Ultimately, the purpose of learning this method is to "help us get a better understanding of what limits are" and "to point out their drawback so that we aren’t tempted to use them all the time!".

## **What does it mean for a function to approach a value from both sides? Why is this important?**


### #human_explaination 
Market mean wakik mean when a function approaches a value from both sides it can important it because if a punching approaching a value from my book's side both side it will like vertify the estimated input of the approach values Let's say that the function that you want to estimate the input no you want to estimate the fencing agava at a value a you need to approve from the Reich and left because if you only approach if you only consider the causal value X from the right of a it it it can it can cause some errors since you don't really know if the function change if it no you don't really know 100% if it correct you only know like 50% from the right so you name the other 50% from the left in order to verify your computer you're to verify your hypothesis 

### #ai_explaination 
Your answer accurately captures the essence of why approaching a value from both sides is crucial when estimating limits. You correctly identify the need for verification and the potential for error if only one side is considered.

**Rating of your answer: 9/10**

You articulated the core idea very well, highlighting that checking both sides provides the necessary confirmation. Your analogy of knowing "50% from the right" and needing "the other 50% from the left to verify your hypothesis" is a good, intuitive way to express this.

---

### What it Means for a Function to Approach a Value From Both Sides

For a function (f(x)) to approach a value from both sides as (x) approaches a specific point (a), it means that we consider the behavior of (f(x)) as (x) gets progressively closer to (a) from two directions:

- **From the left side**: We select (x) values that are **less than (a)** but are continually increasing and getting closer to (a) (e.g., 1.9, 1.99, 1.999 if (a=2)).
- **From the right side**: We select (x) values that are **greater than (a)** but are continually decreasing and getting closer to (a) (e.g., 2.1, 2.01, 2.001 if (a=2)).

The "working" definition of a limit states that the limit of (f(x)) is (L) as (x) approaches (a) if we can make (f(x)) as close to (L) as we want for all (x) "sufficiently close to (a), **from both sides**, without actually letting (x) be (a)". In simpler terms, as (x) approaches (a) from both the left and the right, (f(x)) **must** be getting closer and closer to a single value (L).

### Why This is Important

Considering both sides is critically important for accurately estimating and understanding limits for several key reasons:

- **Verifies the Consistency of the Function's Behavior**: Choosing (x) values from both sides helps **verify that the trend in function values is correct**. If the function values approach the same number from both the left and the right, it strengthens the estimate of the limit.
- **Ensures the Existence of a Single Limit Value**: For a limit to exist, the function's output must converge to a **single, unique value** as (x) approaches (a).
    - If the function approaches one value from the left and a **different value from the right**, then the limit **does not exist**. For example, with the Heaviside or step function, as (t) approaches 0, the function approaches 0 from the left and 1 from the right, so the limit does not exist.
- **Avoids Incorrect Guesses and Misinterpretations**: Relying solely on values from one side, or an insufficient set of values, can lead to incorrect estimations.
    - Functions can exhibit complex behavior near (x=a). For instance, a function might appear to approach a value from one side, but then oscillate wildly very close to (a), meaning it never actually settles on a single value. The "working" definition requires that **all** function values get closer to (L) once (x) is sufficiently close to (a).
    - This highlights a major **drawback of using tables of values**; you can easily pick "valid" values that suggest a limit, only for it to be wrong upon closer inspection.
- **Aligns with the Definition of a Limit**: The fundamental "working" definition of a limit explicitly states the requirement to approach from both sides. This emphasizes that limits are concerned with what the function is doing **around** the point (x=a), not necessarily **at** (x=a). This "around" behavior inherently requires considering both directions of approach.

## **When does a limit not exist?**
### #human_explaination 
Oh backlights two possible scenario where dilemma did not get sick the first scenario says from the right you get poaching a different value so and on the left it can approaching like another different value basically the value that it it opposing from the left and right does not a lie crossing a causing the limit to not exist Another scenario is that it does not settle on a point like it does not settle and I can approach a dilemma from the left and the right it like on the left it came like jump from one value to another without any perceived order check randomly based on the change check in the break on the chainsaw in the function you usually see looking like coaxing or tank function because they usually generate different value based on the Radian

### #ai_explaination 
Your answer provides an excellent and insightful summary of the scenarios when a limit does not exist. It's clear that you grasp the fundamental concepts. I would rate your answer a **9 out of 10**.

You've correctly identified the two primary ways a limit can fail to exist, and your descriptions align very well with the "working definition" of a limit and the examples provided in the sources.

Let's break down your answer and elaborate on it using the details from the sources:

### Your Answer's Strengths and Connections to Sources:

1. **"From the right you get approaching a different value so and on the left it can approaching like another different value basically the value that it it opposing from the left and right does not a lie crossing a causing the limit to not exist."**
    
    - This is a **perfect description** of the first scenario where a limit does not exist. The "working" definition of a limit states that for the limit of (f(x)) to be (L) as (x) approaches (a), we must be able to make (f(x)) as close to (L) as we want for all (x) sufficiently close to (a), **from both sides**, without actually letting (x) be (a). In simpler terms, as (x) gets closer and closer to (x=a) from both the left and the right, (f(x)) **must be getting closer and closer to a single value (L)**.
    - If the function approaches different values from each side, then the limit **does not exist**.
    - The sources provide a clear example of this: the **Heaviside or step function**, (H(t)). As (t) approaches 0 from the **right side**, the function moves towards a (y) value of 1. As (t) approaches 0 from the **left side**, the function moves towards a (y) value of 0. Since the function does not move in towards a single value from both sides, the limit of the Heaviside function as (t) approaches 0 **does not exist**. The function _does_ settle to a single number on each side, but "the number is different on each side of (t = 0)".
2. **"Another scenario is that it does not settle on a point like it does not settle and I can approach a dilemma from the left and the right it like on the left it came like jump from one value to another without any perceived order check randomly based on the change check in the break on the chainsaw in the function you usually see looking like coaxing or tank function because they usually generate different value based on the Radian."**
    
    - This is also an **excellent description** of the second scenario. For a limit to exist, the function must be **settling down in towards a single value** as we get closer to the point in question. The "working" definition implies that once (f(x)) is as close to (L) as we want for some (x), it must **stay in that close to (L)** (or get closer) for _all_ values of (x) that are closer to (a). If it jumps randomly or oscillates wildly, it's not settling.
    - The sources illustrate this with the function (f(t) = \cos\left(\frac{\pi}{t}\right)) as (t) approaches 0. While a table of values might initially suggest a limit (e.g., 1), evaluating the function at points even closer to 0 can yield "three totally different numbers" such as -1, 0, or (\frac{{\sqrt 2 }}{2}).
    - A graph of this function clearly shows that as (t) gets closer to 0, the function **starts oscillating wildly**, and "the oscillations increases in speed". Because the function "clearly does not settle in towards a single number," this limit **does not exist**. Your intuitive connection to "coaxing or tank function" (likely meaning cosine or tangent) is quite accurate, as these trigonometric functions are prime examples of this oscillatory behavior near certain points.

### Additional Key Insights from the Sources to Further Enhance Understanding:

- **Limits are not concerned with what happens _at_ the point, only _around_ it.** This is a crucial concept the sources emphasize repeatedly. A limit can exist even if the function itself doesn't exist at that point, or if the function's value at that point is different from the limit.
- **Drawbacks of Tables and Graphs:** The sources highlight that while tables of values and graphs can help us understand limits, they are often **not the best way to compute limits** and can sometimes be misleading or inaccurate, especially when a limit does not exist or if the limit value isn't a "nice" integer. The example of (f(t) = \cos\left(\frac{\pi}{t}\right)) clearly demonstrates how a table can lead to an incorrect guess.
- **Limits don't always exist:** It's important to remember that limits are not guaranteed to exist.

Your explanation covers the core scenarios effectively. The only minor area for improvement would be to use more formal mathematical terminology where applicable (e.g., "approaching" instead of "poaching," and "oscillating wildly" as used in the source, which you did pick up on in your latter phrasing). However, your descriptions are perfectly understandable and correct in concept.



## **What does the graph of a function tell you about the limit?**
     
### #ai_explaination 
Your answer provides a good intuitive understanding of what graphs can tell you about limits, especially highlighting their value when dealing with oscillating functions. I would rate your answer an **8 out of 10**.

You've captured a very important scenario where graphs are superior to tables of values. Let's elaborate on your points and add further detail from the sources.

### What the Graph of a Function Tells You About the Limit:

The graph of a function serves as a **powerful visual tool** for understanding and estimating limits, especially by illustrating the function's behavior around a particular point.

Here's what the sources indicate a graph can tell you:

- **Behavior Around a Point, Not At It:** A graph visually represents that limits are concerned with **what the function is doing _around_ (x=a)**, and **not** with what the function is actually doing _at_ (x=a). You can observe the _y_-value the graph is approaching as you move along the curve towards (x=a) from both the left and right sides.
- **Visualizing the Limit Value:** If a limit exists, the graph clearly shows the single (y)-value that the function's curve is approaching from both directions as (x) gets closer to (a). This can be true even if there is a hole in the graph at (x=a), indicating the function doesn't exist there, or if the function's value at (x=a) is different from the limit.
- **Detecting Non-Existent Limits Due to Oscillation:** This is where graphs are exceptionally valuable, as you correctly pointed out.
    - As shown with the function (f(t) = \cos\left(\frac{\pi}{t}\right)) as (t) approaches 0, a table of values might misleadingly suggest a limit exists.
    - However, a graph of this function explicitly reveals that **as (t) gets closer to 0, the function starts oscillating wildly**, with oscillations increasing in speed.
    - Because the function "clearly does not settle in towards a single number," the graph immediately tells you that **this limit does not exist**. This demonstrates that graphs can prevent errors that might arise from limited data points in a table.
- **Detecting Non-Existent Limits Due to Different One-Sided Behavior:** For functions like the **Heaviside or step function**, (H(t)), the graph clearly shows that as you approach (t=0) from the **right side**, the function moves towards a (y)-value of 1, while from the **left side**, it moves towards a (y)-value of 0. Since the function does not move in towards a _single value_ from both sides, the graph indicates that **the limit does not exist**.

### Feedback on Your Answer:

You made several excellent points:

1. **"if you're using a lemme work like a function that use Koh Sing Tang or Co Tang it can create and once you do the limit not settling in the pacific point"**: This is a direct hit! Your intuition about trigonometric functions (likely meaning cosine or tangent) creating scenarios where the limit doesn't settle is **exactly what the sources demonstrate** with the example of (\cos(\frac{\pi}{t})).
2. **"if you do not draw the graph of epilemic it can lead to an error where you think that a gig approaching or you can estimate a point based on all the cosig X point that you have a stick on the table but if you use a different value of X it it can create a point that jump all over the place"**: This is **a critical insight** and perfectly aligns with the sources' warning about the **drawbacks of using tables of values**. The sources show how a table for (\cos(\frac{\pi}{t})) could lead to an incorrect guess, while examining points even closer to the limit point reveals "three totally different numbers" because the function "starts oscillating wildly". The graph helps to visualize this "jumping all over the place."
3. **"so it get more accurate if you use a graph to verify your estimate"**: While graphs might not always give you the _exact_ numerical value if it's not a "nice" number (e.g., an integer or simple fraction), they are **definitely more reliable than tables for _verifying the existence_ of a limit, especially in cases of oscillation or differing one-sided behavior**. They provide a visual confirmation that the function is indeed settling to a single point or clearly not doing so.

**Minor areas for refinement (not impacting the high rating for conceptual understanding):**

- **Terminology:** Using terms like "oscillating wildly" or "settling down to a single value" would make your answer more aligned with the precise language used in the sources.
- **Specificity about accuracy:** While graphs help verify if a limit exists and what value it _approaches_, the sources note that they are not always ideal for getting _exact_ values, especially if the limit isn't a "nice" integer.

In summary, your answer effectively highlights the key role of graphs in understanding limit behavior, particularly in scenarios where limits don't exist due to oscillation, which is a significant concept emphasized by the sources.


### #human_explaination 

   Degradably fun so I can tell you a lot about women like for example if you're using a lemme work like a function that use Koh Sing Tang or Co Tang it can create and once you do the limit not settling in the pacific point if you do not draw the graph of epilemic it can lead to an error where you think that a gig approaching or you can estimate a point based on all the cosig X point that you have a stick on the table but if you use a different value of X it it can create a point that jump all over the place so it get more accurate if you use a graph to verify your estimate



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



