---
title: ' Application and Limitations of the Method of Dimensional Analysis.'
weight: 22
extensions:
    - katex
---
{{< katex diaplay >}}  {{< /katex >}}

# Application and Limitations of the Method of Dimensional Analysis.


**This method is used to** 

(i) Convert a physical quantity from one system of units to another. 

(ii) Check the dimensional correctness of a given physical equation.

(iii) Establish relations among various physical quantities.

**(i) To convert a physical quantity from one system of units to another**

This is based on the fact that the product of the numerical values (n) and its corresponding unit (u) is a constant. i.e, n [u] = constant (or) \\(n_1\\)[\\(u_2\\)] = \\(n_2\\)[\\(u_2\\)].

Consider a physical quantity which has dimension ‘_a’_ in mass, ‘_b’_ in length and ‘_c’_ in time. If the fundamental units in one system are \\(M_1\\), \\(L_1\\) and \\(T_1\\) and the other system are \\(M_2\\), \\(L_2\\) and \\(T_2\\) respectively, then we can write,\\(n_1\\)  \\([M_1^aL_1^bT_1^C]\\)\\(n_{2}=[M_{2}^{a}L_{2}^{b}T_{2}^{c}]\\)

We have thus converted the numerical value of physical quantity from one system of units into the other system.

**EXAMPLE 1.12**

Convert 76 cm of mercury pressure into Nm−2 using the method of dimensions.

**_Solution_**

In cgs system 76 cm of mercury pressure = 76 × 13.6 × 980 dyne cm−2

The dimensional formula of pressure P is \\([ML^{−1}T^{−2}\]\\)

\\(P_{1}[M_{1}^{a}L_{1}^{b}T_{1}^{c}]=P_{2}[M_{2}^{a}L_{2}^{b}T_{2}^{c}]\\)

We have \\(P_{2}=P_{1}\left[\frac{M_{1}}{M_{2}}\right]^{a}\left[\frac{L_{1}}{L_{2}}\right]^{b}\left[\frac{T_{1}}{T_{2}}\right]^{c}\\)

\\(M₁ = 1g, M₂ = 1kg,
L₁ = 1 cm, L₂ = 1m,
T₁ = 1 s, T₂ = 1s\\)

As a =1, b= -1, and c = -2

Then

\\(P_{2}=76\times13.6\times980\left[\frac{1g}{1kg}\right]\left[\frac{1cm}{1m}\right]^{-1}\left[\frac{1s}{1s}\right]^{-1}\\)

\\(=76\times13.6\times980\left[\frac{10^{-3}kg}{1kg}\right]\left[\frac{10^{-2}m}{1m}\right]^{-1}\left[\frac{1s}{1s}\right]^{-2}\\)

\\(=76\times13.6\times980\times[10^{-3}]\times10^{2}\\)

\\(P_{2}=1.01\times10^{5}Nm^{-2}\\)


**EXAMPLE 1.13**

If the value of universal gravitational constant in SI is 6.6 × 10⁻¹¹ Nm² kg⁻² = 6.6, then find its value in CGS System?

**_Solution_**

Let \\(G_{SI}\\) be the gravitational constant in the SI system and \\(G_{cgs}\\) in the cgs system. Then

\\(G_{SI}=6.6\times10^{-11}Nm^{2}kg^{-2}\\)

\\(G_{cgs}\\)

\\(n_{2}=n_{1}\left[\frac{M_{1}}{M_{2}}\right]^{a}\left[\frac{L_{1}}{L_{2}}\right]^{b}\left[\frac{T_{1}}{T_{2}}\right]^{c}\\)

\\(G_{cgs}=G_{SI}\left[\frac{M_{1}}{M_{2}}\right]^{a}\left[\frac{L_{1}}{L_{2}}\right]^{b}\left[\frac{T_{1}}{T_{2}}\right]^{c}\\)

M₁ = 1 kg

L₁ = 1 m

T₁ = 1 s

M₂ = 1 g

L₂ = 1 cm

T₂ = 1 s

**(ii) To check the dimensional correctness of a given physical equation** Let us take the equation of motion v = u + at Apply dimensional formula on both sides [LT−1] = [LT−1] + [LT−2] [T]  [LT−1] = [LT−1] + [LT−1]

(Quantities of same dimension only can be added)

We see that the dimensions of both sides are same. Hence the equation is dimensionally correct.

**EXAMPLE 1.14**

Check the correctness of the equation \\(\frac{1}{2}mv^2 = mgh\\) using dimensional analysis

method.

**_Solution_**

Dimensional formula for

\\(\frac{1}{2}mv^2 = [M][LT^{-1}]^{2} = [ML^{2}T^{-2}]\\)

Dimensional formula for

\\(mgh = [M][LT^{-2}][L] = [ML^{2}T^{-2}]\\)

\\([ML^2T^{-2}]\\) = \\(ML^2T^{-2}\\)

Both sides are dimensionally the

same, hence the equations \\(\frac{1}{2}mv^2 = mgh\\) is dimensionally correct.

**(iii) To establish the relation among various physical quantities** If the physical quantity Q depends upon the quantities \\(Q_1\\), \\(Q_2\\) and \\(Q_3\\) ie. Q is proportional to \\(Q_1\\), \\(Q_2\\) and \\(Q_3\\).

Then,

\\(Q \propto Q_{1}^{a}Q_{2}^{b}Q_{3}^{c}\\)

\\(Q = K Q_{1}^{a}Q_{2}^{b}Q_{3}^{c}\\)

where k is a dimensionless constant. When the dimensional formula of Q, \\(Q_1\\), \\(Q_2\\) and \\(Q_3\\)

are substituted, then according to the principle of homogeneity, the powers of M, L, T are made equal on both sides of the equation. From this, we get the values of a, b, c

**EXAMPLE 1.15**

Obtain an expression for the time period T of a simple pendulum. The time period T depends on (i) mass ‘_m’_ of the bob (ii) length ‘_l’_ of the pendulum and (iii) acceleration due to gravity _g_ at the place where the pendulum is suspended. (Constant k = 2π) i.e **_Solution_**

\\(T \propto m^{a}l^{b}g^{c}\\)

\\(T = km^{a}l^{b}g^{c}\\)  

Here k is the dimensionless constant. Rewriting the above equation with dimensions

\\([T^{1}]=[M^{a}][L^{b}][LT^{-2}]^{c}\\)

\\([M^{0}L^{0}T^{1}]=[M^{a}L^{b+c}T^{-2c}]\\)

Comparing the powers of M, L and T on both sides, a=0, b+c=0, -2c=1

Solving for a,b and c a = 0, b = 1/2, and c = −1/2

From the above equation T = km0 l \\(C^{1/2}g^{-1/2}\\)

\\(T = k\left(\frac{l}{g}\right)^{1/2} = k\sqrt{\frac{l}{g}}\\)

Experimentally k = 2π, hence \\(T = 2\pi\sqrt{\frac{l}{g}}\\)

**Limitations of Dimensional analysis**

1. This method gives no information about the dimensionless constants in the formula like 1, 2, ……..π, e (Euler number), etc.

2. This method cannot decide whether the given quantity is a vector or a scalar.

3. This method is not suitable to derive relations involving trigonometric, exponential and logarithmic functions.

4. It cannot be applied to an equation involving more than three physical quantities.

5. It can only check on whether a physical relation is dimensionally correct but not the correctness of the relation. For example using
dimensional analysis, \\(s = ut + \frac{1}{3}\\)
is dimensionally correct whereas the correct relation is \\(s = ut + \frac{1}{3}\\)