<!-- dubline-subs {"title": "Lead Architect Reveals His Rules for Coding Agents", "author": "Beyond Coding", "files": 3, "updated": "2026-10-24"} -->
# Lead Architect Reveals His Rules for Coding Agents

<img src="c6c587/2901e12d/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=mkN4uRZYPfs](https://www.youtube.com/watch?v=mkN4uRZYPfs) |
| 发布 | 2026-10-14 |
| 时长 | 1 小时 15 分 23 秒 |
| 语言 | 英语 |
| 原作者 | [Beyond Coding](https://www.youtube.com/@BeyondCoding)（@BeyondCoding，约 9 万订阅） |

## 中文信息

**标题**：主架构师实录：如何用高质量脚手架约束 AI Agent

**原标题译文**：首席架构师揭秘他的 Coding Agents 编码规则

在当前 AI 技术爆发的浪潮中，很多开发者正面临一个核心困境：虽然 AI 能快速生成代码片段，但在面对复杂的工程项目时，往往因为缺乏清晰的约束而导致代码难以维护、逻辑混乱甚至产生大量技术债。本期视频邀请到首席架构师 Carlos Kelkboom，深入剖析如何通过构建高质量的“脚手架”来规范 AI 的行为。他将分享一套完整的实战方法论，旨在帮助开发者将 AI 从一个简单的“对话式代码生成工具”，转型为能够真正参与复杂软件工程、产出高可靠性的生产力伙伴。

通过本期视频的学习，你将掌握以下核心知识点：
首先是关于“脚手架”的构建逻辑。由于 AI 在处理持续迭代任务时表现往往不如一次性生成，开发者必须在让 AI 介入前，手动建立清晰的目录结构、严谨的类型定义以及基于 Markdown 的指令规范，从而为 AI 划定明确的功能边界。
其次是高效的多智能体协作架构。视频详细讲解了主/子智能体分工的策略：主智能体专注于与用户沟通并澄清意图，只有在确定性极高的情况下，才派生出具备文件操作权限的子智能体去执行具体任务。
此外，你还将学习到如何利用 Git Worktrees 技术实现并行实验，让多个智能体同时生成不同版本的实现方案，再通过评估模型或人工筛选最优结果。
在上下文工程方面，视频介绍了如何利用“渐进式披露”和基于图谱的索引搜索技术，在不增加过多 Token 成本的前提下提供精准的上下文信息。
最后，课程强调了核心的工程原则：追求确定性编程，减少非确定性的逻辑复杂度；并严格执行“丢弃原则”，即一旦生成的代码不符合预期或难以理解，就立即丢弃并重新开始，而不是在错误的基础上反复修补。

本期内容特别适合软件工程师、技术负责人以及系统架构师观看。如果你正处于从简单的“氛围编程”向构建可维护、高确定性的生产级软件转型的过程中，或者你正在探索如何让 AI Agent 在实际的工程流中落地，那么这套关于约束、结构与协作的深度思考将为你提供极具价值的实战指导。看完本期视频后，你将能够建立起一套科学的开发工作流，学会通过预设规范来约束 AI 的产出，从而显著提升复杂项目的开发效率和代码质量。

章节
00:00:00 为什么 Carlos 会丢弃运行中的 AI 代码
00:00:53 为什么 Pull Request 和团队协作正在消失
00:03:50 永远无法完成项目的陷阱
00:06:06 逃离孤独的 AI 开发者泡沫
00:11:54 在调用 AI Agent 前如何构建代码脚手架
00:15:54 利用 AI Agent 学习新编程语言
00:21:14 为什么我们必须摒弃堆内存
00:28:32 在工程团队之间建立通用语言
00:31:31 氛围编程与深度软件工程的对立
00:40:12 代码是廉价的：用于并行 Agent 的 Git Worktrees
00:41:45 在 Agent 运行前需要构建多深度的脚手架
00:45:09 软件民主化、缺失的初级工程师与 AI 泡沫
00:53:33 为 AI Agent 上下文设计图谱支撑
00:58:18 为什么他的主智能体从不触碰文件
01:03:07 丢弃你无法理解的代码
01:06:25 重新思考代码审查与变异测试

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Lead Architect Reveals His Rules for Coding Agents - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](c6c587/43777cd8/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/K03NX/c6c587/43777cd8/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |
| Lead Architect Reveals His Rules for Coding Agents - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](c6c587/b728bc29/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/K03NX/c6c587/b728bc29/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Lead Architect Reveals His Rules for Coding Agents - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](c6c587/cf850757/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/K03NX/c6c587/cf850757/Lead%20Architect%20Reveals%20His%20Rules%20for%20Coding%20Agents%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，时间轴与原视频一致，可直接拖进播放器（PotPlayer、VLC、IINA 等）加载。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 00:00:00 | Why Carlos Throws Away Working AI Code |
| 00:00:53 | Why Pull Requests and Team Collaboration Are Dying |
| 00:03:50 | The Trap of Starting Projects You Never Finish |
| 00:06:06 | Escaping the Solo AI Developer Bubble |
| 00:11:54 | How to Scaffold Code Before Using AI Agents |
| 00:15:54 | Learning New Programming Languages With AI Agents |
| 00:21:14 | Why We Must Get Rid of the Heap |
| 00:28:32 | Building a Shared Language Across Engineering Teams |
| 00:31:31 | Vibe Coding vs Deep Software Engineering |
| 00:40:12 | Code Is Cheap: Git Worktrees for Parallel Agents |
| 00:41:45 | How Deep to Scaffold Before the Agent Runs |
| 00:45:09 | Democratizing Software, Missing Juniors, and the AI Bubble |
| 00:53:33 | Designing a Graph Harness for AI Agent Context |
| 00:58:18 | Why His Main Agent Never Touches Files |
| 01:03:07 | Throw Away Code You Don't Understand |
| 01:06:25 | Rethinking Code Reviews and Mutation Testing for AI |

## 原视频简介

Lead Architect Carlos Kelkboom shares his rules for coding agents and how great engineers architect software with AI. One of the great ones is: he throws away generated code the moment he doesn't understand it. He breaks down why coding agents fail at iterative changes, why his main agent never touches files, and how he scaffolds projects for one-shot execution.

---

视频内容版权归原作者所有，字幕仅供学习交流。
