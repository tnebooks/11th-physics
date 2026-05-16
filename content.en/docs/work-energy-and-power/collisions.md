---
title: "Collisions"
weight: 4
---

Collision is a common phenomenon that happens around us every now and then. For example, carom, billiards, marbles, etc. Collisions can happen between two bodies with or without physical contacts.

Linear momentum is conserved in all collision processes. When two bodies collide, the mutual impulsive forces acting between them during the collision time \( (\Delta t) \) produces a change in their respective momenta. That is, the first body exerts a force \( \bar{\mathbf{F}}_{21} \) on the second body. From Newton's third law, the second body exerts a force \( \bar{\mathbf{F}}_{12} \) on the first body. This causes a change in momentum \( \Delta \bar{\mathbf{p}}_1 \) and \( \Delta \bar{\mathbf{p}}_2 \) of the first body and second body respectively. Now, the relations could be written as,

\[
\Delta \bar{\mathbf{p}}_1 = \bar{\mathbf{F}}_{12} \Delta t, \quad \Delta \bar{\mathbf{p}}_2 = \bar{\mathbf{F}}_{21} \Delta t
\]

Adding the two equations, we get

\[
\Delta \bar{\mathbf{p}}_1 + \Delta \bar{\mathbf{p}}_2 = \bar{\mathbf{F}}_{12} \Delta t + \bar{\mathbf{F}}_{21} \Delta t = (\bar{\mathbf{F}}_{12} + \bar{\mathbf{F}}_{21}) \Delta t
\]

According to Newton's third law, \( \bar{\mathbf{F}}_{12} = -\bar{\mathbf{F}}_{21} \)

\[
\Delta \bar{\mathbf{p}}_1 + \Delta \bar{\mathbf{p}}_2 = 0
\]
\[
\Delta (\bar{\mathbf{p}}_1 + \bar{\mathbf{p}}_2) = 0
\]

Dividing both sides by \( \Delta t \) and taking limit \( \Delta t \to 0 \), we get

\[
\lim_{\Delta t \to 0} \frac{\Delta(\bar{\mathbf{p}}_1 + \bar{\mathbf{p}}_2)}{\Delta t} = \frac{d(\bar{\mathbf{p}}_1 + \bar{\mathbf{p}}_2)}{dt} = 0
\]

The above expression implies that the total linear momentum is a conserved quantity.

Note: The momentum is a vector quantity. Hence, vector addition has to be followed to find the total momentum of the individual bodies in collision.

### 4.4.1 Types of Collisions

In any collision process, the total linear momentum and total energy are always conserved whereas the total kinetic energy need not be conserved always. Some part of the initial kinetic energy is transformed to other forms of energy. This is because, the impact of collisions and deformation occurring due to collisions may in general, produce heat, sound, light etc. By taking these effects into account, we classify the types of collisions as follows:

(a) Elastic collision

(b) Inelastic collision

**(a) Elastic collision**

In a collision, the total initial kinetic energy of the bodies (before collision) is equal to the total final kinetic energy of the bodies (after collision) then, it is called as elastic collision. i.e.,

Total kinetic energy before collision = Total kinetic energy after collision

**(b) Inelastic collision**

In a collision, the total initial kinetic energy of the bodies (before collision) is not equal to the total final kinetic energy of the bodies (after collision) then, it is called as inelastic collision. i.e.,

Total kinetic energy before collision \( \neq \) Total kinetic energy after collision

Even though kinetic energy is not conserved but the total energy is conserved. This is because the total energy contains the kinetic energy term and also a term \( \Delta Q \), which includes all the losses that take place during collision. Note that loss in kinetic energy during collision is transformed to another form of energy like sound, thermal, etc. Further, if the two colliding bodies stick together after collision such collisions are known as completely inelastic collision or perfectly inelastic collision. Such a collision is found very often. For example when a clay putty is thrown on a moving vehicle, the clay putty sticks to the moving vehicle and they move together with the same velocity.

**Table 4.4 Comparison between elastic and inelastic collisions**

| S.No. | Elastic Collision |
|---|---|
| 1. | Total momentum is conserved |
| 2. | Total kinetic energy is conserved |
| 3. | Forces involved are conservative forces |
| 4. | Mechanical energy is not dissipated |

### 4.4.2 Elastic collisions in one dimension

Consider two elastic bodies of masses \( m_{1} \) and \( m_{2} \) moving in a straight line (along positive \( x \) direction) on a frictionless horizontal surface as shown in Figure 4.16.

**Figure 4.16 Elastic collision in one dimension**

| | Mass | Initial velocity | Final velocity |
|---|---|---|---|
| Mass \( m_1 \) | \( m_1 \) | \( u_1 \) | \( v_1 \) |
| Mass \( m_2 \) | \( m_2 \) | \( u_2 \) | \( v_2 \) |

In order to have collision, we assume that the mass \( m_{1} \) moves faster than mass \( m_{2} \) i.e., \( u_{1} > u_{2} \). For elastic collision, the total linear momentum and kinetic energies of the two bodies before and after collision must remain the same.

From the law of conservation of linear momentum,

Total momentum before collision \( (p_i) = \) Total momentum after collision \( (p_f) \)

\[
m_1 u_1 + m_2 u_2 = m_1 v_1 + m_2 v_2
\]

| | Kinetic energy of mass \( m_1 \) | Kinetic energy of mass \( m_2 \) | Total kinetic energy |
|---|---|---|---|
| Before collision | \( KE_{i1} = \frac{1}{2} m_1 u_1^2 \) | \( KE_{i2} = \frac{1}{2} m_2 u_2^2 \) | \( KE_i = \frac{1}{2} m_1 u_1^2 + \frac{1}{2} m_2 u_2^2 \) |
| After collision | \( KE_{f1} = \frac{1}{2} m_1 v_1^2 \) | \( KE_{f2} = \frac{1}{2} m_2 v_2^2 \) | \( KE_f = \frac{1}{2} m_1 v_1^2 + \frac{1}{2} m_2 v_2^2 \) |

For elastic collision,

Total kinetic energy before collision \( KE_i = \) Total kinetic energy after collision \( KE_f \)

\[
\frac{1}{2} m_1 u_1^2 + \frac{1}{2} m_2 u_2^2 = \frac{1}{2} m_1 v_1^2 + \frac{1}{2} m_2 v_2^2
\]

After simplifying and rearranging the terms,

\[
m_1 (u_1^2 - v_1^2) = m_2 (v_2^2 - u_2^2)
\]

Using the formula \( a^2 - b^2 = (a+b)(a-b) \) we can rewrite the above equation as

\[
m_1 (u_1 + v_1)(u_1 - v_1) = m_2 (v_2 + u_2)(v_2 - u_2)
\]

Dividing this equation by the momentum equation (after rearranging), we get

\[
u_1 - v_1 = v_2 - u_2
\]

Rearranging,

\[
u_1 - u_2 = -(v_1 - v_2)
\]

or

\[
u_1 - u_2 = v_2 - v_1
\]

This means that for any elastic head-on collision, the relative speed of the two elastic bodies after the collision has the same magnitude as before collision but in opposite direction. Further note that this result is independent of mass.

Rewriting the above equation for \( v_1 \) and \( v_2 \),

\[
v_1 = v_2 + u_2 - u_1
\]

or

\[
v_2 = v_1 + u_1 - u_2
\]

To find the final velocities \( v_1 \) and \( v_2 \):

Substituting the expression for \( v_2 \) in the momentum equation gives the velocity of \( m_1 \) as

\[
v_1 = \left( \frac{m_1 - m_2}{m_1 + m_2} \right) u_1 + \left( \frac{2 m_2}{m_1 + m_2} \right) u_2
\]

Similarly, we get the final velocity of \( m_2 \) as

\[
v_2 = \left( \frac{2 m_1}{m_1 + m_2} \right) u_1 + \left( \frac{m_2 - m_1}{m_1 + m_2} \right) u_2
\]

**Case 1: When bodies have the same mass i.e., \( m_1 = m_2 \),**

\[
v_1 = \left( \frac{m - m}{m + m} \right) u_1 + \left( \frac{2m}{m + m} \right) u_2 = 0 \cdot u_1 + \frac{2m}{2m} u_2 = u_2
\]
\[
v_2 = \left( \frac{2m}{m + m} \right) u_1 + \left( \frac{m - m}{m + m} \right) u_2 = \frac{2m}{2m} u_1 + 0 \cdot u_2 = u_1
\]

The equations show that in one dimensional elastic collision, when two bodies of equal mass collide after the collision their velocities are exchanged.

**Case 2: When bodies have the same mass i.e., \( m_1 = m_2 \) and second body (usually called target) is at rest \( (u_2 = 0) \),**

\[
v_1 = \left( \frac{m - m}{m + m} \right) u_1 + \left( \frac{2m}{m + m} \right) \cdot 0 = 0
\]
\[
v_2 = \left( \frac{2m}{m + m} \right) u_1 + \left( \frac{m - m}{m + m} \right) \cdot 0 = u_1
\]

Equations show that when the first body comes to rest the second body moves with the initial velocity of the first body.

**Case 3: The first body is very much lighter than the second body**

\( (m_1 \ll m_2, \frac{m_1}{m_2} \ll 1) \) then the ratio \( \frac{m_1}{m_2} \approx 0 \) and also if the target is at rest \( (u_2 = 0) \)

\[
v_1 = \left( \frac{\frac{m_1}{m_2} - 1}{\frac{m_1}{m_2} + 1} \right) u_1 + \left( \frac{2}{\frac{m_1}{m_2} + 1} \right) \cdot 0 = \left( \frac{0 - 1}{0 + 1} \right) u_1 = -u_1
\]
\[
v_2 = \left( \frac{2 \frac{m_1}{m_2}}{\frac{m_1}{m_2} + 1} \right) u_1 + \left( \frac{1 - \frac{m_1}{m_2}}{\frac{m_1}{m_2} + 1} \right) \cdot 0 = \left( \frac{2 \times 0}{0 + 1} \right) u_1 = 0
\]

The first equation implies that the first body which is lighter returns back (rebounds) in the opposite direction with the same initial velocity as it has a negative sign. The second equation implies that the second body which is heavier in mass continues to remain at rest even after collision. For example, if a ball is thrown at a fixed wall, the ball will bounce back from the wall with the same velocity with which it was thrown but in opposite direction.

**Case 4: The second body is very much lighter than the first body**

\( (m_2 \ll m_1, \frac{m_2}{m_1} \ll 1) \) then the ratio \( \frac{m_2}{m_1} \approx 0 \) and also if the target is at rest \( (u_2 = 0) \)

\[
v_1 = \left( \frac{1 - \frac{m_2}{m_1}}{1 + \frac{m_2}{m_1}} \right) u_1 + \left( \frac{2 \frac{m_2}{m_1}}{1 + \frac{m_2}{m_1}} \right) \cdot 0 = \left( \frac{1 - 0}{1 + 0} \right) u_1 = u_1
\]
\[
v_2 = \left( \frac{2}{1 + \frac{m_2}{m_1}} \right) u_1 + \left( \frac{\frac{m_2}{m_1} - 1}{1 + \frac{m_2}{m_1}} \right) \cdot 0 = \left( \frac{2}{1 + 0} \right) u_1 = 2u_1
\]

The first equation implies that the first body which is heavier continues to move with the same initial velocity. The second equation suggests that the second body which is lighter will move with twice the initial velocity of the first body. It means that the lighter body is thrown away from the point of collision.

**EXAMPLE 4.20**

A lighter particle moving with a speed of \( 10 \, \mathrm{m}\mathrm{s}^{-1} \) collides with an object of double its mass moving in the same direction with half its speed. Assume that the collision is a one dimensional elastic collision. What will be the speed of both particles after the collision?

**Solution**

Let the mass of the first body be \( m \) which moves with an initial velocity, \( \mathbf{u}_1 = 10 \, \mathrm{m}\mathrm{s}^{-1} \). Therefore, the mass of second body is \( 2m \) and its initial velocity is \( \mathbf{u}_2 = \frac{1}{2} \mathbf{u}_1 = 5 \, \mathrm{m}\mathrm{s}^{-1} \)

Then, the final velocities of the bodies can be calculated from the equations:

\[
v_1 = \left( \frac{m - 2m}{m + 2m} \right) 10 + \left( \frac{2 \times 2m}{m + 2m} \right) 5 = \left( \frac{-m}{3m} \right) 10 + \left( \frac{4m}{3m} \right) 5 = -\frac{10}{3} + \frac{20}{3} = \frac{10}{3} = 3.33 \, \mathrm{ms}^{-1}
\]
\[
v_2 = \left( \frac{2m}{m + 2m} \right) 10 + \left( \frac{2m - m}{m + 2m} \right) 5 = \left( \frac{2m}{3m} \right) 10 + \left( \frac{m}{3m} \right) 5 = \frac{20}{3} + \frac{5}{3} = \frac{25}{3} = 8.33 \, \mathrm{ms}^{-1}
\]

As the two speeds \( v_1 \) and \( v_2 \) are positive, they move in the same direction with the velocities, \( 3.33 \, \mathrm{m}\mathrm{s}^{-1} \) and \( 8.33 \, \mathrm{m}\mathrm{s}^{-1} \) respectively.

### 4.4.3 Perfect inelastic collision

In a perfectly inelastic or completely inelastic collision, the objects stick together permanently after collision such that they move with common velocity. Let the two bodies with masses \( m_1 \) and \( m_2 \) move with initial velocities \( u_{1} \) and \( u_{2} \) respectively before collision. After perfect inelastic collision both the objects move together with a common velocity \( \mathbf{v} \) as shown in Figure 4.17.

Since, the linear momentum is conserved during collisions,

\[
m_{1}u_{1} + m_{2}u_{2} = (m_{1} + m_{2})\mathbf{v}
\]
\[
\mathbf{v} = \frac{m_{1}u_{1} + m_{2}u_{2}}{m_{1} + m_{2}}
\]

**4.4.4 Loss of kinetic energy in inelastic collision**

Total kinetic energy before collision,

\[
\mathrm{KE}_{i} = \frac{1}{2} m_{1} u_{1}^{2} + \frac{1}{2} m_{2} u_{2}^{2}
\]

Total kinetic energy after collision,

\[
\mathrm{KE}_{f} = \frac{1}{2} (m_{1} + m_{2}) v^{2}
\]

Then the loss of kinetic energy is

\[
\Delta Q = KE_{i} - KE_{f} = \frac{1}{2} m_{1} u_{1}^{2} + \frac{1}{2} m_{2} u_{2}^{2} - \frac{1}{2} (m_{1} + m_{2}) v^{2}
\]

Substituting the expression for \( v \) and simplifying, we get

\[
\text{Loss of KE}, \Delta Q = \frac{1}{2} \left( \frac{m_{1} m_{2}}{m_{1} + m_{2}} \right) (u_{1} - u_{2})^{2}
\]

### 4.4.5 Coefficient of restitution (e)

Suppose we drop a rubber ball and a plastic ball on the same floor. The rubber ball will bounce back higher than the plastic ball. This is because the loss of kinetic energy for an elastic ball is much lesser than the loss of kinetic energy for a plastic ball. The amount of kinetic energy after the collision of two bodies, in general, can be measured through a dimensionless number called the coefficient of restitution (COR).

It is defined as the ratio of velocity of separation (relative velocity) after collision to the velocity of approach (relative velocity) before collision, i.e.,

\[
\mathrm{e} = \frac{\text{velocity of separation (after collision)}}{\text{velocity of approach (before collision)}} = \frac{(v_{2} - v_{1})}{(u_{1} - u_{2})}
\]

In an elastic collision, we have obtained the velocity of separation is equal to the velocity of approach i.e.,

\[
(u_{1} - u_{2}) = (v_{2} - v_{1}) \rightarrow \mathrm{e} = \frac{(v_{2} - v_{1})}{(u_{1} - u_{2})} = 1
\]

This implies that, coefficient of restitution for an elastic collision, \( \mathrm{e} = 1 \). Physically, it means that there is no loss of kinetic energy after the collision. So, the body bounces back with the same kinetic energy which is usually called as perfect elastic.

In any real collision problems, there will be some losses in kinetic energy due to collision, which means e is not always equal to unity. If the ball is perfectly plastic, it will never bounce back and therefore their separation of velocity is zero after the collision. Hence, the value of coefficient of restitution, \( \mathrm{e} = 0 \).

In general, the coefficient of restitution for a material lies between \( 0 < \mathrm{e} < 1 \).

**EXAMPLE 4.22**

Show that the ratio of velocities of equal masses in an inelastic collision when one of the masses is stationary is \( \frac{v_{1}}{v_{2}} = \frac{1 - e}{1 + e} \).

**Solution**

\[
\mathrm{e} = \frac{(v_2 - v_1)}{(u_1 - u_2)} = \frac{(v_2 - v_1)}{(u_1 - 0)} = \frac{(v_2 - v_1)}{u_1}
\]
\[
\Rightarrow v_2 - v_1 = e u_1
\]

From the law of conservation of linear momentum,

\[
m u_1 = m v_1 + m v_2 \Rightarrow u_1 = v_1 + v_2
\]

Using the equation for \( u_1 \) in the first equation, we get

\[
v_2 - v_1 = e (v_1 + v_2)
\]

On simplification, we get

\[
\frac{v_1}{v_2} = \frac{1 - e}{1 + e}
\]