<!-- dubline-subs {"title": "Build & Train a GLM-5.3-Flash Model From Scratch with Python", "author": "freeCodeCamp.org", "files": 3, "updated": "2026-10-20"} -->
# Build & Train a GLM-5.3-Flash Model From Scratch with Python

<img src="4148fa/bd1854d0/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=-gfgQfw2g_E](https://www.youtube.com/watch?v=-gfgQfw2g_E) |
| 发布 | 2026-10-06 |
| 时长 | 44 分 26 秒 |
| 语言 | 英语 |
| 原作者 | [freeCodeCamp.org](https://www.youtube.com/@freecodecamp)（@freecodecamp，119 订阅） |

## 中文信息

**标题**：从零手写并训练一个 2500 万参数的 GLM-5.3-Flash 模型

**原标题译文**：使用 Python 从零开始构建并训练 GLM-5.3-Flash 模型

本期视频带你深度参与一项极具实战意义的科研项目：从零开始手写并训练一个包含 2500 万参数的 GLM-5.3-Flash 模型（代号 Ox Alpha）。这不仅仅是一个简单的模型复现过程，而是通过这个具体的实战案例，全方位拆解现代 AI 研究的核心流程。视频将带你走过从底层架构设计、多模态融合技术到预训练策略，再到基于强化学习的后训练优化的完整科研链路，旨在帮助观众建立起系统性的科研思维。

在这一期内容中，你将掌握以下核心知识点：
第一，模型基础与架构选型。包括如何通过小词表策略（如 260 个 ASCII 字符）来节省参数空间，以及对 RoPE 位置编码、RMSNorm、AdamW 等关键组件的实战应用；同时深入对比标准注意力、线性注意力与稀疏索引器的优劣。
第二，高效架构设计。详细讲解如何利用混合专家模型（MoE）中的共享专家处理通用信息，并结合特定专家处理特定任务以降低冗余。
第三，多模态融合技术。学习如何通过 Patch Embeddings 将图像切片转化为 token，并利用 2D RoPE 处理视觉位置信息。
第四，预训练与后训练的本质区别。明确预训练是基于交叉熵的模仿学习以获取基础知识，而强化学习则是通过奖励机制引导模型学会思考并解决复杂任务。
第五，强化学习实战。深入讲解 GRPO 算法的应用、多维度奖励函数的设计（如格式与正确性），以及在实验过程中如何控制变量（如 Temperature 和 Group Size）并确保统计显著性。

本视频非常适合有一定 Python 基础，且渴望深入了解大模型底层架构、研究方法论以及强化学习实战流程的 AI 爱好者或准研究员。通过观看本期内容，你将能够跳出单纯的代码堆砌，从宏观角度理解科研人员的核心价值在于设计实验与优化算法。看完视频后，你不仅能掌握构建 GLM-5.3-Flash 模型的技术细节，还能建立起严谨的实验科学原则，学会如何通过多维度评估和统计分析来验证模型的真实能力，从而在实际研究中避免模型“作弊”或陷入无效实验的误区。

章节
00:00 介绍与我们将要构建的内容
01:02 现代 AI 研究员的角色与提问方法
04:50 词表设计与字节级词汇表（为何小词表很重要）
07:01 嵌入向量与 Transformer 前向传播概述
08:53 GLM-5.3 架构概览与模型规格
10:25 代码实战：嵌入与 Token 表示
11:56 流形约束超连接（DeepSeek 残差）
13:27 输出投影与权重共享
14:27 RMSNorm 与归一化层
15:10 位置编码（RoPE 对比无 RoPE）与稀疏注意力索引器
18:30 线性注意力（状态空间记忆）对比稀疏注意力
20:46 混合专家模型 (MoE) 与共享专家
23:06 加入视觉：Patch Embeddings 与 2D RoPE
26:14 预训练流水线、损失函数与优化（AdamW）
28:05 预训练实验：数据多样性、交错与课程学习
30:27 后训练与强化学习 (RL) 设置
34:44 设计奖励函数与群体相对策略优化 (GRPO)
37:37 参数高效的 RL 更新与冻结层
39:35 评估 RL 结果：任务收益与退化风险
40:47 RL 超参数实验：群体规模、温度与种子
43:03 总结与给抱负中的 AI 研究者的建议

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Build & Train a GLM-5.3-Flash Model From Scratch with Python - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](5c7b81/1e43e9d7/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/A6ZYZ/5c7b81/1e43e9d7/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Build & Train a GLM-5.3-Flash Model From Scratch with Python - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](5c7b81/2eb256d5/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/A6ZYZ/5c7b81/2eb256d5/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Build & Train a GLM-5.3-Flash Model From Scratch with Python - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](5c7b81/70802aae/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/A6ZYZ/5c7b81/70802aae/Build%20%26%20Train%20a%20GLM-5.3-Flash%20Model%20From%20Scratch%20with%20Python%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Introduction & What We're Building |
| 01:02 | The Modern AI Researcher Role & Asking Research Questions |
| 04:50 | Tokenization & Byte-Level Vocabulary (Why Small Vocab Matters) |
| 07:01 | Embeddings & Transformer Forward Pass Overview |
| 08:53 | GLM-5.3 Architecture Overview & Model Specifications |
| 10:25 | Code Walkthrough: Embeddings & Token Representation |
| 11:56 | Manifold Constrained Hyperconnections (DeepSeek Residuals) |
| 13:27 | Output Projection & Weight Tying |
| 14:27 | RMSNorm & Normalization Layers |
| 15:10 | Positional Encodings (RoPE vs. NoPE) & Sparse Attention Indexer |
| 18:30 | Linear Attention (State-Space Memory) vs. Sparse Attention |
| 20:46 | Mixture of Experts (MoE) & Shared Experts |
| 23:06 | Adding Vision: Patch Embeddings & 2D RoPE |
| 26:14 | Pre-Training Pipeline, Loss & Optimization (AdamW) |
| 28:05 | Pre-Training Experiments: Data Diversity, Interleaving & Curriculums |
| 30:27 | Post-Training & Reinforcement Learning (RL) Setup |
| 34:44 | Designing Reward Functions & Group Relative Policy Optimization (GRPO) |
| 37:37 | Parameter-Efficient RL Updates & Freezing Layers |
| 39:35 | Evaluating RL Results: Task Gains & Regression Risks |
| 40:47 | RL Hyperparameter Experiments: Group Size, Temperature & Seeds |
| 43:03 | Summary & Advice for Aspiring AI Researchers |

## 原视频简介

Learn how to design, build, and train an advanced multimodal language model from scratch using modern techniques like mixture-of-experts, sparse attention, and reinforcement learning. This hands-on guide walks you through the entire lifecycle from tokenization and pre-training to post-training optimization and evaluation.

---

视频内容版权归原作者所有，字幕仅供学习交流。
