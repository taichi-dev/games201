# GAMES201线上课程：高级物理引擎实战指南2020 

**最新课程主页**：https://yuanming.taichi.graphics/teaching/2020-games201/ (本页面不再更新)

**课件下载（讲义与代码）**：https://forum.taichi.graphics/t/topic/272

**课程回放地址**：https://www.bilibili.com/video/BV1ZK411H7Hc

**课程直播地址**: http://webinar.games-cn.org （直播结束后Bilibili有回放，请点上一个链接）

**建议前置课程**： 高等数学、Python或任何一门程序设计语言

**课程安排**： 共10节课，每周一次。2020年6月1日开始，时间为北京时间晚上8：30-10：00。

**课程作业**： 课程共有三个开放项目。自愿完成。开放项目可以1-3人组队。

开放项目以同学们自由发挥为主，同学们可以自己将代码分享到 https://forum.taichi.graphics/ 论坛进行讨论，互相切磋。每次我们会选择有代表性的几个项目会在下次上课展示、点评。课程最后会进行最终点评、线上颁奖。

## 课程大纲（暂定）

### 第一讲，6月1日 导论
* 基于物理的动画简介
* Taichi（太极）编程语言简介
* 课程与作业安排

（开放作业0：编写你自己的任意Taichi程序）

### 第二讲，6月8日 拉格朗日视角（1）

* 弹簧质点系统（Mass-spring systems）：你的第一个物理模拟器
* 显式与隐式时间积分器（Explicit/implicit time integrators）
* 光滑粒子流体动力学（Smoothed particle hydrodynamics）
* 快速邻居搜索（Neighborhood search）

### 第三讲，6月15日 拉格朗日视角（2）

* 基于四面体网格（tetrahedral mesh）的拉格朗日有限元模拟
* 隐式有限元求解器（Implicit FEM solvers）
* 边界条件处理
* Taichi编程语言高级特性

（开放作业1：实现任意隐式积分器: implicit mass-spring/FEM, PCI-SPH, MPS, ..., 并进行显式时间积分器器与隐式时间积分器器对比）

### 第四讲，6月22日 欧拉视角

* 稳定流体与半拉格朗日输送（Stable fluids and Semi-Lagrangian advection）
* Chorin式压力投影（Chorin-Style projection）
* Staggered网格与零空间（nullspaces）
* Krylov子空间求解器（Krylov-subspace solvers）与共轭梯度法 (Conjugate gradients)
* 用无矩阵（Matrix-free）Krylov子空间方法求解泊松方程（Poisson equations）
* 预条件（Preconditioning）
* 几何与代数多重网格方法（multigrid methods）

### 第五讲，6月29日 多体问题与涡方法

**客座讲师: [张心欣](https://zhxx1987.github.io/)**

* 多体问题以及他们与柏松方程的联系
* 涡方法的乐趣
* 从直观的角度引导同学认识几种不同的快速求和方法

7月6日，空一周，实现开放作业1

7月11日，开放作业1截止，点评

Homework 2 (最终作业)
* 实现一个可交互的物理模拟器(2D)，或⽤⾼质量渲染可视化模拟结果(3D)，或进⾏性能优化
* 可以基于⾃己的或别人的Homework 1

### 第六讲，7月13日 线性弹性有限元与拓扑优化

* 弱形式（weak form）与有限元理论入门
* 基于六面体网格（hexahedral grid）的拉格朗日有限元模拟
* 拓扑优化（Topology optimization）


### 第七讲，7月20日 混合欧拉-拉格朗日视角（1）

* 粒子-网格传输（Particle-grid transfers）
* 粒子元胞法（Particle-in-Cell, PIC）
* 流体隐粒子（Fluid Implicit Particles, FLIP）
* 仿射粒子元胞法（Affine Particle-in-Cell, APIC）与多项式粒子元胞法(Polynomial Particle-in-Cell, PolyPIC)
* 用FLIP与APIC进行流体模拟
* 物质点法（Material Point Method, MPM）基础


### 第八讲，7月27日 混合欧拉-拉格朗日视角（2）

* 移动最小二乘物质点法（Moving Least Squares MPM, MLS-MPM）
* 本构模型（Constitutive models）
* 塑性 （Plasticity）
* 物质点法中的拉格朗日力（Lagrangian forces in MPM）

### 第九讲，8月3日 高性能计算与物理引擎

* 现代处理器微结构（processor microarchitectures）
* 内存层级（memory hierarchy）
* 性能调优
* Taichi中的高级数据布局
* Taichi中的稀疏数据结构

8月10日空一次，大家完善自己的物理引擎（开放作业2）。

8月15日开放作业2 deadline。

### 第十讲，8月17日 总结

* 课程回顾
* 引擎项目最终点评、评奖
* 基于物理的动画中的未解难题

## 助教团队

未来课程的顺利进行，离不开助教同学们的鼎力相助。理论组助教负责在论坛答疑、筛选优秀编程作业：

    夏一鸣
    史雨宸
    袁宇杰

技术组助教主要负责与课程相关的Taichi开发与维护：

    杨玄达
    翟骁
    曹亚帝
    禹鹏
    冯旭东
