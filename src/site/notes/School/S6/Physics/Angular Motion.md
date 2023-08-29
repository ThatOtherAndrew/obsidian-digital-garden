---
{"dg-publish":true,"dg-permalink":"physics/angular-motion","permalink":"/physics/angular-motion/"}
---


## Basic Definitions

![Linear and Angular Velocity 2023-08-25 10.50.33.excalidraw.png|400](/img/user/!%20Obsidian/Excalidraw/Linear%20and%20Angular%20Velocity%202023-08-25%2010.50.33.excalidraw.png)
#### Angular Motion
**Angular motion** is the movement of an object which is rotating around an axis.

#### Angular Displacement
**Angular displacement** ( $\large \theta$ ) is the **angle through which the object rotates**, measured in **radians** ( $\textup{rad}$ ).

> [!tip]
> $360^\circ = 2\pi$ radians.

#### Angular Velocity
**Angular velocity** ( $\large \omega$ ) is the **rate of change of [[School/S6/Physics/Angular Motion#Angular Displacement\|angular displacement]]**, measured in **radians per second** ( $\textup{rad s}^{-1}$ ).

> [!summary] Formula
> $$\huge
> \omega = \frac{d\theta}{dt}
> $$

#### Angular Acceleration
**Angular acceleration** ( $\large \alpha$ ) is the **rate of change of [[School/S6/Physics/Angular Motion#Angular Velocity\|angular velocity]]**, measured in **radians per second squared** ( $\textup{rad s}^{-2}$ ).

> [!warning] Alpha, not A!
> Don't confuse $\large \alpha$ with $\large a$ ([[School/S6/Physics/Angular Motion#Linear Acceleration\|linear acceleration]])! They look similar, but they are the Greek letter alpha and the letter A respectively.

> [!summary] Formula
> $$\huge
> a = \frac{d\omega}{dt}
> $$

#### Linear Velocity
**Linear velocity** or **tangential velocity** ( $\large v$ ) is the **instantaneous linear velocity** of a rotating object - it is the velocity of an object revolving around an axis if the tether breaks.

#### Linear Acceleration
**Linear acceleration** or **tangential acceleration** ( $\large a_t$ ), like [[School/S6/Physics/Angular Motion#Tangential Velocity\|tangential velocity]], is the **instantaneous linear acceleration** of a rotating object - it's the **change in tangential velocity**.

> [!summary] Formula
> $$\huge
> a_t = \frac{dv}{dt}
> $$

#### Radial Acceleration
**Radial acceleration** ( $\large a_r$ ) is the **acceleration towards the centre** of a rotating system, caused by [[School/S6/Physics/Angular Motion#Centripetal Force\|centripetal force]].

> [!summary] Formula
> $$\huge
> {\color{red} a_r}
> = {\color{cyan} r} {\color{yellow} \omega}^2
> = \frac{{\color{violet} v}^2}{\color{cyan} r}
> $$
> > [!info] Variable Key
> > - $\large \color{red} a_r$ is the **radial acceleration**, in metres per second squared.
> > - $\large \color{cyan} r$ is the **radius** of the rotating system, in metres.
> > - $\large \color{yellow} \omega$ is the **[[School/S6/Physics/Angular Motion#Angular Velocity\|angular velocity]]**, in radians per second.
> > - $\large \color{violet} v$ is the **[[School/S6/Physics/Angular Motion#Linear Velocity\|linear velocity]]**, in metres per second.

## Equations of Motion
The equations of motion **can be applied to angular motion** as well as linear motion, as long as all tangential/linear quantities are substituted for their angular counterparts.

| Quantity               |   Linear   |      Angular      |
| ---------------------- |:----------:|:-----------------:|
| Displacement           | $\large s$ |  $\large \theta$  |
| Initial Velocity       | $\large u$ | $\large \omega_0$ |
| Current Velocity       | $\large v$ |  $\large \omega$  |
| Acceleration           | $\large a$ |  $\large \alpha$  |
| Time (doesn't change!) | $\large t$ |    $\large t$     |

You can convert between **linear** and **angular** motion by **multiplying or dividing the radius** as a factor. To think about this intuitively, this is because $\large c = 2\pi r$, and if the circumference is directly proportional to the radius, then velocity, acceleration, etc. must be directly proportional to the radius as well.
## Centripetal Force
[[School/S5/Physics/1. Our Dynamic Universe/Basics of Forces#Newton's Laws\|Newton's laws of motion]] state that an object cannot accelerate unless an unbalanced force acts upon it. In this case, a force which isn't parallel to the direction of motion is required to change the direction of an object's motion, i.e. to get it to turn.

This force is known as the **radial force** or **centripetal force**, as the force vector always points towards the centre of the circle of rotation and is hence parallel to the radius. This force can be caused by friction, gravity, tension, an electromagnetic force, or any other such force.

Using $\large F=ma$, we can calculate the centripetal force of an object with a known mass:

> [!summary] Formula
> $$\huge
> {\color{red} F_c} = {\color{cyan} m} {\color{yellow} a_r}
> $$
> > [!info] Variable Key
> > - $\large \color{red} F_c$ is the **centripetal force**, in newtons.
> > - $\large \color{yellow} a_r$ is the **[[School/S6/Physics/Angular Motion#Radial Acceleration\|radial acceleration]]**, in metres per second squared.
