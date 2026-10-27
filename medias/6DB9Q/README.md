<!-- dubline-subs {"title": "Matt Pocock's 3 New Skills Close the AI Coding Loop", "author": "Eric Tech", "files": 3, "updated": "2026-10-27"} -->
# Matt Pocock's 3 New Skills Close the AI Coding Loop

<img src="8fb9b6/a98fc5ce/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop.webp" alt="封面" width="480">

| | |
|---|---|
| 原视频 | [youtube.com/watch?v=1MNSJhCGMLY](https://www.youtube.com/watch?v=1MNSJhCGMLY) |
| 发布 | 2026-10-20 |
| 时长 | 11 分 18 秒 |
| 语言 | 英语 |
| 原作者 | [Eric Tech](https://www.youtube.com/@EricWTech)（@EricWTech，约 9 万订阅） |

## 中文信息

**标题**：【中配】利用3个新技能构建完整的 AI 软件开发闭环

**原标题译文**：Matt Pocock 的 3 个新技能完善了 AI 编程闭环

在当前人工智能辅助编程的浪潮中，许多开发者已经发现了一个核心痛点：虽然 AI 生成代码的速度极快，但人类去审查、验证并合并这些代码的速度却成为了整个研发流程中的严重瓶颈。本期视频将带你深入解析由 Matt Pocock 更新的三个核心 AI 开发技能——/implement-spec、/pr 和 /retro。这三个技能并非孤立存在，它们共同构建了一个包含并行处理、自动化审查和持续学习机制的完整 AI 软件开发闭环。通过这一套完整的逻辑体系，你可以从单纯地让 AI 写代码，进化到建立一套高效且能够自我优化的 AI 协作工作流。

在视频的前半部分，我们将首先回顾并夯实基础技能。为了确保 AI 在后续步骤中拥有极高的准确率，我们必须强调 Grooming 与 To-spec 的重要性。这意味着在进入实际开发阶段之前，必须收集充分的业务上下文并将其转化为正式的技术计划。随后，通过 To-ticket 技巧将宏大的计划拆解为具有原子性的任务单。这些任务单应当按照功能逻辑进行划分，而非简单的层级划分，其核心目的在于保护 AI 的上下文窗口，确保它在处理每一个具体任务时都能聚焦于当前目标，从而减少因信息过载导致的幻觉或错误。

随后进入核心环节，我们将深入探讨 /implement-spec 技能。这一技能的核心在于解决多任务并行处理的问题。通过构建清晰的任务树，我们可以识别出那些互不干扰、没有依赖关系的子任务，从而让多个 AI Agent 同时并行工作。这种模式能够显著提升整体的开发速度，打破单线程开发的限制。在具体的实现阶段，我们还会结合测试驱动开发（TDD）以及基于 Martin Fowler 著作中提到的 12 条重构原则来确保代码质量。

针对目前最棘手的“人工审核慢”问题，视频重点介绍了 /pr 技能。传统的 AI 生成结果往往缺乏足够的上下文信息给人类去判断，而 /pr 通过提供可视化图表、实测证据（如性能截图或测试通过情况）以及明确的合并风险评估，让开发者能够快速判断代码是否安全可放行。这极大地降低了人工审核的认知负担，让团队协作变得更加顺滑。

最后，为了让整个系统具备自我进化的能力，我们将学习 /retro 技能。这个环节的核心是建立反馈闭环：通过分析 Agent 在执行过程中犯错的原因，来反向优化 agents.md 文件中的上下文路径和硬性规则护栏。所谓的“护栏”，就是为 AI 建立固定的编码标准，例如明确禁止使用的 API 或错误的文件夹路径，从而防止 AI 重复犯入同样的错误。需要注意的是，/retro 并不是全自动运行的盲目过程，而是作为一种定期优化的工具，由人类开发者决定是否采纳系统提供的优化建议。

这期视频非常适合正在使用 Matt Pocock 系列技能进行 AI 应用开发的开发者；同时也非常适合那些正在构建 AI Agent 工作流、寻求提高 AI 代码生成效率和自动化流程的软件工程师。如果你正面临“AI 生成代码多但人工审核慢”这一具体痛点，或者希望建立一套更严谨、可扩展的 AI 协作体系，那么本期内容将为你提供实操性极强的解决方案。

章节
0:00 Matt 的新技能
0:22 回顾
2:32 Implement Spec 技能
3:39 AI PR 瓶颈
5:48 PR 技能
7:26 Retro 技能
9:52 完整工作流

原视频：Matt Pocock's 3 New Skills Close the AI Coding Loop
原作者：Eric Tech
发布日期：2026-10-20
视频链接：https://www.youtube.com/watch?v=1MNSJhCGMLY

## 文件下载

| 文件 | 说明 | 页面 | 直链 |
|---|---|---|---|
| Matt Pocock's 3 New Skills Close the AI Coding Loop - 简体中文字幕（翻译）.zh.srt | 译文字幕 | [查看 / 下载](310b13/00e97a03/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6DB9Q/310b13/00e97a03/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87%E5%AD%97%E5%B9%95%EF%BC%88%E7%BF%BB%E8%AF%91%EF%BC%89.zh.srt) |
| Matt Pocock's 3 New Skills Close the AI Coding Loop - 英语字幕（转写）.en.srt | 原文字幕（转写） | [查看 / 下载](310b13/063757ad/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6DB9Q/310b13/063757ad/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E8%8B%B1%E8%AF%AD%E5%AD%97%E5%B9%95%EF%BC%88%E8%BD%AC%E5%86%99%EF%BC%89.en.srt) |
| Matt Pocock's 3 New Skills Close the AI Coding Loop - 中英双语字幕.srt | 双语字幕 | [查看 / 下载](310b13/3139e654/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) | [直链](https://github.com/forestqqqq/dubline-subs/raw/main/medias/6DB9Q/310b13/3139e654/Matt%20Pocock%27s%203%20New%20Skills%20Close%20the%20AI%20Coding%20Loop%20-%20%E4%B8%AD%E8%8B%B1%E5%8F%8C%E8%AF%AD%E5%AD%97%E5%B9%95.srt) |

- 点「查看 / 下载」进入文件页面，再点右上角的下载按钮（↓）保存。
- 点「直链」会在浏览器里直接打开文本，右键「另存为」即可。
- 字幕是 UTF-8 编码，各文件的适用时间轴见上表说明，请匹配对应版本视频。

## 原视频章节

| 时间 | 章节 |
|---|---|
| 0:00 | Matt's New Skills |
| 0:22 | Recap |
| 2:32 | Implement Spec Skill |
| 3:39 | AI PR Bottleneck |
| 5:48 | PR Skill |
| 7:26 | Retro Skill |
| 9:52 | Full Workflow |

## 原视频简介

Matt Pocock skills v1.3 adds three new skills I find really helpful, and where each fits in the AI software development lifecycle. /implement-spec runs your tickets with parallel AI agents, /pr makes AI pull requests fast to review with proof and risk, and /retro learns from agent mistakes to improve your AGENTS.md and guardrails.

---

视频内容版权归原作者所有，字幕仅供学习交流。
