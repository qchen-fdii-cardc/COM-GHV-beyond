---
title: "COM of GHV and beyond"
weight: 1
# bookFlatSection: false
# bookToc: true
# bookHidden: false
# bookCollapseSection: false
# bookComments: false
# bookSearchExclude: false
---

## 面向控制的模型

$$
\begin{equation}
 \dot{h} = V \sin (\theta - \alpha) \\
 \dot{V} = \frac{1}{m} \left( F - D - m g \sin \theta \right) \\
 \dot{\theta} = \frac{1}{V} \left( L \cos \alpha + W \sin \theta \right) \\
 \dot{\alpha} = \frac{1}{V} \left( L \sin \alpha - W \cos \theta \right)
\end{equation}
$$

这个名称是一个在高超声速飞行器建模、控制、仿真领域中常用的名称，来源于Parker等[^parker2007]的一篇高引的文章。

[^parker2007]: PARKER J, SERRANI A, YURKOVICH S, 等. Control-oriented modeling of an air-breathing hypersonic vehicle[J/OL]. Journal of Guidance Control and Dynamics, 2007, 30: 856-869. DOI:10.2514/1.27830.

在这篇文章里，Parker等作者总结自1940年代末期以来高超声速飞行器建模的数据和方法，提出一个后面被大部分控制领域的相关研究所采用的模型。

这篇文章的模型主要基于[^Bolender2005]以及[^Groves2005]，其模型工作基本在[^Chavez1994]的模型基础上进行。

[^Bolender2005]: BOLENDER M, DOMAN D. A Non-Linear Model for the Longitudinal Dynamics of a Hypersonic Air-breathing Vehicle[C/OL]//AIAA Guidance, Navigation, and Control Conference and Exhibit. San Francisco, California: American Institute of Aeronautics and Astronautics, 2005[2025-03-12]. https://arc.aiaa.org/doi/10.2514/6.2005-6255. DOI:10.2514/6.2005-6255.

[^Groves2005]: GROVES K, SIGTHORSSON D, SERRANI A, 等. Reference Command Tracking for a Linearized Model of an Air-Breathing Hypersonic Vehicle[C/OL]//AIAA Guidance, Navigation, and Control Conference and Exhibit. 2005. https://www.semanticscholar.org/paper/a751c5fc2c6018c53bcf105772a551539492c28c. DOI:10.2514/6.2005-6144.


[^Chavez1994]: CHAVEZ F R, SCHMIDT D K. Analytical aeropropulsive-aeroelastic hypersonic-vehicle model with dynamic analysis[J/OL]. Journal of Guidance, Control, and Dynamics, 1994, 17(6): 1308-1319. DOI:10.2514/3.21349.

这里准备实现一个较为完整的GHV-COM模型，充分考虑空气动力学、发动机、飞行器结构变形、热效应。


## 本项工作的计划

### 第一步工作

[经典文献工作内容的实现]({{< relref "ImplementationsOfClassicRefs" >}})。

### 第二步工作

基于第一步的工作，实现一个较为完整的GHV-COM模型。

### 第三步工作

基于模型探索应用，包括灵敏度分析、控制器设计、仿真验证、系统参数设计等。


## 参考文献