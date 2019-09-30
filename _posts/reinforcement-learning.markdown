---
layout:     post
title:      "强化学习-初览"
subtitle:   " \"Reinforcement learning\""
date:       2019-09-16 12:00:00
author:     "wxf"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - RL
typora-root-url: ..
---

# 本质：一种顾全大局的行为

![1569571942734](/img/1569571942734.png)

> 强化学习：machine 会对场景做出反应，并在**整局（Trajectory）结束时候**获得reward，在下次时以增加reward为标准行动。
>
> 监督学习：有个teacher告诉每次应当做出哪种反应，然后看看反应是否接近。
>
> 通常先监督学习、后强化学习。AlphaGO 便是如此训练的。

## 举例：

- 
- model-based 方法

## 大厂应用：

1. alphago
2. 腾讯AI LAB 出的觉悟机器人
3. 

## 问题

- reward delay ： 牺牲短期，获取长期利益
- action 会影响后续输入。