---
title: "Power"
weight: 3
---

### 4.3.1 Definition of power

Power is a measure of how fast or slow a work is done. Power is defined as the rate of work done or energy delivered.

\[
\mathrm{Power} (P) = \frac{\mathrm{work\ done} (W)}{\mathrm{time\ taken} (t)} = \frac{W}{t}
\]

**Average power**

The average power \( (P_{av}) \) is defined as the ratio of the total work done to the total time taken.

\[
P_{av} = \frac{\mathrm{total\ work\ done}}{\mathrm{total\ time\ taken}}
\]

### 4.3.2 Unit of power

Power is a scalar quantity. Its dimension is \( [\mathrm{ML}^{2}\mathrm{T}^{-3}] \). The SI unit of power is watt (W), named after the inventor of the steam engine James Watt. One watt is defined as the power when one joule of work is done in one second, \( (1 \, \mathrm{W} = 1 \, \mathrm{J} \, \mathrm{s}^{-1}) \).

The higher units are kilowatt (kW), megawatt (MW), and Gigawatt (GW).

\[
1 \, \mathrm{kW} = 1000 \, \mathrm{W} = 10^{3} \, \mathrm{W}
\]
\[
1 \, \mathrm{MW} = 10^{6} \, \mathrm{W}
\]
\[
1 \, \mathrm{GW} = 10^{9} \, \mathrm{W}
\]

For motors, engines and some automobiles an old unit of power still commercially in use which is called as the horse-power (hp). We have a conversion for horse-power (hp) into watt (W) which is,

\[
1 \, \mathrm{hp} = 746 \, \mathrm{W}
\]

All electrical goods come with a definite power rating in watt printed on them. A 100 watt bulb consumes 100 joule of electrical energy in one second. The energy measured in joule in terms of power in watt and time in second is written as, \( 1 \, \mathrm{J} = 1 \, \mathrm{W} \, \mathrm{s} \). When electrical appliances are put in use for long hours, they consume a large amount of energy. Measuring the electrical energy in a small unit watt·second (W s) leads to handling large numerical values. Hence, electrical energy is measured in the unit called kilowatt hour (kWh).

\[
1 \, \mathrm{electrical\ unit} = 1 \, \mathrm{kWh} = 1 \times (10^{3} \, \mathrm{W}) \times (3600 \, \mathrm{s}) = 3600 \times 10^{3} \, \mathrm{W\,s}
\]
\[
1 \, \mathrm{electrical\ unit} = 3.6 \times 10^{6} \, \mathrm{J}
\]
\[
1 \, \mathrm{kWh} = 3.6 \times 10^{6} \, \mathrm{J}
\]

Electricity bills are generated in units of kWh for electrical energy consumption. 1 unit of electrical energy is \( 1 \, \mathrm{kWh} \). (Note: kWh is unit of energy and not of power.)

**EXAMPLE 4.18**

Calculate the energy consumed in electrical units when a 75 W fan is used for 8 hours daily for one month (30 days).

**Solution**

Power, \( \mathrm{P} = 75 \, \mathrm{W} \)

Time of usage, \( \mathrm{t} = 8 \, \text{hour} \times 30 \, \text{days} = 240 \, \text{hours} \)

Electrical energy consumed is the product of power and time of usage.

\[
\text{Electrical energy} = \text{power} \times \text{time of usage} = P \times t = 75 \, \mathrm{W} \times 240 \, \text{hour} = 18000 \, \mathrm{Wh} = 18 \, \mathrm{kWh}
\]
\[
1 \, \mathrm{electrical\ unit} = 1 \, \mathrm{kWh}
\]
\[
\mathrm{Electrical\ energy} = 18 \, \mathrm{units}
\]

Incandescent lamps glow for 1000 hours. CFL lamps glow for 6000 hours. But LED lamps glow for 50000 hrs (almost 25 years at 5.5 hour per day).

### 4.3.3 Relation between power and velocity

The work done by a force \( \bar{\mathbf{F}} \) for a displacement \( \mathrm{d}\bar{\mathbf{r}} \) is

\[
\mathrm{W} = \int \bar{\mathrm{F}} \cdot \mathrm{d}\bar{\mathrm{r}}
\]

Left hand side can be written as

\[
\mathrm{W} = \int \mathrm{dW} = \int \frac{\mathrm{dW}}{\mathrm{dt}} \mathrm{dt}
\]

Since, velocity is \( \bar{\nu} = \frac{d\bar{r}}{dt} \); \( d\bar{r} = \bar{\nu} dt \). Right hand side can be written as

\[
\int \bar{\mathrm{F}} \cdot \mathrm{d}\bar{\mathrm{r}} = \int \left( \bar{\mathrm{F}} \cdot \frac{d\bar{r}}{dt} \right) \mathrm{dt} = \int \left( \bar{\mathrm{F}} \cdot \bar{\nu} \right) \mathrm{dt}
\]

Substituting, we get

\[
\int \frac{\mathrm{d}W}{\mathrm{d}t} \mathrm{d}t = \int \left( \bar{\mathrm{F}} \cdot \bar{\nu} \right) \mathrm{d}t
\]
\[
\int \left( \frac{\mathrm{d}W}{\mathrm{d}t} - \bar{\mathrm{F}} \cdot \bar{\nu} \right) \mathrm{d}t = 0
\]

This relation is true for any arbitrary value of dt. This implies that the term within the bracket must be equal to zero, i.e.,

\[
\frac{\mathrm{d}W}{\mathrm{d}t} - \bar{\mathrm{F}} \cdot \bar{\nu} = 0
\]
\[
\text{Or} \quad \frac{\mathrm{d}W}{\mathrm{d}t} = \bar{\mathrm{F}} \cdot \bar{\nu} = P
\]

**EXAMPLE 4.19**

A vehicle of mass \( 1250 \, \mathrm{kg} \) is driven with an acceleration \( 0.2 \, \mathrm{ms}^{-2} \) along a straight level road against an external resistive force \( 500 \, \mathrm{N} \). Calculate the power delivered by the vehicle's engine if the velocity of the vehicle is \( 30 \, \mathrm{ms}^{-1} \).

**Solution**

The vehicle's engine has to do work against resistive force and make vehicle to move with an acceleration. Therefore, power delivered by the vehicle engine is

\[
\mathrm{P} = (\text{resistive force} + \text{mass} \times \text{acceleration}) \times \text{velocity}
\]
\[
\mathrm{P} = \bar{\mathrm{F}}_{\mathrm{tot}} \cdot \bar{\mathrm{v}} = (F_{\mathrm{resistive}} + ma)v
\]
\[
= (500 \, \mathrm{N} + 1250 \, \mathrm{kg} \times 0.2 \, \mathrm{ms}^{-2}) \times 30 \, \mathrm{ms}^{-1} = (500 + 250) \times 30 = 750 \times 30 = 22500 \, \mathrm{W} = 22.5 \, \mathrm{kW}
\]