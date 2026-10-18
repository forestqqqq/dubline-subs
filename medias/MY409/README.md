<!-- dubline-subs {"title": "Why One AI Agent Isn’t Enough (And How to Run 1,000) - CJ Avilla & Harrison Stall, Anthropic", "author": "AI Engineer", "files": 3, "updated": "2026-10-17"} -->
# Why One AI Agent Isn’t Enough (And How to Run 1,000) - CJ Avilla & Harrison Stall, Anthropic

<img src="b3b34a/e2f0632a/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=kiClTcJUnhc](https://www.youtube.com/watch?v=kiClTcJUnhc) |
| 发布 | 2026-10-16 |
| 时长 | 1 小时 41 分 43 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 76 万订阅） |

## 中文信息

**标题**：支持 1000 个智能体协作：Anthropic 发布的动态工作流实战

**原标题译文**：为什么一个 AI Agent 不够用（以及如何运行 1,000 个）- CJ Avilla & Harrison Stall, Anthropic

本期视频带你深度解析 Anthropic 最新发布的云端托管智能体以及动态工作流核心技术。随着 AI 应用从简单的对话走向复杂的工程化落地，单智能体在处理长链路、高复杂度任务时往往会遇到严重的痛点，例如模型变得懒惰、产生自我偏好偏差或者在过程中出现目标漂移。Anthropic 提出的动态工作流正是为了解决这些问题而生的核心方案。通过将复杂任务拆解为多智能体协作，并利用 API 端实现的编排方式，系统能够自动规划并协调多达 1000 个子智能体协同完成任务。

在本次视频中，你将学到以下关键技术点：
首先是动态工作流的实操逻辑，了解如何通过这种架构降低开发者管理复杂拓扑结构的负担；
其次是关于“生成器与判别器分离”以及扇出机制的深度解析，学习如何让不同智能体分别负责内容生产和审核验证，从而显著提升处理海量数据时的准确性；
第三是资源差异化分配策略。视频将演示如何在低成本要求的扫描阶段使用快速模型（如 Haiku），而在高标准要求的审核或推理阶段切换到高性能模型（如 Opus），实现成本与效果的最优平衡；
此外，还会深入探讨“大脑”与“手”的物理分离架构。通过出站代理层和凭据库等技术手段，将推理逻辑与执行工具在物理上隔离，确保生产环境中的敏感信息不被泄露；
最后是核心安全三原则：涵盖声明、隔离、检测三个维度的实操标准，包括如何定义受限的运行环境以及通过防火墙限制特定域名的访问。

本期内容非常适合正在构建生产级 AI 应用的工程师和技术负责人，或者是关注多智能体系统架构、致力于解决复杂工作流编排难题的开发者。同时，如果你是面临 AI 智能体在处理复杂任务时稳定性不足、安全性难以把控等问题的技术决策者，这期视频提供的架构思路将非常有参考价值。

通过观看本期视频，你将能够掌握从单一模型应用向大规模多智能体协作系统的跨越式思维。你将学会如何构建更稳健的自动化流程，利用“爬坡”技术让模型自动迭代优化提示词，并建立起一套符合工业标准的安全防护体系。无论你是希望提升现有产品的稳定性，还是在探索如何通过 Anthropic 提供的托管服务进行规模化扩展，本视频都将为你提供清晰的技术路径和实战思路。

章节
0:00 Unix 与 OS/360：扩展性问题
6:00 介绍 CJ 与 Harrison
7:00 介绍 Claude Managed Agents 中的 Flows
9:05 为什么单智能体会遇到瓶颈
14:00 动态工作流如何运作
17:25 演示：股票观察清单扫描器
23:20 从控制台到生产：优化每个阶段
32:15 问答环节 1
1:04:45 Bug Hunter：多智能体 PR 审查
1:07:15 Explainer Studio：制作视频的流式工作流
1:12:15 懒惰、自我偏好与目标漂移
1:15:20 大规模场景下的智能体安全
1:20:05 声明、隔离、检测
1:21:15 将大脑与手分离
1:27:50 凭据库与工具锁定
1:31:45 总结与问答环节 2

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Why One AI Agent Isn’t Enough (And How to Run 1,000) - CJ Avilla & Harrison Stall, Anthropic - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](b3b34a/9562da6b/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MY409/b3b34a/9562da6b/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Why One AI Agent Isn’t Enough (And How to Run 1,000) - CJ Avilla & Harrison Stall, Anthropic - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](b3b34a/be5c5366/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MY409/b3b34a/be5c5366/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Why One AI Agent Isn’t Enough (And How to Run 1,000) - CJ Avilla & Harrison Stall, Anthropic - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](b3b34a/e1c89ae4/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/MY409/b3b34a/e1c89ae4/Why%20One%20AI%20Agent%20Isn%E2%80%99t%20Enough%20%28And%20How%20to%20Run%201%2C000%29%20-%20CJ%20Avilla%20%26%20Harrison%20Stall%2C%20Anthropic%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Unix vs. OS/360: the scaling problem |
| 6:00 | Meet CJ & Harrison |
| 7:00 | Introducing Flows in Claude Managed Agents |
| 9:05 | Why single agents hit a wall |
| 14:00 | How dynamic workflows work |
| 17:25 | Demo: stock watchlist scanner |
| 23:20 | From console to production: tuning each phase |
| 32:15 | Q&A, round 1 |
| 1:04:45 | Bug Hunter: multi-agent PR review |
| 1:07:15 | Explainer Studio: flows that make videos |
| 1:12:15 | Laziness, self-bias & goal drift |
| 1:15:20 | Agent safety at scale |
| 1:20:05 | Declare, contain, detect |
| 1:21:15 | Separating the brain from the hands |
| 1:27:50 | Credential vaults & locking down tools |
| 1:31:45 | Wrap-up + Q&A, round 2 |

## 原视频简介

Ken Thompson built Unix in a month. IBM put 1,000 engineers on OS/360. And in 1998, Linus Torvalds hit his limit. Now we're hitting that same wall managing AI agents.

---

视频内容版权归原作者所有，字幕仅供学习交流。
