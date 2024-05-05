---
author: 老王
layout: post
title: 飞机飞上天也不容易
date: 2018-02-13
categories: blog
tags: [航空]
header-img: "img/posts/20180213.jpg"
---
上次介绍了飞机是怎么降落的，今天来介绍飞机是怎么起飞的

## 机翼的结构

说到起飞，机翼是关键。我们先来看一看机翼的结构。

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/a.png)
>图片来自维基百科
> 
>1. 翼尖小翼
>2. 低速副翼
>3. 高速副翼
>4. 襟翼滑轨整流罩
>5. 前缘襟翼－克鲁格襟翼
>6. 前缘缝翼
>7. 内侧襟翼
>8. 外侧襟翼
>9. 扰流板
>10. 扰流板-减速板

机翼是飞机产生升力的主要部件，主要由主翼、襟翼和副翼构成。由于上缘向上拱起，下缘基本平直的气动外形，机翼可以产生足够飞机运行的升力。

**襟翼**  是一种安装在机翼上的活动面，使用的时候会改变翼剖面的弧度，增加机翼可以提供的升力，在低速起飞与降落的时候最常使用。襟翼也被称为高升力装置的一种，当襟翼向下垂时也会增加机翼的迎风面积而有减速的作用。

**副翼**  是安装在机翼后缘外侧的活动翼面，用以控制航空器的滚转姿态。某些高速飞机为减小副翼偏转所引起的机翼扭转变形，还装有内侧副翼。

**翼尖小翼**  是安装在翼尖的垂直方向翼片，主要用于削弱翼尖下表面气流绕流至上表面的效应，减少升力损失，改善机翼性能。

飞机在不同飞行过程中，机翼的操纵面形态也不同，如下图所示：

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/ba.png)
>图片来自维基百科

由图可知，机翼的弧度越大，产生的升力越大，在着陆时，机翼上的减速板还能辅助减速。（详见我的另一文 [飞机停下来太费劲啦](https://allen5261.github.io/blog/2018/02/09/飞机停下来太费劲啦/)）

## 升力的产生

我们物理书上的版本（等时间论）是这样的：

>如下图所示，当气流经过机翼上表面和下表面时，由于上表面路程比下表面长，则气流要在相同时间内通过上下表面，根据$$s=vt$$，上表面流速比下表面大，再根据伯努利定理：由不可压、理想流体沿流管作定常流动时的伯努利定理知，**流动速度增加，流体的静压将减小；反之，流动速度减小，流体的静压将增加。但是流体的静压和动压之和，称为总压始终保持不变。从而产生压力差，形成升力。**

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/c.gif)

这种说法不完整，未完全说明机翼上下表面产生流速差的本质。根据牛顿第二定律，一个物体要加速或者减速必定会受到合外力的的影响，而不是仅靠路程长短就能导致速度差的。

一架飞机在起飞时，我们对其进行整体受力分析：

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/d.jpg)
>这是一架你们绝对没见过的波音727，图片来自维基百科

上图中，$$L$$即为升力，根据现在被广泛认可的说法，升力的产生需要机翼的结构支撑。如下图，机翼的横截面大致是上缘向上拱起，下缘基本平直，气流在经过机翼时改变方向，并沿着一条向下弯曲的路径前进。根据牛顿第二定律，气流方向的变化具有一个向下作用于机翼上空气的力。然后，根据牛顿第三定律，空气必须在机翼上施加一个向上的反作用力。总的结果是，升力与方向变化相反，且大于机翼的压力，这样，二力合成，产生向上的和力，作用在整架飞机上即为升力。

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/e.png)

## 升力的计算公式

根据伯努利原理及库塔-茹可夫斯基方程，\\[L=\rho v \bf\Gamma\\] （$$\bf\Gamma$$为此时的环量值，即流体的速度沿着一条闭曲线的路径积分）。由此可知，当气体密度与此时环量值不变，飞机速度过低时，就会产生升力不足的危险情况，就是我们称的**失速**。在失速状态下，就有可能发生机毁人亡的惨剧。

飞机飞上蓝天，要降落，咋办？参看我的另一文：[飞机停下来太费劲啦](https://allen5261.github.io/blog/2018/02/09/飞机停下来太费劲啦/)

We have known how the plane lands last time. I will show how the plane takes off.

## Structure of airfoils

The _airfoil_(机翼) is the key to taking off. Let's take a look at the _structure_(结构) of the airfoil.

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/a.png)
>Picture From Wikipedia.
> 
>1. Winglet
>2. Low Speed ​​Aileron
>3. High Speed ​​Aileron
>4. Landing Flap Fairing
>5. Kruger Flap
>6. Slat
>7. Inner Flaps
>8. Outer Flaps
>9. Fault Flaps
>10. Air Brake

The airfoil is the main part of producing _lift_(升力),  mainly includes the main airfoil, _flaps_(襟翼) and _ailerons_(副翼). Because of the _aerodynamic_(空气动力学) shape of _arched_(拱形的) upper-edge and flat lower-edge, the airfoil can generate enough lift to operate the aircraft.

**FLAP** is a movable surface mounted on the airfoil, which changes the curve of the airfoil profile when used, increasing the lift that the airfoil can provide, and is most commonly used at low speed taking off and landing. The flaps are also called high lift devices, and when the flaps are _pendulous_(下垂的), they also increase the windward area of the airfoil and also decelerate.

**ALIERON**  is the airfoil surface mounted on the outer and trailing edge of the airfoil to control the _roll attitude_(滚转姿态) of the aircraft. Some high-speed aircraft have a medial aileron to reduce the _torsional deformation_(扭转变形) caused by the airfoil deflection.

**WINGLET**  is the _vertical_(垂直的) airfoil mounted on the tip of the airfoil, which is mainly used to reduce the effect of airfoil between upper and lower-edge of the airfoil tip, reduce the lift loss and improve the _performance_(性能) of the airfoil.

In different situation, the airfoil of the aircraft has different control surfaces, as shown in the figure below:

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/bb.png)
>Picture From Wikipedia.

As can be seen from the figure, the _curver_(弯曲的) the airfoils are, the more gather the lift will be. When landing, the airbrake on the airfoil can also _assist_(辅助) deceleration. (For more detail, please jump to [飞机停下来太费劲啦](https://allen5261.github.io/blog/2018/02/09/飞机停下来太费劲啦/).)

## Generation of Lift

The vision on our physics textbook (equal transit-time) ：

>As shown in the figure below, when the airfoil passes through the upper-surface and the lower-surface, the airfoil should pass through the upper and lower surfaces at the same time, but the upper surface is longer than the lower surface. According to the equation $$s=vt$$, The upper-surface's velocity is larger than the lower surface, according to the Bernoulli's principle: **If the flow speed increases, the pressure of the _fluid_(流体) will decrease. Conversely, if the flow speed decreases, the pressure will increase. But the total pressure stays the same. This creates pressure and lift.**

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/c.gif)
>Picture From Wikipedia.

This saying is incomplete and does not fully explain the difference of velocity between the upper and lower surfaces of the airfoils. According to Newton's Second Law, an object's speed must be changed by force rather than by distance alone.

When a plane taking off, we can _analyzed_(分析) what force it applies.

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/d.jpg)
>This is a Boeing 727 that you've never seen before. Picture From Wikipedia.

In the figure above, $$L$$ is the lift. According to the widely accepted saying, lift needs the support the structure of the airfoils. in the following figure, the shape of airfoils is arched upper and flat lower. The air flow changes direction as it passes the airfoil and follows a path that is curved downward. According to Newton's Second Law, this change in flow direction requires a downward force applied to the air by the airfoil. Then, according to Newton's third law, the air must exert an upward force on the airfoil. The overall result is that the lift is opposite to the direction, and is greater than the pressure. In this way, the two forces are _synthesized_(合成) to produce upward force, which is the lift on the whole plane.

![alt](https://raw.githubusercontent.com/allen5261/allen5261.github.io/master/img/posts/20180213/e.png)

## Equation of Lift

According to the Bernoulli's principle and the Kutta-Zhoukowski Equation, \\[L=\rho v \bf\Gamma\\] ($$\bf\Gamma$$ is the circulation, the line integral around a closed curve of the velocity field). We can know that if the air _density_(密度) and the circulation is same, but the speed is too low, There will be a risk of lacking lift, which is what we call ** stall**. When the plane stalls, it is possible that the machine will destroy and cause disastrous accident.