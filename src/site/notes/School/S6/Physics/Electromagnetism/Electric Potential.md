---
{"dg-publish":true,"dg-path":"Advanced Higher/Physics/Electromagnetism/Electric Potential.md","dg-permalink":"physics/electric-potential","permalink":"/physics/electric-potential/","created":"","updated":""}
---

## Electric Field Strength

> [!note]- Using the Analogy
> <sup>This explanation uses the [[School/S6/Physics/Electromagnetism/Altitude Analogy\|altitude analogy]] - give it a read if you haven't already!</sup>
> 
> #Todo

Electric field strength is a **vector** which represents the **electrical force per unit of positive charge** - similar to how gravitational field strength is the weight per unit of mass. The electric field strength can be calculated at the point of a charged particle, if the charge and mass of the particle is known:

> [!summary] Formula
> $$\huge
> {\color{red} E} = \frac{\color{cyan} F}{\color{yellow} Q}
> $$
> > [!info] Variable Key
> > - $\large \color{red} E$ is the **electric field strength**, in newtons per coulomb.
> > - $\large \color{cyan} F$ is the **electrostatic force** acting on the particle, in newtons.
> > - $\large \color{yellow} Q$ is the **charge of the particle**, in coulombs.

### Radial Fields

Substituting $\large \color{cyan} F$ with [[School/S6/Physics/Electromagnetism/Coulomb's Law#Formula\|Coulomb's law]] causes the charge of the particle, $\large \color{yellow} Q$, to cancel out with one of the charges in the numerator - which leaves us with the below formula for **radial fields**:

> [!summary] Formula
> $$\huge
> {\color{red} E} = \frac {
> 	\color{yellow} Q
> } {
> 	4\pi\ {\color{limegreen} \varepsilon_0}\ {\color{violet} r}^2
> }
> $$
> > [!info] Variable Key
> > - $\large \color{red} E$ is the **electric field strength**, in newtons per coulomb.
> > - $\large \color{yellow} Q$ is the ⚠️ **charge of the particle creating the field**, in coulombs.
> > - $\large \color{limegreen} \varepsilon_0$ is the **[[School/S6/Physics/Electromagnetism/Coulomb's Law#Vacuum Permittivity\|vacuum permittivity]]** constant.
> > - $\large \color{violet} r$ is the **distance to the particle**, in metres.

> [!warning] Charge Confusion!
> This below formula can **only be used for radial fields** - it's essentially just the [[School/S6/Physics/Electromagnetism/Coulomb's Law#Formula\|Coulomb's law formula]] but with one of the particles removed, hence leaving behind a radial field.
> 
> In this formula, $\large \color{yellow} Q$ refers to the charge of the particle which is **creating the field you're measuring** - any test charge that may be situated at the point you're trying to measure the electric field strength of doesn't matter!

## Electric Potential

> [!note]- Using the Analogy
> <sup>This explanation uses the [[School/S6/Physics/Electromagnetism/Altitude Analogy\|altitude analogy]] - give it a read if you haven't already!</sup>
> 
> #Todo

The electric potential at a point (sometimes referred to **potential** within an appropriate context) is a **scalar** which represents **electric potential energy** - the electric counterpart to [[School/S4/Physics/Dynamics and Space/Energy, Work and Power#Gravitational potential energy\|gravitational potential energy]] - per unit of charge. This can be **positive or negative** depending on the polarity of the charge creating the [[School/S5/Physics/Particles and Waves/Electric Fields\|electric field]].

The formal definition of electric potential is the energy required to move a **1 coulomb positive test charge** to that point from an infinitely far location, where the [[School/S6/Physics/Electromagnetism/Electric Potential#Electric Field Strength\|electric field strength]] would be zero. This helps to explain why the electric potential at a point increases when it approaches a positively charged particle, and not vice versa.

> [!summary] Formula
> $$\huge
> {\color{mediumpurple} V} = \frac{\color{orange} W}{\color{yellow} Q}
> $$
> > [!info] Variable Key
> > - $\large \color{mediumpurple} V$ is the **electric potential** at a point, in joules per coulomb.
> > - $\large \color{orange} W$ is the **work done** bringing a positive test charge from infinity, in joules.
> > - $\large \color{yellow} Q$ is the **charge** of #Todo, in coulombs.

> [!question] Wait, isn't this just voltage?
> Does this look familiar from the Higher Physics course? While this is the same formula for **[[School/S5/Physics/Particles and Waves/Electric Fields#Voltage\|voltage]]** or **potential difference**, the term "voltage" can be confusing, since as the name "potential difference" suggests it describes only differences in electric potentials. This is why you'll never see it on an SQA Advanced Higher exam paper! Despite you having most likely used the term up until this point in physics, now would be a good time to stop and forget using the term altogether, and reframe what you knew about voltage in the context of **differences in [[School/S6/Physics/Electromagnetism/Electric Potential#Electric Potential\|electric potential]]**. Ah, the joy of SQA Physics :D

#Todo $\large V = Er$
