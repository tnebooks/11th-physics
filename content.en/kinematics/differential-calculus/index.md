---
title: 'differential calculus'
weight: 7
---

# DIFFERENTIAL CALCULUS


**The Concept of a function** 

1) Any physical quantity is represented by a "function" in mathematics. Take the example of temperature {{< katex >}}\mathrm{T}{{< /katex >}}. We know that the temperature of the surroundings is changing throughout the day. It increases till noon and decreases in the evening. At any
time " {{< katex >}}\mathrm{t}{{< /katex >}} " the temperature {{< katex >}}\mathrm{T}{{< /katex >}} has a unique value. Mathematically this variation can be represented by the notation ' {{< katex >}}\mathrm{T}(\mathrm{t}){{< /katex >}} ' and it should be called "temperature as a function of time". It implies that if the value of ' {{< katex >}}t{{< /katex >}} ' is given, then the function " {{< katex >}}\mathrm{T}(\mathrm{t}){{< /katex >}} " will give the value of the temperature at that time ' {{< katex >}}t{{< /katex >}} '. Similarly, the position of a bus in motion along the {{< katex >}}\mathrm{x}{{< /katex >}} direction can be represented by {{< katex >}}x(t){{< /katex >}} and this is called ' {{< katex >}}x{{< /katex >}} ' as a function of time'. Here ' {{< katex >}}x{{< /katex >}} ' denotes the {{< katex >}}\mathrm{x}{{< /katex >}} coordinate.

**_Example_**

Consider a function {{< katex >}}f(x)=x^{2}{{< /katex >}}. Sometimes it is also represented as {{< katex >}}y=x^{2}{{< /katex >}}. Here {{< katex >}}y{{< /katex >}} is called the dependent variable and {{< katex >}}\mathrm{x}{{< /katex >}} is called independent variable. It means as {{< katex >}}x{{< /katex >}} changes, {{< katex >}}\mathrm{y}{{< /katex >}} also changes. Once a physical quantity is represented by a function, one can study the variation of the function over time or over the independent variable on which the quantity depends. Calculus is the branch of mathematics used to analyse the change of any quantity.

If a function is represented by {{< katex >}}y=f(x){{< /katex >}}, then {{< katex >}}d y / d x{{< /katex >}} represents the derivative of {{< katex >}}y{{< /katex >}} with respect to {{< katex >}}x{{< /katex >}}. Mathematically this represents the variation of {{< katex >}}y{{< /katex >}} with respect to change in {{< katex >}}\mathrm{x}{{< /katex >}}, for various continuous values of {{< katex >}}\mathrm{x}{{< /katex >}}.

Mathematically the derivative {{< katex >}}\mathrm{dy} / \mathrm{dx}{{< /katex >}} is defined as follows

{{< katex >}}
\begin{aligned}
\frac{d y}{d x} & =\lim _{\Delta x \rightarrow 0} \frac{y(x+\Delta x)-y(x)}{\Delta x} \\
& =\lim _{\Delta x \rightarrow 0} \frac{\Delta y}{\Delta x}
\end{aligned}
{{< /katex >}}

{{< katex >}}\frac{d y}{d x}{{< /katex >}} represents the limit that the quantity {{< katex >}}\frac{\Delta y}{\Delta x}{{< /katex >}} attains, as {{< katex >}}\Delta x{{< /katex >}} tends to zero.
Graphically this is represented as shown in Figure 2.28.

![Alt text](<./fig-2.28.png>)

**Figure 2.28 Derivative of a function**

**EXAMPLE 2.18**

Consider the function {{< katex >}}y=x^{2}{{< /katex >}}. Calculate the derivative {{< katex >}}\frac{d y}{d x}{{< /katex >}} using the concept of limit, at the point {{< katex >}}x=2{{< /katex >}}.

**_Solution_**

Let us take two points given by

{{< katex >}}
\mathrm{x}_{1}=2 \text { and } \mathrm{x}_{2}=3 \text {, then } \mathrm{y}_{1}=4 \text { and } \mathrm{y}_{2}=9
{{< /katex >}}

Here {{< katex >}}\Delta x=1{{< /katex >}} and {{< katex >}}\Delta y=5{{< /katex >}}

Then

{{< katex >}}\frac{\Delta y}{\Delta x}=\frac{9-4}{3-2}=5{{< /katex >}}

If we take {{< katex >}}\mathrm{x}_{1}=2{{< /katex >}} and {{< katex >}}\mathrm{x}_{2}=2.5{{< /katex >}}, then {{< katex >}}\mathrm{y}_{1}=4{{< /katex >}} and {{< katex >}}\mathrm{y}_{2}=(2.5)^{2}=6.25{{< /katex >}}

{{< katex >}}
\text { Here } \Delta x=0.5=\frac{1}{2} \text { and } \Delta y=2.25
{{< /katex >}}

Then

{{< katex >}}\frac{\Delta y}{\Delta x}=\frac{6.25-4}{0.5}=4.5{{< /katex >}}

If we take {{< katex >}}\mathrm{x}_{1}=2{{< /katex >}} and {{< katex >}}\mathrm{x}_{2}=2.25{{< /katex >}}, then {{< katex >}}\mathrm{y}_{1}=4{{< /katex >}} and {{< katex >}}\mathrm{y}_{2}=5.0625{{< /katex >}}

{{< katex >}}
\text { Here } \Delta x=0.25=\frac{1}{4}, \Delta y=1.0625
{{< /katex >}}

{{< katex >}}\frac{\Delta y}{\Delta x}=\frac{5.0625-4}{0.25}=\frac{(5.0625-4)}{\frac{1}{4}}{{< /katex >}}

{{< katex >}}
=4(5.0625-4)=4.25
{{< /katex >}}

If we take {{< katex >}}\mathrm{x}_{1}=2{{< /katex >}} and {{< katex >}}\mathrm{x}_{2}=2.1{{< /katex >}}, then {{< katex >}}\mathrm{y}_{1}=4{{< /katex >}} and {{< katex >}}\mathrm{y}_{2}=4.41{{< /katex >}}

{{< katex >}}
\begin{gathered}
\text { Here } \Delta x=0.1=\frac{1}{10} \text { and } \\
\frac{\Delta y}{\Delta x}=\frac{(4.41-4)}{\frac{1}{10}}=10(4.41-4)=4.1
\end{gathered}
{{< /katex >}}

These results are tabulated as shown below:

| {{< katex >}}\mathrm{x}_{1}{{< /katex >}} | {{< katex >}}\mathrm{x}_{2}{{< /katex >}} | {{< katex >}}\Delta x{{< /katex >}} | {{< katex >}}\mathrm{y}_{1}{{< /katex >}} | {{< katex >}}\mathrm{y}_{2}{{< /katex >}} | {{< katex >}}\frac{\Delta y}{\Delta x}{{< /katex >}} |
| :--- | :--- | :--- | :---: | :--- | :--- |
| 2 | 2.25 | 0.25 | 4 | 5.0625 | 4.25 |
| 2 | 2.1 | 0.1 | 4 | 4.41 | 4.1 |
| 2 | 2.01 | 0.01 | 4 | 4.0401 | 4.01 |
| 2 | 2.001 | 0.001 | 4 | 4.004001 | 4.001 |
| 2 | 2.0001 | 0.0001 | 4 | 4.00040001 | 4.0001 |

From the above table, the following inferences can be made.

- As {{< katex >}}\Delta x{{< /katex >}} tends to zero, {{< katex >}}\frac{\Delta y}{\Delta x}{{< /katex >}} approaches the limit given by the number 4 .
- At a point {{< katex >}}\mathrm{x}=2{{< /katex >}}, the derivative {{< katex >}}\frac{d y}{d x}=4{{< /katex >}}.
- It should also be mentioned here that {{< katex >}}\Delta x \rightarrow 0{{< /katex >}} does not mean that {{< katex >}}\Delta x=0{{< /katex >}}.
This is because, if we substitute {{< katex >}}\Delta x=0{{< /katex >}}, {{< katex >}}\frac{\Delta y}{\Delta x}{{< /katex >}} becomes indeterminate.

In general, we can obtain the derivative of the function {{< katex >}}y=x^{2}{{< /katex >}}, as follows:

{{< katex >}}
\begin{aligned}
\frac{\Delta y}{\Delta x} & =\frac{(x+\Delta x)^{2}-x^{2}}{\Delta x}=\frac{x^{2}+2 x \Delta x+\Delta x^{2}-x^{2}}{\Delta x} \\
& =\frac{2 x \Delta x+\Delta x^{2}}{\Delta x}=2 x+\Delta x \\
& \frac{d y}{d x}=\lim _{\Delta x \rightarrow 0} 2 x+\Delta x=2 x
\end{aligned}
{{< /katex >}}

The table below shows the derivatives of some common functions used in physics

| Function | Derivative |
| :--- | :--- |
| {{< katex >}}y=x{{< /katex >}} | {{< katex >}}d y / d x=1{{< /katex >}} |
| {{< katex >}}y=x^{2}{{< /katex >}} | {{< katex >}}d y / d x=2 x{{< /katex >}} |
| {{< katex >}}y=x^{3}{{< /katex >}} | {{< katex >}}d y / d x=3 x^{2}{{< /katex >}} |
| {{< katex >}}y=x^{n}{{< /katex >}} | {{< katex >}}d y / d x=n x^{n-1}{{< /katex >}} |
| {{< katex >}}y=\sin x{{< /katex >}} | {{< katex >}}d y / d x=\cos x{{< /katex >}} |
| {{< katex >}}y=\cos x{{< /katex >}} | {{< katex >}}d y / d x=-\sin x{{< /katex >}} |
| {{< katex >}}y=\operatorname{constant}{{< katex >}} | {{< /katex >}}d y / d x=0{{< /katex >}} |
| {{< katex >}}y=A B{{< /katex >}} | {{< katex >}}\frac{d y}{d x}=A\left(\frac{d B}{d x}\right)+\left(\frac{d A}{d x}\right) B{{< /katex >}} |

In physics, velocity, speed and acceleration are all derivatives with respect to time ' {{< katex >}}\mathrm{t}{{< /katex >}} '. This will be dealt with in the next section.

**EXAMPLE 2.19**

Find the derivative with respect to {{< katex >}}t{{< /katex >}}, of the function {{< katex >}}\mathrm{x}=\mathrm{A}_{0}+\mathrm{A}_{1} \mathrm{t}+\mathrm{A}_{2} \mathrm{t}^{2}{{< /katex >}} where {{< katex >}}\mathrm{A}_{0}, \mathrm{~A}_{1}{{< /katex >}} and {{< katex >}}\mathrm{A}_{2}{{< /katex >}} are constants.

**_Solution_**

Note that here the independent variable is ' {{< katex >}}\mathfrak{t}{{< /katex >}} ' and the dependent variable is ' {{< katex >}}\mathrm{x}{{< /katex >}} '

The required derivative is {{< katex >}}\mathrm{dx} / \mathrm{dt}=0+{{< /katex >}} {{< katex >}}\mathrm{A}_{1}+2 \mathrm{~A}_{2} \mathrm{t}{{< /katex >}}

The second derivative is {{< katex >}}\mathrm{d}^{2} \mathrm{x} / \mathrm{dt}^{2}=2 \mathrm{~A}_{2}{{< /katex >}}