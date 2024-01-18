---
title: 'Power'
weight: 3
---

[comment]: <> (katex Header)
{{< katex display >}}{{< /katex >}}

# POWER

## Definition of power

Power is a measure of how fast or slow work is done. Power is defined as the rate of work done or energy delivered.

$$
P = \frac{W}{t}
$$

_Average power ($P_{\text{av}}$)_ is defined as the ratio of the total work done to the total time taken.

$$
P_{\text{av}} = \frac{\text{total work done}}{\text{total time taken}}
$$

**Instantaneous power ($P_{\text{inst}}$)** is defined as the power delivered at an instant (as the time interval approaches zero).

$$
P_{\text{inst}} = \frac{dW}{dt}
$$

## Unit of power

Power is a scalar quantity with dimensions [ML²T⁻³]. The SI unit of power is watt (W), named after the inventor of the steam engine James Watt. One watt is defined as the power when one joule of work is done in one second ($1 \text{ W} = 1 \text{ J s}^{-1}$).

Higher units include kilowatt (kW), megawatt (MW), and gigawatt (GW).

$$
1 \text{ kW} = 1000 \text{ W} = 10^3 \text{ watt}
$$

$$
1 \text{ MW} = 10^6 \text{ watt}
$$

$$
1 \text{ GW} = 10^9 \text{ watt}
$$

For motors, engines, and some automobiles, an old unit of power still in use is called horsepower (hp), which can be converted to watts:

$$
1 \text{ hp} = 746 \text{ W}
$$

Electricity consumption is measured in kilowatt-hours (kWh):

$$
1 \text{ electrical unit} = 1 \text{ kWh} = 1 \times (10^3 \text{ W}) \times (3600 \text{ s})
$$

$$
1 \text{ electrical unit} = 3600 \times 10^3 \text{ W s}
$$

$$
1 \text{ electrical unit} = 3.6 \times 10^6 \text{ J}
$$

$$
1 \text{ kWh} = 3.6 \times 10^6 \text{ J}
$$

Electricity bills are generated in units of kWh for electrical energy consumption. Note that kWh is a unit of energy, not power.

**EXAMPLE 4.18**

Calculate the energy consumed in electrical units when a 75 W fan is used for 8 hours daily for one month (30 days).

**_Solution_**

Power, $P = 75 \text{ W}$

Time of usage, $t = 8 \text{ hours} \times 30 \text{ days} = 240 \text{ hours}$

Electrical energy consumed is the product of power and time of usage.

$$
\text{Electrical energy} = \text{power} \times \text{time of usage} = P \times t
$$

$$
= 75 \times 240 \text{ watt-hours} = 18000 \text{ watt-hours}
$$

$$
= 18 \text{ kilowatt-hours (kWh)}
$$

**DO YOU KNOW**

Incandescent lamps glow for 1000 hours. CFL lamps glow for 6000 hours. But LED lamps glow for 50000 hrs (almost 25 years at 5.5 hours per day).

## Relation between power and velocity

The work done by a force $\vec{F}$ for a displacement $\vec{dr}$ is

$$
W = \int \vec{F} \cdot d\vec{r}
$$

Left-hand side of the equation can be written as

$$
W = \frac{dW}{dt} \cdot dt
$$

Since velocity is $\vec{v} = \frac{d\vec{r}}{dt}$, right-hand side of the equation can be written as

$$
W = \vec{F} \cdot \vec{v}
$$

Substituting these equations in, we get

$$
\frac{dW}{dt} = \vec{F} \cdot \vec{v}
$$

This implies that

$$
\frac{dW}{dt} = \vec{F} \cdot \vec{v} = \vec{P}
$$

**EXAMPLE 4.19**

A vehicle of mass 1250 kg is driven with an acceleration $0.2 \text{ m/s}^2$ along a straight level road against an external resistive force 500 N. Calculate the power delivered by the vehicle's engine if the velocity of the vehicle is $30 \text{ m/s}$.

**_Solution_**

The vehicle's engine has to do work against the resistive force and make the vehicle move with acceleration. Therefore, power delivered by the vehicle engine is

$$
P = (\text{resistive force} + \text{mass} \times \text{acceleration}) \times \text{velocity}
$$

$$
P = (500 \text{ N} + (1250 \text{ kg}) \times (0.2 \text{ m/s}^2)) \times (30 \text{ m/s}) = 22.5 \text{ kW}
$$
