### Routed DiT-Policy：基于 Token Routing 的高效 Transformer 扩散策略

**丰浩浩**（第一作者）| *投稿中 (IEEE ICRA/IROS 机器人顶会)*

针对 Transformer-based 机器人扩散策略训练成本高昂的问题，提出 **Routed DiT** 架构。

#### 核心创新：
- 引入 **Token Routing** 机制，利用动作序列的空间冗余性，在训练期间随机选择 Token 子集进行计算，其余 Token 直接透传。
- 通过结构化随机性增强模型的 **流形粘附性（Manifold Adherence）**，显著提升各项任务的成功率。

#### 实验结果：
- 在 **PushT、Robomimic 和 MetaWorld** 等 14 个任务中进行验证。
- 相比基线方法，性能提升最高达 **43%**。
