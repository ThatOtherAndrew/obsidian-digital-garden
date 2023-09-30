---
{"dg-publish":true,"dg-path":"Advanced Higher/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia.md","dg-permalink":"physics/torque","permalink":"/physics/torque/","created":"","updated":""}
---

## Torque
Torque ( $\large \tau$ ) is the **tendency of a force to turn an object** around an axis - the angular counterpart to a linear force, hence it can be thought of as **"angular force"**.

> [!summary] Formula
> $$\huge
> {\color{red} \tau} = {\color{cyan} F} {\color{yellow} r}
> $$
> > [!info] Variable Key
> > - $\large \color{red} \tau$ is **torque**, in newton metres.
> > - $\large \color{cyan} F$ is the **linear force applied**, in newtons.
> > - $\large \color{yellow} r$ is the **distance** between the force and the centre of rotation, in metres.

## Moment of Inertia
Moment of inertia ( $\large I$ ) is the tendency of an object to **resist change in angular motion** - the angular counterpart to inertia, hence it can be thought of as **"angular inertia"**. Linearly, inertia is entirely dependent on mass, however with moment of inertia the radius is also involved as shown below:

> [!summary] Formula
> $$\huge
> {\color{limegreen} I} = {\color{violet} m} {\color{yellow} r}^2
> $$
> > [!info] Variable Key
> > - $\large \color{limegreen} I$ is the **moment of inertia**, in $\textup{kg m}^2$.
> > - $\large \color{violet} m$ is the **point mass** of a rotating object, in kilograms.
> > - $\large \color{yellow} r$ is the **distance** between the mass and the centre of rotation, in metres.

Note how this formula assumes a **point mass** - a mass condensed onto an infinitely small point. In practice, this provides a good enough approximation for masses with very little variance in radius, like a small ball or a thin ring - however for more accurate results, it's necessary to multiply by a constant depending on the shape of the mass. This constant can be calculated by using calculus to find a point mass which has an equivalent moment of inertia to the real mass - in other words, by finding an **average moment of inertia** for all points of mass in the object.
## Unbalanced Torque
Just as Newton's second law of motion states that $\large F = ma$, a similar logic can be applied to an unbalanced torque, by substituting the linear properties with their angular counterparts:

| Linear                                                                                     | Angular                                                                                            |
| ------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| $\large \color{cyan} F$ Force                                                              | $\large \color{red} \tau$ [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Torque\|Torque]]                          |
| $\large \color{violet} m$ Mass                                                             | $\large \color{limegreen} I$ [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|Moment of Inertia]] |
| $\large \color{darkgrey} a$ [[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Linear Acceleration\|Linear Acceleration]] | $\large \color{orange} \alpha$ [[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Acceleration\|Angular Acceleration]]    |

> [!summary] Formula
> $$\huge
> {\color{red} \tau} = {\color{limegreen} I} {\color{orange} \alpha}
> $$
> > [!info] Variable Key
> > - $\large \color{red} \tau$ is **unbalanced torque**, in newton metres.
> > - $\large \color{limegreen} I$ is the **moment of inertia**, in $\textup{kg m}^2$.
> > - $\large \color{orange} \alpha$ is **[[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Acceleration\|angular acceleration]]**, in radians per second squared.

> [!question]- Moment of Inertia Proof
> For the curious, this can also be used to explain why the [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]] is proportional to $\large {\color{yellow} r}^2$ and not $\large \color{yellow} r$, which may seem unintuitive. This can be done by substituting in the equations for [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Torque\|torque]] and [[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Acceleration\|angular acceleration]], then Newton's second law. Notice how the two $\large \color{yellow} r$ terms multiply together, whereas the $\large \color{darkgrey} a$ terms cancel out:
> 
> $$\large
> \begin{align}
> {\color{red} \tau} &= {\color{limegreen} I} {\color{orange} \alpha} \\[10pt]
> {\color{cyan} F} {\color{yellow} r} &= {\color{limegreen} I} \frac{\color{darkgrey} a}{\color{yellow} r} \\[10pt]
> {\color{violet} m} {\color{darkgrey} a} {\color{yellow} r} &= {\color{limegreen} I} \frac{\color{darkgrey} a}{\color{yellow} r} \\[10pt]
> {\color{limegreen} I} = {\color{violet} m} &{\color{darkgrey} a} {\color{yellow} r} \times \frac{\color{yellow} r}{\color{darkgrey} a} \\[10pt]
> {\color{limegreen} I} = {\color{violet} m} &{\color{yellow} r}^2
> \end{align}
> $$

## Angular Momentum
Just as [[School/S5/Physics/Our Dynamic Universe/Momentum\|linear momentum]] is mass times velocity ( $\large p = mv$ ), **angular momentum** is [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]] times [[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Velocity\|angular velocity]].

> [!summary] Formula
> $$\huge
> {\color{violet} L} = {\color{limegreen} I} {\color{salmon} \omega}
> $$
> > [!info] Variable Key
> > - $\large \color{violet} L$ is **angular momentum**, in $\textup{kg m}^2 \textup{ s}^{-1}$.
> > - $\large \color{limegreen} I$ is the **[[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]]**, in kilograms per metre squared.
> > - $\large \color{salmon} \omega$ is the **[[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Velocity\|angular velocity]]**, in radians per second.

### Conservation of Angular Momentum
[[School/S5/Physics/Our Dynamic Universe/Momentum#Conservation of Momentum\|Conservation of Momentum]] states that in the absence of external forces, the **total momentum of a system remains constant** - it can be transferred between objects via collisions, however the total momentum cannot increase or decrease in the process.

This applies to [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Angular Momentum\|angular momentum]] as well - it is still the same concept of momentum, just considered from a different perspective (for example, linear momentum can be thought of as angular momentum with an radius that approaches infinity).

> [!summary]
> In the absence of external [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Torque\|torques]], the **total [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Angular Momentum\|angular momentum]]** of a system **remains constant**.

In practice, this means that if the [[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]] of a rotating object decreases (e.g. by a mass being pulled closer to the centre), the [[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Velocity\|angular velocity]] must increase to keep $\large \color{violet} L$ constant, and vice versa.

## Rotational Kinetic Energy
Just as a linearly moving mass has kinetic energy, a rotating mass has kinetic energy as well - it just revolves around a point instead of travelling in a straight line. Using the formula we already know for kinetic energy, $\large E_k = \frac{1}{2}mv^2$, we can substitute the variables for their rotational counterparts to get the following formula:

> [!summary] Formula
> $$\huge
> {\color{pink} E_k} = \frac{1}{2} {\color{limegreen} I} {\color{salmon} \omega}^2
> $$
> > [!info] Variable Key
> > - $\large \color{pink} E_k$ is the **rotational kinetic energy** of the mass, in joules.
> > - $\large \color{limegreen} I$ is the **[[School/S6/Physics/Rotational Motion and Astrophysics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]]**, in kilograms per metre squared.
> > - $\large \color{salmon} \omega$ is the **[[School/S6/Physics/Rotational Motion and Astrophysics/Rotational Motion#Angular Velocity\|angular velocity]]**, in radians per second.
