---
<<<<<<< HEAD
title: 'Mean Free Path'
=======
title: 'mean free path'
>>>>>>> 9468d8de506ee3fe7a32ff32aec5f0ee5a849f86
weight: 5
---
[comment]: <> (katex Header)
{{< katex display >}}{{< /katex >}}
 
# MEAN FREE PATH
 
Usually, the average speed of gas molecules is several hundred meters per second even at room temperature (27°C). The odor from an open perfume bottle takes some time to reach us even if we are closer to the room. The time delay is because the odor molecules cannot travel straight to us as they undergo many collisions with nearby air molecules and move in a zigzag path. This average distance traveled by the molecule between two successive collisions is called the mean free path (λ). We can calculate the mean free path based on kinetic theory.
 
**Expression for Mean Free Path:**
We know from the postulates of kinetic theory that gas molecules are in random motion and collide with each other. Between two successive collisions, a molecule moves along a straight path with uniform velocity. This path is called the mean free path.
 
Consider a system of molecules, each with diameter d. Let n be the number of molecules per unit volume.
 
Assume that only one molecule is in motion and all others are at rest as shown in Figure 9.8.
 
![Alt text](figure9.8.png)
 
If a molecule moves with an average speed v in a time t, the distance traveled is $vt$. In this time t, consider the molecule to move in an imaginary cylinder of volume \\(\pi d^2vt\\). It collides with any molecule whose center is within this cylinder. Therefore, the number of collisions is equal to the number of molecules in the volume of the imaginary cylinder. It is equal to \\(\pi \frac{d^2vtn}{2}\\). The total path length divided by the number of collisions in time $t$ is the mean free path.
 
Mean free path, \\(\lambda = \frac{\text{distance travelled}}{\text{Number of collisions}}\\)

$$\lambda = \frac{vt}{\pi d^2 vt} = \frac{1}{\pi d^2}$$

(9.25)
 
Though we have assumed that only one molecule is moving at a time and other molecules are at rest, in actual practice, all the molecules are in random motion. So the average relative speed of one molecule with respect to other molecules has to be taken into account. After some detailed calculations (you will learn in higher classes), the correct expression for mean free path
 
$$
\lambda = \frac{1}{\sqrt{2} \pi n d^2}
$$ (9.26)
 
The equation (9.26) implies that the mean free path is inversely proportional to the number density. When the number density increases, the molecular collisions increase, decreasing the distance traveled by the molecule before collisions.
 
**Case 1:**
Rearranging the equation (9.26) using 'm' (mass of the molecule):
 
$$
\therefore \lambda = \frac{m}{\sqrt{2}\pi d^2 mn}
$$ (9.27)
 
But mn=mass per unit volume = ρ (density of
the gas)

$$\therefore \lambda = \frac{m}{\sqrt{2}\pi d^2 \rho}$$

Also we know that PV = NkT

$$P = \frac{N}{V}kT = nkT$$

$$\therefore n = \frac{P}{kT}$$

Substituting n= \\(\frac{P}{kT}\\) in equation (9.26), we get

$$\lambda = \frac{kT}{\sqrt{2}\pi d^2 P}$$

(9.28)
 
The equation (9.28) implies the following:
1. Mean free path increases with increasing temperature. As the temperature increases, the average speed of each molecule will increase. It is the reason why the smell of hot sizzling food reaches several meters away than the smell of cold food.
2. Mean free path increases with decreasing pressure of the gas and diameter of the gas molecules.
 
**EXAMPLE 9.6:**

An oxygen molecule is traveling in air at 300 K and 1 atm, and the diameter of an oxygen molecule is 1.2 \\(10^{-10} m.\\) Calculate the mean free path of an oxygen molecule.
 
**Solution:**

From Equation (9.26):
 
$$
\lambda = \frac{1}{\sqrt{2} \pi n d^2}
$$
 
We have to find the number density n. By using the ideal gas law
 
$$n = \frac{N}{V} = \frac{P}{kT} = \frac{101.3 \times 10^3}{1.381 \times 10^{-23} \times 300}$$
 
$$= 2.449 \times 10^{25} \text{molecules/m}^3$$
 
$$\lambda = \frac{1}{\sqrt{2} \times \pi \times 2.449 \times 10^{25} \times (1.2 \times 10^{-10})^2}$$

$$= \frac{1}{15.65 \times 10^5}$$

$$\lambda = 0.63 \times 10^{-6} \text{m}$$
