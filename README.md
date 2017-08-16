# BallCollect
---

# Small Game of Ball（小球收集游戏）
**简介**：这是一款基于九轴传感器和次元台的球球收集小游戏，面向小朋友和娱乐场所。主要形式仿照黄金矿工和愤怒的小鸟，击飞弹性物体获得分数，关卡制的休闲小游戏。

## 1. 日程表
日期|更新内容|Commit 信息|
---|---|---|
2017.8.15|项目初始化|new project|
2017.8.15|项目基础文件夹|basic folder|
2017.8.15.16:19|创建了场景，添加了鼠标XY控制摄像头视角|Qian Change|
2017.8.15.17:37|在BallPawn_BP中添加了鼠标左键发射子弹功能，添加了子弹蓝图BP_Actor_Bullet ，添加了一些Static Mesh|Qian Change|
2017.8.16.09:50|在BallPawn_BP中添加了摄像机按Y轴随时间左右移动|Qian Change|
2017.8.16.14:18|在BallPawn_BP中添加了摄像机按C键切换视角，并左右平移|Qian Change|
2017.8.16.19:26|创建了BP_Actor_BounceA&B&C，BP_Actor_Spawn，BP_SC_Hover蓝图|Qian Change 2017.8.16.19:26|

## 2. 功能描述

1. 2017.8.15.16:19/修改了BallPawn_BP,Add Camera,Add Mouse Control
2. 2017.8.15.17:37/添加了鼠标左键发射子弹功能
3. 2017.8.16.09:50/在BallPawn_BP中添加了摄像机按Y轴随时间左右移动
4. 2017.8.16.14:18/在BallPawn_BP中添加了摄像机按C键切换视角，并左右平移
5. 2017.8.16.19:26/创建了BP_Actor_BounceA&B&C,三个不同颜色和形状的悬浮物体，添加了BP_Actor_Spawn使得可以在场景中同一时间生成ABC三种物体，添加了BP_SC_Hover使得物体可以在场景中悬浮
