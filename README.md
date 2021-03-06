﻿# 计算方法
上了计算方法的课程，把其中的算法写成了matlab程序，初步认识一下数值分析算法

## 直接解法

|算法名称           |分解方法|文件名|
|:----------------:|:----:|:-----:|
|高斯消去法|LU分解 (Doolittle分解)| `LU_equ.m` |
|  追赶法 |LU分解求解三对角方程组的特殊情形| `Thomas_equ.m` |
|列主元高斯消去法|                       | `GE_equ.m` |
|改进平方根法|对称矩阵的三角分解| `LDL_equ.m` |
|Household方法|QR分解| `Household_QR.m` <br> `Household_equ.m` |
|龙贝格积分| | `Romberg_calculus.m` |


## 迭代解法
|算法名称   |  文件名  |
|:--------:|:--------:|
|共轭梯度法 |`CG_equ.m`|
|牛顿迭代法 |`newton_iteration.m`|
|四级RK法   |`Runge_Kutta.m`|


## 插值
|  算法名称   |             |     文件名      |
|:----------:|:-----------:|:---------------:|
|三次样条插值 |第一种边界条件 <br> 第二种边界条件 <br> 第三种边界条件|`Spline1_inter.m` <br> `Spline2_inter.m` <br> `Spline3_inter.m` |
