## 1. Header block

- title/topic: constant-acceleration kinematics, displacement, free fall, sign conventions, “weightless” vs weight, components, projectile-motion preview
    
- course: [not stated]
    
- date: [not stated]
    
- transcript source: from recording (speech-to-text)
    

---

## 2. Cleaned transcript body

### Notation: velocity as a function of time; why “final” vs “at time t”

Instructor: When the [object] has this velocity, this is the— so there’s a time interval, right, when $t = 0$ is the beginning of that time interval and then some other time $t$ in general. So this [at] $0$ is the velocity of the [object], one of the time was $0$. $a$ is the constant acceleration throughout that time interval. And the final is the velocity at that instant of time, $t$.

Instructor: And that’s the question that you— other authors of textbooks just write this as $v = v_\text{initial} + at$, like this is a velocity of time $t$. In fact, you can write this like a function of time, like $v$ as a function of time is $v_\text{initial} + kt$. I don’t like this question. You might think that this is a lot more than one part of time. But it’s written like this. It’s written meant to say that $v$ is a function of time, which clearly is if you see that by using some time.

Instructor: So I don’t like to use this notation. I need to use the $v_\text{final}$ to remind me that that’s what I’m talking about. That’s the question. Questions?

Instructor: If you took physics in the high school, you probably used that equation. But I don’t know if you were told where it comes from. You just learned from the definition of the equation $d/dt$. And then you would not get this expression if you did not pull $a$ outside the integral. That’s a must. So this equation only applies when the acceleration of an object is constant throughout.

Instructor: And when we get to chapter 4, we are going to discuss when that would be the case. Why would the acceleration be constant? What else must be true if the acceleration happens to be constant? We’ll talk about that in a second.

Source map for this section

- target: “other authors … write this as $v = v_\text{initial} + at$ … only applies when the acceleration … is constant”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 (Particle Moving Under Constant Acceleration) | confidence: high | note: it lists the constant-acceleration kinematic equations and the condition “constant acceleration.”
        
- target: “you would not get this expression if you did not pull $a$ outside the integral … only applies when … acceleration … is constant”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.6 (Velocity and Position by Integration) | confidence: medium | note: it shows the integral form and the “constant acceleration” vs “not constant” distinction.
        
- target: “$v$ is a function of time”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: chapter on kinematics in 1D/2D (exact section unknown) | confidence: medium | note: it explicitly frames $v(t)$ via integration and constant-acceleration tables.
        

Deep dive reading (project library)

- source: Chapter_2_Zemansky.pdf | location: §2.6 | note: read the integral relationships $v_f = v_i + \int_0^t a,dt$ and $x_f = x_i + \int_0^t v,dt$ and compare to the constant-$a$ special case.
    

---

### From $v = dr/dt$ to displacement; integrating with constant acceleration

Instructor: Now, if I use this instead of that as my final position, right, we also know that the velocity of an object is defined as the derivative of the position vector [with respect to] time. So again, if I do the same thing here, if I push more, I then $dr$ is equal to [something] times $dt$. And if I integrate both sides of this equation, I will get the integral of $dr$ equals the integral of $dt$.

Instructor: So what I will do is I’m going to take this expression for a while, because I cannot solve this integral unless this comes down, or unless I explicitly express this velocity in terms of time so that I can continue. So I’ll just take this expression.

Instructor: And then I’ll have $\int dr$ equals the integral of $v_0 + at , dt$.

Instructor: And now I’m going to put the integration. So the integral of the left-hand side is with respect to the position vector of— remember I talked about position vector the other day? Like the [planet] is here, right? And then there’s an $xy$ coordinate system, like this is $x$. And this is $y$, so that the origin is here, right?

Instructor: Before I want to know the position of the objects, I can tell you the position vector. Or I can tell you the coordinates, the $x$ and the $y$ coordinates, or I can tell you if I use other coordinates [like] $r$ and $\theta$. So various ways to express the coordinates of this class of position of the [object] can be used.

Instructor: And the object moves to maybe over here, right? So we can say that this is when $t = 0$. That’s the initial position. And then we can say that when the object will be here, the moment in time is $t$ and this is the final position.

Instructor: But what is the final position vector? So this will be— if this is the initial, then it’s the initial position vector. And the final position vector is the vector that tells you its position from the [origin] at that moment in time.

Instructor: So then [for bounds] I’m going to say, OK, so here I’m going to say $t = 0$ to some [later] time $t$. So therefore, what I’ll do over here is the position vector at the initial moment in time, so it’s $r_0$. And over here, my [upper limit] of integration must be the position vector at this moment in time, which is $r_\text{final}$.

Instructor: And then I can split the [right side] into two parts. I can write it as the integral of $v_0,dt$ from $0$ to $t$ plus the integral of $at,dt$ from $0$ to $t$. Are you with me?

Instructor: Now, then we evaluate: $r_\text{final} - r_\text{initial}$. So this becomes $r_\text{final} - r_\text{initial}$.

Instructor: Now, the initial velocity of something, what it really is, is just a given velocity at that moment in time. Like, if I throw a [ball] upwards at $3,\text{m/s}$ at some angle, that initial velocity is whatever it was given to the object. So the velocity, the initial velocity is a constant.

Instructor: And we are considering cases where the acceleration is a constant. So then we can pull $a$ outside. And what is the integral of $t,dt$? $t^2/2$. I’m going to evaluate that from $0$ to $t$. I’m just going to get $t^2/2$.

Instructor: Now, what is this? Mathematically, something final minus something initial is the change in that something. So mathematically, you write that as delta. Like, if I have $x_\text{final} - x_\text{initial}$, you can write that as $\Delta x$. $y_\text{final} - y_\text{initial}$, we can write that as $\Delta y$.

Instructor: So we can write this as $\Delta r$. So notice that I already have equation number one:  
$$  
\Delta r = v_0 t + \tfrac{1}{2} a t^2.  
$$  
That’s equation number one.

Source map for this section

- target: “velocity … derivative of the position vector … $dr$ … integrate both sides”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.6 (Velocity and Position by Integration) | confidence: high | note: it gives the integration relationships for velocity/position from acceleration.
        
- target: “$\Delta r = v_0 t + \tfrac{1}{2} a t^2$”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 (Particle Moving Under Constant Acceleration) | confidence: high | note: the constant-acceleration displacement equation appears there (vector/1D forms).
        
- target: “$\Delta x$, $\Delta y$ notation as ‘final minus initial’”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 (also the note “for one-dimensional motion along x/y”) | confidence: medium | note: it explicitly connects vector displacement to $\Delta x$ or $\Delta y$ in 1D cases.
        

Deep dive reading (project library)

- source: Chapter_2_Zemansky.pdf | location: §2.4 and §2.6 | note: read §2.6 first for the integral setup, then §2.4 for the closed-form constant-$a$ results.
    

---

### Displacement is “final minus initial”; vector picture; head-to-tail idea

Instructor: Let me say more about what $\Delta r$ represents— OK, it’s the change in the position vector. But let’s give it some meaning.

Instructor: If you look at this picture over here, let’s give it a little bit of origin. Because it’s going to be like a coordinate system.

Instructor: You know that that’s initial. That’s the final. [gesture] If I tell you, or if I ask you, what is this? Remember how I define displacement?

Instructor: If I start here and then I— [INAUDIBLE]— I go one, two, three, four, maybe. And then I turn. I go one, two, three. And this is my final moment in time.

Instructor: The displacement we said is a vector drawn straight from start to finish regardless of the path. So if the object starts over here, this is $t = 0$. That’s the final. Then this straight arrow is the displacement.

Instructor: Now, can you see maybe in disguise of it here that we have a head-to-tail [idea] of vector addition? Notice that something plus something equals something.

Instructor: So talk to someone. What plus what is equal to what in this [diagram]? What should go here? What plus what equals what? Talk to someone and tell them what you think this should be, that should be, and that should be.

[INAUDIBLE] [INAUDIBLE] [LAUGHTER] [INAUDIBLE]

Instructor: I can see Jack from up here. Is it $r_0$ plus $r$ or $r_f$? [unclear] That’s going to be the result. Equal to the displacement vector. [INAUDIBLE]

Instructor: And when it’s in mathematics, final minus initial, it’s changing that thing. So that’s why the displacement vector is written like that. It’s $\Delta r$. Yes?

Instructor: It has to do with— it’s defined as the change in the position vector. Now, it doesn’t matter what a path is taken by the object from the initial to the final position.

Instructor: [More examples of paths] … What matters is just draw a straight arrow from start to finish.

Source map for this section

- target: “displacement … vector drawn straight from start to finish regardless of the path”
    
    - source: Chapter_2_Zemansky.pdf | location: early Chapter 2 displacement discussion (exact subsection unknown) | confidence: medium | note: the chapter’s kinematics framing uses displacement vs path length; exact spot not verified in this snippet.
        
- target: “$\Delta r$ … change in the position vector … final minus initial”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 (notes using $\Delta r \Rightarrow \Delta x$ or $\Delta y$ for 1D) | confidence: medium | note: it explicitly uses $\Delta$ notation and relates vector displacement to components in 1D.
        
- target: “head-to-tail … vector addition”
    
    - source: Chapter_2_Zemansky.pdf | location: chapter material on vectors/kinematics setup (location unknown) | confidence: low | note: this handout excerpt doesn’t show the vector-addition diagram; you may need the Chapter 1 vectors handout/notes if it exists in your library.
        

If you want tighter mapping here: I can scan your project folder for whatever file covers “vectors: head-to-tail addition” and “displacement vs distance” (often Chapter 1 “Vectors” in course notes), but I won’t guess a filename that isn’t in your library list.

---

### Eliminating time to get an equation without $t$ (the “third equation”)

Instructor: OK. So we have the [equations] one and two. Now, equation number three, you just use one and two. What does equation number three not have, that means [it] involved equation one and two? Time.

Instructor: So just take time from this equation over here, for example. From number two, take time. So time is going to be what? $v_\text{final} - v$ [initial] over $a$ then. And then take that time. And then plug it here. And then plug it here. And then you do the algebra. And you’re going to get this equation.

Instructor: Which I don’t want to do that. If you’re bored, it’s really good to go to the [bus stop] … waiting for someone … late for lunch … [joke/aside].

Instructor: Questions? So those are the human equations. I would not be able to obtain this result if I did not take this step. I’d have to be able to take the acceleration outside the equation. And I can only do that in this class.

Instructor: If the acceleration of an object is changing, then … we’ve got to use the key equation. We have to use our [means]. And we’ll learn that in the [software]. Why? Actually, even in this [software], maybe. OK.

Source map for this section

- target: “equation number three … does not have … time … take time … $t = (v_f - v_i)/a$ … plug it … do algebra”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 (constant-acceleration equations set) | confidence: high | note: §2.4 presents the three standard kinematic equations (including the one without time).
        
- target: “if acceleration … is changing … we’ve got to use … [integration]”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.6 (Velocity and Position by Integration) | confidence: high | note: it explicitly states constant-acceleration formulas fail if $a(t)$ varies and gives the integral method.
        

---

### Free fall near Earth: assumptions, air resistance, what “free fall” means; moon/Earth in free fall

Instructor: As an example of an object that [moves] with acceleration constant, let’s consider an object that’s said to be in free fall, but in [post-acquisition], that the object is moving near the surface of the Earth. And not too fast.

Instructor: By near the surface of the Earth, I pretty much see inside the Earth atmosphere. The atmosphere extends, well, to around up to $25,\text{km}$ or so, $20$ miles above the surface of the Earth. It’s like $99%$ of the atmosphere is the Earth. But the radius of the Earth is $6{,}380,\text{km}$ [or] $6{,}400,\text{km}$. So if you compare $25$, $30,\text{km}$ to $6{,}400,\text{km}$ … anything inside the Earth atmosphere is what I mean when I say near the surface of the Earth.

Instructor: Also, I said not too fast. Because if the object is moving too fast through the air, then the object experiences air friction.

Instructor: So the problem that I want to consider here is an object that’s said to be in free fall. And now I have to be part of what free fall means. So what’s free fall? Anyone know? … An object is said to be in free fall [when] only gravity, only the force of gravity, is [acting]. And we’re going to talk about the force of gravity when we get to chapter 4.

Instructor: Now, I said that if an object moves through the Earth atmosphere and moves too fast, it would experience air friction. So therefore, the object would be subjected to two forces in that case: force of gravity acting on it, and force of friction acting on it. And because there’s an additional force besides gravity, [then] … [it’s not free fall].

Instructor: So let me ask you this question. Is the moon in free fall? Talk to someone and say yes, no. Is the moon in free fall?

Instructor: The moon orbits around Earth … [about] $28$ or so days. But as it moves around the Earth, is it in free fall?

Instructor: [discussion with students; partially unclear] … pulling you … closer … If the moon is stable … [unclear] … It’s only [gravity]. Yes. Nothing as special.

Instructor: So the only force that can act on [the moon] is the force of gravity. So the only force acting on the moon as it [orbits] around the Earth is the force of gravity. In fact, it’s mainly the force of gravity exerted by planet Earth. It’s also [gravity] exerted by the sun … [and other bodies] … you add them all up, you get a resultant gravitational force.

Instructor: Is the Earth [itself] in free fall? Not we as in the U.S., but, you know, the entire [planet]. Our entire home. Yes. We are in free fall also.

Instructor: Now, if I take this marker, I throw it upward. As I’m throwing it, there are two forces acting on it: force of gravity exerted by planet Earth, and the force set by my hand. So, it’s not in free fall. But as soon as it is [released] by hand, if I don’t throw it too fast, you know, so there’s no air friction, only gravity is [acting], then we’re back [to] free fall.

Source map for this section

- target: “free fall … only the force of gravity is [acting]”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 (Freely Falling Bodies) | confidence: high | note: it states free fall is motion only under gravity, regardless of initial motion.
        
- target: “near the surface of the Earth … atmosphere … $25,\text{km}$ … Earth radius $6{,}380,\text{km}$”
    
    - source: no match found in project library | location: n/a | confidence: low | note: you’d want an intro text’s “Earth atmosphere thickness vs Earth radius” note; the kinematics handout covers the modeling assumptions but not these specific numbers (not verified).
        
- target: “moon … in free fall … resultant gravitational force from multiple bodies”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: sections discussing free fall/orbits/weightlessness (exact location unknown) | confidence: medium | note: that book discusses free fall and apparent weightlessness (elevator/spacecraft examples) and treats gravity as always acting.
        

Deep dive reading (project library)

- source: Chapter_2_Zemansky.pdf | location: §2.5 | note: read the definition of free fall, the vector direction “down,” and how the kinematic equations specialize with $a_y = -g$ or $+g$ depending on axis choice.
    

---

### The number $9.8,\text{m/s}^2$, direction, and the symbol $g$; “$g$ is not gravity (force)”

Instructor: When we talk about the force of gravity, [later] we’re going to apply Newton’s theory of gravity, and his equations of motions, and we’re going to come out with a specific number for the acceleration of gravity.

Instructor: If the object is near the surface of the Earth, the number happens to be about $10$. Needless to say, it’s a vector. And the acceleration, it’s a vector. It points downwards towards the center of [the Earth].

Instructor: So, if I take this marker and throw it upward like that, if I neglect the effect of air friction, its acceleration is $9.8,\text{m/s}^2$ down. If I throw it around, as it moves in the air, [neglect] the effect of air friction, the acceleration is $9.8,\text{m/s}^2$ down.

Instructor: If it’s too far from the surface of the Earth, then it’s not $9.8,\text{m/s}^2$ down. There will be some other value.

Instructor: But near the surface of the Earth, the acceleration … we’re going to use this also … $9.8,\text{m/s}^2$ down with no justification, just $9.8,\text{m/s}^2$ down.

Instructor: Now, the symbol that we use to denote just the magnitude … of the acceleration due to gravity or free-fall acceleration, the symbol is the [lowercase] $g$. So $g$ down is the same as $9.8,\text{m/s}^2$ down if $g$ is [near] the surface of the Earth.

Instructor: So $g$ is the name given to the magnitude of the free-fall acceleration.

Instructor: Some people, even professors, and I don’t like it … Some people call $g$ “gravity.” Gravity is the force. This $g$ is the acceleration that results when that force is active, and acceleration is not the same as force. Acceleration is a vector … and force is not in $\text{m/s}^2$ … it’s a different unit.

Instructor: So the force is gravity. The acceleration that we solve for is the acceleration due to gravity, not gravity. But a lot of people … in high school … called it gravity … But to me it’s just an incorrect way of saying what that thing is. It is not gravity when you talk about gravity. Gravity is [a] force.

Instructor: [aside about people saying things wrong; includes a long analogy about electric circuits, “current flows,” electrons, and a textbook author named Sears; parts unclear]

Source map for this section

- target: “acceleration is $9.8,\text{m/s}^2$ down … near the surface”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 (Freely Falling Bodies) | confidence: high | note: it states free-fall acceleration near Earth is $9.8,\text{m/s}^2$ downward and defines $g$ as the magnitude.
        
- target: “$g$ denotes just the magnitude … some people call $g$ ‘gravity’ … gravity is the force”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 | confidence: medium | note: it distinguishes $g$ as magnitude of acceleration; the “don’t call it gravity” warning matches the instructor’s emphasis (exact wording differs).
        
- target: “weightless … astronaut/elevator … still gravity acts”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: section discussing free fall and apparent weightlessness (exact location unknown) | confidence: high | note: it contains the elevator/spacecraft “apparent weightlessness” discussion.
        

Deep dive reading (project library)

- source: Chapter_2_Zemansky.pdf | location: §2.5 | note: focus on the definition “$g$ is the magnitude” and the sign convention ($a_y = -g$ if up is positive).
    
- source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: “mass vs weight” and “apparent weightlessness” sections (exact location unknown) | note: read the passages clarifying that gravity still acts in free fall; “weightless” refers to scale/normal-force reading.
    

---

### Coordinate choice and components: $a_x = 0$; horizontal velocity constant; projectile-motion preview

Instructor: So let’s go back to the case of one. So let me ask you this so that you see why we’re already about vectors.

Instructor: Let’s say we know that the acceleration, the free fall acceleration, is $9.8,\text{m/s}^2$ down … towards the center [of Earth].

Instructor: So when you solve a problem you introduce an $xy$ coordinate and now you have two choices.

Instructor: Choice number one: choose the $x$ axis to be to the right positive, and the $y$ axis to be up. But that acceleration vector is down, so the $x$ component is $0$ and the $y$ component is $-9.8,\text{m/s}^2$ or $-g$.

Instructor: Another choice: choose down as positive on the $y$ axis and $x$ to the right. In this case the $x$ component is $0$ and the $y$ component is $+9.8,\text{m/s}^2$ or $+g$.

Instructor: Now this chapter 2 is motion in one dimension. So I want to talk about free fall in one dimension … object moves up and down … and then you choose either up or down.

Instructor: … Notice that in both cases this is $0$ and this is $0$. What does that mean? My question is what does it mean … the $x$ component being $0$?

Student: [attempt] … when it says $0$ it is not getting further away or closer … [unclear] … I don’t know sorry.

Instructor: Yes. What exactly it means: the $x$ component of the velocity is constant. If the acceleration is $0$ along some direction, the velocity in that direction is constant. Which doesn’t necessarily mean $0$. $0$ is a constant but it will also be something else.

Instructor: If I take this [marker], I am holding it now. I’m going to let go and shh it went straight down. Why didn’t it go like this …? As soon as I let go, what was the acceleration? $9.8,\text{m/s}^2$ down. What is the $x$ component of that acceleration? $0$. So the velocity component in this direction has to stay the same constant throughout the motion.

Instructor: But when I let it go what was the initial velocity? $0$. What was the $x$ component of that? $0$. So it has to stay $0$ throughout the motion because there is no acceleration component this way.

Instructor: Now if I take these keys and I throw it [not] straight down … suppose I threw them at $5,\text{m/s}$ at $37^\circ$. So what is the $x$ component of that initial velocity? [instructor says numbers:] “we find … $4$ … and … $3$.”

Instructor: The fact that the acceleration on the $x$ axis is $0$ … means the component of velocity … will stay the same. So later on … the velocity is tangent to the path … I know the $x$ component of the velocity is going to be $4,\text{m/s}$ because that’s not going to change.

Instructor: If I throw this object upward … initially the velocity vector is upward. What is initially the $x$ component? $0$. So therefore as it goes up the $x$ component has to stay $0$ so it’s not going to turn … it has to go straight up and then straight back down.

Instructor: Unless … there’s a wind … then you have an additional force besides gravity acting on it … so that is not in free fall anymore.

Instructor: … We’ll get to chapter 3 when we study motion in two dimensions … but I do know that the $x$ component of the velocity is going to be $4,\text{m/s}$.

Instructor: Some people say a picture is worth a thousand words … I’m one of those people who says … the equation is worth a thousand pictures.

Instructor: If the acceleration of the [horizontal] direction is zero, the velocity of that direction … is going to remain constant.

Instructor: Now remember what I said on Monday … as soon as this thing left my hand the velocity vector was this one … it has an $x$ component … it stays the same … and it has a $y$ component … the acceleration vector is down so if the initial velocity is up, it slows down as it rises; then speeds up as it falls.

Source map for this section

- target: “$a_x = 0$ … velocity component in that direction is constant”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: projectile motion discussion (exact section unknown) | confidence: high | note: it states $a_x = 0$, $a_y = -g$ (no air resistance) and emphasizes independent components.
        
- target: “chapter 2 is motion in one dimension … free fall in one dimension”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 (Freely Falling Bodies) and §2.4 | confidence: high | note: it specializes kinematics to $y$-motion and writes the component equations.
        
- target: “velocity vector tangent to the path … (two dimensions later)”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: projectile motion section (exact location unknown) | confidence: medium | note: it frames trajectory, components, and velocity along the path in 2D.
        

---

### Rewriting the three kinematic equations in 1D free fall (component form)

Instructor: So therefore let’s rewrite these three equations … just for free fall in one dimension, which is just up and down.

Instructor: What do we call the $y$ component of the displacement vector? We can call it $\Delta y$.

Instructor: What is the $y$ component of the initial velocity? I can just call it $v_{\text{initial},y}$.

Instructor: And then $t$ is $t$. $t$ doesn’t have any components, right? Time is a scalar component. You don’t talk about the $x$ component of time or the $y$ component of time. Time is time.

Instructor: Velocity is a vector so there I can talk about components.

Instructor: What about if it’s in free fall near the surface of the earth? Notice that the $y$ component of the acceleration is either $-g$ or $+g$.

Instructor: What determines whether it’s going to be plus or minus $g$? What we choose to be positive for the $y$ axis. If we choose up as positive, then $a_y = -g$. If we choose down as positive, then $a_y = +g$.

Instructor: So therefore I’m going to write plus or minus $g$ depending on which direction you choose as positive.

Instructor: And then … I write the $y$ component of the final velocity as $v_{\text{final},y}$, and:  
$$  
v_{\text{final},y} = v_{\text{initial},y} \pm g t.  
$$  
Instructor: And then:  
$$  
v_{\text{final},y}^2 = v_{\text{initial},y}^2 + 2(\pm g),\Delta y.  
$$  
Instructor: And also the displacement:  
$$  
\Delta y = y_f - y_i = v_{\text{initial},y},t + \tfrac{1}{2}(\pm g)t^2.  
$$

Instructor: … those are the [equations] … and we need to have study of [quiz] vectors … but those are the two [notions] … velocity and acceleration vectors point in the same direction or opposite direction.

Source map for this section

- target: “$\Delta y = y_f - y_i = v_{\text{initial},y}t + \tfrac{1}{2}(\pm g)t^2$; $v_{\text{final},y} = v_{\text{initial},y} \pm gt$; $v_{\text{final},y}^2 = v_{\text{initial},y}^2 + 2(\pm g)\Delta y$”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 (Freely Falling Bodies) | confidence: high | note: it lists the free-fall-specialized kinematics and defines $g$ and sign via direction.
        
- target: “time is a scalar … velocity is a vector”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.3 (Acceleration) and surrounding vector/scalar notes (exact location unknown) | confidence: medium | note: the handout emphasizes vectors vs scalars and component reasoning.
        

---

### Example 1 (worked): weightless vs weight; scale reading; normal force; free fall in a falling system

Example 1

- Given:
    
    - a bathroom scale with a spring
        
    - standing at rest vs “jumping with the scale” in free fall
        
    - concept of “weightless” (apparent) vs weight (gravity force)
        
- Steps:
    
    - Instructor: the scale has a spring; when you stand on it you compress the spring; the spring pushes you back up; you push the scale.
        
    - Instructor: there are two forces on you: your weight (gravity) and the force of the spring/scale pushing you upward.
        
    - Instructor: if you stand at rest, your acceleration is $0$, so the net force must be $0$.
        
    - Instructor: therefore the upward spring force and downward weight must have equal magnitude and opposite direction.
        
    - Instructor: the scale reading is the force with which the spring pushes you upward; in the rest case this equals your weight (because net force is $0$).
        
    - Instructor: if you go to the edge [and] jump while holding the scale under your feet, in free fall the scale will read $0$ because nothing is pushing you against it (no spring compression / no normal force).
        
    - Instructor: people say “you’re weightless,” but you do have a weight (gravity still acts); you just don’t have the correct setup to measure your weight with a scale.
        
- Result:
    
    - “weightless” in free fall refers to the scale reading (normal force) going to $0$, not gravity disappearing.
        

Source map for this example

- target: “the scale reading … is the force with which the spring is pushing you upward … if acceleration is zero … it equals your weight”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: mass vs weight + apparent weightlessness sections (exact location unknown) | confidence: high | note: it discusses weight, normal force, and apparent weightlessness (elevator/spacecraft/scale context).
        
- target: “in free fall … scale reads zero … gravity still acts”
    
    - source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: free fall / apparent weightlessness discussion (exact location unknown) | confidence: high | note: it explicitly states gravity still acts but sensations/scale readings can be zero in free fall.
        

Deep dive reading (project library)

- source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: apparent weightlessness + weight vs mass sections (exact location unknown) | note: read the passages that distinguish true weight from “scale reading” (normal force).
    

---

### Example 2 (worked): stone thrown upward from a building; choosing origin and sign; answering multiple questions

Example 2

- Given:
    
    - a stone (or marker) thrown from the top of a building
        
    - initial velocity: $20,\text{m/s}$ straight upward
        
    - building height: $50,\text{m}$
        
    - stone “just misses the edge of the roof on its way down”
        
    - neglect air friction; treat as 1D vertical motion
        
    - choose a coordinate system (origin and sign convention)
        
- Steps:
    
    - Instructor: list of questions to answer:
        
        1. determine the time when the stone reaches the maximum height
            
        2. determine the maximum height above the rooftop
            
        3. determine the time when the stone returns to the level of the thrower (rooftop level)
            
        4. determine the velocity of the stone when it reaches the level of the thrower
            
        5. what is the acceleration of the stone as it reaches the maximum height
            
        6. what is the velocity and position $5$ seconds after it’s thrown
            
    - Instructor: acceleration is constant while in the air (neglect air friction): “$9.8,\text{m/s}^2$ down” on the way up, on the way down, and at the top; the velocity can be $0$ at the top but acceleration is still $9.8,\text{m/s}^2$ down.
        
    - Instructor: choose a coordinate system:
        
        - choose the origin at the bottom of the building (ground)
            
        - choose $+y$ upward
            
        - then acceleration is downward, so $a_y = -g$
            
    - Instructor: for maximum height, final vertical velocity is $0$ at the top:
        
        - use the velocity equation (the one involving $v_y$ and $t$):
            
            - set $v_{\text{final},y} = 0$
                
            - $0 = v_{\text{initial},y} - gt$
                
            - solve $t = 20/g$
                
            - instructor’s numeric: “$2.04$ seconds”
                
    - Instructor: for maximum height position:
        
        - use the displacement equation:
            
            - $y_f - y_i = v_{\text{initial},y}t + \tfrac{1}{2}(-g)t^2$
                
        - interpret $y_i$ and $y_f$ as coordinates measured from the chosen origin (ground)
            
        - plug $v_{\text{initial},y} = 20$ and $t = 2.04$
            
        - instructor’s computed coordinate: “$70.4$” (units spoken as “centimeters” once, but context indicates meters; keep as stated: “$70.4$ [centimeters]”)
            
        - instructor: this $y_f$ is height above the ground because origin is at ground
            
        - to get “above the roof top,” subtract the building height $50$:
            
            - “therefore that has to be $20.4$ meters … above the roof”
                
    - Instructor: time to return to the thrower’s level (rooftop):
        
        - treat the rooftop position as the final position for this part
            
        - use displacement equation with $\Delta y = 0$ because it returns to the same level:
            
            - $0 = v_{\text{initial},y}t + \tfrac{1}{2}(-g)t^2$
                
        - factor out $t$; cancel; solve:
            
            - $t = 2(20)/9.8$
                
        - instructor: this equals twice the rise time:
            
            - “$4.08$ seconds” (also said “$4.48$ seconds” once; keep both as spoken: [unclear/conflict])
                
        - instructor: principle statement:
            
            - time to rise to the top equals time to come back down to the same level (no air friction), so the total to return to launch level is twice the rise time
                
    - Instructor: velocity when it returns to the thrower’s level:
        
        - use the velocity equation:
            
            - $v_{\text{final},y} = v_{\text{initial},y} - gt$
                
        - plug $t = 4.08,\text{s}$:
            
            - compute gives $v_{\text{final},y} = -20,\text{m/s}$
                
        - interpret the minus sign:
            
            - it means direction opposite the chosen positive ($+y$ up), so the velocity is $20,\text{m/s}$ downward
                
        - instructor: not asking for speed; must give velocity with direction:
            
            - acceptable: “$20,\text{m/s}$ down,” or “$-20,\text{m/s}$ in the $\hat{\jmath}$ direction” as “$-,\hat{\jmath}$” [spoken as “minus J hat direction”]
                
    - Instructor: acceleration at the maximum height:
        
        - still $9.8,\text{m/s}^2$ downward (free fall; velocity $0$ doesn’t change that)
            
    - Instructor: position/velocity at $5$ seconds:
        
        - note: since return-to-roof time is about $4.08,\text{s}$, at $5,\text{s}$ the stone is already below the rooftop level; if you picture it “still above the roof” you made a mistake.
            
- Result:
    
    - rise time to max height: $2.04,\text{s}$ (as stated)
        
    - max height coordinate from ground: “$70.4$ [centimeters]” (as stated; unit inconsistent with context) and “$20.4,\text{m}$ above the roof” (as stated)
        
    - return to rooftop level: “$4.08,\text{s}$” (also “$4.48,\text{s}$” once) (as stated)
        
    - velocity at rooftop level on return: $-20,\text{m/s}$ (meaning $20,\text{m/s}$ downward)
        
    - acceleration throughout flight (neglect air): $9.8,\text{m/s}^2$ downward
        

Source map for this example

- target: “stone … $20,\text{m/s}$ straight upward … building $50,\text{m}$ high … solve time to max height … $v_y=0$ at the top”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.5 (Freely Falling Bodies) | confidence: high | note: it provides the free-fall kinematic equations in $y$ and the sign convention with $a_y = \pm g$.
        
- target: “choose origin … choose $+y$ up … then $a_y=-g$ … be careful what $y_i, y_f$ mean”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.4 and §2.5 (component/coordinate usage notes) | confidence: medium | note: it explicitly frames $\Delta y = y_f - y_i$ and component forms; origin choice is a modeling step emphasized in these problems.
        
- target: “time to rise equals time to return to same level (no air resistance)”
    
    - source: no match found in project library | location: n/a | confidence: low | note: this symmetry fact follows directly from constant-acceleration equations; if you want it stated explicitly, look for a “symmetry of vertical motion” note in your course’s Chapter 2/3 notes (if present).
        
- target: “$v_{\text{final},y} = -20,\text{m/s}$ … not speed … must state direction”
    
    - source: Chapter_2_Zemansky.pdf | location: §2.3–§2.5 (vectors/components + free fall) | confidence: medium | note: the handout emphasizes vector direction/sign and writing components.
        

Deep dive reading (project library)

- source: Chapter_2_Zemansky.pdf | location: §2.5 | note: read the free-fall specialization and the “$g$ is magnitude; sign comes from axis choice” warning; then redo this exact building-throw structure.
    
- source: University Physics with Modern Physics … Young/Freedman … 13th ed … Anna’s Arch.pdf | location: projectile/free-fall sections (exact location unknown) | note: read the part that explicitly says $a_x = 0$, $a_y = -g$ (no air resistance) and treats components independently.
    

---

### Class/admin tail: homework posting; unrelated talk; many inaudibles

Speaker: [inaudible] … [inaudible] …

Instructor: Hey guys, I need like five minutes to see their homework posted. I’ll be right with you.

Speaker: Oh, it’s on the map. [inaudible]

Speaker: Sylvy make a detail not likebooks for me make aure to map what he is talking about to the chapter and section so thwt I can learn myself

Source map for this section

- target: “homework posted”
    
    - source: no match found in project library | location: n/a | confidence: low | note: this is course logistics, not physics content.
        

---

## 3. Glossary (as stated in lecture)

- free fall: “only gravity, only the force of gravity is [acting]”
    
- displacement: “a vector drawn straight from start to finish regardless of the path”
    
- $g$: “the symbol … to denote just the magnitude … of the acceleration due to gravity or free-fall acceleration”
    
- “weightless”: “it’s going to read zero … you just don’t have the correct [setup] to measure your weight” (scale context)
    
- time (scalar): “time is time … it’s a scalar component … you don’t talk about the $x$ component of time”
    
- [current analogy]: “the flow of these electrons in the wires is what constitutes a current … what’s flowing are the electrons not the current … the flow of the electrons is the current”
    

---

## 4. Transcript integrity notes

- [unclear] “this 0 is the velocity of the Arctic” (object name misheard)
    
- [unclear] “$v$ as a function of time is $v_\text{initial} + kt$” (uses $k$ instead of $a$)
    
- [unclear] “if I push more, I then $dr$ is equal to equal to 3 times $dt$”
    
- [unclear] “the paulantic is here” (object/word misheard)
    
- [unclear] “it’s $r$ sub 2” (likely $r_0$)
    
- [unclear] “Is it $r_0$ plus $r$ or $r_f$? … Equal to the displacement vector.”
    
- [unclear] “equation number three … what does equation number three not have … that means C involved”
    
- [unclear] “we’ve got to use our means … learn that in the software”
    
- [unclear] free-fall/orbit discussion segment: multiple lines of repeated “it’s a bit of a long way to go … it’s one …” (speech-to-text loop)
    
- [unclear] “$70.4$ centimeters” vs context suggesting meters; kept exactly as spoken but unit conflicts with the rest
    
- [unclear/conflict] “$4.08$ seconds” vs “$4.48$ seconds” for return-to-rooftop time; both kept as stated
    
- cut-off / derail: long unrelated segment about “quiet the issues … Justin … temperature or cold … radical fear of the sun …” (content not physics; preserved; meaning unclear)
    
- [inaudible] blocks preserved throughout exactly as “[INAUDIBLE]” / “[inaudible]”