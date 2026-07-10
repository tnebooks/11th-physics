---
title: "Theory of errors"
weight: 6
references:
  links: []

  books:
    - b1:
        title: "Units and Measurements"
        url: "https://ncert.nic.in/textbook/pdf/keph101.pdf"
---
## 1.6 THEORY OF ERRORS

The foundation of all experimental science and technology is measurement. The result obtained from any measurement will contain some uncertainty. Such an uncertainty is termed error. Any calculation made using the measured values will also have an error. It is not possible to make exact measurements in an experiment.

In measurements, two different terms, accuracy and precision, are used and need to be distinguished at this stage. Accuracy refers to how far we are from the true value, and precision refers to how well we measure.

> In India, the National Physical Laboratory (New Delhi) has the responsibility of maintenance and improvement of physical standards of length, mass, time, etc.

### 1.6.1 Accuracy and Precision

Let us say, you know your true height is exactly $5'9''$. You first measure your height with a yardstick and get the value $5'0''$. Your measurement is hence not accurate. Now you measure your height with a laser yardstick and get $5'9''$ as the value. Now your measurement is accurate. The true value is also called theoretical value. The level of accuracy required for each application varies greatly. Highly accurate data can be very difficult to produce and compile. For example, if you consistently measure your height as $5'0''$ with a yard stick, your measurements are precise. The level of precision required for different applications varies to a great extent. Engineering projects such as road and utility construction require very precise information measured to the millimeter or one-tenth of an inch.

If a measurement is precise, that does not necessarily mean that it is accurate. However, if the measurement is consistently accurate, it is also precise.

For example, if the temperature outside a building is $40^\circ$C as measured by a weather thermometer and if the real outside temperature is $40^\circ$C, the thermometer is accurate. If the thermometer consistently registers this exact temperature in a row, the thermometer is precise.

Consider another example. Let the temperature of a refrigerator repeatedly measured by a thermometer be given as $10.4^\circ$C, $10.2^\circ$C, $10.3^\circ$C, $10.1^\circ$C, $10.2^\circ$C, $10.1^\circ$C, $10.1^\circ$C, $10.1^\circ$C. However, if the real temperature inside the refrigerator is $9^\circ$C, we say that the thermometer is not accurate (it is almost one degree off the true value), but since all the measured values are close to $10^\circ$C, hence it is precise.

**A visual example:** Target shooting is an example which explains the difference between accuracy and precision. In Figure 1.9 (a), the shots are focused so as to reach the bull's eye (midpoint), but the arrows have reached only around this point. Hence the shots are not accurate and also not precise.

![](<fig 1.8.png>)

In Figure 1.9 (b), all the shots are close to each other but not at the central point. Hence the shots are said to be precise but not accurate. In Figure 1.9 (c), the shots are closer and also at the central point. Hence the shots are both precise and accurate.

**A numerical example:** The true value of a certain length is nearly $5.678$ cm. In one experiment, using a measuring instrument of resolution $0.1$ cm, the measured value is found to be $5.5$ cm. In another experiment using a measuring instrument of greater resolution, say $0.01$ cm, the length is found to be $5.38$ cm. We find that the first measurement is more accurate as it is closer to the true value, but it has lesser precision. On the contrary, the second measurement is less accurate, but it is more precise.

### 1.6.2 Errors in Measurement

The uncertainty in a measurement is called an error. Random error, systematic error and gross error are the three possible errors.

**i) Systematic errors**

Systematic errors are reproducible inaccuracies that are consistently in the same direction. These occur often due to a problem that persists throughout the experiment. Systematic errors can be classified as follows:

1. **Instrumental errors:** When an instrument is not calibrated properly at the time of manufacture, instrumental errors may arise. If a measurement is made with a meter scale whose end is worn out, the result obtained will have errors. These errors can be corrected by choosing the instrument carefully.
2. **Imperfections in experimental technique or procedure:** These errors arise due to the limitations in the experimental arrangement. As an example, while performing experiments with a calorimeter, if there is no proper insulation, there will be radiation losses. This results in errors and to overcome these, necessary correction has to be applied.
3. **Personal errors:** These errors are due to individuals performing the experiment, may be due to incorrect initial setting up of the experiment or carelessness of the individual making the observation due to improper precautions.
4. **Errors due to external causes:** The change in the external conditions during an experiment can cause error in measurement. For example, changes in temperature, humidity, or pressure during measurements may affect the result of the measurement.
5. **Least count error:** Least count is the smallest value that can be measured by the measuring instrument, and the error due to this measurement is least count error. The instrument's resolution hence is the cause of this error. Least count error can be reduced by using a high precision instrument for the measurement.

**ii) Random errors**

Random errors may arise due to random and unpredictable variations in experimental conditions like pressure, temperature, voltage supply etc. Errors may also be due to personal errors by the observer who performs the experiment. Random errors are sometimes called "chance error". When different readings are obtained by a person every time he repeats the experiment, personal error occurs. For example, consider the case of the thickness of a wire measured using a screw gauge. The readings taken may be different for different trials. In this case, a large number of measurements are made and then the arithmetic mean is taken.

If $n$ number of trial readings are taken in an experiment, and the readings are $a_1, a_2, a_3, \ldots, a_n$. The arithmetic mean is:

$$
a_m = \frac{a_1 + a_2 + a_3 + \ldots + a_n}{n} \tag{1.1}
$$

or

$$
a_m = \frac{1}{n} \sum_{i=1}^{n} a_i \tag{1.2}
$$

Usually this arithmetic mean is taken as the best possible true value of the quantity.

Certain procedures to be followed to minimize experimental errors, along with examples are shown in Table 1.8.

**iii) Gross Error**

The error caused due to the shear carelessness of an observer is called gross error. For example: 

(i) Reading an instrument without setting it properly. 

(ii) Taking observations in a wrong manner without bothering about the sources of errors and the precautions. 

(iii) Recording wrong observations. 

(iv) Using wrong values of the observations in calculations. 

These errors can be minimized only when an observer is careful and mentally alert.

---
**Table 1.8 Minimizing Experimental Error**

---
| Type of error | Example | How to minimize it |
|---------------|---------|---------------------|
| Random error | Suppose you measure the mass of a ring three times using the same balance and get slightly different values: $15.46$ g, $15.42$ g, $15.44$ g | Take more data. Random errors can be evaluated through statistical analysis and can be reduced by averaging over a large number of observations. |
| Systematic error | Suppose the cloth tape measure that you use to measure the length of an object has been stretched out from years of use. (As a result all of the length measurements are not correct). | Systematic errors are difficult to detect and cannot be analysed statistically, because all of the data is in the same direction (either too high or too low). |
---

### 1.6.3 Error Analysis

**i) Absolute Error**

The magnitude of difference between the true value and the measured value of a quantity is called absolute error. If $a_1, a_2, a_3, \ldots, a_n$ are the measured values of any quantity $a$ in an experiment performed $n$ times, then the arithmetic mean of these values is called the true value ($a_m$) of the quantity.

$$
a_m = \frac{a_1 + a_2 + a_3 + \ldots + a_n}{n} = \frac{1}{n} \sum_{i=1}^{n} a_i
$$

The absolute error in measured values is given by:

$$
\begin{array}{l}
|\Delta a_1| = |a_m - a_1| \\
|\Delta a_2| = |a_m - a_2| \\
\vdots \\
|\Delta a_n| = |a_m - a_n|
\end{array}
$$

**ii) Mean Absolute Error**

The arithmetic mean of absolute errors in all the measurements is called the mean absolute error.

$$
\Delta a_m = \frac{|\Delta a_1| + |\Delta a_2| + |\Delta a_3| + \ldots + |\Delta a_n|}{n} = \frac{1}{n} \sum_{i=1}^{n} |\Delta a_i|
$$

If $a_m$ is the true value and $\Delta a_m$ is the mean absolute error then the magnitude of the quantity may lie between $a_m + \Delta a_m$ and $a_m - \Delta a_m$.

**iii) Relative Error**

The ratio of the mean absolute error to the mean value is called relative error. This is also called as fractional error. Thus

$$
\text{Relative error} = \frac{\text{Mean absolute error}}{\text{Mean value}} = \frac{\Delta a_m}{a_m}
$$

Relative error expresses how large the absolute error is compared to the total size of the object measured. For example, a driver's speedometer shows that his car is travelling at $60$ km h$^{-1}$ when it is actually moving at $62$ km h$^{-1}$. Then absolute error of speedometer is $62 - 60 = 2$ km h$^{-1}$. Relative error of the measurement is $2$ km h$^{-1} / 62$ km h$^{-1} = 0.032$.

**iv) Percentage Error**

The relative error expressed as a percentage is called percentage error.

$$
\text{Percentage error} = \frac{\Delta a_m}{a_m} \times 100\%
$$

A percentage error very close to zero means one is close to the targeted value, which is good and acceptable. It is always necessary to understand whether error is due to impression of equipment used or a mistake in the experimentation.

---

**EXAMPLE 1.4**

In a series of successive measurements in an experiment, the readings of the period of oscillation of a simple pendulum were found to be $2.63$ s, $2.56$ s, $2.42$ s, $2.71$ s and $2.80$ s. Calculate (i) the mean value of the period of oscillation (ii) the absolute error in each measurement (iii) the mean absolute error (iv) the relative error (v) the percentage error. Express the result in proper form.

**Solution**

$t_1 = 2.63$ s, $t_2 = 2.56$ s, $t_3 = 2.42$ s, $t_4 = 2.71$ s, $t_5 = 2.80$ s

(i) 
$$
T_m = \frac{t_1 + t_2 + t_3 + t_4 + t_5}{5} = \frac{2.63 + 2.56 + 2.42 + 2.71 + 2.80}{5} = \frac{13.12}{5} = 2.624 \text{ s}
$$

$T_m = 2.62$ s (Rounded off to 2nd decimal place)

(ii) Absolute error $|\Delta T| = |T_m - t|$

$$
\begin{array}{l}
\Delta T_1 = |2.62 - 2.63| = +0.01 \text{ s} \\
\Delta T_2 = |2.62 - 2.56| = +0.06 \text{ s} \\
\Delta T_3 = |2.62 - 2.42| = +0.20 \text{ s} \\
\Delta T_4 = |2.62 - 2.71| = +0.09 \text{ s} \\
\Delta T_5 = |2.62 - 2.80| = +0.18 \text{ s}
\end{array}
$$

(iii) Mean absolute error:

$$
\Delta T_m = \frac{0.01 + 0.06 + 0.20 + 0.09 + 0.18}{5} = \frac{0.54}{5} = 0.108 \text{ s} = 0.11 \text{ s} \text{ (Rounded off to 2nd decimal place)}
$$

(iv) Relative error:

$$
S_T = \frac{\Delta T_m}{T_m} = \frac{0.11}{2.62} = 0.0419 = 0.04
$$

(v) Percentage error in $T = 0.04 \times 100\% = 4\%$

(vi) Time period of simple pendulum $T = (2.62 \pm 0.11)$ s

---

### 1.6.4 Propagation of Errors

A number of measured quantities may be involved in the final calculation of an experiment. Different types of instruments might have been used for taking readings. Then we may have to look at the errors in measuring various quantities, collectively. The error in the final result depends on 

(i) The errors in the individual measurements 

(ii) On the nature of mathematical operations performed to get the final result. So we should know the rules to combine the errors.

The various possibilities of the propagation or combination of errors in different mathematical operations are discussed below:

**(i) Error in the sum of two quantities**

Let $\Delta A$ and $\Delta B$ be the absolute errors in the two quantities $A$ and $B$ respectively. Then,

 Measured value of $A = A \pm \Delta A$,
 
Measured value of $B = B \pm \Delta B$. 

Consider the sum, $Z = A + B$. 

The error $\Delta Z$ in $Z$ is then given by

$$
Z \pm \Delta Z = (A \pm \Delta A) + (B \pm \Delta B) = (A + B) \pm (\Delta A + \Delta B) = Z \pm (\Delta A + \Delta B)
$$

(or)

$$
\Delta Z = \Delta A + \Delta B \tag{1.3}
$$

The maximum possible error in the sum of two quantities is equal to the sum of the absolute errors in the individual quantities.

**EXAMPLE 1.5**

Two resistances $R_1 = (100 \pm 3) \Omega$, $R_2 = (150 \pm 2) \Omega$, are connected in series. What is their equivalent resistance?

**Solution**

$R_1 = 100 \pm 3 \Omega$, $R_2 = 150 \pm 2 \Omega$. Equivalent resistance $R = R_1 + R_2 = (100 \pm 3) + (150 \pm 2) = (100 + 150) \pm (3 + 2) = (250 \pm 5) \Omega$.

**(ii) Error in the difference of two quantities**

Let $\Delta A$ and $\Delta B$ be the absolute errors in the two quantities $A$ and $B$ respectively. Consider the difference, $Z = A - B$. The error $\Delta Z$ in $Z$ is then given by

$$
Z \pm \Delta Z = (A \pm \Delta A) - (B \pm \Delta B) = (A - B) \pm (\Delta A + \Delta B) = Z \pm (\Delta A + \Delta B)
$$

or

$$
\Delta Z = \Delta A + \Delta B \tag{1.4}
$$

The maximum error in difference of two quantities is equal to the sum of the absolute errors in the individual quantities.

**EXAMPLE 1.6**

The temperatures of two bodies measured by a thermometer are $t_1 = (20 \pm 0.5)^\circ$C, $t_2 = (50 \pm 0.5)^\circ$C. Calculate the temperature difference and the error therein.

**Solution**

$t = t_2 - t_1 = (50 \pm 0.5) - (20 \pm 0.5) = (50 - 20) \pm (0.5 + 0.5) = (30 \pm 1)^\circ$C.

**(iii) Error in the product of two quantities**

Let $\Delta A$ and $\Delta B$ be the absolute errors in the two quantities $A$ and $B$ respectively. Consider the product $Z = AB$. The error $\Delta Z$ in $Z$ is given by

$$
Z \pm \Delta Z = (A \pm \Delta A)(B \pm \Delta B) = (AB) \pm (A \Delta B) \pm (B \Delta A) \pm (\Delta A \cdot \Delta B)
$$

Dividing L.H.S by $Z$ and R.H.S by $AB$, we get,

$$
1 \pm \frac{\Delta Z}{Z} = \left(1 \pm \frac{\Delta A}{A}\right) \left(1 \pm \frac{\Delta B}{B}\right) = 1 \pm \frac{\Delta A}{A} \pm \frac{\Delta B}{B} \pm \frac{\Delta A}{A} \cdot \frac{\Delta B}{B}
$$

As $\Delta A/A$, $\Delta B/B$ are both small quantities, their product term can be neglected. The maximum fractional error in $Z$ is

$$
\frac{\Delta Z}{Z} = \pm \left( \frac{\Delta A}{A} + \frac{\Delta B}{B} \right) \tag{1.5}
$$

The maximum fractional error in the product of two quantities is equal to the sum of the fractional errors in the individual quantities.

**EXAMPLE 1.7**

The length and breadth of a rectangle are $(5.7 \pm 0.1)$ cm and $(3.4 \pm 0.2)$ cm respectively. Calculate the area of the rectangle with error limits.

**Solution**

Length $l = (5.7 \pm 0.1)$ cm, Breadth $b = (3.4 \pm 0.2)$ cm. Area $A = l \times b = 5.7 \times 3.4 = 19.38 = 19.4$ cm$^2$.

$$
\frac{\Delta A}{A} = \frac{\Delta l}{l} + \frac{\Delta b}{b}
$$

$$
\Delta A = \left( \frac{0.1}{5.7} + \frac{0.2}{3.4} \right) \times 19.4 = (0.0175 + 0.0588) \times 19.4 = 1.48 = 1.5
$$

Area with error limit $A = (19.4 \pm 1.5)$ cm$^2$.

**(iv) Error in the division or quotient of two quantities**

Let $\Delta A$ and $\Delta B$ be the absolute errors in the two quantities $A$ and $B$ respectively. Consider the quotient $Z = \frac{A}{B}$. The error $\Delta Z$ in $Z$ is given by

$$
Z \pm \Delta Z = \frac{A \pm \Delta A}{B \pm \Delta B} = \frac{A \left(1 \pm \frac{\Delta A}{A}\right)}{B \left(1 \pm \frac{\Delta B}{B}\right)} = Z \left(1 \pm \frac{\Delta A}{A}\right) \left(1 \pm \frac{\Delta B}{B}\right)^{-1}
$$

or

$$
Z \pm \Delta Z = Z \left(1 \pm \frac{\Delta A}{A}\right) \left(1 \mp \frac{\Delta B}{B}\right) \quad \text{[using $(1+x)^n \approx 1+nx$, when $x \ll 1$]}
$$

Dividing both sides by $Z$, we get

$$
1 \pm \frac{\Delta Z}{Z} = 1 \pm \frac{\Delta A}{A} \mp \frac{\Delta B}{B} \mp \frac{\Delta A}{A} \cdot \frac{\Delta B}{B}
$$

As the terms $\Delta A/A$ and $\Delta B/B$ are small, their product term can be neglected. The maximum fractional error in $Z$ is given by

$$
\frac{\Delta Z}{Z} = \frac{\Delta A}{A} + \frac{\Delta B}{B} \tag{1.6}
$$

The maximum fractional error in the quotient of two quantities is equal to the sum of their individual fractional errors.

**EXAMPLE 1.8**

The voltage across a wire is $(100 \pm 5)$ V and the current passing through it is $(10 \pm 0.2)$ A. Find the resistance of the wire.

**Solution**

Voltage $V = (100 \pm 5)$ V, Current $I = (10 \pm 0.2)$ A. Resistance $R = \frac{V}{I} = \frac{100}{10} = 10 \Omega$.

$$
\frac{\Delta R}{R} = \frac{\Delta V}{V} + \frac{\Delta I}{I}
$$

$$
\Delta R = \left( \frac{5}{100} + \frac{0.2}{10} \right) \times 10 = (0.05 + 0.02) \times 10 = 0.07 \times 10 = 0.7
$$

The resistance $R = (10 \pm 0.7) \Omega$.

**(v) Error in the power of a quantity**

Consider the $n$th power of $A$, $Z = A^n$. The error $\Delta Z$ in $Z$ is given by

$$
Z \pm \Delta Z = (A \pm \Delta A)^n = A^n \left(1 \pm \frac{\Delta A}{A}\right)^n = Z \left(1 \pm n \frac{\Delta A}{A}\right)
$$

[using $(1+x)^n \approx 1+nx$, when $x \ll 1$]. Dividing both sides by $Z$,

$$
1 \pm \frac{\Delta Z}{Z} = 1 \pm n \frac{\Delta A}{A}
$$

or

$$
\frac{\Delta Z}{Z} = n \frac{\Delta A}{A} \tag{1.7}
$$

The fractional error in the $n$th power of a quantity is $n$ times the fractional error in that quantity.

**General rule:** If $Z = \frac{A^p B^q}{C^r}$, then the maximum fractional error in $Z$ is given by

$$
\frac{\Delta Z}{Z} = p \frac{\Delta A}{A} + q \frac{\Delta B}{B} + r \frac{\Delta C}{C}
$$

The percentage error in $Z$ is given by

$$
\frac{\Delta Z}{Z} \times 100 = p \left( \frac{\Delta A}{A} \times 100 \right) + q \left( \frac{\Delta B}{B} \times 100 \right) + r \left( \frac{\Delta C}{C} \times 100 \right)
$$

---

**EXAMPLE 1.9**

A physical quantity $x$ is given by $x = \frac{a^2 b^3}{c d^{1/2}}$. If the percentage errors of measurement in $a$, $b$, $c$ and $d$ are $4\%$, $2\%$, $3\%$ and $1\%$ respectively, then calculate the percentage error in the calculation of $x$. (NEET 2013)

**Solution**

Given $x = \frac{a^2 b^3}{c d^{1/2}}$. The percentage error in $x$ is given by

$$
\frac{\Delta x}{x} \times 100 = 2 \left( \frac{\Delta a}{a} \times 100 \right) + 3 \left( \frac{\Delta b}{b} \times 100 \right) + 1 \left( \frac{\Delta c}{c} \times 100 \right) + \frac{1}{2} \left( \frac{\Delta d}{d} \times 100 \right)
$$

$$
= (2 \times 4\%) + (3 \times 2\%) + (1 \times 3\%) + \left( \frac{1}{2} \times 1\% \right)
$$

$$
= 8\% + 6\% + 3\% + 0.5\% = 17.5\%
$$

The percentage error in $x$ is $17.5\%$.