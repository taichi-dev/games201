# GAMES201线上课程：高级物理引擎实战指南2020 

**课程主页**：http://games-cn.org/games201/

**课件下载（讲义与代码）**：https://github.com/taichi-dev/games201/releases

**课程回放**：https://www.bilibili.com/video/BV1ZK411H7Hc

**课程直播地址**: http://webinar.games-cn.org （直播结束后Bilibili有回放，请点上一个链接）

**建议前置课程**： 高等数学、Python或任何一门程序设计语言

**课程安排**： 共10节课，每周一次。2020年6月1日开始，时间为北京时间晚上8：30-9：30。

**课程作业**： 课程共有五次简单的编码练习和三个开放项目。自愿完成。开放项目可以1-3人组队。

开放项目以同学们自由发挥为主，同学们可以自己将代码分享到 https://forum.taichi.graphics/ 论坛进行讨论，互相切磋。每次我们会选择有代表性的几个项目会在下次上课展示、点评。课程最后会进行最终点评、线上颁奖。

**课程大纲（暂定）**：

【第一讲，6月1日】

导论

– 基于物理的动画简介

– Taichi（太极）编程语言简介

– 课程与作业安排

（开放作业0：编写你自己的任意Taichi程序）

【第二讲，6月8日】

拉格朗日视角（1）

– 弹簧质点系统（Mass-spring systems）：你的第一个物理模拟器

– 布料模拟

– 显式与隐式时间积分器（Explicit/implicit time integrators）

– 光滑粒子流体动力学（Smoothed particle hydrodynamics）与基于位置的流体（Position-based fluids）

– 体素化（Voxelization）: 从三角网格生成粒子

– 快速邻居搜索（Neighborhood search）

– 刚体模拟简介

【第三讲，6月15日】

拉格朗日视角（2）

– 弱形式（weak form）与拉格朗日有限元模拟入门

– 基于六面体网格（hexahedral grid）的拉格朗日有限元模拟

– 基于四面体网格（tetrahedral mesh）的拉格朗日有限元模拟

– 边界条件处理

– 可逆（invertible）有限元法

– 隐式有限元求解器（Implicit FEM solvers）

– 拓扑优化（Topology optimization）

【第四讲，6月22日】

欧拉视角（1）

– 稳定流体与半拉格朗日输送（Stable fluids and Semi-Lagrangian advection）

– Chorin式压力投影（Chorin-Style projection）

– Staggered网格与零空间（nullspaces）

– Krylov子空间求解器（Krylov-subspace solvers）

– 用无矩阵（Matrix-free）Krylov子空间方法求解泊松方程（Poisson equations）

– 预条件（Preconditioning）

– 几何与代数多重网格方法（multigrid methods）

【第五讲，6月29日】

欧拉视角（2）与大规模物理效果渲染

– 高级输送格式（Advanced advection schemes）

– 有符号距离场与等势面（Signed-distance fields, level sets）

– 用等势面方法实现自由表面（Free-surface）追踪（tracking）

– 自由表面与高阶边界条件处理

– 路径追踪（Path tracing）与球面追踪（Sphere tracing）

– 运动模糊（Motion blur）

– 行军立方体（Marching cubes）表面重建

– 数字微分分析器（Digital differential analyzer，DDA）

– 用数字微分分析器进行光线-粒子求交（DDA ray-particle intersection）

– 体素渲染（Voxel rendering）

– 体积渲染（Volumetric rendering）

（开放作业1：渲染你的模拟结果）

7月6日，空一周，实现开放作业1

7月11日，开放作业1截止，点评

【第六讲，7月13日】

混合欧拉-拉格朗日视角（1）

– 开放作业1点评，公布优秀代码

– 粒子-网格传输（Particle-grid transfers）

– 粒子元胞法（Particle-in-Cell, PIC）

– 流体隐粒子（Fluid Implicit Particles, FLIP）

– 仿射粒子元胞法（Affine Particle-in-Cell, APIC）

– 用FLIP与APIC进行流体模拟

（开放作业2开始，可以使用开放作业1的代码，自由实现一个物理引擎，并完成渲染）

【第七讲，7月20日】

混合欧拉-拉格朗日视角（2）

– 物质点法（Material Point Method, MPM）基础

– 本构模型（Constitutive models）

– 移动最小二乘物质点法（Moving Least Squares MPM, MLS-MPM）

– 物质点法中的拉格朗日力（Lagrangian forces in MPM）

– MPM中的数值断裂（numeric fracture）与连续介质伤害力学（Continuum Damage Mechanics, CDM）

【第八讲，7月27日】

高性能计算与物理引擎

– 现代处理器微结构（processor microarchitectures）

– 内存层级（memory hierarchy）

– 单线程性能调优

– 并行编程与性能调优

– 高性能GPU编程

– MPM的性能优化

【第九讲，8月3日】

物理引擎中的稀疏数据结构与可微编程

– 稀疏数据结构简介

– 传统稀疏数据结构：OpenVDB

– 用稀疏数据结构加速物质点法的模拟

– 稀疏数据结构的调优

– 可微编程与可微物理引擎

– 利用可微编程从势能计算受力

– 利用Checkpointing技巧节约内存

– 实例：优化软体机器人控制器

8月10日空一次，大家完善自己的物理引擎（开放作业2）。

8月15日开放作业2 deadline。

【第十讲，8月17日】

总结

– 课程回顾

– 引擎项目最终点评、评奖

– 基于物理的动画中的未解难题

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
