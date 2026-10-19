<!-- dubline-subs {"title": "Using Jev In Your Agent Harness", "author": "Sam Witteveen", "files": 3, "updated": "2026-10-19"} -->
# Using Jev In Your Agent Harness

<img src="04551d/60fb6e9a/Using%20Jev%20In%20Your%20Agent%20Harness.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=zaLQ0AnY9dI](https://www.youtube.com/watch?v=zaLQ0AnY9dI) |
| 发布 | 2026-09-29 |
| 时长 | 20 分 24 秒 |
| 语言 | 英语 |
| 原作者 | [Sam Witteveen](https://www.youtube.com/@samwitteveenai)（@samwitteveenai，约 14 万订阅） |

## 中文信息

**标题**：20 分钟，用 Jev 把智能体的 LLM 调用成本砍一半

**原标题译文**：在您的 Agent Harness 中使用 Jev

在构建智能体（Agent）的过程中，很多开发者都会遇到一个核心痛点：为了让智能体能够做出正确的决策或判断，往往需要频繁调用高性能的大语言模型（LLM）。然而，随着用户量增加和逻辑变得复杂，这种全量调用不仅会导致 Token 成本大幅飙升，还会显著拖慢系统的响应速度。本期视频将带你深入探讨如何利用 Jev 等开放决策模型来优化这一流程，通过引入“智能 if 语句”机制，在保证系统逻辑准确性的同时，有效降低一半以上的 Token 消耗，并提升整体运行效率。

通过这期视频的学习，你将掌握以下核心知识点：首先是理解智能体循环中模型调用的本质，即大部分决策任务并不需要复杂的文本生成能力，而只需要精准的分类或判断；其次是深入了解 Jev 作为一种无需生成文本、支持并行多问的概率化分类模型的特性，以及它在智能体循环中的六大核心集成位置。具体实操层面，你将学习到如何构建级联分类器架构来大幅节省成本，如何通过风险门控机制在执行前拦截不安全操作以增强系统鲁棒性，以及如何在 RAG（检索增强生成）流程中利用决策模型进行结果重排序与评分。此外，视频还会讲解渐进式披露策略以优化资源加载，以及如何利用分诊功能来评估工单紧急程度。同时，为了确保工程落地可行，视频还会明确指出决策模型在长文本生成、多步复杂推理等场景中的局限性，并提醒在处理提示词注入时的潜在风险。

本期内容非常适合正在构建或优化 LLM Agent 框架的开发者与工程师，以及希望通过技术手段降低项目运营成本、提升响应速度的技术决策者。如果你正面临高昂的 Token 账单，或者在追求更高效的任务分派和检索结果优化时遇到瓶颈，这期视频将为你提供实用的解决方案。

观看完本视频后，你将能够掌握基于 OpenRouter 和 LangChain 的实操建议，学会通过引入决策模型来重构你的智能体工作流。你将具备在实际项目中部署级联分类器、建立风险过滤机制以及优化 RAG 流程的能力，从而构建出一个既经济又高效的智能体系统。如果你具备基础的 Python 编程经验以及对 LangChain 或 OpenRouter 等工具的基本了解，本期教程将为你提供非常实用的技术路径。

章节
00:00 Intro
00:58 The Agent Loop
02:35 The Cost of Full LLM Calls
03:17 Jev as a Smart If Statement
04:26 Model Routing
04:52 Risk Gating
05:43 Tool & Skill Selection
06:16 Ranking & Judging
06:36 Triage & Real-Time Filtering
07:41 Wiring Jev Into the Loop
08:35 Jev Runs the Loop
09:15 Where Jev Doesn't Fit
10:26 Compound Questions & Prompt Injection
11:12 Decision Criteria & Local vs Cloud
12:19 Demo: Skill Progressive Disclosure
16:33 Demo: RAG Re-ranking with Jev
19:18 Resources: OpenRouter & LangChain

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Using Jev In Your Agent Harness - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](04551d/cd9350ba/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7EJ13/04551d/cd9350ba/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Using Jev In Your Agent Harness - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](04551d/e28ae8f8/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7EJ13/04551d/e28ae8f8/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Using Jev In Your Agent Harness - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](04551d/ff7a83ec/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/7EJ13/04551d/ff7a83ec/Using%20Jev%20In%20Your%20Agent%20Harness%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00 | Intro |
| 00:58 | The Agent Loop |
| 02:35 | The Cost of Full LLM Calls |
| 03:17 | Jev as a Smart If Statement |
| 04:26 | Model Routing |
| 04:52 | Risk Gating |
| 05:43 | Tool & Skill Selection |
| 06:16 | Ranking & Judging |
| 06:36 | Triage & Real-Time Filtering |
| 07:41 | Wiring Jev Into the Loop |
| 08:35 | Jev Runs the Loop |
| 09:15 | Where Jev Doesn't Fit |
| 10:26 | Compound Questions & Prompt Injection |
| 11:12 | Decision Criteria & Local vs Cloud |
| 12:19 | Demo: Skill Progressive Disclosure |
| 16:33 | Demo: RAG Re-ranking with Jev |
| 19:18 | Resources: OpenRouter & LangChain |

## 原视频简介

In this video I return to looking at how you can use Jev in an Agent Harness

---

视频内容版权归原作者所有，字幕仅供学习交流。
