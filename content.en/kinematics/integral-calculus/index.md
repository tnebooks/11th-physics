---
title: 'INTEGRAL CALCULUS'
weight: 8
---

# INTEGRAL CALCULUS

Integration is an area finding process. For certain geometric shapes we can directly find the area. But for irregular shapes the process of integration is used. Consider for example the areas of a rectangle and an irregularly shaped curve, as shown in Figure 2.29.

The area of the rectangle is simply given by {{< katex >}}\mathrm{A}={{< /katex >}} length {{< katex >}}\times{{< /katex >}} breadth {{< katex >}}=(\mathrm{b}-\mathrm{a}) \mathrm{c}{{< /katex >}}

![Alt text](<./fig-2.29.png>)

**Figure 2.29** Area of rectangular and irregular shape

But to find the area of the irregular shaped curve given by {{< katex >}}f(x){{< /katex >}}, we divide the area into rectangular strips as shown in the Figure 2.30.
The area under the curve is approximately equal to sum of areas of each rectangular strip.

This is given by {{< katex >}}A \approx f(a) \Delta x+f\left(x_{1}\right) \Delta x{{< /katex >}} {{< katex >}}+f\left(x_{2}\right) \Delta x+f\left(x_{3}\right) \Delta x{{< /katex >}}.

![Alt text](<./fig-2.30.png>)

**Figure 2.30** Area under the curve using rectangular strip

Where {{< katex >}}f(a){{< /katex >}} is the value of the function {{< katex >}}f(x){{< /katex >}} at {{< katex >}}\mathrm{x}=\mathrm{a}, f\left(x_{1}\right){{< /katex >}} is the value of {{< katex >}}f(x){{< /katex >}} for {{< katex >}}\mathrm{x}=\mathrm{x}_{1}{{< /katex >}} and so on.

As we increase the number of strips, the area evaluated becomes more accurate. If the area under the curve is divided into {{< katex >}}\mathrm{N}{{< /katex >}} strips, the area under the curve is given by {{< katex >}}\mathrm{A}=\sum_{n=1}^{N} f\left(x_{n}\right) \Delta x{{< /katex >}}

As the number of strips goes to infinity, {{< katex >}}N \rightarrow \infty{{< /katex >}}, the sum becomes an integral,

{{< katex >}}
\mathrm{A}=\int_{a}^{b} f(x) d x
{{< /katex >}}

(Note: As {{< katex >}}N \rightarrow \infty, \Delta x \rightarrow 0{{< /katex >}} )

The integration will give the total area under the curve {{< katex >}}f(x){{< /katex >}}. This is shown in Figure 2.31.

![Alt text](<./fig-2.31.png>)

**Figure 2.31** Relation between su

**Examples** 

In physics the work done by a force {{< katex >}}\mathrm{F}(x){{< /katex >}} on an object to move it from point {{< katex >}}a{{< /katex >}} to point {{< katex >}}b{{< /katex >}} in one dimension is given by

{{< katex >}}
W=\int_{a}^{b} F(x) d x
{{< /katex >}}

(No scalar products is required here, since motion here is in one dimension)

1) The work done is the area under the force displacement graph as shown in Figure 2.32

![Alt text](<./fig-2.32.png>)

**Figure 2.32** Work done by the force

2) The impulse given by the force in an interval of time is calculated between the interval from time {{< katex >}}t=0{{< /katex >}} to time {{< katex >}}\mathrm{t}=\mathrm{t}_{1}{{< /katex >}} as

{{< katex >}}
\text { Impulse } I=\int_{0}^{t_{1}} F d t
{{< /katex >}}

The impulse is the area under the force function {{< katex >}}F(t){{< /katex >}} - {{< katex >}}t{{< /katex >}} graph as shown in Figure 2.33.

![Alt text](<./fig-2.33.png>)

**Figure 2.33** Impulse of a force

**Average velocity** 

Consider a particle located initially at point {{< katex >}}\mathrm{P}{{< /katex >}} having position vector {{< katex >}}\vec{r}_{1}{{< /katex >}}. In a time interval {{< katex >}}\Delta t{{< /katex >}} the particle is moved to the point {{< katex >}}\mathrm{Q}{{< /katex >}} having position vector {{< katex >}}\vec{r}_{2}{{< /katex >}}. The displacement vector is {{< katex >}}\Delta \vec{r}=\vec{r}_{2}-\vec{r}_{1}{{< /katex >}}. This is shown in Figure 2.34.

The average velocity is defined as ratio of the displacement vector to the corresponding time interval

{{< katex >}}
\vec{v}_{a v g}=\frac{\Delta \vec{r}}{\Delta t}
{{< /katex >}}

It is a vector quantity. The direction of average velocity is in the direction of the displacement vector {{< katex >}}(\Delta \vec{r}){{< /katex >}}.

This is also shown in Figure 2.34.

![Alt text](<./fig-2.34.png>)

**Average speed**

The average speed is defined as the ratio of total path length travelled by the particle in a time interval. 

Average speed = total path length / total time

EXAMPLE 2.20
Consider an object travelling in a semi-circular path from point O to point P in 5 second, as shown in the Figure given below. Calculate the average velocity and average speed.

![Alt text](<./eg-2.20.png>)

{{< katex >}}
\begin{gathered}
\text { Average velocity } \vec{v}_{\text {avg }}=\frac{\vec{r}_{P}-\vec{r}_{O}}{\Delta t} \\
\text { Here } \Delta t=5 \mathrm{~s} \\
\vec{r}_{O}=0, \vec{r}_{P}=10 \hat{i} \\
\vec{v}_{\text {avg }}=\frac{10 \hat{i} \mathrm{~cm}}{5 \mathrm{~s}}=2 \hat{i} \mathrm{~cm} \mathrm{~s}^{-1} .
\end{gathered}
{{< /katex >}}

The average velocity is in the positive {{< katex >}}\mathrm{x}{{< /katex >}} direction.

The average speed = total path length / time taken (the path is semi-circular)

{{< katex >}}
=\frac{5 \pi c m}{5 s}=\pi c m ~ s^{-1} \approx 3.14 \mathrm{cms}^{-1}
{{< /katex >}}

Note that the average speed is greater than the magnitude of the average velocity.

**Instantaneous velocity or velocity**
The instantaneous velocity at an instant {{< katex >}}t{{< /katex >}} or simply 'velocity' at an instant {{< katex >}}t{{< /katex >}} is defined as limiting value of the average velocity as {{< katex >}}\Delta t \rightarrow 0{{< /katex >}}, evaluated at time {{< katex >}}t{{< /katex >}}.

In other words, velocity is equal to rate of change of position vector with respect to time. Velocity is a vector quantity.

{{< katex >}}
\vec{v}=\lim _{\Delta t \rightarrow 0} \frac{\Delta \vec{r}}{\Delta t}=\frac{d \vec{r}}{d t}
{{< /katex >}}

In component form, this velocity is

{{< katex >}}
\begin{aligned}
\vec{v} & =\frac{d \vec{r}}{d t}=\frac{d}{d t}(x \hat{i}+y \hat{j}+z \hat{k}) \\
& =\frac{d x}{d t} \hat{i}+\frac{d y}{d t} \hat{j}+\frac{d z}{d t} \hat{k}
\end{aligned}
{{< /katex >}}

Here {{< katex >}}\frac{d x}{d t}=v_{x}=x-{{< /katex >}} component of velocity

{{< katex >}}
\begin{aligned}
& \frac{d y}{d t}=v_{y}=y-\text { component of velocity } \\
& \frac{d z}{d t}=v_{z}=z-\text { component of velocity }
\end{aligned}
{{< /katex >}}

The magnitude of velocity {{< katex >}}v{{< /katex >}} is called speed and is given by

{{< katex >}}
v=\sqrt{v_{x}^{2}+v_{y}^{2}+v_{z}^{2}}
{{< /katex >}}

Speed is always a positive scalar. The unit of speed is also meter per second.

**EXAMPLE 2.21**
The position vector of a particle is given {{< katex >}}\vec{r}=2 t \hat{i}+3 t^{2} \hat{j}-5 \hat{k}{{< /katex >}}.

a) Calculate the velocity and speed of the particle at any instant {{< katex >}}t{{< /katex >}}

b) Calculate the velocity and speed of the particle at time {{< katex >}}t=2 \mathrm{~s}{{< /katex >}}

**_Solution_** 

The velocity {{< katex >}}\vec{v}=\frac{d \vec{r}}{d t}=2 \hat{i}+6 \hat{j}{{< /katex >}}

The speed {{< katex >}}v(t)=\sqrt{2^{2}+(6 t)^{2}} m s^{-1}{{< /katex >}}

The velocity of the particle at {{< katex >}}t=2 \mathrm{~s}{{< /katex >}}

{{< katex >}}
\vec{v}(2 \sec )=2 \hat{i}+12 \hat{j}
{{< /katex >}}

The speed of the particle at {{< katex >}}t=2 \mathrm{~s}{{< /katex >}}

{{< katex >}}
\begin{aligned}
v(2 s) & =\sqrt{2^{2}+12^{2}}=\sqrt{4+144} \\
& =\sqrt{148} \approx 12.16 \mathrm{~ms}^{-1}
\end{aligned}
{{< /katex >}}

Note that the particle has velocity components along {{< katex >}}\mathrm{x}{{< /katex >}} and {{< katex >}}\mathrm{y}{{< /katex >}} direction. Along the {{< katex >}}z{{< /katex >}} direction the position has constant value {{< katex >}}(-5){{< /katex >}} which is independent of time. Hence there is no z-component for the velocity.

**EXAMPLE 2.22**
The velocity of three particles A, B, C are given below. Which particle travels at the greatest speed?

{{< katex >}}
\begin{aligned}
& \overrightarrow{v_{A}}=3 \hat{i}-5 \hat{j}+2 \hat{k} \\
& \overrightarrow{v_{B}}=\hat{i}+2 \hat{j}+3 \hat{k} \\
& \overrightarrow{v_{C}}=5 \hat{i}+3 \hat{j}+4 \hat{k}
\end{aligned}
{{< /katex >}}

**_Solution_** 

We know that speed is the magnitude of the velocity vector. Hence,

{{< katex >}}
\begin{aligned}
\text { Speed of } A & =\left|\overrightarrow{v_{A}}\right|=\sqrt{(3)^{2}+(-5)^{2}+(2)^{2}} \\
& =\sqrt{9+25+4}=\sqrt{38} \mathrm{~m} \mathrm{~s}^{-1} \\
\text { Speed of } B & =\left|\overrightarrow{v_{B}}\right|=\sqrt{(1)^{2}+(2)^{2}+(3)^{2}} \\
& =\sqrt{1+4+9}=\sqrt{14} \mathrm{~m} \mathrm{~s}^{-1} \\
\text { Speed of } C & =\left|\overrightarrow{v_{C}}\right|=\sqrt{(5)^{2}+(3)^{2}+(4)^{2}} \\
& =\sqrt{25+9+16}=\sqrt{50} \mathrm{~m} \mathrm{~s}^{-1}
\end{aligned}
{{< /katex >}}

The particle {{< katex >}}\mathrm{C}{{< /katex >}} has the greatest speed.

{{< katex >}}
\sqrt{50}>\sqrt{38}>\sqrt{14}
{{< /katex >}}


**EXAMPLE 2.23**
Two cars are travelling with respective velocities {{< katex >}}\vec{v}_{1}=10 \mathrm{~m} \mathrm{~s}^{-1}{{< /katex >}} along east and {{< katex >}}\vec{v}_{2}=10 \mathrm{~m} \mathrm{~s}^{-1}{{< /katex >}} along west. What are the speeds of the cars?

**_Solution_** 

Both cars have the same magnitude of velocity. This implies that both cars travel at the same speed even though they have velocities in different directions. Speed will not give the direction of motion.

![Alt text](./motion..png)

**Momentum**
The linear momentum or simply momentum of a particle is defined as product of mass with velocity. It is denoted as ' {{< katex >}}\vec{p}{{< /katex >}} '. Momentum is also a vector quantity.

{{< katex >}}
\vec{p}=m \vec{v}
{{< /katex >}}

The direction of momentum is also in the direction of velocity, and the magnitude of momentum is equal to product of mass and speed of the particle.

{{< katex >}}
p=m v
{{< /katex >}}

In component form the momentum can be written as

{{< katex >}}
p_{x} \hat{i}+p_{y} \hat{j}+p_{z} \hat{k}=m v_{x} \hat{i}+m v_{y} \hat{j}+m v_{z} \hat{k}
{{< /katex >}}

Here {{< katex >}}p_{x}=x{{< /katex >}} component of momentum and is equal to {{< katex >}}m v_{x}{{< /katex >}}

{{< katex >}}p_{y}=y{{< /katex >}} component of momentum and is equal to {{< katex >}}m v_{y}{{< /katex >}}

{{< katex >}}p_{z}=z{{< /katex >}} component of momentum and is equal to {{< katex >}}m v_{z}{{< /katex >}}

The momentum of the particle plays a very important role in Newton's laws. The physical significance of momentum can be well understood by the following example.
Consider a butterfly and a stone, both moving towards you with the same velocity {{< katex >}}5 \mathrm{~m} \mathrm{~s}^{-1}{{< /katex >}}. If both hit your body, the effects will not be the same. The effects not only depend upon the velocity, but also on the mass. The stone has greater mass compared to the butterfly. The momentum of the stone is thus greater than the momentum of the butterfly. It is the momentum which plays a major role in explaining the 'state' of motion of the object.

The unit of the momentum is {{< katex >}}\mathrm{kg} \mathrm{m} \mathrm{s}^{-1}{{< /katex >}}

**EXAMPLE 2.24**
Consider two masses of {{< katex >}}10 \mathrm{~g}{{< /katex >}} and {{< katex >}}1 \mathrm{~kg}{{< /katex >}} moving with the same speed {{< katex >}}10 \mathrm{~m} \mathrm{~s}^{-1}{{< /katex >}}. Calculate the magnitude of the momentum.

**_Solution_** 

We use {{< katex >}}p=m v{{< /katex >}}

For the mass of {{< katex >}}10 \mathrm{~g}, \mathrm{~m}=0.01 \mathrm{~kg}{{< /katex >}}

{{< katex >}}
p=0.01 \times 10=0.1 \mathrm{~kg} \mathrm{~m} \mathrm{~s}^{-1}
{{< /katex >}}

For the mass of {{< katex >}}1 \mathrm{~kg}{{< /katex >}}

{{< katex >}}
p=1 \times 10=10 \mathrm{~kg} \mathrm{~m} \mathrm{~s}^{-1}
{{< /katex >}}

Thus even though both the masses have the same speed, the momentum of the heavier mass is 100 times greater than that of the lighter mass.