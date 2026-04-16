# papers-on-embodied-intelligence
papers on embodied intelligence
## 1.RoboSafe Safeguarding Embodied Agents via Executable Safety Logic
本文提出**RoboSafe**，一种面向**VLM 驱动具身智能体**的**混合推理运行时安全护栏**，通过**长短时安全记忆**与**前向预测推理 + 后向反思推理**，精准解决动态场景中**上下文风险**与**时序风险**，可将危险行为发生率降低**36.8%**，在保持近原任务性能的同时，实现可解释、可执行的代码级安全逻辑验证，仿真与实体机械臂实验均验证其有效性。
## 2.Compromising LLM Driven Embodied Agents With Contextual Backdoor Attacks
本文提出上下文后门攻击（CBA），通过毒化少量上下文演示样本即可感染黑盒大语言模型，使其生成含隐蔽缺陷的控制代码，并采用文本 + 视觉双模态触发策略激活恶意行为；该攻击覆盖机器人规划、操作、自动驾驶等具身智能场景，在多任务与真实无人车实验中攻击成功率（ASR）超 80%，且现有常规防御手段难以有效检测，首次揭示了 LLM 驱动代码型具身智能在上下文学习 - 代码生成 - 物理执行全链路的重大安全威胁。
## 3.useniexsecurity25-yeke.pdf(Automated Discovery of Semantic Attacks in Multi-Robot Navigation Systems)
提出了名为Raven的自动化语义攻击发现工具，针对多机器人导航避碰算法（ORCA、GLAS） 展开虚假数据注入攻击（FDIA） 挖掘，定义了围捕（Herding）、死锁（Deadlock）、导航延迟、机器人碰撞、机器人 - 障碍物碰撞五类攻击目标，通过信号时序逻辑（STL） 与随机优化实现有效且隐蔽的攻击生成，在数值仿真、高保真 PX4/Gazebo 仿真、Crazyflie 无人机真机三大平台验证，发现两类算法共5 项设计缺陷，单次虚假数据注入即可引发故障，攻击成功率达90%–100%，并给出针对性防御方案。
·因为实现了真实攻击验证，我们可以参考它的环境、攻击方式来提出防御
