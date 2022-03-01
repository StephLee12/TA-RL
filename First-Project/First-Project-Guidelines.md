# First Project

## Overview

​	互联网与计算智能第一次课程设计——基于Mujoco环境的强化学习(Reinforcement Learning, RL)智能体搭建

### Important Information	

1. 在[github](https://github.com/StephLee12/TA-RL)和QQ群同步更新代码demo和课程设计信息
2. **Deadline**: 未确定

### Goals

1. 熟悉团队协作编写代码
2. 熟悉RL经典算法, i.e., PPO, DQN, etc.,  理解背后算法原理
3. 使用Mujoco环境实践强化学习算法
4. 最后进行课设汇报展示

## Requirements

1. 搭建Mujoco环境（对于使用windows系统电脑的同学，需要安装Linux双系统）
1. 在Mujoco下的**Ant-v2**和**HalfCheeah-v2**环境中任选其一实践强化学习算法（若在两个环境中都实践有额外加分）
1. 关于实践的强化学习算法，不限数量（至少一种，多做有额外加分），但必须理解背后算法原理，汇报时会随机提问
3. 不限训练平台(Pytorch, Tensorflow或其他均可)，建议使用GPU加速训练
4. 训练时保存训练结果(强化学习模型)以及奖励(reward)，以便汇报时进行结果展示
6. 制作ppt进行汇报展示

## Mujoco环境安装Instructions

注意事项：

1. Mujoco是Open AI Gym库中包含比较有趣的**连续控制**任务的环境
1. Mujoco环境只能在Mac OS或Linux系统下运行，请使用windows电脑的同学务必安装linux双系统（之后强化学习智能体会用到gpu加速，所以如果使用虚拟机下的linux系统可能会很慢）
1. 本次实验的特定环境可以在Mujoco下的**Ant-v2**和**HalfCheetah-v2**任选其一 (完成两个有额外加分)
1. 本次实验可以选取任意强化学习算法（注意有些RL算法只能应用于离散动作空间），至少选一个算法（多选有额外加分）
1. 关于Mujoco安装流程可以参照[Mujoco's Github](https://github.com/openai/mujoco-py/)，安装时遇到bug可以参照[这篇blog](https://its201.com/article/chch2010523/121163493)(验证过本篇blog的可行性)

## Useful Links

1. [李宏毅强化学习videos](https://www.bilibili.com/video/BV1UE411G78S?from=search&seid=3678911345920384551&spm_id_from=333.337.0.0)
2. [Open AI Gym](https://gym.openai.com/)
2. [Mujoco](https://gym.openai.com/envs/#mujoco)&[Mujoco's Github](https://github.com/openai/mujoco-py/)
2. [Mujoco安装instructions](https://its201.com/article/chch2010523/121163493)

## Submission

1. 代码和ppt一起压缩打包发送到邮箱---245012580@qq.com 
1. 邮件主题格式：压缩名命名格式：
1. **Deadline**

## Tips

1. 在编写RL算法代码之前，建议边看强化学习公开课边阅读算法对应的论文。**不建议直接看论文(难度太大)，配合强化学习公开课(如李宏毅的)食用，公开课不清楚的地方再去原文查看**
2. 网络上很多开源RL算法代码，可以借鉴，但不能照搬哟(会查重～)。**强烈建议先自己对照算法流程编写**。

