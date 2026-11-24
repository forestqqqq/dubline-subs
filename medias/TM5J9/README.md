<!-- dubline-subs {"title": "CS329Z Lecture 6: Agent Design Patterns & Scaffolds — Engineering AI Agents (unofficial walkthrough)", "author": "CatDataING", "files": 3, "updated": "2026-11-23"} -->
# CS329Z Lecture 6: Agent Design Patterns & Scaffolds — Engineering AI Agents (unofficial walkthrough)

<img src="ab0928/24fb8630/CS329Z%20Lecture%206%20Agent%20Design%20Patterns%20%26%20Scaffolds%20%E2%80%94%20Engineering%20AI%20Agents%20%28unofficial%20walkthrough%29.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=N-pz69yBvOc](https://www.youtube.com/watch?v=N-pz69yBvOc) |
| 发布 | 2026-10-18 |
| 时长 | 57 分 43 秒 |
| 语言 | 英语 |
| 原作者 | [CatDataING](https://www.youtube.com/@catdataing3822)（@catdataing3822，923 订阅） |

## 中文信息

**标题**：【中配】57分钟带你拆解Agent设计模式，从ReAct到上下文工程

**原标题译文**：CS329Z 第6讲：Agent 设计模式与脚手架 —— 工程化 AI Agent（非官方讲解）

这期视频将带你深入拆解 AI 智能体（Agent）的核心设计模式与工程架构。随着大模型技术的快速发展，简单的提示词工程已经不足以支撑复杂的业务需求，构建能够自主决策、具备复杂逻辑推理能力的智能体系统成为了开发者面临的核心挑战。本视频旨在为开发者提供一套从理论到工程实践的完整指南，帮助你理解如何构建复杂、可扩展且高效的智能体系统。

在视频中，我们将首先厘清智能体基础的核心概念，特别是工作流（Workflow）与智能体（Agent）之间的本质区别。工作流通常是预定义路径的高可预测性调用，而智能体则是模型在自主决策下展现出的高灵活性系统。通过对比这两者的差异，你可以更清晰地判断在什么场景下该使用固定的工作流，又在什么情况下需要引入智能体的自主决策能力。

接着，我们将深入探讨五种基础工作流模式：包括提示词链（Prompt Chaining）、路由（Routing）、并行化（Parallelization）、编排器-工作者（Orchestrator-Workers）以及评估器-优化器（Evaluator-Optimizer）。这些模式构成了构建复杂系统的基石，视频将详细讲解每种模式的适用场景及其在实际工程中的组合方式。

视频的核心内容之一是针对多种推理与行动模式的深度解析。我们将详细拆解 ReAct 模式，即通过思考、行动、观察的循环，让模型在采取行动前进行推理，从而减少幻觉并利用错误反馈进行自我修正。此外，我们还会对比反思（Reflection）模式、代码操作（Code Act）以及 ReWOO 模式。例如，反思模式通过在上下文窗口中保存反思句子来实现类似文字版的强化学习；而代码操作模式则通过利用 Python 处理逻辑来减少交互轮数和 Token 消耗，但这也带来了对沙箱环境的需求。我们还会探讨 ReWOO 如何提高 Token 效率，以及 LLM 编译器如何通过将任务转化为有向无环图（DAG）来实现并行化处理。

除了推理逻辑，上下文工程（Context Engineering）是决定智能体能否在长对话中保持稳定运行的关键。视频将讲解上下文管理的核心原则：即如何聚焦于当前步骤所需的上下文，同时保持目标、约束和关键历史的连续性。我们将介绍五种具体的上下文管理模式：事件日志、内存卸载、压缩、观测掩码以及上下文隔离。同时，为了提升工程效率，视频还会涉及 KV cache 优化技术，讲解如何通过保持提示词开头的一致性来利用缓存，并通过修改结尾来更新信息。

最后，视频将进入实战架构与安全讨论。我们将以 Pi 框架为例，展示其极简主义设计如何支持 Read、Write、Edit 和 Bash 等工具，并展示其如何利用事件日志和压缩技术处理长对话。同时，我们也会警惕在缺乏权限检查的脚手架中可能出现的提示词注入风险，讨论智能体执行网页或文件中的恶意指令带来的安全威胁。

本视频非常适合那些已经具备一定大模型基础，并且正准备从简单的提示词工程转向构建复杂 Agent 系统、或是在实际工程中遇到智能体逻辑混乱、上下文丢失等问题的开发者。看完本视频后，你将能够准确区分工作流与智能体的应用边界，掌握 ReAct、反思等多种核心推理模式的实现原理，学会运用多种策略进行高效的上下文管理，并能够基于工业级的架构思路去设计和优化自己的智能体系统，从而构建出更稳健、更强大的 AI 应用。

原视频：CS329Z Lecture 6: Agent Design Patterns & Scaffolds — Engineering AI Agents (unofficial walkthrough)
原作者：CatDataING
发布日期：2026-10-18
视频链接：https://www.youtube.com/watch?v=N-pz69yBvOc

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| CS329Z Lecture 6 Agent Design Patterns & Scaffolds — Engineering AI Agents (unofficial walkthrough) - 英语字幕（转写）.en.srt | 原文字幕（转写）（原片时间轴） | [查看 / 下载](287494/74eb5347/CS329Z%20Lecture%206%20Agent%20Design%20Patterns%20%26%20Scaffolds%20%E2%80%94%20Engineering%20AI%20Agents%20%28unofficial%20walkthrough%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TM5J9/287494/74eb5347/CS329Z%20Lecture%206%20Agent%20Design%20Patterns%20%26%20Scaffolds%20%E2%80%94%20Engineering%20AI%20Agents%20%28unofficial%20walkthrough%29%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| CS329Z Lecture 6 Agent Design Patterns & Scaffolds — Engineering AI Agents (unofficial walkthrough) - 中英双语字幕.srt | 双语字幕（原片时间轴） | [查看 / 下载](287494/7efb6d85/CS329Z%20Lecture%206%20Agent%20Design%20Patterns%20%26%20Scaffolds%20%E2%80%94%20Engineering%20AI%20Agents%20%28unofficial%20walkthrough%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TM5J9/287494/7efb6d85/CS329Z%20Lecture%206%20Agent%20Design%20Patterns%20%26%20Scaffolds%20%E2%80%94%20Engineering%20AI%20Agents%20%28unofficial%20walkthrough%29%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| dubbed.srt | 配音版字幕（配音版时间轴） | [查看 / 下载](287494/a9be2669/dubbed.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/TM5J9/287494/a9be2669/dubbed.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频简介

An unofficial, AI-generated walkthrough of Stanford CS329Z: Engineering AI Agents, Lecture 6: Agent Design Patterns & Scaffolds (originally Monday, October 12, 2026).

---

视频内容版权归原作者所有，字幕仅供学习交流。
