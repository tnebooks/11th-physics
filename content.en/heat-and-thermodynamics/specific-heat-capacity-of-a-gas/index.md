---
<<<<<<< HEAD
title: 'Specific Heat Capacity Of A Gas'
=======
title: 'specific heat capacity of a gas'
>>>>>>> 9468d8de506ee3fe7a32ff32aec5f0ee5a849f86
weight: 7
---


Specific heat capacity of a given system plays a very important role in determining the structure and molecular nature of the system. Unlike solids and liquids, gases have two specific heats: specific heat capacity at constant pressure {{< katex display >}}(s_p){{< /katex >}}and specific heat capacity at constant volume {{< katex display >}}(s_v){{< /katex >}}.


**Specific heat capacity at constant pressure** (**_sp_**): 
The amount of heat energy required to raise the temperature of one kg of a substance by 1 K or 1°C by keeping the pressure constant is called specific heat capacity of at constant pressure. When the heat energy is supplied to the gas, it expands to keep the pressure constant as shown in Figure 8.23
![images](image_2.jpg)

**Figure 8.23** Specific heat capacity at constant pressure


In this process a part of the heat energy is used for doing work (expansion) and the remaining part is used to increase the internal energy of the gas. 

**Specific heat capacity at constant volume (sv):** 

The amount of heat energy required to raise the temperature of one kg of a substance by 1 K or 1°C by keeping the volume constant is called specific heat capacity at constant volume.

If the volume is kept constant, then the supplied heat is used to increase only the internal energy. No work is done by the gas as shown in Figure 8.24.

![images](image_3.jpg)

**Figure 8.24**  Specific heat capacity at constant volume


It implies that to increase the temperature of the gas at constant volume requires less heat than increasing the temperature of the gas at constant pressure. In other words {{< katex display >}}(s_p){{< /katex >}}is always greater than {{< katex display >}}(s_v){{< /katex >}}.

**Molar Specific heat capacities** 

Sometimes it is useful to calculate the molar heat capacities Cp and Cv. The amount of heat required to raise the temperature of one mole of a substance by 1K or 1°C at constant volume is called molar specific heat capacity at constant volume (Cv). If pressure is kept constant, it is called molar specific heat capacity at constant pressure (Cp).


If Q is the heat supplied to mole of a gas at constant volume and if the temperature changes by an amount {{< katex display >}}\Delta T {{< /katex >}}, we have

{{< katex display >}}Q = \mu C_v \Delta T {{< /katex >}}

By applying the first law of thermodynamics for this constant volume process (W=0, since dV=0), we have

{{< katex display >}}  Q = \Delta U - 0 {{< /katex >}}

By comparing the equations (8.18) and (8.19),

{{< katex display >}} \Delta U = \mu C_v \Delta T {{< /katex >}}

or

{{< katex display >}}C_v = \frac{1}{\mu}\frac{\Delta U}{\Delta T} {{< /katex >}}


If the limit {{< katex display >}}\Delta T {{< /katex >}}goes to zero, we can write


{{< katex display >}} C_v = \frac{1}{\mu} \frac{dU}{dT} {{< /katex >}}


Since the temperature and internal energy are state variables, the above relation holds true for any process.

## Meyer’s relation


Consider µ mole of an ideal gas in a container with volume V, pressure P and temperature T.

When the gas is heated at constant volume the temperature increases by dT. As no work is done by the gas, the heat that flows into the system will increase only the internal energy. Let the change in internal energy be dU.

If Cv is the molar specific heat capacity at constant volume, from equation (8.20)

{{< katex display >}}dU = \mu C_v \, dT{{< /katex >}}


Suppose the gas is heated at constant pressure so that the temperature increases by dT. If ‘Q’ is the heat supplied in this process and ‘dV’ the change in volume of the gas.  

{{< katex display >}}  Q = \mu C_p \Delta T {{< /katex >}}
If W is the workdone by the gas in this process, then
{{< katex display >}}  W = P \, dV {{< /katex >}}

But from the first law of thermodynamics,

{{< katex display >}}  Q = \Delta U + W {{< /katex >}}

Substituting equations (8.21), (8.22) and (8.23) in (8.24), we get,
{{< katex display >}}  \mu C_p dT = \mu C_v dT + P dV {{< /katex >}}


For mole of ideal gas, the equation of state is given by

{{< katex display >}}  PV = \mu RT {{< /katex >}}

{{< katex display >}}  PdV + VdP = \mu RdT {{< /katex >}}

Since the pressure is constant, dP=0 ∴CpdT = CvdT +RdT

∴{{< katex display >}} C_p dT = C_v dT + R dT{{< /katex >}}

{{< katex display >}} C_P = C_V + R {{< /katex >}}

or

{{< katex display >}}  C_P - C_V = R {{< /katex >}}

This relation is called Meyer’s relation

It implies that the molar specific heat capacity of an ideal gas at constant pressure is greater than molar specific heat capacity at constant volume. The relation shows that specific heat at constant pressure (sp) is always greater that specific heat at constant volume (sv).