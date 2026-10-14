<!-- dubline-subs {"title": "How to Build Quality Gates into Agentic Coding Workflows — Nnenna Ndukwe, Qodo AI", "author": "AI Engineer", "files": 3, "updated": "2026-10-14"} -->
# How to Build Quality Gates into Agentic Coding Workflows — Nnenna Ndukwe, Qodo AI

<img src="ec0588/8bac1c52/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=-AKPRSYccJc](https://www.youtube.com/watch?v=-AKPRSYccJc) |
| 发布 | 2026-10-11 |
| 时长 | 57 分 45 秒 |
| 语言 | 英语 |
| 原作者 | [AI Engineer](https://www.youtube.com/@aiDotEngineer)（@aiDotEngineer，约 69 万订阅） |

## 中文信息

**标题**：57分钟实操：用多层级质量门禁让AI Agent写出生产级代码

**原标题译文**：如何在 Agentic Coding 工作流中构建质量门禁 —— Nnenna Ndukwe, Qodo AI

在当前的 AI 编程浪潮中，许多开发者和团队在实际应用时都会遇到一个核心痛点：虽然 AI 生成代码的速度极快，但往往难以直接达到生产环境的标准，经常出现逻辑不严谨、不符合团队规范或无法通过自动化测试的情况。本期视频将带你深入探讨如何通过构建结构化的工作流，并定义明确的规则与技能系统，在 AI Agent 的编程过程中建立起多层级的质量门禁。通过这套机制，我们可以确保 AI 生成的代码不仅是能跑通，而是真正符合团队工程标准且能够自动通过各类验证。

在本期实操视频中，你将获得以下核心知识点：
首先是结构化工作流的构建，学习如何利用 agents.md 和专门的规则文件为 AI 提供清晰的上下文，让 Agent 在执行任务前进入预设的规划模式。
其次是双层计划机制的落地，要求 Agent 先生成高层级的实施计划（Implementation Plan），再细化为具体的执行计划（Execution Plan），确保每一步操作都有据可依。
第三是确定性验证的集成，演示如何在本地阶段利用 Ruff、PyTest 和 Semgrep 等工具进行自动化检查，从源头上拦截不规范的代码。
第四是规则分级与严重程度管理，学习如何对不同类型的规则赋予不同的权重，从而精准控制哪些问题会导致构建阻塞。
第五是技能（Skills）系统的应用，通过引入特定技能让 Agent 能够自动关联相关的工程标准和工具链。
最后是自动化修复循环的闭环，演示在 PR 阶段利用 Qodo 等工具自动识别违规项，并由专门的 Resolver 技能自动修复高风险问题。

本视频内容非常适合正在探索 AI 工程领域的开发者、软件架构师，以及希望将 AI Agent 正式引入生产环境的工程团队。如果你具备一定的 Python 开发基础，熟悉 FastAPI 框架和 Git 工作流（如 Pull Request），并且对 AI 提示词工程有初步了解，那么这期视频将为你提供极具实操价值的参考。

通过观看本视频并跟随其中的实操步骤，你将能够掌握一套完整的、可落地的工业级 AI Agent 开发规范。你将学会如何构建从任务拆解、计划制定到本地验证、再到自动化修复的完整全链路流程。

章节
0:00 结构化 AI 编程工作流
3:15 代码质量崩溃点
4:09 定义并编成规则
5:06 操作化上下文
6:00 SignalPay 工作坊仓库
7:11 规划、测试和审查门禁
8:21 仓库结构与本地设置
10:00 质量检查点与共享规则
11:32 计划与验证证据
13:23 将 Qodo 连接到仓库
16:55 选择支付工作流
18:13 为 Codex 配置规则和技能
20:47 在实施前规划变更
25:07 遍历规划模板
27:13 构建执行与完成笔记
28:38 实现退款工作流
29:07 技能与本地代码审查
33:17 规则类别与严重程度
36:14 推断规则与人工批准
39:10 发起 Pull Request 进行审查
42:24 验证与审查上下文
44:00 规则违规与构建阻塞
45:46 确定性与规则选择限制
47:13 检查评审结果
49:03 使用 Agent 技能解决问题
50:16 重新运行验证并更新 PR
53:08 复用工作坊流程
55:15 关于上下文和部署的问题
56:39 验证完成的修复

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| How to Build Quality Gates into Agentic Coding Workflows — Nnenna Ndukwe, Qodo AI - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](ec0588/03c9a65d/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Y0BPM/ec0588/03c9a65d/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| How to Build Quality Gates into Agentic Coding Workflows — Nnenna Ndukwe, Qodo AI - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](ec0588/d77352da/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Y0BPM/ec0588/d77352da/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| How to Build Quality Gates into Agentic Coding Workflows — Nnenna Ndukwe, Qodo AI - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](ec0588/f7f7da2d/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/Y0BPM/ec0588/f7f7da2d/How%20to%20Build%20Quality%20Gates%20into%20Agentic%20Coding%20Workflows%20%E2%80%94%20Nnenna%20Ndukwe%2C%20Qodo%20AI%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Structured AI coding workflows |
| 3:15 | Where code quality breaks down |
| 4:09 | Define and codify standards |
| 5:06 | Operationalize context |
| 6:00 | The SignalPay workshop repository |
| 7:11 | Planning, testing, and review gates |
| 8:21 | Repository structure and local setup |
| 10:00 | Quality checkpoints and shared rules |
| 11:32 | Plans and verification evidence |
| 13:23 | Connect Qodo to the repository |
| 16:55 | Choose a payment workflow |
| 18:13 | Prepare Codex with rules and skills |
| 20:47 | Plan the change before implementation |
| 25:07 | Walk through planning templates |
| 27:13 | Build execution and completion notes |
| 28:38 | Implement the refund workflow |
| 29:07 | Skills and local code review |
| 33:17 | Rule categories and severity |
| 36:14 | Inferred rules and human approval |
| 39:10 | Open the pull request for review |
| 42:24 | Verification and review context |
| 44:00 | Rule violations and merge blocking |
| 45:46 | Determinism and rule selection limits |
| 47:13 | Inspect the review findings |
| 49:03 | Resolve issues with an agent skill |
| 50:16 | Rerun verification and update the PR |
| 53:08 | Reuse the workshop process |
| 55:15 | Questions on context and deployment |
| 56:39 | Verify the completed fixes |

## 原视频简介

A small refund feature passes through planning, implementation, local checks and pull request review before it is considered complete. Nnenna Ndukwe uses SignalPay, a deliberately narrow FastAPI payments application, to turn that sequence into quality gates for an AI coding agent. Participants choose a refund or capture retry workflow, identify the relevant payment rules and create both an implementation plan and a build execution plan. The point is to give the agent an explicit definition of the expected behavior, constraints, verification commands and evidence it must produce.

---

视频内容版权归原作者所有，字幕仅供学习交流。
