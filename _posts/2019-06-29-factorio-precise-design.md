---
layout: post
title: "【异星工厂】配比计算方法"
subtitle: ''
date: 2019-06-29 21:09:00
author: "Mike Lyou"
header-style: text
#header-img: "img/dream-catcher-902508_1920.jpg"
mathjax: false
catalog: true
copyright-statement: CC BY-NC-SA
hidden: false
excerpt:
tags:
 - Game
 - Factorio
 - 游戏攻略


---

<!-- more -->

## 生产配比计算方法

计算方法：

1. 先按原料/产品数量配平方程组

2. 然后分析哪些配方是产能富余的（制造时间更短），哪些是瓶颈（制造更慢）

3. 同时将每个配方扩倍，产能富余的乘时间，瓶颈的乘制造机数量

4. 求和得到“最优配方”，可以从中得知“基元配方”数量 和 物品流动速度

![](https://raw.githubusercontent.com/mikelyou/image-public/master/factorio_recipe_calculation-01.png)

![](https://raw.githubusercontent.com/mikelyou/image-public/master/factorio_recipe_calculation-02.png)

![](https://raw.githubusercontent.com/mikelyou/image-public/master/factorio_recipe_calculation-03.png)
