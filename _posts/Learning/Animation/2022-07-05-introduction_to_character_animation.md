---
layout: post
title:  "skeleton animation binding pose"
author: iteevo
categories: [ animation, character ]
tags: [yellow]
image: assets/images/animations//animations/Animation_Vulkan/skeleton_walking.jpg
description: "骨骼动画"
featured: true
hidden: true
---


## Introduction to character animation
### 角色动画之前向动力学
![big pendulum ride](../../../assets/images/animations/Animation_Vulkan/big_pendulum_ride.png)
让角色自然运动的方式
Techniques such as skeletal animation, morphing,
ragdoll physic simulation, and inverse kinematics have already existed for a long time
- skeletal
animation for overall movement, and morphing animation for more subtle
things like facial expressions.
### Tool that captures state from actors and then displays it visually in game or editor.
- 读取游戏中的Actor中的状态数据，然后可视化的显示在UnityEditor里
- 替换DLL，Hook，实时修改Runtime数据
- https://docs.unrealengine.com/4.27/en-US/TestingAndOptimization/VisualLogger/
- 帧同步Log
- [Gameplay Debugger(虚幻调试器)对于开发者查看运行时数据非常有用](https://blog.csdn.net/zhang1461376499/article/details/113395607)

### 为实现可视化调试如何设计游戏代码
- 逻辑和表现分离？
- 龙之谷为什么不能直接进入场景调试GamePlay ？

