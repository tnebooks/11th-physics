---
title: 'kinetic theory of gases'
weight: 9
---

# Unit 9: Kinetic Theory of Gases

"With thermodynamics one can calculate almost everything crudely; with kinetic theory, one can calculate fewer things, but more accurately." - Eugene Wigner

## Learning Objectives

In this unit, the student is exposed to:
- necessity of kinetic theory of gases
- the microscopic origin of pressure and temperature
- correlate the internal energy of the gas and translational kinetic energy of gas molecules
- meaning of degrees of freedom
- calculate the total degrees of freedom for mono atomic, diatomic and triatomic molecules
- law of equipartition of energy
- calculation of the ratio of \( C_{\mathrm{p}} \) and \( C_{\mathrm{v}} \)
- mean free path and its dependence with pressure, temperature and number density
- Brownian motion and its microscopic origin

## 9.1 Kinetic Theory

### 9.1.1 Introduction

Thermodynamics is basically a macroscopic science. We discussed macroscopic parameters like pressure, temperature and volume of thermodynamical systems in unit 8. In this unit we discuss the microscopic origin of pressure and temperature by considering a thermodynamic system as collection of particles or molecules. Kinetic theory relates pressure and temperature to molecular motion of sample of a gas and it is a bridge between Newtonian mechanics and thermodynamics. The present chapter introduces the kinetic nature of gas molecules.

### 9.1.2 Postulates of kinetic theory of gases

Kinetic theory is based on certain assumptions which makes the mathematical treatment simple. None of these assumptions are strictly true yet the model based on these assumptions can be applied to all gases.

1. All the molecules of a gas are identical, elastic spheres.
2. The molecules of different gases are different.
3. The number of molecules in a gas is very large and the average separation between them is larger than size of the gas molecules.
4. The molecules of a gas are in a state of continuous random motion.
5. The molecules collide with one another and also with the walls of the container.
6. These collisions are perfectly elastic so that there is no loss of kinetic energy during collisions.
7. Between two successive collisions, a molecule moves with uniform velocity.
8. The molecules do not exert any force of attraction or repulsion on each other except during collision. The molecules do not possess any potential energy and the energy is wholly kinetic.
9. The collisions are instantaneous. The time spent by a molecule in each collision is very small compared to the time elapsed between two consecutive collisions.
10. These molecules obey Newton's laws of motion even though they move randomly.

## 9.2 Pressure Exerted by a Gas

### 9.2.1 Expression for pressure exerted by a gas

Consider a monoatomic gas of N molecules each having a mass m inside a cubical container of side \( l \) as shown in the Figure 9.1 (a).

**Figure 9.1 (a) Container of gas molecules**

**Figure 9.1 (b) Collision of a molecule with the wall**

The molecules of the gas are in random motion. They collide with each other and also with the walls of the container. As the collisions are elastic in nature, there is no loss of kinetic energy, but a change in momentum occurs.

The molecules of the gas exert pressure on the walls of the container due to collision on it. During each collision, the molecules impart certain momentum to the wall. Due to transfer of momentum, the walls experience a continuous force. The force experienced per unit area of the walls of the container determines the pressure exerted by the gas. It is essential to determine the total momentum transferred by the molecules in a short interval of time.

A molecule of mass m moving with a velocity \( \bar{\nu} \) having components \( (v_{x}, v_{y}, v_{z}) \) hits the right side wall. Since we have assumed that the collision is elastic, the particle rebounds with same speed and its x-component is reversed. This is shown in the Figure 9.1 (b). The components of velocity of the molecule after collision are \( (- \nu_{x}, \nu_{y}, \nu_{z}) \).

The x-component of momentum of the molecule before collision \( = m\nu_{x} \)

The x-component of momentum of the molecule after collision \( = - mv_{x} \)

The change in momentum of the molecule in x direction

\( = \) Final momentum - initial momentum \( = - mv_{x} - mv_{x} = - 2mv_{x} \)

According to law of conservation of linear momentum, the change in momentum of the wall \( = 2mv_{x} \)

**Figure 9.2 Number of molecules hitting the wall**

The number of molecules hitting the right side wall in a small interval of time \( \Delta t \) is calculated as follows.

The molecules within the distance of \( v_{x}\Delta t \) from the right side wall and moving towards the right will hit the wall in the time interval \( \Delta t \). This is shown in the Figure 9.2. The number of molecules that will hit the right side wall in a time interval \( \Delta t \) is equal to the product of volume \( (Av_{x}\Delta t) \) and number density of the molecules \( (n) \). Here \( A \) is area of the wall and \( n \) is number of molecules per unit volume \( \left(\frac{N}{V}\right) \). We have assumed that the number density is the same throughout the cube.

Not all the n molecules will move to the right, therefore on an average only half of the n molecules move to the right and the other half moves towards left side.

The number of molecules that hit the right side wall in a time interval \( \Delta t \)

\[
= \frac{n}{2} A v_{x} \Delta t
\]

In the same interval of time \( \Delta t \), the total momentum transferred by the molecules

\[
\Delta p = \frac{n}{2} A v_{x} \Delta t \times 2 m v_{x} = A v_{x}^{2} m n \Delta t
\]

From Newton's second law, the change in momentum in a small interval of time gives rise to force.

The force exerted by the molecules on the wall (in magnitude)

\[
\mathrm{F} = \frac{\Delta p}{\Delta t} = n m A v_{x}^{2}
\]

Pressure, \( \mathrm{P} = \) force divided by the area of the wall

\[
\mathrm{P} = \frac{F}{A} = n m v_{x}^{2}
\]

Since all the molecules are moving completely in random manner, they do not have same speed. So we can replace the term \( v_{x}^{2} \) by the average \( \overline{v_{x}^{2}} \) in the above equation.

\[
P = n m \overline{v_{x}^{2}}
\]

Since the gas is assumed to move in random direction, it has no preferred direction of motion (the effect of gravity on the molecules is neglected). It implies that the molecule has same average speed in all the three direction. So, \( \overline{v_{x}^{2}} = \overline{v_{y}^{2}} = \overline{v_{z}^{2}} \). The mean square speed is written as

\[
\overline{v^{2}} = \overline{v_{x}^{2}} + \overline{v_{y}^{2}} + \overline{v_{z}^{2}} = 3 \overline{v_{x}^{2}}
\]
\[
\overline{v_{x}^{2}} = \frac{1}{3} \overline{v^{2}}
\]

Using this, we get

\[
P = \frac{1}{3} n m \overline{v^{2}} \quad \text{or} \quad P = \frac{1}{3} \frac{N}{V} m \overline{v^{2}} \quad \left[ n = \frac{N}{V} \right]
\]

The following inference can be made from the above equation. The pressure exerted by the molecules depends on

(i) Number density \( n = \frac{N}{V} \). It implies that if the number density increases then pressure will increase. For example when we pump air inside the cycle tyre or car tyre essentially the number density increases and as a result the pressure increases.

(ii) Mass of the molecule: Since the pressure arises due to momentum transfer to the wall, larger mass will have larger momentum for a fixed speed. As a result the pressure will increase.

(iii) Mean square speed: For a fixed mass if we increase the speed, the average speed will also increase. As a result the pressure will increase.

For simplicity the cubical container is taken into consideration. The above result is true for any shape of the container as the area A does not appear in the final expression. Hence the pressure exerted by gas molecules on the wall is independent of area of the wall (A).

### 9.2.2 Kinetic interpretation of temperature

To understand the microscopic origin of temperature, rewrite the equation

\[
P = \frac{1}{3} \frac{N}{V} m \overline{v^{2}}
\]
\[
PV = \frac{1}{3} N m \overline{v^{2}}
\]

Comparing this with ideal gas equation \( PV = NkT \)

\[
NkT = \frac{1}{3} N m \overline{v^{2}}
\]
\[
kT = \frac{1}{3} m \overline{v^{2}}
\]

Multiply the above equation by \( 3/2 \) on both sides,

\[
\frac{3}{2} kT = \frac{1}{2} m \overline{v^{2}}
\]

R.H.S of the equation is called average kinetic energy of a single molecule \( (\overline{KE}) \).

The average kinetic energy per molecule

\[
\overline{KE} = \epsilon = \frac{3}{2} kT
\]

This implies that the temperature of a gas is a measure of the average translational kinetic energy per molecule of the gas.

Equation is a very important result from kinetic theory of gas. We can infer the following from this equation.

(i) The average kinetic energy of the molecule is directly proportional to absolute temperature of the gas. The equation gives the connection between the macroscopic world (temperature) to microscopic world (motion of molecules).

(ii) The average kinetic energy of each molecule depends only on temperature of the gas not on mass of the molecule. In other words, if the temperature of an ideal gas is measured using thermometer, the average kinetic energy of each molecule can be calculated without seeing the molecule through naked eye.

By multiplying the total number of gas molecules with average kinetic energy of each molecule, the internal energy of the gas is obtained.

Internal energy of ideal gas \( U = N \left( \frac{1}{2} m \overline{v^{2}} \right) \)

By using the above equation

\[
U = \frac{3}{2} NkT
\]

From this equation, we understand that the internal energy of an ideal gas depends only on absolute temperature and is independent of pressure and volume.

**EXAMPLE 9.1**

A football at \( 27^{\circ}C \) has 0.5 mole of air molecules. Calculate the internal energy of air in the ball.

**Solution**

The internal energy of ideal gas \( = \frac{3}{2} NkT \)

The number of air molecules is given in terms of number of moles so, rewrite the expression as follows

\[
U = \frac{3}{2} \mu RT
\]

Since \( Nk = \mu R \). Here \( \mu \) is number of moles.

Gas constant \( R = 8.31 \, \frac{J}{mol \cdot K} \)

Temperature \( T = 273 + 27 = 300 \, K \)

\[
U = \frac{3}{2} \times 0.5 \times 8.31 \times 300 = 1869.75 \, J
\]

This is approximately equivalent to the kinetic energy of a man of \( 57 \, \text{kg} \) running with a speed of \( 8 \, \text{m} \, \text{s}^{-1} \).

### 9.2.3 Relation between pressure and mean kinetic energy

From earlier section, the internal energy of the gas is given by

\[
U = \frac{3}{2} NkT
\]

The above equation can also be written as

\[
U = \frac{3}{2} PV \quad (\text{since } PV = NkT)
\]
\[
P = \frac{2}{3} \frac{U}{V} = \frac{2}{3} u
\]

From the equation, we can state that the pressure of the gas is equal to two thirds of internal energy per unit volume or internal energy density \( \left(u = \frac{U}{V}\right) \).

Writing pressure in terms of mean kinetic energy density using the earlier equation

\[
P = \frac{1}{3} n m \overline{v^{2}} = \frac{1}{3} \rho \overline{v^{2}}
\]

where \( \rho = n m = \) mass density (Note n is number density)

Multiply and divide R.H.S by 2, we get

\[
P = \frac{2}{3} \left( \frac{1}{2} \rho \overline{v^{2}} \right) = \frac{2}{3} \overline{KE}
\]

### 9.2.4 Some elementary deductions from kinetic theory of gases

**Boyle's law:**

From earlier, we know that \( PV = \frac{2}{3} U \). But the internal energy of an ideal gas is equal to N times the average kinetic energy \( (\epsilon) \) of each molecule.

\[
U = N\epsilon
\]

For a fixed temperature, the average translational kinetic energy \( \epsilon \) will remain constant. It implies that

\[
PV = \frac{2}{3} N\epsilon \quad \text{Thus} \quad PV = \text{constant}
\]

Therefore, pressure of a given gas is inversely proportional to its volume provided the temperature remains constant. This is Boyle's law.

**Charles' law:**

From the equation, we get \( PV = \frac{2}{3} U \). For a fixed pressure, the volume of the gas is proportional to internal energy of the gas or average kinetic energy of the gas and the average kinetic energy is directly proportional to absolute temperature. It implies that

\[
V \propto T \quad \text{or} \quad \frac{V}{T} = \text{constant}
\]

This is Charles' law.

**Avogadro's law:**

This law states that at constant temperature and pressure, equal volumes of all gases contain the same number of molecules. For two different gases at the same temperature and pressure, according to kinetic theory of gases,

From the pressure equation

\[
P = \frac{1}{3} \frac{N_1}{V} m_1 \overline{v_1^2} = \frac{1}{3} \frac{N_2}{V} m_2 \overline{v_2^2}
\]

where \( \overline{v_1^2} \) and \( \overline{v_2^2} \) are the mean square speed for two gases and \( N_1 \) and \( N_2 \) are the number of gas molecules in two different gases.

At the same temperature, average kinetic energy per molecule is the same for two gases.

\[
\frac{1}{2} m_1 \overline{v_1^2} = \frac{1}{2} m_2 \overline{v_2^2}
\]

Dividing the first equation by the second we get \( N_1 = N_2 \).

This is Avogadro's law. It is sometimes referred to as Avogadro's hypothesis or Avogadro's Principle.

### 9.2.5 Root mean square speed \( (v_{rms}) \)

Root mean square speed \( (v_{rms}) \) is defined as the square root of the mean of the square of speeds of all molecules. It is denoted by \( v_{\mathrm{rms}} = \sqrt{\overline{v^2}} \).

From earlier equation can be re-written as,

\[
\text{mean square speed } \overline{v^2} = \frac{3kT}{m}
\]

root mean square speed,

\[
v_{\mathrm{rms}} = \sqrt{\frac{3kT}{m}} = 1.73 \sqrt{\frac{kT}{m}}
\]

From the equation we infer the following

(i) rms speed is directly proportional to square root of the temperature and inversely proportional to square root of mass of the molecule. At a given temperature the molecules of lighter mass move faster on an average than the molecules with heavier masses.

Example: Lighter molecules like hydrogen and helium have high \( v_{rms} \) than heavier molecules such as oxygen and nitrogen at the same temperature.

(ii) Increasing the temperature will increase the r.m.s speed of molecules.

We can also write the \( v_{rms} \) in terms of gas constant R. The above equation can be rewritten as follows

\[
v_{rms} = \sqrt{\frac{3 N_A kT}{N_A m}} \quad \text{Where } N_A \text{ is Avogadro number}
\]

Since \( N_A k = R \) and \( N_A m = M \) (molar mass)

The root mean square speed or r.m.s speed

\[
v_{rms} = \sqrt{\frac{3RT}{M}}
\]

The pressure equation can also be written in terms of rms speed \( P = \frac{1}{3} n m v_{rms}^{2} \) since \( v_{rms}^{2} = \overline{v^{2}} \).

**Impact of \( v_{rms} \) in nature:**

**1. Moon has no atmosphere.** The escape speed of gases on the surface of Moon is much less than the root mean square speeds of gases due to low gravity. Due to this all the gases escape from the surface of the Moon.

**2. No hydrogen in Earth's atmosphere.** As the root mean square speed of hydrogen is much greater than that of nitrogen, it easily escapes from the earth's atmosphere. In fact, the presence of nonreactive nitrogen instead of highly combustible hydrogen deters many disastrous consequences.

**EXAMPLE 9.2**

A room contains oxygen and hydrogen molecules in the ratio 3:1. The temperature of the room is \( 27^{\circ}C \). The molar mass of \( O_2 \) is \( 32 \, \text{g mol}^{-1} \) and of \( H_2 \) is \( 2 \, \text{g mol}^{-1} \). The value of gas constant R is \( 8.32 \, \text{J mol}^{-1} \text{K}^{-1} \).

Calculate

(a) rms speed of oxygen and hydrogen molecule

(b) Average kinetic energy per oxygen molecule and per hydrogen molecule

(c) Ratio of average kinetic energy of oxygen molecules and hydrogen molecules

**Solution**

(a) Absolute Temperature \( \mathrm{T} = 27^{\circ} \mathrm{C} = 27 + 273 = 300 \, \mathrm{K} \)

Gas constant \( \mathrm{R} = 8.32 \, \mathrm{J \, mol^{-1} \, K^{-1}} \)

For Oxygen molecule: Molar mass \( \mathrm{M} = 32 \, \mathrm{g} = 32 \times 10^{-3} \, \mathrm{kg \, mol^{-1}} \)

\[
\mathrm{rms \, speed} \, v_{rms} = \sqrt{\frac{3RT}{M}} = \sqrt{\frac{3 \times 8.32 \times 300}{32 \times 10^{-3}}} = 483.73 \, \text{m s}^{-1} \approx 484 \, \text{m s}^{-1}
\]

For Hydrogen molecule: Molar mass \( \mathrm{M} = 2 \times 10^{-3} \, \mathrm{kg \, mol^{-1}} \)

\[
\mathrm{rms \, speed} \, v_{rms} = \sqrt{\frac{3RT}{M}} = \sqrt{\frac{3 \times 8.32 \times 300}{2 \times 10^{-3}}} = 1934 \, \text{m s}^{-1}
\]

Note that the rms speed is inversely proportional to \( \sqrt{\mathrm{M}} \) and the molar mass of oxygen is 16 times higher than molar mass of hydrogen. It implies that the rms speed of hydrogen is 4 times greater than rms speed of oxygen at the same temperature. \( \frac{1934}{484} \approx 4 \).

(b) The average kinetic energy per molecule is \( \frac{3}{2} kT \). It depends only on absolute temperature of the gas and is independent of the nature of molecules. Since both the gas molecules are at the same temperature, they have the same average kinetic energy per molecule. \( k \) is Boltzmann constant.

\[
\frac{3}{2} kT = \frac{3}{2} \times 1.38 \times 10^{-23} \times 300 = 6.21 \times 10^{-21} \, \text{J}
\]

(c) Average kinetic energy of total oxygen molecules \( = \frac{3}{2} N_o kT \) where \( N_o \) - number of oxygen molecules in the room.

Average kinetic energy of total hydrogen molecules \( = \frac{3}{2} N_H kT \) where \( N_H \) - number of hydrogen molecules in the room.

It is given that the number of oxygen molecules is 3 times more than number of hydrogen molecules in the room. So the ratio of average kinetic energy of oxygen molecules with average kinetic energy of hydrogen molecules is 3:1.

### 9.2.6 Mean (or) average speed \( (\overline{v}) \)

It is defined as the mean (or) average of all the speeds of molecules.

If \( \nu_{1}, \nu_{2}, \nu_{3}, \ldots, \nu_{N} \) are the individual speeds of molecules then

\[
\overline{\nu} = \frac{\nu_{1} + \nu_{2} + \nu_{3} + \ldots + \nu_{n}}{N} = \sqrt{\frac{8RT}{\pi M}} = \sqrt{\frac{8kT}{\pi m}}
\]

Here M - Molar Mass and m - mass of the molecule.

\[
\overline{\nu} = 1.60 \sqrt{\frac{kT}{m}}
\]

### 9.2.7 Most probable speed \( (V_{mp}) \)

It is defined as the speed acquired by most of the molecules of the gas.

\[
\nu_{mp} = \sqrt{\frac{2RT}{M}} = \sqrt{\frac{2kT}{m}}
\]
\[
\nu_{mp} = 1.41 \sqrt{\frac{kT}{m}}
\]

The derivation of the above equations is beyond the scope of the book.

**Comparison of \( v_{rms}, \overline{\nu} \) and \( \nu_{mp} \)**

Among the speeds \( v_{rms} \) is the largest and \( \nu_{mp} \) is the least

\[
v_{rms} > \overline{\nu} > \nu_{mp}
\]

Ratio-wise,

\[
v_{rms} : \overline{\nu} : \nu_{mp} = \sqrt{3} : \sqrt{\frac{8}{\pi}} : \sqrt{2} = 1.732 : 1.6 : 1.414
\]

**EXAMPLE 9.3**

Ten particles are moving at the speed of 2, 3, 4, 5, 5, 5, 6, 6, 7 and \( 9 \, \text{m} \, \text{s}^{-1} \). Calculate rms speed, average speed and most probable speed.

**Solution**

The average speed \( \overline{\nu} = \frac{2 + 3 + 4 + 5 + 5 + 5 + 6 + 6 + 7 + 9}{10} = 5.2 \, \text{m s}^{-1} \)

To find the rms speed, first calculate the mean square speed \( \overline{\nu^{2}} \)

\[
\overline{\nu^{2}} = \frac{2^{2} + 3^{2} + 4^{2} + 5^{2} + 5^{2} + 5^{2} + 6^{2} + 6^{2} + 7^{2} + 9^{2}}{10} = 30.6 \, \text{m}^{2} \text{s}^{-2}
\]

The rms speed

\[
\nu_{rms} = \sqrt{\overline{\nu^{2}}} = \sqrt{30.6} = 5.53 \, \text{m s}^{-1}
\]

The most probable speed is \( 5 \, \text{m s}^{-1} \) because three of the particles have that speed.

**EXAMPLE 9.4**

Calculate the rms speed, average speed and the most probable speed of 1 mole of hydrogen molecules at \( 300 \, \mathrm{K} \). Neglect the mass of electron.

**Solution**

The hydrogen atom has one proton and one electron. The mass of electron is negligible compared to the mass of proton. Mass of one proton \( = 1.67 \times 10^{-27} \, \text{kg} \). One hydrogen molecule \( = 2 \) hydrogen atoms \( = 2 \times 1.67 \times 10^{-27} \, \text{kg} \).

The average speed

\[
\bar{\nu} = \sqrt{\frac{8kT}{\pi m}} = 1.60 \sqrt{\frac{kT}{m}} = 1.60 \sqrt{\frac{(1.38 \times 10^{-23}) \times 300}{2(1.67 \times 10^{-27})}} = 1.78 \times 10^{3} \, \text{m s}^{-1}
\]

(Boltzmann Constant \( k = 1.38 \times 10^{-23} \, \text{J K}^{-1} \))

The rms speed

\[
\nu_{rms} = \sqrt{\frac{3kT}{m}} = 1.73 \sqrt{\frac{kT}{m}} = 1.73 \sqrt{\frac{(1.38 \times 10^{-23}) \times 300}{2(1.67 \times 10^{-27})}} = 1.93 \times 10^{3} \, \text{m s}^{-1}
\]

Most probable speed

\[
\nu_{mp} = \sqrt{\frac{2kT}{m}} = 1.41 \sqrt{\frac{kT}{m}} = 1.41 \sqrt{\frac{(1.38 \times 10^{-23}) \times 300}{2(1.67 \times 10^{-27})}} = 1.57 \times 10^{3} \, \text{m s}^{-1}
\]

Note that \( \nu_{rms} > \bar{\nu} > \nu_{mp} \).

### 9.2.8 Maxwell-Boltzmann speed distribution function

In a classroom, the air molecules are moving in random directions. The speed of each molecule is not the same even though macroscopic parameters like temperature and pressure are fixed. Each molecule collides with every other molecule and they exchange their speed. In the previous section we calculated the rms speed of each molecule and not the speed of each molecule which is rather difficult. In this scenario we can find the number of gas molecules that move with the speed of \( 5 \, \text{m s}^{-1} \) to \( 10 \, \text{m s}^{-1} \) or \( 10 \, \text{m s}^{-1} \) to \( 15 \, \text{m s}^{-1} \) etc. In general our interest is to find how many gas molecules have the range of speed from \( \nu \) to \( \nu + d\nu \). This is given by Maxwell's speed distribution function.

\[
N_{\nu} = 4\pi N \left( \frac{m}{2\pi kT} \right)^{\frac{3}{2}} \nu^{2} e^{-\frac{m\nu^{2}}{2kT}}
\]

The above expression is graphically shown as follows

**Figure 9.3 Maxwell's molecular speed distribution**

From the Figure 9.3, it is clear that, for a given temperature the number of molecules having lower speed increases parabolically \( (\nu^{2}) \) but decreases exponentially \( (e^{-\frac{m\nu^{2}}{2kT}}) \) after reaching most probable speed. The rms speed, average speed and most probable speed are indicated in the Figure 9.3. It can be seen that the rms speed is greatest among the three.

## 9.3 Degrees of Freedom

The minimum number of independent coordinates needed to specify the position and configuration of a thermodynamical system in space is called the degrees of freedom of the system.

1. A free particle moving along x-axis needs only one coordinate to specify it completely. So its degree of freedom is one.
2. Similarly a particle moving over a plane has two degrees of freedom.
3. A particle moving in space has three degrees of freedom.

Suppose if we have N number of gas molecules in the container, then the total number of degrees of freedom is \( f = 3N \).

But, if the system has \( q \) number of constraints (restrictions in motion) then the degrees of freedom decreases and it is equal to \( f = 3N - q \) where N is the number of particles.

### 9.3.2 Monoatomic molecule

A monoatomic molecule by virtue of its nature has only three translational degrees of freedom.

Therefore \( f = 3 \)

Example: Helium, Neon, Argon

### 9.3.3 Diatomic molecule

There are two cases.

**1. At Normal temperature**

A molecule of a diatomic gas consists of two atoms bound to each other by a force of attraction. Physically the molecule can be regarded as a system of two point masses fixed at the ends of a massless elastic spring.

The center of mass lies in the center of the diatomic molecule. So, the motion of the center of mass requires three translational degrees of freedom (figure 9.5 a). In addition, the diatomic molecule can rotate about three mutually perpendicular axes (figure 9.5 b). But the moment of inertia about its own axis of rotation is negligible (about y axis in the figure 9.5). Therefore, it has only two rotational degrees of freedom (one rotation is about Z axis and another rotation is about X axis). Therefore totally there are five degrees of freedom.

\[
f = 5
\]

**Figure 9.5 Degree of freedom of diatomic molecule**

**2. At High Temperature**

At a very high temperature such as \( 5000 \, \text{K} \) the diatomic molecules possess additional two degrees of freedom due to vibrational motion [one due to kinetic energy of vibration and the other is due to potential energy] (Figure 9.5c). So totally there are seven degrees of freedom.

\[
f = 7
\]

Examples: Hydrogen, Nitrogen, Oxygen.

### 9.3.4 Triatomic molecules

There are two cases.

**Linear triatomic molecule**

In this type, two atoms lie on either side of the central atom as shown in the Figure 9.6

**Figure 9.6 A linear triatomic molecule**

Linear triatomic molecule has three translational degrees of freedom. It has two rotational degrees of freedom because it is similar to diatomic molecule except there is an additional atom at the center. At normal temperature, linear triatomic molecule will have five degrees of freedom. At high temperature it has two additional vibrational degrees of freedom. So a linear triatomic molecule has seven degrees of freedom.

Example: Carbon dioxide.

**Non-linear triatomic molecule**

In this case, the three atoms lie at the vertices of a triangle as shown in the Figure 9.7

**Figure 9.7 A non-linear triatomic molecule**

It has three translational degrees of freedom and three rotational degrees of freedom about three mutually orthogonal axes. The total degrees of freedom, \( f = 6 \)

Example: Water, Sulphur dioxide.

## 9.4 Law of Equipartition of Energy

We have seen in Section 9.2.1 that the average kinetic energy of a molecule moving in x direction is \( \frac{1}{2} m v_{x}^{2} = \frac{1}{2} kT \).

Similarly, when the motion is in y direction, \( \frac{1}{2} m v_{y}^{2} = \frac{1}{2} kT \) and for the motion along z direction, \( \frac{1}{2} m v_{z}^{2} = \frac{1}{2} kT \).

According to kinetic theory, the average kinetic energy of system of molecules in thermal equilibrium at temperature \( T \) is uniformly distributed to all degrees of freedom (x or y or z directions of motion) so that each degree of freedom will get \( \frac{1}{2} kT \) of energy. This is called law of equipartition of energy.

Average kinetic energy of a monatomic molecule (with \( f = 3 \)) \( = 3 \times \frac{1}{2} kT = \frac{3}{2} kT \)

Average kinetic energy of diatomic molecule at low temperature (with \( f = 5 \)) \( = 5 \times \frac{1}{2} kT = \frac{5}{2} kT \)

Average kinetic energy of a diatomic molecule at high temperature (with \( f = 7 \)) \( = 7 \times \frac{1}{2} kT = \frac{7}{2} kT \)

Average kinetic energy of linear triatomic molecule (with \( f = 7 \)) \( = 7 \times \frac{1}{2} kT = \frac{7}{2} kT \)

Average kinetic energy of nonlinear triatomic molecule (with \( f = 6 \)) \( = 6 \times \frac{1}{2} kT = 3kT \)

### 9.4.1 Application of law of equipartition energy in specific heat of a gas

Meyer's relation \( C_{p} - C_{v} = R \) connects the two specific heats for one mole of an ideal gas.

Equipartition law of energy is used to calculate the value of \( C_{p} - C_{v} \) and the ratio between them \( \gamma = \frac{C_{p}}{C_{v}} \). Here \( \gamma \) is called adiabatic exponent.

**i) Monatomic molecule**

Average kinetic energy of a molecule \( = \left[ \frac{3}{2} kT \right] \)

Total energy of a mole of gas \( = \frac{3}{2} kT \times N_{A} = \frac{3}{2} RT \)

For one mole, the molar specific heat at constant volume \( C_{v} = \frac{dU}{dT} = \frac{d}{dT} \left[ \frac{3}{2} RT \right] \)

\[
C_{v} = \frac{3}{2} R
\]
\[
C_{p} = C_{v} + R = \frac{3}{2} R + R = \frac{5}{2} R
\]

The ratio of specific heats,

\[
\gamma = \frac{C_{p}}{C_{v}} = \frac{\frac{5}{2}R}{\frac{3}{2}R} = \frac{5}{3} = 1.67
\]

**ii) Diatomic molecule**

Average kinetic energy of a diatomic molecule at low temperature \( = \frac{5}{2} kT \)

Total energy of one mole of gas \( = \frac{5}{2} kT \times N_{A} = \frac{5}{2} RT \)

(Here, the total energy is purely kinetic)

For one mole Specific heat at constant volume

\[
C_{v} = \frac{dU}{dT} = \frac{5}{2} R
\]
\[
C_{p} = C_{v} + R = \frac{5}{2} R + R = \frac{7}{2} R
\]
\[
\gamma = \frac{C_{p}}{C_{v}} = \frac{\frac{7}{2}R}{\frac{5}{2}R} = \frac{7}{5} = 1.40
\]

Energy of a diatomic molecule at high temperature is equal to \( \frac{7}{2} RT \)

\[
C_{v} = \frac{dU}{dT} = \frac{7}{2} R
\]
\[
C_{p} = C_{v} + R = \frac{7}{2} R + R = \frac{9}{2} R
\]
\[
\gamma = \frac{C_{p}}{C_{v}} = \frac{\frac{9}{2}R}{\frac{7}{2}R} = \frac{9}{7} = 1.28
\]

Note that the \( C_{v} \) and \( C_{p} \) are higher for diatomic molecules than the monoatomic molecules. It implies that to increase the temperature of diatomic gas molecules by \( 1^{\circ}C \) it requires more heat energy than monoatomic molecules.

**iii) Triatomic molecule**

**a) Linear molecule**

Energy of one mole \( = \frac{7}{2} kT \times N_{A} = \frac{7}{2} RT \)

\[
C_{v} = \frac{dU}{dT} = \frac{7}{2} R
\]
\[
C_{p} = C_{v} + R = \frac{7}{2} R + R = \frac{9}{2} R
\]
\[
\gamma = \frac{C_{p}}{C_{v}} = \frac{\frac{9}{2}R}{\frac{7}{2}R} = \frac{9}{7} = 1.28
\]

**b) Non-linear molecule**

Energy of a mole \( = \frac{6}{2} kT \times N_{A} = 3RT \)

\[
C_{v} = \frac{dU}{dT} = 3R
\]
\[
C_{p} = C_{v} + R = 3R + R = 4R
\]
\[
\gamma = \frac{C_{p}}{C_{v}} = \frac{4R}{3R} = \frac{4}{3} = 1.33
\]

Note that according to kinetic theory model of gases the specific heat capacity at constant volume and constant pressure are independent of temperature. But in reality it is not sure. The specific heat capacity varies with the temperature.

**EXAMPLE 9.5**

Find the adiabatic exponent \( \gamma \) for mixture of \( \mu_{1} \) moles of monoatomic gas and \( \mu_{2} \) moles of a diatomic gas at normal temperature \( (27^{\circ}C) \).

**Solution**

The specific heat of one mole of a monoatomic gas \( C_{V} = \frac{3}{2} R \)

For \( \mu_{1} \) mole, \( C_{V} = \frac{3}{2} \mu_{1} R \), \( C_{P} = \frac{5}{2} \mu_{1} R \)

The specific heat of one mole of a diatomic gas \( C_{V} = \frac{5}{2} R \)

For \( \mu_{2} \) mole, \( C_{V} = \frac{5}{2} \mu_{2} R \), \( C_{P} = \frac{7}{2} \mu_{2} R \)

The specific heat of the mixture at constant volume \( C_{V} = \frac{3}{2} \mu_{1} R + \frac{5}{2} \mu_{2} R \)

The specific heat of the mixture at constant pressure \( C_{P} = \frac{5}{2} \mu_{1} R + \frac{7}{2} \mu_{2} R \)

The adiabatic exponent \( \gamma = \frac{C_{P}}{C_{V}} = \frac{5\mu_{1} + 7\mu_{2}}{3\mu_{1} + 5\mu_{2}} \)

## 9.5 Mean Free Path

Usually the average speed of gas molecules is several hundred meters per second even at room temperature \( (27^{\circ}C) \). Odour from an open perfume bottle takes some time to reach us even if we are closer to the room. The time delay is because the odour of the molecules cannot travel straight to us as it undergoes a lot of collisions with the nearby air molecules and moves in a zigzag path. This average distance travelled by the molecule between two successive collisions is called mean free path \( (\lambda) \). We can calculate the mean free path based on kinetic theory.

**Expression for mean free path**

We know from postulates of kinetic theory that the molecules of a gas are in random motion and they collide with each other. Between two successive collisions, a molecule moves with uniform velocity. The mean free path of a gas molecule is given by

\[
\lambda = \frac{1}{\sqrt{2} \pi n d^{2}}
\]

where \( n \) is the number density and \( d \) is the diameter of the molecule.

Using ideal gas law \( n = \frac{P}{kT} \), we can also write

\[
\lambda = \frac{kT}{\sqrt{2} \pi d^{2} P}
\]

**EXAMPLE 9.6**

An oxygen molecule is travelling in air at \( 300 \, \text{K} \) and 1 atm, and the diameter of oxygen molecule is \( 1.2 \times 10^{-10} \, \text{m} \). Calculate the mean free path of oxygen molecule.

**Solution**

\[
\lambda = \frac{1}{\sqrt{2} \pi n d^{2}}
\]

We have to find the number density \( n \). By using ideal gas law

\[
n = \frac{N}{V} = \frac{P}{kT} = \frac{101.3 \times 10^{3}}{1.381 \times 10^{-23} \times 300} = 2.449 \times 10^{25} \, \text{molecules/m}^{3}
\]

\[
\lambda = \frac{1}{\sqrt{2} \times \pi \times 2.449 \times 10^{25} \times (1.2 \times 10^{-10})^{2}} = \frac{1}{15.65 \times 10^{5}} = 0.63 \times 10^{-6} \, \text{m}
\]

## 9.6 Brownian Motion

In 1827, Robert Brown, a botanist reported that grains of pollen suspended in a liquid moves randomly from one place to other. The random (Zig-Zag path) motion of pollen suspended in a liquid is called Brownian motion. In fact we can observe the dust particle in water moving in random directions. This discovery puzzled scientists for long time. There were a lot of explanations for pollen or dust to move in random directions but none of these explanations were found adequate. After a systematic study, Wiener and Gouy proposed that Brownian motion is due to the bombardment of suspended particles by molecules of the surrounding fluid. But during \( 19^{\text{th}} \) century people did not accept that every matter is made up of small atoms or molecules. In the year 1905, Einstein gave systematic theory of Brownian motion based on kinetic theory and he deduced the average size of molecules.

According to kinetic theory, any particle suspended in a liquid or gas is continuously bombarded from all the directions so that the mean free path is almost negligible. This leads to the motion of the particles in a random and zig-zag manner as shown in Figure 9.9. But when we put our hand in water it causes no random motion because the mass of our hand is so large that the momentum transferred by the molecular collision is not enough to move our hand.

**Figure 9.9 Particles in Brownian motion**

**Factors affecting Brownian Motion**

1. Brownian motion increases with increasing temperature.
2. Brownian motion decreases with bigger particle size, high viscosity and density of the liquid (or) gas.

## Summary

- Kinetic theory explains the microscopic origin of macroscopic parameters like temperature, pressure.
- The pressure exerted on the walls of gas container is due to the momentum imparted by the gas molecules on the walls. The pressure \( P = \frac{1}{3} n m \overline{v^{2}} \). The pressure is directly proportional to the number density, mass of molecule and mean square speed.
- The temperature of a gas is a measure of the average translational kinetic energy per molecule of the gas. The average kinetic energy per molecule is directly proportional to absolute temperature of gas and independent of nature of molecules.
- The pressure is also equal to \( 2/3 \) of internal energy per unit volume.
- The rms speed of gas molecules \( v_{rms} = \sqrt{\frac{3kT}{m}} = 1.73 \sqrt{\frac{kT}{m}} \)
- The average speed of gas molecules \( \bar{\nu} = \sqrt{\frac{8kT}{\pi m}} = 1.60 \sqrt{\frac{kT}{m}} \)
- The most probable speed of gas molecules \( \nu_{mp} = \sqrt{\frac{2kT}{m}} = 1.41 \sqrt{\frac{kT}{m}} \)
- Among the speeds \( v_{rms} \) is the largest and \( \nu_{mp} \) is the least: \( v_{rms} > \bar{\nu} > \nu_{mp} \)
- The number of gas molecules in the range of speed \( \nu \) to \( \nu + d\nu \) is given by Maxwell-Boltzmann distribution \( N_{\nu} d\nu = 4\pi N \left( \frac{m}{2\pi kT} \right)^{\frac{3}{2}} \nu^{2} e^{\frac{m\nu^{2}}{2kT}} d\nu \)
- The minimum number of independent coordinates needed to specify the position and configuration of a thermodynamical system in space is called the degrees of freedom of the system.
- If a sample of gas has N molecules, then the total degrees of freedom \( f = 3N \). If there are q number of constraints then total degrees of freedom \( f = 3N - q \)
- For a monoatomic molecule, \( f = 3 \)
- For a diatomic molecule (at normal temperature), \( f = 5 \)
- For a diatomic molecule (at high temperature), \( f = 7 \)
- For a triatomic molecule (linear type), \( f = 7 \)
- For a triatomic molecule (non-linear type), \( f = 6 \)
- The average kinetic energy of sample of gas is equally distributed to all the degrees of freedom. It is called law of equipartition of energy. Each degree of freedom will get \( \frac{1}{2} kT \) energy.
- The ratio of molar specific heat at constant pressure and constant volume of a gas \( \left[ \gamma = \frac{C_p}{C_v} \right] \)

For
- Monoatomic molecule: 1.67
- Diatomic molecule (Normal temperature): 1.40
- Diatomic molecule (High temperature): 1.28
- Triatomic molecule (Linear type): 1.28
- Triatomic molecule (Non-linear type): 1.33

- The mean free path \( \lambda = \frac{kT}{\sqrt{2} \pi d^{2} P} \). The mean free path is directly proportional to temperature and inversely proportional to size of the molecule and pressure of the molecule.
- The Brownian motion explained by Albert Einstein is based on kinetic theory. It proves the reality of atoms and molecules.

## Multiple Choice Questions

1. A particle of mass m is moving with speed \( u \) in a direction which makes \( 60^{\circ} \) with respect to x axis. It undergoes elastic collision with the wall. What is the change in momentum in x and y direction?

   (a) \( \Delta p_{x} = -mu, \Delta p_{y} = 0 \)
   (b) \( \Delta p_{x} = -2mu, \Delta p_{y} = 0 \)
   (c) \( \Delta p_{x} = 0, \Delta p_{y} = mu \)
   (d) \( \Delta p_{x} = mu, \Delta p_{y} = 0 \)

   **Answer: a**

2. A sample of ideal gas is at equilibrium. Which of the following quantity is zero?
   (a) rms speed
   (b) average speed
   (c) average velocity
   (d) most probable speed

   **Answer: c**

3. An ideal gas is maintained at constant pressure. If the temperature of an ideal gas increases from \( 100 \, \text{K} \) to \( 10000 \, \text{K} \) then the rms speed of the gas molecules
   (a) increases by 5 times
   (b) increases by 10 times
   (c) remains same
   (d) increases by 7 times

   **Answer: b**

4. Two identically sized rooms A and B are connected by an open door. If the room A is air conditioned such that its temperature is \( 4^{\circ}C \) lesser than room B, which room has more air in it?
   (a) Room A
   (b) Room B
   (c) Both room has same air
   (d) Cannot be determined

   **Answer: a**

5. The average translational kinetic energy of gas molecules depends on
   (a) number of moles and T
   (b) only on T
   (c) P and T
   (d) P only

   **Answer: a**

6. If the internal energy of an ideal gas U and volume V are doubled then the pressure
   (a) doubles
   (b) remains same
   (c) halves
   (d) quadruples

   **Answer: b**

7. The ratio \( \gamma = \frac{C_p}{C_v} \) for a gas mixture consisting of 8 g of helium and 16 g of oxygen is
   (a) 23/15
   (b) 15/23
   (c) 27/17
   (d) 17/27

   **Answer: c**

8. A container has one mole of monoatomic ideal gas. Each molecule has f degrees of freedom. What is the ratio of \( \gamma = \frac{C_p}{C_v} \)? (Options not fully visible in original)

9. If the temperature and pressure of a gas is doubled the mean free path of the gas molecules
   (a) remains same
   (b) doubled
   (c) tripled
   (d) quadrupled

   **Answer: a**

10. Which of the following shows the correct relationship between the pressure and density of an ideal gas at constant temperature? (Graph options - Answer: d)

11. A sample of gas consists of \( \mu_{1} \) moles of monoatomic molecules, \( \mu_{2} \) moles of diatomic molecules and \( \mu_{3} \) moles of linear triatomic molecules. The gas is kept at high temperature. What is the total number of degrees of freedom?
    \[
    \text{(a)} \quad [3\mu_{1} + 7(\mu_{2} + \mu_{3})] N_{A}
    \]
    \[
    \text{(b)} \quad [3\mu_{1} + 7\mu_{2} + 6\mu_{3}] N_{A}
    \]
    \[
    \text{(c)} \quad [7\mu_{1} + 3(\mu_{2} + \mu_{3})] N_{A}
    \]
    \[
    \text{(d)} \quad [3\mu_{1} + 6(\mu_{2} + \mu_{3})] N_{A}
    \]

    **Answer: a**

12. If \( \mathbf{s}_{\mathrm{p}} \) and \( \mathbf{s}_{\mathrm{v}} \) denote the specific heats of nitrogen gas per unit mass at constant pressure and constant volume respectively, then
    (a) \( s_{p} - s_{v} = 28R \)
    (b) \( s_{p} - s_{v} = R/28 \)
    (c) \( s_{p} - s_{v} = R/14 \)
    (d) \( s_{p} - s_{v} = R \)

    **Answer: b**

13. Which of the following gases will have least rms speed at a given temperature?
    (a) Hydrogen
    (b) Nitrogen
    (c) Oxygen
    (d) Carbon dioxide

    **Answer: d**

14. For a given gas molecule at a fixed temperature, the area under the Maxwell-Boltzmann distribution curve is equal to
    \[
    \text{(a)} \quad \frac{PV}{kT} \qquad \text{(b)} \quad \frac{kT}{PV} \qquad \text{(c)} \quad \frac{P}{NkT} \qquad \text{(d)} \quad PV
    \]

    **Answer: a**

15. The following graph represents the pressure versus number density for ideal gas at two different temperatures \( T_{1} \) and \( T_{2} \). The graph implies
    (a) \( T_{1} = T_{2} \)
    (b) \( T_{1} > T_{2} \)
    (c) \( T_{1} < T_{2} \)
    (d) Cannot be determined

    **Answer: b**

## Short Answer Questions

1. What is the microscopic origin of pressure?
2. What is the microscopic origin of temperature?
3. Why moon has no atmosphere?
4. Write the expression for rms speed, average speed and most probable speed of a gas molecule.
5. What is the relation between the average kinetic energy and pressure?
6. Define the term degrees of freedom.
7. State the law of equipartition of energy.
8. Define mean free path and write down its expression.
9. Deduce Charles' law based on kinetic theory.
10. Deduce Boyle's law based on kinetic theory.
11. Deduce Avogadro's law based on kinetic theory.
12. List the factors affecting the mean free path.
13. What is the reason for Brownian motion?

## Long Answer Questions

1. Write down the postulates of kinetic theory of gases.
2. Derive the expression of pressure exerted by the gas on the walls of the container.
3. Explain in detail the kinetic interpretation of temperature.
4. Describe the total degrees of freedom for monoatomic molecule, diatomic molecule and triatomic molecule.
5. Derive the ratio of two specific heat capacities of monoatomic, diatomic and triatomic molecules.
6. Explain in detail the Maxwell Boltzmann distribution function.
7. Derive the expression for mean free path of the gas.
8. Describe the Brownian motion.

## Numerical Problems

1. A fresh air is composed of nitrogen \( N_{2} (78\%) \) and oxygen \( O_{2} (21\%) \). Find the rms speed of \( N_{2} \) and \( O_{2} \) at \( 20^{\circ}C \).

   **Ans:** For \( N_{2}, v_{\mathrm{rms}} = 511 \, \text{m s}^{-1} \); For \( O_{2}, v_{\mathrm{rms}} = 478 \, \text{m s}^{-1} \)

2. If the rms speed of methane gas in the Jupiter's atmosphere is \( 471.8 \, \text{m s}^{-1} \), show that the surface temperature of Jupiter is sub-zero.

   **Ans:** \( -130^{\circ}C \)

3. Calculate the temperature at which the rms velocity of a gas triples its value at S.T.P. (standard temperature \( T_{1} = 273 \, \text{K} \))

   **Ans:** \( T_{2} = 2457 \, \text{K} \)

4. A gas is at temperature \( 80^{\circ}C \) and pressure \( 5 \times 10^{-10} \, \text{N m}^{-2} \). What is the number of molecules per \( \text{m}^{3} \) if Boltzmann's constant is \( 1.38 \times 10^{-23} \, \text{J K}^{-1} \)

   **Ans:** \( 1.02 \times 10^{11} \)

5. If \( 10^{20} \) oxygen molecules per second strike \( 4 \, \text{cm}^{2} \) of wall at an angle of \( 30^{\circ} \) with the normal when moving at a speed of \( 2 \times 10^{3} \, \text{m s}^{-1} \), find the pressure exerted on the wall. (mass of one oxygen atom \( = 2.67 \times 10^{-26} \, \text{kg} \))

   **Ans:** \( 46.2 \, \text{N m}^{-2} \)

6. During an adiabatic process, the pressure of a mixture of monatomic and diatomic gases is found to be proportional to the cube of the temperature. Find the value of \( \gamma = (C_p / C_v) \)

   **Ans:** \( 3/2 \)

7. Calculate the mean free path of air molecules at STP. The diameter of \( N_{2} \) and \( O_{2} \) is about \( 3 \times 10^{-10} \, \text{m} \)

   **Ans:** \( \lambda = 9.3 \times 10^{-8} \, \text{m} \)

8. A gas made of a mixture of 2 moles of oxygen and 4 moles of argon at temperature T. Calculate the energy of the gas in terms of RT. Neglect the vibrational modes.

   **Ans:** \( 11RT \)

9. Estimate the total number of air molecules in a room of capacity of \( 25 \, \text{m}^{3} \) at a temperature of \( 27^{\circ}C \) with 1 atm pressure.

   **Ans:** \( 6.1 \times 10^{26} \) molecules

## Books for Reference

1. Serway and Jewett, Physics for scientist and Engineers with modern physics, Brook/Coole publishers, Eighth edition
2. Paul Tipler and Gene Mosca, Physics for scientist and engineers with modern physics, Sixth edition, W.H. Freeman and Company
3. H.C. Verma, Concepts of physics - Volume 2, Bharati Bhawan Publishers
4. Douglas C. Giancoli, Physics for scientist & Engineers, Pearson Publications, Fourth Edition
5. James Walker, Physics, Addison Wesley, Fourth Edition