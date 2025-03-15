---
title: "Shaughnessy1990: Hypersonic vehicle simulation model: Winged-cone configuration"
weight: 3
---
## 总结

NASA Langley中心的高超声速飞行器模拟模型：翼锥构型[^Shaughnessy1990]。

[^Shaughnessy1990]: SHAUGHNESSY J D, PINCKNEY S Z, MCMINN J D, 等. Hypersonic vehicle simulation model: Winged-cone configuration: NAS 1.15:102610[R/OL]. [1990-11-01](2025-03-12). <https://ntrs.nasa.gov/citations/19910003392>.

Aerodynamic, propulsion, and mass models for a generic, horizontal-takeoff, single-stage-to-orbit (SSTO) configuration are presented which are suitable for use in point mass as well as batch and real-time six degree-of-freedom simulations.
The

## 模型

![Winged-cone高超声速飞行器构型](/COM-GHV-beyond/Shaughnessy1990/configuration.png)

这个模型包含了三个操作舵面：

Canard (鸭翼/前翼)：

- 位于飞机前部的水平控制面
- 主要用于俯仰控制和提供额外升力
- 在某些设计中也可以帮助改善飞机的机动性能
- 在低速飞行时，可以提供额外的升力
- 可以考虑在高超声速飞行时，折叠收起，改善激波构型，减小阻力

Rudder (方向舵)：

- 位于垂直尾翼上的可动控制面
- 主要用于偏航控制，即控制飞机左右转向
- 通过改变气流方向产生侧向力矩

Elevon (升降副翼)：

- 是elevator(升降舵)和aileron(副翼)的组合词
- 位于机翼后缘，集合了升降舵和副翼的功能
- 可以同时控制俯仰(上下)和横滚运动
- 同向偏转时，产生俯仰力矩
- 反向偏转时（差动），产生滚转力矩
- 常见于三角翼或三角形后掠翼飞机设计中

## 结果
