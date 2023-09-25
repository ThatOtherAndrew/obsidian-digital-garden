---
{"dg-publish":true,"dg-path":"Advanced Higher/Physics/Electromagnetism/Coulomb's Law.md","dg-permalink":"physics/coulombs-law","permalink":"/physics/coulombs-law/","created":"","updated":""}
---

Coulomb's law is an **inverse-square law** which defines the force between two charged particles. It suggests that as the distance between two charged particles doubles, the force between them is four times weaker.

## Formula

---
$$\huge
{\color{red} F} = \frac {
	\color{cyan} Q_1\ Q_2
} {
	4\pi\ {\color{yellow} \varepsilon_0}\ {\color{violet} r}^2
}
$$
---

> [!info] Variable Key
> - $\large \color{red} F$ is **electrostatic force**, in newtons.
> - $\large \color{cyan} Q_1$ and $\large \color{cyan} Q_2$ are the **charges of the respective particles**, in coulombs.
> - $\large \color{yellow} \varepsilon_0$ is the **[[School/S6/Physics/Electromagnetism/Coulomb's Law#Vacuum Permittivity\|vacuum permittivity]]** constant.
> - $\large \color{violet} r$ is the **distance between the particles**, ⚠️ **in metres**.

> [!question] Attract or repel?
> If the calculated electrostatic force is **positive**, then the charged particles are **repelling** each other (since both $\large \color{cyan} Q_1$ and $\large \color{cyan} Q_2$ will have the same sign), and vice versa - if the electrostatic force is **negative**, then the charged particles are **attracting** each other.

### Finding the Distance Between Particles
The above formula can be rearranged to make $\large \color{violet} r$ the subject, as shown below:

> [!warning] The Naïve Approach
> $$\huge
> {\color{violet}r} = \sqrt{ \frac {
> 	\color{cyan} Q_1\ Q_2
> } {
> 	4\pi\ {\color{yellow} \varepsilon_0}\ {\color{red} F}
> } }
> $$

However, this won't work if the charges are attracting each other, as the fraction under the square root would be negative and $\large \color{violet} r$ would be undefined (or *technically* a complex number). To get around this, we have to take the **absolute value** of the numerator:

---
$$\huge
{\color{violet}r} = \sqrt{ \frac {
	| {\color{cyan} Q_1\ Q_2} |
} {
	4\pi\ {\color{yellow} \varepsilon_0}\ {\color{red} F}
} }
$$
---
## Vacuum Permittivity
**Vacuum permittivity**, also known as **permittivity of free space** or the **electric constant**, is a constant which determines how easy it is for an electric field to "penetrate" a vacuum, and consequently how strongly charges influence each other.

Permittivity is represented by the Greek letter epsilon, $\large \varepsilon$.
