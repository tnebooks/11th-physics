---
title: 'Propagation of errors'
weight: 16
extensions:
    - katex
---
{{< katex diaplay >}}
{{< /katex >}}

# Propagation of errors

A number of measured quantities may be involved in the final calculation of an experiment. Different types of instruments might have been used for taking readings. Then we may have to look at the errors in measuring various quantities, collectively.

The error in the final result depends on

(i) The errors in the individual measurements

(ii) On the nature of mathematical operations performed to get the final result. So we should know the rules to combine the errors.

The various possibilities of the propagation or combination of errors in different mathematical operations are discussed below:

**(i) Error in the sum of two quantities** 

Let ∆A and ∆B be the absolute errors in the two quantities A and B respectively. Then,

Measured value of A = A ± ∆A 


Measured value of B = B ± ∆B 


Consider the sum, Z = A + B

The error ∆Z in Z is then given by

Z ± ∆Z = (A ± ∆A) + (B ± ∆B)

\= (A + B) ± (∆A + ∆B)

\= Z ± (∆A + ∆B)

(or) ∆Z = ∆A + ∆B (1.3)

The maximum possible error in the sum of two quantities is equal to the sum of the absolute errors in the individual quantities.

**EXAMPLE 1.5**

Two resistances R1 = (100 ± 3) \\(\Omega\\), R2 = (150 ± 2) \\(\Omega\\), are connected in series. What is their equivalent resistance?

**_Solution_**

R1 = 100 ± =3 1502\\(\Omega\\); _R_ ± 2\\(\Omega\\)

Equivalent resistance R = ? 

Equivalent resistance R = R\\(_1\\) + _R_\\(_2\\)

\= (100 ± +3 150) ( ± 2)

\= (100 + 150) ± (3 + 2)

R = (250 ± 5) \\(\Omega\\)

**(ii) Error in the difference of two quantities**

Let ∆A and ∆B be the absolute errors in the two quantities, A and B, respectively. Then, Measured value of A = A ± ∆A Measured value of B = B ± ∆B Consider the difference, Z = A – B The error ∆Z in Z is then given by Z ± ∆Z = (A ± ∆A) – (B ± ∆B)  

\= (A − B) ± ∆A ± ∆B

\= Z ± ∆A ± ∆B

(or) ∆Z = ∆A + ∆B………………(1.4)

The maximum error in difference of two quantities is equal to the sum of the absolute errors in the individual quantities.

**EXAMPLE 1.6**

The temperatures of two bodies measured by a thermometer are t1 = (20 + 0.5)°C, t2 = (50 ± 0.5)°C. Calculate the temperature difference and the error therein.

**_Solution_**

t\\(_1\\) = (20 ± 0 5. )°C t\\(_2\\) = (50 ± 0 5. )°C

temperature difference t=?

t = t\\(_2\\) - t\\(_1\\) = (50 ± 0 5. ) - (20 ± 0 5. )°C

(Using equation1.4)

\= (50 – 20) ± (0.5+0.5)

t = (30 ± 1)°C

**(iii) Error in the product of two quantities** Let ∆A and ∆B be the absolute errors in the two quantities A, and B, respectively. Consider the product Z = AB The error ∆Z in Z is given by Z ± ∆Z = (A ± ∆A) (B ± ∆B)

\= (AB) ± (A ∆B) ± (B ∆A) ± (∆A . ∆B)

Dividing L.H.S by Z and R.H.S by AB, we get,

\\( 1 ± \frac{∆Z}{Z} = 1 ± \frac{∆B}{B} ± \frac{∆A}{A} ± \frac{∆A}{A} . \frac{∆B}{B} \\)

As ∆A /A, ∆B / B are both small quantities, their product term \\(\frac{∆A}{A}.\frac{∆B}{B}\\) can be neglected. The maximum fractional error in Z is

\\(\frac{∆Z}{Z} =± \lparen \frac{∆A}{A}+\frac{∆B}{B}\rparen \\)
 (1.5)

The maximum fractional error in the product of two quantities is equal to the sum of the fractional errors in the individual quantities.

\[Alternative method is given in Appendix A1.2\]

**EXAMPLE 1.7**

The length and breadth of a rectangle are (5.7 ± 0 1. ) cm and (3.4 ± 0 2. ) cm respectively. Calculate the area of the rectangle with error limits.

**_Solutions_**

Length l \= (5.7 ± 0 1. ) cm

Breadth b =(3.4 ± 0 2. ) cm

Area A with error limit = A ± ∆A = ?

Area A = l × b = 5.7 × 3.4 = 19.38 = 19.4 cm2

\\(\frac{\Delta A}{A} = \frac{\Delta l}{l} + \frac{\Delta b}{b}\\)

\\(\Delta A = \left( \frac{\Delta l}{l} + \frac{\Delta b}{b} \right) A
\\)

\\(\Delta A = \left( \frac{0.1}{5.7} + \frac{0.2}{3.4} \right) 19.4
\\)


\= (0.0175+0.0588) × 19.4 

= 1.48 = 1.5

Area with error limit 

A = (19.4±1.5) cm2  

**(iv) Error in the division or quotient of two quantities** Let ∆A and ∆B be the absolute errors in the two quantities A and B respectively.

Consider the quotient, \\(Z=\frac{A}{B}\\)

The error ∆Z in Z is given by

\\(Z \pm \Delta Z = \frac{A \pm \Delta A}{B \pm \Delta B} = \frac{A \left( 1 \pm \frac{\Delta A}{A} \right)}{B \left( 1 \pm \frac{\Delta B}{B} \right)}
\\)

\\(= \frac{A}{B} \left( 1 \pm \frac{\Delta A}{A} \right) \left( 1 \pm \frac{\Delta B}{B} \right)^{-1}
\\)

\\(Z \pm \Delta Z = Z \left( 1 \pm \frac{\Delta A}{A} \right) \left( 1 \pm \frac{\Delta B}{B} \right)
\\)
\\(\text{[using }(1 + x)^n \approx 1 + nx \text{, when } x \ll 1 \text{]}
\\)

Dividing both sides by Z, we get,

\\(1 \pm \frac{\Delta Z}{Z} = \left( 1 \pm \frac{\Delta A}{A} \right) \left( 1 \pm \frac{\Delta B}{B} \right)
\\)

\\(= 1 \pm \frac{\Delta A}{A} \pm \frac{\Delta B}{B} \pm \frac{\Delta A}{A} \cdot \frac{\Delta B}{B}
\\)

As the terms ∆A/A and ∆B/B are small, their product term can be neglected.

The maximum fractional error in Z is

given by \\(\frac{\Delta Z}{Z} = \left( \frac{\Delta A}{A} + \frac{\Delta B}{B} \right)
\\)  (1.6)

The maximum fractional error in the quotient of two quantities is equal to the sum of their individual fractional errors.

(Alternative method is given in Appendix A1.2)

**EXAMPLE 1.8**

The voltage across a wire is (100 ± 5)V and the current passing through it is (10 ± 0.2) A. Find the resistance of the wire.

**_Solution_**

Voltage V = (100±5)V Current I = (10±0.2) A Resistance R = ?

Then resistance R is given by Ohm’s law,
R = \\(\frac {V} {I}\\)

\\(\frac{100}{10} = 10 \, \Omega
\\)

\\(\frac{\Delta R}{R} = \left( \frac{\Delta V}{V} + \frac{\Delta I}{I} \right)
\\)

\\(\Delta R = \left( \frac{\Delta V}{V} + \frac{\Delta I}{I} \right) R
\\)

\\(\Delta R = \left( \frac{5}{100} + \frac{0.2}{10} \right) 10
\\)

\= (0.05 + 0.02)10

\= 0.07 × 10 = 0.7

The resistance R = (10 ± 0.7)Ω

**(v) Error in the power of a quantity** Consider the nth power of A, Z = An
The error ∆Z in Z is given by

\\(Z \pm \Delta Z = (A \pm \Delta A)^n = A^n \left(1 \pm \frac{\Delta A}{A}\right)^n = Z \left(1 \pm n \frac{\Delta A}{A}\right)\\) 

We get \[(1+x)n ≈1+nx, when x<<1\] neglecting remaining terms, Dividing both sides by Z

\\(1 \pm \frac{\Delta Z}{Z} = 1 \pm n \frac{\Delta A}{A} \text{ or}\\)

\\(\frac{\Delta Z}{Z} = n \frac{\Delta A}{A}\\)


The fractional error in the nth power of a quantity is n times the fractional error in that quantity.

**General rule**: If \\(Z = \frac{A^n B^m}{C^p}\\) Then
maximum fractional error in Z is given by \\(\frac{\Delta Z}{Z} = p \frac{\Delta A}{A} + q \frac{\Delta B}{B} + r \frac{\Delta C}{C}\\) The percentage error in Z is given by


\\([\frac{\Delta Z}{Z}\times100=p\frac{\Delta A}{A}\times100+q\frac{\Delta B}{B}\times100]\\)

\\([+r\frac{\Delta C}{C}\times100]\\)


**EXAMPLE 1.9**

A physical quantity _x i_s given by _x_ \\([=\frac{a^{2}b^{3}}{c\sqrt{d}}.]\\) If the percentage errors of measurement in a, b, c and d are 4%, 2%, 3% and 1% respectively, then calculate the percentage error in the calculation of _x._ (NEET 2013)

**_Solution_**

Given _x_ = \\([=\frac{a^{2}b^{3}}{c\sqrt{d}}.]\\)

The percentage error in x is given by

\\([\frac{\Delta x}{x}\times100=2\frac{\Delta a}{a}\times100+3\frac{\Delta b}{b}\times100+\frac{\Delta c}{c}\times100+\frac{1}{2}\frac{\Delta d}{d}\times100]\\)

= (2 × 4%) + (3 × 2%) + (1 × 3%) +
(½ ×1%)

= 8% +6%+3% +0.5% 

The percentage error is x = 17.5%