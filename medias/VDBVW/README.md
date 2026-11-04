<!-- dubline-subs {"title": "Stanford CS229 I Machine Learning I Building Large Language Models (LLMs)", "author": "Stanford Online", "files": 3, "updated": "2026-11-03"} -->
# Stanford CS229 I Machine Learning I Building Large Language Models (LLMs)

<img src="861803/711cecf4/Stanford%20CS229%20I%20Machine%20Learning%20I%20Building%20Large%20Language%20Models%20%28LLMs%29.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=9vM4p9NN0Ts](https://www.youtube.com/watch?v=9vM4p9NN0Ts) |
| 发布 | 2024-08-27 |
| 时长 | 1 小时 44 分 31 秒 |
| 语言 | 英语 |
| 原作者 | [Stanford Online](https://www.youtube.com/@stanfordonline)（@stanfordonline，约 132 万订阅） |

## 中文信息

**标题**：【中配】1 小时 44 分钟，带你拆解 Llama 3 背后 7500 万美元的训练逻辑

**原标题译文**：Stanford CS229 I 机器学习 I 构建大语言模型 (LLMs)

这期视频将带你深入工业界视角，系统性地拆解构建大语言模型（LLM）的核心全生命周期。我们不仅仅是停留在表面概念，而是通过 Llama 3 背后耗资 7500 万美元的训练逻辑作为切入点，全方位剖析从预训练到后训练（SFT/RLHF）的完整技术路径。无论你是想了解模型是如何“学习”知识的，还是想知道如何在有限的算力下实现最优的工程落地，这期视频都将为你提供极其硬核的干货。

通过本视频的学习，你将掌握以下核心知识点：

首先是 LLM 构建的五个核心组件。我们将探讨在实际工业生产中，数据质量、评估体系和系统工程的权重往往高于单纯的架构创新。你会了解到如何平衡架构、算法、数据、评估和系统工程这五个维度的资源分配。

其次是预训练的基础原理。视频将详细讲解自回归语言模型的建模原理，包括如何通过概率链式法则预测下一个 Token，以及如何利用交叉熵损失函数来最大化文本的对数似然。同时，我们还会深入探讨分词技术（Tokenizer），特别是 BPE 算法的原理，以及它如何影响模型的代码和数学理解能力。

接着是模型规模与数据的核心逻辑。我们将重点剖析缩放定律（Scaling Laws），学习如何利用小模型拟合出的曲线来指导大规模模型的训练决策。视频还会引用 Chinchilla 最优比例的研究，探讨参数量与 Token 数量之间的最优比例关系。此外，你还将看到完整的数据工程流水线，包括从 Common Crawl 提取文本、过滤有害内容、大规模去重，到基于启发式规则和机器学习模型进行质量过滤的实操流程。

在工程落地方面，视频涵盖了关键的系统工程优化技巧。我们将讨论如何利用自动混合精度（AMP）、算子融合（Operator Fusion）以及 torch.compile 等技术来减少通信开销并提升吞吐量。最后，视频将带你进入后训练阶段，讲解奖励模型（Reward Model）的训练，以及 PPO 和 DPO 算法在模型对齐到人类偏好中的对比应用。

本视频非常适合机器学习研究者、AI 工程人员，以及希望深入了解 LLM 底层构建逻辑的开发者。如果你具备基础的机器学习知识（例如了解交叉熵损失函数）并且拥有基本的 Python 编程基础，那么这期视频将是你进阶 AI 领域的必备课程。

看完这期视频后，你将能够从全局视角理解大模型诞生的全过程。你不仅能掌握从数据清洗到模型对齐的每一个关键技术环节，还能学会如何通过缩放定律进行科学的训练规划，并掌握工业界常用的系统工程优化手段。通过这 1 小时 44 分钟的深度拆解，你将能够独立分析不同模型背后的训练逻辑，为自己的 AI 项目提供更具工业水准的技术支撑。

章节
00:00 介绍
00:10 LLM 回顾
00:16 LLM 定义
00:19 LLM 示例
01:16 数据的重要性
01:20 评估指标
01:33 系统组件
01:41 系统的重要性
01:47 基于 Transformer 的 LLM
01:57 聚焦核心主题
02:00 过渡到预训练
03:02 语言建模概述
04:17 生成式模型解释
05:15 自回归模型定义
06:36 自回归任务解释
07:49 训练概述
08:48 分词的重要性
10:50 分词过程
13:30 分词示例
16:00 使用困惑度进行评估
20:50 当前的评估方法
24:30 学术基准：MMLU

原视频：Stanford CS229 I Machine Learning I Building Large Language Models (LLMs)
原作者：Stanford Online
发布日期：2024-08-27
视频链接：https://www.youtube.com/watch?v=9vM4p9NN0Ts

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Stanford CS229 I Machine Learning I Building Large Language Models (LLMs) - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](861803/08670fa3/Stanford%20CS229%20I%20Machine%20Learning%20I%20Building%20Large%20Language%20Models%20%28LLMs%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VDBVW/861803/08670fa3/Stanford%20CS229%20I%20Machine%20Learning%20I%20Building%20Large%20Language%20Models%20%28LLMs%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](861803/585b9a14/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VDBVW/861803/585b9a14/dubbed.srt) |
| Stanford CS229 I Machine Learning I Building Large Language Models (LLMs) - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](861803/9f82c401/Stanford%20CS229%20I%20Machine%20Learning%20I%20Building%20Large%20Language%20Models%20%28LLMs%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/VDBVW/861803/9f82c401/Stanford%20CS229%20I%20Machine%20Learning%20I%20Building%20Large%20Language%20Models%20%28LLMs%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Introduction |
| 00:10 | Recap on LLMs |
| 00:16 | Definition of LLMs |
| 00:19 | Examples of LLMs |
| 01:16 | Importance of Data |
| 01:20 | Evaluation Metrics |
| 01:33 | Systems Component |
| 01:41 | Importance of Systems |
| 01:47 | LLMs Based on Transformers |
| 01:57 | Focus on Key Topics |
| 02:00 | Transition to Pretraining |
| 03:02 | Overview of Language Modeling |
| 04:17 | Generative Models Explained |
| 05:15 | Autoregressive Models Definition |
| 06:36 | Autoregressive Task Explanation |
| 07:49 | Training Overview |
| 08:48 | Tokenization Importance |
| 10:50 | Tokenization Process |
| 13:30 | Example of Tokenization |
| 16:00 | Evaluation with Perplexity |
| 20:50 | Current Evaluation Methods |
| 24:30 | Academic Benchmark: MMLU |

## 原视频简介

For more information about Stanford's Artificial Intelligence programs visit: https://stanford.io/ai

---

视频内容版权归原作者所有，字幕仅供学习交流。
