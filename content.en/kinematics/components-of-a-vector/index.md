---
title: 'components of a vector'
weight: 3
---

# COMPONENTS OF A VECTOR

In the Cartesian coordinate system, any vector {{< katex >}}\vec{A}{{< /katex >}} can be resolved into three components along {{< katex >}}x, y{{< /katex >}} and {{< katex >}}z{{< /katex >}} directions. This is shown in Figure 2.20.

Consider a 3-dimensional coordinate system. With respect to this, a vector can be written in component form as

$$
\vec{A}=A_{x} \hat{i}+A_{y} \hat{j}+A_{z} \hat{k}
$$

![Alt text](<./fig-2.20.png>)

**Figure 2.20** Components of a vector in 2 dimensions and 3 dimensions

Here {{< katex >}}\vec{A}_{x}{{< /katex >}} is the {{< katex >}}x{{< /katex >}}-component of {{< katex >}}\vec{A}{{< /katex >}}, {{< katex >}}A_{y}{{< /katex >}} is the {{< katex >}}y{{< /katex >}}-component of {{< katex >}}\vec{A}{{< /katex >}}, and {{< katex >}}A_{z}{{< /katex >}} is the {{< katex >}}z{{< /katex >}}-component of {{< katex >}}\vec{A}{{< /katex >}}.

In a 2-dimensional Cartesian coordinate system (which is shown in Figure 2.20) the vector 
{{< katex >}}\vec{A}{{< /katex >}} is given by

\\(\vec{A}=A_{x} \hat{i}+A_{y} \hat{j}\\)


If {{< katex >}}\vec{A}{{< /katex >}} makes an angle {{< katex >}}\theta{{< /katex >}} with {{< katex >}}\mathrm{x}{{< /katex >}} axis, and {{< katex >}}A_{x}{{< /katex >}} and {{< katex >}}A_{y}{{< /katex >}} are the components of {{< katex >}}\vec{A}{{< /katex >}} along {{< katex >}}x{{< /katex >}}-axis and {{< katex >}}y{{< /katex >}}-axis respectively, then as shown in Figure 2.21,

{{< katex >}}
A_{x}=A \cos \theta, A_{y}=A \sin \theta
{{< /katex >}}

where ' {{< katex >}}A{{< /katex >}} ' is the magnitude (length) of the vector {{< katex >}}\vec{A}{{< /katex >}}, {{< katex >}}A=\sqrt{A_{x}^{2}+A_{y}^{2}}{{< /katex >}}

![Alt text](<fig-2.21.png>)

**Figure 2.21 Resolution of a vector**

**EXAMPLE 2.3**

What are the unit vectors along the negative x–direction, negative y–direction, and negative z– direction?

**_Solution_**

The unit vectors along the negative directions can be shown as in the following figure.  

![Alt text](<./fig-2.23.png>)

Then we have:
 The unit vector along the negative {{< katex >}}\mathrm{x}{{< /katex >}} direction is  {{< katex >}}-\hat{i} {{< /katex >}}.
 The unit vector along the negative  {{< katex >}}y {{< /katex >}} direction is  {{< katex >}}-\hat{j} {{< /katex >}}.
 The unit vector along the negative {{< katex >}}\mathrm{z}{{< /katex >}} direction is  {{< katex >}}-\hat{k} {{< /katex >}}.



## Vector addition using components

In the previous section we have learnt about addition and subtraction of two vectors using geometric methods. But once we choose a coordinate system, the addition and subtraction of vectors becomes much easier to perform.

The two vectors {{< katex >}} \vec{A}  {{< /katex >}} and {{< katex >}}\vec{B}{{< /katex >}} in a Cartesian coordinate system can be expressed as

{{< katex >}}
\begin{aligned}
\vec{A} & =A_{x} \hat{i}+A_{y} \hat{j}+A_{z} \hat{k} \\
\vec{B} & =B_{x} \hat{i}+B_{y} \hat{j}+B_{z} \hat{k}
\end{aligned}
{{< /katex >}}



Then the addition of two vectors is equivalent to adding their corresponding x, y and z components.

{{< katex >}}
\vec{A}+\vec{B}=\left(A_{x}+B_{x}\right) \hat{i}+\left(A_{y}+B_{y}\right) \hat{j}+\left(A_{z}+B_{z}\right) \hat{k}
{{< /katex >}} 

Similarly, the subtraction of two vectors is equivalent to subtracting the corresponding {{< katex >}} x, y and  z {{< /katex >}} components.

{{< katex >}}
\vec{A}-\vec{B}=\left(A_{x}-B_{x}\right) \hat{i}+\left(A_{y}-B_{y}\right) \hat{j}+\left(A_{z}-B_{z}\right) \hat{k}
{{< /katex >}}

The above rules form an analytical way of adding and subtracting two vectors.

**EXAMPLE 2.4**

Two vectors  {{< katex >}}\vec{A}{{< /katex >}} and {{< katex >}} \vec{B}{{< /katex >}} are given in the component form as {{< katex >}} \vec{A}=5 \hat{i}+7 \hat{j}-4 \hat{k}{{< /katex >}} and {{< katex >}} \vec{B}=6 \hat{i}+3 \hat{j}+2 \hat{k}{{< /katex >}}. Find {{< katex >}} \vec{A}+\vec{B}{{< /katex >}} and {{< katex >}} \vec{A}-\vec{B}{{< /katex >}}.

**_Solution_** 

{{< katex >}}
\begin{aligned}
\vec{A}+\vec{B} & =(5 \hat{i}+7 \hat{j}-4 \hat{k})+(6 \hat{i}+3 \hat{j}+2 \hat{k}) \\
& =11 \hat{i}+10 \hat{j}-2 \hat{k} \\
\vec{B}+\vec{A} & =(6 \hat{i}+3 \hat{j}+2 \hat{k})+(5 \hat{i}+7 \hat{j}-4 \hat{k}) \\
& =(6+5) \hat{i}+(3+7) \hat{j}+(2-4) \hat{k} \\
& =11 \hat{i}+10 \hat{j}-2 \hat{k} \\
\vec{A}-\vec{B} & =(5 \hat{i}+7 \hat{j}-4 \hat{k})-(6 \hat{i}+3 \hat{j}+2 \hat{k}) \\
& =-\hat{i}+4 \hat{j}-6 \hat{k} \\
\vec{B}-\vec{A} & =\hat{i}-4 \hat{j}+6 \hat{k}
\end{aligned}
{{< /katex >}}

Note that the vectors {{< katex >}}\vec{A}+\vec{B}{{< /katex >}} and {{< katex >}}\vec{B}+\vec{A}{{< /katex >}} are same and the vectors {{< katex >}}\vec{A}-\vec{B}{{< /katex >}} and {{< katex >}}\vec{B}-\vec{A}{{< /katex >}} are opposite to each other.

---
**Note**
The addition of two 
vectors using components 
depends on the choice of 
the coordinate system. But the geometric 
way of adding and subtracting two 
vectors is independent of the coordinate 
system used

---
