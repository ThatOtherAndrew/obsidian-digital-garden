---
{"dg-publish":true,"dg-permalink":"physics/torque","permalink":"/physics/torque/"}
---

## Torque
Torque ( $\large \tau$ ) is the **tendency of a force to turn an object** around an axis - the angular counterpart to a linear force, hence it can be thought of as **"angular force"**.

> [!summary] Formula
> $$\huge
> {\color{red} \tau} = {\color{cyan} F} {\color{yellow} r}
> $$
> > [!info] Variable Key
> > - $\large \color{red} \tau$ is the **torque**, in newton metres.
> > - $\large \color{cyan} F$ is the **linear force applied**, in newtons.
> > - $\large \color{yellow} r$ is the **distance** between the force and the centre of rotation, in metres.

## Moment of Inertia
Moment of inertia ( $\large I$ ) is the tendency of an object to **resist change in angular motion** - the angular counterpart to inertia, hence it can be thought of as **"angular inertia"**. Linearly, inertia is entirely dependent on mass, however with moment of inertia the radius is also involved as shown below:

> [!summary] Formula
> $$\huge
> {\color{limegreen} I} = {\color{violet} m} {\color{yellow} r}^2
> $$
> > [!info] Variable Key
> > - $\large {\color{limegreen} I}$ is the **moment of inertia**, in $\textup{kg m}^2$.
> > - $\large {\color{violet} m}$ is the **mass** of the rotating object, in kilograms.
> > - $\large {\color{yellow} r}$ is the **distance** between the mass and the centre of rotation, in metres.

## Unbalanced Torque
Just as Newton's second law of motion states that $\large F = ma$, a similar logic can be applied to an unbalanced torque, by substituting the linear properties with their angular counterparts:

| Linear                                                          | Angular                                                          |
| --------------------------------------------------------------- | ---------------------------------------------------------------- |
| **Force**                                                       | [[School/S6/Physics/Torque and Moment of Inertia#Torque\|#Torque]]                                                      |
| **Mass**                                                        | [[School/S6/Physics/Torque and Moment of Inertia#Moment of Inertia\|#Moment of Inertia]]                                           |
| [[School/S6/Physics/Rotational Motion#Linear Acceleration\|Linear Acceleration]] | [[School/S6/Physics/Rotational Motion#Angular Acceleration\|Angular Acceleration]] |

> [!summary] Formula
> $$\huge
> {\color{red} \tau} = {\color{limegreen} I} {\color{orange} \alpha}
> $$
> > [!info] Variable Key
> > - $\large {\color{red} \tau}$ is the **moment of inertia**, in $\textup{kg m}^2$.
> > - $\large {\color{limegreen} I}$ is the **mass** of the rotating object, in kilograms.
> > - $\large {\color{orange} \alpha}$ is the **distance** between the mass and the centre of rotation, in metres.

This can also be used to explain why the [[School/S6/Physics/Torque and Moment of Inertia#Moment of Inertia\|moment of inertia]] is proportional to $\large {\color{yellow} r}^2$ and not $\large {\color{yellow} r}$, which may seem unintuitive, by substituting in the equations for [[School/S6/Physics/Torque and Moment of Inertia#Torque\|torque]] and [[School/S6/Physics/Rotational Motion#Angular Acceleration\|angular acceleration]], then Newton's second law. Notice how the two $\large {\color{yellow} r}$ terms multiply together, whereas the $\large {\color{darkgrey} a}$ terms cancel out:

> [!hint] Moment of Inertia Proof
> $$\huge
> \begin{align}
> {\color{red} \tau} &= {\color{limegreen} I} {\color{orange} \alpha} \\[10pt]
> {\color{cyan} F} {\color{yellow} r} &= {\color{limegreen} I} \frac{\color{darkgrey} a}{\color{yellow} r} \\[10pt]
> {\color{violet} m} {\color{darkgrey} a} {\color{yellow} r} &= {\color{limegreen} I} \frac{\color{darkgrey} a}{\color{yellow} r} \\[10pt]
> {\color{limegreen} I} = {\color{violet} m} &{\color{darkgrey} a} {\color{yellow} r} \times \frac{\color{yellow} r}{\color{darkgrey} a} \\[10pt]
> {\color{limegreen} I} = {\color{violet} m} &{\color{yellow} r}^2
> \end{align}
> $$
