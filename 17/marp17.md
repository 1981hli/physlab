---

marp: true
title: 光电效应测定Planck常数
description: 17
theme:
size: 4:3
paginate: true
_paginate: false

---

# <!--fit--> 光电效应测定Planck常数
$$$$
$$$$
$$$$

南华大学/数理学院/物理实验室
2019.09.13

---

![bg 27%](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig1.png)

---

![bg 90% right:40%](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig2.png)

- 电流随着电压单调增加
- 存在饱和电流
- 存在截止电压

---

![bg 90% right:40%](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig3.png)

改变入射光光强：
- 截止电压不变
- 饱和电流随光强成正比变化

---

![bg 90% right:40%](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig4.png)

改变入射光频率：
- 截止电压随频率成正比变化
- 存在**红限频率**

---

光电效应的实验规律：
1.  饱和电流与入射光光强成正比；
2. 光电子初始动能大小与入射光频率成正比，与强度无关；
3. 入射光频率小于红限频率时无光电流；
4. 光电效应是瞬时产生的。
$$$$
$$$$
$$$$
$$$$

光电效应的实验规律用经典物理理论无法很好解释。

---

Einstein提出了光量子假说。光子能量为
$$E=h \nu$$

电子碰撞阴极材料表面电子，电子吸收光子能量，克服逸出功，逸出成为光电子。过程中能量守恒
$$h\nu=\frac{1}{2}mv^2+A$$

光电子向阳极移动，过程中电场对其做功。如果加上的是截止电压，电子运动到阳极时，动能减为0，有功能关系
$$\frac{1}{2}mv^2=eU_c$$

---

1. 光强表示光子数密度。光强越大，光子数目越多，激发的光电子数目越多，可解释饱和电流正比于入射光强；
$$$$
$$$$

2. 单个光子的能量决定了光电子的初动能，而光子能量正比于其频率，可解释光电子初动能正比于光频率；
$$$$
$$$$

3. 光子能量如果小于逸出功，则电子无法逸出，没有光电流，此时光频率即为红限频率；
$$$$
$$$$

4. 光子碰撞电子，电子逸出是瞬时发生的。

---

由Einstein光电效应理论可以设计测量Planck常数的方案。
$$$$
$$$$
$$
\left.
\begin{matrix}
h\nu=\frac{1}{2}mv^2+A \\\\
\frac{1}{2}mv^2=eU_c
\end{matrix}
\right\}
\Rightarrow h\nu=eU_c+A
\Rightarrow U_c= \color{red}\frac{h}{e} \color{black}\nu-\frac{A}{e}
$$
$$$$
$$$$

可以通过实验测得$\nu-U_c$图像，确定斜率$K$，之后即可计算Planck常数
$$h=Ke$$

---

实验中提供了5种不同波长的滤光片，可以提供5个频率的光。需要测量5个频率下对应的光电管的截止电压。

| 入射光波长 (nm)          |   365 |   405 |   436 |   546 |   577 |
| :----------------------- | ----: | ----: | ----: | ----: | ----: |
| 频率 ($10^{14}$Hz) | 8.214 | 7.408 | 6.879 | 5.490 | 5.196 |
| 截止电压 (V)             |       |       |       |       |       |

之后画出$\nu-U_c$图像，确定斜率$K$，即可计算Planck常数。

![h:200](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig6.png)

---

由于存在暗电流、本地电流、反向电流，实际的伏安特性曲线存在下移。

故在实验中应找到伏安特性曲线的抬头点，其电压即截止电压。

![bg 90% right:40%](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig5.png)

---

对于每一块滤光片，测量光电管的伏安特性曲线的抬头点附近的10个$(I,U)$数据。

![h:400](https://raw.githubusercontent.com/1981hli/physlab/master/17/fig7.png)
