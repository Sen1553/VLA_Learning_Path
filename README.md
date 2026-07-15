# VLA Learning Path

> 💡 **Vision-Language-Action（VLA）个人学习路线记录：精选重要工作，并用简短总结与 Poster笔记 梳理学习脉络。**



### 🎯 收录原则

VLA 领域工作众多，本仓库不追求完整收录，仅记录具有代表性、里程碑意义，或对技术路线有重要影响的工作。

本仓库不提供逐篇文字笔记。每篇论文仅保留一份由个人阅读笔记提炼而成的**总结 PDF**，用于快速回顾核心方法、模型结构与实验结论。

## 分类方式

表中的类别按照 VLA 领域两条主要技术分支组织：

| 类别 | 生成方式 |
| --- | --- |
| **Autoregressive** | 以自回归 VLA 为主线 |
| **Diffusion/Flow-based** | 通过去噪或流匹配生成动作，可直接建模连续、多峰的动作分布 |


## 学习路线

| # | 分类 | 论文 | 时间 | TL;DR | 阅读总结 |
| :---: | --- | --- | :---: | --- | :---: |
| 1 | Autoregressive | [OpenVLA: An Open-Source Vision-Language-Action Model](https://arxiv.org/abs/2406.09246) | 2024.06 | 开源的 7B VLA，在 97 万条真实机器人轨迹上训练，将视觉、语言与离散动作 token 统一到自回归生成框架中。 | 待整理 |
| 2 | Autoregressive | [OpenVLA-OFT: Fine-Tuning Vision-Language-Action Models: Optimizing Speed and Success](https://arxiv.org/abs/2502.19645) | 2025.02 | 提出 OFT 微调方案，以并行解码、动作分块、连续动作表示和 L1 回归显著提升 OpenVLA 的推理速度与任务成功率。 | 待整理 |
| 3 | -- | [LIBERO: Benchmarking Knowledge Transfer for Lifelong Robot Learning](https://arxiv.org/abs/2306.03310) | 2023.06 | 面向机器人终身学习与知识迁移的基准，提供 4 个任务套件、共 130 个任务及配套的人类遥操作演示数据。 | 待整理 |
| 4 | Diffusion/Flow-based | [$\pi_{0}$: A Vision-Language-Action Flow Model for General Robot Control](https://arxiv.org/abs/2410.24164) | 2024.10 | 在预训练 VLM 上引入 Flow Matching 动作专家，并利用跨机器人平台的大规模数据训练通用机器人策略。 | 待整理 |
| 5 | Diffusion/Flow-based | [$\pi_{0.5}$: a Vision-Language-Action Model with Open-World Generalization](https://arxiv.org/abs/2504.16054) | 2025.04 | 在 $\pi_{0}$ 之上引入异构数据协同训练与高层语义子任务预测，使机器人能在未见过的家庭环境中完成长时程、灵巧操作。 | <a href="./reading_note/pi05/pi05.pdf"><img src="./reading_note/pi05/pi05.png" alt="π_0.5 总结 PDF 首页" width="160"></a> |



